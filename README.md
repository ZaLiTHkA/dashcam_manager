# Dashcam Editor and Manager

> **note**: this aims to effectively replace my `dashcam-vid-clipper` project with something better.. the internal design of _this_ project is built up on the knowledge that I gained from creating the PowerShell script version of it.

this app is written in Dart and powered by Flutter, aiming to be an all-in-one place for extracting useful video clips from segmented dashcam clips.

no configuration or behaviour with side-effects is assumed, though some places will have sensible defaults (which may only be used after prompting the user) will be set.

## Inspiration and History

the biggest driving force for this project, is twofold..

firstly, I cannot find any decent, lightweight, *truly free* video clip editing software. I've tried a great many programs on multiple platforms that would classify as "video editing software" is some or other form.. but either they just don't have the required functionality, are just too unstable, or the necessities are hidden behind a paid license along with a ton of unnecessary stuff.

secondly, this a good excuse to spend some time learning how to make _proper_ use of Dart and Flutter.
