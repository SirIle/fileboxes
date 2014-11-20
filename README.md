# Fileboxes

## Versions

Node.js: 0.10.33
Java JRE 8: 1.8.0_25
Jetty: 9.2.4.v20141103

## General

This repository contains the Docker build files for filebox volume containers
used with running Microcontainers.

At the moment it contains four fileboxes:

### Basefilebox

Basic filebox containing Consul and runit support files. As they're all statically
linked, no extra libraries are needed to get them running on BusyBox x86_64.

### Nodejsfilebox

Contains the executable for Node.js and the required libstdc++.so.6 lifted from
Ubuntu 14.04.

### Java8filebox

Contains the JRE for Java 8.

### Jettyfilebox

Contains the Jetty runtime.
