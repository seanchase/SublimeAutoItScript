# AutoItScript - Syntax Package for Sublime Text 2/3
AutoItScript AU3 language package for SublimeText including syntax highlighting, comments toggling, snippets, build systems for run and compile, and Tidy command.

For the build systems and Tidy command, if you have a non-default installation you will need to set your specific path to AutoIt3.exe, Aut2Exe.exe, and Tidy.exe in a file named AutoIt.sublime-settings in your User folder. You can access these settings file from the Menu Preferences>Package Settings>AutoIt. You should make a copy of "AutoIt Settings - Default" at "AutoIt Settings - User" since then your settings file in your User folder will not get overwritten when this package updates.

## Key Bindings
If you have the default Sublime keybindings intact, then:
* {Ctrl+B} will run the current file (with AutoIt3.exe)
* {Ctrl+Shift+B} will compile the current file (with Aut2Exe.exe)
* {Alt+T}{T} will invoke Tidy on the current file (with Tidy.exe).

## Credits
* Syntax rules: http://sublime-text-community-packages.googlecode.com/svn/pages/AutoIt.html
* Snippets: http://www.autoitscript.com/forum/topic/148016-sublimetext/page-3#entry1080276
