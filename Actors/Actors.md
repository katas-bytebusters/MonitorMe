## Actors

#### Nurses / Clinical Staff:  
- *Role & Needs:*
  - Primary users, continuously monitoring patient vitals.
  - Need a user-friendly interface to minimize cognitive load.
  - Require functionality to acknowledge alerts and document interventions.

- *Interactions:*
  - View consolidated screens, interact with alerts, and consult historical data.


#### Medical Professionals (Doctors / Physicians):
- *Role & Needs:*
  - Periodically check on patients, relying on key notifications.
  - Need access to advanced analytics and integration with electronic health records.
- *Interactions:*
  - Review patient snapshots, vitals history, and upload snapshots to medical records.

#### Patients: 
Patients are not directly interactive with the system, we are just monitoring/analyzing vital from the existing monitoring equipments/systems.
- *Role & Needs:*
  - The source of vital signs data, with minimal direct system interaction.
  - Comfort with monitoring devices is a consideration for system design. (need to understand)
- *Interactions:*
  - Passively provide data through body sensors and devices.

#### Vital sign Monitoring Devices:
- *Role & Needs:*
  - Capture and transmit vital signs data at varied intervals.
  - Require secure data transmission and device management capabilities.
- *Interactions:*
  - Send data to Monitor, may need configuration and updates through the system.

#### Consolidated Monitoring Screen:
- *Role & Needs:*
  - Ingests, stores, and analyzes high-frequency patient data.
  - Must ensure data privacy/security and allow for scalability and modularity.
- *Interactions:*
  - Process data streams, issue alerts, and integrate with other hospital systems.

#### StayHealthy Mobile App:
- *Role & Needs:*
  - Medical professionals expected to receive alerts when patient vital go beyond defined threshold.
- *Interaction*
  - Medical Professional receive Notification/alert.

#### MyMedicalData:
- *Role & Needs:*
  - Maintains patients’ health records access by the medical professionals.
  - Needs latest captured patients’ vital data.
- *Interaction*
  - Upload patients’ vitals’ snapshot via secure HTTP API 
    

#### Notification System:
- *Role & Needs:*
  - Generate notification based on the threshold reach.
- *Interaction:*
  - On Mobile app or Consolidated Monitoring system.

### Additional Actors

#### StayHealthy Inc.:

#### IT and System Administrators:
- *Role & Needs:*
  - Manage the deployment, maintenance, and operation of MonitorMe.
  - Require monitoring and management tools for system health and user access.
- *Interactions:*
  - Perform system updates, manage configurations, and ensure system reliability.

#### Data Analysts / Biomedical Engineers
- *Role & Needs:*
  - Engage with the system for research and to refine health issue detection algorithms.
  - Feedback from these actors can inform system enhancements.
- *Interactions:*
  - Extract and analyze data, contribute to system improvement discussions.

### Hardware and Software

#### Server Infrastructure:
- *Role & Needs:*
  - Serve as the backbone of MonitorMe, hosting applications, databases, and ensuring high availability, scalability, and security of the system.

- *Interactions:*
  - Host the core software components of MonitorMe, manage data storage, processing, and provide secure access to authorized users.

#### Networking Equipment:
- *Role & Needs:*
  - Essential for maintaining robust and secure communications between the various components of the system.

- *Interactions:*
  - Facilitate the transfer of data across the system, ensuring secure and efficient communication.

#### Data Storage Solutions:
- *Role & Needs:*
  - Store vast amounts of time-sensitive and historical patient data securely and efficiently.

- *Interactions:*
  - Securely store and manage access to patient data, allowing for efficient data retrieval.

#### Monitoring and Management Tools:
- *Role & Needs:*
  - Allow IT and system administrators to oversee system performance and manage configurations.

- *Interactions:*
  - Used by IT staff to monitor system operations, perform maintenance tasks, and ensure smooth operation.

#### Application Software (MonitorMe and Associated Applications):
- *Role & Needs:*
  - The primary interface for users, facilitating the monitoring, analysis, and management of patient data.

- *Interactions:*
  - Process, display, and analyze patient data, manage user interactions.

#### End-User Devices (Computers, Tablets, Smartphones):
- *Role & Needs:*
  - Enable access to the MonitorMe system for users on the go or at the bedside.

- *Interactions:*
  - Run MonitorMe applications, allowing users to interact with the system
