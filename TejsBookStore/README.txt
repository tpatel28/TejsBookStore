﻿2023-10-31
0835
Created web application TejsBookStore using .Net 5.0 and authentication type Individual account type.

0837
Comment out "sslPort": 44396 to run project

0839
Created README.txt and added descriptions in it
Created README.md

0840
In startup.cs , comment out options => options.SignIn.RequireConfirmedAccount = true on line 35.

0841
Created Github Repository

0842
Reviewed all files mentioned in PPT.

0844
Added breakpoints in HomeControllers.cs for Home and Privacy pages.

0845
Downloaded SuperHero theme from Bootswatch.com . file name bootstrap.css

0850
Change name of bootstrp.css
Created new bootstrap.css
Added theme styles in it
Modified Site.css with Provided Site.css styles.

0853
In Layout.cshtml , Attached new bootstrap.css
Modified  Footer and anchor tags class properties.

0858
In _loginPartial.cshtml, removed text-dark from anchor tags.
Ran project and worked perfectly.

0901
Added provided scrpits and styles from CSS_JS.txt

0903
Added Dropdown in _Layout.cshtml

0908
Added 3 new Projects 
TejsBooks.DataAccess
TejsBooks.Models
TejsBooks.Utility
Copied Data folder to .DataAccess project

0913
Installed  2 packages described in PPT.
Delated migration folder from .DataAccess project.

0917
Installed Indentity.EntityFrameworkCore package

0920
Removed Class1.cs from three projects
Modified namespace ApplicationDbContext.cs

0921
Solved 3 eerors by adding project reference

0924
Moved models folder in .Models project
Modified Error.cshtml

0927
Added projects references to Main project
Modified namespace in Error.cshtml

0932
Added Project references to Minproject and .DataAccess project

0934
Added new area named Customer to Areas folder
Modified Startup.cs , added {area:exists}

0935
Moved HomeController.cs to Customer's Controller
Removed Data and Models folder 

0939
Modified Homecontroller.cs
Moved Views folder

0950
Moved _Viewimport and_Viewstart in customer Area.
Application ran successfully

0954
Added new Area named Admin
Deleted data and Models
Moved proper Views in that area

2023-11-06
1810
Started the project part 2

1812
changed this  "DefaultConnection": "Server=(localdb)\\mssqllocaldb;Database=TejsBookStore;Trusted_Connection=True;MultipleActiveResultSets=true"
1813
add-migration from the NuGet Package manager and changed the project to .DataAccess
1817
updateed the database
1820
Added the Category.cs in Models project
1822
added this to   public DbSet<Category> Categories { get; set; } in ApplicationDbContext.cs to add migration
1827
created new repository and irepository folder and added IRepository and Repository and added the code from the blackBorad.
1831
Added new categoryRepository and Interface file 
1839
Added new file and interface file named ISP_Call.cs and SP_Call.cs and installed Dapper in ISP_Call.cs
1843
Created new class and interface for UnitOfWork and commited to github
1847
Added -  services.AddScoped<IUnitOfWork, UnitOfWork>(); to startup.cs and with using statement
1900
Created new index.cshtml used template Empty(wihtout model) and added code from the blackbroad and modified the nav link
1907
Added the javascript file to index.cshtml and added code for the edit and delete action
1910
created upsert.cshtml and added the code from the blackborad and added two partial views
1915
modified the Upsert.cshtml
1921
added the deletlition functionality
1945
Check all the files and folder and run the application and checked all functionality

11-17-2023
1305

Cloned projects Started Part- 3
Added CoverType.cs model in models project and added Id and Name in it.

1313
Added new class CoverTypeRepository.cs in Repository and ICoverTypeRepository.cs interface in IRepository

1321
Added covertype to UnitOfWork and IUnitOfWork 

1335
Added Migration 20231117183442_AddedCoverTypeMigration.cs and Updated database 

1344
Added CoverType to the NavBar
Added CoverType Controller to Admin Area

1348
Added CoverType Index View and Upsert view to Admin Area
Added new coverType.js to add delete function

1534
Added new Product class to .Models project and solved errors.

1539
Added Reference to ApplicationDbContext.cs

1548
Ran migration in .Dataccess named 20231117204406_addProductToDb.cs
Updated database
Reviewed SOE and dbo.Products is there.

1558
Updated product class and added validation for title , author, ISBN.
added new migration 20231117210030_addValidationToProduct.cs in .Dataccess project.

1610
Added new class ProductRepository and Interface IProductRepository

1621
Added product to UnitOfWork and IUnitOfWork
Built Application, Ran perfectly.

1819
Added new Product Controller in Admin Area

1829
Added Product View Model in .Models project. 
Installed Microsoft.AspNetCore.Mvc.ViewFeatures package

1834
Commented out Upsert post method
Modified the API Call to include the Category and CoverType properties 

1849
Added new Index view To Product
Created product.js , copied code of category.js and renamed it.

1852
Added new link to product in  _Layout.cshtml
Tested Application , Ran perfectly

2023-11-27

1135
Cloned repository and started section 3 of part 3 

1140
Created account on tiny.cloud and took script code from it .

1142
Added upsert view code for product in admin area and added code from given files

1146
Created folder in wwwroot>images>products 

1152
uncommented code from productcontroller and added other necessary code in it.

1156
Modified Product.cs

1158
tested application ,ran perfectly

1200
Part-3 section -3 completed

1807
Added HttpPost in product controller and added the code for the image in upsert.cshtml of product
1812
Added the IUnitOfWork in HomeController.cs
1815
Added the index.cshtml for product to display the product and updated the product.js
1819
Added this services.AddControllersWithViews().AddRazorRuntimeCompilation(); to startup.cs
1827
Had an error when trying to click the product link then found out that there was an extra space in productController.cs. Removed it and ran it successfully.
1830
Added the images in the wwwroot folder 