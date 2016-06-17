# Node.js Portable

A DOS Batch script to make [Node.js](http://nodejs.org/) portable on Windows systems.

# Forked

Based on the script of @crazy-max and adapted for full-automatic processing support.

## Requirements

* Have an Internet connection (for installation when downloading the application).
* [WSH (Windows Script Host)](http://support.microsoft.com/kb/232211) : Open a command prompt and type ``cscript`` to check.

## Usage

* Put the ``nodejs-portable.bat`` in an empty directory for a new nodejs installation.
* Run ``nodejs-portable.bat`` manually and step through installation.
* OR run ``nodejs-portable.bat`` with the following three parameters to install nodejs automatically:

``nodejs-portable 2 <version> <architecture>``

* whereas <version> should be replaced by a vaild nodejs version 
* and <architecture> should be replaced by x64 or x86 according to the target system's architecture

e.g. ``start cmd /C nodejs-portable.bat 2 4.4.4 x64``
