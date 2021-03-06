[![Bintray](https://api.bintray.com/packages/takhion/kotlin-metadata/kotlin-metadata/images/download.svg) ](https://bintray.com/takhion/kotlin-metadata/kotlin-metadata/_latestVersion)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](/LICENSE)

# Kotlin Metadata

This library is a wrapper around Kotlin's `@Metadata` annotation, exposing its data in a typesafe manner. 

The `@Metadata` annotation contains information about Kotlin specific features that would otherwise be lost when compiling Kotlin to Java, and are especially useful when developing annotation processors.

## Usage

Gradle:
```gradle
compile("me.eugeniomarletti.kotlin.metadata:kotlin-metadata:<version>")
```
