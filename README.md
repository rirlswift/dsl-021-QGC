# Swift DevOps - QGroundControl for Swift 021 PX4 Docker containers.

Repository for QGroundControl tar ball used by Swift PX4 Docker containers.

## Overview

This repository is a temporary placeholder, until something better can be implemented. The tar ball (derived from the QGC app image) is referenced from Docker files using:
``` Dockerfile
ADD https://github.com/rirlswift/dsl-021-QGC/raw/master/QGroundControl.tar.gz \
/opt/swift/QGC
```

## Authors

* **Rick Landon** - *Initial work* - [Swift Engineering](https://swiftengineering.com/)