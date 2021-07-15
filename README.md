# MinVer example

Example for how to build DotNet packages with Github Actions using MinVer and publish to nuget.org

[![OnPublishedRelease](https://github.com/Kurpanik/MinVerExample/actions/workflows/OnPublishedRelease.yml/badge.svg)](https://github.com/Kurpanik/MinVerExample/actions/workflows/OnPublishedRelease.yml)  [![OnPush develop](https://github.com/Kurpanik/MinVerExample/actions/workflows/OnPushDevelop.yml/badge.svg)](https://github.com/Kurpanik/MinVerExample/actions/workflows/OnPushDevelop.yml)  [![NuGet Status](https://img.shields.io/nuget/v/MinVer.Example.svg)](https://www.nuget.org/packages/MinVer.Example/)

## Features

- Build with Github Actions
- Build Release packages from main/master branch
- Build Pre-Release packages from develop branch (or any other you require for your Git Flow)
- Automatic versioning with SemVer 2.0 and [MinVer](https://github.com/adamralph/minver), based on Git Tags and "Git height"
- Including [SourceLink](https://github.com/dotnet/sourcelink)

## Nuget Package Metadata

- See [MSDN: Package authoring best practices](https://tinyurl.com/syhtn6u6)

## Readme.md

Consider including the following items in your README:

- An introduction to what your package is and does – what problems does it solve?
- How to get started with your package – are there any specific requirements?
- Links to more comprehensive documentation if not included in the README itself.
- At least a few code snippets/samples or example images.
- Where and how to leave feedback such as link to the project issues, Twitter, bug tracker, or other platform.
- How to contribute, if applicable.

[See more about README.md for Nuget packages here](https://devblogs.microsoft.com/nuget/add-a-readme-to-your-nuget-package/)

## SourceLink

- See [MSDN](https://docs.microsoft.com/en-us/dotnet/standard/library-guidance/sourcelink)
- See [Github](https://github.com/dotnet/sourcelink#using-source-link-in-net-projects)
