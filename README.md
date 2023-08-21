# percentage

team_ct rating 
team_t_rating

calculateWinProbabilities takes two arguments:
calculateWinProbabilities(team1Rating,team2Rating)
The ratings of the two teams are used to calculate the win probabilities.

The function works as follows:
First, it calculates the rating difference between the two teams:

ratingDifference = team1Rating - team2Rating
It then applies a scaling factor of 0.0043 to the rating difference:

ratingDifferenceScaled = ratingDifference * 0.0043
This scaled rating difference is then passed to the mathematical function Math.exp, which calculates the exponential of the given number.

The result is stored in the variable exponential.
