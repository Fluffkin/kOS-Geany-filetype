# kOS-Geany-filetype
A crude syntax highlighter for kOS scripts in Geany

# Install:
Put the filetypes.kOS.conf file in the relevant geany directory.
On windows: %appdata%\Roaming\geany\filedefs

Edit the Geany filetype_extensions.conf file to include:
[Extensions]
...
kOS=*.ks;

[Groups]
...
Script=Graphviz;kOS;

# Notes:

It's far from perfect, for one thing I can't figure out how to make it case insensitive, so it only picks up lowercase code.
On the other hand, it's a lot better than nothing.
Advice / hints / tips / improvements welcomed.
Oh and "do what you like with it" license applies.
