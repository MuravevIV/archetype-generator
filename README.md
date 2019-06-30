# Archetype generator

#### Initial template

```
mvn archetype:generate \
  -DarchetypeGroupId=org.apache.maven.archetypes \
  -DarchetypeArtifactId=maven-archetype-archetype \
  -DarchetypeVersion=1.4 \
  -DgroupId=com.muravyev \
  -DartifactId=archetype-generator \
  -Dversion=1.0-SNAPSHOT \
  -DinteractiveMode=false
```

### Installation

```
mvn clean install
```

### Generation

```
mvn archetype:generate \
  -DarchetypeGroupId=com.muravyev \
  -DarchetypeArtifactId=archetype-generator \
  -DarchetypeVersion=1.0-SNAPSHOT \
  -DgroupId=${groupId} \
  -DartifactId=${artifactId} \
  -Dversion=1.0-SNAPSHOT \
  -DinteractiveMode=false
```
