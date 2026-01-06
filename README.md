# Academic DFIR Incident Response Case Study (Windows Lab)

## Overview

This repository documents an academic Digital Forensics and Incident Response (DFIR) case study conducted using a Windows workstation disk image. 
The objective of the investigation was to analyse suspected insider-related data handling activity and demonstrate evidence-led forensic methodology.

The investigation was performed in a controlled lab environment using a single forensic disk image (`.001`). 
Analysis focused on non-volatile artefacts recorded on the workstation, including file system activity, deleted data recovery, USB connection artefacts, browser history, email artefacts, and timeline correlation.

This case study is intended for learning and portfolio purposes and reflects DFIR practices aligned with professional standards, 
while remaining explicit about scope and limitations.


## Skills Demonstrated

- Digital forensic evidence handling and integrity verification (hash validation)
- Analysis of forensic disk images in a read-only environment
- Windows artefact analysis (file system metadata, registry, browser history, email artefacts)
- Deleted file recovery from unallocated space
- USB device usage inference through operating system artefacts
- Timeline construction and correlation across multiple artefact sources
- Application of ACPO principles within an academic DFIR context
- Clear technical reporting suitable for non-technical stakeholders



## Objective

- Practise structured DFIR triage, evidence handling, and forensic analysis using a workstation disk image
- Identify and analyse artefacts related to suspected insider activity, including file access, deletion, USB usage, browser activity, and email communications
- Construct and correlate a timeline of key events to support evidence-led conclusions
- Produce clear, professional findings suitable for handover to a SOC analyst or incident response team

## Dataset

- Windows workstation disk image (synthetic, non-production)
- Single forensic disk image provided in segmented format (`.001`)
- Dataset contains no real personal or organisational data


## Environment & Tools

**Environment**
- Virtualised lab environment
- Analysis performed on a non-production Windows workstation disk image
- All forensic analysis conducted in a controlled, read-only environment

**Tools**
- Autopsy – forensic artefact analysis and timeline correlation
- Exterro FTK Imager – forensic image verification and integrity checking
- SANS SIFT / Linux forensic utilities – independent hash verification and supporting analysis
- Native Windows utilities – contextual artefact review

## Methodology

The investigation followed a structured Digital Forensics and Incident Response (DFIR) workflow aligned with recognised best practices and ACPO principles.

1. **Scope and Assumptions**  
   Defined the scope of analysis based on the provided forensic disk image and identified relevant artefact categories related to suspected insider activity.

2. **Evidence Acquisition and Integrity Verification**  
   Verified the integrity of the forensic disk image using cryptographic hashing prior to analysis. All examination was conducted in a read-only environment.

3. **Triage and Artefact Collection**  
   Identified and extracted relevant artefacts, including file system metadata, deleted files, USB connection artefacts, browser history, and email artefacts.

4. **Timeline Analysis and Correlation**  
   Correlated timestamps across multiple artefact sources to reconstruct a sequence of events and identify relationships between user actions.

5. **Findings and Reporting**  
   Interpreted artefacts in context and documented findings in a clear, evidence-led manner suitable for handover to a SOC or incident response team.


## Deliverables

- Digital forensic investigation report (PDF) documenting findings and conclusions
- Selected screenshots of key artefacts (redacted)
- Timeline illustrating correlation of events
- Supporting notes outlining analysis steps and observations


## Disclaimer

This repository contains an academic Digital Forensics and Incident Response (DFIR) case study based on a simulated scenario. 
All data, systems, and events are synthetic and non-production.
The content is intended solely to demonstrate DFIR methodology, evidence handling, and analytical reasoning. 
It does not represent a real-world allegation, investigation, or legal determination.

## Author

Final-year BEng Cyber Security student  
Focus areas: Security Operations (SOC), Digital Forensics and Incident Response (DFIR)
