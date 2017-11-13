# Img2dot
Turn picture into characters using braille system
# Requirments
* python (python 3 would be preferable)
* numpy
* pillow
# Usage
In terminal, run:

`python <path-to-python-file> <path-to-image>`

or:

`python <path-to-python-file> <path-to-image> [<path-to-text-file>]`

Recommend using small pitures or doing some edits on the picture before turn it into dots.

It works fine with color pictures. Not supporting transparency.

If you ever get an error with location then open img2dot.py and change the dirpath to your folder in which img2dot.py is.
# Known issues
If you use this in `command run` on Windows, you will only get a whole bunch of \xxxx characters, what a shame. But worry not, it's fine if you export them to a file.

However, `notepad` can't read that file. Open it with `notepad ++` or the like. What a shame again. Yes, I'm looking at you, Windows.
# Demo
```
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠠⠶⠾⠀
⠀⠀⠀⠀⠀⠀⠀⠤⠤⠤⠀⠀⠀⠀⠠⠤⠤⠄⠀⠀⠀⠀⠀⠀⠠⠾⠿⠿⠇⠀
⠀⠀⠀⠀⠀⠀⠠⠿⠉⠙⠙⠦⠠⠞⠫⠭⠙⠿⠀⠀⠀⠠⠾⠀⠾⠟⠴⠿⠁⠀
⠀⠀⠀⠀⠀⠀⠸⠇⠾⠀⠀⠈⠛⠵⠛⠀⠀⠸⠄⠀⠠⠟⠿⠱⠋⠴⠿⠁⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠿⠘⠧⠀⠀⠠⠏⠀⠀⠀⠟⠀⠀⠘⠇⠿⠷⠿⠿⠷⠗⠀⠀
⠀⠀⠀⠀⠀⠀⠠⠾⠓⠊⠓⠦⠼⠀⠀⠠⠚⠳⠤⠀⠠⠾⠿⠋⠽⠿⠟⠀⠀⠀
⠀⠀⠀⠀⠀⠼⠏⠀⠀⠀⠀⠴⠻⠍⠉⠙⠛⠷⠞⠷⠘⠩⠴⠾⠿⠋⠀⠀⠀⠀
⠀⠠⠤⠤⠴⠿⠀⠤⠤⠶⠋⠁⠀⠧⠀⠀⠀⠀⠈⠼⠇⠭⠿⠛⠻⠆⠀⠀⠀⠀
⠀⠈⠿⠟⠙⠻⠷⠾⠽⠲⠎⠀⠀⠺⠸⠶⠶⠶⠾⠿⠥⠏⠶⠁⠈⠷⠀⠀⠀⠀
⠀⠀⠀⠙⠿⠷⠶⠶⠤⠈⠷⠀⠀⠽⠸⠢⠇⠄⠀⠀⠙⠼⠇⠀⠀⠏⠀⠀⠀⠀
⠀⠀⠠⠾⠿⠟⠋⠉⠤⠆⠘⠧⠄⠧⠏⠀⠹⠜⠦⠀⠀⠸⠀⠀⠘⠋⠓⠶⠄⠀
⠀⠼⠿⠿⠧⠴⠾⠿⠟⠱⠶⠌⠛⠋⠀⠀⠀⠱⠮⠙⠒⠼⠗⠚⠋⠛⠛⠊⠻⠧
⠘⠻⠟⠿⠻⠻⠛⠉⠰⠯⠂⠉⠢⠀⠠⠄⠴⠋⠀⠀⠠⠎⠸⠄⠀⠀⠀⠠⠾⠃
⠀⠀⠀⠀⠀⠀⠀⠀⠘⠞⠇⠀⠸⠫⠵⠻⠇⠀⠤⠶⠫⠀⠀⠹⠜⠖⠚⠋⠁⠀
⠀⠀⠀⠀⠀⠠⠖⠋⠉⠁⠹⠄⠰⠋⠀⠸⠷⠭⠭⠶⠿⠀⠀⠸⠇⠇⠀⠀⠀⠀
⠀⠀⠸⠿⠳⠾⠅⠤⠤⠤⠤⠿⠣⠤⠐⠾⠁⠀⠦⠬⠙⠳⠤⠐⠽⠃⠀⠀⠀⠀
⠀⠀⠀⠹⠶⠭⠹⠮⠥⠕⠁⠸⠀⠈⠙⠮⠣⠀⠝⠿⠿⠶⠿⠿⠏⠀⠀⠀⠀⠀
⠀⠴⠾⠟⠛⠛⠙⠄⠸⠁⠀⠼⠲⠄⠀⠈⠼⠰⠧⠹⠏⠙⠛⠛⠛⠂⠀⠀⠀⠀
⠘⠻⠿⠿⠾⠾⠟⠁⠸⠆⠐⠫⠎⠉⠛⠋⠋⠁⠻⠿⠃⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠛⠛⠋⠀⠀⠀⠀⠀⠀⠀⠙⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀
```
