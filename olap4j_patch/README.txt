
1.  If you have already built the project, delete these folders in your local maven repository:
/Users/joe/.m2/repository/org/olap4j/olap4j/TRUNK-SNAPSHOT
/Users/joe/.m2/repository/org/olap4j/olap4j-xmla/TRUNK-SNAPSHOT

2.  Run these commands to install the patch jars for Olap4J to your local maven repository:
mvn install:install-file -Dfile=olap4j_patch/olap4j-TRUNK-SNAPSHOT.jar -DpomFile=olap4j_patch/olap4j-TRUNK-SNAPSHOT.pom
mvn install:install-file -Dfile=olap4j_patch/olap4j-xmla-TRUNK-SNAPSHOT.jar -DpomFile=olap4j_patch/olap4j-xmla-TRUNK-SNAPSHOT.pom