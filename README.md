# Capinibal
#### « another anticapitalist images generator »

# Author
Jérôme Blanchi aka d.j.a.y

contributor : vloop

# Usage
```
usage: capinibal.py [-h] [-o OUTPUTFILE] [-r FPS] [-d DURATION]
                    [-s SPEED_OF_CHANGE] [-p PIPENAME] [-v]

Generate another anticapitalist moving images to a named pipe...or not.

optional arguments:
  -h, --help            show this help message and exit
  -o OUTPUTFILE, --output OUTPUTFILE
                        Output file
  -r FPS, --rate FPS    Frames per second
  -d DURATION, --duration DURATION
                        Seconds, 0 for infinite
  -s SPEED_OF_CHANGE, --speed SPEED_OF_CHANGE
                        Speed of change (changes per second)
  -p PIPENAME, --pipe PIPENAME
                        Name of the pipe to stream to, if missing, name is
                        generated
  -v, --verbose         Enable debug output (default: off)
```
See also cpb_client.py
See the file [Issue.md](Issues.md) for known problem and task list and [LICENSE.md](LICENSE.md)
for information about copyright and usage terms.

# Dependencies
* [Wand](http://wand-py.org/), ctypes-based simple ImageMagick binding for Python.
```
pip3 install Wand
```
* [pyliblo](http://das.nasophon.de/pyliblo/), pyliblo is a Python wrapper for the liblo OSC library.
```
pip3 install pyliblo
```
Tested with wand 0.4.4 (use `pip3 install wand==0.4.4`) and broken with wand 0.5.1
