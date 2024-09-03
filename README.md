# OrcaleCMS
This is project based on the task requirement.

This is the description of how I worked on the task
1) I added the necessary packages 
- MicrosoftEntityFrameworkCore
- MicrosoftEntityFrameworkCore.SqlServer
- MicrosoftEntityFrameworkCore.Tools
- Swashbuckle.AspNetCore.Swagger
- Swashbuckle.AspNetCore.SwaggerGen
- Swashbuckle.AspNetCore.SwaggerUI

2) I created the Model Folder with 2 models
- Cars.cs
	- int CarID
	- string Make
	- string Model
	- int Year
	- int Stock
- ApiDbContext.cs
	- For DbContext
	- For DbSet of Cars

3) I added the connection string to the database in appsetting.json

4) I added the model and entityframeworkcore package to program.cs
5) I also added the DbContext to program.cs

6) I created a database(Car) on SSMS
7) I created a table(Cars) in the database
8) I added the columns (CarId, Make, Model, Year, Stock) to the table

9) I created a controller (CarApiController.cs) and 5 api methods
- GetAllCar (Retrieves all cars in the table
- GetCarById (Retrieves a specific car info by it's CarId
- UpdateCar (Updates a car info specified by it's CarId)
- DeleteCar (Deletes a car info specified by it's CarId)
- SearchCar (Retrieves a specific car info by it's make and model.

10) I was not able to dockerize it because I was doing the project on my tablet. 
