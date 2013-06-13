---
layout: page
title: "About"
comments: false
sharing: false
footer: true
---

This project is to complete the development of ScribeUI, a mapfile editing and management GUI developed internally by Mapgears, and to contribute it as a new open source component to the MapServer project. It is currently being developped as a [Google Summer of Code project](http://www.google-melange.com/gsoc/project/google/gsoc2013/jlapointe/4001).

Currently, the configuration of MapServer maps involves the use of a text editor to edit a mapfile with layers and class definitions, etc. It is no secret that lots of users would prefer to use a web GUI to edit, manage and preview their mapfiles directly on the server where their maps are hosted. 

Two components are involved in this project: Scribe and ScribeUI.

Scribe is a python utility developed internally by Mapgears with the goal of making the edition of large mapfiles easier. It helps with the management of zoom levels and lets you define and use variables, two features that greatly simplify mapfile management. Scribe then generates a valid mapfile that can be used with any application supporting the file type. [Learn more about Scribe](http://www.mapgears.com/en/blog/archive/2013-03-12-scribe).

This tool currently has a web GUI, called ScribeUI, using Flask and jquery-ui, that allows the edition of scribe, mapfile and basemap files. That GUI is however not complete, currently it is only used internally by Mapgears, it still has bugs and needs some work before it can be packaged and made available to the community. 

The project for the Google Summer of Code 2013 is to finish that tool, fully support mapfile and basemaps filetypes, refine the GUI, test and fix bugs, clean the code behind and then package and publish the project as an open source utility accessible to all MapServer users, and user-friendly enough to appeal to both newbies and experienced mapfile developers looking for a productivity tool. 

The end result will also be presented to the MapServer Project Steering Committee (PSC) in the hope that it could become an official component of the MapServer project.
