# Zooming and Panning Options with Blazor Charts

## Overview

This sample demonstrates how to configure zooming and panning interactions in a Syncfusion [Blazor Chart](https://www.syncfusion.com/blazor-components/blazor-charts). The implementation showcases how users can focus on selected chart regions, navigate across large datasets, and interact with chart data through zooming and panning operations. The sample also illustrates zoom toolbar customization, zoom mode configuration, and automatic interval calculation for improved readability while exploring chart data.

## Key Features

- Demonstrates zooming support in the Syncfusion Blazor `SfChart` component.
- Configures chart zoom behavior through chart zoom settings.
- Shows how to enable and customize zooming modes for chart interaction.
- Demonstrates toolbar options used for zoom-related actions.
- Includes panning functionality to navigate between zoomed chart regions.
- Demonstrates automatic interval calculation for zoomed chart areas.
- Uses sample chart data to visualize changes while zooming and panning.
- Illustrates interactive chart exploration without modifying the underlying data source.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the verified solution file `ZoomingAndPanning.sln`.
3. Restore all NuGet packages.
4. Set the appropriate startup project if Visual Studio does not automatically select it. 
5. Build the solution.
6. Run the application using `Ctrl+F5`.
7. The application will launch using the local URL configured in the project's launch settings.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the folder containing `ZoomingAndPanning.csproj`.

```bash
dotnet restore
dotnet run
```

4. Open the local URL displayed in the terminal after the application starts.
## Project Structure

- `Pages/Index.razor` — contains the Syncfusion Blazor `SfChart` implementation, chart series definitions, zooming configuration, panning behavior, toolbar settings, and user interaction settings that demonstrate zooming and panning functionality in the chart.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For feature documentation, see the Syncfusion Blazor Chart Zooming documentation: https://help.syncfusion.com/chart-sdk/blazor/charts/zooming

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
