* title: From Websockets to Kafka with Akka Streams
* presenter: Paul G. Kinsky
* length: 15 minutes
* Twitter: @paul_kinsky
* Meetup: http://www.meetup.com/members/88028382/

Your app is a hit. Everyone's using your service. You've instrumented your website to collect real time usage data and you've set up a data processing pipeline to work with large amounts of data in real time, but how do you bridge the gap between web page and data pipeline? With websockets, Kafka and Akka Streams, of course!

This talk covers using Akka Streams and Akka HTTP to, in less than 100 lines of code, build a server that consumes streams of events via websocket and publishes them to a Kafka topic, after which you can use the data analysis framework of your choice to analyze them to your heart's content.
