# The Cala Project
Easily create cross-platform applications.  Some common tasks are not easily portable across different platforms, and this crate hopes to fix that.  That way you don't have to worry about how to port your GUI, audio, or bluetooth interface, etc. and can get straight to building your application's content!

Cala is a platform-agnostic system interface for hardware IO.  This means that eventually, Cala should support all of the different hardware that's connected to your computer.  Cala is designed so that it talks to the operating system to interface with the hardware, so no special permissions are needed for your application.

## Motivation & Naming
The aim is to create a newer, better GTK + SDL in Rust!  Why GTK + SDL?  Because a lot of programs need to depend on both anyway (like [totem](https://en.wikipedia.org/wiki/Totem_Video_Player)), and they do a lot of the same things; Usually one library does each specific task better than the other.  The goal of this library is to provide the common ground for video games and general GUI applications together.  The name cala is derived from the fungus known as calafate rust.

# Blog
- [New Website - *2019-08-07, by Aldarobot*](new-website)
