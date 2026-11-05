---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education  
**Carnegie Mellon University (CMU)**  
*Pittsburgh, PA*  
PHD IN COMPUTER SCIENCE  
August 2025 - present  
- Advisor: Dr. Sarah Scheffler  

**Massachusetts Institute of Technology (MIT)**  
*Cambridge, MA*  
M.ENG. IN ELECTRICAL ENGINEERING AND COMPUTER SCIENCE  
September 2022 - June 2023  
- Advisor: Dr. Karen Sollins  
- GPA: 4.8/5.0  

**Massachusetts Institute of Technology (MIT)**  
*Cambridge, MA*  
B.S. IN ELECTRICAL ENGINEERING AND COMPUTER SCIENCE  
September 2018 - May 2022  
- Minor: Economics  
- GPA: 5.0/5.0  

---

## Research Interests  

My broad research interests lie in the application of cryptography to solve social problems and protect privacy. I am interested in bringing formal, provable security to real-world computer systems. I am particularly interested in problems with competing tensions between authenticity, anonymity, and efficiency.

---

## Research Experience  

**Carnegie Mellon University - CyLab**  
*Pittsburgh, PA*  
ADVISOR: DR. SARAH SCHEFFLER  
June 2026 - present  
**ANONYMOUS C2PA: FEASIBILITY OF LARGE-SCALE ANONYMOUS IMAGE PROVENANCE**  

- This project analyzes the technical standard for image provenance from the Coalition for Content Provenance and Authenticity (C2PA). My work first formalized the security properties the current version of C2PA claims to have. Then, I address dangerous surveillance concerns in C2PA by analyzing and formalizing the properties desirable in an ideal anonymous image provenance system. I find several fundamental incompatibilities between these properties, both from results existing in the literature in different contexts and my own novel results. Given this, I improve existing cryptographic constructions and propose candidate system architectures to achieve different versions of anonymous C2PA that make different trade-offs between these properties.  
- Formalized security properties of C2PA v2.5 for use in cryptography proofs by systems using C2PA as a module.  
- Derived formal cryptographic and system property desiderata from needs of different actors and systems using C2PA, including generator anonymity, key revocation, and generators' efficiency.  
- Developed a novel generic construction for shrinkable ring signatures allowing for shrinking to arbitrary subrings.  
- Proved that shrinking a list of signatures requires linear work in the number of signatures being shrunk, and combined with existing results in the literature, demonstrated that the full set of properties one might desire from an anonymous C2PA system is unachievable in a single scheme in a scalable way.  
- Architected candidate systems across the trade-off space and analyzed their efficiency and viability.  

**Carnegie Mellon University - CyLab**  
*Pittsburgh, PA*  
ADVISOR: DR. SARAH SCHEFFLER  
August 2025 - June 2026  
**ZERO-KNOWLEDGE BARCODE SCANNING**  

- Design and implementation of a zero-knowledge proof system for barcode decoding from images with application to private online attribute verification using physical IDs.  
- Designed, implemented, and measured end-to-end zero-knowledge proof system for PDF417 barcode decoding, achieving an 18x speedup and using 6.9x less RAM.  
- Developed technical gadgets of independent interest for arithmetization of highly data-dependent algorithms for zero-knowledge proofs.  

**Massachusetts Institute of Technology - CSAIL**  
*Cambridge, MA*  
ADVISOR: DR. KAREN SOLLINS  
September 2022 - June 2023  
**THESIS TITLE: “ZK-SIGSTORE: SYSTEM FOR ANONYMOUS CERTIFICATE-BASED SOFTWARE SIGNING”**  
*2024 CHARLES & JENNIFER JOHNSON COMPUTER SCIENCE MENG THESIS AWARD*  

- My research focused on software supply chain security, particularly concerning open-source software authenticity. My work developed a practical, easy-to-use, and easy-to-deploy system for convincing users a particular software package is trustworthy while protecting the privacy of open-source maintainers. This project involved applied cryptography work as well as system design and implementation.  
- Designed, implemented, and measured a proof-of-concept system for anonymous, certificate-based software signing using zk-SNARKs.  
- Developed novel application of cryptographic commitment technique (Pedersen commitments) to achieve desired privacy properties for software signing system more efficiently.  
- Implemented and measured Pedersen commitment system for efficient, deployable, anonymous, certificate-based software signing.  
- Developed and formalized state machine model of a package repository, useful for discussing package repository security.  
- Applied Merkle tree techniques to package repository setting for greater efficiency while maintaining desired consistency properties.  
- Published paper on the project at CCS 2023.  

**Massachusetts Institute of Technology - Research Laboratory of Electronics**  
*Cambridge, MA*  
ADVISOR: DR. MURIEL MÉDARD  
Summer 2021  
- Implemented SGRAND algorithm in C++ for universal soft network decoding  
- Simulated network noise and SGRAND decoding in software and measured SGRAND’s performance  

---

## Publications  

