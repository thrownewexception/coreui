# coreui
A cross platform user interface library built on the new open sourced cross platform .Net Core.

With Microsoft recently open-sourcing the .Net Framework, they created the .Net Core, a cross platform .Net Framework. One of the major flaws of this framework is that it lacks a cross platform user interface system. coreui aims to fix this by introducing System.UserInterface for cross platform user interface development.

## Layout
System.UserInterface exposes a cross platform set of classes that represent user interface controls similar to System.Windows.Forms, but using these classes will render the closest match on each operating system using their respective native libraries.

System.UserInerface is interface driven, so anyone could write a backend for another ui toolkit and use that to produce the user interface for your project.

The backends are not exposed to the developer, as we are trying to create a standard set of controls that are customizable and can render cross platform.

## Initial backend support
Windows: WinAPI / GDI
Mac OSX: Cocoa
Linux: X11

This is a community driven project.

ANYONE is welcome :)
