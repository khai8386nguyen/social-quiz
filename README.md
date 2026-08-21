<!--
Scoring logic for the Whimsy Swirls froyo personality quiz:

Each answer is tagged with one (sometimes two) of six decision-making styles:
  doer    -> The Doer            -> Rainbow Rush
  planner -> The Planner         -> Honey Granola Bliss
  thinker -> The Thinker         -> Matcha Bloom
  laser   -> The Laser           -> Triple Chocolate Crunch
  follow  -> Follow Through      -> Salted Caramel Crunch
  storm   -> The Storm           -> Berry Burst

Every question contributes 2 points total. Answers tagged with a single style
give that style 2 points; answers tagged with two styles split the points,
giving 1 point to each.

Each category doesn't get the same number of scoring opportunities across
the 10 questions, so raw point totals aren't compared directly. Instead each
category's earned points are divided by that category's own attainable max
(the total it could have earned had every question's best-scoring option for
that category been picked). The style with the highest resulting percentage
wins (ties resolved in the order listed above), and that same percentage is
what's shown in the bars on the result screen.
-->
