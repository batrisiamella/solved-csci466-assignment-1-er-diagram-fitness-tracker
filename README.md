Download Link: https://assignmentchef.com/product/solved-csci466-assignment-1-er-diagram-fitness-tracker
<br>
You are being employed by a company that offers a fitness tracking service. They are working on a phone app that will allow the user to track what they eat, as well as when/how they work out. Another employee will be designing the user interface, but you are responsible for designing the database. <strong>Design an ER diagram to fulfill this goal</strong>, making sure to meet all of the requirements. All entities must have an appropriate identifier specified. If a surrogate key is used, explain why a natural key was not appropriate. In the interests of saving space, attributes that are not part of an identifier may be omitted from the diagram, but they should be included and explained in that portion of your submission. (See “What to turn in?” below.)

<h2>Requirements</h2>

<ul>

 <li>Every user will have an account, and all of their meals and workouts will be linked to this account.</li>

 <li>To track weight loss, the user will update their weight periodically. This data must be retained.</li>

 <li>The serving size will be some number of <em>units </em>(grams, ounces, Tbsp, cups, lbs, etc.). There will be information stored for conversion between different unit types.</li>

 <li>There will need to be a database of foods/beverages. Each of these will have information on serving size, calories per serving, and grams per serving of each of the macronutrients (protein, fat, carbohydrates). • It should be possible to store information on the quantities of micronutrients or chemicals (i.e. vitamin D, caffeine) that are present in a given food or beverage in significant amounts. Recommended daily values for any of these should be stored, when applicable.</li>

 <li>Each time the user eats, a record of who ate how many servings of what and when is stored.</li>

 <li>The app needs to allow a user to track their workouts. This includes the type of the workout, its intensity, and its duration.</li>

 <li>When a user tracks their workout, a record is created of who did what type of workout, when, and for how long.</li>

</ul>

<strong>Note: </strong>If you are not sure what needs to be included for foods/drinks/etc., a good place to look for example data would be the nutritional facts on food packaging.

<h2>NecessaryViews</h2>

The database needs to be able to store its operational data in such a way that the final app will be able to show the following views (at minimum). You don’t need to implement the views, but the necessary data should be modeled.

<ul>

 <li>A graph will be generated of how many calories a user consumed each day of the week.</li>

 <li>A similar graph will be generated that shows how many calories were burnt each day of the week through workout.</li>

 <li>Show a pie graph of the percentage of the diet made up of each macronutrient during a given time period (day, week, month).</li>

 <li>Track the consumption of a given micronutrient/chemical over a specified period of time. If there is a recommended daily value, show a comparison of their consumption with the recommended amount.</li>

 <li>Allow the user to search through the food database to find common foods, in order to plan their diets. These same foods will be used to track their eating.</li>

 <li>The user will search through a list of workouts to find the one closest to the one they’re going to do, in order to track the activity.</li>

</ul>

A line graph of user weight over time