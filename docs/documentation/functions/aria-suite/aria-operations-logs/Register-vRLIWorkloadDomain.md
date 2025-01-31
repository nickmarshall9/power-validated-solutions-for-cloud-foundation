# Register-vRLIWorkloadDomain

## Synopsis

Connect a Workload Domain to VMware Aria Operations for Logs

## Syntax

```powershell
Register-vRLIWorkloadDomain [-server] <String> [-user] <String> [-pass] <String> [-domain] <String>
 [-status] <String> [-ProgressAction <ActionPreference>] [<CommonParameters>]
```

## Description

The `Register-vRLIWorkloadDomain` cmdlet connects a Workload Domain to VMware Aria Operations for Logs.
The cmdlet connects to SDDC Manager using the -server, -user, and -password values.

- Validates that network connectivity and authentication is possible to SDDC Manager
- Validates that VMware Aria Operations for Logs has been deployed in VCF-aware mode and retrieves its details
- Validates that network connectivity and authentication is possible to VMware Aria Operations for Logs
- Obtains the Workload Domain details from the SDDC Manager inventory
- Connects the Workload Domain with VMware Aria Operations for Logs if not already configured.

## Examples

### Example 1

```powershell
Register-vRLIWorkloadDomain -server sfo-vcf01.sfo.rainpole.io -user administrator@vsphere.local -pass VMw@re1! -domain sfo-w01 -status ENABLED
```

This example ENABLES the Workload Domain in VMware Aria Operations for Logs

### Example 2

```powershell
Register-vRLIWorkloadDomain -server sfo-vcf01.sfo.rainpole.io -user administrator@vsphere.local -pass VMw@re1! -domain sfo-w01 -status DISABLED
```

This example DISABLES the Workload Domain in VMware Aria Operations for Logs.

## Parameters

### -server

The fully qualified domain name of the SDDC Manager.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -user

The SDDC Manager administrator username.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: 2
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -pass

The SDDC Manager administrator password.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: 3
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -domain

The name of the workload domain to run against.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: 4
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -status

The status of the Workload Domain in VMware Aria Operations for Logs "ENABLED" "DISABLED".

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: 5
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ProgressAction

Progress Action

```yaml
Type: ActionPreference
Parameter Sets: (All)
Aliases: proga

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### Common Parameters

This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).
