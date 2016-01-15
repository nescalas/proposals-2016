* title: How (Not) to Destroy Your Reactive Application
* presenter: Zach Cox
* length: 15 minutes
* Twitter: https://twitter.com/zcox
* Meetup: http://www.meetup.com/members/12841552/

The Scala ecosystem contains many great tools for building reactive, asynchronous, concurrent systems such as futures, tasks, actors, and streams. These tools all ultimately execute code on pools of threads, which are finite resources. It is fairly simple (and common) for applications built on these tools to exhaust these finite resources, grinding reactive systems to a halt. We will see just how easily each of these concurrency tools can get blocked, and review specific techniques to prevent such problems in our applications.
