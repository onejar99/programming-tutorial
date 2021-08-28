# How to Install Python on Windows

A simple guide to installing Python on Windows.

## Outline

* Step 1. Installing Anaconda.
* Step 2. Verifying Python installed successfully.
* Step 3: Installing and running Jupyter Notebook.
* Step 4: Running a Python Hello World example.


## Step 1: Installing Anaconda.

Anaconda is a popular open-source data science toolkit that includes Python runtime environments and package management tools. Installing Anaconda is recommended to manage your Python environments easier, instead of installing Python directly.

> **Note: Suggest that 5GB disk space reserved for installing Anaconda.**

1. Go to the [Anaconda official site](https://www.anaconda.com/products/individual-d#Downloads) and download the installer dependent on your laptop OS.

![](https://i.imgur.com/U2OrGJQ.png)

2. Execute the installer.

![](https://i.imgur.com/6sj970V.png)

3. Follow the default setup and complete the installation.

![](https://i.imgur.com/jH00BwH.png)


## Step 2. Verifying Python installed successfully.

1. Type "Anaconda" in Windows search, find the "Anaconda Prompt (anaconda3)" application and execute it.

![](https://i.imgur.com/NniqFJZ.png)

2. Type following command to print Python version:

```
$ python --version
```

![](https://i.imgur.com/xHJpBGs.png)


## Step 3: Installing and running Jupyter Notebook.

Jupyter Notebook offers a web interactive interface for executing your Python code.

1. Install Jupyter Notebook by anaconda command:

```
$ conda install jupyter
```

2. Launch Jupyter Notebook:

```
$ Jupyter Notebook
```

![](https://i.imgur.com/r8LU5dF.png)

3. A web page will be opened automatically with your default browser.

![](https://i.imgur.com/xXPzeBO.png)


## Step 4: Running a Python Hello World example.

1. Add a new file.

![](https://i.imgur.com/pohbkNs.png)

2. The default file name is "Untitled". You can rename it.

![](https://i.imgur.com/9IhOj9I.png)

3. Type Python code into the Jupyter Notebook cell and run it.

```python
print("hello world")
```
![](https://i.imgur.com/h2RuNAw.png)

![](https://i.imgur.com/toDTWXc.png)
