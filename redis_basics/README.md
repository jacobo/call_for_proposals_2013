# The Basics of Redis

## Abstract

I don't know if you people already knew this, but Redis is the ultimate tool for hacking something together and shipping it straight to production.  And let me tell you, I've shipped my share of hacks to production.

The secret, of course, is key expiration. Plus you don't have to ship migrations, so reverting your hacks leaves way less cruft!

Allow me to show you some real-world examples. That you too may be engorged with the sense of power I first experienced when I realized how easy this is.

Cheat sheet:

    redis.set("foo", "bar")
    redis.get("foo") #returns "bar"
    redis.expire("foo", 5.minutes)

## Reviewer Notes

This is *nearly* an intro level talk, but with a lesson I think many experienced rails folks have yet to notice. I hope to teach a mindset about building things with Redis as a backend (as opposed to (or complimentary to) traditional ActiveRecord). Real, substantial, hopefully-impressive, things.

## Jacob Burkhart

Jacob is the world's foremost expert on Redis (within the subset of people who: work in Ruby for a living, surf the Pacific regularly, and brew sour beers). He does all these things in San Francisco California, while working at Engine Yard.

![Profile picture](http://jbirdcreations.com/JacobBurkhart.png)

- [My website](http://birdswell.com)
- [My twitter](https://twitter.com/beanstalksurf)
- [Past talk slides](http://jacobo.github.com/building_services)
- [Past talk video](http://www.confreaks.com/videos/1079-cascadiaruby2012-being-present)
