# 🌐 Inside the Wire – OSI & TCP/IP Network Simulator

<p align="center">
  <strong>An interactive packet-level network simulator for learning Computer Networks through visualization, simulation, and virtual laboratory experiments.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="MIT License">
</p>

---

## 📖 Overview

**Inside the Wire** is a browser-based educational network simulator designed to help students, educators, and networking enthusiasts understand how data travels through the **OSI** and **TCP/IP** protocol stacks.

Unlike traditional network simulators that focus only on device configuration, this project provides **packet-level visualization**, allowing users to observe how packets are encapsulated, transmitted, processed, and delivered across different layers of the network.

The simulator also includes interactive laboratory modules covering important Data Communication and Computer Networking concepts such as **line encoding, framing, CRC error detection, and Hamming code error correction**.

---

## ✨ Key Features

### 🚀 Interactive Network Simulation

* Visualize packet flow through all **OSI** and **TCP/IP** layers
* Real-time packet animation
* Step-by-step protocol execution
* Layer-wise packet encapsulation and decapsulation
* Packet inspection with protocol headers
* Adjustable simulation speed
* Pause, resume, and step controls

---

### 🖥️ Demo Simulation

Run a complete network communication on a predefined network.

Features include:

* Custom message input
* Protocol selection
* Encoding selection
* Configurable network parameters
* Live packet animation
* Detailed packet inspection

---

### 🌐 Topology Builder

Design and simulate your own computer network.

Features:

* Drag-and-drop device placement
* Routers, switches, hubs, servers, and PCs
* Interactive cable connections
* Sender/Receiver selection
* Packet routing visualization
* Device status monitoring
* Canvas navigation with minimap
* Zoom and pan support

---

### 📡 Line Encoding Laboratory

Explore digital signal encoding techniques through animated waveforms.

Supported encoding methods:

* NRZ-L
* NRZ-I
* Manchester
* Differential Manchester
* AMI
* Pseudoternary
* RZ
* B8ZS
* HDB3
* Polar
* Unipolar
* Bipolar

Features:

* Interactive waveform generation
* Signal comparison
* Binary-to-signal visualization
* Theory and explanations
* Encoding characteristics

---

### 📦 Framing Laboratory

Understand how data framing works at the Data Link Layer.

Includes:

* Byte Stuffing
* Bit Stuffing
* Frame creation
* Frame parsing
* De-stuffing process
* Step-by-step visualization

---

### 🛡️ CRC Error Detection Laboratory

Learn Cyclic Redundancy Check through interactive simulation.

Features:

* Binary polynomial division
* Generator polynomial selection
* Automatic CRC generation
* Error injection
* Receiver-side validation
* Remainder calculation
* Complete division visualization

---

### 🔧 Hamming Code Laboratory

Interactive implementation of **Hamming (7,4)** error correction.

Features:

* Automatic parity generation
* Syndrome calculation
* Single-bit error detection
* Error correction
* Binary visualization
* Step-by-step execution

---

### 📊 Performance Dashboard

Monitor simulation performance in real time.

Metrics include:

* Packets Sent
* Packets Delivered
* Packet Loss
* Retransmissions
* Delivery Success Rate
* Average Transmission Time
* Simulation History
* Protocol Statistics

---

### 📄 Lab Report Generator

Generate professional lab reports directly from simulations.

Reports include:

* Simulation parameters
* Results
* Performance statistics
* Screenshots (optional)
* Student observations
* Conclusions
* Printable format

---

### 🎨 Modern User Interface

* Responsive design
* Dark & Light themes
* Smooth animations
* Glassmorphism-inspired components
* Interactive dashboards
* Clean educational interface

---

## 📁 Project Structure

```text
network-simulator/
│
├── index.html
│
├── src/
│   ├── assets/
│   │
│   ├── css/
│   │   └── styles.css
│   │
│   └── js/
│       ├── app.js
│       ├── config.js
│       ├── crc.js
│       ├── dashboard.js
│       ├── encoding.js
│       ├── framing.js
│       ├── hamming.js
│       ├── main.js
│       ├── minimap.js
│       ├── reports.js
│       ├── simulation.js
│       ├── topology.js
│       └── utils.js
│
├── README.md
├── LICENSE
└── .gitignore
```

---

## 🛠️ Built With

| Technology       | Purpose                          |
| ---------------- | -------------------------------- |
| HTML5            | Application Structure            |
| CSS3             | Styling & Responsive Design      |
| JavaScript (ES6) | Application Logic                |
| SVG              | Packet Animation & Visualization |

---

## 🚀 Getting Started

### Prerequisites

* Modern web browser

  * Google Chrome
  * Mozilla Firefox
  * Microsoft Edge
  * Safari

No installation, build tools, or backend server is required.

---

