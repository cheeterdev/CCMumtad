# CCMumtad
![CraftsCore](https://img.shields.io/badge/Based%20on-CraftsCore%20v3.7.59-SNAPSHOT)
![License](https://img.shields.io/badge/License-AGPL%203.0-blue)
![Mumtad](https://img.shields.io/badge/Mumtad-1.0%20ALPHA-red)

## Info
Mumtad is a modified Version of [the CraftsBlock CraftsCore.](https://github.com/CrAfTsArMy/CraftsCore) Mumtad is used internally to make the programming of our projects easier, it does not offer that much more than the original CraftCore. it is compatible with normal CraftsCore plugins and also with other plugins like MumtadJDA or MumtadMC 

## Credits
[Based on CraftsCore.](https://github.com/CrAfTsArMy/CraftsCore)

Original Contributors:
[Philipp](https://github.com/CrAfTsArMy) /
[Vincenz](https://github.com/vinc3nz) /
[xvcf](https://github.com/RafaeloxMC) /
[Website](https://repo.craftsblock.de/#/releases/de/craftsblock/craftscore/CraftsCore)

## Installation
We didnt updated the installation process yet, the Installation below is for [the unedited original CraftsCore.](https://github.com/CrAfTsArMy/CraftsCore) We will [announce in our Discord Server.](https://dsc.gg/cheeter) when we update it.

### Maven
```xml
<repositories>
  ...
  <repository>
    <id>craftsblock-releases</id>
    <name>CraftsBlock Repositories</name>
    <url>https://repo.craftsblock.de/releases</url>
  </repository>
</repositories>
```
```xml
<dependencies>
  ...
  <dependency>
    <groupId>de.craftsblock.craftscore</groupId>
    <artifactId>CraftsCore</artifactId>
    <version>X.X.X-SNAPSHOT</version>
  </dependency>
</dependencies>
```

### Gradle
```gradle
repositories {
  ...
  maven { url "https://repo.craftsblock.de/releases" }
  mavenCentral()
}
```
```gradle
dependencies {
  ...
  implementation 'de.craftsblock.craftscore:CraftsCore:X.X.X-SNAPSHOT'
}
```

## Open Source Licenses
We are using some third party open source libraries. Below you find a list of all third party open source libraries used:
| Name                                                                   | Description                                                                                                                           | Licecnse                                                                                         |
| ---------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| [OkHttp](https://github.com/square/okhttp)                             | Square’s meticulous HTTP client for the JVM, Android, and GraalVM.                                                                    | [Apache License 2.0](https://github.com/square/okhttp/blob/master/LICENSE.txt)                   |
| [MySQL Connector-J](https://github.com/mysql/mysql-connector-j)        | MySQL Connector/J                                                                                                                     | [GPLv2 with FOSS exception](https://github.com/mysql/mysql-connector-j/blob/release/8.x/LICENSE) |
| [GSON](https://github.com/google/gson)                                 | A Java serialization/deserialization library to convert Java Objects into JSON and back                                               | [Apache License 2.0](https://github.com/google/gson/blob/main/LICENSE)                           |

## Issues
If you find any issues from the plugin or documentation please [open up issue](https://github.com/CrAfTsArMy/CraftsCore/issues)
