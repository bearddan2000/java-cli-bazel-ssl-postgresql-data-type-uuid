# java-cli-bazel-ssl-postgresql-data-type-uuid

## Description
Creates a small table `dog` that uses
a uuid data type.

A java bazel build, that connects to postgresql database.

Uses self-sign ssl.

## Tech stack
- java
- bazel
  - log4j
  - postgresql drivers

## Docker stack
- alpine:edge
- postgresql:alpine
- l.gcr.io/google/bazel:latest

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
