# ENCODER 8TO3 DATAFLOW Modelling


### Developed by: ADITYAH M S
### RegisterNumber:212223220002

**AIM:**

To implement  Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:** Quartus prime

**THEORY**

**Encoder 8 To 3**

The 8 to 3 line Encoder is also known as Octal to Binary Encoder. In 8 to 3 line encoder, there is a total of eight inputs, i.e., D0, D1, D2, D3, D4, D5, D6, and D7 and three outputs, i.e., A0, A1, and A2. In 8-input lines, one input-line is set to true at a time to get the respective binary code in the output side. Below are the block diagram and the truth table of the 8 to 3 line encoder.

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/0bc242c1-eb9e-4c47-afe5-30428470efc3)

Figure 01  Block Diagram of Encoder 8 * 3

**Truth Table**

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/35496b14-ae6e-4cd1-9abd-d6736b576575)

The logical expression of the term A0, A1, and A2 are as follows:

A0 = D1 + D3 + D5 + D7

A1 = D2 + D3 + D6 + D7

A2 = D4 + D5 + D6 + D7

Logical circuit of the above expressions is given below:

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/95acaee6-c873-4c75-89eb-ef09fb158053)

Figure 02  Encoder 8 * 3

**Procedure**

/* write all the steps invloved */

**PROGRAM**





![Screenshot 2024-04-03 210212](https://github.com/NaveenKumarV2005/ENCODER8TO3DATAFLOW/assets/151476286/9d29d01c-4a7a-4fb8-8fc8-e54ee71ce400)






**RTL LOGIC FOR Encoder 8 To 3 in Dataflow Modelling**

![Screenshot 2024-04-03 205445](https://github.com/NaveenKumarV2005/ENCODER8TO3DATAFLOW/assets/151476286/7329dca4-0120-4c9d-8057-296054ed3325)







**TIMING DIGRAMS FOR Encoder 8 To 3 in Dataflow Modelling**

![Screenshot 2024-04-03 205501](https://github.com/NaveenKumarV2005/ENCODER8TO3DATAFLOW/assets/151476286/51f09703-e8a1-441a-be50-f0e20b6ace03)





**RESULTS**



   implement  Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables





