###Diet Optimization With USDA Nutrition Data

####Data Set:
Sandra's original dataset contains nutrition and portion information for a large set of foods.

I have created a condensed version that contains the info that **I** thought was important.  **Please feel free to contribute your own interpretation of the original data set.**

####Problem:
Starting with one user-selected food, find a combination of 5 foods (food + portion) which meet the user’s constraints

Sandra's two sets of constraints for the Mimic Fasting diet are:
* 1090 calories
	* 10% Protein
	* 56% Fat
	* 34% Carbs
* 725 calories
	* 9% Protein
	* 44% Fat
	* 47% Carbs

####More Details:
We have determined that this problem is essentially the [knapsack problem](https://en.wikipedia.org/wiki/Knapsack_problem), which is considered to be [intractable](https://en.wikipedia.org/wiki/Computational_complexity_theory#Intractability).

There are some suggested "solutions" to the [knapsack problem](https://en.wikipedia.org/wiki/Knapsack_problem) on the wikipedia page.  I would encourage you to explore them. [Dynamic Programming](https://en.wikipedia.org/wiki/Dynamic_programming) is one that I have a small amount of experience with.

There may also be some interesting optimization algorithms which are capable of finding good suggested solutions if you frame this as an optimization problem. Many flavors of  [Hill Climbing](https://en.wikipedia.org/wiki/Hill_climbing) exist.  Some more advanced options include [Simulated Annealing](https://en.wikipedia.org/wiki/Simulated_annealing) and [Genetic Algorithms](https://en.wikipedia.org/wiki/Genetic_algorithm).

**Also, feel free to experiment with finding solutions intuitively by manipulating the data in an educated way.** For example, you may be able to eliminate large areas of the feature space by eliminating food combinations that a person would be highly unlikely to eat together.

###Keep In Touch
* Join the Chadev slack: http://Chadev-slackin.herokuapp.com
* Post comments to the meetup page: http://www.meetup.com/Chattanooga-Data-Science/events/224403955/
* If you have an interpretation of the dataset, or code you want to share, submit a PR on this repo.
* **Bring your ideas and solutions to the next meetup!**
