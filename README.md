#HXSRC

This is version 2.16 of the source files for Japheth's HXDOS Extender and related tools. I have not done any modification to the code,
this is only a snapshot of the v2.16 release so that it can remain available for use.

It still retains the Sybase license that he released it with.

The HXSRC package contains the HX DOS extender source code. This consists of:
* DPMI host HDPMI32.EXE / HDPMI16 (MASM)
* DPMI loader DPMILD32.EXE / DPMILD16.EXE (MASM)
* Win32 emulation dlls DKRNL32, DADVAPI, DGDI32, DUSER32, OLE32, OLEAUT32, WINMM, DDDRAW, DINPUT, DSOUND (MASM)
* GUI helper dll HXGuiHlp.dll
* Tools HXLdr32.exe, PEStub.exe, PatchPE.exe, PatchNE.exe(MASM)
* MZ stubs DPMIST32.BIN / DPMIST16.BIN (MASM)
* HX's MZ/NE file format support (MASM)
* WD debugger trap helper files HXHELP.EXE / HXHP16.EXE (MASM)
* VESA support dll VESA32 (MASM)
* HX's source code is about 100.000 lines of code.
