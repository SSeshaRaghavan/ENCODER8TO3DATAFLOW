### ENCODER 8TO3 DATAFLOW Modelling

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
![WhatsApp Image 2024-12-08 at 21 12 31_1043ff34](https://github.com/user-attachments/assets/b02c6197-3ed2-4f2f-90c0-ec12cb4c4f96)

/* Program for Encoder 8 To 3 in Dataflow Modelling and verify its truth table in quartus using Verilog programming. 

Developed by:S Sesha Raghavan RegisterNumber: 24900320
*/

**RTL LOGIC FOR Encoder 8 To 3 in Dataflow Modelling**
![WhatsApp Image 2024-12-08 at 21 12 30_f18daf45](https://github.com/user-attachments/assets/3d0fee39-a916-4848-8c42-2a56b9c04b6a)

**TIMING DIGRAMS FOR Encoder 8 To 3 in Dataflow Modelling**
![WhatsApp Image 2024-12-08 at 12 23 55_6d58531b](https://github.com/user-attachments/assets/3678450a-113a-4d12-a20f-2a238b114bc9)

**RESULTS**
![WhatsApp Image 2024-12-08 at 21 12 30_f708146a](https://github.com/user-attachments/assets/75f0b354-dc11-4e06-82ea-a67052216e49)




