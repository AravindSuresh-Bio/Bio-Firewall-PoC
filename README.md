# ENGIN: Edge-Native Genomic Inspection Node
**Version:** 1.0.0-Beta
**Lead Developer:** Aravind Suresh (AMRSB)
**Architecture:** Python Stream-Processing (Client-Server)



## 🧬 Project Abstract
**ENGIN** is a specialized real-time filtration protocol for DNA sequencing pipelines. Acting as a "Genomic Firewall," it sits between the sequencer and the storage infrastructure to perform **Deep Packet Inspection** on biological data.

**The Problem:** Clinical sequencing generates massive amounts of non-informative "Host" data (e.g., 99% Human background in an infection sample), clogging bandwidth and storage.

**The Solution:** ENGIN utilizes a **Negative Selection Algorithm** to intercept raw FASTQ reads at the source. It automatically identifies and discards known Host reads while preserving Pathogen and Variant data, achieving **>90% Data Minimization** before the data ever touches the disk.
