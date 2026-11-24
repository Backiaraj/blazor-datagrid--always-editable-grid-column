# Blazor DataGrid — Always Editable Grid Column

A sample Blazor application demonstrating how to render the [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) component with columns in an always-editable state, allowing users to edit data inline without entering a dedicated edit mode.

## Overview

This repository demonstrates how to configure the Blazor DataGrid for always-editable columns. Instead of requiring users to click an edit button or double-click a cell to enter edit mode, all specified columns remain in an editable state by default. This approach is ideal for data entry-heavy applications where users frequently update records.

The sample uses custom column templates with input components (like `SfTextBox`) to provide a seamless editing experience with built-in data binding and key event handling.

## Features

- **Always-Editable Columns** - Configure grid columns to remain in edit mode without requiring activation, enabling seamless inline data updates
- **Custom Column Templates** - Use Razor templates to render interactive controls like TextBox, DropDown, and DatePicker directly in cells
- **Inline Data Binding** - Two-way binding with `@bind-Value` ensures changes are immediately reflected in the component state
- **Pagination Support** - Handle large datasets efficiently with built-in pagination controls

## Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
* [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/SyncfusionExamples/blazor-datagrid--always-editable-grid-column.git
cd blazor-datagrid--always-editable-grid-column
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

**Documentation**: https://help.syncfusion.com/grid-sdk/blazor/data-grid/in-line-editing

**Online example**: https://blazor.syncfusion.com/demos/datagrid/inline-editing?theme=fluent2