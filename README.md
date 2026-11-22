# CS6048: Advanced Computer Networks (IIT Madras)

Lecture slides, research papers, and course material for **CS6048: Advanced Computer Networks** at the **Indian Institute of Technology, Madras** (Fall 2026). The course explores modern transport protocol evolution, internet performance engineering, and the architectural shifts driving hyperscale networked systems—covering HTTP/3, QUIC, congestion control, adaptive video streaming, WebRTC, multipath transport, CDNs, BGP routing, and IP geolocation.

> **Course Project:** Our team's implementation of a frame-aware Multipath QUIC (MPQUIC) live video streaming engine in Rust on TQUIC is hosted at **[PrasannaBhavan2005/CS-Project](https://github.com/PrasannaBhavan2005/CS-Project)**.

---

## Course Materials & Reading List

### 1. Modern Web & QUIC Transport Protocol
| Material | Type | Description |
| :--- | :--- | :--- |
| [`HTTP_HTTP2_HTTP3.pdf`](HTTP_HTTP2_HTTP3.pdf) | Lecture Slides | Evolution from HTTP/1.1 to HTTP/2 multiplexing, QPACK, and HTTP/3 over QUIC |
| [`The QUIC Transport Protocol Design.pdf`](The%20QUIC%20Transport%20Protocol%20Design.pdf) | Paper | Core QUIC protocol design, 0-RTT handshake, stream multiplexing, and connection migration |
| [`Taking a Long Look at QUIC (2).pdf`](Taking%20a%20Long%20Look%20at%20QUIC%20(2).pdf) | Paper | Empirical Internet-wide measurement and deployment analysis of QUIC |
| [`QUIC is not Quick Enough over Fast Internet.pdf`](QUIC%20is%20not%20Quick%20Enough%20over%20Fast%20Internet.pdf) | Paper | User-space packet I/O, crypto, and CPU bottlenecks in high-throughput QUIC transfers |

### 2. Congestion Control & Adaptive Video Streaming
| Material | Type | Description |
| :--- | :--- | :--- |
| [`CubicTCP.pdf`](CubicTCP.pdf) | Lecture / Paper | Loss-based congestion control with cubic window growth for high-BDP networks |
| [`BBRCongestionControl.pdf`](BBRCongestionControl.pdf) | Lecture / Paper | Bottleneck Bandwidth and Round-trip propagation time (BBR) model-based congestion control |
| [`Video_Streaming_CDN.pdf`](Video_Streaming_CDN.pdf) | Lecture Slides | Adaptive bitrate video delivery, CDN architectures, and edge caching |
| [`DASH_Tutorial.pdf`](DASH_Tutorial.pdf) | Tutorial Slides | MPEG-DASH MPD manifest structure, chunk segmentation, and ABR client logic |
| [`DASH-Tutorial.pdf`](DASH-Tutorial.pdf) | Reference | Supplementary MPEG-DASH streaming tutorial and walkthrough |
| [`Lec05-BBA (2).pdf`](Lec05-BBA%20(2).pdf) | Lecture Slides | Buffer-Based Approach (BBA) to adaptive video bitrate selection |
| [`BBA-sigcomm14 (2).pdf`](BBA-sigcomm14%20(2).pdf) | Paper (SIGCOMM '14) | *A Buffer-Based Approach to Rate Adaptation: Evidence from a Large Video Streaming Service* |
| [`Video-streaming-over-QUIC-varied-network-b...`](Video-streaming-over-QUIC-varied-network-b...) | Paper | Performance analysis of adaptive video streaming over QUIC under dynamic network conditions |

### 3. Real-Time Media & WebRTC
| Material | Type | Description |
| :--- | :--- | :--- |
| [`WebRTC.pdf`](WebRTC.pdf) | Lecture Slides | Real-time peer-to-peer media architecture, ICE/STUN/TURN, RTP/RTCP, and jitter buffers |
| [`WebRTCRefMaterial.pdf`](WebRTCRefMaterial.pdf) | Reference | Supplementary technical reference on WebRTC congestion control and media transport |

### 4. Multipath Transport (MPTCP & MPQUIC)
| Material | Type | Description |
| :--- | :--- | :--- |
| [`Multipath-TCP.pdf`](Multipath-TCP.pdf) | Lecture / Paper | Multipath TCP architecture, subflow management, and coupled congestion control |
| [`Accelerating Multipath Transport.pdf`](Accelerating%20Multipath%20Transport.pdf) | Paper | Path scheduling and latency optimization across heterogeneous wireless links |
| [`Experimental-evaluation-of-multipath-TCP-sch...`](Experimental-evaluation-of-multipath-TCP-sch...) | Paper | Comparative evaluation of MPTCP packet schedulers (MinRTT, Round-Robin, BLEST/ECF) |
| [`Multipath_ DEMS.pdf`](Multipath_%20DEMS.pdf) | Paper | Decoupled Multipath Scheduler (DEMS) for splitting application data across asymmetric paths |
| [`MPQUIC-Xlink (1).pdf`](MPQUIC-Xlink%20(1).pdf) | Lecture Slides | Cross-layer Multipath QUIC design and QoE-driven scheduling for mobile video |
| [`xlink-paper (1).pdf`](xlink-paper%20(1).pdf) | Paper | *XLINK: QoE-Driven Multi-Path QUIC Transport in Large-scale Video Services* |
| [`Converge_ QoE-driven Multipath Video Confer...`](Converge_%20QoE-driven%20Multipath%20Video%20Confer...) | Lecture Slides | QoE-aware multipath scheduling for interactive real-time video conferencing |
| [`Converge-paper.pdf`](Converge-paper.pdf) | Paper | *Converge*: Frame- and QoE-driven multipath transport for low-latency video conferencing |

### 5. Internet Routing, CDNs & IP Geolocation
| Material | Type | Description |
| :--- | :--- | :--- |
| [`BGP-full (1).pdf`](BGP-full%20(1).pdf) | Lecture Slides | Inter-domain routing, Border Gateway Protocol (BGP) path selection, policies, and convergence |
| [`CDN_Cloud.pdf`](CDN_Cloud.pdf) | Lecture Slides | Content Delivery Networks, anycast routing, and cloud-edge infrastructure |
| [`IP-geolocation-slides-full.pdf`](IP-geolocation-slides-full.pdf) | Lecture Slides | Active and passive IP geolocation methodologies and Internet topology mapping |
| [`IP-geolocation-slides (1).pdf`](IP-geolocation-slides%20(1).pdf) | Lecture Slides | Supplementary slides on delay-based geolocation |
| [`Active-geolocation-CBG.pdf`](Active-geolocation-CBG.pdf) | Paper | Constraint-Based Geolocation (CBG) using multilateration and RTT distance constraints |
| [`Too Close for Comfort.pdf`](Too%20Close%20for%20Comfort.pdf) | Paper | Fine-grained client IP geolocation, privacy implications, and measurement limits |
