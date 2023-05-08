Download Link: https://assignmentchef.com/product/solved-robotics-project1-puma-560-robot-manipulator
<br>
For a PUMA 560 robot manipulator with the following kinematic table,

<table width="227">

 <tbody>

  <tr>

   <td width="58">Joint</td>

   <td width="51">d(m)</td>

   <td width="51">a(m)</td>

   <td width="43"><em>α</em></td>

   <td width="22"><em>θ</em></td>

  </tr>

  <tr>

   <td width="58">1</td>

   <td width="51">0</td>

   <td width="51">0</td>

   <td width="43">-90<sup>◦</sup></td>

   <td width="22">0◦</td>

  </tr>

  <tr>

   <td width="58">2</td>

   <td width="51">0</td>

   <td width="51">0.432</td>

   <td width="43">0◦</td>

   <td width="22">0◦</td>

  </tr>

  <tr>

   <td width="58">3</td>

   <td width="51">0.149</td>

   <td width="51">-0.02</td>

   <td width="43">90<sup>◦</sup></td>

   <td width="22">0◦</td>

  </tr>

  <tr>

   <td width="58">4</td>

   <td width="51">0.433</td>

   <td width="51">0</td>

   <td width="43">-90<sup>◦</sup></td>

   <td width="22">0◦</td>

  </tr>

  <tr>

   <td width="58">5</td>

   <td width="51">0</td>

   <td width="51">0</td>

   <td width="43">90<sup>◦</sup></td>

   <td width="22">0◦</td>

  </tr>

  <tr>

   <td width="58">6</td>

   <td width="51">0</td>

   <td width="51">0</td>

   <td width="43">0◦</td>

   <td width="22">0◦</td>

  </tr>

 </tbody>

</table>

−160<sup>◦ </sup>≤<em>θ</em><sub>1 </sub>≤ 160<sup>◦</sup>, −125<sup>◦ </sup>≤<em>θ</em><sub>2 </sub>≤ 125<sup>◦</sup>

−135<sup>◦ </sup>≤<em>θ</em><sub>3 </sub>≤ 135<sup>◦</sup>, −140<sup>◦ </sup>≤<em>θ</em><sub>4 </sub>≤ 140<sup>◦</sup>

−100<sup>◦ </sup>≤<em>θ</em><sub>5 </sub>≤ 100<sup>◦</sup>, −260<sup>◦ </sup>≤<em>θ</em><sub>6 </sub>≤ 260<sup>◦</sup>

please write a program for the following two transformations:

<ul>

 <li>input: Cartesian point (n, o, a, p), output: the corresponding joint variables.</li>

 <li>input: joint variables, output: Cartesian point (n, o, a, p) and (x, y, z, <em>φ</em>, <em>θ</em>, <em>ψ</em>).</li>

</ul>

1