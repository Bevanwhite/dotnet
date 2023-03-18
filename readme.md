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
