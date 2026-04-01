This project is aimed to bring WASAPI layer support to previous Windows versions such like Win2k, XP, 2003 converting WASAPI calls to DirectSound.

DO NOT TRY TO USE ON Windows VISTA and higher you will break your sound completely!

How to install:
1. Copy mmdevapi.dll info System32 folder (if using 64-bit Windows - SysWOW64 is for x86 version)
2. Register mmdevapi.dll using regsvr32 "C:\Windows\System32\mmdevapi.dll"

This code can be compiled using Microsoft Visual Studio and corresponding Windows SDK kit. Personally I use Microsoft Visual Studio 2026 and Windows SDK for Windows 10 2004 (10.0.19041.0) on Windows 10.
