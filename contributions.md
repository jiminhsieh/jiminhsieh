# Open Source Contributions

[All of my open source contributions](https://github.com/search?utf8=%25E2%259C%2593&q=author:jiminhsieh+-user:jiminhsieh+is:merged&s=updated&type=Issues&s=created&o=desc). Below are some PRs which I categorize by a daily job of a software engineer.  

## Add features
* [Added new APIs to Eclipse Collections](https://github.com/eclipse/eclipse-collections/pull/754) which is formerly Goldman Sachs Collections.
* [Added a command-line option for sbt-jmh to export JFR report.](https://github.com/ktoso/sbt-jmh/pull/120)

## Fix issues

* Thread leak
    * [Akka cluster was not closed.](https://github.com/akka/akka-persistence-cassandra/pull/380)
    * [A Kafka producer was not terminated.](https://github.com/cakesolutions/scala-kafka-client/pull/137)
* Build failed
    * [Oracle JDK license was changed.](https://github.com/azakordonets/fabricator/pull/34)
* Others 
    * [One of Kafka's classes didn't initialize the parent class.](https://github.com/apache/kafka/pull/4859)
  
## Testing

* [Increased testing coverage and fixed build failed.](https://github.com/azhur/kafka-serde-scala/pull/104)

## Refactor

* [Changed to lambda expressions for Java 8 SAM types](https://github.com/paypal/squbs/pull/660) at [payal squbs](https://github.com/paypal/squbs).

## Documentation

* [Improved docs for other learners.](https://github.com/weihsiu/reactive-streams/pull/2)
* [Fixed hyperlinks couldn't display correctly at source code.](https://github.com/lomigmegard/akka-http-cors/pull/15)
* [Fixed broken links which were caused by jekyll.](https://github.com/scala/docs.scala-lang/pull/851)
    
## Open issues

* Suggested [jabba](https://github.com/shyiko/jabba) to [add BellSoft's Liberica JDK](https://github.com/shyiko/jabba/issues/433) since they're also a TCK certified OpenJDK.
* Suggested [kafka-visualizer](https://github.com/manasb-uoe/kafka-visualizer) to package their code in Docker since not everyone has the JDK 9 locally.
