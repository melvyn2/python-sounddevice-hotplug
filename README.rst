About this fork
===============
- This fork was not made to be merged, as the portaudio branch it relies on isn't merged
- This fork adds:
    - a function to refresh device lists without interupting current streams
    - a callback that is triggered when a device is added or removed

Play and Record Sound with Python
=================================

This Python_ module provides bindings for the PortAudio_ library and a few
convenience functions to play and record NumPy_ arrays containing audio signals.

Documentation:
   http://python-sounddevice.readthedocs.io/

Source code repository and issue tracker:
   https://github.com/spatialaudio/python-sounddevice/

License:
   MIT -- see the file ``LICENSE`` for details.

.. _Python: https://www.python.org/
.. _PortAudio: http://www.portaudio.com/
.. _NumPy: http://www.numpy.org/
