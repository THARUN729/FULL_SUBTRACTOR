# FULL_SUBTRACTOR
# Truth Table and Circuit Diagram
![image](https://github.com/RESMIRNAIR/FULL_SUBTRACTOR/assets/154305926/351addef-f7bb-4862-9817-616a41b4c882)
![image](https://github.com/RESMIRNAIR/FULL_SUBTRACTOR/assets/154305926/906152b8-63bc-4f70-9132-6b6b4420b22d)
![image](https://github.com/RESMIRNAIR/FULL_SUBTRACTOR/assets/154305926/7d480140-153a-4a7e-a6d2-5323c6bd4974)
# Program
```
module fs(a,b,bin,d,bout);
input a,b,bin; 
output d,bout;
wire w1,w2,w3;
xor g1(w1,b,bin; 
xor g2(d,w1,a);
and g3(w2,a,~w1);
and g4(w3,~b,bin);
or g5(bout,w2,w3);
endmodule
```
# Output
![fullsubtractor](https://github.com/RESMIRNAIR/FULL_SUBTRACTOR/assets/161407766/f541f303-1343-4f59-945e-1dff6607cde4)

