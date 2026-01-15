# In-silico TRFLP R Pipeline

## Overview
This repository contains an R-based bioinformatics pipeline for performing **in-silico Terminal Restriction Fragment Length Polymorphism (T-RFLP)** analysis using 16S rRNA gene sequences.  
The workflow is designed to simulate restriction enzyme digestion, generate predicted terminal restriction fragment (TRF) sizes, and compare in-silico profiles with experimental T-RFLP (EX-TRFLP) data.

This project was developed as part of research on microbial community dynamics associated with animal decomposition and is intended to support applications in microbial ecology, forensic microbiology, and environmental bioinformatics.

---

## Objectives
- Simulate in-silico T-RFLP profiles from 16S rRNA sequence datasets  
- Generate predicted TRF fragment sizes based on restriction enzyme digestion  
- Match and compare in-silico TRFs with experimental T-RFLP profiles  
- Support downstream ecological and statistical analysis  
- Provide a reproducible R-based workflow for TRFLP analysis  

---

## Features
- FASTA sequence processing in R  
- Primer-based sequence trimming  
- Restriction enzyme digestion simulation  
- Forward-labelled TRF extraction  
- Fragment size calculation  
- Matching of in-silico TRFs to experimental TRFLP data  
- Customizable parameters for enzyme choice and fragment tolerance  

---

## Tools and Environment
- R (>= 4.0 recommended)  
- Core R packages (e.g. tidyverse, Biostrings where applicable)    

---

## Project Status
This pipeline is actively under development and refinement.  
Future updates will include:
- Modularized functions  
- Example input/output datasets  
- Improved documentation  
- Visualization modules  
- Reproducible workflow examples  

---

## Disclaimer
This repository represents an academic research pipeline and is intended for educational and research purposes. Users are encouraged to validate results independently before applying to critical datasets.

---

## Author
**Sam Pei Fong**  
MSc Researcher | Microbiology
Department of Biological Sciences and Biotechnology
Faculty of Science and Technology
Universiti Kebangsaan Malaysia (UKM) 

---

## License
This project is released under the MIT License.
