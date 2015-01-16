# boot-batch-hashtagcount
Sample Boot batch job

Requires that some tweets in one or more *.txt files are available in HDFS under /xd/tweets dir.

Build with:

    $ mvn clean package

Run with:

    $ java -jar target/hashtag-count-0.1.0-exec.jar
