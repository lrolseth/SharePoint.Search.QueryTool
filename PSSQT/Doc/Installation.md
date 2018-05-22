﻿Installation
============

If you run Windows 10 or have WMF 5 installed (https://www.microsoft.com/en-us/download/details.aspx?id=50395), you can very easily install it by running the command 

`Install-Module -Name PSSQT`

directly in PowerShell, and it will be installed from the PowerShell gallery. (https://www.powershellgallery.com/packages/PSSQT/)

(There is no need to download the search query tool zip file, if all you want is to install the PowerShell module)

Once it has been installed on your system, you load it by running the command

`Import-Module PSSQT`

It exports only one cmdlet at the moment: **Search-SPIndex**

It is primarily a tool for scripting and testing. E.g. automated testing of result sets against a golden set etc.

If you downloaded the search query tool from CodePlex and extracted the zip file, you can load the module directly by running the command 

`Import-Module <path to search query tool>\psmodules\PSSQT.psd1`

E.g:

`Import-Module C:\SearchQueryTool\psmodules\PSSQT.psd1`

