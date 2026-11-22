# CS6048: Advanced Computer Networks (IIT Madras)

Course notes, paper discussions, and lecture material for **CS6048: Advanced Computer Networks** at the **Indian Institute of Technology, Madras** (Fall 2026)[cite: 1]. The course explores modern transport protocol evolution, internet performance engineering, and the architectural shifts driving hyperscale networked systems—covering the transition from legacy TCP/HTTP to QUIC, HTTP/3, and WebRTC, alongside congestion control, multipath transport dynamics, and host-networking bottlenecks[cite: 1].

> **Course Project:** Our team's implementation of a frame-aware Multipath QUIC (MPQUIC) live video streaming engine in Rust on TQUIC is hosted at **[PrasannaBhavan2005/CS-Project](https://github.com/PrasannaBhavan2005/CS-Project)**.

---

## Topics Covered
* **Transport Protocol Evolution:** Limitations of TCP/HTTP2 (head-of-line blocking, ossification), QUIC architecture, 0-RTT connection establishment, stream multiplexing, and HTTP/3[cite: 1].
* **Congestion Control & Active Queue Management:** Loss-based vs. delay-based vs. model-based congestion control (CUBIC, BBR), bufferbloat, and packet pacing[cite: 1].
* **Multipath Transport:** Multipath TCP (MPTCP) and Multipath QUIC (MPQUIC) path management, asymmetric link scheduling (MinRTT, ECF, Round-Robin), and application-aware framing[cite: 1].
* **Real-Time Media & Low-Latency Streaming:** WebRTC, RTP/RTCP, jitter buffers, deadline-aware playout, and interactive video delivery[cite: 1].
* **Data Center & Systems-Level Networking:** Kernel-bypass, NIC offloading bottlenecks, RDMA, and hyperscale transport design[cite: 1].

---

## Repository Contents

### Lecture Notes (`Class2.txt` – `Class9.txt`, `sigcomm.txt`)
* [`Class2.txt`](Class2.txt) – [`Class9.txt`](Class9.txt): Running class notes covering protocol design, congestion control, multipath scheduling, and systems papers[cite: 1].
* [`sigcomm.txt`](sigcomm.txt): Notes and takeaways from SIGCOMM research paper discussions[cite: 1].

### Lecture Slides & PDFs
*(Update the links below with your uploaded PDF filenames)*
| Document | Description |
| :--- | :--- |
| [`Lecture_Slides.pdf`](Lecture_Slides.pdf) | Course presentation decks and protocol diagrams |
| [`Reading_Material.pdf`](Reading_Material.pdf) | Reference papers and supplementary handouts |
