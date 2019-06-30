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
