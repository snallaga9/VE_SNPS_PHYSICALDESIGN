# VE_SNPS_PHYSICALDESIGN
DC_ICC2_PT
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# DESIGN_COMPILER
file:///home/snallaga/Documents/VLSI%20EXPERT/synth_sai_1.tcl.png![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/2dc860cf-0def-4c0f-8611-fc9cad2a264f)

file:///home/snallaga/Documents/VLSI%20EXPERT/synth_sai_2.tcl.png![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/0cf96717-a524-49c7-a6bd-9ae70f2f6f81)

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# generate_sdc.tcl

the script will write the sdc constraints into the sdc file as per the user inputs from the prompt when synth_sai.tcl is run

file:///home/snallaga/Documents/VLSI%20EXPERT/generate_sdc.tcl.png![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/b1829f2c-dda9-41c0-b7ca-7a3d2995c526)

file:///home/snallaga/Documents/VLSI%20EXPERT/generate_sdc_clock_latency.png![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/122ac3fc-8469-4558-ade3-142e097ec166)


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# run:
dc_shell -f ./synth_sai.tcl

# assignment 1:
file:///home/snallaga/Pictures/Ghub.png![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/3d2be0be-57a6-40eb-94f4-522612425780)

file:///home/snallaga/Pictures/Ghub.png![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/1184a7c3-1583-408c-82e5-8360c8528014)

file:///home/snallaga/Pictures/all_registers.png![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/146fb97b-df3a-41ac-9740-c685447a13fa)

file:///home/snallaga/Pictures/Ghub.png![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/3a9ac2f8-062f-45e9-83d5-5e16a16f5e86)
file:///home/snallaga/Pictures/Ghub.png![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/564acbea-9840-44db-bc4f-5ed2361722fa)

file:///home/snallaga/Pictures/Ghub.png![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/e2f2ad80-6c3b-4d51-aabc-288e526729af)

file:///home/snallaga/Pictures/Ghub.png![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/166935a3-b50c-4121-a3db-266a4265236e)



# assignment 2:
file:///home/snallaga/Pictures/Ghub.png![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/39d9e862-ea67-42d5-b47d-53ecb948d13a)




# assignment 3:
file:///home/snallaga/Pictures/Ghub.png![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/590483ab-4ec3-4663-a0f5-8f247e71d76b)

set_input_delay -max [expr {0.4*$clock_period}] -clock clk [all_inputs] 

file:///home/snallaga/Pictures/Ghub.png![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/3ddb18a6-50a5-4c0e-b3ed-6f78dfe7e7d5)


# assignment 4:
file:///home/snallaga/Pictures/Ghub.png![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/1f4d8799-b76b-4cde-bfa7-5118be4813dc)

file:///home/snallaga/Pictures/Ghub.png![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/0cb1b1bb-3789-4277-8d58-4307baedd6c0)

# screenshot
![paths tcl](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/f286c293-5e02-4898-bce6-994f2b6a2273)

![bashrc_env_var](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/d3aaa88f-d8bd-44d7-9286-42893765420a)
![bashrc](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/d48bb950-e2a5-4877-8696-2315dae08a19)
![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/18c2845c-5c5b-4239-8b35-f7249324ab0c)

![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/7b27e27b-b644-4cc8-9562-40cab0d9880f)

#gobals & paths definitions
![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/e8ef2605-e58b-4d7f-8802-1bf74b5c8b28)
![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/8722fe08-90fc-4c98-8dbe-a9c0bafbf29d)

![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/3736132e-7cbd-4674-9975-ed11370123c0)

* if ref_libs are created, we need to delete the existing ref_libs and then can create with the same name orelse you can always create a new one.

![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/911450e0-c5b2-4fe5-8c18-54d740b6c9c7)

* after reading the verilog design, link the design:
  ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/fd415fff-ef19-44d4-84a1-4aa7f6c82d0f)

* setenv DISPLAY issue when start_gui was run. Reason X11 -> not enabled X11 forwarding. Once, enabled it was fixed:

  ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/fa1a0a8d-fe90-4d1f-931d-676e5981d142)

  ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/2dd7a64e-643d-45ac-b47a-653aecf36b9e)

  ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/c931ec54-5972-4bd5-a68e-8b1d7412b62e)

  ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/ce740882-37b3-420a-b59d-d4b20b9d7886)

  ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/18bc9ac3-42dc-484f-bf27-40c431e79aec)


  ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/f7afc8ec-8dc7-4dd1-be8d-492ca335778f)
* Apply <- when enabled or disabled any settings in the view settings
* explore view settings -> Tasks on the right pane/pallette

  ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/bf1a704e-be8f-4773-b593-fa209a846b54)
  * You can notice the tracks
 
    ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/e7adde31-8c43-4cf1-8384-b6c06f03e5d8)

    ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/3b85276e-85f6-4298-bf12-99130c181931)

    # initialize_floorplan examples:
    * initialize_floorplan -shape L -side_length {100 500 600 200}
    * initialize_floorplan -core_utilization 0.5 -shape L -side_ratio {100 200 200 200}
   
  
   
  ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/0a6d69c9-d26e-4d7b-b604-2a3a6ef15a3f)

![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/86817be9-a729-4ace-a4f8-47ab72437b61)


![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/bde10b37-ef8d-4a2a-91dc-04dcb98009b5)
* read the Error & understand the mistake made before. (Hint: ring & ring_pattern <- created)


![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/1251375e-c44d-4a2d-8008-a065205ba0f9)

![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/cabe31d4-08d1-42f7-ba58-5fee53a26cf6)

