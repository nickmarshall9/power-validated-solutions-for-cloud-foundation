# Get-NsxtGlobalSegmentID

## Synopsis

Return the events for an NSX Manager SegmentID.

## Syntax

```powershell
Get-NsxtGlobalSegmentID [-segmentName] <String> [-ProgressAction <ActionPreference>] [<CommonParameters>]
```

## Description

The `Get-NsxtGlobalSegmentID` cmdlet will return the events for a NSX Segment.

## Examples

### Example 1

```powershell
Get-NsxtGlobalSegmentID [-segmentName] <String> [-ProgressAction <ActionPreference>] [<CommonParameters>]
```

## Parameters

### -segmentName

The name of the NSX Global Segment.

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
