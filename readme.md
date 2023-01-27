# Notes made to understand and document .NET info

## What is .NET?
Multiplatform environment for software development, including:
* Desktop apps
* Web apps
* Web services
* OS services
* Games
* IoT Apps

## What is .NET 5?
Homogenous, unified and multiplatform development environment

## .NET runtimes as of .NET 5
* .NET Framework (Windows apps)
* Unity (Games)
* .NET Compact Framework (Phone apps)
* Silverlight (Web)
* .NET Core
* Mono/Xamarin

## .NET 5 Characterics
* Open-source
* Multiplatform
* Free to use
* New version every year

## Why use .NET instead of .NET Framework
.NET Framework **won't have new functionality** only bug fixes.

## Relation between .NET Standard & .NET 5
.NET Standard has only a selection of APIs while .NET 5 is entirely multi platform, in this sense .NET 5 englobes .NET Standard as well as every other .NET product.

## What is a TFM?
*A target framework moniker (TFM) is a standardized token format for specifying the target framework of a . NET app or library.*

Basically is a tag inside the project setting that changes the target platform of the app/library.


Using the .netX.Y TFM you are developing a multi platform software, in case of wanting to target a specific platform, you can add their respectives TFMs, like netX.Y-android for Android, netX.Y-windows for Windows and netX.Y-ios for IOS. The functionalities of every API are then added together.

## Supported .NET programming languages
You can use any of the following programming languages to use .NET:
* C# 9.0
* F# 5.0
* VB 16.0
Which one you use is based on your own personal preferences.

## Installation of .NET SDK
You have 2 options for downloading and installing .NET, though one of them is only used if you plan to use Visual Studio as your IDE, the 2 options are the following:
* Going to the official .NET page [dot.net](https://dot.net) and downloading it from there.
* Managing the Visual Studio modules **this option is only useful for Visual Studio users**

