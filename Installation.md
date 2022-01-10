# __Jupyter Notebook Installation__

## 1. Linux

Most Linux distros come equipped with Python. Here we will assume a Debian based distro, primarily Ubuntu. We will be primarily using Python 3 in these sessions to it imperitive that you have it properly set up so you can follow along with the sessions. To check you Python version, run the following command in your bash shell:
```bash
python3 --version
```
If this shows a python version of the form ```3.x.x```, congrats! You're done here.</br>
Otherwise install Python 3 with the following command.
```bash
sudo apt install python3
```
You can also set your default Python version to be Python 3 to avoid invoking ```python3``` instead of ```python``` using the following command:
```bash
sudo apt install python-is-python3
```

Next, install __Jupyter Notebook__ using the following _pip_ command.
```bash
pip3 install notebook
```
You can run Jupyter Notebook from your terminal using the following command.
```bash
jupyter-notebook
```

## 2. Windows

Head over to [anaconda.com](https://www.anaconda.com/) and install the latest version of Anaconda. Make sure to download the “Python 3.9 Version” for the appropriate architecture.

To install Jupyter using Anaconda, just go through the following instructions:

Step 1: Launch Anaconda Navigator

Step 2: Click on the Install Jupyter Notebook Button

Step 3: Beginning the Installation

Step 4: Finished Installation

Step 5: Launch Jupyter

## 3. MacOS

Make sure you have __Homebrew Package Manager__ installed on your system. In case you do not, follow this [resource](https://www.geeksforgeeks.org/download-and-install-python-3-latest-version/#macos) for Homebrew installation.

Install Python 3.
```bash
brew install python3
```

Check if pip3 and python3 are correctly installed.
```bash
python3 --version
pip3 --version
```

Upgrade your pip to avoid errors during installation.
```bash
pip3 install --upgrade pip
```

Enter the following command to install Jupyter Notebook using pip3.
```bash
pip3 install jupyter
```

## 4. Google Colab

OR if you want to avoid all the hassle of installing Jupyter Notebook, you can use Google Colab. 

Just open up your Google Drive go to _New_ and create a new Google Colaboratory Notebook.

# Library Installation
Usually Python 3 ships with NumPy and Matplotlib. But in case you don't have them, you can install them using the following commands:
```bash
pip3 install numpy
pip3 install matplotlib
```