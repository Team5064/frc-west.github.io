---
title: Libraries
layout: coursepage
---

A really cool part of programs is their ability to use code from other programs. These other programs are known as "libraries", or "dependencies". They are used to abstract away some of the lower level details of how it will run.

You might want to display a window on the screen with a program. To do so, you would use libraries, like so:

    Ask Operating System for graphics manager
    Ask Graphics Manager for window space
    Ask Graphics Manager to render a screen on the window space
    Graphics Managers asks Renderer to process the screen
    Screen is displayed

So instead of having to write really low level code to display pixel by pixel, you can ignore the details of how it's done and only worry about what to display.

There are also usually programming language libraries. For example, python has a large assortment of libraries to do anything you want. This makes things much easier for the programmer, so that they don't need to worry about details.

This is all known as low-level abstraction. This simply means that the hard-to-do details are taken care of for you, and you just need to provide input.

You will probably be unknowingly using a lot of libraries when programming. They make everyone's life easier, because re-writing already established code is tedious and a waste of time. It's building on the shoulders of giants.
