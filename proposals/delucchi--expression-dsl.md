* title: Building a Reasonable Expression DSL with Kleisli
* presenter: Ryan Delucchi
* length: 45 minutes
* Twitter: https://twitter.com/ryanonsrc
* Meetup: http://www.meetup.com/nescala/members/14053885/

It wasn't long ago that creating a highly specialized mini-language was a herculean undertaking. After dusting off the ol' "Dragon Book" we would implement a tokenizer and write our own BNF grammar. Then, we run these grammar rules through some arcane compiler-compiler tool (e.g. yacc) and iterate ad infinitum. But, now we have a truly scalable language at our fingertips. With the aid of predefined constructs and open source libraries, we can build our very own DSL, using this sophisticated language, requiring nothing more than the scalac compiler.

Yet, even for building a rather simple expression style DSL, which is at the very heart of many modern rule-based languages, it doesn't take long for the intrinsic complexity of language design to surface. In this talk, we will dig deep in the functional programmer's tool chest, and uncover a little known gem known as the Kleisli. We will explore how this deceptively simple piece of machinery in category theory can be used to build complex expression DSLs, with a completely modular library of operations and pluggable error handling. The code examples will be entirely Scala, with dependencies on the scalaz library. This presentation is geared towards those with an intermediate/advanced skill level in Scala and/or functional programming.
