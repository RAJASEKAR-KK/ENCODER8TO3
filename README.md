# ENCODER8TO3
# AIM:
To simulate and synthesis Encoder using vivado.

# APPARATUS REQUIRED:
vivado Xilinx 14.7 Spartan 6 FPGA.

# PROCEDURE:
STEP:1 Start the vivado software, Select and Name the New project.

STEP:2 Select the device family, device, package and speed.

STEP:3 Select new source in the New Project and select Verilog Module as the Source type.

STEP:4 Type the File Name and module name and Click Next and then finish button. Type the code and save it.

STEP:5 Select the run simulation and then run Behavioral Simulation in the Source Window and click the check syntax.

STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table.

STEP:7 compare the output with truth table.

![image](https://github.com/RESMIRNAIR/ENCODER3TO8/assets/154305926/824226c8-c767-44b5-ab35-26fed65b195e)
# Truth Table
![image](https://github.com/RESMIRNAIR/ENCODER3TO8/assets/154305926/e228c14b-b814-40c8-92eb-748d48570c04)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/ENCODER3TO8/assets/154305926/6fa5fe84-fe6f-472d-b9c0-e6dfa17413d3)
![image](https://github.com/RESMIRNAIR/ENCODER3TO8/assets/154305926/7d147e2a-ba03-4714-baee-17615c9c50c1)
# VERILOG CODE:
```
module encoder(d,a,b,c);
input [7:0]d;
output a,b,c;
or (a,d[4],d[5],d[6],d[7]);
or (b,d[2],d[3],d[6],d[7]);
or (c,d[1],d[3],d[5],d[7]);
endmodule
```
# OUTPUT:
![Encoder 8 to 3](https://github.com/RESMIRNAIR/ENCODER8TO3/assets/165815233/14e1bed4-5d3c-43ce-b7e7-7c39241f1faf)

# RESULT:
Thus, the verilog program for Encoder has been simulated and verified successfully.
