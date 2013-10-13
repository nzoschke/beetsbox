Thin wrappers arout beets to make it self-contained.

Create a virtualenv and install beets:

```
$ python virtualenv.py venv --distribute
$ source venv/bin/activate
$ pip install -r requirements.txt
```

Import a folder or two, and query it with the beets "list" syntax:

```
$ bin/import /Volumes/Music

$ bin/list sun

$ bin/list sun
Modeselektor - Happy Birthday! - The Dark Side of the Sun (ft. Puppetmastaz)
The Beatles - A Hard Day's Night - Here Comes the Sun
The Beatles - A Hard Day's Night - Sun King
The Beatles - A Hard Day's Night - I'll Follow The Sun
The Beatles - A Hard Day's Night - Good Day Sunshine
```

Listen to the resulting file(s) in Quick Look, or reveal in Finder:
```
$ bin/quicklook sun
Testing Quick Look preview with files:
  /Volumes/Music/iTunes Media/Music/Modeselektor/Happy Birthday!/11 The Dark Side of the Sun (ft. Puppetmastaz).mp3
  /Volumes/Music/iTunes Media/Music/The Beatles/A Hard Day's Night/07 - Here Comes The Sun.mp3
  /Volumes/Music/iTunes Media/Music/The Beatles/A Hard Day's Night/10 - Sun King.mp3
  /Volumes/Music/iTunes Media/Music/The Beatles/A Hard Day's Night/05 - I'll Follow The Sun.mp3
  /Volumes/Music/iTunes Media/Music/The Beatles/A Hard Day's Night/08 - Good Day Sunshine.mp3

$ bin/finder sun
```

## Todo

Import paths as specified in config file
Automatically source virtualenv in helpers
Figure out why .m4a tags aren't read
List / preview helpers
Fix info plugin
