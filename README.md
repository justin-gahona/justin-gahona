# Hey, I'm Justin Gahona

B.S. Computer Engineering → M.S. Electrical Engineering @ Texas Tech University  
Texas Instruments SDE Program  
19 years old | Minneapolis, MN → Lubbock, TX  
Open to FPGA, embedded systems, firmware, and embedded ML roles

## Projects

### ECG Arrhythmia Classifier
Real-time 1-D CNN deployed on two independent embedded targets — STM32F446RE
via X-CUBE-AI and a Nexys A7-100T FPGA via a hand-written SystemVerilog
inference pipeline. Trained on MIT-BIH Arrhythmia Database. 98.17% INT8
accuracy (float32 baseline 98.14%). Added adaptive average pooling to reduce
FC1 parameters 11× and fit within the STM32F446RE's 512 KB flash constraint.
FPGA target renders live scrolling ECG + classification label on VGA at 640×480.

`PyTorch` `SystemVerilog` `STM32` `FPGA` `C` `Embedded ML`

[→ View Repository](https://github.com/justin-gahona/ecg-arrhythmia-classifier)

---

### Custom 16-bit RISC CPU with Hardware GPU
Designed from scratch in SystemVerilog on Basys 3 (Artix-7) FPGA. Custom ISA,
ALU, register file, memory-mapped GPU with 32-sprite renderer, SPI NOR Flash
cartridge interface, and Python assembler. Synthesized to 3,448 LUTs at 100 MHz.
Runs Pong end-to-end as the demonstration application.

`SystemVerilog` `FPGA` `CPU Architecture` `Vivado`

[→ View Repository](https://github.com/justin-gahona/fpga-risc-cpu)

---

## Skills
**HDL:** SystemVerilog, Verilog  
**Embedded:** STM32, C, UART, SPI, DMA  
**ML:** PyTorch, ONNX, INT8 Quantization  
**Tools:** Vivado, STM32CubeIDE, X-CUBE-AI, KiCad, Git  

🔗 [LinkedIn](https://linkedin.com/in/justin-gahona)
