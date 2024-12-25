# SERIAL-IN-SERIAL-OUT-SHIFTREGISTER

**AIM:**

To implement  SISO Shift Register using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**SISO shift Register**

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![image](https://github.com/naavaneetha/SERIAL-IN-SERIAL-OUT-SHIFTREGISTER/assets/154305477/e81c4072-37f9-46c6-8145-566764b74c3a)

Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.

**Procedure**


![image](https://github.com/user-attachments/assets/31f76e45-c7a3-4bcd-ba7a-05c70a11c348)


**PROGRAM**


![image](https://github.com/user-attachments/assets/16e43fa7-1ebc-48da-a534-31dea1ecc4b1)

/* Program for flipflops and verify its truth table in quartus using Verilog programming.

Developed by:Priyesh. S


RegisterNumber:24008184

*/

**RTL LOGIC FOR SISO Shift Register**


![image](https://github.com/user-attachments/assets/e5dbba6d-13b9-4b01-9925-71c4312228f2)

**TIMING DIGRAMS FOR SISO Shift Register**


![image](https://github.com/user-attachments/assets/8d6d2afe-f5e9-4938-a724-df70f7c45558)

**RESULTS**

Thus the SISO shift register is implemented and its functionality is validated in
 Quartus using Verilog Programming
