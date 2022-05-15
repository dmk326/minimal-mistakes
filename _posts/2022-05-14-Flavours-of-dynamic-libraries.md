---
title: "Flavours of Dynamic Libraries"
categories:
  - OS 
tags:
  - C++
  - DLL
  - Static Library
  - Dynamic Library
---

A library is code, designed to be reused by other programs. It is just normal C or C++ code except for the absence of `main()`. Libraries can be plugged into executables or other libraries. On most platforms, libraries come in two flavors: **static** or **dynamic**, each with its own advantages and disadvantages.

## Static Library:

<!-- The **static library** contains functionality that is bound to a program statically at compile time. This differs from **dynamic libraries**, which are loaded when an application is loaded and binding occurs at run time. Below Figure shows the library hierarchy in Linux. -->


<!-- this is how we add image to any post in jekylly and markdown -->
<!-- ![Alternative  text]({{ page.image | relative_url }}) -->