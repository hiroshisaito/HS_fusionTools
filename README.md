# HS_fusionTools

## System Requirment
BlackmagicDesign FUSION 16 and FUSION STUDIO 16.
(Probably works with DaVinci Resolve Fusion page)

macOS, Linux, Windows
 

## Macros

#### HS_latlongToAngular.setting 
Convert Latitude Longitude coord to angular coord. Mainly for environment map or VR comp. 
https://www.youtube.com/watch?v=bAXimme33Mk
 
[![HS_latlongToAngular.png](./images/HS_latlongToAngular.png)

#### HS_envRelight.setting 
Reflection map with Normal(World) and PointPosition passes.
Specular mode requires Camera position and Normal and Position channel must be included in AUX layers.
Environment texture input requires Lat-Long image.

Output includes UV map pass for angular environment map.

[![HS_latlongToAngular.png](./images/HS_envRelight.png)
