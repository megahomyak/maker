# What?

`maker` stands for `MAKE Recursively`. This is a program that runs a `Makefile` using GNU Make (needs to be installed) in each directory recursively (including the current one), and if a `Makefile` wasn't found, a `Makerfile` (notice the `r`) from the invocation directory is used.

# Why?

I wanted something like [little\_server](https://github.com/megahomyak/little_server), but for static websites.

# How?

Either copy `maker.sh` into your project or run the `install.sh` script (don't forget `sudo`!) and then invoke `maker` anywhere.
