# Docker SBT

This is a Docker image for SBT based on Alpine to get as small an image as possible. There are three tags. I'll check in the following:

| Tags | Description |
| ---- | ----------- |
| `0.13.15`<br>`0.13`<br>`latest`<br>`stable` | The latest stable version of SBT which is [0.13.15](http://www.scala-sbt.org/0.13/docs/index.html). |
| `1.0` | The latest non-stable version of SBT which is [1.0.0-RC2](http://www.scala-sbt.org/1.0/docs/index.html). |
| `0.12`<br>`0.12.4`<br>`obsolete` | The latest supported obsolete version of SBT which is [0.12.4](http://www.scala-sbt.org/0.12.4/docs/index.html). |

You can run Scala through SBT using `docker run --rm -it aa8y/sbt:latest sbt console`.
