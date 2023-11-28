2023-10-31
0836
Created the MVC project with the .NET 5.0 since there was an error in the previous attempt.

0838
Commented out the SSL portal in the properties and removed options => options.SignIn.RequireConfirmedAccount = true in the startup.cs file.

0839
In HomeController added the breakpoints between the line 22 and 27 and tested.

0842
Created the Git repository and commited the first changes.

0850
added the bootstrap.css from bootswatch.com also the site.cs file replaced provided in the blackboard.
changed the file name in the layout.cshtml

0856
Changed the navigation properties and changed the footer as well.

0859
removed the text-dark in the loginPartial

0902
Added 3rd party JS and CSS in the layout.

0905
Added the dropdown layout on the page works fine.

0908
Added three new project libraries into the solution folder.

0911
Data folder is added into the .DataAccess folder and deleted the original Data file.
installed the packages.

0915
Deleted the migration folder in Data file.

0918
Installed another NuGet package in the DataAccess folder.

0920
Deleted the class files in all the recently added three libraries.
modified the the namespace to AryasBookStore.DataAccess.Data

0924
Models folder is moved to the AryasBooks.Models project and deleted the original models folder.

0927
Change the ErrorViewModels.cs namespace .Models.ViewModels

0929
Modify Startup.cs service ‘AddContext’ with the using statement

0931 
Correct any default reference to ErrorViewModel to the new .Models.ViewModels.ErrorViewModels
0933
In the Utility project, create a static details class called SD.cs

Add project reference to the main project

0935
In the DataAccess project add project references to Models and Utility

0939
Added a ‘Customers’ area to Areas

0943
Edited the HomeController.cs to explicitly define that the controller is in the Customer Area

0945
Move Views > Home and modify the HomeController namespace

0948
Copy _ViewImport and _ViewStart to Customer Area, Modify the _ViewStart.cshtml to reflect the new path

0950
Add a new Admin area in Areas
Add the proper view files and delete the Data and Models folder

0953
Delete the Controllers folder
Update the GitHub repo


1953
created 2 migration named 
20231107004537_AddDefaultIdentityMigration
20231107005330_AddCategoryToDb

2008
created Repository folder and inside that created IRepository folder, And Added interface in IRepository


2021
created isp_call and sp_call

2025
added UnitOfWork and register it to index file

2026
commit to github

2031
created CategoryController

2035
created index view

2038
linked the category to dropdown menu

2042
created js file

2052
added Upsert view

2055
created two partial views.

2058
modified the code

2102
created delete function and all buttons works

2103
assignment complete

2023-20-11
1513
Cloned repository and started Part-III Section-1.

1515
Addded CoverType class in .Models project

1517
Added new CoverTypeRepository class to Repository folder and new ICoverTypeRepository interface to IRepository folder

1519
Added reference to ApplicationDbContext.cs

1520
Added CoverType to UnitOfWork and IUnitOfWork

1524
Ran migration 20231120202417_addCoverType.cs and updated database

1526
Added CoverType to navbar by adding it to _Layout.cshtml

1528
Added CoverType controller with all required mathods

1530
Created new folder CoverType to Views. Added Index and Upsert view in it

1532
Added coverType.js to add delete method

1534
Tested application , ran perfectly.

1536
Created new Product class to .Models and solved some errors

1539
Added its reference to ApplicationDbContext.cs

1540
Ran migration 20231120204024_addProductToDb.cs and updated database

1542
Reviewed SOE and reqiered validation is already added.
Ran migration 20231120204644_addValidationToProduct.cs and updated database

1546
Added new ProductRepository class to Repository folder
added new IProductRepository interface to IRepository folder

1550
Added Product to UnitOfWork and IUnitOfWork

1554
Built project , worked good
Finished Section - 1

1558
Started section-2 

1600
Added new ProductController to admin area for CRUD operations
Added some statements mentioned in PPT

1602
Added new Product viewmodel in Viewmodel in .Models folder

1604
Installed Microsoft.AspNetCore.Mvc.ViewFeatures package and added statement in ProductController.cs

1608
Commented out Upsert post method
Modified API call

1613
Added Index view to Product in Admin area

1615
Created product.js by using category.js code and modifying it

1616
Added Product to navbar by updating _Layout.cshtml

1618
tested application, ran as expected, clicked continue
completed section-2

2023-11-27
2110
Cloned repository , started section3 part-3 

2112
Added Upsert view to product and added code to it from provided file, created account on tiny.cloud and copied script from it and added to Upsert scripts.

2115
Uncommented Upsert method in  productcontroller

2118
Modified foriegn key in Product.cs , ran migration 20231128021826_updatedForeignKey.cs and updated database

2122
Tested Application , Ran perfectly, part-3 completed

2124
Started Part-4 

2126
Added httppost method and httpdelete method in productcontroller

2128
Added IUnitOfWork reference to customer area HomeController.cs