[![Build Status](https://travis-ci.org/walkingdevs/tomee-simple.svg?branch=master)](https://travis-ci.org/walkingdevs/tomee-simple)
[![Download](https://api.bintray.com/packages/walkingdevs/mvn/tomee-simple/images/download.svg) ](https://bintray.com/walkingdevs/mvn/tomee-simple/_latestVersion)

## What is it?
- Simple JEE 6 WAR template based on TomEE 1.7

## How to create a project?

CLI:

    mvn archetype:generate \
        -DarchetypeGroupId=walkingdevs \
        -DarchetypeArtifactId=tomee-simple \
        -DarchetypeVersion=1.7.4 \
        -DarchetypeRepository=http://dl.bintray.com/walkingdevs/mvn \
        -DgroupId=test \
        -DartifactId=app \
        -Dversion=0.1

## Something wrong?

Let's discuss. I am a very discussful guy