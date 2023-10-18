# adrika_riscv
RISCV based MYTH 
This project is done as a part of MYTH : Microprocessor for you in thirty hours , hosted by RedWood EDA , VSD .
Day 1 and 2 can be found in the following repo : 

All the days codes are uploaded, feel free to look into it!

<details>
  <summary>
    DAY3:Digital logic with TL verilog and maker chip 
  </summary>

## What is RISCV?
RISC-V is an open-source instruction set architecture used to develop custom processors for Variety of applications.

## Why RISCV?
+ Open source and free to use
+  One of its kind open source hardware
+  Availability of smaller , energy - efficient and modular options .
+  Customizable ISA

What is TL Verilog?
Transaction level verilog or TL Verilog is an emerging System Verilog that supports a new design methodology, called transaction level design.

The fundamental building blocks for digital logics are logic gates , all in 1's and 0's 
+ Not gate
+ AND Gate
+ OR Gate
+ XOR Gate
+ NAND Gate
+ NOR Gate
+ XNOR Gate


### Combinational circuits 
Circuits dont have any memory , the output of the circuit at any instant of time , depends only on the levels present at input terminals .

### LAB EXERSCISES :
Pythagorean example 

![image](https://github.com/AdrikaMohanty/adrika_riscv/assets/84654826/689451c7-2ef7-456b-9bdb-064df1e4aed5)




A simple combinational calculator :

![image](https://github.com/AdrikaMohanty/adrika_riscv/assets/84654826/0e4a20af-5b71-4387-bd94-f86cfb05aac0)



### Sequential logic:
A sequential logic introduces a clock .
It has memory 


Let's take an example of Fibiniocci series : 1,1,2,3,5,8,13 and so on . It takes the sum of the previous number and the number before that . This in sequential can be implemented as below , here you will observe new notation ``` >>1 ``` this indicated the previous number as in n-1 and ``` >>2 ``` this indicates the number before the previous number as in n-2.


![image](https://github.com/AdrikaMohanty/adrika_riscv/assets/84654826/205d3233-b46a-4dd8-8ebb-3c2768515824)




A simple example of counter :

![image](https://github.com/AdrikaMohanty/adrika_riscv/assets/84654826/f42af53a-4eb6-4b6b-858c-5496c65b356a)


Sequential calculator :


![image](https://github.com/AdrikaMohanty/adrika_riscv/assets/84654826/ed5a5e1b-c8db-44d0-8eef-637fa9957782)



2 cycle Sequential calculator with validity and memory 


![image](https://github.com/AdrikaMohanty/adrika_riscv/assets/84654826/7423f209-61b7-4647-91c5-b5a8e1f58a18)

  
</details>


<details>
  <summary> DAY 4 AND DAY 5</summary>


  PC : Program counter 

  ![image](https://github.com/AdrikaMohanty/adrika_riscv/assets/84654826/fb56cdf7-5e46-4663-b212-9a6d423cf5f7)



  Instruction fetch

  ![image](https://github.com/AdrikaMohanty/adrika_riscv/assets/84654826/e8199f43-c6de-465b-a7ce-ff37008d37ee)



  Instruction decode :


  ![image](https://github.com/AdrikaMohanty/adrika_riscv/assets/84654826/5f573dba-a910-47a2-8256-34a0e35854b2)



  Read file 

  ![image](https://github.com/AdrikaMohanty/adrika_riscv/assets/84654826/8ab53195-1baf-4e91-9276-d2620d1306f1)



 


  Write register 

  ![image](https://github.com/AdrikaMohanty/adrika_riscv/assets/84654826/2e2441d2-7f81-46ac-b34d-5e73dd81a739)





   Branch instruction :


  ![image](https://github.com/AdrikaMohanty/adrika_riscv/assets/84654826/335915c8-ced2-4037-bf57-3ec56e4800f9)



</details>
