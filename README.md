# personal_projects
Projects I've Done for my Own Reference and Practice

# Dice Experiment
My roommates and I have a board game where your movement on the board depends on the sum you are able to roll with a die configuration you choose.

Higher sums are always better. The minimum value to avoid a penalty changes for each turn.

The following configurations are available:

Base Configurations:
- 6-Sided Die: Roll 3 die. Sum all values.

Level 1 Configurations:
* 6-Sided Die // Roll 4 die. // Sum 3 highest values.
* 10-Sided Die:           Roll 2 die. Sum all values.
* 20-Sided Die:           Roll 1 die. = rolled value.

Level 2 Configurations:
- 6-Sided Die:            Roll 5 die. Sum 3 highest values.
- 10-Sided Die:           Roll 3 die. Sum 2 highest values.
- 20-Sided Die:           Roll 2 die. Retain highest value.

Level 3 Configurations:
- 6-Sided Die:            Roll 6 die. Sum 3 highest values.
- 10-Sided Die:           Roll 4 die. Sum 2 highest values.
- 20-Sided Die:           Roll 3 die. Retain highest value.

Any configuration above the base configuration requires purchase in the game. Configurations of the same level have the same cost.

This script produces a probability table to determine how likely I am to receive a desired minimum roll value with each purchased dice configuration.

It's been a big success. :)

# Confidence Interval Sim
This is a simulation I made to show how confidence intervals change for each sample. I took 20 samples (n=30) and calculated the confidence interval for each. I plotted the histgoram of data with markers for the CI as well as the population proportion to show how placement of \mu changes within the intervals.

This was an exercise I made for the recitation I lead, but ultimately didn't use. The course I work with is an elementary stats course, and I got carried away creating this exercise a bit above the class level.
