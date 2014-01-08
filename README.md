qmspeedtest
===========

Quantum Chemistry speed test. Note that it must only use a single CPU.

Pedro Silva's results
----------------------

**Machine:** 
Intel(R) Core2 Quad Q8300@2.5 GHz with 3.9 GB memory with Ubuntu 10.04

**Fancy compiler or maths libraries used when compiling:** Gamess US was built using ATLAS math library

### HF
<table>
<tr>
<th>QM Package</th><th>Time (min)</th><th>Steps</th><th>per step</th>
<th>Total E</th><th>HOMO</th><th>LUMO</th>
</tr>
<tr>
<td>Gamess(US)
<td>9.2</td><td>30</td>
<td>0.31</td>
<td> -644.6757056212</td>
<td></td>
<td></td>
</tr>

<tr>
<td>Firefly</td>
<td>11.5</td>
<td>23</td>
<td>0.5</td>
<td> -644.6757047981</td>
<td></td>
<td></td>
</tr>


<tr>
<td>Q-Chem 4.0</td>
<td>4.96</td>
<td>14</td>
<td>0.35</td>
<td> -644.675706161</td>
<td></td>
<td></td>
</tr>


</table>

### B3LYP
<table>
<tr>
<th>QM Package</th><th>Time (min)</th><th>Steps</th><th>per step</th>
<th>Total E</th><th>HOMO</th><th>LUMO</th>
</tr>
<tr>
<td>Gamess(US)
<td>142.2</td><td>41</td>
<td>3.47</td>
<td>   -648.4956883277  </td>
<td></td>
<td></td>
</tr>
<tr>


<td>Firefly</td>
<td>22.2</td>
<td>25</td>
<td>0.89</td>
<td> -648.4956786524</td>
<td></td>
<td></td>
</tr>

<tr>


<td>Q-Chem 4.0</td>
<td>9.30</td>
<td>14</td>
<td>0.66</td>
<td> -648.495723731</td>
<td></td>
<td></td>
</tr>


</table>
