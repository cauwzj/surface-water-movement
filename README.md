# surface-water-movement
The surface water movement module using 2DSOIL

How to run each example:

Ex1: turn on the lines between "cccz turn this on for Ex_1" in "SurfaceWaterBalanceAdjustment" module;

     turn on the lines between "cccz turn this on for Ex_1" in "WMassbl" module;
     
     use a separated "SETMAT01.for" file;
     
     Note: This simulation was made for 1/10 length of the real soil slope.
     
           The result is reported as "cm^2/15 sec". One should multiply the results by 5.1 cm (width of the soil slope), 
           
           10 (length scaling number) and 1/15 (time scaling number), then compare to the experimental results.
           
Ex2: nothing need to be done

Ex3: turn on the lines between "cccz turn this on for Ex_3" in "SurfaceWaterBalanceAdjustment" module;

Ex4: soil mulching: nothing need to be done;

     plastic mulching: turn on the lines between "cccz turn this on for Ex_4 plastic mulching" in "Watermov" module;
