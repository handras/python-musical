# python-musical

A Python module for procedural music creation.


## Installation
    python setup.py install

The setup will install *numpy* as it is a dependency.
For the playback function to work, one of the following packages has to
be available. (i.e. install with *pip* or *conda*)

Playback is supported with 3 different backends:
* pyaudio
* pygame
* ossaudiodev