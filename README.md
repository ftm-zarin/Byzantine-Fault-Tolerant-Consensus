# Byzantine-Fault-Tolerant-Consensus
An English translation of a survey on Byzantine Fault-Tolerant consensus, focusing on PBFT, HotStuff, and HotStuff-2.
### From PBFT to HotStuff-2

This repository contains an English translation of selected chapters from a comprehensive technical survey on Byzantine Fault-Tolerant (BFT) consensus algorithms. 

Originally written in Persian, this manuscript explores the evolution of consensus protocols in distributed systems. The translated document specifically focuses on the lineage of algorithms that transitioned BFT from theoretical complexity to practical linear responsiveness.

## 📄 Content of the Translation

The provided PDF focuses on three pivotal algorithms that represent the evolution of BFT state machine replication in the partially synchronous model:

1.  **PBFT (Practical Byzantine Fault Tolerance):** The foundational algorithm that proved BFT could be practical, despite its $O(n^2)$ communication complexity.
2.  **HotStuff:** A breakthrough protocol that introduced linearity ($O(n)$) and Optimistic Responsiveness using a three-phase pipeline.
3.  **HotStuff-2:** The state-of-the-art refinement that achieves the theoretical minimum of two phases while maintaining linearity and responsiveness.

## 📚 Context: The Original Comprehensive Survey

Please note that this translation represents only a **subset** of the original comprehensive survey. The full Persian manuscript provides a broader taxonomy of the BFT landscape, covering the following categories and algorithms which are **not** included in this specific translation:

* **Speculative & Low-Latency Protocols:** Zyzzyva (Speculative BFT).
* **Robustness-Oriented Protocols:** Aardvark (censorship resistance), RBFT (Redundant BFT), and Mir-BFT (Multi-leader throughput).
* **Blockchain-Era Consensus:** Tendermint (Instant finality) and Algorand (Cryptographic sortition/VRFs).
* **Scalability Optimizations:** SBFT (Threshold signatures) and Q/U (Quorum-based).
* **Asynchronous BFT:** HoneyBadgerBFT (Randomized consensus without timing assumptions).
* **Hardware-Assisted BFT:** MinBFT (Using Trusted Execution Environments/USIG).

## 🎯 Purpose

The purpose of this partial translation is to highlight the specific architectural shift from the classic two-phase quadratic approach of PBFT to the modern linear pipelines of the HotStuff family. This lineage is particularly relevant for researchers studying the optimization of view-change mechanisms and communication complexity in modern blockchains.

## 📥 Usage

You can view or download the translated survey here:
* [**Download PDF**](./Byzantine.pdf) 

## ✍️ Author

* **Fatemeh Zarinjouei** - *Translation & Original Survey Author*
* Master's Student, Sharif University of Technology

---
*Disclaimer: This translation is intended for academic and educational purposes. Citations and references within the PDF adhere to the standard distributed systems literature.*
