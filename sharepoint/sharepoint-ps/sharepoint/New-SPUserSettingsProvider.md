---
applicable: SharePoint Server 2013, SharePoint Server 2016
schema: 2.0.0
---

# New-SPUserSettingsProvider

## SYNOPSIS
**Below Content Applies To:**SharePoint Server 2013

Applies to:

**Below Content Applies To:**SharePoint Server 2016

Adds a new User Settings Provider.



## SYNTAX

```
New-SPUserSettingsProvider -AssemblyName <String> -DisplayName <String> -Type <String>
 [-AssignmentCollection <SPAssignmentCollection>] [<CommonParameters>]
```

## DESCRIPTION
Use the New-SPUserSettingsProvider cmdlet to add a new User Settings Provider to the farm.

For permissions and the most current information about Windows PowerShell for SharePoint Products, see the online documentation at http://go.microsoft.com/fwlink/p/?LinkId=251831 (http://go.microsoft.com/fwlink/p/?LinkId=251831).

## EXAMPLES

### -----------EXAMPLE------- (SharePoint Server 2013)
```
C:\PS>New-SPUserSettingsProvider -DisplayName "My User Settings Provider" -AssemblyName MyProvider.dll -Type MyProvider
```

This example adds a user setting provider with a display name of "My User Settings Provider" which uses the MyProvider.dll file.

### -----------EXAMPLE------- (SharePoint Server 2016)
```
C:\PS>New-SPUserSettingsProvider -DisplayName "My User Settings Provider" -AssemblyName MyProvider.dll -Type MyProvider
```

This example adds a user setting provider with a display name of "My User Settings Provider" which uses the MyProvider.dll file.

## PARAMETERS

### -AssemblyName
Specifies the assembly name for the provider.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 
Applicable: SharePoint Server 2013, SharePoint Server 2016

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DisplayName
Specifies the display name to use for this provider.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 
Applicable: SharePoint Server 2013, SharePoint Server 2016

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Type
Specifies the type name to use for this provider.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 
Applicable: SharePoint Server 2013, SharePoint Server 2016

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AssignmentCollection
Manages objects for the purpose of proper disposal.
Use of objects, such as SPWeb or SPSite, can use large amounts of memory and use of these objects in Windows PowerShell scripts requires proper memory management.
Using the SPAssignment object, you can assign objects to a variable and dispose of the objects after they are needed to free up memory.
When SPWeb, SPSite, or SPSiteAdministration objects are used, the objects are automatically disposed of if an assignment collection or the Global parameter is not used.

When the Global parameter is used, all objects are contained in the global store.
If objects are not immediately used, or disposed of by using the Stop-SPAssignment command, an out-of-memory scenario can occur.

```yaml
Type: SPAssignmentCollection
Parameter Sets: (All)
Aliases: 
Applicable: SharePoint Server 2013, SharePoint Server 2016

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Get-SPUserSettingsProvider]()

[Remove-SPUserSettingsProvider]()

[Get-SPUserSettingsProviderManager]()
