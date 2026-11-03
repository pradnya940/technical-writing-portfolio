# Common Python Errors and How to Fix Them

## 1. Python Is Not Recognized

### Error

```text
'python' is not recognized as an internal or external command
```

### Possible Cause

Python may not be installed or its installation directory may not be included in PATH.

### Solution

1. Verify Python is installed.
2. Reopen Command Prompt.
3. Try `python --version`.
4. If necessary, configure the Python installation path.

## 2. Module Not Found

### Error

```text
ModuleNotFoundError: No module named 'requests'
```

### Possible Cause

The required Python package is not installed in the active environment.

### Solution

Run:

```bash
python -m pip install requests
```

Then rerun the program.

## 3. Syntax Error

### Error

```text
SyntaxError: invalid syntax
```

### Possible Cause

The program contains invalid Python syntax.

### Solution

1. Read the line number shown in the error.
2. Check brackets and quotation marks.
3. Verify indentation and punctuation.
4. Run the program again.

## 4. File Not Found

### Error

```text
FileNotFoundError
```

### Possible Cause

The program cannot locate the requested file.

### Solution

1. Verify the filename.
2. Check the file path.
3. Confirm the terminal is opened in the correct folder.
4. Use the correct relative or absolute path.

## Troubleshooting Best Practices

* Read the complete error message.
* Identify the line where the error occurs.
* Reproduce the issue.
* Change one thing at a time.
* Verify that the solution works.
