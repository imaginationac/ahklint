# ahklint.ahk

## A static analysis program for [Autohotkey](http://www.autohotkey.com) 
programs, written in Autohotkey.

Like other lint programs before it, ahklint will hurt your feelings, but will be worth it.

I do not profess to an Autohotkey expert. In fact I'm very new at this, but I have noticed
enough things to know that certain styles of writing scripts can be done to prevent errors.

This is currently *very* experimental. Use at your own risk.

### How to use

Drag a script over the ahklink.ahk file in Explorer or pass the file as the 
first parameter to the script.

### Design

Modular: A set of functionality to test should be broken into a seperate module, 
in a seperate file. This allows granular controls of tests if need be. For now,
I'm not going to bother, but if I write a second module, that'll be happening.

### How to help

1. Test the script
2. Fork, hack, push, pull request
3. Use the issue tracker to report bugs, make feature requests, and discuss changes.
