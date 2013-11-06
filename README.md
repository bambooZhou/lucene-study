#develop
	mvn eclipse:eclipse

#run
	mvn compile
	mvn exec:java -Dexec.mainClass="com.bambooZhou.study.Indexer" -Dexec.args="index data"
	mvn exec:java -Dexec.mainClass="com.bambooZhou.study.Searcher" -Dexec.args="index Indexer"