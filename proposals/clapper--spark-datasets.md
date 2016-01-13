* title: Spark Datasets: A comparison with RDDs and DataFrame Queries
* presenter: Brian Clapper
* length: 45 minutes
* Twitter: https://twitter.com/brianclapper
* Meetup: http://www.meetup.com/nescala/members/12380763/

Traditionally, Apache Spark jobs have been written using Resilient
Distributed Datasets (RDDs), a Scala Collections-like API. RDDs are
type-safe, but they can be problematic: It's easy to write a suboptimal
job, and RDDs are _significantly_ slower in Python than in Scala.
DataFrames address some of these problems, and they're much faster, even in
Scala; but, DataFrames aren't type-safe, and they're arguably less flexible.

Enter Datasets, a type-safe, object-oriented programming interface that
works with the DataFrames API, provide some of the benefits of RDDs, and
can be optimized via the Catalyst optimizer.

This talk will briefly recap RDDs and DataFrames, introduce the Datasets
API, and then, through a live demonstration, compare the performance of all
three against the same non-trivial data source.
