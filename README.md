isync
=====

An rsync-inspired command-line synchronisation tool for iPod devices.

The isync script is in a *VERY* proof-of-concept state. It works amazingly
well for me, but it is by no means as flexible/fast/foolproof as I'd want
it to be. Use at your own risk.

I had the idea for writing this tool ages ago, but I just never did it.
Then at some point I got really sick of gtkpod. Adding stuff was a pain,
the synchronisation never worked (or I was too dumb to figure out how)
and last but not least they decided to do "incremental saves" when adding
tracks, which made adding a bunch of albums a task of hours.

The isync script is, currently, intended to work nicely if you want to
synchronise your whole media collection to your iPod. If that's not what
you want, it's probably too hard to use. If it is what you want...

  isync --delete --mountpoint=/mnt/ipod sync /path/to/mp3s

Oh, did I mention it currently only works for mp3 audio and mp4 video?

You can add the --dry-run option to see what it would do. You can also
run with --verbose for some more information.

Oh, I've never tested the 'initialise' command.

Enjoy!
