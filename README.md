# wats1030-manipulating-text
An assignment based on editing text using command line text editors.

For this assignment, you must use three different text editors from the command
line of your Digital Ocean Droplet. (You should still have the Droplet from the
previous assignment. The instructions here will assume you are using an Ubuntu
14.04 server to complete this work.)

## Pre-Requirements

In order to complete the Basic Requirements below, you will need to verify that
all three editors are available to you. For this assignment you will need to
complete the basic requirements in each of the three editors.

### Nano
Nano is generally considered the easiest command line editor to use. There are
only a few commands available and it is based on the editor that was
included with the popular email software, Pine (which people used to use on
Unix servers to check their email).

To check for `nano`, try to run it:

`nano`

If `nano` is not there, you can install it by running:

`apt-get install nano`

### Emacs
Emacs was created with an eye towards "editor macros" (hence the name), and it
remains strong with many macros available to tie emacs in to all sorts of
systems and processes. It is a very flexible editor, with an idiosyncratic
interface that is not like any other application.

To check for `emacs`, try to run it:

`emacs`

If `emacs` is not there, you can install it by running:

`apt-get install emacs`

### Vi
Vi is a "mode-based" editor, meaning that it starts looking at files in "view"
mode and you must switch into "interactive" mode to edit them. Vi is also designed
to keep your fingers on the home row as much as possible, and fans of Vi love
that they can use all sorts of keyboard shortcuts to navigate precisely within
files. Like Emacs, Vi is not at all like any other text editor you've probably
used.

Vi should be included in your system already, but you can check for it and
install it just like the other packages. Check for it by trying to run it:

`vi`

If `vi` does not work, then install it:

`apt-get install vi`

## Basic Requirements
Once you have all of your editors available on your Droplet, you can begin
working on the tasks outlined below. There are three directories in this repo:

```
emacs/
nano/
vi/
```

You will work through this set of tasks in each of the three directories,
allowing you to experience the differences between these three editors. Files
have been copied into each directory already, so you have fresh files to work
with in each directory. As you work through the tasks, be sure you are editing
files in the correct directory.

* Create a new file called `unix_philosophy.txt` and type in the text from the
`unix_philosophy.pdf` file.

* Open the file `power_of_unix.html` and remove all of the HTML tags. Save the
file with a new filename: `power_of_unix.txt`. (Hint: You can zap those pesky
comments with a "delete line" command in some editors...)

* Open the file `gancarz_unix_philosophy.txt` and correct the typos of
`beautiflu` and `effishingly`. Save and close the file when you're done.

* Open the file `17_rules.txt` and remove all of the bracketed footnote numbers
left over from the copy/paste of text. (The footnote numbers look like this:
`[12]`. They are sprinkled throughout the file. You could probably use some
kind of search or find function to get them all...)

* Update `example.httpd.conf` to have the following settings:

```
<VirtualHost *:80>
DocumentRoot /www/unix
ServerName www.unix.com
</VirtualHost>

<VirtualHost *:80>
DocumentRoot /www/linux
ServerName www.unix.org
</VirtualHost>
```

* In the short story "The Machine Stops" (contained in the
`the_machine_stops.txt` file), the main characters are Vishta and Kuno. How many
times does the word "Vishta" show up in the short story? How many times does the
word "Kuno" show up in the short story? (Type your answers here.)

## Stretch Goals

* Play Tetris in Emacs.
* How do you turn on line numbering in Vi? Emacs?
* Explore the Emacs file browser mode.
