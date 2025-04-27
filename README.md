 Secure Access: Next-Generation Authentication on iOS

![GitHub Repo Stars](https://img.shields.io/github/stars/Mounikanarra2706/SecureAccess-iOS?style=social)
![GitHub Forks](https://img.shields.io/github/forks/Mounikanarra2706/SecureAccess-iOS?style=social)
![GitHub License](https://img.shields.io/github/license/Mounikanarra2706/SecureAccess-iOS)
![Made With Swift](https://img.shields.io/badge/Made%20with-Swift-orange.svg)
![Privacy Focused](https://img.shields.io/badge/Privacy-Focused-brightgreen)

Project Overview

In today's digital-first world, mobile devices are hubs for sensitive data. Traditional single-mode authentication — passwords, Touch ID, or Face ID — are prone to vulnerabilities.  
Secure Access introduces a dual biometric authentication system that integrates both **Touch ID** (fingerprint) and Face ID (facial recognition) for robust iOS security.

By requiring two independent biometric verifications, the system enhances mobile device security while maintaining user convenience and privacy compliance.

Objectives
Strengthen Security**: Eliminate single-point failures by combining Touch ID and Face ID.
Enhance User Convenience**: Allow flexible, fast, and seamless authentication.
Ensure Privacy**: Biometric data stored locally and encrypted inside the Secure Enclave.
Future-Proof the System**: Modular architecture ready for additional biometrics (iris, voice).

System Architecture
Biometric Input Interfaces**:
Touch ID API: Captures and encrypts fingerprint data.
Face ID API: Captures and encrypts facial structure via infrared and depth sensing.

Secure Enclave:
Secure hardware-based encrypted storage.
Biometric data stays local, never sent externally.

Authentication Logic Module:
Independent Mode: Accepts either Touch ID or Face ID.
Dual Authentication Mode: Requires both biometrics for access.

User Interface:
Real-time prompts for face/fingerprint scans.
Accessibility support and error feedback.

Testing and Results

| Metric                 | Result |
|:------------------------------|:-----------|
| False Acceptance Rate (FAR)    | Very low  |
| False Rejection Rate (FRR)     | Minimal (fallback to second biometric) |
| Authentication Response Time  | Under 2 seconds |
| Spoof Resistance              | Passed (dummy fingerprints and photos ineffective) |

The system maintains reliable performance across diverse lighting, device models, and user conditions.
 
 Privacy and Compliance
 Biometric data is encrypted and stored **only** on the device using Apple's

