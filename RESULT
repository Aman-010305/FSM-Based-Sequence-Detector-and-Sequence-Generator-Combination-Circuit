## Results

The FSM-based sequence generator and detector system was successfully simulated and implemented on FPGA, demonstrating accurate real-time performance and reliable hardware operation.

## Simulation Waveforms

![Simulation Waveform](Simulated_OP_Waveform.jpg)
![ILA Waveform](OP_gen_detec.jpg)

The simulation results validate the correct operation of the system:
- Stable clock ensures synchronized FSM transitions  
- Generated output (`gen_out`) exhibits both random and controlled sequence behavior  
- Detection signal (`detect`) is asserted HIGH only after complete sequence match (`01111110`)  

## Waveform Analysis

- Detection occurs strictly at the **final state**, ensuring precise operation  
- Output is active for **one clock cycle only**, avoiding redundant signals  
- No false triggering for partial or incorrect patterns  
- FSM accurately follows each bit through defined state transitions  

## ILA Observations

- In **random mode (`a = 0`)**, the detect signal remains LOW, confirming no unintended detection  
- In **controlled mode (`a = 1`)**, the system injects the target sequence and produces clear detection pulses  
- Real-time waveform capture confirms correct hardware-level FSM behavior  

## Hardware Output

![FPGA Output](HW_imp_2.jpg)

- LED turns ON only when the target sequence is detected  
- LED remains OFF for invalid or incomplete sequences  
- Demonstrates reliable real-time implementation on FPGA hardware  

## Final Outcome

- Accurate detection of sequence `01111110`  
- Zero false detection  
- One-clock-cycle precise output  
- Efficient FSM design with optimized transitions  
- Successful real-time FPGA validation  
