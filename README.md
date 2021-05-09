# orvCoreProto
orvCore Js Library. Some handy core functionality. At this point it is a *working prototype*.

- Note that at this point, there are a bunch of stubs in here that do not have their functionality yet.
- It does have error handling functionality which allows you to display nicely formatted error messages on the web page while working on the development of your site.
- It has some @CodePen functionality that you can use when including it in a Pen on @CodePen...
 - It has a property: ```codepenId``` which will return the CodePen Id (if being run from a Pen). Otherwise it will return a blank string.
 - It has a property: ```codepenView``` which returns the *view* of the Pen. If the page is not a pen it will return the string: 'notAPen'.
- It has a ```currentVersion``` property which will return the version of the library you are currently using.
- The property: ```isLocalHost``` checks the page URL to determine if the page is running on a website hosted on the same computer that you are viewing the page on. If it is, it returns a value of **true**.
- If site is running locally, I am making the assumption that web applications are designated by a path name on the domain. I use this for the indexDb wrapper to use for naming of the indexDb database files so each separate "site" gets its own database file. 
- Note that if using indexDb functionality, it will automatically name the new indexDb file based on the Pen's Id. Thus each Pen will get its own database!
- Note that right now, the indexDb functionality is not fully built out and is still not usable.
