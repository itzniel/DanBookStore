
Started the Assignment-2 inh class on the lab computer
Set uip the ASP.NET MVC w/core 1.3(out- of support)
HTTPS enabled, individual account authentication ... no RAzor 
Reviewed the Areas folder, controller, Model, View
1506 in startup.cs (Line 33)
removed options for default identity:
options=> options.SignIn.RequireConfirmedAccount = true
1510
Tested the App .. ran it and it was goosd... tested the link as well
Action Items:
-Modify the Navigation
1516
Modified the default welcome message
review the route pattern in startup.cs
-Update the Copyright.. from static to Dynamic

2023-03-03
1510 clone my repository UwaguosaBookStore in Github.. test it 
1550
Created the READ.md File and pulled it.

2023-03-09
@1412 cloned my repository 
@1420 Created a navigation for books in the shared views
@1425 Selected the bootstrap theme from bootswatch and downloaded the bootstrap.css
@1430 
Replaced the existing bootstrap.css in the lib/bootstrap/dist/css with the downloaded bootstrap 
Also replaced the site.css in the main css folder with the downloaded bootstrap.css
Changed the file name from bootstrap.min.css to bootstrap.css in the shared _layout.cshtml head
Changed the nav class from navbar-light to navbar dark and bg-white to bg-primary
removed the text-dark in line 23, Added "text-white-50 bg-primary" to the footer class 
Replaced the @RenderSection("script, required:false") with @await RenderSectionAsync("script, required:false") in line 48
In the _LoginPartial.cshtml removed the "text dark" in line 9
Ran the project and the theme was updated.
@1510 Added addidtional stylesheet  and JS to the _Layout.cshtml page 
@1525 Added a Dropdown menu in the navigation bar
ran it but the drop down did not work
@1540 then I replaced the id with "navbarDropdownMenuList" and added "data-toggle="dropdown""
also replaced the aria-labelledby with "navbarDropdownMenuList"
@1555 Ran the app and the dropdown worked 

2023-03-10
@1427 Made three new projects (DanBooks.DataAccess, DanBooks.Model, DanBooks.Utility)

2023-04-03
@1500 Installed the Microsoft.EntityFrameworkCore.Relational" Version=3.1.32",Microsoft.EntityFrameworkCore.SqlServer" Version="3.1.32,
Microsofyt.AspNEtCore.Identity.EntityFrameworkCore Version 3.1.32
2023-03-16
@1200 Modified the namespace and deleted the class1.cs file then I did build the project , had some errors
@1230 moved the models into DanBooks.Model, modified the error.cshtml
@1300 Added a project reference in the DanBookStore.proj then renamed the Model folder to ViewModels
Changed the namespace in the ErrorViewModels.cs to .Model.ViewModels, Built the project and it ran fine
@
2023-03-22
@1700 Created a static details class called SD.cs in the utility project, modified the class
@1715 In the DataAccess project added the projec refernces to Models and Utility
@1745 Added a customer area to he Areas, then changed the route with the text given in the scaffoldingReadMe.txt
Moved the HomeController.cs to the Area > Customer > Controller folder and deleted Data and Models.
Edite the HomeController.cs to explicitly define that the controller is in the Customer Area
Moved the Views > Home and modify the HomeController namespace
@1815 ran the Application and everything went to default
@1825Copied _ViewImport and _ViewStart to Customer Area and modified the _viewStart.cshtml to reflect new path
@1838 Ran the application and everything worked out fine

@1900 Added a new Admin area in Areas
Added the proper view files and deleted the Data and Models folder
Deleted the Controllers folder
Updated my GitHub repository

2023-03-23
@1205 Reviewed appsettings.json and made the require changes
@1211 Created the migration using code-first , Using the nuget Package manager console 
Added a migration with the name 20230406152540_AddDefaultIdentityMigration.cs
Updated database in PM console 
@1230 Added a new table to the DB by creating a Category model and pushed it to the DB:@
@1238 Added a new class file to the .Models project and modified it
@1245  Added the migration via the PM Console
Updated this and new statements were  added
@1300 Updated the database, confirmed the new Categories table via the SQL SOE and pushed my commits to GitHub







