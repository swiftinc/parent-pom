# parent-pom

[![Maven Central](https://img.shields.io/maven-central/v/com.swift/parent-pom.svg?label=Maven%20Central)](https://search.maven.org/search?q=g:%22com.swift%22%20AND%20a:%22parent-pom%22)

## Overview

This is the parent pom for all projects maintained by [SWIFT developers](https://github.com/orgs/swiftinc/people).

Use of the pom is intended to:

* Establish a predictable baseline of goals.
* Make builds maintainable by avoiding duplication information.

## Referencing the Parent POM

To reference the parent pom, include the following in the child `pom.xml`:

```xml
<parent>
       <groupId>com.swift</groupId>
       <artifactId>parent-pom</artifactId>
       <version>$version</version>
</parent>
```

## License

See the [LICENSE](LICENSE.md) file for license rights and limitations (SWIFT).

----
* [Contact](mailto:support@case.swift.com)
* [Issues](https://github.com/swiftinc/parent-pom/issues)
* [Source Control](https://github.com/swiftinc/parent-pom/)
