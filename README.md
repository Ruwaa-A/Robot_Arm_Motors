# Robot Arm Motors
Calculating the required motor torque for a robot arm and selecting the appropriate servo motors.

___________________________________

## Calculating Motors Torque  

1- Shoulder: 

T =(0.4 (0.15/2)+0.2 (0.15+0.10/2)+(0.1+1) (0.15+0.10+0.04)) 9.81    
T = 3.816 Nm  

Required Torque = 3.816 × 1.5   
= 5.724 Nm

 ---------------------------------

2- Elbow:  
T = (0.2 kg (0.10/ 2) +(0.1 +1 ) 0.10 ) 9.81    
T ≈ 1.177 Nm    
    
Required Torque = 1.177 × 1.5  
= 1.766 Nm


 ---------------------------------

3- Wrist:   
T =(0.1 kg (0.04/2) m+1 kg X 0.04 m) 9.81   
T= 0.412 Nm 
     
Required Torque = 0.412 × 1.5  
= 0.618 Nm


  ---------------------------------
## Choosing Servo Motors  

1- Shoulder: 
- AC servo motor  
Since the robot shoulder carry the heavy lifting. A 750W AC servo motor is  idle.
   
Link for purchasing:  
https://www.alibaba.com/product-detail/Servo-Motor-And-Driver-750w-1kw_1600495722663.html?spm=a2700.7735675.0.0.53d213a0EFS39A&s=p    

    
  ---------------------------------
              
2- Elbow: 
- AC Servo Motor 200W ECMA-C20602RS
  
       
Link for purchasing:  
https://www.damencnc.com/en/ac-servo-motor-200w-ecma-c20602rs/a3579

  ---------------------------------

3- Wrist: 
- BLDC servo motor  
The wrist needs to be precise, light, and compact. Dynamixel module is idle.


       
Link for purchasing:  
https://www.electromaker.io/shop/product/xm430-w210-r?srsltid=AfmBOorSPDmqbCJ6ggTv8teKAkQR5_XGyBxmRCuXgbS5tZgb32zQzDlr8HY
  
---------------------------------


## Lifting 2 kg by Adding Gears
The motors can lift 2 kg by adding twice the gears to lift twice the weight.

Option 2 (Slightl

## Disadvantages
- slow speed
- Heavy size
Less efficent overall 

## Alternatives 
- USing the right motors 
