# Shopping-list-generator
Jupyter notebook using Spoonacular API to recommend healthy personalised recipes matching individual dietary requirements and create a weekly shopping list. Developed in collaboration with Stewart Buchan (https://github.com/stewartbuchan) as part of a Science to Data Science (S2DS) fellowship project

In more detail:
The user inputs their age and activity level and from this the program calculates the diatry requirments of the user based on current NHS guidelines.

Later the user can ask for n days of recipes.

The code will query the Spoonacular database of recipes to return lunches and dinners which it breaks down into ingredients.

nb. This program was developed before Spoonacular released their 'Complex Recipe Search' API which would dramatically reduce the number of API requests the program uses.

