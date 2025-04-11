# Setting Up VS Code for Python Development

Visual Studio Code (VS Code) is a powerful and lightweight code editor that is perfect for Python development. Follow this guide to set up your environment.

---

## Prerequisites

- Install [Python](https://www.python.org/downloads/) (ensure it's added to your PATH).
- Install [Visual Studio Code](https://code.visualstudio.com/).

---

## Step 1: Install the Python Extension

1. Open VS Code.
2. Go to the Extensions view by clicking on the Extensions icon in the Activity Bar or pressing `Ctrl+Shift+X`.
3. Search for "Python" and install the extension by Microsoft.

---

## Step 2: Configure Python Interpreter

1. Open a Python file or create a new one with a `.py` extension.
2. Press `Ctrl+Shift+P` to open the Command Palette.
3. Type `Python: Select Interpreter` and select the appropriate Python interpreter from the list.

---

## Step 3: Install Useful Extensions (Optional)

- **Pylance**: For better IntelliSense and type checking.
- **Python Docstring Generator**: To generate docstrings for your functions.
- **Code Runner**: To quickly run Python scripts.

---

## Step 4: Set Up a Virtual Environment (Recommended)

1. Open the terminal in VS Code (`Ctrl+``).
2. Run the following commands:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```
3. Select the virtual environment as your Python interpreter.

---

## Step 5: Debugging Configuration

1. Open the Debug view by clicking on the Debug icon in the Activity Bar or pressing `Ctrl+Shift+D`.
2. Click on "create a launch.json file" and select "Python".
3. Customize the configuration as needed.

---

## Step 6: Install Python Packages

Use the terminal to install packages:
```bash
pip install <package_name>
```

---

## Step 7: Customize Settings (Optional)

1. Open the settings (`Ctrl+,`).
2. Search for Python-specific settings like `python.linting.enabled` or `python.formatting.provider` and configure them.

---

## Step 8: Start Coding!

You are now ready to start developing Python projects in VS Code. In this tutorial, we will be following along Coursera's Google IT Automation With Python. 

[Google IT Automation With Python](https://www.coursera.org/professional-certificates/google-it-automation) 

We will be making our code open-source, and all of it will be available on [Github](https://github.com).

If you would like to support this software-engineer, buy me a coffee! <3 :)

```
buy_me_a_coffee = "0xb26DDe29cF72F37A64aF8B292209B6FEe686A3B6"
print(buy_me_a_coffee)
# Output: Buy me a coffee: 0xb26DDe29cF72F37A64aF8B292209B6FEe686A3B6
```
---

## Resources

- [VS Code Python Documentation](https://code.visualstudio.com/docs/python/python-tutorial)
- [Python Official Documentation](https://docs.python.org/3/)
- [Github Official Documentation](https://docs.github.com)
- [Git Official Documentation](https://git-scm.com/doc)
---