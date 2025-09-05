# Solar Panel Charging Battery in Cisco Packet Tracer

## 🎯 Aim
To design and set up a simple battery system in Cisco Packet Tracer that charges a battery using energy from a solar panel, and verify its operation through the Power Meter and Battery monitoring tools.

---

## ⚡ Explanation / Procedure
1. Open **Cisco Packet Tracer** and place the following devices from **End Devices → Power Grid**:
   - Solar Panel
   - Power Meter
   - Battery

2. Use the **IoT Custom Cable** to make the following connections:
   - Solar Panel `D0 → Power Meter D0`
   - Battery `D0 → Power Meter D1`

3. Switch from **Logical view** to **Physical view**. Select the environment (e.g., *Home/City*) and increase the **Sunlight** value under the **Environment** tab.

4. Switch back to **Logical view**.  
   - Open the **Power Meter GUI** to observe the power flow from the solar panel.  
   - Open the **Battery GUI** to check the state of charge.

---

## ✅ Results
- When the sunlight level is increased above zero in the Environment settings, the Solar Panel begins to generate power.  
- The **Power Meter** displays the watts produced by the panel.  
- The **Battery GUI** shows the charging percentage increasing.  

This demonstrates that the battery system successfully charges using solar energy.

---

## 📌 Conclusion
A simple solar power system was implemented in Cisco Packet Tracer. The simulation shows that sunlight drives energy generation in the solar panel, which is measured by the power meter and stored in the battery. Thus, the objective of designing a battery system that charges using solar energy was achieved.
