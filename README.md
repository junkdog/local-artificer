## About
I got tired of manually installing dependencies not found in maven repositories. This downloads the zips/jars
from the interwebs and installs them into the local repository.

## Usage

```
mvn -P<profile> install
```
See main [pom](https://github.com/junkdog/local-artificer/blob/master/pom.xml) for available profiles.
