# revigniter-hmvc-modules
HMVC Modules for Revigniter

##NOT READY FOR PRIMETIME##
This project is in it's inital development state and only contains CODE FRAGMENTS that are not usable for any real use. Once the project gets to a point where you'll be able to do something with it, I'll remove this warning.

##Overview##
This extension allows for Hierarchical Model View Controller(HMVC) implementations within the Revigniter framework. In theory, this will allow for more reusable code, and the ability to distribute modules in a single directory to be included within a Revigniter installation.

##Functionality##
This is the basic structure of an HMVC module:

```
/modules
     /module-name
          /controllers
          /models
          /views
     module-name.lc
     index.html
```
