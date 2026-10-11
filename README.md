# Droidvalds

Simple bash script coupled with a systemd service that will run on each user session start. The script itself plays a random video made by [Linus Droidvalds](https://www.youtube.com/@linusdroidvalds) on all connected monitors at the same time in fullscreen using mpv. Service can be disabled with:

```
systemctl --user disable droidvalds.service
```

For those unlucky enough to end up with an openrc system, a patch providing a service was submitted recently:

```
rc-service --user del droidvalds
```

Script can also be ran via:

```
droidvalds
```
