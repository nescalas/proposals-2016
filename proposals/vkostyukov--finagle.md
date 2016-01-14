* title: Finagle Under the Hood
* presenter: Vladimir Kostyukov
* length: 45 minutes
* Twitter: https://twitter.com/vkostyukov
* Meetup: http://www.meetup.com/members/92415602/

[Finagle][finagle] is an extensible RPC system for JVM written in Scala that is used and developed at Twitter. It promotes a programming model where servers and clients might be viewed [as functions][marius], which are both easy to compose and reason about. Although, there is quite a complex logic (connection pooling, load balancing, circuit breaking and so on) hidden behind those functions. In this talk, we'll dig into Finagle internals and carefully walk through each of its modules to see what happens when we a) send a request to a Finagle client b) receive a request by a Finagle server.

[finagle]: https://github.com/twitter/finagle
[marius]: http://monkey.org/~marius/funsrv.pdf
