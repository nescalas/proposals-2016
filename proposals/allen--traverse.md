* title: Traverse and sequence: flip your types inside out
* presenter: Cody Allen
* length: 30 minutes
* Twitter: [FouriersTrick](https://twitter.com/FouriersTrick)
* Meetup: http://www.meetup.com/members/19099171/

> I have a `List[Future[A]]`. How do I turn it into a `Future[List[A]]`?

If you haven't asked this question yourself, you've probably seen someone ask it at some point. The answer was probably `Future.sequence` or maybe even `Future.traverse`. But what if I have an `Option` instead of a `List`? Or an `Either` instead of a `Future`? `Future.sequence`'s (rather complicated) type signature breaks down in these cases. Luckily the `Traverse` type class (found in both Cats and Scalaz) has these and many more cases covered. We'll talk about how `Traverse` combines the notion of `map`ing a structure with that of `fold`ing a structure - bridging the gap between `Functor` and `Foldable`. If time permits we might even talk about the mysterious `sequenceU` and `traverseU`.
