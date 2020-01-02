# mgyky-clang-format

My .clang-format file for using with Objective-C projects.

# How to use with latest XCode

* download latest release of XcodeClangFormat plug-in from https://github.com/mapbox/XcodeClangFormat
* then, go to System Preferences → Extensions, and make sure that clang-format in the Xcode Source Editor section is checked
* edit how you wish and put your .clang-format file in root project directory
* open XcodeClangFormat.app and show the custom path
* add your keyboard shortcut: open System Preferences, click on Keyboard, and switch to the Shortcuts tab. In the list on the left, select App Shortcuts, then hit the + button. Select Xcode, enter Format Source Code, and define a shortcut of your liking
* Then, use the Format Source Code command in Xcode's Editor menu or use your shortcut like line above
* tested on: XCode8, XCode9, XCode10, **XCode11**, **macos Catalina** 10.15.2 (19C57)
* Enjoy it! 🎉🎉🎉
* ⭐️😉


# Installing clang-format

To install clang-format for your macOS use command line below:

```
brew install clang-format
```

checked again, you'll I found an empty clang-format file in your HOME directory.

If your clang-format application is already installed, you can place your clang-format file at your HOME directory. That will effect all project which hasn't own a ".clang-format" file.


# Testing your clang-format on the Terminal

To testing on a file from terminal use command line below:

```
clang-format -i *.m
```





