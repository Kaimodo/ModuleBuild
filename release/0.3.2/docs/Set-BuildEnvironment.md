---
external help file: ModuleBuild-help.xml
Module Name: ModuleBuild
online version: https://github.com/zloeber/ModuleBuild
schema: 2.0.0
---

# Set-BuildEnvironment

## SYNOPSIS
Sets a stored setting in a buildenvironment.json file.

## SYNTAX

```
Set-BuildEnvironment [[-Path] <String>] [-AdditionalModulePaths <Object[]>] [-BaseReleaseFolder <String>]
 [-BaseSourceFolder <String>] [-BuildReportsFolder <String>] [-BuildToolFolder <String>] [-Encoding <String>]
 [-ExcludeRules <Object[]>] [-FirstRun <Boolean>] [-Force <Boolean>] [-ForceInstallModule <Boolean>]
 [-FunctionTemplates <String>] [-ModuleAuthor <String>] [-ModuleCopyright <String>]
 [-ModuleDescription <String>] [-ModuleLicenseURI <String>] [-ModuleTags <Object[]>] [-ModuleToBuild <String>]
 [-ModuleVersion <String>] [-ModuleWebsite <String>] [<CommonParameters>]
```

## DESCRIPTION
Sets the stored setting in a buildenvironment.json file.

## EXAMPLES

### BEISPIEL 1
```
Set-BuildEnvironment -OptionSensitiveTerms @('myapikey','myname','password')
```

## PARAMETERS

### -Path
Specifies the path to a buildenvironment.json file.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 1
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -AdditionalModulePaths
Update the setting for AdditionalModulePaths

```yaml
Type: Object[]
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -BaseReleaseFolder
Update the setting for BaseReleaseFolder

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -BaseSourceFolder
Update the setting for BaseSourceFolder

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -BuildReportsFolder
Update the setting for BuildReportsFolder

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -BuildToolFolder
Update the setting for BuildToolFolder

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Encoding
Update the setting for Encoding

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ExcludeRules
Update the setting for ExcludeRules

```yaml
Type: Object[]
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -FirstRun
Update the setting for FirstRun

```yaml
Type: Boolean
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Force
Update the setting for Force

```yaml
Type: Boolean
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ForceInstallModule
Update the setting for ForceInstallModule

```yaml
Type: Boolean
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -FunctionTemplates
Update the setting for FunctionTemplates

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ModuleAuthor
Update the setting for ModuleAuthor

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ModuleCopyright
Update the setting for ModuleCopyright

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ModuleDescription
Update the setting for ModuleDescription

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ModuleLicenseURI
Update the setting for ModuleLicenseURI

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ModuleTags
Update the setting for ModuleTags

```yaml
Type: Object[]
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ModuleToBuild
Update the setting for ModuleToBuild

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ModuleVersion
Update the setting for ModuleVersion

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ModuleWebsite
Update the setting for ModuleWebsite

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable.
For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[https://github.com/zloeber/ModuleBuild](https://github.com/zloeber/ModuleBuild)

