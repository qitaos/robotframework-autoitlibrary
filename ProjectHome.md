# AutoItLibrary #

## Overview ##

AutoItLibrary is a Python keyword library that extends [Robot Framework](http://www.robotframework.org/) by providing keywords based on the COM interface to [AutoIt](http://www.autoitscript.com/autoit3/index.shtml), a freeware tool for automating the Windows GUI.

In order to do screenshots, the AutoItLibrary requires the Open Source Python
Image Library tool [PIL](http://www.pythonware.com/products/pil/).

## News ##

  * _2010-04-23_ **[AutoItLibrary 1.1](http://code.google.com/p/robotframework-autoitlibrary/wiki/ReleaseNotes)** released
  * _2009-11-17_ **AutoItLibrary 1.0** released


## Prerequisites ##

  * Install [Python](http://www.activestate.com/activepython/) and [Robot Framework](http://www.robotframework.org/)
  * If you are not using [ActivePython](http://www.activestate.com/activepython/), which comes with the Python for Windows extensions such as win32com, then you'll need to install Mark Hammond's [Python for Windows Extensions](http://starship.python.net/crew/mhammond/win32/).
  * If you want AutoItLibrary to do screen captures then
    * Install the Open Source Python Image Library tool [PIL](http://www.pythonware.com/products/pil/)
  * Download the latest [AutoItLibrary](http://code.google.com/p/robotframework-autoitlibrary/downloads/list) release

## Installation ##

AutoItLibrary installs its own files and the required parts of AutoIt.  To install, unzip the downloaded source release file into a temporary directory on your PC, open a command window in that directory and type:

> python setup.py install

**NOTE:** In Windows Vista and Windows 7 you must do this installation as Administrator!

The installation creates the folder:

> C:\RobotFramework\Extensions\AutoItLibrary

on your PC and puts various files into this directory folder.


## Documentation ##

AutoItLibrary documentation is installed by the installation process into

> C:\RobotFramework\Extensions\AutoItLibrary\AutoItLibrary.html

The AutoItX documentation is also installed into this folder as AutoItX.chm.
You can also view the [Keyword Documentation online](http://robotframework-autoitlibrary.googlecode.com/svn/tags/robotframework-AutoItLibrary-1.0/doc/AutoItLibrary.html).


## Tests ##

The AutoItLibrary installer puts a suite of self-tests here:

> C:\RobotFramework\Extensions\AutoItLibrary\tests

To run these tests, which exercise the Windows Calculator GUI, run the
RunTests.bat file in the above folder.