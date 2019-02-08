# Gradle Test Framework Plugin

[![Travis CI Badge](https://travis-ci.org/mechjacktv/gradle-test-framework.svg?branch=develop)](https://travis-ci.org/mechjacktv/gradle-test-framework)

Adds a test framework source set to java projects.

## Using the Plugin

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

## License

Gradle Test Framework is distributed under the MIT license. You can read the license at [LICENSE](./LICENSE.md).
