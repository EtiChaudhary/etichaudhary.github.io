---
layout: page
title: Pinaka
description: Verifier for C Programs
img: /assets/img/pinaka_star.png
---

Pinaka is single-path symbolic execution engine that makes use of eager infeasibility checks and incremental-solving.

Pinaka has been participating in an international software verification competition, SVCOMP, for the past 2 years. It is the **first ever** verifier from Indian academia to qualify in SVCOMP.

Here's an overview of Pinaka's performance (i.e the *positions bagged* in different categories). 
<div class="my_table_style">
<table align="center">
<thead>
	<th> Category </th>
	<th> SVCOMP 2019 </th>
	<th> SVCOMP 2020 </th>
</thead>
<tr>
	<td style="text-align: left"> ReachSafety </td>
	<td> - </td>
	<td> 8 </td>
</tr>
<tr>
	<td style="text-align: left"> -&nbsp;&nbsp;&nbsp;&nbsp;ReachSafety-Floats </td>
	<td> 2 </td>
	<td> 3 </td>
</tr>
<tr>
	<td style="text-align: left"> -&nbsp;&nbsp;&nbsp;&nbsp;ReachSafety-Arrays </td>
	<td> 4 </td>
	<td> 5 </td>
</tr>
<tr>
	<td style="text-align: left"> -&nbsp;&nbsp;&nbsp;&nbsp;ReachSafety-Sequentialized </td>
	<td> - </td>
	<td> 5 </td>
</tr>
<tr>
	<td style="text-align: left"> -&nbsp;&nbsp;&nbsp;&nbsp;ReachSafety-Recursive </td>
	<td> 8 </td>
	<td> 9 </td>
</tr>
<tr>
	<td style="text-align: left"> -&nbsp;&nbsp;&nbsp;&nbsp;ReachSafety-Heaps </td>
	<td> 9 </td>
	<td> 10 </td>
</tr>
<tr>
	<td style="text-align: left"> Termination </td>
	<td> 8 </td>
	<td> 6 </td>
</tr>
<tr></tr>
</table>
</div>
<br>
Pinaka's two strengths are **speed and accuracy**. If it produces an answer, it does so very fast. For example, in the ReachSafety-Floats subcategory, Pinaka was more than 10 times as fast as the verifier that stood first. Pinaka had 0 incorrect results in SVCOMP 2019, and only 3 in SVCOMP 2020 out of more than **4K benchmarks** that it was run on.


<a href="https://github.com/sbjoshi/Pinaka" class="button"><i class="fab fa-github fa-1g"></i> Tool</a>
<a href="https://arxiv.org/abs/1903.02309" class="button"><i class="far fa-file-pdf fa-1g"></i> Tool Paper</a>
<a href="https://sv-comp.sosy-lab.org/2019/results/results-verified/" class="button"><i class="far fa-star"></i> SVCOMP19</a>
<a href="https://sv-comp.sosy-lab.org/2020/results/results-verified/" class="button"><i class="far fa-star"></i> SVCOMP20</a>

