# Solar-Wind-Biomass Hybrid Microgrid Architecture

## Block Diagram / Architecture

<p align="center">
  <img src="activity/images/img 2.png" alt="Hybrid OTEC System Block Diagram" width="50%">
  <br>
  <em>Figure 1: Block Diagram of a Tribrid Renewable Energy System.</em>
</p>

The system is centered around an **AC Bus** (for the load and controllable source) and a **DC Bus** (for variable sources and storage).  
A **Central Microgrid Controller** manages power flow among the three sources, the Battery Bank, and the loads, ensuring **frequency and voltage stability**.

---

## System Explanation

### **Source of Energy**
This **Tribrid Microgrid** combines three complementary renewable sources for maximum reliability:
- **Solar PV:** Converts sunlight into DC electrical energy.
- **Wind Energy:** Converts wind’s kinetic energy into electrical energy.
- **Biomass:** Converts organic residues (agricultural or forest waste) into Syngas through gasification for controllable power generation.

---

### **Conversion Process**
- **Solar PV:** Generates DC power regulated through MPPT and fed to the DC Bus or used to charge the Battery Bank.  
- **Wind Turbine:** Produces AC power that is rectified to DC via an AC/DC converter to integrate with the DC Bus.  
- **Biomass Gasifier System:** Converts biomass into Syngas, which powers a Gas Engine Generator to produce AC power for the AC Bus.  
- **Battery Bank:** Interfaces between DC and AC buses through a Bi-directional Inverter, balancing supply and demand dynamically.

---

### **Output / Utilization**
The hybrid microgrid delivers high-quality **AC power** to:
- Residential and agricultural loads  
- Water pumping systems  
- Rural health clinics and schools  
- Street lighting and communication systems  

---

### **Real-World Application Relevance**
Hybrid systems like this are vital for **off-grid or remote communities** where national grid access is unreliable or absent.  
By integrating **solar**, **wind**, and **biomass**, the system ensures:
- **Reduced Loss of Power Supply Probability (LPSP)**  
- **24/7 operation capability** via biomass as a dispatchable backup  
- **Local resource utilization** reducing dependency on fossil fuels  
- **Socio-economic upliftment** by converting local waste into energy  

