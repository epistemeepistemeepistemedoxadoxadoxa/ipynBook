# ipynBook

# Setting Up Jupyter Notebooks in Visual Studio Code

This guide will walk you through installing Jupyter Notebooks on your computer using Visual Studio Code (VS Code).

## Step 1: Install VS Code

If you haven’t already:

1. Go to [https://code.visualstudio.com/](https://code.visualstudio.com/)
2. Download and install the latest version for your operating system.

## Step 2: Install Python

Make sure Python is installed on your system.

- Download Python from [https://www.python.org/downloads/](https://www.python.org/downloads/)
- During installation, **check the box that says "Add Python to PATH"**

## Step 3: Install Jupyter Extension in VS Code

1. Open VS Code
2. Go to the **Extensions** panel (click the square icon on the sidebar or press `Ctrl+Shift+X`)
3. Search for **"Jupyter"**
4. Click **Install** on the extension provided by Microsoft

More info: [Official Jupyter in VS Code Docs](https://code.visualstudio.com/docs/datascience/jupyter-notebooks)

## Step 4: Install Jupyter via the Terminal

In the VS Code terminal (open with `` Ctrl+` ``):

```bash
pip install notebook
```

This will install the Jupyter backend that runs your notebooks.

## Step 5: Open or Create a Jupyter Notebook

- Open a `.ipynb` file or create a new one:  
  `File > New File > Jupyter Notebook`
- You’re ready to start coding in cells!
