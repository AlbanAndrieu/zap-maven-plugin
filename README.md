zap-maven-plugin
================

[![Jenkins Build Status](http://home.nabla.mobi:8380/jenkins/job/zap-maven-plugin-nightly/badge/icon)](http://home.nabla.mobi:8380/jenkins/job/zap-maven-plugin-nightly)

Dependency Status using [versioneye](https://www.versioneye.com/users/AlbanAndrieu)

[![Dependency Status](https://www.versioneye.com/user/projects/55279e012ced4f5816000583/badge.svg?style=flat)](https://www.versioneye.com/user/projects/55279e012ced4f5816000583/visual)

This is a Maven Plugin to control ZAProxy. It is based on https://code.google.com/p/zap-maven-plugin.

#### build

```
$ mvn clean install -DzapApiPath=/workspace-tmp/divers/zaproxy-read-only/build/zap/zap-api-v2-4.jar
#-DzapApiPath=/workspace/slave/tools/com.cloudbees.jenkins.plugins.customtools.CustomTool/ZAPROXY/ZAP_2.8.0/ZAP_2.8.0/zap-2.8.0.jar
```

#### integration test

Please see the following project: https://github.com/AlbanAndrieu/bodgeit-maven
This project is used to test zap-maven-plugin

#### Jenkins project

https://wiki.jenkins-ci.org/display/JENKINS/Zapper+Plugin

https://github.com/parrot55/zap-plugin

#### Similar project

Please follow :

https://code.google.com/r/bmrosantos-zap-maven-plugin

https://github.com/TeamPraxis/grunt-zaproxy

