# dronelogshare
Sharing my DataFlash logs (.bin files) 

## 2 1-1-1980 01-00-00.bin ## 
I'm doing the Pozyx IndoorLoiter project for my drone. So I know where the first errors come from, thats because I didn't had enough altitude before loitering. In the last cycle the loitering works to a certain degree, because I'm having COMPASS VARIANCE error. The BCON_ORIENT_YAW have been set, so the pozyx positioning knows whats North. When loitering I try do some circling on the same altitude with pitch and roll, then I notice the circling is to wide. Which refers most probably to the COMPASS VARIANCE error. How can I fix this? I was thinking of adjusting the AHRS_ORIENTATION. But I don't know what values to use. Also I'm using the internal compass of the PX. Is it possible it has to much interference of metal construction of the Hangar I'm in. Does this mean I have to set the declination manualy?
