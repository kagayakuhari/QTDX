# QTDX
QTDX (QEMU-TDX) aims to be an Intel TDX emulator that uses QEMU to enforce TDX
compliance. Currently,
Intel TDX technology is limited to Intel Xeon 4th and 5th generation processors.
The main goal of this project is to be able to launch a guest Trusted Domain
(TD) in a non-TDX-enabled host machine. For this, we plan to use the open-source
Intel TDX module for TD <--> hypervisor communication and QEMU for TDX behaviour
emulation.

## Disclaimer
This repository is very much a work in progress and definitely not suited for
any current purpose. I do not guarantee complete functionality at any point of
the development of this project.
