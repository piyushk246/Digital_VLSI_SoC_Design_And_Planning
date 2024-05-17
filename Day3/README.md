*Day Three*

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/7528d596-5400-406e-94e9-528e7e08aa8a)


![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/1b949d68-9a5a-466f-8cd7-11be365a3bd3)

magic tool open with the sky130A.tech
![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/092fc0f9-396f-42c0-8eb5-1081a8321499)

Invter Layout on Magic

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/11cb37c9-e702-4c97-89dd-a8655b31bff1)


![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/baf82066-1a06-4ee5-932a-d8da432d799e)

extracting the files

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/d81d9c4d-3f08-4ef0-92ca-d6ae706433b0)


![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/a8da5e1b-463a-4f13-9500-444fd8bb7837)

vim sky130_inv.spice
![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/ff480a8d-9af4-48e6-b293-76078fc9234f)


LES फ़ाइलsky130_inv.ext तकनीक से बनाई गई:sky130A

.ऑप्शन स्केल=0.01u

.include/libs/pshort.lib

// लेआउट में ग्रिड बॉक्स का आयाम

include/libs/nshort.lib

// इसमें pmos और nmos के बारे में जानकारी शामिल है

//.subcktsky130_inv A Y VPWR VGND

M1000 Y A VPWR VPWR pshort_model. w=37 1=23

+ विज्ञापन=1443 पीडी=152 एएस=1517 पीएस=156

M1001 Y A VGND VGND nshort_model.0 w=35 1=23

+ विज्ञापन=1435 पीडी=152 एएस=1365 पीएस=148

वीडीडी वीपीडब्ल्यूआर0 3.3वी वीएसएस वीजीएनडीओ ओवी

वीए ए वीजीएनडी पल्स (0V 3.3V 0 0.1ης 0.1ns 2ns 4ns)

COAY 0.05fF

C1 VPWR 0.11fF

C2 A VPWR 0.07fF

C3 Y 0 2fF

C4 A 00.59fF

//C5 VPWR VGND 0.000017f

//.समाप्त होता है

.ट्रान 1एन 20एन

।नियंत्रण

दौड़ना

// C3 नामक लोड कैपेसिटेंस नोड Y और VGND के बीच जुड़ा हुआ है
