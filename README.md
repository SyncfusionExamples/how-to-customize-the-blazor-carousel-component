# How to Customize the Blazor Carousel Component

## Overview

This sample demonstrates how to customize the appearance and behavior of the Syncfusion [Blazor Carousel](https://www.syncfusion.com/blazor-components/blazor-carousel) component in a hosted Blazor WebAssembly application. The implementation focuses on customizing carousel indicators, previous and next navigators, and playback controls through template-based configuration. It also demonstrates how to hide default navigation elements and replace them with tailored user interface elements that better match application design requirements.

The sample is useful for developers who need complete control over Carousel navigation experiences for scenarios such as product galleries, promotional banners, onboarding screens, featured content rotators, and interactive dashboards. The project shows how Syncfusion Carousel templates can be used to create a more engaging and branded user experience while retaining built-in Carousel functionality. 

## Key Features

- Uses the Syncfusion `SfCarousel` component to display a rotating image gallery with four destination images.
- Configures automatic slide transitions using the `AutoPlay` property with a custom play/pause toggle implementation.
- Sets a 2-second slide interval using the `Interval="2000"` property.
- Applies the `CarouselAnimationEffect.Fade` animation effect for smooth slide transitions.
- Disables continuous navigation by setting `Loop="false"`.
- Hides the default indicator UI using `ShowIndicators="false"` and replaces it with a fully customized `IndicatorsTemplate`.
- Implements image-based thumbnail indicators through the `IndicatorsTemplate`, allowing users to navigate using preview images.
- Uses `PreviousButtonTemplate` and `NextButtonTemplate` to replace the default navigator buttons with custom `SfButton` components and SVG icons.
- Configures navigator visibility using `ButtonsVisibility="CarouselButtonVisibility.VisibleOnHover"`.
- Enables the built-in play button functionality using `ShowPlayButton="true"` and overrides the default UI through `PlayButtonTemplate`.
- Implements custom play and pause states using SVG icons and a toggle button.
- Uses the `IsSlidePlay` boolean property to dynamically control Carousel autoplay behavior.
- Binds indicator images through the `IndicatorsImageNameList` collection.
- Customizes active indicator appearance using CSS, including borders, spacing, sizing, and highlighting.
- Applies custom CSS styling for navigation buttons, play/pause controls, thumbnail indicators, and image presentation.
- Demonstrates template-based customization of Carousel navigation and playback controls without modifying the component's core functionality.

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)
- [.NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet) compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download the repository.
2. Open the `CustomizingCarousel.sln` solution file.
3. Restore all NuGet packages.
4. Build the solution.
5. Run the application using `Ctrl+F5`.
6. Open the local application URL displayed by Visual Studio after successful startup.

**Visual Studio Code**

1. Clone or download the repository.
2. Open the repository folder in Visual Studio Code.
3. Navigate to the repository root directory.

```bash
dotnet restore
dotnet run
```

4. Open the application URL displayed in the terminal after the application starts successfully.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Relevant documentation: https://blazor.syncfusion.com/documentation/carousel/navigators-and-indicators
- Online demo: https://blazor.syncfusion.com/demos/carousel/templates

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.