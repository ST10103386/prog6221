# prog6221
**RecipeApp - Instructions for Compilation and Execution** 

  

This README provides instructions on how to compile and run the RecipeApp software, a command-line application with a graphical user interface (GUI) built using Windows Presentation Foundation (WPF). The RecipeApp allows users to enter and manage recipes, including ingredients, steps, and nutritional information. 

  

**System Requirements:** 

1. Windows Operating System (Windows 7 or later) 

2. .NET Framework 4.7.2 or later 

3. Visual Studio (for compiling and running the application) 

  

**Compilation:** 

1. Clone or download the RecipeApp repository to your local machine. 

2. Open the project in Visual Studio by navigating to the "RecipeApp" folder and double-clicking the "RecipeApp.sln" file. 

3. Once the project is loaded, build the solution by clicking on "Build" > "Build Solution" in the Visual Studio menu. 

  

**Execution:** 

1. After successful compilation, navigate to the "bin/Debug" or "bin/Release" folder (depending on your build configuration) within the "RecipeApp" project directory. 

2. Locate the "RecipeApp.exe" executable file. 

3. Double-click on "RecipeApp.exe" to run the application. 

  

**Using the RecipeApp:** 

1. When the application starts, you'll see a graphical user interface (GUI) with various controls and sections for managing recipes. 

2. To add a new recipe, enter the name of the recipe and click on the "Add Recipe" button. Follow the prompts to enter the details of the recipe, including ingredients and steps. 

3. To display all recipes, click on the "Display All Recipes" button. The list of available recipes will be shown in the "Recipes" section. 

4. To view the details of a specific recipe, select the recipe from the list in the "Recipes" section, and click on the "Display Recipe" button. 

5. To scale a recipe, select the recipe from the list and enter a scaling factor (e.g., 2 for double, 0.5 for half, etc.) in the "Scale Recipe by" text box. Click on the "Scale Recipe" button to apply the scaling. 

6. To filter recipes based on specific criteria, use the "Filter Recipes" section. You can filter recipes by ingredient name, food group, or maximum calories. Enter the desired filtering criteria and click on the "Filter" button to view the filtered recipes in the "Recipes" section. 

7. To reset the recipe list and start with a new set of recipes, click on the "Clear All" button in the "Recipes" section. 

  

**Important Notes:** 

1. The RecipeApp stores the data in memory during the application runtime. Data will not be persisted between application runs. 

2. To add or edit recipe details, use the provided controls in the GUI. The application will update the recipe list and display the relevant information accordingly. 

3. The application notifies the user when the total calories of a recipe exceed 300. 

4. Ensure that you have the necessary .NET Framework version installed on your machine to run the application successfully. 

  

Enjoy using the RecipeApp to manage your favorite recipes with ease! 
