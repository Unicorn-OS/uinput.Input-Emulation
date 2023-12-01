# uinput.Input Emulation
uinput module  - used in "ydotool"

# Doc:
https://www.kernel.org/doc/html/latest/input/uinput.html

[.old](https://www.kernel.org/doc/html/v4.12/input/uinput.html)


# Comparison:
[uinput vs libei](https://gitlab.freedesktop.org/libinput/libei#uinput-vs-libei)
>uinput is a Linux kernel module that allows creating /dev/input/event-compatible devices. Unlike XTest it is independent of a windowing system but requires write access to /dev/uinput, usually limited to root. uinput devices are effectively identical to physical devices and will thus work on the tty and in any windowing system.
