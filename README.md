[![NuGet Badge](https://buildstats.info/nuget/Raspberry.System3)](https://www.nuget.org/packages/Raspberry.System3/)[![Build status](https://ci.appveyor.com/api/projects/status/d9bswf8kwk484tva?svg=true)](https://ci.appveyor.com/project/JTrotta/raspberry-sharp-system) [![BCH compliance](https://bettercodehub.com/edge/badge/JTrotta/raspberry-sharp-system?branch=master)](https://bettercodehub.com/)

Raspberry# System
=================

See the **[Raspberry\# System Wiki](raspberry-sharp-system/wiki)** for full documentation and samples.

Introduction
------------
Raspberry# System is a .NET/Mono Library for Raspberry Pi. This project is an initiative of the [Raspberry#](http://www.raspberry-sharp.org) Community.

Current release is an early public release. Some features may not have been extensively tested.
Raspberry# System currently supports high resolution timer, as well as Raspberry Pi system board identification.

Features
--------

### Raspberry.System
Raspberry.System provides utilities for Raspberry Pi boards, while using .NET concepts, syntax and case.
You can easily add a reference to it in your Visual Studio projects using the **[Raspberry.System Nuget](https://www.nuget.org/packages/Raspberry.System3)**.

It currently support the following features:
+ Automatic detection of various Raspberry Pi revisions, as of 2013-09, **Raspberry Pi model B rev1 and rev2 and Raspberry Pi model A**
+ High resolution (about 1µs) timers
