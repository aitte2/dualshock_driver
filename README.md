# dualshock_driver
Playstation 2 DualShock controller driver for Windows 10

# Driver for?

Most chinese "dualshock to USB controller" adapters have a Hardware Identifier of "VID_0810&PID_0001" in Windows device manager.

Without a driver, Windows will just have basic functionality but won't support Force Feedback (rumble/vibration).

To get vibration you need a driver. This is a generic driver for all "VID_0810&PID_0001" devices, which adds rumble support to the USB adapter on Windows 10 (and earlier).

It is for 64-bit systems only!

# And xbox 360 compatibility?

To play games that look for a Xbox 360 controller, you can use http://www.x360ce.com/ to emulate the controller. That application is able to work together with this driver to give Force Feedback vibration!
