# ii

i2c for synth modules

## intro

"`ii`" came into existence with the creation of [teletype](http://monome.org/docs/teletype/) to take advantage of the unpopulated i2c header on the monome trilogy modules (white whale, meadowphysics, earthsea).

`ii` is a protocol layer and configuration which uses the [i2c](https://en.m.wikipedia.org/wiki/I%C2%B2C) physical bus. (this is to say, `ii` is a subset of `i2c`.)

a [community created guide](https://llllllll.co/t/a-users-guide-to-i2c/19219) goes into further details of the current implementation.

## 1.0

as more modules are added to the `ii` ecosystem it's become clearer that we should establish a set of standards for the protocol. this will reduce code complexity and create some reusable patterns that will benefit the system.

the goal will be establish a "ii 1.0 standard" document here.
