# docker-firebase

## Purpose

This image was created specifically for usage with continuous integration
systems, and contains the minimum requirements to deploy a project to
[Firebase](https://firebase.google.com/). Currently being used with
[wercker](https://app.wercker.com), but should meet the requirements for most CI
systems.

## Details

### Base Image

- [node (erbium)](https://hub.docker.com/r/library/node/) - The latest Node
  LTS (currently v12.x.x or code name Erbium) image

### Additional Node Modules

- [Firebase CLI](https://github.com/firebase/firebase-tools) - Firebase Command
  Line Tools. Required to deploy to Firebase.
