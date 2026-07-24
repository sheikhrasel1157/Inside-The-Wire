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

## Technologies Used

- Pure HTML, CSS, and JavaScript
- SVG for visualizations
- CSS custom properties for theming (light/dark mode support)