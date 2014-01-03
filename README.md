qmspeedtest
===========

Quantum Chemistry speed test. Note that it must only use a single CPU.

Baoilleach's results
--------------------

**Machine:** Intel(R) Core(TM) i7-2600 CPU @ 3.40GHz running 64-bit Centos 6.3

**Fancy compiler or maths libraries used when compiling:** None (system gcc, blas, lapack)

### HF
<table>
<tr>
<th>QM Package</th><th>Time (min)</th><th>Steps</th><th>per step</th>
<th>Total E</th><th>HOMO</th><th>LUMO</th>
</tr>
<tr>
<td>erkale</td><td>810</td>
<td>90</td><td>9</td>
<td>-644.67570139</td>
<td>-0.353712</td>
<td>0.074269</td>
</tr>
</table>

### B3LYP
<table>
<tr>
<th>QM Package</th><th>Time (min)</th><th>Steps</th><th>per step</th>
<th>Total E</th><th>HOMO</th><th>LUMO</th>
</tr>
<tr>
<td>erkale</td><td>933</td>
<td>58</td><td>16.1</td>
<td>-648.49566820</td>
<td>-0.260899</td>
<td>-0.064457</td>
</tr>
</table>

Michael Banck's results
----------------------

**Machine:** Lenovo T400 (Intel(R) Core(TM)2 Duo CPU     P8400  @ 2.26GHz)

**Fancy compiler or maths libraries used when compiling:** Debian 7 packages

### HF
<table>
<tr>
<th>QM Package</th><th>Time (min)</th><th>Steps</th><th>per step</th>
<th>Total E</th><th>HOMO</th><th>LUMO</th>
</tr>
<tr>
<td>erkale</td><td>3394</td>
<td>90</td><td>37.7</td>
<td>-644.67570139</td>
<td>-0.353712</td>
<td>0.074269</td>
</tr>
<tr>
<td>MPQC</td><td>64</td>
<td>28</td><td>2.3</td>
<td>-644.67570622</td>
<td>-0.353644</td>
<td>0.074333</td>
</tr>
<tr>
<td>PSI4</td><td>115</td>
<td>16</td><td>7.2</td>
<td>-644.67570580</td>
<td>-0.353619</td>
<td>0.074353</td>
</tr>
<tr>
<td>NWChem</td><td>22</td>
<td>21</td><td>1.0</td>
<td>-644.67570680</td>
<td>-0.353608</td>
<td>0.074350</td>
</tr>
</table>

### B3LYP
<table>
<tr>
<th>QM Package</th><th>Time (min)</th><th>Steps</th><th>per step</th>
<th>Total E</th><th>HOMO</th><th>LUMO</th>
</tr>
<tr>
<td>MPQC</td><td>387</td>
<td>25</td><td>15.4</td>
<td>-648.495700269</td>
<td>-0.260571</td>
<td>-0.064391</td>
</tr>
<tr>
<td>PSI4</td><td>190</td>
<td>16</td><td>11.9</td>
<td>-648.495697810</td>
<td>-0.260556</td>
<td>-0.064363</td>
</tr>
<tr>
<td>NWChem</td><td>56</td>
<td>26</td><td>2.1</td>
<td>-648.495694155</td>
<td>-0.260569</td>
<td>-0.064392</td>
</tr>
</table>

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


<td>Firefly<td></td>
<td>11.5</td>
<td>23</td>
<td>0.5</td>
<td> -644.6757047981</td>
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
<td>141.7</td><td>41</td>
<td>3.46</td>
<td>  -648.1465175955 </td>
<td></td>
<td></td>
</tr>


<td>Firefly<td></td>
<td>22.2</td>
<td>25</td>
<td>0.89</td>
<td> -648.4956786524</td>
<td></td>
<td></td>
</tr>
</table>
