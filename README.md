fefebot
=======

1. Download [diaspy](https://github.com/marekjm/diaspy) (>=0.5.0.1)
2. Extract the diaspy subfolder to your fefebot folder
3. Install the [diaspy requirements](https://github.com/marekjm/diaspy/blob/master/requirements.txt) (sudo pip3 install dateutils)
4. Edit ```config.py```
5. Run ```install.py```
6. Run ```bot.py```  (it is ment to be run in crontab.)

```
# crontab examble to run every hour
@hourly cd /path/to/fefebot/; ./bot.py
```
