[![Build Status](https://app.travis-ci.com/anr-ru/base.config.svg?branch=master)](https://app.travis-ci.com/anr-ru/base.config)

## Part of [Base.Platform Project](https://github.com/anr-ru/base.platform.parent)

### Base.Config

Here are provided some Maven configuration which can simplify creating Java projects 
from scratch. It contains base settings for the most popular plugins and dependencies. 
Also, with the use of this configuration, it's easy to manage versions of frequently used
artifacts— all you need is just to override the required version property in your pom.xml.

You can use this artifact **org.anrruf:base.config** as the maven parent for your 
own projects, like this:

```xml
    <parent>    
        <groupId>org.anrruf</groupId>
        <artifactId>base.config</artifactId>
        <version>2.6.1</version>
    </parent>
```

Please use the following location for the project repository:

```xml
<repositories>
    <repository>
      <id>base-platform</id>
      <url>https://gitlab.com/api/v4/projects/39021055/packages/maven</url>
      <releases>
        <enabled>true</enabled>
      </releases>
      <snapshots>
        <enabled>true</enabled>
      </snapshots>
    </repository>
  </repositories>
```
