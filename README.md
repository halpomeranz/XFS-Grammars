XFS Grammars
============

Over several years I've been working on a series of blog posts detailing the on-disk data structures
of the XFS file system. You can read those posts here: https://righteousit.wordpress.com/tag/xfs/

Throughout the series, I've been using Synalize IT! and Hexinator to produce colored breakdowns of
each data structure. I have no reason not to release the grammars I created and they may be of use
to somebody else, so here you go!

The biggest problem with these grammars at the moment is that they are not dynamic. Various arrays
and other data structures should be sized based on different fields in the data structures themseleves.
At the moment, I've hard-coded many of these values per my specific examples. But obviously things are
going to break in the general case.

So there's some scripting work that needs to happen before these grammars are generally applicable.
I didn't want to wait to release what I had before I learned the scripting interface for these tools,
because I'm not sure when I'm going to have time to do that. Feel free to send me a pull request if
you end up doing that work before I do.

Cheers!

Hal Pomeranz
hal@deer-run.com
@hal_pomeranz
