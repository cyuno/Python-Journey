# Python-Journey
For windows 10

In Control Panel uninstall programs

uninstall python 2.7

uninstall python 3.5

uninstall old python launcher

Explorer Directory

delete python 2.7 folder

delete python 3.5 folder

Downloaded python 3.6.0

Go to Environment Variables App.

Edit both user path and system path

Delete paths to old python versions.

In windows 10, the python download will go to AppData\Local\Python36 etc.

Copy Python36 file and paste it off root C:\

Restart your machine

Edit both local and system paths for Python36:

C:\Python36

C:\Python36\Scripts

C:\Python36\Tools\scripts

You should be able to run pip install virtualenv now

follow the instructions from https://www.packtpub.com/mapt/book/All%20Books/9781787120761/1/ch01lvl1sec14/Installing+Python

c:\Users\yourusername\PythonStuff\Python-Journey-from-Novice-to-Expert-2016-Packt\Module 1

mkdir learning.python

cd learning.python

c:\Users\yourusername\PythonStuff\Python-Journey-from-Novice-to-Expert-2016-Packt\Module 1\learning.python>pip install virtualenv

Collecting virtualenv
  Downloading virtualenv-15.1.0-py2.py3-none-any.whl (1.8MB)
  
    100% |████████████████████████████████| 1.8MB 310kB/s
    
Installing collected packages: virtualenv

Successfully installed virtualenv-15.1.0

c:\Users\yourusername\PythonStuff\Python-Journey-from-Novice-to-Expert-2016-Packt\Module 1\learning.python>virtualenv -p

\Python36\python.exe .lpenv

Running virtualenv with interpreter C:\Python36\python.exe

Using base prefix 'C:\\Python36'

New python executable in c:\Users\yourusername\PYTHON~1\PYTHON~1\MODULE~1\LEARNI~1.PYT\LPENV~1\Scripts\python.exe
Installing setuptools, pip, wheel...done.

c:\Users\yourusername\PythonStuff\Python-Journey-from-Novice-to-Expert-2016-Packt\Module 1\learning.python>.lpenv\Scripts\activate

(LPENV~1) c:\Users\yourusername\PythonStuff\Python-Journey-from-Novice-to-Expert-2016-Packt\Module 1\learning.python>where python

c:\Users\yourusername\PythonStuff\Python-Journey-from-Novice-to-Expert-2016-Packt\Module 1\learning.python\.lpenv\Scripts\python.exe

C:\Windows\System32\python

C:\Python36\python.exe

C:\Users\yourusername\AppData\Local\Programs\Python\Python36\python.exe

(LPENV~1) c:\Users\yourusername\PythonStuff\Python-Journey-from-Novice-to-Expert-2016-Packt\Module 1\learning.python>python

Python 3.6.0 (v3.6.0:41df79263a11, Dec 23 2016, 08:06:12) [MSC v.1900 64 bit (AMD64)] on win32

Type "help", "copyright", "credits" or "license" for more information.

>>> exit()

(LPENV~1) c:\Users\yourusername\PythonStuff\Python-Journey-from-Novice-to-Expert-2016-Packt\Module 1\learning.python>

To deactivate:

(LPENV~1) c:\Users\yourusername\PythonStuff\Python-Journey-from-Novice-to-Expert-2016-Packt\Module 1\learning.python>deactivate


