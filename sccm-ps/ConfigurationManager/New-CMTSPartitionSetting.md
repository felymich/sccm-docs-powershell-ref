<<<<<<< HEAD
---
title: New-CMTSPartitionSetting
titleSuffix: Configuration Manager
description: Creates a t s partition setting.
ms.date: 05/07/2019
ms.prod: configuration-manager
ms.technology: configmgr-other
ms.topic: conceptual
author: aczechowski
ms.author: aaroncz
manager: dougeby
=======
﻿---
external help file: AdminUI.PS.Osd.dll-Help.xml
online version: 
schema: 2.0.0
>>>>>>> master
---

# New-CMTSPartitionSetting

# SYNOPSIS

Creates a t s partition setting.

## SYNTAX

### PrimaryPartition (Default)
```
New-CMTSPartitionSetting [-PartitionPrimary] [-Name <String>] [-Size <Int32>] [-SizeUnit <SizeUnitType>]
 [-EnableDriveLetterAssignment <Boolean>] [-IsBootPartition <Boolean>] [-EnableQuickFormat <Boolean>]
 [-PartitionFileSystem <FileSystemType>] [-Variable <String>] [-DisableWildcardHandling]
 [-ForceWildcardHandling] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### EfiPartition
```
New-CMTSPartitionSetting [-PartitionEfi] [-Name <String>] [-Size <Int32>] [-SizeUnit <SizeUnitType>]
 [-DisableWildcardHandling] [-ForceWildcardHandling] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### ExtendedPartition
```
New-CMTSPartitionSetting [-PartitionExtended] [-Name <String>] [-Size <Int32>] [-SizeUnit <SizeUnitType>]
 [-DisableWildcardHandling] [-ForceWildcardHandling] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### HiddenPartition
```
New-CMTSPartitionSetting [-PartitionHidden] [-Name <String>] [-Size <Int32>] [-SizeUnit <SizeUnitType>]
 [-DisableWildcardHandling] [-ForceWildcardHandling] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### LogicalPartition
```
New-CMTSPartitionSetting [-PartitionLogical] [-Name <String>] [-Size <Int32>] [-SizeUnit <SizeUnitType>]
 [-DisableWildcardHandling] [-ForceWildcardHandling] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### MsrPartition
```
New-CMTSPartitionSetting [-PartitionMsr] [-Name <String>] [-Size <Int32>] [-SizeUnit <SizeUnitType>]
 [-DisableWildcardHandling] [-ForceWildcardHandling] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### RecoveryPartition
```
New-CMTSPartitionSetting [-PartitionRecovery] [-Name <String>] [-Size <Int32>] [-SizeUnit <SizeUnitType>]
 [-DisableWildcardHandling] [-ForceWildcardHandling] [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
 

## EXAMPLES

> [!NOTE]
> Configuration Manager CmdLets must be run from the Configuration Manager site drive. For more information, see the [getting started documentation](https://docs.microsoft.com/powershell/sccm/overview).


### Example 1
```
PS XYZ:\>  
```

 

## PARAMETERS

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DisableWildcardHandling
DisableWildcardHandling treats wildcard characters as literal character values. Cannot be combined with **ForceWildcardHandling**.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -EnableDriveLetterAssignment
 

```yaml
Type: Boolean
Parameter Sets: PrimaryPartition
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -EnableQuickFormat
 

```yaml
Type: Boolean
Parameter Sets: PrimaryPartition
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ForceWildcardHandling
ForceWildcardHandling processes wildcard characters and may lead to unexpected behavior (not recommended). Cannot be combined with **DisableWildcardHandling**.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsBootPartition
 

```yaml
Type: Boolean
Parameter Sets: PrimaryPartition
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Name
 

```yaml
Type: String
Parameter Sets: (All)
Aliases: PartitionName, VolumeName

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PartitionEfi
 

```yaml
Type: SwitchParameter
Parameter Sets: EfiPartition
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PartitionExtended
 

```yaml
Type: SwitchParameter
Parameter Sets: ExtendedPartition
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PartitionFileSystem
 

```yaml
Type: FileSystemType
Parameter Sets: PrimaryPartition
Aliases: 
Accepted values: Ntfs, Fat32

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PartitionHidden
 

```yaml
Type: SwitchParameter
Parameter Sets: HiddenPartition
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PartitionLogical
 

```yaml
Type: SwitchParameter
Parameter Sets: LogicalPartition
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PartitionMsr
 

```yaml
Type: SwitchParameter
Parameter Sets: MsrPartition
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PartitionPrimary
 

```yaml
Type: SwitchParameter
Parameter Sets: PrimaryPartition
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PartitionRecovery
 

```yaml
Type: SwitchParameter
Parameter Sets: RecoveryPartition
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Size
 

```yaml
Type: Int32
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SizeUnit
 

```yaml
Type: SizeUnitType
Parameter Sets: (All)
Aliases: 
Accepted values: MB, GB, Percent

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Variable
 

```yaml
Type: String
Parameter Sets: PrimaryPartition
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### None

## OUTPUTS

### IResultObject#SMS_TaskSequence_PartitionSettings

## NOTES

## RELATED LINKS

