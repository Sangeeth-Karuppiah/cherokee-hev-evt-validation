# Jeep Cherokee HEV – EVT Validation Toolkit

> Engineering Validation Test (EVT) planning and execution framework for the 2026 Jeep Cherokee Hybrid Electric Vehicle program. This repository contains anonymized templates, tools, and methodologies developed during a global OEM hybrid SUV program.

---

## 📋 Program Overview

**Vehicle:** 2026 Jeep Cherokee HEV (Hybrid Electric Vehicle)  
**Powertrain:** 1.6L turbocharged inline-4 + dual electric motors  
**System Output:** ~210 hp / 230 lb-ft combined  
**Fuel Economy:** ~37 MPG combined  
**Range:** 500+ miles / 800+ km  
**Significance:** First hybrid system in Jeep's North American lineup, part of Stellantis' multi-energy strategy

---

## 🎯 Validation Objectives

The EVT phase focused on validating:

- **Emissions & Fuel Economy:** Meeting EPA/CARB standards across representative drive cycles
- **Durability:** High-mileage endurance testing for hybrid powertrain components
- **NVH (Noise, Vibration, Harshness):** Seamless transitions between engine and electric operation
- **Drivability:** Customer-acceptable power delivery, responsiveness, and mode transitions
- **Thermal Management:** Battery, inverter, and engine cooling across extreme ambient conditions
- **Safety & Functional Safety:** ASIL-compliant behavior for hybrid control systems

---

## 👨‍🔧 My Role

**Position:** EVT Lead Engineer, Hybrid Powertrain Validation  
**Responsibilities:**
- Led EVT planning and sequencing across dyno, vehicle, and environmental test campaigns
- Coordinated cross-functional DFMEA (Design Failure Mode & Effects Analysis) for hybrid subsystems
- Developed and managed DVP&R (Design Verification Plan & Report) covering 200+ test cases
- Optimized dyno test matrix to reduce campaign duration by 9 weeks and save $150k+ in facility costs
- Managed risk reviews with suppliers, integration teams, and program management
- Tracked issues through 8D problem-solving and validated fixes in accelerated test cycles

**Key Achievement:**  
> Implemented a risk-driven test sequencing approach that identified critical failures 6 weeks earlier than baseline plan, enabling supplier corrective action before production tooling freeze.

---

## 📂 Repository Contents

This toolkit contains anonymized and generalized artifacts inspired by the Cherokee HEV program:

### `01_requirements/`
- **system_requirements_example.md** – High-level hybrid system requirements (anonymized)
- **validation_objectives.md** – EVT test objectives mapped to program milestones

### `02_test_plan/`
- **evt_validation_plan_template.xlsx** – Master test plan structure
- **dyno_test_matrix_example.xlsx** – Dyno test sequencing with cycle definitions
- **drive_cycle_definition.md** – Description of EPA, WLTP, and custom cycles used

### `03_dfmea/`
- **dfmea_structure_example.xlsx** – DFMEA template (AIAG/VDA-compliant structure, no proprietary data)
- **risk_prioritization_guide.md** – Approach to RPN calculation and mitigation tracking

### `04_tools/`
- **dyno_cycle_optimizer.ipynb** – Python notebook for optimizing test sequence to minimize dyno downtime
- **test_coverage_checker.py** – Script to validate DVP&R coverage against requirements
- **synthetic_data_generator.py** – Generate dummy test data for demonstration purposes

### `05_reporting/`
- **weekly_status_template.md** – Weekly EVT status report structure
- **risk_register_template.xlsx** – Active issue tracking and escalation matrix

---

## 🔧 Tech Stack & Tools

- **Test Management:** JIRA, Excel-based DVP&R tracking
- **Data Analysis:** Python (pandas, matplotlib), MATLAB
- **DFMEA:** Helix QMS (anonymized templates provided here)
- **Dyno Control:** Industry-standard dyno control software (not included due to licensing)
- **Reporting:** Markdown, Jupyter Notebooks

---

## 📊 Results & Impact

**Test Efficiency:**  
- Reduced dyno test campaign duration by **9 weeks** through optimized sequencing
- Saved **$150k+** in dyno facility costs and extended booking fees

**Quality & Risk Management:**  
- Identified 12 critical issues during EVT, 8 resolved before PVT (Production Validation Test)
- Zero major supplier-related delays to program timeline
- Achieved 98% DVP&R completion rate at EVT exit gate

**Cross-Functional Coordination:**  
- Coordinated testing across 4 global sites (USA, Mexico, Europe, Asia)
- Managed supplier collaboration with 15+ Tier 1 and Tier 2 partners

---

## 🚀 How to Use This Repo

1. **For Students/Early-Career Engineers:**  
   Study the DFMEA structure and DVP&R template to understand how validation is planned for complex systems.

2. **For Validation Engineers:**  
   Adapt the dyno optimization tool and test coverage checker to your programs. Modify the synthetic data generator to match your test parameters.

3. **For Program Managers:**  
   Use the weekly status and risk register templates as a starting point for EVT governance.

4. **For Researchers:**  
   The drive cycle definitions and test objectives provide context for hybrid vehicle development best practices.

---

## 🔗 Related Links

- **Portfolio Site:** [sangeeth-karuppiah.github.io](https://sangeeth-karuppiah.github.io/) – See full program details and impact under "Stellantis / Jeep Cherokee HEV"
- **LinkedIn:** [linkedin.com/in/sangeeth-karuppiah](https://linkedin.com/in/sangeeth-karuppiah)
- **Public References:**  
  - [2026 Jeep Cherokee Official Announcement](https://www.stellantis.com/) (update with actual link if available)
  - EPA Hybrid Vehicle Testing Guidelines

---

## ⚠️ Disclaimer

**Confidentiality Notice:**  
All data, templates, and examples in this repository are anonymized, generalized, or synthetically generated. No proprietary Stellantis information, test data, or design details are disclosed. This toolkit is intended as an educational resource and case study showcase.

**Usage Restrictions:**  
- Part numbers, calibration data, and exact test results are replaced with placeholders or removed entirely
- DFMEA content follows public AIAG/VDA standards, not internal OEM formats
- Dyno test optimization uses synthetic cycle data, not actual Cherokee HEV test logs

---

## 📜 License

This repository is shared under the MIT License for educational and portfolio purposes. See `LICENSE` file for details.

---

## 🤝 Contributing

This is a portfolio/showcase repository and is not actively seeking contributions. However, if you have suggestions for improving the templates or tools, feel free to open an issue.

---

## 📧 Contact

**Sangeeth Karuppiah**  
Mechanical Engineer | Product Launch Specialist | EV Systems Expert  
📧 Email: [your-email]  
💼 LinkedIn: [linkedin.com/in/sangeeth-karuppiah](https://linkedin.com/in/sangeeth-karuppiah)  
🌐 Portfolio: [sangeeth-karuppiah.github.io](https://sangeeth-karuppiah.github.io/)

---

*Last Updated: December 2025*
