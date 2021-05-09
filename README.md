# orvCoreProto
orvCore Js Library. Some handy core functionality. At this point it is a *working prototype*.

- Note that at this point, there are a bunch of stubs in here that do not have their functionality yet.
- It does have error handling functionality which allows you to display nicely formatted error messages on the web page while working on the development of your site.
- It has some @CodePen functionality that you can use when including it in a Pen on @CodePen...
 - It has a property: ```codepenId``` which will return the CodePen Id (if being run from a Pen). Otherwise it will return a blank string.
 - It has a property: ```codepenView``` which returns the *view* of the Pen. If the page is not a pen it will return the string: 'notAPen'.
- It has a ```currentVersion``` property which will return the version of the library you are currently using.
