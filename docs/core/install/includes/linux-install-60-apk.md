---
author: adegeo
ms.author: adegeo
ms.date: 11/22/2022
ms.topic: include
---

### Install the SDK

The .NET SDK allows you to develop apps with .NET. If you install the .NET SDK, you don't need to install the corresponding runtime. To install the .NET SDK, run the following command:

```bash
sudo apk add dotnet6-sdk
```

### Install the runtime

The ASP.NET Core Runtime allows you to run apps that were made with .NET that didn't provide the runtime. The following command install the ASP.NET Core Runtime, which is the most compatible runtime for .NET. In your terminal, run the following command:

```bash
sudo apk add aspnetcore6-runtime
```

As an alternative to the ASP.NET Core Runtime, you can install the .NET Runtime, which doesn't include ASP.NET Core support: replace `aspnetcore6-runtime` in the previous command with `dotnet6-runtime`:

```bash
sudo apk add dotnet6-runtime
```
