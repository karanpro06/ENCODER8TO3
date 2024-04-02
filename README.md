# ENCODER8TO3
# Aim
To design and simulate encoder using vivado.
# Apparatus Required
Personal computer with vivado software.
# Block diagram
![image](https://github.com/RESMIRNAIR/ENCODER3TO8/assets/154305926/824226c8-c767-44b5-ab35-26fed65b195e)
# Truth Table
![image](https://github.com/RESMIRNAIR/ENCODER3TO8/assets/154305926/e228c14b-b814-40c8-92eb-748d48570c04)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/ENCODER3TO8/assets/154305926/6fa5fe84-fe6f-472d-b9c0-e6dfa17413d3)
![image](https://github.com/RESMIRNAIR/ENCODER3TO8/assets/154305926/7d147e2a-ba03-4714-baee-17615c9c50c1)
# Program
~~~
 module encoder8to3(a0,a1,a2,d0,d1,d2,d3,d4,d5,d6,d7);
 input d0,d1,d2,d3,d4,d5,d6,d7;
 output a0,a1,a2;
 assign a0 = d1 | d3 | d5 | d7 ;
 assign a1 = d2 | d3 | d6 | d7 ;
 assign a2 = d4 | d5 | d6 | d7 ;
 endmodule
~~~
# Output
![image](https://github.com/karanpro06/ENCODER8TO3/assets/119782103/b7eead51-860e-4d7c-ad79-f7abccae9270)
# Result
Hence encoder is verified and simulated.
