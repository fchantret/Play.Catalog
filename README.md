# Moving generic code into a reusable NuGet package

1. Add a source for Nuget packages

```
dotnet nuget add source ../../../packages -n PlayEconomy
```

2. Add the Play.Common package

```
dotnet add package Play.Common
```