- **Kelsey Merrill**, Anna Woo, Wenting Zheng, Sarah Scheffler. Cryptology ePrint Archive, Paper 2026/1567. *Zero Knowledge Barcode Decoding with Application to Private Online Attribute Verification.* [https://eprint.iacr.org/2026/1567](https://eprint.iacr.org/2026/1567)
- **Kelsey Merrill**, Zachary Newman, Santiago Torres-Arias, Karen Sollins. CCS 2023. *Speranza: Usable, privacy-friendly software signing.* [https://doi.org/10.1145/3576915.3623200](https://doi.org/10.1145/3576915.3623200)

---

## Presentations  

- **Speranza: Usable, Privacy-Friendly Software Signing.** ACM CCS, November 2023. ([slides](/files/speranza_slides_ccs_2023.pdf))  

---

## Teaching Experience  

**Applied Cryptography MIT**  
*TEACHING ASSISTANT*  
Spring 2023  
- Teaching assistant for graduate course in applied cryptography. Topics include symmetric and asymmetric key encryption, message authentication codes, digital signatures, zero knowledge proofs, and hashing.  
- Collaborated with other course instructors to develop problem sets, the exam, and corresponding solutions.  
- Taught recitations on select topics and assisted students one-on-one in office hours.  
- Managed a team of graders to ensure problem sets were graded correctly and in a timely manner.  
- Student evaluation: 7.0/7.0  

**Design and Analysis of Algorithms MIT**  
*TEACHING ASSISTANT*  
Fall 2022  
- Teaching assistant for advanced undergraduate course in algorithms. Topics include randomized algorithms, amortized analysis, hashing, max flow, random walks, and intractability.  
- Collaborated with other course instructors to develop problem sets, exams, and corresponding solutions.  
- Taught weekly recitations reviewing course material and assisted students one-on-one in office hours.  
- Student evaluation: 7.0/7.0  

**Future MIT Course Design - Introductory Electronics**  
*Cambridge, MA*  
*UNDERGRADUATE ASSISTANT*  
September 2020 - August 2021  
- Collaborated with a team of three to design hands-on labs for a new introductory electronics course at MIT  
- Brainstormed and tested innovative ways to introduce students to basic electronics concepts using Infineon PSoC  
- Developed lab documentation for beginner students including explanations of core electrical engineering topics  

**Introduction to Circuits MIT**  
*TUTOR, LAB ASSISTANT, AND GRADER*  
Spring 2020 - Spring 2022  
- Tutor, lab assistant, and grader for introductory undergraduate course on electronic circuits. Topics include circuit analysis with resistors, capacitors, and inductors in both the time and frequency domain, resonance, transistors, and transformers.  
- Assisted students with weekly hands-on electronics lab exercises. Instructed in the use of oscilloscope, signal generator, soldering iron, and other common lab equipment.  
- Graded weekly student homework.  
- Assisted students one-on-one in office hours.  
- Tutored struggling students one-on-one outside of the class time and developed additional supplementary materials.  

---

## Professional Experience  

**Jane Street Capital**  
*SOFTWARE ENGINEER, AI TOOLS TEAM*  
August 2023 - August 2025  
- Built and maintained scalable and available software system for managing firmwide requests to external LLM vendors including rate limiting, priority queuing, and fairness enforcement.  
- Designed, built, and maintained AI semantic search service for internal use  
- Responded to live production incidents  
- Advised and consulted on LLM applications throughout the firm  

*SOFTWARE ENGINEERING INTERN*  
Summer 2022  
- Designed and built memory error debugging tool for large, distributed computation system  
- Developed fuzzing testing system for internal web application compiler  

**Omnivis**  
*SOFTWARE ENGINEERING INTERN*  
Summer 2020  
- Implemented computer vision algorithm for detecting cholera in water  
- Built GUI for cholera detection application  

**HINTS**  
*SOFTWARE ENGINEERING INTERN*  
June 2019 - February 2020  
- Implemented parallelized algorithm in Golang for identifying and tracking misinformation on social media; rewrote code and increased scalability from tens of thousands to tens of millions of datapoints  
- Built backend API server for using the algorithm and accessing results in Google Cloud Platform  
- Designed and built Golang module for managing and abstracting multi-threaded jobs  

---

## Leadership  

**Cecilia Chorus of New York**  
*DEVELOPMENT CO-CHAIR AND BOARD MEMBER*  
July 2024 - June 2025  
- Led and organized grant writing and applications for community chorus of approximately 150 members resulting in over $100,000 in funding  
- Participated in board meetings and whole-chorus decision-making  

**MITvote**  
*UNDERGRADUATE CO-CHAIR*  
January 2019 - December 2020  
- Oversaw group of over 70 members, organized volunteers, and set group goals for student voter engagement and turnout  
- Coordinated with MIT administration and other student groups on voter turnout efforts  
- Developed new methods and planned new initiatives for empowering students to vote  
- Received MIT Priscilla King Grey Award for Public Service for continued voter engagement work in 2023  

**Chorallaries of MIT**  
*PRESIDENT*  
January 2021 - December 2021  
- Led executive board meetings and oversaw group progress towards goals  
- Resolved conflicts among members or with administration  
- Interfaced with MIT administration and corresponded with group alumni to plan events  

---

## References

*contact information available upon request*

**Professor Sarah Scheffler**  
Department of Software and Societal Systems  
Carnegie Mellon University

**Dr. Karen R. Sollins**  
Department of Electrical Engineering and Computer Science  
Massachusetts Institute of Technology

**Professor Santiago Torres-Arias**  
Department of Electrical and Computer Engineering  
Purdue University

**Professor Henry Corrigan-Gibbs**  
Department of Electrical Engineering and Computer Science  
Massachusetts Institute of Technology

**Zachary Newman**  
Jane Street

**Dr. Nathan Linger**  
Jane Street
