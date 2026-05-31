# Simpson's Paradox

## The following is not a Simpson's paradox

Alice and Bob are two students who participated in 4 Math competitions, each was focused on a different category of Maths. Out of 4 Math competitions, Alice's total score was 54.5 out of 100, while Bob's total score was 39 out of 100. The total score is the average of four scores. Looking at the total scores, you would think that Alice is better than Bob in Maths.

Now let's look at the individual competition scores:

<table>
  <thead>
    <tr><th>Subject</th><th>Alice's Scores</th><th>Bob's Scores</th></tr>
  </thead>
  <tbody>
    <tr><th>Geometry</th><td>62</td><td>72</td></tr>
    <tr><th>Calculus</th><td>63</td><td>67</td></tr>
    <tr><th>Probability & Statistics</th><td>90</td><td>13</td></tr>
    <tr><th>Number theory</th><td>3</td><td>4</td></tr>
  </tbody>
</table>

After looking at each scores, we can check that the averages are infact 54.5 and 39. However, Bob got a higher score than Alice on three subjects, while Alice got higher only on one. This means that overall, it is Bob who is better in Maths.

Can you think of why this happens?

This happens because of the extreme case in the Probability & Statistics scores. Even though Bob's score is higher than Alice's in three subjects, their scores are not more than 10%. When considering these three subjects only, Bob's average is higher. However, because Alice got a higher score in Probability & Statistics, and the score difference is more than 70%, Alice's average ended up being higher than Bob's.