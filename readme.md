<h1>Insertion Sort</h1>
<h2>Q1 </h2>
[22,27,16,2,18,6]

[22|27,16,2,18,6]
[22,27|16,2,18,6]
[22,16,27|2,18,6]->[16,22,27|2,18,6]
[16,22,2,27|18,6]->[2,16,22,27|18,6]
[2,16,22,18,27|6]->[2,16,18,22,27|6]
[2,16,18,22,6,27]->[2,6,16,18,22,27]

<h3> Big O Notation</h3>
n = 6, O(6^2) <br>
<h3>Time Complexity</h3>
Best Case=6 <br>
Worst Case 6^2 <br>
Average Case log6

Dizi sıralandıktan sonra 18 sayısı average case kapsamına girer.
<h2>Q2</h2>
[7,3,5,8,2,9,4,15,6] <br>
1. 3,7|5,8,2,9,4,15,6 <br>
2. 3,5,7|8,2,9,4,15,6 <br>
3. 3,5,7,8|2,9,4,15,6 <br>
4. 3,5,7,2,8|9,4,15,6->2,3,5,7,8|9,4,15,6