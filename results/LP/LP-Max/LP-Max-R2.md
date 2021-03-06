# LP-MAX-R1  
Lift-Priority Scoring, Max Velocity, Run 2: 3,000,000 generations.
### Run Constants  
| V-Infinity (V∞) | Density (ρ) | angle-of-attack (AOT) |
|-----------------|-------------|----------------------|
| 163.17m/s       | 0.6805kg/m^3| 2.1 degrees          |
### Wing Characteristics  
| Span   | Root-Chord | Min-Lift |
|--------|------------|----------|
| 11.24m | 2.67       | 27585N   |
### Highest Scoring Individual  
**Standard NACA:** (NACA: 0.01, 2.608739162, 13)  
**Generation:** 543  

| Lift         | Drag        | Cl-2D         |CL-3D       |CD-Induced    |Score|
|--------------|------------ |---------------|------------|--------------|-----|
| 36810.92989N | 376.8706535N|0.2313147543   |0.1723973451|0.001765005674|999623.1293|

![LP-Max-R2-543](LP-Max-R2-img/LP-Max-Run2-Gen543.png)  

### Progress Over Time  

![Lift-Drag-Score-v-generation](https://docs.google.com/spreadsheets/d/e/2PACX-1vTCY-ZgJswZxZ2wHg70SCysg52iXBS9KCiMRhmkYokfgpuD-i0IVX3sFsi8B1J4ZdYKnEGhSytkkbGJ/pubchart?oid=69823846&format=image)

![cl-2D, CL-3D, CD-I vs Generation](https://docs.google.com/spreadsheets/d/e/2PACX-1vTCY-ZgJswZxZ2wHg70SCysg52iXBS9KCiMRhmkYokfgpuD-i0IVX3sFsi8B1J4ZdYKnEGhSytkkbGJ/pubchart?oid=918986096&format=image)

![C-M, C-P vs Gen](https://docs.google.com/spreadsheets/d/e/2PACX-1vTCY-ZgJswZxZ2wHg70SCysg52iXBS9KCiMRhmkYokfgpuD-i0IVX3sFsi8B1J4ZdYKnEGhSytkkbGJ/pubchart?oid=121517066&format=image)


**Number of Successful Generations:** 10  

![LP-Max-R2-Gif](https://media.giphy.com/media/3o6fJg2DBggmQPzClW/giphy.gif)

### Raw Data    
```CSV
Run 2: Max Speed| V-infity: 163.17m/s| p = 0.6805kg/m^3| a = 2.1

:thickness , 2.11 , :generation , 543 , :positon-camber , 2.608739161687238 , :CD-Induced , 0.0017650056737083177 , :Lift , 36810.929889694 , :corrected-thickness , 0.021099999999999997 , :score , 999623.1293465329 , :cl-2D , 0.231314754314477 , :Drag , 376.870653467174 , :corrected-position-camber , 0.2608739161687238 , :corrected-max-camber , 1.0E-4 , :max-camber , 0.01 , :CL-3D , 0.1723973451157776 ,
:thickness , 2.34 , :generation , 396 , :positon-camber , 4.455497092203647 , :CD-Induced , 0.0017804408674618496 , :Lift , 36971.53759654905 , :corrected-thickness , 0.023399999999999997 , :score , 999619.8335658773 , :cl-2D , 0.23147913592070082 , :Drag , 380.1664341226912 , :corrected-position-camber , 0.4455497092203647 , :corrected-max-camber , 1.0E-4 , :max-camber , 0.01 , :CL-3D , 0.1731495223183072 ,
:thickness , 4.67 , :generation , 143 , :positon-camber , 4.673342042378192 , :CD-Induced , 0.0020187551766182375 , :Lift , 39368.200345824065 , :corrected-thickness , 0.0467 , :score , 999568.9477977689 , :cl-2D , 0.2339321145480475 , :Drag , 431.05220223109933 , :corrected-position-camber , 0.46733420423781924 , :corrected-max-camber , 3.0E-4 , :max-camber , 0.03 , :CL-3D , 0.18437385966460634 ,
:thickness , 0.04 , :generation , 67 , :positon-camber , 7.8493535537113965 , :CD-Induced , 0.003454106753018213 , :Lift , 51495.77675934713 , :corrected-thickness , 4.0E-4 , :score , 999262.4661277035 , :cl-2D , 0.24634466018171441 , :Drag , 737.5338722964798 , :corrected-position-camber , 0.7849353553711397 , :corrected-max-camber , 8.0E-4 , :max-camber , 0.08 , :CL-3D , 0.24117117455573195 ,
:thickness , 1.12 , :generation , 42 , :positon-camber , 5.84762549836304 , :CD-Induced , 0.011561996476136968 , :Lift , 94215.02156033748 , :corrected-thickness , 0.011200000000000002 , :score , 997531.2390026532 , :cl-2D , 0.29006770569778406 , :Drag , 2468.7609973467975 , :corrected-position-camber , 0.5847625498363039 , :corrected-max-camber , 0.0043 , :max-camber , 0.43 , :CL-3D , 0.44123904600343533 ,
:thickness , 7.810000000000002 , :generation , 19 , :positon-camber , 1.492085935619604 , :CD-Induced , 0.013389629713524568 , :Lift , 101388.34149558746 , :corrected-thickness , 0.07810000000000002 , :score , 997140.9958761111 , :cl-2D , 0.2974095816015218 , :Drag , 2859.0041238889607 , :corrected-position-camber , 0.1492085935619604 , :corrected-max-camber , 0.006999999999999999 , :max-camber , 0.7 , :CL-3D , 0.4748339950093122 ,
:thickness , 17.67 , :generation , 17 , :positon-camber , 4.450917206594334 , :CD-Induced , 0.04149683587719529 , :Lift , 178488.90575935913 , :corrected-thickness , 0.17670000000000002 , :score , 991139.43944384 , :cl-2D , 0.3763218258681009 , :Drag , 8860.560556160077 , :corrected-position-camber , 0.4450917206594334 , :corrected-max-camber , 0.0123 , :max-camber , 1.23 , :CL-3D , 0.8359205697259153 ,
:thickness , 16.34 , :generation , 6 , :positon-camber , 4.052252332702942 , :CD-Induced , 0.46453339342357325 , :Lift , 597189.5575740086 , :corrected-thickness , 0.1634 , :score , 900811.0817179177 , :cl-2D , 0.8048609478067812 , :Drag , 99188.91828208226 , :corrected-position-camber , 0.4052252332702942 , :corrected-max-camber , 0.050199999999999995 , :max-camber , 5.02 , :CL-3D , 2.7968294896415804 ,
:thickness , 13.74 , :generation , 2 , :positon-camber , 3.015863246403734 , :CD-Induced , 0.484593910171159 , :Lift , 609947.8594920791 , :corrected-thickness , 0.1374 , :score , 896527.6846908319 , :cl-2D , 0.8179190394952051 , :Drag , 103472.3153091681 , :corrected-position-camber , 0.3015863246403734 , :corrected-max-camber , 0.0558 , :max-camber , 5.58 , :CL-3D , 2.8565806935761677 ,


```
