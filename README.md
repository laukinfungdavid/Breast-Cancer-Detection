# Breast Cancer Detection

<p>This project makes use of KNN to detect breast cancer using the Breast Cancer Wisconsin (Diagnostic) dataset.</p>
<p>Dataset: https://github.com/dataspelunking/MLwR/blob/master/Machine%20Learning%20with%20R%20(2nd%20Ed.)/Chapter%2003/wisc_bc_data.csv</p>

<h1> Different Experiments </h1>
<ol>
  <li>different values for k</li>
  <li>different ways to do the voting (for k>2), such as
    <ul>
      <li>adding weights to the votes according to distance;
      <li>adding a threshold such the ones that are too far off are dropped;
      <li>if there is a tie, reduce or increase k until there's a clear winner;
    </ul>
  </li>
  <li>different ways of splitting the data.</li>
</ol>


<h1> Result </h1>
<p>Accuracy when using the normal way to implement the algorithm:  98.0 %</p>
<p>Accuracy when adding weight according to the distance:  98.0 %</p>
<p>Accuracy when trying different k values ( 21 ):  98.0 %</p>
<p>Accuracy when trying different k values ( 234 ):  89.0 %</p>
<p>Accuracy when trying different k values ( 156 ):  91.0 %</p>
<p>Accuracy when trying different k values ( 117 ):  92.0 %</p>
<p>Accuracy when using the normal way to implement the algorithm (handle tie):  98.0 %</p>
<p>Accuracy when spliting the data randomly:  97.5 %</p>
<h1> Conclusion </h1>
From different experiments, I found out that by spliting data randomly and adding weight according to the distance can sometimes get an accuracy that is higher than 98% but it is not a must as sometimes it may be lower than 98%.
