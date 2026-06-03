# Blazor Server DataGrid - ComboBox Editing with Foreign Key Column

A comprehensive example demonstrating how to implement inline editing with ComboBox components for foreign key columns in [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) using Blazor Server rendering.

## Overview

This project showcases best practices for handling related data in DataGrid columns. When editing records that reference other entities (foreign keys), users need an intuitive way to select from available options. This sample demonstrates how to replace the default dropdown with a ComboBox control for improved user experience and flexibility.

## Key Features

- **Foreign Key Column Editing**: Edit related data through intuitive ComboBox controls
- **DataGrid Capabilities**: Full CRUD operations (Add, Edit, Delete) with toolbar support
- **Blazor Server Rendering**: Seamless server-side interactivity without page refreshes
- **Sample Data**: Pre-configured with employee and order data for immediate testing

## Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
* [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the repository

```bash
git clone https://github.com/SyncfusionExamples/EJ2-DataGrid-BlazorServer-Editing-ComboBox-ForeignKeyColumn.git
cd EJ2-DataGrid-BlazorServer-Editing-ComboBox-ForeignKeyColumn
```

### Run with Visual Studio

1. Open the solution file using Visual Studio 2022 or later.
2. Restore the NuGet packages by rebuilding the solution.
3. Build the project to ensure there are no compilation errors.
4. Run the project.

### Run with .NET CLI

```bash
# Restore dependencies
dotnet restore

# Run the project
dotnet run
```

## References

**Documentation**: https://blazor.syncfusion.com/documentation/datagrid/foreignkey-column

**Online example**: https://blazor.syncfusion.com/demos/datagrid/foreign-key-column?theme=bootstrap5