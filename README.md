# Vanara.Compatibility
Compatibility packs for .NET exposing Windows specific functionality. Since there are numerous projects doing this for .NET Standard and .NET Core, these libraries focus on bringing parity to older .NET versions still in use (2.0, 3.5 and 4.0). In cases where there isn't a well-known or Microsoft sponsored compatibility library for Core or Standard, those will be included too.

## Installation
Each project's assemblies are available via NuGet. Find a link to the NuGet page under each project's heading.

## Vanara.Compatibility.EventLog
[![NuGet](https://img.shields.io/nuget/v/Vanara.Compatibility.EventLog.svg?style=flat-square)](https://www.nuget.org/packages/Vanara.Compatibility.EventLog)  [![Downloads](https://img.shields.io/nuget/dt/Vanara.Compatibility.EventLog.svg?style=flat-square)](https://www.nuget.org/packages/Vanara.Compatibility.EventLog/)

Provides .NET 2.0 and .NET Standard 2.0 classes for the System.Diagnostics.Eventing.Reader namespace related to reading events from the Windows Event Log. These classes were introduced into the standard library in .NET 3.5.
