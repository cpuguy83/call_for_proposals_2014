# Concurrent Programming in Ruby with Celluloid

So apparently there is this new fangled language out there from Google, called Go,
which provides these awesome concurrecny primitives, goroutines and channels which
makes concurrent programming easy(ish).
Did you know we already had these kinds of primitives in Ruby?

Celluloid is a Ruby framework which provides some very intesreting concurrency
primitives called actors.  Actors are not new, and you are probably even using them
already in your app via Sidekiq... but are you taking advantage of them in your
own code?

Actors are great! They really do make threaded/concurrent programming
significantly more simple, but you may have to adjust how you think about and
write your code.

In this talk I will take you through Celluloid Actor basics and some tips and
tricks I've picked up along the way of writing a large project from the ground up
with Celluloid.

## Brian Goff

Brian is the head of IT at EnVu, LLC, a pioneer in interactive digital signage.
He is responsible for building and mantaining software for managing large
networks of digital signage devices.


![Profile picture](http://farm3.staticflickr.com/2872/11371245914_ec3d39a1c5_d.jpg)

- [My twitter](https://twitter.com/cpuguy83)
