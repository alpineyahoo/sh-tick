# sh-tick
timer using [dateutils](https://formulae.brew.sh/formula/dateutils).
<br>
24-hour clock.
<br>
I didn't know the word "[shtick](https://en.wikipedia.org/wiki/Shtick)" ever.
## Installation Example

```shell
$ git clone https://github.com/alpineyahoo/sh-tick.git
$ cp ./sh-tick/snoopy/shtick /usr/local/bin/shtick
$ chmod +x /usr/local/bin/shtick
```

## Use

```shell
# v3
# situation: current_date = 14:52
$ shtick 1530
 == 15:30:00 ==  0:37:59
 
# snoopy version
# situation: current_date = 05:45
$ shtick 0600
 ______
< == 06:00:00 ==  0:14:59 >
 ------
 \
  \
   \     O_      __)(
       ,'  `.   (_".`.
      :      :    /|`
      |      |   ((|_  ,-.
      ; -   /:  ,'  `:(( -\
     /    -'  `: ____ \\\-:
    _\__   ____|___  \____|_
   ;    | |        '-`      :
  :_____|:|__________________:
  ;     |:|                  :
 :      |:|                   :
 ;_______`'___________________:
:                              :
|______________________________|
 `---.--------------------.---'
     |____________________|
     |                    |
     |____________________|
     |                    |
   _\|_\|_\/(__\__)\__\//_|(_

```
 
## Log
Check [log](/log.md)
