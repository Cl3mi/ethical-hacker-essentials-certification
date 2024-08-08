#### What is OT?
- **Operational Technology (OT)** involves hardware and software that detect or cause changes through direct monitoring and control of physical devices, processes, and events in industries.
- **Examples:** Automated baggage handling at airports, city traffic lights, sensors in water and gas pipelines, industrial robots, HVAC systems, and medical devices.

#### Key Differences Between IoT and OT
- **IoT (Internet of Things)** focuses on consumer devices and smart home applications (e.g., smart doorbells, toasters).
- **OT** is more industrial and involves older systems that control critical infrastructure and industrial processes.

#### Essential Terminology in OT
- **Assets:** Important elements to protect, such as sensors, actuators, servers, workstations, and programmable logic controllers (PLCs). Assets can be physical (hardware) or logical (software, firmware).
- **Zones and Conduits:** Methods to segregate and isolate networks to enhance security. This segmentation prevents an attacker from accessing all areas if one segment is compromised.
- **Industrial Network vs. Business Network:** Industrial networks control physical operations (e.g., manufacturing processes), while business networks handle administrative tasks and general IT functions. These networks should be kept separate to avoid cross-contamination of security breaches.
- **Industrial Protocols:** Specialized communication protocols used in OT environments, like S7, Modbus, CDA, CIP, which are different from common IT network protocols.

#### Network Security Concepts
- **Network Perimeter and Boundary Network:** The edge of a network that separates secure from insecure zones. Security measures may include different Wi-Fi networks with varying levels of access control.
- **Critical Infrastructure:** Systems whose failure could result in severe consequences, including public health and safety risks. Examples include gas sensors and industrial control systems.

#### IT/OT Convergence
- **Industry 4.0:** The integration of OT and IT, leading to smart manufacturing and improved industrial operations through connected systems. Examples include Tesla's automated manufacturing processes.

#### Purdue Model
- **Purpose:** Describes internal connections and dependencies within ICS (Industrial Control Systems) networks.
- **Zones:**
  - **OT Systems Zone:** Includes operating systems, control systems, and physical access at the lowest level.
  - **Enterprise Zone:** Includes business logic and enterprise networks.
  - **DMZ (Demilitarized Zone):** The separation layer between OT and enterprise zones to protect both from cross-contamination if one is breached.
