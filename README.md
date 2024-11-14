![dosbox-logo_banner](https://github.com/user-attachments/assets/d0c8332a-0377-4579-9ece-2c6c6f192b61)

# DOSXBox360
is a native port of DOSBox for the Xbox 360 by Lantus 

DOSXBox is an emulator which emulates an IBM PC compatible computer running MS-DOS.
It is intended especially for use with old PC games. DOSBox is free software.

DOSBox is a command-line program, configured either by a set of command-line arguments or by editing a plain text configuration file. For ease of use, several graphical front-ends have been developed by the user community.


DOSBox is a full CPU emulator, capable of running DOS programs that require the CPU to be in either real mode or protected mode. Other similar programs, such as dosemu or VDMs for Windows and OS/2, provide compatibility layers and rely on virtualization capabilities of the 386 family processors. Since DOSBox can emulate its CPU by interpretation, it is independent of its host CPU. However, on systems which provide the i386 instruction set, the option to use dynamic instruction translation is available in DOSBox. Though this setting is less accurate and reliable, it is faster than interpretive CPU emulation.

Features
--------

Full USB and Chatpad keyboard support
Mouse support via left analog stick
Mouse buttons are simulated by 'A' and 'B' buttons

Installation
------------

The package contains 2 files.

DOSBox.xex - if you are running a retail (JTAG) console. Use this version.

DOSBox-Dev.xex - if you have access to a devkit, this version will replace the analog stick mouse with real mouse support. Plug in a mouse into any USB port.

Note - you cannot run DOSBox-Dev.xex on a retail console.

Special
-------
DOSBox360 Browser by begal

https://github.com/mLoaDs/DOSXBox360Browser

Notes
-----

I started out by working with XeDosBox source and fixing the long standing keyboard issue as well as fixing a crash to protected mode games. I decided to just port over the latest 0.74 repository. Compatability should be much improved over XeDosBox.
