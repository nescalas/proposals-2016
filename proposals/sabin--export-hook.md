* title: Juggling implicit priorities with export-hook
* presenter: Miles Sabin
* length: 45 minutes
* Twitter: https://twitter.com/milessabin
* Meetup: http://www.meetup.com/members/4414303/

Does anybody really understand how implicit instances are selected when there are multiple choices? The specification
is clear but incomplete, complicated, and hard to relate to the implementation and to practice. Many people know that
using the implicit scope avoids the "import tax". Despite that, many important projects use imports. Why? In this talk
I will try to explain the pros and cons of using the implicit scope vs. imports, and argue that the Typelevel
export-hook project shows one way we might get the best of both worlds.
