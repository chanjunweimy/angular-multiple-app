# angular-multiple-app

This repository contains of a **ASP.net Core 2.0 Web application project** and three angular applications, 
which located in **MultipleApp/main**, **MultipleApp/sub-one**, **MultipleApp/sub-two**.

### About this project
1. Goal: To develop multiple modules of a project parallelly without depending on each other.
2. Method: Creating multiple angular cli app which each app correspond to a module.

### Quick-Start
1. Clone this repository ````git clone https://github.com/chanjunweimy/angular-multiple-app.git````
2. ````cd angular-multiple-app/MultipleApp````
3. ````npm install````
4. ````npm run build-all````
5. ````dotnet run````
6. Open ````http://localhost:52440```` in a browser.
    1. **MultipleApp/main**: ````http://localhost:52440````
    2. **MultipleApp/sub-one**: ````http://localhost:52440/sub-one````
    3. **MultipleApp/sub-two**: ````http://localhost:52440/sub-two````
    
### Implementation of the concept
The concept is implemented in [abp_plugin_with_ui](https://github.com/chanjunweimy/abp_plugin_with_ui). Feel free to give comment! Thanks!
