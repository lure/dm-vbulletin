# dm-vbulletin
vBuletin forums data extraction tool


This is actually an experiment of using [Akka-Streams](http://doc.akka.io/docs/akka/2.4.12/scala.html) to process and transform some data from WEB-services, with page transformation and data extraction.

So far this tool allows to crawl some vBulletin-based forums, using user-id and password for an existing account, to
- extract the profile data as an unsorted map
- extract lists of likes per user to build sort of a social graph

The plan is to add some Spark-ML processing to allow extraction of
- user clusters
- registration spikes and gauge
- registration anomalies
- etc

Powered by Scala, Akka and friends.