![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/1e04ce3f-f5a2-4040-851f-70e4fbeaebe9)
* before compile_pg

  ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/cafa14b4-25eb-4829-9df4-66aa0604aaeb)


  ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/d0f8e96a-505b-41eb-ab50-6edfde30c1c5)
  * Have you noticed, there is a problem (Hint: connection)
  * VDD & VSS of core_mesh not connected to core_ring
  * solution: -extension switch in set_pg_strategy
 
    ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/475e2140-892e-46a4-a406-9a685d46c9f5)

    ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/242acc73-e852-4a25-b56e-53c0979ad20e)

    ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/ed7dba63-1b08-4196-a497-123e1e46de3d)

    ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/1bee686f-fa6e-4ba2-86e4-0153c20708b4)
    * note: above -extension option fixed the connection issue
   
    ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/decff612-3311-4e3d-8df3-42a4f2b9301d)

    ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/b680cb87-f627-4ece-a887-eb99e583b49e)
    ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/d2752c4a-79c3-4885-87cd-a0a58cf401b9)

    # fp.tcl
    ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/7b1cd732-a838-4096-84d9-e2a27360190e)

    ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/5084745c-7c08-4d7d-a219-9af312c31b3f)

    ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/b74e0b9c-d86a-4364-81a6-f6bbe8e0f125)



    ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/ef9d2c15-7230-4d5b-b1d1-918f7931fdd5)

    ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/93e4133f-f932-474a-827a-a6c0aa6a1d10)


    * Lab: Experiment
    ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/a37700bf-179b-497b-bb1f-bb5a51f05b95)



![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/4fea0d50-cc7c-4d5a-898a-1190eb7b6601)
* no sroutes/site row rails

![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/b8493f2d-0780-4bdd-bba2-bac94640af92)
![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/6e3c2c01-6a1a-4f99-865a-5dd0140bc124)

![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/a6c42c47-046c-4de1-9c0c-9c42bd8f1f21)


![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/6e8eac4e-7dd8-45a4-a6f9-1ce561bf9e5c)

![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/1d966a56-ffbe-4f42-bf2d-2518c975268b)

![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/69a72020-475b-4f60-9b57-22f5a86ffc03)
* default flip_first_row is true -> flips the row sites for std_cell placement

![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/133bc3b6-e4d5-4551-8abd-9576a97b27d9)


![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/2f1ec88e-d555-4f18-8771-3837d30ff1fb)

![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/4b508dc2-2759-45ae-aa04-2d116abe7ac3)


![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/d8a7e992-c240-456d-9cff-38372f7b0a22)
![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/437e1649-cd6e-453f-b5df-fd3632bb84d0)

![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/e35ad199-b5ef-4985-ade7-e72353cc55b0)

![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/e8b5e0d3-34ad-49d0-a62a-105667bc1efb)



* There was issue with VSS site row rail: The VSS was not being routed when compiled.
*   Because, we have used create_net -power {VDD VSS}. VSS is ground.
*   create_net -power {VDD}
*   create_net -ground {VSS}
  ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/c7b654c0-80d1-4ecd-9952-36c4c12c2b7d)

![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/62d0bf62-6c65-4aec-9680-4b63e9534ad5)



# Vlsi expert pulp:
![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/1fdb8aaa-f84d-4355-ab72-07eb97758a69)

![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/4de5c96a-de1f-4e49-a8a6-4a61336181c3)

![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/00db5c90-d86a-4eee-b78e-9e0e73dfd6c5)

![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/166db4be-5d3d-4edc-bb4f-bd026ee8a022)

![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/2f591149-4a6c-4f87-b7c7-f746902bbcdd)

![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/063f28ed-c31d-4b1a-bcfb-2b30cf2a2d52)

![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/c0a43e87-508e-4e43-bf56-b8fee6195ddc)


# fixed PADRING
![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/60a717a7-316f-475d-bb9e-dd5a15da5231)

# scripts
![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/752c19ae-167a-46e9-aabd-823de384b1d6)
![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/8ee4de3e-241d-48da-8ef3-0732e905ca15)
![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/1c826f44-f4bc-49e9-8a7f-1f3ae62bc952)
![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/d8fe5e1d-a3dd-4d40-8c9e-ca416fd856ed)

# TCL padring placement
![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/1ea6a667-410e-42cd-8b15-002542456817)
![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/80c19af4-813c-473e-b458-e029ad37808a)
![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/955eebf3-ec55-4e2f-afb8-30db5bcf6eff)

* the question is why place_io needed after set_attribute on flipping the pad cell? && it works!!! Reason???? [need explanation]
* IN the below image you can notice, the place_io at line: 61 is commented out. Now only, place_io at line 90 is used. It worked.
  ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/77f55e6c-2dc8-4189-95f7-6a8603c3a7cd)


  # above script modified with procedures
  ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/86b4ea9c-7335-415b-93fd-f39e893d8fdc)
  ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/8bd92551-a7f5-419c-96a7-99e231dfc6b7)
  ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/c63ec2d2-d4a9-4def-b4a3-f213341c3a0a)
  ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/4763f054-c4c2-4af1-a107-da87add5268a)
  ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/385bbf06-ae19-4059-ae83-2e8206c4363c)



  # New script with power_io_constraints & flip_objects to flip the pads
  ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/7acbfc63-3ee0-4467-9a07-d0269af85bf2)
  ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/fd916bc6-f697-4362-bbbe-7aaa442ef7e8)
  ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/dc1a5d58-7494-42fb-ab5c-120062b3e943)
  ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/909fb913-a602-451d-9ea3-e152514d650c)
  ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/cee649d4-7140-4d2a-b198-4133d3b70960)
  ![image](https://github.com/snallaga9/VE_SNPS_PHYSICALDESIGN/assets/110479456/ccffb691-b843-4446-b77a-365683388a12)
  

































  



































  







































