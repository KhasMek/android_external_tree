TREE FOR ANDROID
---

[Original Source](http://mama.indstate.edu/users/ice/tree/src/tree-1.7.0.tgz)

The Android port of tree removed the dependency on langinfo.

There is a patch file for future versions. This file can be regenerated using:
~~~shell
diff -crB orig src > Android.patch
~~~
Patch the source with the follow command:
~~~shell
patch -p0 < Android.patch
~~~

---
INSTALLATION

This program has been tested with success being installed to /system/xbin, which will require root to install. This program will not work if installed to a shared storage such as internal, or external SD. YMMV

---
EXAMPLE:
~~~shell
shell@jflte:/ $ tree system/usr/share/

system/usr/share/
├── bmd
│   ├── RFFspeed_501.bmd
│   └── RFFstd_501.bmd
├── vim
│   ├── autoload
│   │   └── spacehi.vim
│   ├── colors
│   │   ├── default.vim
│   │   └── desert.vim
│   ├── doc
│   │   ├── editing.txt
│   │   ├── help.txt
│   │   ├── intro.txt
│   │   ├── motion.txt
│   │   ├── options.txt
│   │   ├── scroll.txt
│   │   ├── tags
│   │   └── term.txt
│   ├── filetype.vim
│   ├── ftoff.vim
│   ├── indent.vim
│   ├── indoff.vim
│   ├── plugin
│   │   └── matchparen.vim
│   ├── scripts.vim
│   └── syntax
│       ├── awk.vim
│       ├── c.vim
│       ├── conf.vim
│       ├── config.vim
│       ├── context.vim
│       ├── cpp.vim
│       ├── css.vim
│       ├── diff.vim
│       ├── doxygen.vim
│       ├── dtd.vim
│       ├── gitcommit.vim
│       ├── help.vim
│       ├── html.vim
│       ├── java.vim
│       ├── javascript.vim
│       ├── logcat.vim
│       ├── lua.vim
│       ├── manual.vim
│       ├── markdown.vim
│       ├── pod.vim
│       ├── sh.vim
│       ├── syncolor.vim
│       ├── synload.vim
│       ├── syntax.vim
│       ├── vb.vim
│       ├── vim.vim
│       └── xml.vim
└── zoneinfo
    └── tzdata

8 directories, 47 files
~~~
