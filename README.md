![GitHub](https://img.shields.io/github/license/BluehillNuGet/Bluehill.Deconstructors?style=flat-square)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=BluehillNuGet_Bluehill.Deconstructors&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=BluehillNuGet_Bluehill.Decontructors)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=BluehillNuGet_Bluehill.Deconstructors&metric=coverage)](https://sonarcloud.io/summary/new_code?id=BluehillNuGet_Bluehill.Deconstructors)
![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/BluehillNuGet/Bluehill.Deconstructors/dotnet.yml?style=flat-square)
[![GitHub issues](https://img.shields.io/github/issues-raw/BluehillNuGet/Bluehill.Deconstructors?style=flat-square)](https://github.com/BluehillNuGet/Bluehill.Deconstructors/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr-raw/BluehillNuGet/Bluehill.Deconstructors?style=flat-square)](https://github.com/BluehillNuGet/Bluehill.Deconstructors/pulls)
[![Nuget](https://img.shields.io/nuget/v/Bluehill.Deconstructors?logo=nuget&style=flat-square)](https://www.nuget.org/packages/Bluehill.Deconstructors)
[![Nuget (with prereleases)](https://img.shields.io/nuget/vpre/Bluehill.Deconstructors?color=616&label=preview&logo=nuget&style=flat-square)](https://www.nuget.org/packages/Bluehill.Deconstructors)
[![Nuget](https://img.shields.io/nuget/dt/Bluehill.Deconstructors?style=flat-square)](https://www.nuget.org/packages/Bluehill.Deconstructors)

A collection of extension methods for deconstruction syntax in C#.

```csharp
int[] ints = { 1, 2, 3, 4, 5 };
var (one, two, three, four, five) = ints;
```

## How to use
Import <code>Bluehill.Deconstructors</code> namespace.

```csharp
using Bluehill.Deconstructors;
```

## Supported types
1. IList (Array, List, etc.) (Up to 30 items)
1. Reference Tuple (System.Tuple) (Up to 21 items)
1. KeyValuePair
1. Drawing Types
   1. Point / PointF
   1. Size / SizeF
   1. Rectangle / RectangleF
   1. Color
1. Windows Forms Types
   1. Padding
   1. TableLayoutPanelCellPosition
1. WPF Types
   1. Point
   1. Size
   1. Rect
   1. Thickness
   1. CornerRadius
   1. Color
1. Numerics Types
   1. Vector2/3/4
   1. Matrix3x2/4x4
1. Version
1. DateTime
   1. DateTime
   1. DateOnly
   1. TimeOnly
   1. DateTimeOffset
1. Span (Up to 30 items)
   1. Span
   1. ReadOnlySpan

## Changelog
[Changelog](CHANGELOG.md)
