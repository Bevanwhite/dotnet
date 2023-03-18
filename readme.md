##### git remote
git remote - git@github.com-bevanwhite:Bevanwhite/dotnet.git

0. to create a dotnet project
    * `dotnet new -l` gives list of dotnet project that can be  build <br>
    * `dotnet -h` gives you a summary of what you can do with the current sdk
    * `dotnet --list-sdks` gives list of the sdks
    * `dotnet --list-runtimes` list of runtimes
 

1. using this configure the sdk <br>
`dotnet new globaljson --sdk-version=3.1.426`

2. in order to run it in the  command line
```
dotnet build && dotnet run
or 
dotnet build
dotnet run
```
3. what is is MVC pattern?
* mvc stands for model, view, controller
* mvc is an architectural design pattern.

4. role of model, view?
* model is responsible for data
* View is responsible for ui(user interface).
* controller is responsible for the flow of application bt accepting user input

5. understanding controller?
* it is in a .cs file which has some methods called action methods.
* when a request comes on controller, it actually hits an action method.
* Now everything depends on Action method what to return from it.
* it may return only view, only data, or both of them.

6. understanding Model?
* simple class which has some properties.
* model is udes to pass data from controller(action method) to view and vise versa.
* model is also used for server side data validation.
* some techniques we can generate client side validation also.
* it not mandatory that each action method will return some model.

7. understanding View?  
* a view is the ombination of html and C#.
* hence for C# applicationthe extension of view is .cshtml
* whatever you see on your browser is a view.
* not mandatory that each action method will return a view.
* when a view containing c# get rendered on browser then all its C# is coverted into HTML.
* it means on browser we will only see HTML and data

8. Benefits of Mvc
* separation of concern
* Each component has a specific job hence it is easy to debug the code.