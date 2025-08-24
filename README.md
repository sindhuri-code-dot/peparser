# PE Parser

A PE file metadata parser for malware analysis and forensic investigations.

## Download

Get the latest pre-built binaries from the [Releases page](https://github.com/sindhuri-code-dot/peparser/releases).

## Installation

### Windows
1. Download `pe-parser-windows.exe` from the Releases page
2. Rename it to `pe-parser.exe`
3. Place it in any directory in your system PATH

### Linux
```bash
curl -LO https://github.com/sindhuri-code-dot/peparser/releases/latest/download/pe-parser-linux
chmod +x pe-parser-linux
sudo mv pe-parser-linux /usr/local/bin/pe-parser

Features


    PE header parsing

    Section information extraction

    Import table analysis

    Machine architecture detection

    Compilation timestamp extraction

Usage

# Basic analysis
pe-parser file.exe

# Windows
pe-parser-windows.exe file.exe

# Linux  
./pe-parser-linux file.exe

# Disable pefile fallback
pe-parser --no-pefile file.exe
