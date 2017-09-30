## <%= $PLASTER_PARAM_ModuleName %>

## Description
<%= $PLASTER_PARAM_ModuleDesc %>

Authored by <%= $PLASTER_PARAM_FullName %>

## Installing <%= $PLASTER_PARAM_ModuleName %>
    
The easiest way to get <%= $PLASTER_PARAM_ModuleName %> is using the [PowerShell Gallery](https://powershellgallery.com/packages/<%= $PLASTER_PARAM_ModuleName %>/)!

### Inspecting the module
Best practice is that you inspect modules prior to installing them. You can do this by saving the module to a local path:

``` PowerShell
PS> Save-Module -Name <%= $PLASTER_PARAM_ModuleName %> -Path <path>
```

### Installing the module
Once you trust a module, you can install it using:

``` PowerShell
PS> Install-Module -Name <%= $PLASTER_PARAM_ModuleName %>
```

### Updating <%= $PLASTER_PARAM_ModuleName %>
Once installed from the PowerShell Gallery, you can update it using:

``` PowerShell
PS> Update-Module -Name <%= $PLASTER_PARAM_ModuleName %>
```
## License

[MIT](LICENSE.md)