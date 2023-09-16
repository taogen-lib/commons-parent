# commons-parent

Add the parent

```xml
<parent>
	<groupId>com.github.taogen-lib</groupId>
	<artifactId>commons-parent</artifactId>
	<version>-SNAPSHOT</version>
</parent>
```

Add the [JitPack](https://jitpack.io/#taogen-lib/commons-parent) repository to your build file

```xml
<repositories>
	<repository>
		<id>jitpack.io</id>
		<url>https://jitpack.io</url>
	</repository>
</repositories>
```

## Check for updated dependencies in repository

```shell
# Display new versions
mvn versions:display-dependency-updates
mvn versions:display-plugin-updates
# Update dependency versions from properties
mvn versions:update-properties
# Update the parent version
mvn versions:update-parent 
```

Don't use alpha versions

References

- [spring-boot-dependencies-2.1.4.RELEASE.pom](https://github.com/mahendra-shinde/maven-repo-springboot/blob/master/repository/org/springframework/boot/spring-boot-dependencies/2.1.4.RELEASE/spring-boot-dependencies-2.1.4.RELEASE.pom)
