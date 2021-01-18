# PnP Framework

**PnP Framework** is a .NET Standard 2.0 / .NET 5.0 library targeting Microsoft 365 containing the PnP Provisioning engine and a ton of other useful extensions. This library is the cross platform successor of the [PnP-Sites-Core](https://github.com/PnP/PnP-Sites-Core) library. The original [PnP-Sites-Core](https://github.com/PnP/PnP-Sites-Core) library only works on Windows (due to the dependency on .Net Framework) and supports SharePoint on-premises and SharePoint Online, while this library will work cross platform but only supports SharePoint Online. Going forward we'll only be **actively maintaining PnP Framework**, the [PnP-Sites-Core](https://github.com/PnP/PnP-Sites-Core) library is retired and archived.

Next to PnP Framework that will be replacing [PnP-Sites-Core](https://github.com/PnP/PnP-Sites-Core) we're also building a brand new [PnP Core SDK](https://github.com/pnp/pnpcore) that targets modern .NET development and which will work everywhere where .NET will run. This library is the long term evolution of PnP Framework, we'll enable a phased transition from PnP Framework to [PnP Core SDK](https://github.com/pnp/pnpcore) without impacting PnP Framework users.

## Getting started

Pull down the latest version of PnP Framework here: [![PnP.Framework Nuget package](https://img.shields.io/nuget/vpre/PnP.Framework.svg)](https://www.nuget.org/packages/PnP.Framework/).

## PnP .NET roadmap status

We've shipped version 1.0.0 of PnP Framework (GA 🎉) and beta 2 of the [PnP Core SDK](https://github.com/pnp/pnpcore).

![PnP dotnet roadmap](PnP%20dotnet%20Roadmap%20-%20January%20status.png)

## I've found a bug, where do I need to log an issue or create a PR

Issues and PR's need to be created in the PnP Framework repo, the PnP Sites Core repo has been archived.

## Building and contributing

To build PnP Framework you need the following minimal components installed:

- [Visual Studio 2019 version 16.8+](https://visualstudio.microsoft.com/vs/)
- [.NET SDK version 5.0](https://dotnet.microsoft.com/download/dotnet/5.0)

Contributions should be made against the **dev** branch of the repository.

**Community rocks, sharing is caring!**

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
