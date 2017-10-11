# <%= $PLASTER_PARAM_ModuleName %>

## Description

<%= $PLASTER_PARAM_ModuleDescription %>

Authored by <%= $PLASTER_PARAM_AuthorName %>

## Installing

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

### Removing <%= $PLASTER_PARAM_ModuleName %>

To remove <%= $PLASTER_PARAM_ModuleName %>:

``` PowerShell
PS> Uninstall-Module -Name <%= $PLASTER_PARAM_ModuleName %>
```

## Contributing to <%= $PLASTER_PARAM_ModuleName %>

Interested in contributing? Read how you can [Contribute](contributing.md) to <%= $PLASTER_PARAM_ModuleName %>

This project is maintains a [Code of Conduct](code-of-conduct.md) that establishes how the project is governed and how everyone involved is expected to behave. You can report unacceptable behavior to [<%= $PLASTER_PARAM_AuthorEmail %>](mailto:<%= $PLASTER_PARAM_AuthorEmail %>).

## Release History

A detailed release history is contained in the [Change Log](CHANGELOG.md).

## License

<%= $PLASTER_PARAM_ModuleName %> is provided under the [MIT license](LICENSE.md).