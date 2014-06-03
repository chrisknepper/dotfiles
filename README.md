Chris Knepper's dotfiles (for OSX)
========

These are my dotfiles. Currently used by me on OSX 10.8.X, your mileage with Linux may vary.

##man dotfiles | grep 'wat'

Dotfiles are placed in one's home directory, also known as `~/` on Unix-based operating systems. They can alter and improve the functionality of one's terminal emulator (in my case, `Terminal.app`) and its shell (in my case, `bash`).

When moving to a new system, backed-up dotfiles are crucial in reducing reconfiguration time. You're gonna be spending enough time installing the Adobe Creative Suite, so save some time and save your dotfiles.

Since Git is cool, you can manage changes a multitude of ways. The caveman way is to `cp` the files manually when you need to. My favorite is to `ln -s` the files into my home directory. You could even use the Finder to drag and drop, if you're into that sort of thing. Only if you're showing hidden files already, though.

##Inspiration

My dotfiles are inspired by the following:

* [Mathias Bynens' Dotfiles (bretty neat)](https://github.com/mathiasbynens/dotfiles)
* [Several of the scripts found in this 4chan thread (archived)](http://rbt.asia/g/thread/42131516)

##License

* MIT, a.k.a. free as free can be, a.k.a. do whatever you want. See the `LICENSE` file.