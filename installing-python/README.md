# How to Install Python — A Complete Beginner's Guide

No experience needed. This guide walks you through everything from scratch.

---

## What Is Python and Why Do I Need It?

Python is a free programming language that many tools and apps are built on. You don't need to learn how to code — you just need Python installed on your computer so those tools can run.

Think of it like installing Java or a printer driver: you're not going to use it directly, but other software needs it to work.

---

## Before You Start

Check if Python is already installed on your computer.

1. Open a terminal:
   - **Windows:** Press `Windows key + R`, type `cmd`, press Enter
   - **Mac:** Press `Command (⌘) + Space`, type `Terminal`, press Enter

2. Type the following and press Enter:
   ```
   python --version
   ```

3. If you see something like `Python 3.11.4`, Python is already installed and you're done!

   If you see an error or `Python 2.x.x` (an older version), follow the steps below.

---

## Installing Python on Windows

### Step 1 — Download the Installer

1. Open your web browser and go to: [https://www.python.org/downloads/](https://www.python.org/downloads/)
2. You'll see a big yellow button that says **"Download Python 3.x.x"** — click it
3. A file called something like `python-3.x.x-amd64.exe` will download to your computer

### Step 2 — Run the Installer

1. Find the downloaded file (usually in your Downloads folder) and double-click it
2. A setup window will appear

   > ⚠️ **Before you click anything else:** Look at the bottom of the installer window. There is a checkbox that says **"Add Python to PATH"**. **Check this box.** This is the most important step — if you skip it, Python won't work properly.

3. Click **"Install Now"** (the top option is fine for most people)
4. If Windows asks "Do you want to allow this app to make changes?", click **Yes**
5. Wait for the installation to finish — it usually takes 1–2 minutes
6. Click **Close** when done

### Step 3 — Verify the Installation

1. Open a new terminal window (close the old one first if it was open, then press `Windows key + R`, type `cmd`, press Enter)
2. Type:
   ```
   python --version
   ```
3. You should see something like `Python 3.12.0`. If you do, Python is installed successfully!

---

## Installing Python on Mac

### Step 1 — Download the Installer

1. Open your web browser and go to: [https://www.python.org/downloads/](https://www.python.org/downloads/)
2. Click the big yellow **"Download Python 3.x.x"** button
3. A file called something like `python-3.x.x-macos11.pkg` will download

### Step 2 — Run the Installer

1. Find the downloaded file in your Downloads folder and double-click it
2. A setup wizard will open — click **Continue** through each screen
3. When asked, click **Agree** to accept the license
4. Click **Install** — you may be asked to enter your Mac password (this is your normal login password)
5. Wait for the installation to finish, then click **Close**

### Step 3 — Verify the Installation

1. Open Terminal (press `Command + Space`, type `Terminal`, press Enter)
2. Type:
   ```
   python3 --version
   ```
3. You should see something like `Python 3.12.0`

> **Note for Mac users:** On Mac, you may need to type `python3` instead of `python` in some instructions. If a command using `python` doesn't work, try replacing it with `python3`.

---

## Common Problems & Fixes

### "Python is not recognized as an internal or external command" (Windows)

This means Python wasn't added to PATH during installation. Fix it by:

1. Uninstall Python — go to **Settings → Apps**, find Python, and click Uninstall
2. Re-run the installer from [python.org](https://www.python.org/downloads/)
3. This time, make sure to check **"Add Python to PATH"** before clicking Install

### "I see Python 2.7 instead of Python 3"

Python 2 is outdated and won't work with modern tools. Install Python 3 from [python.org](https://www.python.org/downloads/) — having both versions on your computer is fine.

### The installer won't open on Mac

Right-click the `.pkg` file and select **Open**, then click **Open** again when Mac warns you about the file. Mac sometimes blocks files downloaded from the internet unless you do this.

---

## Understanding the Terminal

You'll use the terminal to run Python tools. It looks intimidating but you only need to know a few basics:

- **You type commands and press Enter to run them** — nothing happens until you press Enter
- **Nothing will break** if you type something wrong — you'll just get an error message
- To clear the screen, type `cls` (Windows) or `clear` (Mac) and press Enter
- To close the terminal, type `exit` and press Enter, or just close the window

---

## What's Next?

Now that Python is installed, you can go back to the tool's installation guide and continue from where it told you to install Python.

If you ever need to check that Python is still working, just open a terminal and run `python --version` (or `python3 --version` on Mac).
