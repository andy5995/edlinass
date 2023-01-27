# edlinass

Command line editor assistant that can make it easier to edit a command line
you want to reuse.

# Usage

Copy or install the script to a location in your path. The next time you have
a long command line you want to edit, press the up-arrow key to show the
command. Copy it, then run `edlinass`. A text editor will open. Paste in the
command, then edit (repeat as needed). When you save and exit, the command
will run.

`edlinass` reads the 'EDITOR' environmental variable by default. You can
change the default editor by editing the script, or declaring it at runtime:

    EDITOR=nano edlinass

Hint: Don't set the editor to a GUI application or things will become far more
complicated than you can possibly imagine.

## License

[Public Domain](https://unlicense.org/)



