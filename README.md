# fpst

A C library to check if a string starts with a prefix from a potentially large set of candidates.

Nothing fancy, but I needed this in order to efficiently match DNS queries against a large set of
blacklisted domains, and it might be useful to others.

Usage: see the [fpst.h header file](https://github.com/jedisct1/fpst/blob/master/src/fpst.h).
