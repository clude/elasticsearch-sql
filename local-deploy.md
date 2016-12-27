* command 1
 mvn clean deploy -Dmaven.test.skip=true -Dgpg.skip=true
 
 
* command 2
 mvn deploy:deploy-file -Durl=http://10.57.115.230/artifactory/libs-release-local -DrepositoryId=releases -Dfile=/Users/clude/workspace/clude-git/elasticsearch-sql/target/elasticsearch-sql-5.1.1.0.jar -DgroupId=rg.nlpcn -DartifactId=lasticsearch-sql -Dversion=5.1.1.0
