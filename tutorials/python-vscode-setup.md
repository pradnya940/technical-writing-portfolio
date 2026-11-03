# Python Setup in Visual Studio Code

## Overview

This tutorial explains how to install Python and configure Visual Studio Code to run Python programs.

## Prerequisites

* A computer running Windows, macOS, or Linux
* Internet connection
* Basic computer knowledge

## Step 1: Install Python

1. Visit the official Python website: https://www.python.org/downloads/
2. Download the recommended Python installer.
3. Run the installer.
4. On Windows, enable the option **Add Python to PATH**.
5. Complete the installation.

## Step 2: Verify Python Installation

1. Open Command Prompt or Terminal.
2. Enter:

```bash
python --version
```

If this command is unavailable on your system, try:

```bash
python3 --version
```

Expected output:

```text
Python 3.x.x
```

The exact version depends on the installed release.

## Step 3: Install Visual Studio Code

1. Visit https://code.visualstudio.com/
2. Download Visual Studio Code.
3. Run the installer.
4. Launch Visual Studio Code.

## Step 4: Install the Python Extension

1. Open Visual Studio Code.
2. Click the Extensions icon on the left sidebar.
3. Search for **Python**.
4. Install the Python extension published by Microsoft.

## Step 5: Create a Python Program

1. Click **File → New File**.
2. Save the file as `hello.py`.
3. Enter the following code:

```python
print("Hello, World!")
```

4. Save the file.

## Step 6: Run the Program

Open the terminal in VS Code:

**Terminal → New Terminal**

Run:

```bash
python hello.py
```

Expected output:

```text
Hello, World!
```

## Troubleshooting

If Python is not recognized:

* Verify Python is installed.
* Check whether Python was added to PATH.
* Restart the terminal.
* Try `python3 hello.py` if appropriate for your system.

## Conclusion

Python and Visual Studio Code are now configured to run a basic Python program.
