Base.Platform Project

=============
Config.Java
=============

This is some maven configuration, which can simplify creating of Java projects.
It contains base settings for most popular plugins and dependecies.

You can use this artifact ru.anr:config.java as maven parent for own projects, like:


...
    <parent>    
        <groupId>ru.anr</groupId>
        <artifactId>config.java</artifactId>
        <version>0.9-SNAPSHOT</version>
    </parent>
...