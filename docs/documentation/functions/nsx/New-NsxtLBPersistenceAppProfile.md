# New-NsxtLBPersistenceAppProfile

## Synopsis

Creates a Load Balancer Persistence Application Profile

## Syntax

```powershell
New-NsxtLBPersistenceAppProfile [-appProfileName] <String> [-json] <String>
 [-ProgressAction <ActionPreference>] [<CommonParameters>]
```

## Description

The `New-NsxtLBPersistenceAppProfile` cmdlet creates a Load Balancer Persistence Application Profile.

## Examples

### Example 1

```powershell
New-NsxtLBPersistenceAppProfile -appProfileName -json
```

This example creates a Load Balancer Persistence Application Profile.

## Parameters

### -appProfileName

The name of the Load Balancer Persistence Application Profile.

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

### -json

The JSON configuration for the Load Balancer Persistence Application Profile.

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
