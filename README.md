# Droidvalds

Simple bash script coupled with a systemd service that will run on each user session start. The script itself plays a random video made by [Linus Droidvalds](https://www.youtube.com/@linusdroidvalds) on all connected monitors at the same time in fullscreen using mpv. Service can be disabled with:

```
systemctl --user disable droidvalds.service
```

Script can also be ran via:

```
droidvalds
```
