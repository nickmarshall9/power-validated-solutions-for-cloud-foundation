# Remove-vROPSAdapter

## Synopsis

Delete an adapters

## Syntax

```powershell
Remove-vROPSAdapter [-id] <String> [-ProgressAction <ActionPreference>] [<CommonParameters>]
```

## Description

The `Remove-vROPSAdapter` cmdlet deletes an adapters from VMware Aria Operations.

## Examples

### Example 1

```powershell
Remove-vROPSAdapter [-id] <String> 
```

This example deletes the adapter based on its ID.

## Parameters

### -id

The ID of the adapter to delete.

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
