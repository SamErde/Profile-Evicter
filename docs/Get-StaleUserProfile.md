---
external help file: TheCleaners-help.xml
Module Name: TheCleaners
online version:
schema: 2.0.0
---

# Get-StaleUserProfile

## SYNOPSIS
A script to find old, unused user profiles in Windows.

## SYNTAX

```
Get-StaleUserProfile [-ShowSummary] [<CommonParameters>]
```

## DESCRIPTION
THIS IS AN EARLY POC SCRIPT THAT NEEDS TO BE TESTED FOR PROPER EXCLUSIONS.
This script finds old, unused profiles in Windows and helps you remove them.
It should exclude special accounts and system profiles.

## EXAMPLES

### EXAMPLE 1
```
$StaleUserProfile = Get-StaleUserProfile -ShowSummary
```

Gets stale user profiles into the StaleUserProfiles variable while also showing a summary.

## PARAMETERS

### -ShowSummary
Show a summary of the stale profiles found.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutBuffer, -OutVariable, -PipelineVariable, -Verbose, -WarningAction, -WarningVariable, and -ProgressAction. 
For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES
Author: Sam Erde
        https://twitter.com/SamErde
        https://github.com/SamErde

Partially inspired by http://woshub.com/delete-old-user-profiles-gpo-powershell/

## RELATED LINKS