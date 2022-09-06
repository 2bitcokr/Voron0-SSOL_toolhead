# Voron0-SSOL_toolhead
Vzero Toolhead Design 

This Design Based on the https://github.com/PrintersForAnts/Mini-AfterSherpa 

(Many parts are the same, mostly compatible with each other, with some modifications.)
![ALL2](https://user-images.githubusercontent.com/110684743/183617793-c647f5ba-fb6c-49f9-a819-6bbb3ed8931c.png)

Supports 
V0 / V0.1 

recommended to apply 3MOD

MGN9C MOD (Need Changed X_carrage)

I only tested this on the MGN9C. recommend 9C rail MOD.

Klicky https://github.com/jlas1/Klicky-Probe

FANsaver https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/jappaj/FanSaver


# Printing Setting.
Same VORON PARTS setting
(infill 40% , 4wall )

But, X_carriage is infill 100% !!

If possible, it is very good to apply SLS or SLM , Metal.

Carriage For_XXXX is exclusive parts.

Not compatible with other extruders.

(It is designed to be a little strong.)


Need some extra bolts and nuts.
(Most used as before BOM item)
Most use M3 bolts,
If the hole is large , insert nut (M3x5x4 insert 
![Insertnut](https://user-images.githubusercontent.com/110684743/183639449-545a8ced-5fe3-4717-92e3-ba787e843f28.png)

![image](https://user-images.githubusercontent.com/110684743/188689747-deef9c7d-e6cf-4790-bb4e-49ae0274f5cb.png)






# Surpport  Hotend 
![Hotend](https://user-images.githubusercontent.com/110684743/183648361-d3972f76-e4d9-46b7-b91f-ae5d93a2b0ab.png)


-V6 DUCT = V6 / REVO SIX /  NFZone V6 / Trianglelab,Mellow V6 / Slice Copperhead(groove) / Phaetus BMO 

-Micro Duct = V6Micro(threaded) / REVO micro 

-Dragon Duct = Trianglelab(Phaetus) Dragon / DragonFly BMO 

-Mosquito Duct = Slices Mosquito / NFCrazy 



Most recommended V6+CHC(trianglelab) Or NFZone+CHC is BEST .

Not recommend Mosquito,NFCrazy (It can kill a blowerfan. heatsink structure is Near to 3010blowerFAN.)



# Surpport Extruder
Duct A and duct B are not compatible.
(B ducts are not fitted with Orbiter. )

-A DUCT (USED Big Gear , New Extruder !!)

recommend  OrbiterV2,LGXLite good performance

![bduct](https://user-images.githubusercontent.com/110684743/188689349-4bd53708-b3e5-4c42-9b59-75da39632ca8.png)


LDO Orbiter V2.0
https://orbiterprojects.com/orbiter-v2-0/

Bontech LGX Lite! (Lgxlite is B Dcut Recommend)
https://www.bondtech.se/product/lgx-lite-extruder-no-motor/







-B DUCT (can use before BMG(MiniAB) gears.)

Bontech LGX Lite! (Bduct type Recommend)
https://www.bondtech.se/product/lgx-lite-extruder-no-motor/

SherpaMini
https://github.com/Annex-Engineering/Sherpa_Mini-Extruder

Sailfin (origianl version = Not compatible EBB36,SHT36,RHT36 )
https://github.com/CroXY3D/Sailfin-Extruder

Sailfin (2bitversion = compatible RHT36,EBB36,SHT36  ) 
![sailfin](https://user-images.githubusercontent.com/110684743/186203663-2a6b9436-3e1e-4057-ace7-8e6675046100.png)




I made some changes to the sailfin extruder design.

Change gear alignment

Change bolt, insertnut position

Change shaft to bolt,insertnut(If you are changing from an existing miniAB, there is no shaft.)

Use PC4-M6 (option) (Have you ever experienced the Teflontube coming off when insert filament? I always modify tubefittings on all extruders.


# FAN MOUNT
If you use CanBUS(EBB,SHT36) , RHT expansion board

Need Extender Board cooling .

If Nofan, MCU temperature is 80~90 ℃.

USED FAN, MCU temperature is 60~70 ℃. ( Chamber Temperature+10℃)

Fan mounts are 2 STLs. (defualt,Mirror)

FAN cooling both the motor and the board.

Test results are very good with 1FAN.

![AType_OrbiterV2_LGXLite](https://user-images.githubusercontent.com/110684743/183629411-0dd52714-6a15-49d5-a051-bf9d5bd46da1.png)
![FAN](https://user-images.githubusercontent.com/110684743/183629416-4422dae8-92e0-4757-a2de-d5cba05ab122.png)
![FAN2](https://user-images.githubusercontent.com/110684743/183629438-c4565a7e-af57-482c-806b-35d1365911cf.png)

Also compatible with MiniAB 
![KakaoTalk_20220809_221840444](https://user-images.githubusercontent.com/110684743/183657152-e28ac1c2-4942-4475-bfe7-f615a34b9d7e.jpg)


# Fansaver
FANsaver https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/jappaj/FanSaver

Fansaver is need for 3010blower fans.

I made some modify for V6 and Dragon.

And, NFzone can be use 3010Fan.

modify fansaver for 3010fan.
![fansaver](https://user-images.githubusercontent.com/110684743/183633617-d526e1c8-253e-41ed-8138-533432e7a0b5.png)




# CanBUS / Toolheadboard

EBB36 / SHT36 / ★RHT36★ model is

It's really optimized for Vzero.

If you want to replace multiple toolheads


If you use the Toolheadboard on all tool heads,

The toolhead can be replaced in less than Just 1 minute.

![KakaoTalk_20220809_202830313](https://user-images.githubusercontent.com/110684743/183637019-502fdde9-052c-408e-9aff-d3a802df5a7e.jpg)
![KakaoTalk_20220809_202830313_02](https://user-images.githubusercontent.com/110684743/183637037-f00ccfe3-d9ca-4bfa-bc81-83a382f5b779.jpg)

![KakaoTalk_20220809_202830313_01](https://user-images.githubusercontent.com/110684743/183637066-49a2c845-c952-43cd-98c9-d30cbadcad19.jpg)
![KakaoTalk_20220809_202830313_03](https://user-images.githubusercontent.com/110684743/183637080-8c5ee700-6419-4a2b-99c9-1a142a3c3ea1.jpg)
![KakaoTalk_20220809_221107363](https://user-images.githubusercontent.com/110684743/183655873-c0595822-308a-4a8b-9426-e4780eb812f4.jpg)

![ductzzz](https://user-images.githubusercontent.com/110684743/183643414-07b46496-60eb-442f-b7cd-b45eb652f552.png)
