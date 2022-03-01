# Getting Started
This chapter will help you to get started with Robot Framework.

So basically how to
- install Python
- install Robot Framework
- install an IDE and Extensions for code-completion and debugging

<iframe width="560" height="315" src="https://www.youtube.com/embed/1jdjogCnsDk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Install Python

### Windows

1. Download [Python](https://www.python.org/downloads/)
2. Install it
3. Open a command prompt by pressing `Ctrl` + `Shift` + `C` and type `python`
4. You should see the Python prompt

### Linux

1. Download [Python](https://www.python.org/downloads/)
2. Install it
3. Open a terminal `Ctrl` + `Shift` + `T` and type `python`
4. You should see the Python prompt

### How to use a Virtual Environment

Python allows you to install modules via `pip`.  
By default, those modules are installed in the global Python environment.

But especially when working on multiple projects, it is more convenient to have a separate Python environment for each project with all the modules installed.  
To separate the global Python environment from the project environment, you can use a virtual environment.

1. Open a command prompt and create a new folder for your project
    1. Windows: `mkdir <project_name>`
    2. Linux: `mkdir <project_name>`
2. Change to the new folder
    1. Windows: `cd <project_name>`
    2. Linux: `cd <project_name>`
3. Type `python -m venv venv` to create a virtual environment
4. Activate the virtual environment
    1. Windows: `venv\Scripts\activate`
    2. Linux: `source venv/bin/activate`

Once the virtual environment is created, you can install modules in it using `pip`:

    pip install robotframework

## Install Robot Framework

## Install IDE and Extensions

### PyCharm

### Visual Studio Code

#### RoboCorp Robot Framework Extension

#### RobotCode Extension

### RIDE

### Recommendations

#### Managing Dependencies
