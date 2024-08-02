# Secure Blockchain Framework for Patient-Centered Healthcare IoT

## Overview

This project presents a secure framework for patient-centered healthcare using blockchain technology integrated with the Internet of Medical Things (IoMT). The framework aims to address the security and privacy challenges in modern healthcare data management by leveraging the decentralized and immutable nature of blockchain technology.

## Introduction

In the current landscape of healthcare, maintaining data security and privacy is increasingly challenging due to the rapid expansion of data collection and processing. IoMT devices are widely used for continuous health monitoring and diagnosis, which involves collecting, processing, and storing patient data on cloud servers. However, public channels used for data transmission are vulnerable to various attacks, and centralized storage systems are prone to single-point failures.

## Key Features

### 1. **Blockchain Integration**
   - The framework utilizes blockchain technology to store patient data securely and ensure decentralization, thus preventing single-point failures.
   - Blockchain ensures data integrity and privacy by storing data in an immutable, distributed ledger without including personally identifiable information (PII).

### 2. **IoMT and Body Area Networks (BAN)**
   - IoMT devices monitor various health parameters such as heart rate, blood pressure, and ECG, transmitting data to remote healthcare providers.
   - Data is collected and processed in real-time, allowing for continuous monitoring and quick response to health anomalies.

### 3. **Security Protocols**
   - Multiple layers of security are implemented to protect data during transmission and storage, including cryptographic signatures and hash functions.
   - The framework is designed to resist various attacks such as Sybil, man-in-the-middle, and DDoS attacks.

### 4. **Miner Selection Algorithm**
   - A novel miner selection algorithm is introduced to prevent bias in the blockchain.
   - Miners (doctors) validate the data before it is recorded on the blockchain, ensuring accuracy and reliability.

### 5. **Compliance with GDPR**
   - The framework complies with the General Data Protection Regulation (GDPR), ensuring that patient data is handled securely and ethically.

## System Architecture

The proposed system is composed of four layers:

1. **Physical Layer**: Comprises IoMT devices attached to the patient's body, responsible for data collection.
2. **Network Layer**: Ensures secure transmission of data from the patient's personal device to the cloud server.
3. **Blockchain Layer**: Manages the recording of transactions on the blockchain, including mining and validation.
4. **User Interface Layer**: Provides web and application interfaces for users to interact with the blockchain network.

## Implementation

- The blockchain is implemented using Python, with IoT simulations carried out using Bevywise IoT simulator and MQTT simulator.
- Security protocols are analyzed using Scyther, a tool for automatic verification of security protocols.

## Goals

The main goals of this project are:
1. Develop a patient-centric IoMT-based blockchain system.
2. Assess and address the security requirements of the system.
3. Propose and implement a miner selection algorithm.
4. Simulate the IoT infrastructure and perform security analysis using Scyther.

## Article Organization

1. **Literature Review**: Discusses existing research and identifies gaps in current healthcare blockchain systems.
2. **Proposed System and Algorithms**: Details the architecture and algorithms used in the framework.
3. **Implementation**: Describes the practical implementation of the system.
4. **Results and Security Analysis**: Presents the outcomes and security evaluations of the implemented system.
5. **Comparison with Previous Systems**: Compares the proposed framework with existing solutions.
6. **Conclusion and Future Scope**: Summarizes the findings and discusses potential future enhancements.

## Conclusion

This framework presents a significant advancement in secure and patient-centric healthcare data management. By integrating blockchain technology with IoMT, the proposed system ensures robust security, privacy, and compliance with regulatory standards, paving the way for more reliable and efficient healthcare solutions.

---

Feel free to explore the repository for more details on the implementation and to contribute to the project. For any questions or issues, please open an issue or contact the project maintainers.

---

## References

- Hasan, R., & Salah, K. (Year). [Title of the referenced paper]
- Shu, Y., et al. (Year). [Title of the referenced paper]
- Cai, C., et al. (Year). [Title of the referenced paper]
- Tang, T., et al. (Year). [Title of the referenced paper]

---

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## Acknowledgments

Special thanks to the contributors and the academic community for their valuable insights and research that have guided this project.

---

*Note: This README is based on the article "Secure Blockchain Framework for Patient-Centered Healthcare IoT" by Maryam Yeaganeh.
Goggle drives' link is : https://drive.google.com/drive/folders/1J6XyLZ1nAMBDpZ9gbNgcl3_EopeKaorJ?usp=drive_link *
