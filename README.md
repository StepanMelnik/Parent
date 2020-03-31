# Parent

Parent maven project to work with all Java projects.


## Description
Parent project contains all needed maven plugins, dependencies and properties.

Also maven build performs checkstyle stage to find any violations in main/test packages.


### Usage
```
<parent>
    <groupId>com.sme</groupId>
    <artifactId>parent</artifactId>
    <version>0.0.1-SNAPSHOT</version>
</parent>
```
