<p align="center"><b>This is the snap for Decompyle++</b>, <i>"A Python Byte-code Disassembler/Decompiler"</i>. It works on Ubuntu, Fedora, Debian, and other major Linux
distributions.</p>

## Install

    sudo snap install pycdc

([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

# Decompyle++
***A Python Byte-code Disassembler/Decompiler***

Decompyle++ aims to translate compiled Python byte-code back into valid
and human-readable Python source code. While other projects have achieved
this with varied success, Decompyle++ is unique in that it seeks to
support byte-code from any version of Python.

Decompyle++ includes both a byte-code disassembler (pycdas) and a
decompiler (pycdc).

As the name implies, Decompyle++ is written in C++.
If you wish to contribute, please fork us on github at
https://github.com/zrax/pycdc

## Usage
**To run pycdas**, the PYC Disassembler:
`pycdc.pycdas [PATH TO PYC FILE]`
The byte-code disassembly is printed to stdout.

**To run pycdc**, the PYC Decompiler:
`pycdc [PATH TO PYC FILE]`
The decompiled Python source is printed to stdout.
Any errors are printed to stderr.
