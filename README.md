# Blazor DataGrid - RemoteSaveAdaptor with CRUD

This example shows that how to bind local data and perform CRUD at server by using RemoteSaveAdaptor.

## Overview

To perform all Grid Actions (like paging, filtering, sorting) in client-side except the CRUD operations, that should be interacted with server-side to persist data. It can be achieved in Grid by using **RemoteSaveAdaptor**.

Datasource must be set to json property and set **RemoteSaveAdaptor** to the adaptor property. CRUD operations can be mapped to server-side using insertUrl, updateUrl, removeUrl properties.

### Architecture Overview

This is a Blazor hosted application with a clear separation of concerns:

- **Client** (`/Client`): Blazor WebAssembly frontend with the DataGrid UI and client-side data operations
- **Server** (`/Server`): ASP.NET Core backend with API endpoints for CRUD operations  
- **Shared** (`/Shared`): Shared data models and types used by both client and server

## Features

- **Hybrid Data Operations** – Client-side efficiency meets server-side persistence
- **Real-time Grid Interactions** – Instant UI updates for user actions
- **Sample Data** – Pre-populated with order records for testing
- **Syncfusion Components** – Industry-standard DataGrid with comprehensive features

## Prerequisites

* [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
* [Visual Studio Code](https://code.visualstudio.com/)
* [.NET SDK 7.0](https://dotnet.microsoft.com/download/dotnet/7.0) or later

## Getting Started

### Clone the repository

```bash
git clone https://github.com/SyncfusionExamples/Blazor-DataGrid-Remote-SaveAdaptor-CRUD.git
cd Blazor-DataGrid-Remote-SaveAdaptor-CRUD
```

### Run with Visual Studio

1. Open the solution file using Visual Studio 2022 or later.
2. Restore the NuGet packages by rebuilding the solution.
3. Build the project to ensure there are no compilation errors.
4. Run the project.

## References

- [Remote Data Binding Guide](https://blazor.syncfusion.com/documentation/datagrid/data-binding/remote-data)
- [Live Example](https://blazor.syncfusion.com/demos/datagrid/remote-data?theme=bootstrap5)
- [Blazor Hosting Models](https://learn.microsoft.com/aspnet/core/blazor/hosting-models)