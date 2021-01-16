[![Build Status](https://travis-ci.org/anr-ru/config.java.svg?branch=master)](https://travis-ci.org/anr-ru/config.java)

## Part Of [Base.Platform Project](https://github.com/anr-ru/base.platform.parent)

### Config Java

Here are provided some maven configurations which can simplify creating Java projects from scratch.
It contains base settings for most popular plugins and dependencies.

You can use this artifact **ru.anr:config.java** as the maven parent for your own projects, like this:

```xml
    <parent>
        <groupId>ru.anr</groupId>
        <artifactId>config.java</artifactId>
        <version>1.1.0</version>
    </parent>
```

Please use the following location for the project repository:

```xml
<repositories>
    <repository>
      <id>anr-ru</id>
      <url>https://https://packagecloud.io/ruanr/baseplatform/maven2</url>
      <releases>
        <enabled>true</enabled>
      </releases>
      <snapshots>
        <enabled>true</enabled>
      </snapshots>
    </repository>
  </repositories>
```
