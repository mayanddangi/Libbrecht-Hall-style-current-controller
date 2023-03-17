This project aims to develop an improved version of the Libbrecht-Hall circuit, a popular low-noise current driver for narrow-linewidth diode lasers, by developing a new current controller for the Cold Atom Quantum Technologies Lab at IIT Delhi. To accomplish this, a new current controller is designed with a slight modification to its component that can handle current limits of 750 mA.

Before implementing the new current controller in hardware, the circuit design will be optimized using LTSpice's simulation tools. We have also integrated a display module for displaying current by interfacing it with the microcontroller (ATMega328P). In the future, it is planned to integrate microcontroller circuitry on the same PCB as the current controller to reduce space and costs. This design is highly miniaturized and cost effective, with an estimated cost of around $145 (12k INR). Currently, we are conducting tests to evaluate the new controller's noise performance and contrast it with the current Libbrecht-Hall circuit. The current fluctuations are about 50"mu"A below 200 mA, and they are about 1 mA around 350mA. We are targeting to increase its performance by bringing current fluctuations below 50"mu"A for the high current range and below 10"mu"A for the low current range. The system, which was created for preliminary testing, has a dimension of about 70mm x 150mm. This size can be reduced to about 60mm x 90mm without integrating a display system by switching out some SMT components for SMD ones and reorienting the components position.

We hope to benefit the scientific community by sharing this project on Github and offering a high constant current driver in low cost for noise-free driving of narrow-linewidth diode lasers or for any other applications.

### Image of Schematic's design
![alt text](sch.png)
### Image of PCB's Design
![alt text](pcb2.png)

### Refrences
<ul>
  <li> Libbrecht, K. G., and John L. Hall. "<a href="https://aip.scitation.org/doi/citedby/10.1063/1.1143949">A low‐noise high‐speed diode laser current controller.</a>" Review of scientific instruments 64, no. 8 (1993): 2133-2135.</li>
</ul>
