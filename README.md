Organizer README
================

Organizer _was_ an attempt to create a sort of file metadata
management system upon which further computations could be performed.
It turned out to actually be an endeavor to develop my own GUI widgets
atop the Windows API, namely a text editor widget and a panel widget.
Also, it turned out to be an area for drawing some pretty pictures and
playtime computer art projects while taking a short break from
programming.

Why?
====

At the time of the year 2009, I was still mainly using a budget Dell
PC that was manufactured in the year 2003.  I was constantly having
trouble running short on disk space as I continued to increase my
knowledge of the ever-expanding software development tools landscape.
So, I thought I needed a more systematic plan on managing the finite
available space.  Tremendous system configuration optimizations have
already brought be a long way in maximizing the utility of the finite
space, but I still felt I needed more.

So, I thought, hey, if I write metadata on all my files, surely I'll
have an easy way of tracking what is needed for particular tasks, and
then I can run automated programs to tweak and tune what is stored
where accordingly.  That is, what is stored on the 30 GiB internal
system hard drive versus what is stored on external hard drives or
other computer systems.

Of course, as it turned out, Windows development proved to be my
nemesis.  I was constantly disappointed by defects in proprietary
system components that I wanted to be able to reuse to reduce the
amount of code I was writing, so over the course of this software's
development, it ended up being a library of my own libre Windows
native GUI widgets.

I did, of course, learn my lesson that if I wanted to develop
practical software within a reasonable timeframe, I needed to use a
higher-level libre widget toolkit.  No proprietary widgets allowed.
Hence, I proceeded to learn GTK+ in more detail and have since written
a useful program, albeit for a different purpose.

As for the "Organizer" software concept, that has largely migrated to
a web programming project instead, focusing more on physical objects
than digital objects.  It turned out that I was able to get much
larger digital storage devices that drastically changed my needs and
reasoning about computer storage space from a "linear" standpoint to
an "orders of magnitude" standpoint.
