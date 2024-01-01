# Blazor DataGrid - RemoteSaveAdaptor with CRUD

This example shows that how to bind local data and perform CRUD at server by using RemoteSaveAdaptor.

You may need to perform all Grid Actions (like paging, filtering, sorting) in client-side except the CRUD operations, that should be interacted with server-side to persist data. It can be achieved in Grid by using **RemoteSaveAdaptor**.

Datasource must be set to **json** property and set **RemoteSaveAdaptor** to the **adaptor** property. CRUD operations can be mapped to server-side using **insertUrl**, **updateUrl**, **removeUrl** properties.

## Prerequisites

* Visual Studio 2022

## How to run the project

* Checkout this project to a location in your disk.
* Open the solution file using the Visual Studio 2022.
* Restore the NuGet packages by rebuilding the solution.
* Run the project.