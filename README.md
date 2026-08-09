
# 7nm Finfet Circut design (BGR)
## What is Finfet ?
FinFET (Fin Field-Effect Transistor) is a 3D transistor structure used in modern VLSI technology to overcome the limitations of planar MOSFETs at very small technology nodes.

## Why do we use FinFET?

As transistors became smaller (45nm, 22nm, 14nm, 7nm, etc.), traditional planar MOSFETs started facing serious problems:

- High leakage current
- Increased power consumption
- Poor gate control over the channel
- Short-channel effects
- Reduced performance

To overcome these issues, the semiconductor industry introduced the FinFET architecture.

### 📌 Main Idea

In a planar MOSFET, the gate controls the channel from only one side.

In a FinFET, the channel is shaped like a vertical "fin," and the gate wraps around multiple sides of the fin.

This gives much stronger control over the flow of current.

## What makes FinFET special?
The channel is shaped like a vertical fin standing on the silicon substrate. The gate wraps around the fin on 2 or 3 sides, giving much better control over the channel.

<img width="254" height="199" alt="image" src="https://github.com/user-attachments/assets/4045f257-c71e-4b74-814f-2b7629f2439d" />


## Benefits of FinFET

**1. Lower Leakage Current**

   One of the major advantages of FinFET technology is its ability to reduce leakage current. In conventional planar MOSFETs, a small amount of current can flow      even when the transistor is turned off. FinFETs provide better control over the channel, which significantly reduces this unwanted leakage and improves power      efficiency.

**2. Better Gate Control**
   
   In a FinFET, the gate surrounds the channel from multiple sides instead of controlling it from only one side. This structure allows the gate to control the        flow of current more effectively, resulting in improved transistor operation and reliability.

**3. Lower Power Consumption**
   
   Because of the improved gate control and reduced leakage current, FinFETs consume less power compared to traditional planar MOSFETs. This makes them highly        suitable for battery-powered devices such as smartphones, tablets, and laptops.

**4. Higher Performance**
   
   FinFET transistors can switch on and off more efficiently, which helps circuits operate at higher speeds. This improved switching performance contributes to       faster processors and better overall system performance.

**5. Reduced Short-Channel Effects**
   
   As transistor dimensions shrink to nanometer scales, several unwanted effects begin to appear, degrading performance. FinFET technology minimizes these short-     channel effects by providing stronger control over the channel, ensuring stable operation even at very small technology nodes.

**6. Scalability for Advanced Technologies**
   
   FinFETs are well suited for advanced semiconductor manufacturing processes such as 7nm, 5nm, and beyond. Their structure allows manufacturers to continue          increasing transistor density while maintaining performance and power efficiency


# The topics covered in the Workshop are:

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


**Startup Circuit**

A startup circuit is required to ensure that the bandgap reference starts up correctly and avoids falling into a non-operational state (zero-current state). Without this circuit, the bandgap could remain in an undesired state where no current flows, rendering the reference non-functional.

**Startup Transistors :** The bottom part of the circuit includes additional transistors, like nfet8 and pfet6, that help kick-start the current when power is first applied, ensuring the circuit reaches its stable operating point.
  
   
