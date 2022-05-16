# Installing

- Place this folder in ~/.config/tex/
- Copy "doc" to your local bin path, or add it to path
- Run "doc new" in an empty folder

# Requirements

doc require mupdf and inotifywait to be installed. Possibly latex dist too if
you haven't figure that out yet

# doc options

doc [action] [document]

**defaults**

document defaults to "document.tex" if left empty

action defaults to "build" if left empty

**actions**

- new - create new document
- edit - edit document in folder
- build - build document in folder
- clean - remove temp files and output pdf
- view - view pdf using mupdf
- watch - continuously build document as it's saved
