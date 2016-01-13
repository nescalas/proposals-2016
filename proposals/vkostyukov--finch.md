* title: Finch: When Shapeless, Circe and Cats meet Finagle
* presenter: Vladimir Kostyukov
* length: 30 minutes
* Twitter: https://twitter.com/vkostyukov
* Meetup: http://www.meetup.com/members/92415602/

[Finch][finch] is an idiomatic Scala library that provides a combinator API over the Finagle HTTP services. It's simple, small and [surprisingly performant][perf] given how many levels of indirections it involves on top of raw Finagle services. In this talk, we'll look closely on Finch's internals to understand how modern libraries like Shapeless, Circe and Cats combined with best practices, help Finch to stay clean, boilerplate-less and fast.

[finch]: https://github.com/finagle/finch
[perf]: https://github.com/finagle/finch#performance
