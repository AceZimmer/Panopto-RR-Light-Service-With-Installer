# Panopto-RR-Light-Service-With-Installer
Panopto Remote Recorder Light Button Service

## License
Copyright (c) 2017 Panopto, Swivl, and University of Washington

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Code maintenance

* All files except described below are written and maintained by Panopto.
* PanoptoRRLightService/Delcom/DelcomDLL.dll is provided and maintained by Delcom.
* Files in PanoptoRRLightService/SwivlChico are provided and maintained by Swivl.
    * Please contact Swivl support about Swivl device and the code specific to Swivl.
* Files in PanoptoRRLightService/Serial are provided by the courtesy of University of Washington. See README.console.md for more informaiton.
    * Panopto may not support this part of the code. If you see any issue, open an issure report on GitHub. The author may respond it, although there is no gurantee.

## Release
Installer is available from [release page]( https://github.com/Panopto/Panopto-RR-Light-Service-With-Installer/releases).

## Build environment
You may build the binary and installer from this source code with the following tools. If you need to create a new version, update the version number both in AssemblyInfo.cs and Product.wxs.

* Visual Studio 2015
* WiX Toolset 3.10
* .NET framework 4.5
