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

🔧 Python Version

This project requires Python 3.13.2.

To make sure you’re using the correct version:

Check Your Current Version
Open a terminal and run:

python3 --version"

It should output:
Python 3.13.2

If not, install the correct version using pyenv:

Option 2: Install with pyenv

curl https://pyenv.run | bash

Then add this to your shell profile (.zshrc, .bashrc, or .bash_profile):

export PATH="$HOME/.pyenv/bin:$PATH"
eval "$(pyenv init --path)"
eval "$(pyenv virtualenv-init -)"

Now install Python 3.13.2:

pyenv install 3.13.2
pyenv local 3.13.2

This will ensure you’re using the correct version in this project folder.

Optional: Add .python-version

To lock the version using pyenv, include a .python-version file in the repo:

echo "3.13.2" > .python-version


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

## Step 4a: image_treat_3styles.ipynb Specific Installs

pip install numpy Pillow opencv-python 

## Step 4b: Manually Install Dependencies (Hard Way)

To manually install packages using pip, you can run the following command after activating your virtual environment:

pip install altgraph==0.17.4 appnope==0.1.4 asttokens==3.0.0 comm==0.2.2 contourpy==1.3.1 cycler==0.12.1 debugpy==1.8.13 decorator==5.2.1 executing==2.2.0 fonttools==4.56.0 imageio==2.37.0 ipykernel==6.29.5 ipython==9.0.2 ipython_pygments_lexers==1.1.1 ipywidgets==8.1.5 jedi==0.19.2 joblib==1.4.2 jupyter_client==8.6.3 jupyter_core==5.7.2 jupyterlab_widgets==3.0.13 kiwisolver==1.4.8 macholib==1.16.3 matplotlib==3.10.1 matplotlib-inline==0.1.7 nest-asyncio==1.6.0 numpy==2.2.4 opencv-python==4.11.0.86 packaging==24.2 parso==0.8.4 pdf2image==1.17.0 pexpect==4.9.0 pillow==11.1.0 platformdirs==4.3.7 prompt_toolkit==3.0.50 psutil==7.0.0 ptyprocess==0.7.0 pure_eval==0.2.3 Pygments==2.19.1 pyinstaller==6.12.0 pyinstaller-hooks-contrib==2025.2 pyparsing==3.2.3 pytesseract==0.3.13 python-dateutil==2.9.0.post0 pyzmq==26.3.0 scikit-learn==1.6.1 scipy==1.15.2 setuptools==78.0.2 six==1.17.0 stack-data==0.6.3 threadpoolctl==3.6.0 tornado==6.4.2 traitlets==5.14.3 wcwidth==0.2.13 widgetsnbextension==4.0.13

## Step 5: Add One of the .ipynb Files To Your Folder

https://github.com/epistemeepistemeepistemedoxadoxadoxa/ipynBook/blob/main/animation_stable.ipynb
https://github.com/epistemeepistemeepistemedoxadoxadoxa/ipynBook/blob/main/contact_sheet.ipynb
https://github.com/epistemeepistemeepistemedoxadoxadoxa/ipynBook/blob/main/image_treat_3styles.ipynb


## Step 6: Look for the Kernel Picker

A kernel is the computational engine that runs your code. Each virtual environment or Python interpreter can act as a different kernel.

<img width="250" alt="Screenshot 2025-03-26 at 7 00 24 PM" src="https://github.com/user-attachments/assets/41f39403-4d8d-49f1-911d-6cc134892cce" />
<img width="617" alt="Screenshot 2025-03-26 at 7 01 51 PM" src="https://github.com/user-attachments/assets/be51306f-236c-48f3-8933-cc4c8c587cae" />

## Step 7: Choose Your Virtual Environment

If you’ve already activated your venv, it should show up as something like:
Python 3.x.x ('venv': venv)
It'll also usually have a star  next to it. 

