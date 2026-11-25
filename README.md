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
* [Visual Studio 2026](https://visualstudio.microsoft.com/downloads/) or [Visual Studio Code](https://code.visualstudio.com/)

## Run with Visual Studio

**Visual Studio 2026**:

* Checkout this project to a location in your disk.
* Open the project (`EditableGridColumn.csproj`) file.
* Restore the NuGet packages.
* Run the project.

**Visual Studio Code**:

* Checkout this project to a location in your disk.
* Open the repository folder in Visual Studio Code.
* Open the integrated terminal.
* Navigate to the repository root.

```bash
cd blazor-datagrid--always-editable-grid-column
dotnet restore
dotnet run
```

Open the URL displayed in the terminal after the application starts.

## References

**Documentation**: https://help.syncfusion.com/grid-sdk/blazor/data-grid/in-line-editing

**Online example**: https://blazor.syncfusion.com/demos/datagrid/inline-editing?theme=fluent2