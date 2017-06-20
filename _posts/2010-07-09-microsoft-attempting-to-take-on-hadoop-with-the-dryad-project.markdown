---
layout: post
title: 'Microsoft Attempting to Take on Hadoop with the Dryad Project'
---
<img class="alignnone" style="padding: 15px;" title="Hadoop" src="http://hadoop.apache.org/zookeeper/images/hadoop-logo.jpg" alt="" width="300" height="71" align="right" />I'm learning more and more about distributed computing as I"m playing with larger and larger volumes of data. I understand a lot of the concepts behind the popular distributed computing platform <a href="http://hadoop.apache.org/" target="_blank">Hadoop</a>, but have no actual experience deploying it. I'm diving into all the building blocks of <a href="http://hadoop.apache.org/" target="_blank">Hadoop</a> one by one as I have time:
<ul class="mainlist">
	<li><a href="http://hadoop.apache.org/common/" target="_blank">Hadoop Common</a> - The common utilities that support the other Hadoop subprojects.</li>
	<li><a href="http://hadoop.apache.org/chukwa/" target="_blank">Chukwa</a> -A data collection system for managing large distributed systems.</li>
	<li><a href="HBase" target="_blank">HBase</a> - A scalable, distributed database that supports structured data storage for large tables.</li>
	<li><a href="http://hadoop.apache.org/hdfs/">HDFS</a> - A distributed file system that provides high throughput access to application data.</li>
	<li><a href="http://hadoop.apache.org/hive/" target="_blank">Hive</a> - A data warehouse infrastructure that provides data summarization and ad hoc querying.</li>
	<li><a href="http://hadoop.apache.org/mapreduce/" target="_blank">MapReduce</a> - A software framework for distributed processing of large data sets on compute clusters.</li>
	<li><a href="http://hadoop.apache.org/pig/" target="_blank">Pig</a> - A high-level data-flow language and execution framework for parallel computation.</li>
	<li><a href="http://hadoop.apache.org/zookeeper/" target="_blank">ZooKeeper</a> - A high-performance coordination service for distributed applications.</li>
</ul>
Tonight, a post that really opened my eyes to some of the features and the approach Hadoop takes, was <a href="http://jpatterson.floe.tv/index.php/2009/07/20/a-high-level-comparison-of-hadoop-and-dryad/" target="_blank">A High Level Comparison of Hadoop and Dryad</a>. Not sure why, but the comparison of Hadoops approach using <a href="http://en.wikipedia.org/wiki/MapReduce" target="_blank">Map Reduce</a> and Microsoft's approach using <a href="http://en.wikipedia.org/wiki/Directed_acyclic_graph" target="_blank">Directed Acyclic Graph</a> has got me reading more. I think its because of my history with Windows Server, SQL Server and being a recovering Microsoft Kool-Aid drinker that this comparison is shedding light on Hadoop for me.<p></p>
It appears appears that Microsoft is attempting to take on the <a href="http://hadoop.apache.org/" target="_blank">Hadoop</a> community with its <a href="http://research.microsoft.com/en-us/projects/Dryad/">Dryad Project</a>. I'm way behind in understanding and applying <a href="http://hadoop.apache.org/" target="_blank">Hadoop</a>, but Josh Patterson's comparison has pushed me into learning more. Thanks Josh.