<img width="616" alt="Screenshot 2025-03-26 at 7 03 08 PM" src="https://github.com/user-attachments/assets/e076f650-a5e8-4d9b-bd03-654b3cf512bf" />
<img width="282" alt="Screenshot 2025-03-26 at 7 04 44 PM" src="https://github.com/user-attachments/assets/bdd6c60b-af80-443f-912b-269f024ca11c" />



# Part 3

## Run the program... 

# Once your venv is working, you'll be able to start the program by clicking "Run All"
<img width="424" alt="Screenshot 2025-03-26 at 7 10 18 PM" src="https://github.com/user-attachments/assets/f9f1fae4-6425-4c8c-8b11-ddcdff5c18fd" />


If your venv isn't setup yet, you'll see an error at the very bottom of the code.
<img width="1149" alt="Screenshot 2025-03-26 at 7 12 46 PM" src="https://github.com/user-attachments/assets/2ccfdb02-ae38-4673-98a5-64d49d332c2d" />

If I'm missing a package, I'll usually Google "pip install *name*".
It'll usually take me to https://pypi.org/ where I can get the correct name...
I can also paste the error into an LLM

## Feel free to edit the code's programs. The best one for easy editing will be: image_treat_3styles.ipynb
https://github.com/epistemeepistemeepistemedoxadoxadoxa/ipynBook/blob/main/image_treat_3styles.ipynb

Here are some examples of image treatments you might make:
https://www.are.na/theo-france-haggi-iaj8chvcad8/potential-effects

In the class <i>ImageStyleTransformer</i> all of the image effects are stored... You can paste the entire section of code or just snippets into an LLM along with another effect that you'd to try and see if you can add it...
To find specific classes in my code, I'll use Command + F and paste the class name.

## Example: ChatGPT
 
Prompt
"I'd like to add a fisheye effect to this program... How can we do that?"

<img width="1324" alt="Screenshot 2025-03-26 at 7 22 10 PM" src="https://github.com/user-attachments/assets/c0989a09-99b5-4d1f-bde3-e69cc514d1e3" />

ChatGPT
"To add a fisheye effect to your program, we can create a new style (e.g. “Style 6: Fisheye Distortion”) and apply a remapping transformation to the image using OpenCV."

Here’s how you can implement the fisheye effect:

## 🔧 Step 1: Add the new style option

In both initialize_parameters and create_style_selector, add:

"Style 6: Fisheye"

## 🧠 Step 2: Create a function to apply fisheye distortion

Add this method to your ImageStyleTransformer class:

def apply_fisheye_style(self, img):
    img_np = np.array(img)
    height, width = img_np.shape[:2]

    # Normalize coordinates to [-1, 1]
    x = np.linspace(-1, 1, width)
    y = np.linspace(-1, 1, height)
    xv, yv = np.meshgrid(x, y)
    r = np.sqrt(xv**2 + yv**2)

    # Fisheye distortion factor
    k = 0.5  # Increase for more distortion

    # Distortion function
    theta = np.arctan(r)
    r_distorted = np.tan(theta * (1 + k * r**2))

    # Avoid division by zero
    r[r == 0] = 1e-6
    scale = r_distorted / r

    map_x = (xv * scale + 1) * (width - 1) / 2
    map_y = (yv * scale + 1) * (height - 1) / 2

    # Remap using OpenCV
    map_x = map_x.astype(np.float32)
    map_y = map_y.astype(np.float32)

    distorted = cv2.remap(img_np, map_x, map_y, interpolation=cv2.INTER_LINEAR)
    return Image.fromarray(distorted)

🚀 Step 3: Hook it up in apply_style

Inside your apply_style method, add:

elif "Style 6" in style:
    img = self.apply_fisheye_style(img)

✅ Optional: Add a slider to control distortion strength

In initialize_parameters, when "Style 6" is selected:
self.param_controls["fisheye_strength"] = self.create_slider("Fisheye Strength", 0, 100, 50)

Then modify the distortion strength in apply_fisheye_style:
k = self.param_controls.get("fisheye_strength", tk.IntVar(value=50)).get() / 100

Let me know if you’d like a reverse fisheye, a circular vignette, or a custom center to the distortion..... 



