# <img src="https://github.com/FeatherTools/.github/blob/main/profile/feather-logo-200.png" alt="FeatherTools Logo" width="100" height="100"> Template

[![NuGet](https://img.shields.io/nuget/v/Feather.LibraryTemplate.svg)](https://www.nuget.org/packages/Feather.LibraryTemplate)
[![NuGet Downloads](https://img.shields.io/nuget/dt/Feather.LibraryTemplate.svg)](https://www.nuget.org/packages/Feather.LibraryTemplate)
[![Checks](https://github.com/FeatherTools/LibraryTemplate/actions/workflows/tests.yaml/badge.svg)](https://github.com/FeatherTools/LibraryTemplate/actions/workflows/tests.yaml)

> Library template

## Install

```sh
paket add Feather.LibraryTemplate
```

**Note**: You can also use this library in a Fable project.

## Release
1. Increment version in `LibraryTemplate.fsproj`
2. Update `CHANGELOG.md`
3. Commit new version and tag it

## Development
### Requirements
- [dotnet core](https://dotnet.microsoft.com/learn/dotnet/hello-world-tutorial)

### Build
```bash
./build.sh build
```

### Tests
```bash
./build.sh -t tests
```
