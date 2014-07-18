eggtimer
========

A timer based on a url parameter. Based off of [e.ggtimer.com](http://e.ggtimer.com). This version uses different parsing, focusing on short forms, and allows for clock times. Eg: `2:20` started at 1 PM will end at 2:20 PM. `1:10` started at 11 PM will end at 1:10 AM.

Examples
--------

### Countdown

* `1m` [http://zren.github.io/eggtimer/?t=1m](http://zren.github.io/eggtimer/?t=1m)
* `1min` [http://zren.github.io/eggtimer/?t=1m](http://zren.github.io/eggtimer/?t=1m)
* `1m 45s` [http://zren.github.io/eggtimer/?t=1m+45s](http://zren.github.io/eggtimer/?t=1m+45s)
* `1m45s` [http://zren.github.io/eggtimer/?t=1m45s](http://zren.github.io/eggtimer/?t=1m45s)
* `1h30m` [http://zren.github.io/eggtimer/?t=1h30m](http://zren.github.io/eggtimer/?t=1h30m)

### Clock Times

`h` will use the 24 hour clock.

* `1:00` 1PM if started at 11AM [http://zren.github.io/eggtimer/?t=1:00](http://zren.github.io/eggtimer/?t=1:00)
* `23:00` 11PM [http://zren.github.io/eggtimer/?t=23:00](http://zren.github.io/eggtimer/?t=23:00)
* `1h00` 1AM [http://zren.github.io/eggtimer/?t=1h00](http://zren.github.io/eggtimer/?t=1h00)
* `23h00` 11PM [http://zren.github.io/eggtimer/?t=23h00](http://zren.github.io/eggtimer/?t=23h00)
