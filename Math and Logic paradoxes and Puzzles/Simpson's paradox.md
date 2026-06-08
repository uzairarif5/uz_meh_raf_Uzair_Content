# Simpson's Paradox (Incomplete)

Simpson's paradox is a phenomenon in probability and statistics in which a trend appears in several groups of data but disappears or reverses when the groups are combined.

## Example: University of California's Graduate School Admissions (From Wikipedia)

The table below shows the admissions of the six largest deparments of University of California:

<table>
<thead>
  <tr><th rowspan="2">Department</th><th colspan="2">All</th><th colspan="2">Men</th><th colspan="2">Women</th></tr>
  <tr><th>Applicants</th><th>Admitted</th><th>Applicants</th><th>Admitted</th><th>Applicants</th><th>Admitted</th></tr>
</thead>
<tbody>
  <tr><th>A</th><td>933</td><td>64%</td><td><b>825</b></td><td>62%</td><td>108</td><td>82%</td></tr>
  <tr><th>B</th><td>585</td><td>63%</td><td><b>560</b></td><td>63%</td><td>25</td><td>68%</td></tr>
  <tr><th>C</th><td>918</td><td>35%</td><td>325</td><td>37%</td><td><b>593</b></td><td>34%</td></tr>
  <tr><th>D</th><td>792</td><td>34%</td><td>417</td><td>33%</td><td>375</td><td>35%</td></tr>
  <tr><th>E</th><td>584</td><td>25%</td><td>191</td><td>28%</td><td><b>393</b></td><td>24%</td></tr>
  <tr><th>F</th><td>714</td><td>6%</td><td>373</td><td>6%</td><td>341</td><td>7%</td></tr>
  <tr><th>Total</th><th>4526</th><th>39%</th><th>2691</th><th>45%</th><th>1835</th><th>30%</th></tr>
  </tbody>
</table>

Just by looking at the total, you would think that men are admitted more than woman, but when looking at each department, you would realize that generally, it is the women that are admitted more.


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

An outlier changing an average is simply a math consequence of how the mean is calculated, whereas Simpson's Paradox involves a trend reversing when you split or combine data groups.