# Renato Mignone

Security Research Engineer at **Huawei's Data Privacy Lab** (Düsseldorf), writing my Master's thesis on post-quantum anonymous authentication protocols. Pursuing an MSc in Cybersecurity Engineering at Politecnico di Torino (GPA 29.48/30), expected October 2026.

My work spans **post-quantum cryptography**, **kernel and systems security**, and **AI-driven threat detection**, from designing lattice-based anonymous credential schemes resistant to quantum adversaries, to building ML pipelines for malware classification and zero-day intrusion detection, to low-level eBPF verifier research at the Linux kernel level.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-renato--mignone-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/renato-mignone/)
[![Email](https://img.shields.io/badge/Email-renato.mignone@gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:renato.mignone@gmail.com)

---

## Current Work

**Master's Thesis, Post-Quantum Secure Anonymous Authentication**
Huawei Data Privacy Lab · Düsseldorf, Germany

Designing anonymous token systems secure against both classical and quantum adversaries (Grover and Shor threat models). Two constructions in development in Rust: one using CRYSTALS-Dilithium lattice signatures with Schnorr-based zero-knowledge proofs; one using MPC-based OPRFs to eliminate the ZK proof phase entirely. Research areas: post-quantum cryptography, anonymous credentials, privacy-preserving protocols.

---

## Selected Projects

**[Linux eBPF Verifier Bypass Research](https://github.com/RenatoMignone/Linux-eBPF-Verifier-Bypass-Research)**
Security research developing functional exploit proofs for eBPF verifier bypass techniques on Linux LTS 6.8. Builds on formal vulnerability assessment under ISO/IEC TS 17961-2013, moving from theoretical classification to practical kernel-level exploitation.

**[AI-Driven Threat Detection Research](https://github.com/RenatoMignone/AI-Driven-Threat-Detection-Research)**
Multi-model defence suite across four research modules: malware family classification via GNNs on API-call execution traces (98.1% accuracy); zero-day intrusion detection via unsupervised autoencoders without labelled attack data (95% precision); BERT/UniXcoder-based NLP for MITRE ATT&CK tactic recognition on bash session data.

**[IEEE-HKN International Hackathon, 1st Place](https://github.com/RenatoMignone/team9-spaghetti-overflow)**
Award-winning financial management platform built in 10 days for the IEEE-HKN International Budget Hack 2025. Full-stack application (React, Node.js, PostgreSQL, Docker) with Google OAuth, TOTP 2FA, role-based access control, PDF/CSV reporting, and single-command deployment. Certificate of Achievement signed by central IEEE-HKN leadership.

**[Cryptographic Implementations and CTF Challenges](https://github.com/RenatoMignone/Cryptography)**
Implementations of symmetric and asymmetric cryptographic primitives in C and Python using OpenSSL, alongside cryptanalysis exercises covering padding oracle attacks, keystream reuse, length extension, and timing attacks.

**[SSH Shell Attacks, ML Analysis](https://github.com/RenatoMignone/SSH-Shell-Attacks)**
Machine learning analysis of approximately 230,000 Unix shell sessions captured from distributed honeypots. Pipeline covers feature engineering (TF-IDF, Word2Vec, Doc2Vec), supervised classification (BERT, Random Forest, SVM), and unsupervised clustering with MITRE ATT&CK intent labelling.

---

## Education

**MSc Cybersecurity Engineering**, Politecnico di Torino, Italy
GPA 29.48/30 · Enrolled July 2024 · Expected October 2026
Curriculum aligned with ECSO standards. Language: English.

**BSc Computer Engineering**, Università degli Studi del Sannio, Benevento, Italy
Final grade 101/110 · Graduated June 2024
Thesis: *Extracting Equivocal Behaviours from Trusted Systems*, automated analysis of undisclosed behavioural patterns in trusted software using MITRE ATT&CK, Hybrid Analysis, VirusTotal, and ANY.RUN.

---

## Recognitions

- **1st Place, IEEE-HKN International Hackathon 2025** · Awarded at the 15th anniversary celebration of the IEEE-HKN organisational merger
- **Top 100 (88th), Reply Hack The Code Challenge 2025** · Global algorithmic optimisation and CTF competition (56M points)
- **IEEE-HKN Honor Society Member** · Mu Nu Chapter, Politecnico di Torino · Coordinating technical operations for 5+ STEM events with 150–250 participants
