Moonshine
=========

**Moonshine** is a dark color-scheme for IntelliJ IDEA 12.x based on "Dracula", just less bloody.

Status
------
This section lists the languages (and other sections under `Preferences | Editor | Colors & Fonts`)
for which the syntax highlighting has been adapted:

+ General
![preview](https://raw.github.com/PhannGor/moonshine/master/preview/general.png "General")
+ Console
![preview](https://raw.github.com/PhannGor/moonshine/master/preview/console.png "Console")
+ Java
![preview](https://raw.github.com/PhannGor/moonshine/master/preview/java.png "Java")
+ Android Logcat
![preview](https://raw.github.com/PhannGor/moonshine/master/preview/logcat.png "Android LogCat")
+ Diff
![preview](https://raw.github.com/PhannGor/moonshine/master/preview/diff.png "Diff")
+ File Status

Installation
------------
### Option 1: Install using "Import Settings..."

1. Go to `File | Import Settings...` and specify the `moonshine` directory. Clik `OK` in the dialog that appears.
2. Restart IntelliJ IDEA
3. Go to `Preferences | Editor | Colors & Fonts` and select one of the new color themes.

### Option 2: Manual installation

1. Copy the `Moonshine.icls` file into your IntelliJ IDEA preferences color directory. It is typically in:  
  - Mac OS X:
      `~/Library/Preferences/IntelliJIdea12/colors`
  - Windows:
      `Documents and Settings/<user>/.IntelliJIdea12/config/colors`
2. Restart IntelliJ IDEA
3. Go to `Preferences | Editor | Colors & Fonts` and select one of the new color themes.

Notes
-----
This theme revolves around languages I work with on a daily basis. If you are using some of the more esoteric languages supported by IDEA, you may not have proper highlighting in their respective files. Also, a font in a theme may or may not be available on your platform in which case IDEA will default to something else; typically, any monospace font is an acceptable replacement.