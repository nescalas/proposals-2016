* title: Requester -- The better alternative to ask
* presenter: Mark Waks, AKA Justin du Coeur
* length: 15 minutes
* Twitter: https://twitter.com/jducoeur
* Meetup: http://www.meetup.com/members/14160934/

One of Akka's more infamous traps is `ask`: since it is Future-based, using it inside of an Actor is a fine way to break Akka's
threading invariants and find yourself with mysterious bugs. So instead, I present Requester -- an alternative monad and library that looks
and feels a lot like Future, but which is designed from the ground up to work well inside of Actors. The `request` function allows
you to compose Akka calls the way you expect, without as many headaches.
