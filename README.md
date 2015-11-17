# revigniter-hmvc-modules
HMVC Modules for Revigniter

##NOT READY FOR PRIMETIME##
This project is in it's inital development state and only contains CODE FRAGMENTS that are not usable at the moment. Once the project gets to a point where you'll be able to do something with it, I'll remove this warning.

##Overview##
This extension allows for Hierarchical Model View Controller(HMVC) implementations within the Revigniter framework. In theory, this will allow for more reusable code, and the ability to distribute modules in a single directory to be included within a Revigniter installation.

Each Module contains it's own config, controllers, models and veiws OR not.

My intention is to make HMVC as light weight as possible for the implementation.

##Functionality##
This is the basic structure of an HMVC module:

```
/modules
     /module-name
          /config
          /controllers
          /models
          /views
     index.html
```

(Yes, I know for a more complete HMVC implementation there needs to be more added. If we can get the basics going we'll add in other HMVC elements as development progresses)
