# MinVer example

Example for how to build DotNet packages with Github Actions using MinVer and publish to nuget.org

[![OnPublishedRelease](https://github.com/Kurpanik/MinVerExample/actions/workflows/OnPublishedRelease.yml/badge.svg)](https://github.com/Kurpanik/MinVerExample/actions/workflows/OnPublishedRelease.yml) [![OnPush develop](https://github.com/Kurpanik/MinVerExample/actions/workflows/OnPushDevelop.yml/badge.svg)](https://github.com/Kurpanik/MinVerExample/actions/workflows/OnPushDevelop.yml)  
[![NuGet Status](https://img.shields.io/nuget/v/MinVer.Example.svg)](https://www.nuget.org/packages/MinVer.Example/) [![MinVer.Example on fuget.org](https://www.fuget.org/packages/MinVer.Example/badge.svg)](https://www.fuget.org/packages/MinVer.Example)

## Features

- Build with Github Actions
- Build Release packages from main/master on every new tagged Github Release
- Build Pre-Release packages from develop branch an every push (code in feature branches only)
- Automatic versioning with SemVer 2.0 and [MinVer](https://github.com/adamralph/minver), based on Git Tags and "Git height"
- Including NuGet...
  - Complete metadata
  - [SourceLink](https://github.com/dotnet/sourcelink) configured (link to source/commit for every package)
  - embedded portable PDBs & compressed source (or snupkg symbols if required, just uncomment)
  - Github README.md (this file) used also for listing on nuget.org
  - Icon for NuGet package

## NuGet Package Metadata

- See [MSDN: Package authoring best practices](https://tinyurl.com/syhtn6u6)

## Readme.md

Consider including the following items in your README:

- An introduction to what your package is and does – what problems does it solve?
- How to get started with your package – are there any specific requirements?
- Links to more comprehensive documentation if not included in the README itself.
- At least a few code snippets/samples or example images.
- Where and how to leave feedback such as link to the project issues, Twitter, bug tracker, or other platform.
- How to contribute, if applicable.

[See more about README.md and embedding in your package here](https://devblogs.microsoft.com/nuget/add-a-readme-to-your-nuget-package/)

## SourceLink

- [MSDN Guidance](https://docs.microsoft.com/en-us/dotnet/standard/library-guidance/sourcelink)
- [Github Project](https://github.com/dotnet/sourcelink#using-source-link-in-net-projects)
