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

