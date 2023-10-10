---

## Computer Architecture

### Part I: Access speed of registers
The Intel i5 13600k CPU operates at a clock speed of 5.1GHz. A single CPU register access necessitates one clock cycle. How much time is needed for one register access?

### Part II (Homework): Access speed of RAM
The time it takes to access a specific memory location is determined by the memory module's Column Address Strobe (CAS) latency,  often abbreviated as CL, which represents the number of cycles needed for the access. A DDR5-5600 CL32 module operates at 5600MT/s (megatransfers per second) at a latency of 32 clock cycles. Note that due to the double data rate nature of DDR, the actual clock frequency is half the data rate. So, DDR5-5600 actually operates at a clock frequency of 2800 MHz. How long would a single memory access take?

### Part III (Homework): Von Neuman Bottleneck
What is the Von Neuman Bottleneck? How does the Harvard Architecture address it?

---

## Part 1: Access speed of registers

\[f = \frac{Hz}{s} = 5.1 * 10^{9}\]
\[s = \frac{Hz}{f} =\frac{1}{5.1 * 10^9} \approx 196 * 10^{-12} \approx 196 \text{picosec} \]

## Part II: Access speed of RAM