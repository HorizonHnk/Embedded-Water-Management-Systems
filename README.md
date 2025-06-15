# 🌊 Solar-Powered Washing Machine System

> **Advanced Arduino & Embedded Control for Solar-Powered Washing Machine Automation**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Arduino](https://img.shields.io/badge/Platform-Arduino-blue.svg)](https://www.arduino.cc/)
[![Solar Powered](https://img.shields.io/badge/Power-Solar-green.svg)](https://en.wikipedia.org/wiki/Solar_power)
[![Build Status](https://img.shields.io/badge/Build-Passing-brightgreen.svg)]()
[![Website](https://img.shields.io/badge/Website-Live-brightgreen.svg)](https://peppy-longma-3e4c41.netlify.app/)
[![YouTube](https://img.shields.io/badge/YouTube-Channel-red.svg)](https://www.youtube.com/playlist?list=PLrZbkNpNVSww3QIStzPcdd2qOiZF5aa6b)

---

## 🔗 **Quick Links**

- 🌐 **Live Website**: [https://peppy-longma-3e4c41.netlify.app/](https://peppy-longma-3e4c41.netlify.app/)
- 📺 **YouTube Channel**: [Solar & Washing Machine Engineering](https://www.youtube.com/playlist?list=PLrZbkNpNVSww3QIStzPcdd2qOiZF5aa6b)
- 📧 **Contact**: [hhnk3693@gmail.com](mailto:hhnk3693@gmail.com)
- 💻 **GitHub**: [HorizonHnk](https://github.com/HorizonHnk)

---

## 📖 **Project Overview**

This repository contains a comprehensive **solar-powered washing machine system** that operates completely off-grid using renewable energy. The project demonstrates real-world application of microcontroller programming, solar power management, and automated appliance control in an integrated sustainable solution.

### 🌐 **Live Documentation & Demos**

- **Professional Website**: Complete project documentation, technical specifications, and visual demonstrations available at [https://peppy-longma-3e4c41.netlify.app/](https://peppy-longma-3e4c41.netlify.app/)
- **Video Tutorials**: In-depth technical explanations and build demonstrations on our [YouTube Channel](https://www.youtube.com/playlist?list=PLrZbkNpNVSww3QIStzPcdd2qOiZF5aa6b)
- **Interactive Demos**: System architecture diagrams and component explanations

### **Key Features**

- ☀️ **100% solar-powered operation** - Complete off-grid washing functionality
- 🧺 **Full washing machine automation** - Multi-phase wash, rinse, and spin cycles
- 🖥️ **Real-time LCD status display** - Monitor washing progress and solar power levels
- ⚡ **Intelligent power management** - Optimized energy usage and battery backup
- 🛡️ **Professional safety systems** - Door interlocks, emergency stops, and protection circuits
- 🔄 **Smart motor control** - Variable speed, bidirectional drum rotation
- 📊 **Arduino-based automation** - Complete embedded control system
- 🌐 **Professional website documentation** - Comprehensive technical resources
- 📺 **YouTube video tutorials and demonstrations** - Build guides and explanations

---

## 📁 **Repository Structure**

```
📦 Embedded-Water-Management-Systems/
├── 📂 solar-washing-machine/          # Complete solar-powered washing machine
│   ├── 📂 src/                        # Arduino source code
│   │   ├── 📄 main.ino               # Main control program
│   │   ├── 📄 solar_manager.cpp      # Solar power management
│   │   ├── 📄 washing_cycles.cpp     # Washing machine control
│   │   └── 📄 safety_systems.cpp     # Safety and emergency controls
│   ├── 📂 schematics/                # Circuit diagrams & wiring
│   │   ├── 📄 solar_power_circuit.pdf
│   │   ├── 📄 motor_control_circuit.pdf
│   │   └── 📄 complete_system_wiring.pdf
│   ├── 📂 docs/                      # Technical documentation
│   │   ├── 📄 BUILD_GUIDE.md         # Step-by-step build instructions
│   │   ├── 📄 COMPONENTS.md          # Parts list and specifications
│   │   └── 📄 TROUBLESHOOTING.md     # Common issues and solutions
│   └── 📄 README.md                  # Project-specific documentation
├── 📂 libraries/                     # Custom Arduino libraries
│   ├── 📂 SolarManager/              # Solar power management library
│   ├── 📂 WashingController/         # Washing cycle control library
│   └── 📂 SafetySystems/             # Safety interlock library
├── 📂 tools/                         # Development and testing tools
├── 📂 examples/                      # Code examples and tutorials
├── 📄 LICENSE                        # MIT License
├── 📄 CONTRIBUTING.md               # Contribution guidelines
└── 📄 README.md                     # This file
```

---

## 🚀 **Quick Start**

### **🌐 Explore Online First**

Before diving into the code, check out our comprehensive online resources:

1. **Visit the Website**: [https://peppy-longma-3e4c41.netlify.app/](https://peppy-longma-3e4c41.netlify.app/)
   - View detailed system architecture diagrams
   - Understand component interactions
   - See technical specifications

2. **Watch Tutorial Videos**: [YouTube Channel](https://www.youtube.com/playlist?list=PLrZbkNpNVSww3QIStzPcdd2qOiZF5aa6b)
   - Solar system build walkthroughs
   - Washing machine controller explanations
   - Component-specific tutorials

### **Prerequisites**

```bash
# Required Software
- Arduino IDE (v2.0+)
- PlatformIO (optional, recommended)
- Git

# Required Hardware
- Arduino Uno/Nano
- Solar panel (12V, 10-50W)
- L298N Motor Driver
- TIP120 Transistor
- IR Sensor Module
- LCD Display (16x2 with I2C)
```

### **Installation**

```bash
# Clone the repository
git clone https://github.com/HorizonHnk/Embedded-Water-Management-Systems.git
cd Embedded-Water-Management-Systems

# Install dependencies
# (Instructions for each project in respective README files)
```

---

## 🔧 **Solar-Powered Washing Machine System**

> **Complete off-grid laundry solution using renewable energy and intelligent automation**

### **System Components**

| Component | Function | Specs |
|-----------|----------|-------|
| 🔋 **Solar Panel** | Renewable power generation | 12V, 50-100W |
| 🔋 **Battery System** | Energy storage for cloudy days | 12V, 20-40Ah Lead-acid/LiFePO4 |
| 🧠 **Arduino Uno** | Central control system | ATmega328P, 16MHz |
| 🎛️ **Control Interface** | User operation controls | Push buttons, IR remote |
| 💡 **Status Display** | System monitoring | 16x2 I2C LCD |
| 👁️ **Safety Sensors** | Door interlock & emergency stop | IR proximity sensors |
| ⚡ **Power Management** | High-current switching | TIP120 Darlington transistors |
| 🌊 **Water System** | Inlet/outlet control | Solenoid valves, flow sensors |
| 🔄 **Motor Control** | Drum rotation system | L298N H-bridge, DC motors |
| 🧺 **Washing Mechanism** | Complete laundry cycles | Multi-phase wash/rinse/spin |

### **System Integration Overview**

```
Solar Panel ──→ Battery ──→ Arduino Controller ──→ Washing Machine Components
    │                           │
    ├─ Charge Management        ├─ Motor Control (Drum rotation)
    ├─ Power Monitoring         ├─ Water Management (Valves, pumps)
    └─ Weather Adaptation       ├─ Safety Systems (Door locks, emergency stop)
                                ├─ User Interface (Display, controls)
                                └─ Cycle Management (Wash, rinse, spin)
```

### **Key Features**

- ✅ **100% Off-Grid Operation**: Complete washing functionality using only solar power
- ✅ **Intelligent Energy Management**: Optimizes washing cycles based on available solar energy
- ✅ **Multi-Phase Washing**: Automated wash, rinse, and spin cycles with customizable settings
- ✅ **Professional Safety Systems**: Door interlocks, emergency stops, and fault protection
- ✅ **Real-Time Monitoring**: LCD display showing cycle progress and energy status
- ✅ **Weather Adaptive**: Battery backup ensures operation during cloudy periods
- ✅ **Remote Control**: IR remote operation for convenient user control

---

## 📊 **Technical Specifications**

### **Solar Power System**

| Parameter | Specification | Notes |
|-----------|---------------|-------|
| **Solar Panel Power** | 12V, 50-100W | Monocrystalline or polycrystalline |
| **Battery Capacity** | 12V, 20-40Ah | Lead-acid or LiFePO4 |
| **Charging Time** | 4-6 hours | Full battery in optimal sunlight |
| **Power Consumption** | 300mA - 15A | Varies with washing cycle phase |
| **Operating Temperature** | -10°C to +60°C | Suitable for outdoor solar installation |
| **Protection Rating** | IP54 (with enclosure) | Dust and water resistant |

### **Washing Machine Performance**

| Parameter | Specification | Notes |
|-----------|---------------|-------|
| **Load Capacity** | 5-8 kg | Standard household laundry load |
| **Water Usage** | 40-60L per cycle | Water-efficient design |
| **Cycle Time** | 45-90 minutes | Varies by selected program |
| **Wash Programs** | Normal, Delicate, Heavy | Customizable cycle settings |
| **Spin Speed** | 400-1000 RPM | Variable speed control |
| **Energy Efficiency** | 100% Solar | Zero grid electricity consumption |

### **Control System Components**

| Component | Power Rating | Function | Control Method |
|-----------|--------------|----------|----------------|
| Arduino Uno | 5V, 200mA | System control | Programming/USB |
| TIP120 Transistor | 60V, 5A | High-current switching | PWM control |
| L298N Motor Driver | 12V, 2A per channel | Motor control | H-bridge operation |
| Solenoid Valves | 12V, 1-2A | Water flow control | Relay switching |
| DC Motors | 12V, 1-8A | Drum rotation | Variable speed PWM |
| LCD Display | 5V, 100mA | Status information | I2C communication |
| IR Sensors | 5V, 20mA | Safety interlocks | Digital input |

---

## 💻 **Code Examples**

### **Arduino Main Control Loop**

```cpp
void loop() {
    // Monitor solar power and battery status
    solarVoltage = analogRead(SOLAR_VOLTAGE_PIN) * VOLTAGE_SCALE;
    batteryLevel = analogRead(BATTERY_LEVEL_PIN) * VOLTAGE_SCALE;
    
    // Check safety systems
    doorClosed = digitalRead(DOOR_SENSOR_PIN);
    emergencyStop = digitalRead(EMERGENCY_STOP_PIN);
    
    // Process user input (buttons, IR remote)
    if (irReceiver.decode(&results)) {
        processWashingCommand(results.value);
        irReceiver.resume();
    }
    
    // Manage washing cycle based on available power
    if (washingActive && doorClosed && !emergencyStop) {
        if (batteryLevel > MIN_OPERATING_VOLTAGE) {
            executeWashingCycle();
        } else {
            pauseWashingCycle();
            displayMessage("Waiting for solar charge...");
        }
    }
    
    // Update status display
    updateLCDDisplay();
    
    delay(100); // 10Hz update rate
}
```

### **Solar Power Management**

```cpp
void manageSolarPower() {
    // Monitor solar panel output
    float solarCurrent = analogRead(SOLAR_CURRENT_PIN) * CURRENT_SCALE;
    float solarPower = solarVoltage * solarCurrent;
    
    // Optimize charging based on battery state
    if (batteryLevel < MAX_CHARGE_VOLTAGE) {
        digitalWrite(CHARGE_ENABLE_PIN, HIGH);
        
        // Adjust washing cycle intensity based on available power
        if (solarPower > HIGH_POWER_THRESHOLD) {
            washingIntensity = HIGH_INTENSITY;
        } else if (solarPower > MEDIUM_POWER_THRESHOLD) {
            washingIntensity = MEDIUM_INTENSITY;
        } else {
            washingIntensity = LOW_INTENSITY;
        }
    } else {
        digitalWrite(CHARGE_ENABLE_PIN, LOW); // Prevent overcharge
    }
}
```

### **Washing Cycle Control**

```cpp
void executeWashingCycle() {
    switch (currentCyclePhase) {
        case FILL_WATER:
            digitalWrite(WATER_INLET_VALVE, HIGH);
            if (waterLevel >= TARGET_WATER_LEVEL) {
                currentCyclePhase = WASH_AGITATE;
                digitalWrite(WATER_INLET_VALVE, LOW);
            }
            break;
            
        case WASH_AGITATE:
            // Bidirectional drum rotation
            rotateDrum(WASH_SPEED, agitationDirection);
            if (millis() - phaseStartTime > WASH_DURATION) {
                currentCyclePhase = DRAIN_WATER;
            }
            // Alternate direction every 30 seconds
            if (millis() - directionChangeTime > 30000) {
                agitationDirection = !agitationDirection;
                directionChangeTime = millis();
            }
            break;
            
        case DRAIN_WATER:
            digitalWrite(DRAIN_PUMP_PIN, HIGH);
            if (waterLevel <= MIN_WATER_LEVEL) {
                currentCyclePhase = SPIN_DRY;
                digitalWrite(DRAIN_PUMP_PIN, LOW);
            }
            break;
            
        case SPIN_DRY:
            rotateDrum(SPIN_SPEED, CLOCKWISE);
            if (millis() - phaseStartTime > SPIN_DURATION) {
                currentCyclePhase = CYCLE_COMPLETE;
                stopAllMotors();
            }
            break;
    }
}
```

---

## 📋 **Installation Guide**

### **Step 1: Hardware Assembly**

1. **Mount Arduino** in weatherproof enclosure
2. **Connect solar panel** via charge controller
3. **Wire sensors** according to schematic
4. **Install pumps** and motor drivers
5. **Test all connections** before powering on

### **Step 2: Software Setup**

```bash
# Clone repository
git clone https://github.com/HorizonHnk/Embedded-Water-Management-Systems.git

# Open in Arduino IDE
arduino arduino-solar-system/src/main.ino

# Install required libraries
# - LiquidCrystal_I2C
# - IRremote
# - NewPing (if using ultrasonic)

# Upload to Arduino
```

### **Step 3: Configuration**

1. **Calibrate sensors** using provided calibration sketch
2. **Set water level thresholds** in configuration file
3. **Program IR remote codes** for your specific remote
4. **Test safety features** before deployment

---

## 🔍 **Troubleshooting**

### **Common Issues**

| Problem | Symptoms | Solution |
|---------|----------|----------|
| **No power** | System unresponsive | Check solar panel, battery voltage |
| **Pump not starting** | No water flow | Verify TIP120 wiring, check fuse |
| **Remote not working** | IR commands ignored | Check IR sensor connection, battery |
| **Erratic readings** | Sensor values jumping | Add filtering capacitors, check grounds |
| **Motor stalling** | Overheating, slow operation | Check voltage supply, reduce load |

### **Debug Mode**

```cpp
// Enable debug output
#define DEBUG_MODE 1

void debugPrint(String message) {
    #if DEBUG_MODE
    Serial.println("[DEBUG] " + message);
    #endif
}
```

---

## 🤝 **Contributing**

We welcome contributions! Please read our [Contributing Guidelines](CONTRIBUTING.md) before submitting.

### **Development Workflow**

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** changes (`git commit -m 'Add amazing feature'`)
4. **Push** to branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

### **Code Standards**

- Use **descriptive variable names**
- **Comment** complex logic
- Follow **Arduino style guidelines**
- **Test** on hardware before submitting

---

## 📄 **License**

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2025 HorizonHnk - Embedded Water Management Systems

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files...
```

---

## 🎓 **Additional Resources**

### **📚 Complete Documentation**
Visit our [professional website](https://peppy-longma-3e4c41.netlify.app/) for:
- Interactive solar washing machine system diagrams
- Detailed component specifications and selection guides
- Visual project galleries and build photos
- Professional contact information
- Solar power sizing and battery selection guides
- Washing cycle optimization techniques

### **🎬 Video Content**
Subscribe to our [YouTube Channel](https://www.youtube.com/playlist?list=PLrZbkNpNVSww3QIStzPcdd2qOiZF5aa6b) for:
- Complete solar washing machine build tutorials
- Solar power system setup and configuration
- Component selection and wiring guides
- Troubleshooting and maintenance procedures
- Performance testing and optimization tips
- Off-grid installation case studies

### **💼 Professional Services**
For source code access, technical consultation, or custom development:
- **Email**: [hhnk3693@gmail.com](mailto:hhnk3693@gmail.com)
- **Available Services**: 
  - Custom solar appliance development
  - Off-grid system design consultation
  - Educational collaboration and curriculum development
  - Commercial scaling and manufacturing guidance

### **🌱 Sustainability Impact**
This solar washing machine project demonstrates:
- **Zero electricity bills** for laundry operations
- **Reduced carbon footprint** through renewable energy use
- **Off-grid capability** for remote and developing areas
- **Energy independence** from traditional power grids
- **Scalable design** for community and commercial applications

---

## 🙏 **Acknowledgments**

- **Arduino Community** for excellent hardware platform
- **Open Source Libraries** used in this project
- **Contributors** who helped improve the code
- **Solar Power Community** for renewable energy inspiration

---

## 📞 **Support & Contact**

- 📧 **Email**: [hhnk3693@gmail.com](mailto:hhnk3693@gmail.com)
- 🐛 **Issues**: [GitHub Issues](https://github.com/HorizonHnk/Embedded-Water-Management-Systems/issues)
- 🌐 **Website**: [https://peppy-longma-3e4c41.netlify.app/](https://peppy-longma-3e4c41.netlify.app/)
- 📺 **YouTube**: [Solar & Washing Machine Engineering](https://www.youtube.com/playlist?list=PLrZbkNpNVSww3QIStzPcdd2qOiZF5aa6b)

---

## 🏆 **Project Status**

- ✅ **Solar Power System**: Production Ready and Tested
- ✅ **Washing Machine Control**: Functional and Operational  
- ✅ **Professional Website**: Live and Deployed
- ✅ **YouTube Channel**: Active with Technical Content
- ✅ **System Integration**: Complete and Working
- 📋 **Documentation**: 95% Complete
- 🧪 **Field Testing**: Ongoing Optimization
- 🔄 **Continuous Improvement**: Regular updates and enhancements

---

## 📈 **Roadmap**

### **Version 2.0 Planned Features**

- [ ] **WiFi connectivity** for remote monitoring and control
- [ ] **Mobile app** for smartphone operation and status tracking
- [ ] **Data logging** to SD card for usage analysis and optimization
- [ ] **Weather API integration** for intelligent solar charging prediction
- [ ] **Machine learning** for optimal washing cycle scheduling
- [ ] **Load sensing** for automatic detergent and water adjustment
- [ ] **Multi-language support** for international deployment

### **Content & Documentation Goals**

- [ ] **Complete Video Tutorial Series**: Step-by-step build and installation guides
- [ ] **Interactive Website Features**: Online calculators for solar sizing and battery selection
- [ ] **Technical Blog Posts**: In-depth engineering analysis and optimization guides
- [ ] **Community Contributions**: Open-source collaboration and user modifications
- [ ] **Educational Partnerships**: Integration with renewable energy and embedded systems curricula
- [ ] **Commercial Documentation**: Scaling guides for community and commercial installations

### **Long-term Technical Goals**

- [ ] **Commercial-grade PCB design** for professional manufacturing
- [ ] **IoT platform integration** with smart home systems
- [ ] **Solar tracking system** for maximum energy harvesting
- [ ] **Advanced battery management** with cell balancing and health monitoring
- [ ] **Modular design** for scalability and easy maintenance
- [ ] **Water recycling system** for greywater reuse and conservation
- [ ] **Grid-tie capability** for surplus solar energy export

### **Sustainability & Impact Goals**

- [ ] **Community deployment programs** in off-grid areas
- [ ] **Educational outreach** for sustainable technology awareness
- [ ] **Open-source hardware designs** for global manufacturing
- [ ] **Environmental impact studies** and carbon footprint analysis
- [ ] **Partnership development** with NGOs and sustainability organizations

---

**⭐ Star this repo if you find it useful!**

**🍴 Fork it to contribute!**

**🐛 Report issues to help improve the project!**

**🌐 Visit our [website](https://peppy-longma-3e4c41.netlify.app/) for complete documentation!**

**📺 Subscribe to our [YouTube channel](https://www.youtube.com/playlist?list=PLrZbkNpNVSww3QIStzPcdd2qOiZF5aa6b) for solar washing machine tutorials!**

**♻️ Help us build a more sustainable future with solar-powered appliances!**
