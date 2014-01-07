SetupPC
=======
List of software, settings & plugins to install after the inevitable formatting & OS re-install

Software
==
####Sublime Text 3

* Emmet
  With [Package Control](http://wbond.net/sublime_packages/package_control):
  1. Run “Package Control: Install Package” command, find and install `Emmet` plugin.
  2. Restart ST editor (if required)
* SublimeLinter
  Installing

    **With the Package Control plugin:** The easiest way to install SublimeLinter is through Package Control, which can be found at this site: http://wbond.net/sublime_packages/package_control

  Once you install Package Control, restart ST2 and bring up the Command Palette (`Command+Shift+P` on OS X, `Control+Shift+P` on Linux/Windows). Select "Package Control: Install Package", wait while Package Control fetches the latest package list, then select SublimeLinter when the list appears. The advantage of using this method is that Package Control will automatically keep SublimeLinter up to date with the latest version.

  **Without Git:** Download the latest source from [GitHub](https://github.com/SublimeLinter/SublimeLinter) and copy the SublimeLinter folder to your Sublime Text "Packages" directory.

  **With Git:** Clone the repository in your Sublime Text "Packages" directory:

    git clone https://github.com/SublimeLinter/SublimeLinter.git

* Keyboard shortcut - build in chrome
  Tools -> Build System -> New Build System
    `{
        "cmd": ["C:\\Program Files (x86)\\Google\\Chrome\\Application\\Chrome.exe", "$file"]
    }`
  Save file as 'Chrome.sublime-build' (JSON FILE)
  Then set Chrome as the default from the list in Build system
####Node.js
####Bower
####Grunt
####Github
####WAMP
####Eclipse

* Android SDK
####GIMP
####VisualStudio201X

* DPack
* JSLint.NET for Visaul Studio
* Microsoft ASP.NET and Web Tools
* NuGet Package Manager
* Productivity Power Tools 2012
* Visual Studio Extensions for Windows Library for Javascript
* Web Essentials 2012
