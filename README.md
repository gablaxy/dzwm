DZWM
=====

     /\___/\
    ( o   o )  Made by cat...
    (  =^=  )
    (        )            ... for cat!
    (         )
    (          ))))))________________ Cute And Tiny Window Manager

Summary
-------

forked from catwm, wich is a very simple and lightweight tiling window manager that try to stay under 1000 SLOC.

Status
------
 
 catwm status updates
 * 05.07.19 -> v0.3. Multiple desktops and correct some bugs
 * 30.06.10 -> v0.2. Back again \o/
 * 15.03.10 -> v0.2. The wm is functional -> I only use this wm!
 * 24.02.10 -> First release, v0.1. In this release 0.1, the wm is almost functional

Modes
-----

It allow the "normal" modes of tiling window managers:

    --------------
    |        |___|
    |        |___|
    | Master |___|
    |        |___|
    |        |___|
    --------------

and fullscreen mode

There is no horizontal stack because I never use it. But if someone is interested in, it's very easy to add.

Installation
------------

Need Xlib, then:
    $ vim config.h
    $ make
    # make install
    $ make clean

Bugs
----
 * No bugs for the moment ;) (I mean, no importants bugs ;)

Todo
----
 * Make sure it work after modifications
 * Add multiple view ("desktop")
 * Switch to XCB
 * Add a floating mode
 
