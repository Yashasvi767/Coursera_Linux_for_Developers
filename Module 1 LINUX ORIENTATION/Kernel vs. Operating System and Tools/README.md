# Kernel
Kernel is the central component that connects the hardware to the software, and manages the system's resources such as memory, CPU time sharing among competing applications and services.

It handles all the devices that are connected to the computer by including device drivers and making them available for operating systems to use.

A system running only a kernel has limited functionality, and only such place is in a dedicated device (like an embedded device) such as inside an appliance.

Narrowly defined, Linux is only the kernel of the opetating systems (OS).

# Operating Systems
To be able to do a variety of things we need some other components, which are not a part of Linux:

- Important system libraries
   - shared libraries or dynamic linked libraries
   - most important one is libc, used by virtually every application

- Important system services (called daemons)
   - started when the system runs to control and monitor activities on the system, eg, networking, printing disk maintenance, noticing when new equipment is plugged in, monitoring system load and performance, etc
 
- Basic system utilities
  - Those which handle listing files, viewing them, renaming them, removing them, etc; bringing network connections up and down; compressing and decompressing files, etc.
 
  - important program is the command shell program, which is what users interact with when working at a command line, but which is also ised by non-interactive scripts.
 
  - default shell for Linux is **bash**, (**B**ourne **A**gain **Sh**ell), it is an extension of the older sh, or Bourne Shell progeam.
 
 # Graphical User Interface (GUI)
  - Normal users use GUI
  - Almost all desktop Linux systems are built using X Windows System (or X) as the base of this interface
  - Besides X, window manager controls the appearances and behaviour of windows
  - desktop manager controla the entire desktop, twomost common choices in Linux are GNOME and KDE

 # Developmental Environment Tools
  - eg, compilers, debuggers

 # Linux Distribution 
  - brings all components together in a ceherent way
