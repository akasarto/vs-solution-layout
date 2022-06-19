# About
A template layout for new .NET Solutions using Visual Studio 2022 Community or greater. Include initial folder structure and configuration files.

This template was inspired by David Fowler's [gist](https://gist.github.com/davidfowl/ed7564297c61fe9ab814) and can be adjusted as needed.

# Attention
After creating a project from this template, remember to:
- Update the included LICENSE with your own.
- Rename the .sln file to your own.
- Update this readme.

## Extras
Starting from .NET 5, it is possible to create a `.cs` file in your projects that will hold global `using` statements. E.g.:

File: `Usings.cs`
```csharp
global using System.Buffers.Binary;
global using System.Runtime.CompilerServices;
global using System.Runtime.InteropServices;
global using System.Text;
```
