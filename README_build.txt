
# PowerResizer 0.95 – 64‑bit Upgrade (Source Package)

This package contains **only the patched / updated source code** and build instructions.
You still need the original *PowerResizer 0.95* source tree (from SourceForge) because the
majority of the code is unchanged.  The patch file in this archive (`patch.diff`) adds
64‑bit compatibility and Visual Studio 2022 project files.

## Quick Build Steps

1. Install **Visual Studio 2022 Community** with the *Desktop development with C++* workload.
2. Download the original `PowerResizer_0.95_Sources.zip` from SourceForge and extract it.
3. Extract this package **on top of** the original source directory (it will overwrite /
   add only a few files).
4. Double‑click `PowerResizer.sln`.
5. In the toolbar choose **Release** and **x64**.
6. Build → *Build Solution* (Ctrl + Shift + B).
   * Output files will appear in `bin\x64\Release\`
     - `PowerResizer64.exe`
     - `PowerResizer64.dll`
7. Copy those two files anywhere (e.g. `C:\Program Files\PowerResizer\`) and run
   **PowerResizer64.exe** (Run as Administrator if you need it to manage elevated apps).

## Files in this archive

```
README_build.txt        – these instructions
PowerResizer.sln        – updated VS 2022 solution
PowerResizer\*.vcxproj – updated project files for EXE and DLL
patch.diff              – full textual diff from original v0.95 to 64‑bit version
```

If you run into trouble, let me know in our chat and I can walk you through.

Enjoy!
