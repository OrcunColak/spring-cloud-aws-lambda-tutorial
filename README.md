The original idea is from  
https://collin-smith.medium.com/creating-a-java-21-spring-boot-3-application-on-aws-lambda-48be652fc93f

# Maven archetype

```
mvn archetype:generate -DgroupId=com.colak -DartifactId=spring-cloud-aws-lambda-tutorial -Dversion=1.0-SNAPSHOT -DarchetypeGroupId=com.amazonaws.serverless.archetypes -DarchetypeArtifactId=aws-serverless-springboot3-archetype  -DarchetypeVersion=2.0.0-M2
```

# Profiles

**assembly-zip** profile is the default profile
**shared-jar** profile includes aws-serverless-java-container-core-2.0.0-M2.jar