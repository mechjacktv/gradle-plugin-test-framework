# Gradle Test Framework Plugin

[![Travis CI Badge](https://travis-ci.org/mechjacktv/gradle-test-framework.svg?branch=develop)](https://travis-ci.org/mechjacktv/gradle-test-framework)

Adds a test framework source set to java projects.

## Installing the Plugin

This plugin is hosted on GitHub and distributed using JitPack. Add the following to your `build.gradle`:

```groovy
buildscript {
  repositories {
    maven { url "https://jitpack.io" }
  }
  dependencies {
    classpath 'com.github.mechjacktv:gradle-test-framework:master-0.1.0'
  }
}

plugins {
    id 'tv.mechjack.gradle.testframework'
}
```

## Using the Plugin

Execute the `initTestFramework` task to create your source directory and put the test framework code you want included in a `jar` artifact along side your main `jar` for consumers to use during testing.

## License

Gradle Test Framework is distributed under the MIT license. You can read the license at [LICENSE](./LICENSE.md).
