# FULL_SUBTRACTOR
# AIM:
To simulate and synthesis full subtractor using vivado.

# APPARATUS REQUIRED:
vivado 2023.2 software.

# PROCEDURE:
```
STEP:1 Start the vivado software, Select and Name the New project.
STEP:2 Select the device family, device, package and speed.
STEP:3 Select new source in the New Project and select Verilog Module as the Source type.
STEP:4 Type the File Name and module name and Click Next and then finish button. Type the code and save it.
STEP:5 Select the run simulation and then run Behavioral Simulation in the Source Window and click the check syntax.
STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table.
STEP:7 compare the output with truth table.
```
# Truth Table and Circuit Diagram
![image](https://github.com/RESMIRNAIR/FULL_SUBTRACTOR/assets/154305926/351addef-f7bb-4862-9817-616a41b4c882)
![image](https://github.com/RESMIRNAIR/FULL_SUBTRACTOR/assets/154305926/906152b8-63bc-4f70-9132-6b6b4420b22d)
![image](https://github.com/RESMIRNAIR/FULL_SUBTRACTOR/assets/154305926/7d480140-153a-4a7e-a6d2-5323c6bd4974)
# VERILOG CODE:
# FULL_SUBTRACTOR:
```
module full sub(a, b, bin, diff, borrow);
input a,b,bin;
output diff, borrow;
wire w1,w2, w3;
xor gl(wi,a,bin);
and g2(w2,a,b);
xor (diff, w1, bin);
or g4(borrow, w2,3);
add g5(w3,-w1,bin);
endmodule
```
# OUTPUT:
![image](https://github.com/THARUN729/FULL_SUBTRACTOR/assets/161407766/b294fc76-c9cf-463e-bf7b-c2307e8663b1)

# RESULT:
Thus the verilog program for full subtractor has been simulated and verified successfully.
