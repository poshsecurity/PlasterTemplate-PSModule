# Using this Plaster Template

The contents of this GitHub repostiory form a PowerShell [Plaster](https://github.com/PowerShell/Plaster/) template.

This template was created by [Kieran Jacobsen](https://github.com/poshsecurity), based upon the work of [Rob Sewell](https://github.com/sqldbawithabeard).

The goal of this template is to provide a strong structure for PowerShell module development and to encourage community participation via GitHub.

## Installing Plaster

You can install Plaster from the [PowerShell Gallery](https://powershellgallery.com/packages/Plaster/)

``` PowerShell
PS> Install-Module -Name Plaster
```

## Clone the template

Using Git you can clone the template locally.

``` PowerShell
PS> git clone https://github.com/poshsecurity/PlasterTemplate
```

## Creating a new module

Now that you have template locally, you can run ```Invoke-Plaster``` to create a new module based upon the template.

I typically follow this workflow:

1. Create a public (or private) on GitHub
2. Clone the repository locally
    ``` PowerShell
    PS> git clone <Path to repository>
    ```
3. Create a hash table containing the required parameters, and then call ```Invoke-Plaster```
    ``` PowerShell
    PS> $PlasterParameters = @{
        TemplatePath      = "<path to the Plaster Template above>"
        DestinationPath   = "<path to the new repository you cloned>"
        AuthorName        = "Cool PowerShell Developer"
        AuthorEmail       = "Developer@PowerShellis.Cool"
        ModuleName        = "MyNewModule"
        ModuleDescription = "This is my awesome PowerShell Module!"
    }

    PS> Invoke-Plaster @PlasterParameters
    ```
4. Plaster should then execute, creating the required files and folders.
5. When you are ready you can push everything up to GitHub.
