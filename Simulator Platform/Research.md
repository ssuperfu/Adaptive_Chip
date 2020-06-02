# Research of Simulator Plaform
- Booksim2
  - public time: 2013/7/15
  -  allows for more network geometries but is also driven by synthetic traffic patterns.
  - [open-source](https://github.com/booksim/booksim2)
  - [article](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6557149)
  - Netrace
    - a trace-based network simulation platform that encodes dependencies between network messages
    - capture cycle-accurate benchmark traces for the network simulator
    - [article](https://dl.acm.org/doi/pdf/10.1145/1921249.1921258)
- Gem5-GPU Simulator
  - used to implement routers
  - obtian detailed processor and network-level information
  - DSENT2.0: calucate power consumption
  - Design Compiler: evaluate the area overhead and calibrate the static power consumption
  - GARNET, along with GEMS, provides a detailed and accurate memory system timing model
    - [article](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4919636)
  - SIMICS
- Multi2Sim
  - a full system simulator
  - [open-source](https://github.com/Multi2Sim/multi2sim)
- HORNET
  - a highlly configurable and cycle-acccurate NoC Simulator
  - HORNET can run in network-only mode using synthetic traffic or traces, or directly emulate a MIPS-based multicore.
  - ORION: power estimation
  - [open-source]( http://csg.csail.mit.edu/hornet/)
  - [article](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6200443)
- Noxim
  - models a mesh NoC and, allows the user to customize a variety of parameters like network size, VC sizes, packet size distribution, routing scheme
  - it is limited to 2-D mesh interconnects and is traffic-pattern-driven rather than integrated with a processor frontend
  - [open-source](https://github.com/davidepatti/noxim)

- M5 Simulator
  - Full-system simulation
  - [article](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1677503)
  - [open-source](https://sourceforge.net/projects/m5sim/)
- RSIM
  - publilc time: 1997
  - simulates shared-memory multiprocessors and uniprocessors designed for high instruction-level parallelism; it includes a multiprocessor coherence protocol and interconnect, and models contention at all resources
  - SICOSYS
    - a general-purpose interconnection network simulator that captures essential details of low-level simulation, and has been integrated in RSIM

FPGA-based Simulator
- HaSIM
  - FPGA-based simulators
  - [article](https://dl.acm.org/doi/pdf/10.1145/1575774.1575775?download=true)
- RAMP
  - FPGA-level emulator platforms
  - [article](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1620784)

Directly test on boards

# Some points needs to deeply research
- Trace-driven
- Dependence-driven
