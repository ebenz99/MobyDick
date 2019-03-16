# Moby Dick

An application for when your friend leaves their laptop open.

## Directions

1. Clone/download this repository
2. Open the terminal wherever you have these files stored
3. Run the command `python readMobyDick.py`
4. Hide the terminal window
4. Make the volume soft enough that when they return to their computer, they might not notice the sound at first.

## Notes

This was originally designed to run on Mac computers, as it runs on the Mac-default Python 2.7. If the script doesn't run, try the command `python -V`. If this shows a python version other than 2.7, use the command `alias python2='/usr/bin/python'` to alias python 2.7 as "python2". Then run the script with `python2 readMobyDick.py`.


It should be portable to Linux, but as of creation, Windows CLI still lacks a text-to-speech command, so it won't work there.

If you fear retalliation, I highly encourage you to make your next stop my facial-recognition computer locking repo [here](https://github.com/ebenz99/FacePatrol).