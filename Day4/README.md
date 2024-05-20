*Day Four*
![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/7573013d-c7b1-4568-9a6d-91ffa20138f9)

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/047b8cc8-83dd-42a7-a491-951ed36a745d)

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/028b2b00-fde5-444b-bdb4-d181d619755f)

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/081d6c5f-12ec-464a-8e52-487de025fc71)

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/1dcbd1fb-c037-4e97-85a7-40dc3c5e186f)

grid 0.46um 0.34um 0.23um 0.17um
![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/bbd5dfb9-4311-4f9d-a4c3-c151d77a130f)

sky130_fd_sc_hd__typical.lib
![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/b1a5d6d9-a928-4489-9244-c79b7d8a5604)

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/7e0efaa3-8ec6-4ef4-bdc2-0570d4def3de)

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/e02d6c9f-80fa-4b45-9e8a-4f5f7eadd066)

sky130_vsdinv.lef file open

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/b13d00c1-cc72-4799-8975-e48c2af2f106)


cp of the sky130_vsdinv.lef file 
![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/74b8b3c1-fc89-4e43-8683-46f2844327f7)

sky130_fd_sc__typical.lib

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/58718723-d0c9-40bb-bac9-52ef7551b224)

sky130_fd_sc__fast.lib
![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/6ca6d28c-49cd-42f7-a24e-163c3e959dc6)

sky130_fd_sc__slow.lib
![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/0fc0928f-c9c4-4339-98e7-62b1d871da0d)


![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/da95b75c-226f-4c3f-b8b9-0917f4cd4425)

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/d06bf511-d193-4fd3-9f79-5953835568ab)

set lefs [glob $::env(DESIGN_DIR)/src/*.lef]      
add_lefs -src $lefs
  run_synthesis
![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/f753790d-097e-4551-b484-b9ec9c212c00)

run_floorplan error
![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/a68fdcda-ff01-490d-b254-1f23a790e7b6)

  init_floorplan
  ![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/8f596bd8-5d0e-4a74-b2e5-46af525656ae)

  place_io
  ![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/a65b4ef9-447b-432d-847b-d60b0d9d01fe)

  tap_decap_or
    ![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/b6badfc9-06b1-4f43-99f9-431bc21b9fa3)

run_placement
![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/36880deb-61bb-4131-8ee3-e96e706e48fd)

magic tool opens the placement
![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/02c72b06-cfec-4b43-a434-8c420f9d6da7)


![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/da77af70-d6ce-4159-a882-49a400a1dc37)

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/cf0fb4c5-5c4c-44c4-bc20-6f07d212e47c)


Timing Analysis with OpenSTA tool after synthesis

set lefs [glob $::env(DESIGN_DIR)/src/*.lef] 
add_lefs -src $lefs 
set ::env(SYNTH_SIZING) 1 

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/9c0bcec8-0798-4ff9-8782-3206bdcd9be3)

run_synthesis
![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/6405e219-826d-448b-a4ee-959dfe5176d1)

Create pre_sta.conf 
![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/91c5251a-e3ea-48b7-84d7-a49670c62b11)

create my_base.sdc

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/5594aab5-d78a-40f0-85fb-77a8f7adef05)


sta pre_sta.conf
![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/3c69d070-6d10-4f48-9e5f-fdd330a89048)

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/6e14020c-cf43-4acb-9ae9-1a1a956a816f)

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/843cd428-c645-4442-a358-2af37a008be9)

Reducing slack by Fixes

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/05b90720-3c70-4366-a363-5c5fb15b4c69)

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/c5c8b21b-1457-44ea-a3ab-e7c9a9379197)

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/0b6189da-cade-458a-976d-ee369a7f3d9e)

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/b7ffccf2-cd73-47d1-ab92-77ca1ee08c01)

OR Gate with another OR Gate
![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/2ae922b2-9b97-4dbb-95ef-52b64359ac0b)
![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/998960e2-9d56-4692-8293-c6b7ea17e1f1)

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/47826997-0b49-4e8b-af9e-fbe916e01358)

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/59928946-9311-4e19-806e-9f074007c679)

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/b1ca815f-ea33-4780-8088-4905f5f14575)

The slack is reduced to 23.1362 ns.
![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/3e0cad89-20fc-4ded-9ffc-fe7ecd1a3115)

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/5e88d1a8-bf51-4994-ad58-3d967c789951)

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/d1268123-a19c-4ec3-bd08-e7b1576ffa36)

report_checks -from _29043_ -to _30440_ -through _14506_

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/ef2960af-5e0d-49e2-b83f-9d76ac265609)


Newly Generated Netlist

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/8ee51394-9d29-47b1-bb9a-2d13cb77f6ca)

![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/fed35bc3-67c9-44c0-9b32-314e8188bcc1)
![image](https://github.com/piyushk246/Digital_VLSI_SoC_Design_And_Planning/assets/65733681/7fe48515-07dc-4e5b-8134-bc6b58083525)
synthesis , floorplan , placement and ct

