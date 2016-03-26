# Get-vRAConsumerEntitledCatalogItem

## SYNOPSIS
    
Get the a catalog item that the user is entitled to see

## SYNTAX


## DESCRIPTION

Consumer API for entitled catalog items exposed for users. Consumer Entitled CatalogItem(s) are basically catalog items:
- In an active state.
- The current user has the right to consume.
- The current user is entitled to consume.
- Associated to a service.

## PARAMETERS


### Id


* Required: true
* Position: named
* Default value: 
* Accept pipeline input: false

### Name

The name of the catalog item

* Required: true
* Position: named
* Default value: 
* Accept pipeline input: false

### Limit

The number of entries returned per page from the API. This has a default value of 100.

* Required: false
* Position: named
* Default value: 100
* Accept pipeline input: false

## INPUTS

System.String

## OUTPUTS

System.Management.Automation.PSObject

## EXAMPLES
```
-------------------------- EXAMPLE 1 --------------------------

C:\PS>Get-vRAConsumerEntitledCatalogItem







-------------------------- EXAMPLE 2 --------------------------

C:\PS>Get-vRAConsumerEntitledCatalogItem -Limit 9999







-------------------------- EXAMPLE 3 --------------------------

C:\PS>Get-vRAConsumerEntitledCatalogItem -Id dab4e578-57c5-4a30-b3b7-2a5cefa52e9e







-------------------------- EXAMPLE 4 --------------------------

C:\PS>Get-vRAConsumerEntitledCatalogItem -Name Centos_Template
```
