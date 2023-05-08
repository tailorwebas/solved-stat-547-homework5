Download Link: https://assignmentchef.com/product/solved-stat-547-homework5
<br>
<ol>

 <li>Using fdapace, simulate <em>n </em>= 50 curves for each scenario and perform a functional principal component analysis. Consider the following scenarios:

  <ul>

   <li>Dense or sparse observations are available.</li>

   <li>The true number of components <em>K </em>equals 3 or 20. For <em>K </em>=20, use an appropriate eigenvalue sequence (you can visualize the curves to decide what is appropriate).</li>

   <li>Vary the noise level to be high or low.</li>

  </ul></li>

</ol>

Write a short paragraph reporting what you find for each of the following tasks. You may need FPCA, MakeGPFunctionalData, and MakeSparseGP.

<ul>

 <li>Investigate the number of components chosen by different selection methods. Hint: use the methodSelectK option of FPCA.</li>

 <li>For dense observation, compare the estimated FPC scores using the BLUP method and the integration method. Hint: use the methodXi option of FPCA.</li>

 <li>For sparse observations, compare the estimated FPC scores using the BLUP method and the true scores.</li>

</ul>

<ol start="2">

 <li>Extend the PACE method for bivariate sparsely observed longitudinal data, and create a rudimentary implementation. Apply your implementation to analyze the bivariate process of height and body length growth of Tammar wallabies. Since the scales of the two processes vastly differ you may want to normalize them before the analysis.</li>

</ol>

Reference: Chiou, Chen and Yang (2014), https://www.jstor.org/stable/24310959

1