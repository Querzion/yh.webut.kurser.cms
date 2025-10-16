# CMS Course 
## v42-v46 2025

### Focus on Umbraco Projects 
- Install Umbraco Templates
```bash
dotnet new install Umbraco.Templates
```
- Create Umbraco Project with DOTNET
```bash
dotnet new umbraco --name MyProjectFolderAndProject_Name
```
- Create Solution for Umbraco Project with DOTNET
```bash
dotnet new sln --name MyProjectFolderAndProject_Name_OR_SomethingElse
```
- Link the Solution to the *.csproj file
```bash
dotnet sln add MyProjectFolderAndProject_Name.csproj
```
## OR (if solution file is outside of the project folder)
```bash
dotnet sln add .\ProjectFolder\MyProjectFolderAndProject_Name.csproj
```
