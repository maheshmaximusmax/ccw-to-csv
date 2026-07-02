# CCW ↔ CSV Modbus Mapping Converter

> Convert Allen-Bradley **Connected Components Workbench (CCW)** Modbus Mapping files to **CSV** and back again — entirely in your browser.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Platform](https://img.shields.io/badge/platform-Web-success)
![Technology](https://img.shields.io/badge/JavaScript-Client--Side-orange)

## 🌐 Live Demo

**https://maheshmaximusmax.github.io/ccw-to-csv/**

---

# Overview

CCW ↔ CSV Modbus Mapping Converter is a free browser-based utility developed for Automation Engineers and PLC Programmers working with Allen-Bradley Micro800 controllers.

The tool eliminates one of the most repetitive tasks in industrial automation: manually creating and maintaining Modbus mapping tables between PLCs and SCADA systems.

Instead of manually copying hundreds of Modbus addresses into Excel or SCADA software, engineers can instantly convert between CCW mapping files (.ccwmod) and CSV files.

All processing happens locally in your browser. No files are uploaded to any server.

---

# Why this project?

During PLC development, engineers typically:

1. Create PLC Tags
2. Create Modbus Mapping
3. Export CCW Mapping
4. Manually recreate mappings in Excel
5. Import them into SCADA or other engineering software

This process is slow, repetitive, and prone to human error.

This converter automates that workflow.

---

# Features

- ✅ CCWMOD → CSV conversion
- ✅ CSV → CCWMOD conversion
- ✅ 100% Client-side processing
- ✅ Files never leave your computer
- ✅ No installation required
- ✅ Dark & Light themes
- ✅ Fast conversion
- ✅ Reusable engineering workflow

---

# Typical Use Cases

- PLC Programming
- SCADA Development
- Industrial IoT
- SQL Tag Import
- HMI Development
- Water Treatment Plants
- Manufacturing Automation
- Existing CCW Projects
- New Automation Projects

---

# Benefits

- Save engineering hours
- Reduce manual work
- Eliminate mapping mistakes
- Reuse tag lists
- Generate SCADA import files
- Standardize Modbus mapping

---

# Example CSV

```csv
Variable,Address
MOTOR_START,00001
MOTOR_STOP,00002
FLOW_RATE,40001
PRESSURE,40002
```

---

# Supported Address Types

| Address Range | Type |
|---------------|------|
|00001–09999|Coils|
|10001–19999|Discrete Inputs|
|30001–39999|Input Registers|
|40001–49999|Holding Registers|

---

# Technologies

- HTML5
- CSS3
- JavaScript
- Browser File API

---
# Screen shot
<img width="1894" height="901" alt="image" src="https://github.com/user-attachments/assets/77d4eb80-d93b-4421-bf2a-58dc8b1e9834" />
<img width="1900" height="905" alt="image" src="https://github.com/user-attachments/assets/6dc40b2a-5c1e-4162-973d-3f8aeaacaf5e" />



# Roadmap

- XLSX Export
- Duplicate Address Detection
- Address Conflict Checker
- Batch Conversion
- Additional PLC Support

---

# Author

**Mahesh Parmar**

Automation Engineer

Specializing in PLC Programming, SCADA, Industrial IoT, SQL Integration, and Industrial Automation.

---

# License

MIT License

---

⭐ If this project helps you, please Star the repository.
