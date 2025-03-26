# ipynBook

# Part 1

# Setting Up Jupyter Notebooks in Visual Studio Code

This guide will walk you through installing Jupyter Notebooks on your computer using Visual Studio Code (VS Code).

## Step 1: Install VS Code (You Likely Have This)

If you haven’t already:

1. Go to [https://code.visualstudio.com/](https://code.visualstudio.com/)
2. Download and install the latest version for your operating system.

## Step 2: Install Python (You Likely Have This)

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

## Step 5: Open or Create a Folder, Open That Folder in VSCode

<img width="1312" alt="Screenshot 2025-03-26 at 6 47 17 PM" src="https://github.com/user-attachments/assets/be51acfe-6d6a-4c8c-9230-aeb989d1903c" />


## Step 6: Create a Jupyter Notebook

- Open a `.ipynb` file or create a new one:  
  `File > New File > Jupyter Notebook`
- You’re ready to start coding in cells!


# Part 2

## Step 1: Open the Terminal in VS Code

<img width="1800" alt="Screenshot 2025-03-26 at 6 40 05 PM" src="https://github.com/user-attachments/assets/c327ea33-4513-4e4d-ab1e-8e9bc6c9eaaa" />
<img width="316" alt="Screenshot 2025-03-26 at 6 40 02 PM" src="https://github.com/user-attachments/assets/a12c6fe1-589d-44bf-87ad-b8e1d12e666c" />


## Step 2: Create a Virtual Environment

python3 -m venv venv

This creates a new folder called venv which contains your isolated Python environment.

## Step 3: Activate the Virtual Environment

On macOS/Linux:
source venv/bin/activate

On Windows (PowerShell):
venv\Scripts\Activate.ps1

## Status: Your Folder Should Look Like This

<img width="1258" alt="Screenshot 2025-03-26 at 6 48 22 PM" src="https://github.com/user-attachments/assets/7e4ff4cd-30b5-42e0-8d0b-1c8f283c8eb6" />

## Step 4: Install Dependencies

Install ipynb_requirements.txt file:
pip install -r ipynb_requirements.txt


## Step 4 ALT: Manually Install Dependencies (Hard Way)

To manually install packages using pip, you can run the following command after activating your virtual environment:

pip install altgraph==0.17.4 appnope==0.1.4 asttokens==3.0.0 comm==0.2.2 contourpy==1.3.1 cycler==0.12.1 debugpy==1.8.13 decorator==5.2.1 executing==2.2.0 fonttools==4.56.0 imageio==2.37.0 ipykernel==6.29.5 ipython==9.0.2 ipython_pygments_lexers==1.1.1 ipywidgets==8.1.5 jedi==0.19.2 joblib==1.4.2 jupyter_client==8.6.3 jupyter_core==5.7.2 jupyterlab_widgets==3.0.13 kiwisolver==1.4.8 macholib==1.16.3 matplotlib==3.10.1 matplotlib-inline==0.1.7 nest-asyncio==1.6.0 numpy==2.2.4 opencv-python==4.11.0.86 packaging==24.2 parso==0.8.4 pdf2image==1.17.0 pexpect==4.9.0 pillow==11.1.0 platformdirs==4.3.7 prompt_toolkit==3.0.50 psutil==7.0.0 ptyprocess==0.7.0 pure_eval==0.2.3 Pygments==2.19.1 pyinstaller==6.12.0 pyinstaller-hooks-contrib==2025.2 pyparsing==3.2.3 pytesseract==0.3.13 python-dateutil==2.9.0.post0 pyzmq==26.3.0 scikit-learn==1.6.1 scipy==1.15.2 setuptools==78.0.2 six==1.17.0 stack-data==0.6.3 threadpoolctl==3.6.0 tornado==6.4.2 traitlets==5.14.3 wcwidth==0.2.13 widgetsnbextension==4.0.13

## Step 5: Download Programs and Try Them Out



