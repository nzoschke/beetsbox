Thin wrappers arout beets to make it self-contained.

Create a virtualenv and install beets

```
$ python virtualenv.py venv --distribute
$ source venv/bin/activate
$ pip install -r requirements.txt
```

Import a folder or two, query it, preview files and folders

```
$ bin/import /Volumes/Music

$ bin/list Norwegian
The Beatles - A Hard Day's Night - Norwegian Wood (This Bird Has Flown)

$ bin/ql douche
Testing Quick Look preview with files:
  /Volumes/Music/02 - Norwegian Wood (This Bird Has Flown).mp3
  /Volumes/Music/402-The_Beatles-Norwegian_Wood_(this_Bird_Has_Flown).mp3
```

## Todo

Import paths as specified in config file
Automatically source virtualenv in helpers
Figure out why .m4a tags aren't read
List / preview helpers
Fix info plugin
