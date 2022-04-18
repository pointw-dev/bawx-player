# bawx-player
This is a port of Kelvin Lawson's [pykaraoke library](https://github.com/kelvinlawson/pykaraoke) (upgraded from Python 2 to Python 3 and packaged)

Install with...

    pip install bawx-player

**play_karaoke.py**
```python
from bawx_player import pycdg

player = pycdg.cdgPlayer('some_song.cdg', None)
player.Play()
pycdg.manager.WaitForPlayer()

```
