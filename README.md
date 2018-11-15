# How to use it
Add following snippets to the [pom.xml](https://maven.apache.org/guides/introduction/introduction-to-the-pom.html):

```xml
<repositories>
  <repository>
    <id>robb-mvn-repo</id>
    <url>https://rawgit.com/hxh-robb/mvn-repo/master/releases</url>
  </repository>
  <repository>
    <id>robb-mvn-repo</id>
    <url>https://rawgit.com/hxh-robb/mvn-repo/master/snapshots</url>
    <snapshots>
      <enabled>true</enabled>
    </snapshots>
  </repository>
</repositories>
```
