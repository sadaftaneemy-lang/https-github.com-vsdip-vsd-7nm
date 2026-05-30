
# 7nm Finfet Circut design (BGR)
## What is Finfet ?
FinFET (Fin Field-Effect Transistor) is a 3D transistor structure used in modern VLSI technology to overcome the limitations of planar MOSFETs at very small technology nodes.

## What makes FinFET special?
The channel is shaped like a vertical fin standing on the silicon substrate. The gate wraps around the fin on 2 or 3 sides, giving much better control over the channel.

![WhatsApp Image 2026-01-22 at 5 07 43 PM](https://github.com/user-attachments/assets/b4576905-2c77-4c05-9e8d-bbeec1304e07)

# The Main topics covered in the Workshop are:

## - Scaling beyond CMOS : Finfet Devices and Innovations

   1. Path to Zetta scale Computing
   2. CMOS Evolution And Next-Gen Candidates
   3. Introduction To FinFets
   4. CMOS Technology Inflection Points
   5. Standard Cell Area Scaling and variability
   6. Parasitics Resistance and Capacitance
   7. Device Scaling and Electrical characteristics
   8. 3-D Structures 
   9. BOEL Innovations
 
## - Lab to Simulation: 7nm FinFET Inverter Performance Analysis
   
   10. First N-FET Characteristics using 7nm PDKS
   11. First Inverter Characteristics Using 7nm Fin FETS
   12. Inverter Spice Deck and characteristic Modelling
   13. W/L Ratio, Vt, Power Consumption. Prop Delay, Gain and Noise Margin
   14. Transconductance, Frequency and Inverter Characteristics Table Assignment
   15. Lab Tips to calculate Switching Threshold, Drain Current and power
   16. Lab Tips to calculate Prop Delay, Transconductance and Frequency

 ## - Designing Bandgap References using 7nm FinFETs

   17. Introduction to Bandgap
   18. Bandgap Component Placement Using Xchem
   19. Bandgap Circuit Wiring Using Xschem
   20. Bandgap Circuit Final Simulations
   20. Assignment

## 1. Path to Zetta scale computing
Zetta-scale computing refers to systems capable of performing 10²¹ operations per second (a zettaflop).

<img width="1600" height="865" alt="image" src="https://github.com/user-attachments/assets/be587b5f-aa07-4c3a-8e0e-da3b6141053b" />

The figure titled “50 Years of Microprocessor Trend Data” illustrates the long-term evolution of microprocessor technology from the 1970s to around 2020 by showing how key architectural and physical parameters have scaled over time. Over the decades, the number of transistors on a chip has continued to increase exponentially, following Moore’s Law, enabled by advances in semiconductor fabrication and device scaling.

🔹 1. Transistors (orange ▲)
- Grows exponentially over time
- This is Moore’s Law: transistor count doubles roughly every 18–24 months
- Still increasing even today
  
🔹 2. Single-Thread Performance (blue ●)
- Increased rapidly until ~2005
- After that, growth slows significantly
- Reason: limits of frequency and power
  
🔹 3. Clock Frequency (green ■)
- Rose steadily up to ~2005 (~3–4 GHz)
- Then plateaued
- This is the Frequency Wall
  
🔹 4. Typical Power (red ▼)
- Increased until ~2005
- Then flattened
- Indicates the Power / Thermal Wall
- Chips cannot consume more power without overheating
  
🔹 5. Number of Logical Cores (black ◆)
- Stayed low until ~2005
- After that, increases sharply
- Industry shifted to multi-core processors

   
