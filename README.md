# revigniter-hmvc-modules
HMVC Modules for the revIgniter Framework

##GIVE IT A TRY##
This project is in it's initial development state and contains VERY NEW/UNTESTED code. I am so excited by the possibilities I've pushed out my initial work with LIMITED TESTING. Please, start small and take baby steps. I suggest starting by looking at the original welcome screen (/index.lc) vs. the HMVC welcome screen (index.lc/welcome).

From there, try the sample Chat Application in the docs (see revIgniter user docs as there is CSS and DB setup you need to do to get the chat application working HMVC or not). I’ve included the Chat “Module” but not the css or DB config. You’ll have to get those setup for your environment. 

If you have your own projects, try it out but again, tread lightly. I’ve only implemented Models, Views and Controllers at this point.

Check out the wiki pages here on GitHub as well.

I will need your help getting test samples. As I am new to revIgniter I have NO prior projects to use for testing. HMVC revigniter came out of my initial work on trying to build a CMS (I know, I know. But Livecode/revIgniter should have a CMS-like thingy) but I did not get too far with this effort.

THERE IS A LOT OF DEBUG CODE IN THERE. PERFORMANCE TAKES A HIT. As I mentioned, this is still a very new project and as such, I’ve put in LOADS of debugging points which may cause performance issues.

##Overview##
This extension allows for Hierarchical Model View Controller(HMVC) implementations within the Revigniter framework. In theory, this allows for more reusable code, and the ability to distribute modules in a single directory to be included within a Revigniter installation.

Each Module contains it's own models, views and controllers. If an element is not located within the Module, files are searched in the standard revIgniter Application location for the resources.

My intention is to make HMVC as light weight as possible for the implementation.

##Functionality##
This is the basic structure of an HMVC module:

```
/modules
     /module-name
          /controllers
          /models
          /views
     index.html
```

(Yes, I know for a more complete HMVC implementation there needs to be more added. If we can get the basics going we'll add in other HMVC elements as development progresses)

###Dependencies###

[revIgniter Framework](http://revigniter.com)

[Learn about Livecode](https://livecode.com/products/livecode-platform/livecode-for-developers/)
