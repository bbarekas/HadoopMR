A sample map reduce example using Hadoop MR functionality. 

This is explained in details here: [Linux Journal article](http://www.linuxjournal.com/content/introduction-mapreduce-hadoop-linux)

You can run it as:

    $ hadoop-1.2.0/bin/hadoop jar 
        hadoop-1.2.0/contrib/streaming/hadoop-streaming-1.2.0.jar 
	-mapper map.py -reducer reduce.py  
	-input log.txt -output output
