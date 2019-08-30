# Kubernetes Client API Plugin

This plugin exposes the [Kubernetes Client](https://github.com/fabric8io/kubernetes-client) API to Jenkins plugins like 
[kubernetes-plugins](https://github.com/jenkinsci/kubernetes-plugin) and [kubernetes-credentials-provider-plugin](https://github.com/jenkinsci/kubernetes-credentials-provider-plugin). 

# Environment

The following build environment is required to build this plugin

* `java-1.8` and `maven-3.3.9`

# Build

To build the plugin locally:

    mvn clean verify

# Release

To release the plugin:

    mvn release:prepare release:perform -B

# Test local instance

To test in a local Jenkins instance

    mvn hpi:run
