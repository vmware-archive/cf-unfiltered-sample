# This repository is no longer actively maintained by VMware, Inc.

cf-unfiltered-sample
================
An [Unfiltered](https://github.com/unfiltered/unfiltered) sample generated from the [giter8 template](https://github.com/softprops/unfiltered.g8).  Unfiltered is a toolkit for servicing HTTP requests in Scala.  This example uses embedded Jetty and is deployed to Cloud Foundry as a standalone application.

### Deploying to Cloud Foundry

To deploy the application to Cloud Foundry, simply build the dist and push it to Cloud Foundry using the provided manifest.yml file.  You may need to modify the manifest to use a unique URL.

```bash
sbt clean compile package-dist
vmc push
Would you like to deploy from the current directory? [Yn]:
Pushing application 'cf-unfiltered-sample'...
```
