# CONTENTS OF THIS FILE
   
 * Introduction
 * Requirements
 * Recommended modules
 * Installation
 * Configuration
 * Troubleshooting
 * FAQ
 * Maintainers


## Introduction
Integrates the contrib Group module with the core Book module.

One book can belong to many groups. Without this integration module one would 
need to manually add each book page to each group, and (re)move each book 
page when a book is removed from a group and/or moved to another group.

With this module, once a book belongs to a group: 

* each (new) child page will automatically belong to the same group
* when a book is removed from a group, each child page will be removed as well
* when a book moves to another group, its child pages will move as well


## Requirements
* Book module (core)
* Group module (contrib)
* Group Node module (contrib, part of Group) 


## Installation
Enable module.
 

## Configuration
There is nothing to configure

## Troubleshooting
An admin interface is available at {path} to enable display and/or 
logging of debug information.


## FAQ


## Maintainers
Original creator:
 * Joeri Poesen (jpoesen) - https://drupal.org/u/jpoesen


