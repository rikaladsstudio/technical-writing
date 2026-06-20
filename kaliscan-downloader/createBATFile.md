# How to Create a BAT File for Kaliscan Downloader

## Overview

This guide will show you how to create a BAT file to quickly open the Kaliscan Downloader GUI tool without having to type commands in the Terminal every time.

## Instructions

1. Open Notepad or any text editor.
2. Copy and paste the following text into the editor:

```
@echo off

REM Navigate to kaliscan-downloader folder directory
pushd C:\where\you\extracted\kaliscan-downloader

REM Activate the virtual environment 
call .venv\Scripts\activate

REM: Open GUI
python main.py
```

3. Replace `C:\where\you\extracted\kaliscan-downloader` with the actual path where you extracted the tool.
4. Save the file with a `.bat` extension, for example, `open_kaliscan_downloader.bat`.
5. You're all set! Double-click the `.bat` file to open the Kaliscan Downloader GUI tool.

