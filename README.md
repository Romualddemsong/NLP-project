Objective:
Given a review, determine whether the review is positive or negative.
How to determine if a review is positive or negative?
We could use the Score/Rating. A rating of 4 or 5 could be cosnidered a positive review. A review of 1 or 2 could be considered negative. A review of 3 is nuetral and ignored. This is an approximate and proxy way of determining the polarity (positivity/negativity) of a review.
There are a total of 10 columns in total in the Amazon Fine Food review dataset.

Id : Row Id
ProductId : Unique identifier for the product.
UserId : Unique identifier for the user.
ProfileName : Profile Name of the User.
HelpfulnessNumerator : Number of users who found the review helpful.
HelpfulnessDenominator : Number of users who indicated whether they found the review helpful or not.
Score : Rating between 1 and 5.
Time : Timestamp for the review.
Summary : Brief summary of the review.
Text : Text of the review.
