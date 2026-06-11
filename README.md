# HydroAlert-SL
HydroAlert SL is a Digital Public Good (DPG) designed to improve rural water infrastructure management in Sierra Leone. It leverages IoT sensors and automated alerts to detect mechanical failures in hand‑pumps, ensuring timely repairs and continuous access to clean water.
Unlike traditional mobile or SMS‑based systems, HydroAlert SL requires no user interaction, making it inclusive for low‑literacy communities.

# Problem Statement
Rural Sierra Leone relies heavily on hand‑pumps for clean drinking water.

Pumps frequently break down due to rust, overuse, and poor maintenance.

Reporting failures is slow and inefficient, often taking weeks before authorities respond.

Villagers are forced to use unsafe water sources, leading to diseases like cholera and typhoid.

HydroAlert SL solves this by automating fault detection and reporting, bridging the literacy and accessibility gap.

# System Features
IoT Flow Sensors  
Monitor water output and vibration patterns.

Automated Alert System  
Uses GSM technology to send alerts if no water flow is detected for 24 hours.

Technician Dashboard  
Web‑based interface showing pump status:

Green = Functional

Red = Faulty

# Workflow

Sensor monitors water flow.

If inactive for 24 hours → fault assumed.

Alert sent via mobile network.

Central system logs issue and generates repair ticket.

Nearest technician assigned with GPS details.

Technician repairs and closes ticket.

# Target Users
Primary beneficiaries: Rural villagers relying on hand‑pumps.

Direct users:

Government maintenance technicians

Supervisors at the Ministry of Water Resources

# SDG Alignment
HydroAlert SL supports:

SDG 6: Clean Water and Sanitation

Ensures consistent availability of clean water.

Strengthens community participation in water management.

Indirectly supports:

SDG 3: Good Health and Well‑being

Reduces waterborne diseases by minimizing reliance on unsafe sources.

# Expected Benefits
Faster detection of pump failures.

Reduced downtime of rural water infrastructure.

Improved public health outcomes.

Increased efficiency in government maintenance operations.

Inclusion of low‑literacy communities in digital solutions.

# Project Structure
Code
HydroAlertSL/
│── sensors/          # IoT sensor code & configuration
│── alerts/           # GSM alert system scripts
│── dashboard/        # Web-based technician dashboard
│── docs/             # Documentation (reports, diagrams, references)
│── README.md         # Project overview
# References
Limkokwing University of Creative Technology (2026), PROG 102 Assignment Brief

United Nations (2026), Sustainable Development Goal 6: Clean Water and Sanitation

World Health Organization (2026), Rural Water Infrastructure Challenges in West Africa

# App Screens (HydroAlert SL)
HydroAlert SL includes a mobile interface for supervisors and technicians to monitor and manage rural water pumps. Below are the key frames:

Splash/Login  
Entry point with branding, login via email/password or OTP.

Dashboard  
Overview of pump statistics (functional, faulty, under repair) and recent alerts.

Pump Map  
Interactive map of Sierra Leone showing pump locations and statuses.

Pump Details  
Detailed view of a specific pump: ID, location, status, sensor battery, and activity graph.

Alerts  
List of issues detected (e.g., no water flow, motor failure), categorized by status.

Assign Technician  
Supervisors assign technicians to faulty pumps, set priority, and track ETA.

Work Order  
Displays repair ticket details, technician assignment, and progress updates.

Technician List  
Directory of available technicians with quick assignment options.

Technician Profile  
Shows technician details (contact, zone, vehicle, availability).

Supervisor Profile  
Account settings, notifications, password management, and app info.
