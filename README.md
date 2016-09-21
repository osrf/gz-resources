[ ![Codeship Status for osrf/gz-resources](https://codeship.com/projects/21902870-60c1-0134-82e0-1e1ec2b80fe8/status?branch=master)](https://codeship.com/projects/174634)

[![GitHub version](https://badge.fury.io/gh/osrf%2Fgz-resources.svg)](https://badge.fury.io/gh/osrf%2Fgz-resources)

[![Dependency Status](https://www.versioneye.com/user/projects/57e0292c6dfcd00047c51ead/badge.svg?style=flat-square)](https://www.versioneye.com/user/projects/57e0292c6dfcd00047c51ead)

# \<gz-resources\>

documentation: [https://osrf.github.io/gz-resources/components/gz-resources](https://osrf.github.io/gz-resources/components/gz-resources)

demo: [https://osrf.github.io/gz-resources/components/gz-resources](https://osrf.github.io/gz-resources/components/gz-resources/demo)

* Create new resources
* Delete resources
* Get all resources of a kink

For details, refer to the [Cloudsim wiki](https://bitbucket.org/osrf/cloudsim/wiki/Home)

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
