va-solor-goods
==============

Notes:

The parent pom of this project contains a lot of boilerplate stuff that is used in each of the child modules.  Things like populating a metadata tree in the final 
artifact, publishing the artifacts, etc.  This saves a lot of copy/paste inheritance.

If you follow the existing patterns when creating a new child pom - things will work great.  If you don't follow the existing pattern - things won't work well, as 
the parent pom expects the child modules to have certain files in certain places, and follow established naming conventions.