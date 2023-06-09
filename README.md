## Adding templates to .NET Core

>> I don't want to rely on Visual Studio <<
`dotnet new --install "MonoGame.Templates.CSharp"`

## `dotnet new mgdesktopgl -o SomeProject`
[dotnet new](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-new)

Template | Alias | Tags
-- | -- | -- 
MonoGame Android Application | mgandroid | MonoGame/Games/Mobile/Android
MonoGame Content Pipeline Extension | mgpipeline | MonoGame/Games/Extensions
MonoGame Cross-Platform Desktop Application | mgdesktopgl | MonoGame/Games/Desktop/Windows/Linux/macOS
MonoGame Game Library | mglib | MonoGame/Games/Library
MonoGame iOS Application | mgios | MonoGame/Games/Mobile/iOS
MonoGame Shared Library Project | mgshared | MonoGame/Games/Library
MonoGame Windows Desktop Application | mgwindowsdx | MonoGame/Games/Desktop/Windows/Linux/macOS
MonoGame Windows Universal XAML Application | mguwpxaml | MonoGame/Games/Desktop/Windows/Xbox/UWP/XAML


## TODOs
- [x] Multi-resolution support
    - [x] Calculate render buffer and draw it on window resolution
    - [x] Update render buffer size as soon as the screen is resized