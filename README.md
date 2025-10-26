# no-OS-WindowingSystem
Bare Metal Windowing System in C

A work in progress. A windowing system used to multiplex input devices and framebuffer among multiple layers, viewports or windows.
Visually inspired by AT&T Blit Terminal and Silicon Graphics Multiple EXposure [MEX] on the IRIS.

Currently targetting RP2040 RPi Pico and a ST7789V2 320x240 RGB565 LCD with USB HID mouse and keyboard.

Source code coming soon.

![no-OS-WindowingSystem_image1](https://github.com/user-attachments/assets/e24adb6b-5a45-4cee-b820-115b06381d51)

![no-OS-WindowingSystem_image2](https://github.com/user-attachments/assets/53c38340-0081-40ac-bb14-6000db3988e3)

Running demonstration(s) as GIF movies below [8 Mb GIF image may take a few moments to load]


![no-OS-WindowingSystem_movieLo](https://github.com/user-attachments/assets/649de3c7-8072-4df8-9221-7efd9e4715fc)

You can not claim to be inspired by Silicon Graphics without some sort of IRIS-GL like 3D support.

So here an SGI logo model in Wavefront OBJ format is converted to a .h header and included in the build.

A camera path routine is created and calls to no-OS-WindowingSystem are made to render the model directly into a window.
Currently wireframe and very basic filled triangle shading. [7 Mb GIF image may take a few moments to load]

![no-OS-WindowingSystem_gl3DLo](https://github.com/user-attachments/assets/c37cd262-8c0d-48a2-b052-6439da016dc7)
