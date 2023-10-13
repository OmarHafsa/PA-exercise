﻿# PA-exercise
<h2>Exercise 1:</h2>
  Write the prototype and defintion of the following procedure:
  <h5>int remplirTableauAvecEntiersAleatoires(int *tab, int size, int maxValue</h5>
<p>Use the function: <h4>rand()</h4>from: <h4>stdlib.h</h4></p>
<p>The expression (int)(rand() / ((double)RAND_MAX + 1) * valeur_max) is used to generate a random integer within the range [0, valeur_max) by scaling the output of the rand() function. Let's break down the components of this expression:

rand(): This generates a random integer between 0 and RAND_MAX.
(double)RAND_MAX + 1: This converts RAND_MAX to a double and adds 1 to it. This is done to ensure that when you divide rand() by this value, you get a floating-point number between 0.0 (inclusive) and 1.0 (exclusive).
rand() / ((double)RAND_MAX + 1): This part of the expression generates a random floating-point number between 0.0 (inclusive) and 1.0 (exclusive).
Multiplying by valeur_max: This scales the random floating-point number from the previous step to the desired range. If valeur_max is, for example, 10, then you will get a floating-point number in the range [0.0, 10.0), which is what you want.
(int): Finally, the result is cast to an integer. This truncates the decimal part of the floating-point number and gives you a random integer within the range [0, valeur_max), as required by the function.</p>

<h2>Exercise 2:</h2>
Creating main function  

<h2>Exercise 3:</h2>
Declaring and defining a procedure of selection sort
