EasyDokkaPlugin
===============

Gradle script plugin to generate documentation by Dokka documentation engine in Javadoc format for Java, Kotlin, Android and non-Android projects. It's very easy, you don't need to add to `dependencies` section additional `classpath` or think about compatibility issues, you don't need additional repositories also.

## Usage

### 1. Have a working Gradle build

It is up to you.


### 2. Call the script

Add the following at the end of `build.gradle` of each sub-module that you wish to generate documentation:

```groovy
apply from: 'https://raw.github.com/Vorlonsoft/EasyDokkaPlugin/master/dokka.gradle'
```

### 3. Generate documentation

You can now generate documentation by Dokka documentation engine in Javadoc format:

```bash
$ gradle dokkaJavadocsJar
```

### 4. Get documentation

Get generated documentation from `${buildDir}` directory.

## Our other pligins

[GradleMavenPush](https://github.com/Vorlonsoft/GradleMavenPush) - helper to upload Gradle Android Artifacts, Gradle Java Artifacts and Gradle Kotlin Artifacts to Maven repositories (JCenter, Maven Central, Corporate staging/snapshot servers and local Maven repositories)

## Contribute

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## License

    Copyright 2018 Vorlonsoft LLC

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        https://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.