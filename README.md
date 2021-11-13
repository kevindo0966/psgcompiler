
<p align="center">
  <img src="https://raw.githubusercontent.com/PySimpleGUI/PySimpleGUI/master/images/for_readme/Logo%20with%20text%20for%20GitHub%20Top.png" alt="Python GUIs for Humans">
  <h2 align="center">psgcompiler</h2>
  <h2 align="center">A PySimpleGUI Application</h2>

</p>

"Compile" your Python programs into an EXE for Windows, an APP for Mac, and a binary for Linux


![](https://raw.githubusercontent.com/PySimpleGUI/psgcompiler/main/screenshot_for_readme/psgcompiler_screenshot.jpg?token=ALAGMY3Z33WHFX3RTFXEZ73BTEUPO)



## Installation

### Old-school Straight Pip

pip install psgcompiler

### pip via `python -m pip` the python recommended way

#### If `python` is your command

python -m pip install psgcompiler

#### If `python3` is your command

python3 -m pip install psgcompiler

## Usage

Open a command window and type:   

`psgcompiler`   

## `pyinstaller` Back-end with a `PySimpleGUI` Front-end

The psgcompiler is a front-end GUI for the fantastic `pyinstaller` program.  This program transforms your Python project into an executable that you can distribute to friends, family members, colleagues, the public, other developers, ...  Anyone that does not have Python installed on their machine will be able to run your program after you've turned it into a binary executable.

PySimpleGUI users in particular will greatly benefit from the `psgcompiler` as you'll be able to distribute "Windows Programs".  Most likely no one will know you're using Python.  On Windows, you can create a single EXE file.  This is in fact the default.  After converting, you'll be left with a single EXE file.

## A Multitude Of Options

`pyinstaller` has a sh*t-ton of options!  Unlike the primitive EXE Maker that the PySimpleGUI project created, the `psgcompiler` exposes all of the options in an easy to use way.

## A Simple EXE

If your program is relatively simple, then you only need to supply the name of your Python file, and an optional icon file.

Here is an example session showing only the .pyw file and the .ico file being supplied.  


![](https://raw.githubusercontent.com/PySimpleGUI/psgcompiler/main/screenshot_for_readme/psgcompiler_gif.gif?token=ALAGMYYG5EDJ3FH7GCCWLV3BTEUSE)


## Additional Back-ends

Currently in the works is support for additional back-ends.  `cx_freeze` is up next.

## Create a Shortcut To This Program

If you're a Windows user, then use the [`psgshortcut` application](https://pypi.org/project/psgshortcut/) to make a shortcut to this program so that you can then put on your desktop or pin to your taskbar (or any  other use that stops the need to type `psgresizer` ever again).


## License

Licensed under an LGPL3 License  
Copyright 2021

## This PySimpleGUI Application Was Designed and Written By

[Tanay Findley](https://github.com/Chr0nicT) as part of [**The PySimpleGUI Project**](http://www.PySimpleGUI.com)


## Contributing

Like the PySimpleGUI project, this project is currently licensed under an open-source license, the project itself is structured like a proprietary product. Pull Requests are not accepted.

## Copyright

Copyright 2021 PySimpleGUI
