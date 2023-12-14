To run the project, you should open the NuGet Package Manager Console and type:
 - `Update-Database`

If you want to customize this project, you need to create a new dataset in the database context and migrate it:
  1. `Add-Migration NewDbSet` (your name)
  2. `Update-Database`