## 📥 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/network-simulator.git
```

Navigate to the project folder:

```bash
cd network-simulator
```

Open the project:

### Windows

```bash
start index.html
```

### macOS

```bash
open index.html
```

### Linux

```bash
xdg-open index.html
```

The application runs entirely in the browser.

---

# 📚 User Guide

## 1. Demo Simulation

1. Enter a message.
2. Select desired protocols.
3. Configure network settings.
4. Click **Send**.
5. Observe packet movement through each protocol layer.
6. Click the packet to inspect headers and payload.

---

## 2. Topology Builder

1. Drag devices onto the workspace.
2. Connect devices using cable mode.
3. Select Sender and Receiver.
4. Start the simulation.
5. Watch packets travel across your custom network.

---

## 3. Line Encoding Lab

* Select an encoding technique.
* Enter binary data.
* Generate signal waveforms.
* Compare encoding methods.

---

## 4. Framing Lab

* Input binary data.
* Apply Byte Stuffing or Bit Stuffing.
* Observe frame construction and extraction.

---

## 5. CRC Lab

* Enter binary message.
* Choose generator polynomial.
* Generate CRC.
* Inject transmission errors.
* Verify receiver detection.

---

## 6. Hamming Code Lab

* Enter 4-bit data.
* Generate Hamming code.
* Simulate bit errors.
* Detect and correct errors.

---

## 📈 Performance Analytics

The dashboard continuously records:

* Total Packets
* Delivered Packets
* Dropped Packets
* Retransmissions
* Delivery Percentage
* Network Performance
* Simulation Logs

---

## 🎯 Educational Objectives

This simulator helps learners understand:

* OSI Model
* TCP/IP Model
* Packet Encapsulation
* Packet Decapsulation
* Network Routing
* Data Link Layer
* Physical Layer Encoding
* Error Detection
* Error Correction
* Network Performance Analysis

Suitable for:

* Computer Networking Laboratory
* Data Communication Laboratory
* Computer Science Students
* Information Technology Students
* Networking Enthusiasts
* Classroom Demonstrations

---

## 🤝 Contributing

Contributions are welcome.

To contribute:

```bash
Fork the repository
```

```bash
Create a feature branch
git checkout -b feature/NewFeature
```

```bash
Commit your changes
git commit -m "Add New Feature"
```

```bash
Push to GitHub
git push origin feature/NewFeature
```

Finally, open a Pull Request.

---

## 📄 License

This project is licensed under the **MIT License**.

See the **LICENSE** file for complete details.

---

## 🙏 Acknowledgements

Special thanks to:

* Computer Networking textbooks
* Data Communication laboratory courses
* Networking educators and instructors
* The open-source community

---

## 👨‍💻 Author

**Your Name**

GitHub: https://github.com/yourusername

Email: [email@example.com](mailto:email@example.com)

Project Repository:

https://github.com/yourusername/network-simulator

---

## ⭐ Support the Project

If you found this project helpful for learning Computer Networks, please consider giving it a ⭐ on GitHub.

Your support helps improve the project and encourages future development.

# Inside the Wire — OSI & TCP/IP Network Simulator

A packet-level network simulator that visualizes data flowing through the OSI and TCP/IP protocol stacks, with interactive labs for line encoding, framing, error detection, and error correction.

## Project Structure
network-simulator/
├── index.html # Main HTML file
├── src/
│ ├── css/
│ │ └── styles.css # All CSS styles
│ ├── js/
│ │ ├── config.js # Configuration constants     (layers, device icons, etc.)
│ │ ├── utils.js # Utility functions
│ │ ├── encoding.js # Line encoding lab (waveforms, theory)
│ │ ├── framing.js # Byte/bit stuffing lab
│ │ ├── crc.js # CRC error detection lab
│ │ ├── hamming.js # Hamming(7,4) error correction lab
│ │ ├── simulation.js # Core simulation engine (step builder)
│ │ ├── topology.js # Topology builder (canvas, drag-drop, templates)
│ │ ├── dashboard.js # Performance dashboard
│ │ ├── reports.js # Lab report generator
│ │ ├── app.js # Simulation controllers (demo & builder)
│ │ └── main.js # Main application wiring
│ └── assets/ # (empty) for future images/fonts
└── README.md

text

## Features

- **Demo Simulation**: Watch a message travel through OSI/TCP-IP layers on a fixed reference network
- **Topology Builder**: Drag devices onto a canvas, wire them up, and simulate across your own network design
- **Line Encoding Lab**: 12 encoding schemes with waveforms and theory
- **Framing Lab**: Byte stuffing and bit stuffing with de-stuffing
- **Error Detection**: CRC generator-polynomial division with error injection
- **Error Correction**: Hamming(7,4) code with syndrome detection and correction
- **Performance Dashboard**: Live counters across all simulations
- **Lab Reports**: Generate printable lab reports

## Running the Application

Simply open `index.html` in a modern web browser. No build step or server required.

## Live Link of of the Project
You can visit the live application here: [Inside the Wire](https://inside-the-wire.netlify.app/)

## Technologies Used

- Pure HTML, CSS, and JavaScript
- SVG for visualizations
- CSS custom properties for theming (light/dark mode support)
