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






  







































