# **PSMicrosoftUpdateCatalog**

PowerShell module for querying the Microsoft Update Catalog and retrieving
update metadata, package details, and direct download URLs.

## **Features**
- Search Microsoft Update Catalog by KB/article/update title
- Retrieve package metadata
- Extract direct download links
- Support scripting/automation workflows
- Structured PowerShell object output

## **Installation**
```powershell
Install-Module -Name PSMicrosoftUpdateCatalog
```

## **Examples**
```powershell
Get-CatalogItem -Search "KB5030219"
```
```powershell
Get-CatalogItem -Search "Windows 11 cumulative"
```
```powershell
Get-CatalogItem -UpdateId <guid> -Architecture x64 -ServiceStack
```
