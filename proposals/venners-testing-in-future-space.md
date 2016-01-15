* title: Testing in Future Space
* presenter: Bill Venners
* length: 30 minutes
* Twitter: https://twitter.com/bvenners
* Meetup: http://www.meetup.com/members/14780191/

In ScalaTest 3.0's new async testing styles, tests have a result type of
`Future[Assertion]`. Instead of blocking until a future completes, then
performing assertions on the result, you map assertions onto the
future and return the resulting `Future[Assertion]` to ScalaTest.
The test will complete asynchronously when the `Future[Assertion]`
completes. This way of testing requires a different mindset. In this talk
I'll walk you through the design, show you how to use it, and suggest
best practices for async testing on both the JVM and Scala.js.

