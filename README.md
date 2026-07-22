# 5G Architecture and Telecom Fundamentals

## Objectives

- Understand the architecture of 5G networks.
- Learn about Radio Access Technologies used in 5G.
- Study the 5G Core Network and its components.
- Perform KPI analysis using Python.
- Analyze network packets using Wireshark.
- Study end-to-end packet flow in telecom networks.
- Analyze real-world telecom network scenarios.

## Project Structure

```
5g-architecture-telecom-fundamentals/
│
├── README.md
├── reports/
│   ├── Task1_5G_Architecture.pdf
│   ├── Task2_Radio_Technologies.pdf
│   ├── Task3_Core_Network.pdf
│   ├── Task4_KPI_Analysis.pdf
│   ├── Task5_KPI_Thresholds.pdf
│   ├── Task6_Packet_Analysis.pdf
│   ├── Task7_Packet_Flow.pdf
│   ├── Task8_End_to_End_Data_Session.pdf
│   └── Task9_Case_Study.pdf
│
├── presentation/
│   └── 5G_Technical_Presentation.pptx
│
├── notebook/
│   └── KPI_Analysis.ipynb
│
├── data/
│   └── telecom_kpi_balanced.csv
│
└── screenshots/
    ├── arp.png
    ├── icmp.png
    ├── tcp.png
    ├── udp and dns.png
    ├── http.png
    └── https.png
```

# Tasks Completed

## Task 1 – 5G Architecture

Studied the complete 5G architecture including:

- User Equipment (UE)
- gNB
- AMF
- SMF
- UPF
- N1, N2, N3, N4 and N6 interfaces

Topics covered:

- Registration Procedure
- PDU Session Establishment
- User Plane Communication

## Task 2 – Radio Technologies

Studied:

- OFDM
- Beamforming
- Massive MIMO

Key concepts:

- High spectral efficiency
- Improved signal quality
- Enhanced coverage
- Increased network capacity

## Task 3 – Core Network Technologies

Covered:

### Network Slicing

- eMBB
- URLLC
- mMTC

### O-RAN

- O-RU
- O-DU
- O-CU
- RIC

Benefits:

- Open interfaces
- Vendor interoperability
- AI-driven optimization

## Task 4 – KPI Analysis

Performed telecom KPI analysis using Python.

KPIs analyzed:

- RSRP
- SINR
- Throughput
- Latency
- Packet Loss
- Connected Users

Operations performed:

- Data loading
- Data cleaning
- Statistical analysis
- Visualization
- Peak traffic identification
- Worst cell detection

Libraries used:

- Pandas
- NumPy
- Matplotlib

## Task 5 – KPI Threshold Analysis

Studied KPI performance thresholds.

| KPI | Good | Warning | Critical |
|------|------|----------|-----------|
| RSRP | > -90 dBm | -90 to -105 dBm | < -105 dBm |
| SINR | >20 dB | 10–20 dB | <10 dB |
| Throughput | >100 Mbps | 50–100 Mbps | <50 Mbps |
| Latency | <20 ms | 20–50 ms | >50 ms |
| Packet Loss | <1% | 1–3% | >3% |

## Task 6 – Packet Analysis

Captured and analyzed packets using Wireshark.

Protocols studied:

- ARP
- ICMP
- TCP
- UDP
- DNS
- HTTP
- TLS/HTTPS

Learned:

- Packet headers
- Source/Destination IP
- Protocol fields
- Network troubleshooting

## Task 7 – Packet Flow Analysis

Studied:

- TCP Three-Way Handshake
- DNS Resolution
- HTTP Request-Response
- Packet exchange sequence

## Task 8 – End-to-End Data Session Flow

Analyzed complete 5G communication flow:

UE

↓

gNB

↓

AMF

↓

SMF

↓

UPF

↓

Internet

Topics covered:

- Registration
- Authentication
- PDU Session
- User Data Flow

## Task 9 – Telecom Case Study

Analyzed a degraded network scenario using KPI values.

Observed:

- Weak RSRP
- Low SINR
- High Latency
- High Packet Loss
- Low Throughput

Suggested improvements:

- Beamforming optimization
- Massive MIMO deployment
- Capacity enhancement
- Backhaul optimization
- Continuous KPI monitoring

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Wireshark
- PowerPoint
- Git
- GitHub

## Learning Outcomes

- Understood 5G network architecture.
- Learned radio access technologies.
- Explored core network functions.
- Performed telecom KPI analysis.
- Captured and analyzed network packets.
- Understood TCP/IP communication.
- Gained practical exposure to Wireshark.
- Improved telecom troubleshooting skills.

## Author

**Vibhuti Chaddha**

