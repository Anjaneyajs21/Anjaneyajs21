## Anjaneya J S

**M.Tech, Electrical Engineering · IIT Madras · Class of 2027**

RTL design, verification and VLSI implementation: from pipelined CPUs and AXI-Stream DSP blocks to custom Sky130 layout and static timing analysis. Every project below has a self-checking testbench and measured results.

M.Tech thesis: DSSS radio transceiver on **Zynq UltraScale+ (ZCU102)**

---

### Computer architecture

| Project | Highlights |
|---|---|
| **[5-stage pipelined RV32I CPU →](https://github.com/Anjaneyajs21/rv32i-5stage-pipeline)** | SystemVerilog · full forwarding, load-use stall, branch flush · retire-trace **differential testing vs. a Python ISS** on 100+ random programs · CPI and branch analysis from performance counters |
| **[Direct-mapped cache controller →](https://github.com/Anjaneyajs21/direct_mapped_cache_controller)** | Verilog cache controller (tag/valid, hit/miss handling, memory interface) |

### ASIC design & verification

| Project | Highlights |
|---|---|
| **[AXI4-Stream DSP IP library →](https://github.com/Anjaneyajs21/axis-dsp-ip)** | Zadoff–Chu spreader, cyclic-prefix inserter, Gray-code async FIFO, skid buffer · **bit-exact** vs. a fixed-point Python model under random backpressure · AXI-Stream protocol checkers · 1 beat/clock |
| **[Synchronous FIFO →](https://github.com/Anjaneyajs21/sync-fifo)** | Any depth (incl. non-power-of-2), FWFT/registered read, almost-full/empty, overflow protection · checked **every cycle** against a queue model |
| **[Asynchronous FIFO (CDC) →](https://github.com/Anjaneyajs21/Asynchronous_fifo)** | Dual-clock FIFO with Gray-code pointers and 2-flop synchronizers |
| **[UART TX/RX →](https://github.com/Anjaneyajs21/UART-core-modular-RTL-with-FSM-based-TX-RX)** | Modular FSM-based UART transmitter and receiver |

### VLSI & physical design

| Project | Highlights |
|---|---|
| **[16-bit carry-bypass adder: schematic → layout → STA →](https://github.com/Anjaneyajs21/carry-skip-adder)** | **Custom Sky130 layout in Magic, DRC/LVS clean** · post-layout ngspice: 2.95 ns sum / 1.62 ns carry · Yosys + OpenSTA: **false-path analysis 7.69 → 4.24 ns (1.81× Fmax)** |

### FPGA & hardware acceleration

| Project | Highlights |
|---|---|
| **[3×3 convolution accelerator (Vitis HLS) →](https://github.com/Anjaneyajs21/hls-conv2d)** | Line buffers + sliding window at **II = 1** · AXI-Stream / AXI-Lite for PYNQ · 56 bit-exact tests including 1×1 / 1×N edge cases |

---

### Skills

| | |
|---|---|
| **Design** | Verilog, SystemVerilog, pipelining & hazards, AXI4-Stream / AXI-Lite / AXI DMA, CDC, fixed-point DSP |
| **Verification** | Self-checking & constrained-random testbenches, reference-model / differential testing, protocol checkers, mutation testing |
| **Implementation** | Yosys, OpenSTA, OpenLane (Sky130), Magic, DRC/LVS, ngspice, Vivado, Vitis HLS |
| **Architecture** | Branch prediction (TAGE-SC-L), caches & memory hierarchy, performance analysis |
| **Hardware** | Zynq UltraScale+ ZCU102, PYNQ-Z2 |
| **Languages** | C/C++, Python, TCL, MATLAB |

---

**Contact:** anjaneyajs21@gmail.com · ee25m011@smail.iitm.ac.in · [All repositories](https://github.com/Anjaneyajs21?tab=repositories)
