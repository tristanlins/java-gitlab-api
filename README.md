# Gitlab Java API Wrapper

This is a fork of [timols/java-gitlab-api](https://github.com/timols/java-gitlab-api)!

Most features / enhancements are [open pull requests](https://github.com/timols/java-gitlab-api/pulls/tristanlins)

This fork can be used thanks to gitlabs [maven repository](https://gitlab.com/tristanlins/java-gitlab-api/-/packages) feature.

## How to use this fork

Add the repository to your `build.gradle` or `pom.xml`:

```groovy
repositories {
    maven { url "https://gitlab.com/api/v4/projects/12707257/packages/maven" }
}
```

```xml
<repositories>
    <repository>
        <id>tristanlins/java-gitlab-api</id>
        <url>https://gitlab.com/api/v4/projects/12707257/packages/maven</url>
    </repository>
</repositories>
```

Then change your dependency version, to [latest snapshot](https://gitlab.com/tristanlins/java-gitlab-api/-/packages).
 