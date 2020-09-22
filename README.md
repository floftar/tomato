tomato
======

`tomato` is a simple [pomodoro timer](https://en.wikipedia.org/wiki/Pomodoro_Technique)
shell script written for Bourne shell. Script sets the pomodoro timer
to 25 minutes. `tomato` runs in background and sends a notification after
timer has finished.

Installation
------------

Either place `tomato` on your PATH or run it by specifying the full path.

Usage
-----

```sh
$ tomato # Start a new timer
$ tomato stop # Stop timer
```

Dependencies
------------

Notification requires `send-notify`.
