# 🧠 Lab 01 – GPU Installation and DisplayPort 1.2 Daisy Chaining

**Lab Source:** A+ Core 1 and Core 2 Virtual Workbench  
**Duration:** 53 minutes, 16 seconds  
**Score:** ✅ Passed (100%)  
**Focus Areas:** GPU installation, DisplayPort configuration, daisy chaining monitors  
**Date Completed:** May 2025, June 2025 

---

## 🧩 Summary
This lab introduced me to **graphics card installation** and **DisplayPort 1.2 daisy chaining**, two essential skills for optimizing multi-monitor setups in modern workstations.  
Before this lab, I wasn’t familiar with the concept of daisy chaining — the ability to link multiple monitors together through a single DisplayPort connection. This exercise helped me understand both the physical setup and the underlying protocol that makes it possible.

---

## 🧰 Steps Taken
1. **Powered Down & Discharged System**
   - Shut down the system and **held the power button for 30 seconds** after unplugging to drain residual power.
   - Attached **ESD strap** for protection before opening the case.

2. **Prepared the Case**
   - Removed **blanking plates** from PCIe slots to make room for the discrete GPU.
   - Verified the available PCIe slot and adequate clearance for airflow.

3. **Installed the GPU**
   - Firmly seated the graphics card into the PCIe x16 slot.
   - Secured it with case screws and ensured the external connectors aligned properly.

4. **Configured Daisy Chain**
   - Connected **Monitor 1** directly to the GPU using a DisplayPort 1.2 cable.
   - Connected **Monitor 2** to **Monitor 1** via DisplayPort output (DP Out).
   - Confirmed both monitors received signal in extended display mode.

---

## 🧠 Key Learnings
- **Daisy chaining** only works when **both GPU and monitors support DisplayPort 1.2 MST (Multi-Stream Transport)**.
- DisplayPort’s **bandwidth allocation** determines how many displays can be chained before performance or resolution drops.
- Understanding the physical **signal path** helps with diagnosing common user issues like “only one monitor detected” or “no signal on second display.”
- Taking **ESD precautions** and verifying **power discharge** is critical — it’s easy to forget, but one slip can damage a GPU or motherboard.

---

## 🧩 Reflection
I really enjoyed this lab because it connected multiple pieces of the puzzle: *hardware handling*, *video standards*, and *display configuration logic*.  
I used to think multi-monitor setups were purely software-based, but now I understand the importance of physical signal flow and compatibility layers.  
This also made me curious about **macOS and AV equipment chaining** — how Apple handles Thunderbolt/DisplayPort protocols differently, and how that might impact real-world troubleshooting at places like **Bold Orange**.

---

## 🧱 Skills Demonstrated
- Safe disassembly and component handling (ESD discipline)
- GPU hardware installation
- DisplayPort 1.2 MST configuration
- Multi-monitor diagnostics
- Hardware documentation workflow

---

## 📸 Screenshots
*(Add your screenshots here once gathered — e.g. GPU installation steps, DisplayPort chain diagram, monitor detection results.)*
