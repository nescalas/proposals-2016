* title: Increase Code Quality using Docker Compose Integrated with sbt
* presenter: Kurt Kopchik
* length: 30 minutes

Teams are often great at unit testing but when it comes to End-to-End and Integration testing things get much harder. Especially, when working with may discrete services. I have been working on an sbt plug-in "sbt-docker-compose" that integrates the functionality of Docker Compose (along with some other advanced features) directly into the sbt build environment. With a simple "dockerComposeUp" command in sbt you can launch ephemeral and isolated instances of you changes for live debugging and testing. I'd like to present lessons learned and an overview of how to use the soon to be released (before the conference) sbt-docker-compose plugin.