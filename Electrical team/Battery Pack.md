# Vehicle Parameter

  Velocity=**120km/hr**
  this is equivalent to **33.333m/s**
  
  Vehicle total mass=**200kg**

Number of the Passengers=**4**

$$=4*80=320kg$$

**Total mass=2320kg**

Rolling force --the firction to be overcome...this is based on the standard assalt road

$$=Fr=cr*m*g$$
where cr is the coeffficient of the friction

m is the mass of the vehicle
g is the gravity
F_r$=0.015*2320*9.81$
 $ =341.388N$
## Drag Force

$$F_d =1/2*0.30*1.2*2.2*(100/3)^2=440N$$  
Net force to overcome
$440N+341.388N=781.388N$

## Power required
power is the product of force and the velocity
P=781.388N*33.333m/s=26046.26667w
**=26.046kw**
Total energy usage
E=P*t
 =26.045kw*(300km/120km/hr)
 $=**65.125kwh**$  
this the total capacity of the battery poack that we require topower our car for the 300km range

# Cell Parameter

Taking the semi-solid lithium ion cells we have

**B7A0Y44 model**  
Cell Capacity=56Ah  
Cell Voltage=3.65V  

## Battery Parameter 
Battery Capacity in Ah  
  $ 65125wh/450v $  
$\eq144.7222Ah$ 
###Total Number of cells(ct)  
cells in series normally add up the voltage and the cells in parallel normally add up the voltage  
Pc is the cells in parallel and is given by  
Pc=450v/3.65v  
   $\eq123.2876712\neq124cells$   
Sc is the umber of cells in series  
Sc=Cb/Cc=$144.722Ah/56Ah~=3 cells$  
Total number of cells is therefore    
$124*3=372cells$  
