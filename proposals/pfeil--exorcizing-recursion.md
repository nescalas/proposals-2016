* title: Exorcizing Recursive Data Structures
* presenter: Greg Pfeil
* length: 45 minutes
* Twitter: https://twitter.com/sellout
* Meetup: http://www.meetup.com/members/2077528/

There are recursive data structures in almost every program we write – from JSON and XML to custom ASTs. However, they can be awkward to deal with, and often require code duplication and hand-written traversals. A lot of that work can be generalized across all recursive data structures by … eliminating the recursion.

Parameterizing the recursive part of a data structure converts it into a functor and enables myriad techniques that increase the flexibility of the structure. It makes data structures extensible; allows arbitrary annotatations to be added to the nodes of a data structure; and lets us generalize folds, unfolds, and traversals so they operate on any recursive structure. This talk will explain the technique and go into detail on some of the benefits that can be achieved with this approach.
