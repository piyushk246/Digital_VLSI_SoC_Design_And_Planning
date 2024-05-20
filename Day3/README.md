# *Day Three*

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

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/4d434d59-9732-48b4-a173-d266c2bd0cfd)


after the ngspice run  
![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/1cdfc734-50b1-421b-a909-d8c2f71f6fb7)

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/424ccf8b-961e-4466-bb46-30f264234da3)

plot y vs time a

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/74f77d6a-080f-4ca3-94bd-98f0097f1503)

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/91ec33e0-81c1-4fd4-971d-8c33cd4e9882)

20%
![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/1aceb0cf-3b22-49bc-af42-d719dbb29591)

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/5e5aae1b-0165-4ecb-83ca-65a311629a29)

80%
![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/e762fce2-fbfc-4fca-8a64-19ef3aef1ec5)


Rise delay time 50%
![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/63735e2a-d878-4342-9867-f066d30eae7d)
- Rise Time = Time taken by output to rise to 80% of its final value 
- Time taken by output to rise to 20% of its final value
- output rises to 20% of its final value at 2.1825 ns.
- output rises to 80% of its final value at 2.2464 ns
- RISE TIME = 2.2464 - 2.1825 = 0.0639 ns = 63.9ps

Fall delay time 50%
![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/62b5a20e-3d0e-4894-9053-c083cf0d505a)
- Fall transition time = Time taken by output to fall to 80% of its final value
- - Time taken by output to fall to 20% of its final value
- output rises to 20%(i.e. 2.64V) of its final value at 4.0527 ns
- output rises to 80%(i.e. 660mV) of its final value at 4.0951 ns
- FALL TIME =4.0951 - 4.0527 = 0.0424ns = 42.4ps

# Errors in DRC by Magic tool


![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/698dcbe0-e446-49ee-9840-f9aa8f98c244)

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/85fc30ba-b0cb-40eb-828e-aad4fe8867b4)

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/bd7465f7-2141-46cc-a7c9-3b136f5a0620)

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/27147072-15ae-4d19-9c29-3f98304310f6)


 
magic -d XR
![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/2256a2ae-acae-4078-a241-ac8b30296f33)

Met3.mag open file
![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/32b6048a-5eb4-4684-8129-9170d39b654c)


![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/e3f486ea-1912-41d0-a7a9-ce407aac6410)



![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/29dc0292-64b2-4eaa-afb5-43744c39a46e)


error in poly.mag file

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/1ba35ac3-4d60-49e5-bb4d-a3a697d0da18)

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/783751aa-897b-4602-9063-ea7a21ce1004)

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/d741b0fb-b2c0-493f-8d8a-aff7438ea039)

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/a3d480de-bf93-4258-a6bf-2a8fab5d2063)

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/f2e7b89f-6d29-4fab-ab99-b4ca2b7ceea7)

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/4bd5d960-35af-4b37-952e-c0a890a1b442)

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/ecae5027-bdbd-4e48-acc0-4b663bf95dfb)
