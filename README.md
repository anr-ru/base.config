## Base.Platform Project

# Config Java

These are some maven configurations which can simplify creating of Java projects from scratch.
It contains base settings for most popular plugins and dependencies.

You can use this artifact **ru.anr:config.java** as maven parent for own projects, like this:

```xml
    <parent>    
        <groupId>ru.anr</groupId>
        <artifactId>config.java</artifactId>
        <version>0.9-SNAPSHOT</version>
    </parent>
```


Please use the following location for the project repository:

```xml
<repositories>
    <repository>
      <id>anr-ru</id>
      <url>https://https://packagecloud.io/ruanr/configjava/maven2</url>
      <releases>
        <enabled>true</enabled>
      </releases>
      <snapshots>
        <enabled>true</enabled>
      </snapshots>
    </repository>
  </repositories>
```
