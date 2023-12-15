---
title: How to install
slug: /
sidebar_position: 2
---

### Minimum system requirements

| Parameter | Value    |
|-----------|----------|
| Java      | Java 17+ |
| CPU       | 1 core+  |
| RAM       | 1 GB+    |

??? info "Java"

    Here you can download Java 21, but we recommended use latest LTS release.

    [Java 21](https://www.azul.com/downloads/?version=java-21-lts&package=jdk#zulu){ .md-button } [Java 17](https://www.azul.com/downloads/?version=java-17-lts&package=jdk#zulu){ .md-button }

### On linux

1. Download and install `Java`
2. Put the jar file in a separate folder and create `start.sh`
3. In the start.sh file, enter this: `java -Dfile.encoding=UTF-8 -jar <name of jar file>.jar`
4. Run the commands: `cd /path/to/bot` and `sh start.sh`

### On windows

1. Download and install `Java`
2. Put the jar file in a separate folder and create `start.bat` _(create `start.txt` and rename to `start.bat`)_
3. In the start.sh file, enter this: `java -Dfile.encoding=UTF-8 -jar <name of jar file>.jar`
4. Start `start.bat`