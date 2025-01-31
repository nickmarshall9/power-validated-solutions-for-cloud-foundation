# Get-NsxtVidmUser

## Synopsis

Gets Identity Manager users

## Syntax

```powershell
Get-NsxtVidmUser [-searchString] <String> [-ProgressAction <ActionPreference>] [<CommonParameters>]
```

## Description

The `Get-NsxtVidmUser` cmdlet gets all Identity Manager users from NSX Manager.

## Examples

### Example 1

```powershell
Get-NsxtVidmUser -searchString svc
```

This example gets all Identity Manager users starting with 'svc' from NSX Manager.

## Parameters

### -searchString

The search string.

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
