JSX-JS-Sublime-Text-3
=====================

A JSX to JS compliler for Sublime Text 3

Description

A compiler from JSX to JS, for ReactJS based apps. 
Read more here:
http://facebook.github.io/react/docs/jsx-in-depth.html
http://facebook.github.io/react/jsx-compiler.html

Prerequisites

Requires Node & React-tools library.

Step by step:

Install NodeJS library

OS X & Linux: Install node from http://nodejs.org/

Install React-tools

Do npm install react-tools
Reference: https://www.npmjs.org/package/react-tools

Install JSX-JS plugin

With the Package Control plugin (recommended)

The easiest way to install this package is through Package Control.

Download and install the Package Control Plugin. Follow the instructions on the website.

Open the command panel: Control+Shift+P (Linux/Windows) or Command+Shift+P (OS X) and select 'Package Control: Install Package'.

When the packages list appears type 'JSX-JS' and you'll find the JSX-JS Build System. Select to install it.

Now you can compile your JSX files! Launch your build with Control+B (Linux/Windows) or Command+B (OS X).

Enjoy your coding =)

Using the build

After installing the package you will find a new option in Tools > Build system of your Sublime menu: JSX-JS

By default your .jsx files will be builded using the JSX-JS build.

And remember, always you can launch the selected build with Control+B (Linux/Windows) or Command+B (OS X).

Recommendations


I recomend the plugin SublimeOnSaveBuild. Just save your JSX files and transform them into JS!
If you want to change the default folder of your generated JS files into another one, you can edit the build:

Exemple: Save your JS files into a javascripts folder: "cmd": ["jsx", "-w", "-x", "jsx", "--no-cache-dir", "${file_path}", "./dist/javascripts"],

Author

Created by Vasanth Gopal.
