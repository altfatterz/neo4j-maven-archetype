Neo4j Maven Archetype
=====================

Very basic Maven archetype that sets up an empty project with Neo4j, JUnit and Mockito dependencies.

After cloning, run

    cd neo4j-maven-archetype
    mvn install

Then navigate to where you want to create your new project and type:

    mvn archetype:generate -DarchetypeGroupId=cz.bachman -DarchetypeArtifactId=neo4j-maven-archetype -DarchetypeVersion=1.0-SNAPSHOT

Answer a couple of questions along the way (about your groupId, artifactId and so on), after which you should see

    [INFO] BUILD SUCCESS