# How to fail at Background Jobs

## Abstract

From DRB, XMPP, AMQP to Resque and Rails 4. Running a background worker process is a tool I've reached for often. And while the underlying tools may change, the same problems seem to crop up in every one.

A failed request serves your fancy custom 500 error page, but what about a failed job?

Is there such a thing as a "reliable" queuing system that will never lose OR double process any jobs?

Are we talking about "simple" asynchronous method calls on models or should we build "pure" workers with only the knowledge of a single task?

What does "idempotent" mean again?

Please allow me to enliven the debates.


## Reviewer Notes

This is a mid-level talk that I *think* safely assumes you've done some sort of background processing before. I really do want to hear what people think or if/how they've solved these problems. I hope I can do that by presenting some options and allowing them to self-identify "that's what we do". The tools are great, but they all fall so short in answering (or even having an opinion) on these questions.

## Jacob Burkhart

Jacob is the world's foremost expert on Background Jobs (within the subset of people who: work in Ruby for a living, surf the Pacific regularly, and brew sour beers). He does all these things in San Francisco California, while working at Engine Yard.

![Profile picture](http://jbirdcreations.com/JacobBurkhart.png)

- [My website](http://birdswell.com)
- [My twitter](https://twitter.com/beanstalksurf)
- [Past talk slides](http://jacobo.github.com/building_services)
- [Past talk video](http://www.confreaks.com/videos/1079-cascadiaruby2012-being-present)
