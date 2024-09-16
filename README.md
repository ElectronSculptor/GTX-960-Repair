
# EVGA GTX 960 Graphics Card Repair

It was the first time I'd touched electronics and a soldering iron. The project I completed in 2021 opened my eyes to the world of electronics, showing the complexity of a system like a graphics board. I then began a large series of repairs to electonic cards and computers, in parallel with my studies.


## Overview
This project details the repair of an **EVGA GTX 960** graphics card, which suffered from a power delivery issue due to a faulty MOSFET. The repair involved diagnosing the problem, identifying and replacing the defective **4C10N MOSFET**, and testing the restored GPU.

## Project Steps
1. **Diagnosis**:
   - First time I plugged the card I got an error message: "Please power down and connect the **PCIe power cables** for this graphics card."
   - I then realized that the problem has nothing to do with the GPU and the VRAM (Video RAM), as my screen displayed the error without any issue.
   - So I started investigating power-related components using a digital microscope and multimeter in order to find a faulty component.

2. **Power System Analysis**:
   - Verified PCIe connections using a pinout diagram.
   - Tested all MOSFETs and phases, looking at their resistance and connexions thanks to continuity mode.
   - Then I identified the 4C10N MOSFET (named "Q27" on the card) as faulty, as it was the only one with short-circuited Source pins, and a lower resistance value.

3. **Repair**:
   - I ordered a **NTMFS4C10N** component on Aliexpress 
   - I practiced soldering other simple components to get used to handling the tool before working on the board.
   - Once I felt ready, I replaced the faulty MOSFET with a new NTMFS4C10N component, following proper desoldering and soldering techniques.

4. **Testing**:
   - After reassembly, the GPU was successfully tested without errors. The resistance was correct and no component got too hot.

## Key Components
- **EVGA GTX 960 Graphics Card**: A mid-range GPU used in gaming.
- **NTMFS4C10N MOSFET**: N-channel MOSFET used for power delivery in the GPU.

## Tools and Equipment
- **Digital Microscope**
- **Multimeter**
- **Soldering Station**
- **Flux, clamps**
- **PCIe Power Pinout Diagram** and **NTMFS4C10N Datasheet** for reference.
- **Some Youtube videos**


## Conclusion
By identifying and replacing a faulty MOSFET, the EVGA GTX 960 was successfully repaired. 
I am grateful for the “Actually Hardcore Overclocking” Youtube channel, which helped me troubleshoot the card, explaining how it works and the links between the mosfets. I'd also like to thank my brother Artur for supporting me in this project and ordering the necessary materials, given that I started it without any basic knowledge of welding or electronics.
