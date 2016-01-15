* title: Easier dependency management with coursier
* presenter: Alexandre Archambault
* length: 15 minutes
* Twitter: https://twitter.com/alxarchambault
* Meetup: http://www.meetup.com/members/78577172/

[coursier](https://github.com/alexarchambault/coursier) is an attempt at making it easier to deal with Maven / Ivy dependencies, from Scala and the command-line. It's a replacement for Ivy or Aether, rewritten from scratch. It also features a working SBT plugin, and can even be used from [Scala JS](http://alexarchambault.github.io/coursier/#demo). It follows functional programming practices in both its very core and its user-facing API, and even makes use of algebraic structures like lattices at times. Its command-line programs allow to effortlessly launch programs from Maven / Ivy artifacts, list dependencies, or update caches. In this talk, we'll review the possibilities offered by its API, its command-line tools, and its SBT plugin.
