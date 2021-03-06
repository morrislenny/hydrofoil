#core.clj API

`core.clj` is where the environment for the run will be made. 
This eventually will contain the function that actually runs whole project. 
Things that are stored here include functions that get utalized in both the model
and the evolution as well as run constants like fluid velocity, AOT etc...

## Functions  
#### `run-constants`  
This function contains constants that get used to define the 
environment that the foil will be tested in. The constants are: 
* `dencity`: This is the fluid dencity 
* `velocity`: Fluid velocity
* `angle-of-attack`: This is the angle of the chord, pivoted from the most aft point of the cord, to the horizontal.    

#### `NACA-design`  
This function includes takes the three numbers needed to define an NACA-4 Digit Foil.
Read [here](https://github.com/morrislenny/hydrofoil/blob/master/docs/NACA-4%20Digit%20Design.md) for background on what an NACA-4 Digit foil is. 
