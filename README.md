Quantum Chemistry Speed Test
============================

**The rules**: Calculations must only use a single CPU. The B3LYP used should be that used by default by Gaussian and NWChem (namely the VWN3 not VWN5). And please, no Gaussian input files or results.

Various people have submitted results:
- [Eric Berquist](http://github.com/berky/qmspeedtest)
- [Michael Banck](http://github.com/mbanck/qmspeedtest)
- [Noel O'Boyle](http://github.com/baoilleach/qmspeedtest)
- [Pedro Silva](http://github.com/PedroJSilva/qmspeedtest)

Please fork the [original repo](http://github.com/baoilleach/qmspeedtest) and submit your own!

Pedro Silva's results
----------------------

**Machine:** 
Intel(R) Core2 Quad Q8300@2.5 GHz with 3.9 GB memory with Ubuntu 10.04

**Fancy compiler or maths libraries used when compiling:** Gamess US was built using ATLAS math library.
Q-Chem inputs were takien from [Michael Banck](http://github.com/mbanck/qmspeedtest)

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

Default grids are different in each program: 
- Gamess (US) uses a Lebedev grid with 96 radial points per atom and 302 angular points per radial shell 
- Firefly     uses a pruned Lebedev grid with 63 radial points per atom and 302 angular points per radial shell 
- Q-Chem      uses the "standard grid-1" , which is a pruned version of a Lebedev grid with 50 radial points per atom and 194 angular points per radial shell.

<table>
<tr>
<th>QM Package</th><th>Time (min)</th><th>Steps</th><th>per step</th>
<th>Total E</th><th>HOMO</th><th>LUMO</th>
</tr>
<tr><b>
<td>Gamess (US) default grid
<td><b>42.2</td><td>41</td>
<td><b>3.47</td>
<td><b>   -648.4956883277  </td>
<td></td>
<td></td></b>
</tr>
<tr>
<td>Gamess (US) with Firefly grid 
<td>102.7</td><td>41</td>
<td>2.5</td>
<td>   -648.4956642 </td>
<td></td>
<td></td>
</tr>
<tr>
<td>Gamess (US) with SG-1 grid 
<td>24.7</td><td>40</td>
<td>0.62</td>
<td>-648.4956642 </td>
<td></td>
<td></td>
</tr>

</table>

<table>
<tr>
<th>QM Package</th><th>Time (min)</th><th>Steps</th><th>per step</th>
<th>Total E</th><th>HOMO</th><th>LUMO</th>
</tr>
<tr>
<td>Firefly with Gamess(US) grid </td>
<td>33.7</td>
<td>26</td>
<td>1.3</td>
<td>-648.4956790</td>
<td></td>
<td></td>
</tr>
<tr>
<td>Firefly default grid </td>
<td><b>22.2</td>
<td><b>25</td>
<td><b>0.89</td>
<td> -648.4956786524</td>
<td></td>
<td></td>
</tr>
<tr>
<td>Firefly with SG-1 grid </td>
<td>19.6</td>
<td>23</td>
<td>0.85</td>
<td>-648.4957054791</td>
<td></td>
<td></td>
</tr>
</table>
<table>
<tr>
<th>QM Package</th><th>Time (min)</th><th>Steps</th><th>per step</th>
<th>Total E</th><th>HOMO</th><th>LUMO</th>
</tr>
<tr>
<td>Q-Chem 4.0 with Gamess (US) grid</td>
<td>32.5</td>
<td>14</td>
<td>2.32</td>
<td>-648.495693316716</td>
<td></td>
<td></td>
</tr>
<tr>
<td>Q-Chem 4.0 with Firefly grid</td>
<td>23.25</td>
<td>14</td>
<td>1.66</td>
<td>-648.495693748</td>
<td></td>
<td></td>
</tr>
<tr>
<td><b>Q-Chem 4.0 default grid</td>
<td><b>9.30</td>
<td><b>14</td>
<td><b>0.66</td>
<td> -648.495723731</td>
<td></td>
<td></td>
</tr>


