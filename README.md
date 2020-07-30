---
page_type: sample
languages:
- csharp
products:
- azure
description: "This repository contains the sample discussed in Create a WPF app to detect and frame faces in an image."
urlFragment: Cognitive-Face-CSharp-sample
---

# Detect and frame faces in an image on Windows

This repository contains the sample discussed in [Create a WPF app to detect and frame faces in an image](https://docs.microsoft.com/en-us/azure/cognitive-services/face/tutorials/faceapiincsharptutorial). The sample uses the Windows client library for the Cognitive Services Face service.

## Features

This project provides the following features:

* Detects faces in an image.
* Draws a rectangle around each face.
* Displays face attributes in the status bar when the mouse hovers over each face rectangle.

![GettingStartCSharpScreenshot](https://docs.microsoft.com/en-us/azure/cognitive-services/face/images/getting-started-cs-detected.png)

## Getting Started

### Prerequisites

- You need a subscription key to run the sample. [Create a new Azure account, and try Cognitive Services for free.](https://azure.microsoft.com/free/cognitive-services/)
- Any edition of [Visual Studio 2015 or 2017](https://www.visualstudio.com/downloads/). For Visual Studio 2017, the .NET Desktop application development workload is required.
- The [Microsoft.Azure.CognitiveServices.Vision.Face 2.2.0-preview](https://www.nuget.org/packages/Microsoft.Azure.CognitiveServices.Vision.Face/2.2.0-preview) client library NuGet package. Download not necessary.

### Quickstart

1. Clone or download the repository.
1. Open the *FaceTutorialCS* folder in the repository.
1. Double-click the *FaceTutorialCS.sln* file, which opens in Visual Studio.
1. Expand *MainWindow.xaml*, then open *MainWindow.xaml.cs*.
1. Replace `<SubscriptionKey>` with your valid subscription key.
1. Replace or verify the Azure region (`faceEndpoint`) associated with your key.
1. Build the project, which installs the Face service NuGet package.
1. Run the program.
1. Browse and select an image containing faces.
1. Wait a few seconds for the Face service to respond.
1. Move your mouse over a face rectangle to see a description of that face on the status bar.

For more information, see [Getting Started with Face API in C# Tutorial](https://docs.microsoft.com/en-us/azure/cognitive-services/face/tutorials/faceapiincsharptutorial).

## Resources

- [Face service documentation](https://docs.microsoft.com/en-us/azure/cognitive-services/face/)
- [Face API](https://docs.microsoft.com/en-us/azure/cognitive-services/face/apireference)
