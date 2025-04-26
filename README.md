# comp210-assignment-2--getting-warmer-solved
**TO GET THIS SOLUTION VISIT:** [Comp210 Assignment 2- Getting Warmer Solved](https://www.ankitcodinghub.com/product/comp210-getting-warmer-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;131770&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Comp210 Assignment 2- Getting Warmer Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
Like Assignment 1, this assignment is intended to further warm-up your basic programming skills and can be done without any object-oriented programming using built-in data types and arrays with loops and conditional execution.

A2Novice

This program reads in a list of ingredients used by a restaurant and prints out information derived from the list.

The first input to the program will be an integer number that indicates the number of ingredients. Following this, for each ingredient will be a line with the form:

Ingredient_Name Price_Per_Ounce Is_Vegetarian Calories_Per_Ounce

Ingredient_Name is a single word token naming the ingredient. Price_Per_Ounce will be a real value indicating the cost of the ingredient in dollars per ounce. Is_Vegetarian will be the token “true” or “false” indicating whether the ingredient is vegetarian. Calories_Per_Ounce will be an integer indicating the caloric content of the ingredient per ounce.

The program should count the number of vegetarian ingredients and report which ingredients provide the highest and lowest ratios of calories per dollar.

The output should be formatted as follows:

Number of vegetarian ingredients: &lt;NumberOfVegetarianIngredients&gt; Highest cals/$: &lt;IngredientWithHighestRatio&gt; Lowest cals/$: &lt;IngredientWithLowestRatio&gt;

where the angle bracketed items are placeholders for the actual answers.

For example, the following input:

6 Rice 0.12 true 37 Seaweed 2.95 true 113 Avocado 0.22 true 45 Salmon 1.77 false 48 Yellowtail 0.53 false 41 Eel 2.18 false 84

Should produce the following output:

Number of vegetarian ingredients: 3 Highest cals/$: Rice Lowest cals/$: Salmon

A2Adept

This program first reads in a list of ingredients as specified for A2Novice and then a list of menu item recipes and prints out information about the menu items.

The input to this program starts with the ingredient list in the same form as for A2Novice. Following this will be an integer indicating the number of menu item recipes followed by that many recipes.

Each menu item recipe will start with a single word token name for the menu item. Following the name will be an integer indicating how many ingredients are in the recipe. Then there will be a line for each ingredient with the ingredient name followed by the number of ounces of this ingredient required for the menu item.

For each menu item, the program should produce output describing the number of calories in the menu item, the total cost of the ingredients used, and an indication whether that menu item is “Vegetarian” or “Non-Vegetarian”. A menu item is vegetarian if all of its component ingredients are vegetarian.

The output for each menu item should be formatted as follows (again, bracketed items are placeholders for values to be determined by the program):

&lt;Menu_Item_Name&gt;: &lt;CalorieCount&gt; calories $&lt;Cost&gt; &lt;“Vegetarian” or “Non-Vegetarian”&gt;

CalorieCount should be rounded to the nearest integer. Cost should be rounded to two decimal places.

To round a double to the nearest integer as an int, use the following expression (assume dval is the value that needs to be rounded):

((int) (dval + 0.5))

To print a double to two decimal places, use the following expression to produce the appropriate string:

String.format(“%.2f”, value)

For example, the following input:

“` 6 Rice 0.12 true 37 Seaweed 2.95 true 113 Avocado 0.22 true 45 Salmon 1.77 false 48 Yellowtail 0.53 false 41 Eel 2.18 false 84

4 Avocado_Roll 3 Rice 0.5 Avocado 0.5 Seaweed 0.1

Unagi_Nigiri 2 Rice 0.75 Eel 0.75

KMP_Roll 4 Eel 0.6 Rice 0.4 Seaweed 0.2 Avocado 0.3

Salmon_Sashimi 1 Salmon 0.8 “`

Should produce the following output:

Avocado_Roll: 52 calories $0.47 Vegetarian Unagi_Nigiri: 91 calories $1.73 Non-Vegetarian KMP_Roll: 101 calories $2.01 Non-Vegetarian Salmon_Sashimi: 38 calories $1.42 Non-Vegetarian

A2Jedi

This program reads in a list of ingredients and menu item recipes as specified for A2Adept and then a list of menu items that are part of an order. It should produce an account of how much of each ingredient will be needed to fulfill the whole order.

The first part of the input is the same as A2 Adept. This is followed by a sequence of menu item names that are part of the order. An item can appear more than once or not at all. There will be at least one item. The end of the order will be signalled by the word “EndOrder”

The program should produce an accounting for the total amount of each ingredient required for the order. The ingredients should be listed in the same order as they were provided in the initial ingredient list input and have the following format:

The order will require: &lt;Ingredient1TotalAmount&gt; ounces of &lt;Ingredient1&gt; &lt;Ingredient2TotalAmount&gt; ounces of &lt;Ingredient2&gt; &lt;Ingredient3TotalAmount&gt; ounces of &lt;Ingredient3&gt; … &lt;IngredientNTotalAmount&gt; ounces of &lt;IngredientN&gt;

Note, the “…” above simply indicates possible additional lines of the same form. Ingredient amounts should be printed rounded to two decimal points.

For example the following input:

“` 6 Rice 0.12 true 37 Seaweed 2.95 true 113 Avocado 0.22 true 45 Salmon 1.77 false 48 Yellowtail 0.53 false 41 Eel 2.18 false 84

4

Avocado_Roll 3 Rice 0.5 Avocado 0.5 Seaweed 0.1

Unagi_Nigiri 2 Rice 0.75 Eel 0.75

KMP_Roll 4 Eel 0.6 Rice 0.4 Seaweed 0.2 Avocado 0.3

Salmon_Sashimi 1 Salmon 0.8

Avocado_Roll Unagi_Nigiri Unagi_Nigiri Unagi_Nigiri KMP_Roll Salmon_Sashimi Avocado_Roll KMP_Roll EndOrder “` should produce the following output:

The order will require: 4.05 ounces of Rice 0.60 ounces of Seaweed 1.60 ounces of Avocado 0.80 ounces of Salmon 0.00 ounces of Yellowtail 3.45 ounces of Eel
