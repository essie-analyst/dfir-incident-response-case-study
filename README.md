# Academic DFIR Incident Response Case Study (Windows Lab)

## Overview
## Simulated DFIR case study based on a Windows lab image. 
## This project documents a structured investigation using incident response and forensic handling principles.

## Skills Demonstrated

- Digital forensic evidence handling and integrity verification (hash validation)
- Analysis of forensic disk images in a read-only environment
- Windows artefact analysis (file system metadata, registry, browser history, email artefacts)
- Deleted file recovery from unallocated space
- USB device usage inference through operating system artefacts
- Timeline construction and correlation across multiple artefact sources
- Application of ACPO principles within an academic DFIR context
- Clear technical reporting suitable for non-technical stakeholders


This repository documents an academic Digital Forensics and Incident Response (DFIR) case study conducted using a Windows workstation disk image. 
The objective of the investigation was to analyse suspected insider-related data handling activity and demonstrate evidence-led forensic methodology.

The investigation was performed in a controlled lab environment using a single forensic disk image (`.001`). Analysis focused on non-volatile artefacts recorded on the workstation, 
including file system activity, deleted data recovery, USB connection artefacts, browser history, email artefacts, and timeline correlation.

This case study is intended for learning and portfolio purposes and reflects DFIR practices aligned with professional standards, while remaining explicit about scope and limitations.


## Objective
- Practise triage, evidence handling, timeline building, and reporting
- Produce clear findings that could be handed to a SOC lead or IR manager

## Dataset
- Windows lab image (synthetic / non-production)
- No real personal data










## Environment & Tools
- Host: Virtual lab environment
- Tools: Autopsy, FTK Imager, SANS SIFT, Windows utilities

## Methodology
1. Scope and assumptions
2. Evidence acquisition and integrity (hashing)
3. Triage and artefact collection
4. Timeline analysis
5. Findings and recommendations

## Deliverables
- Investigation notes and evidence table
- Timeline of key events
- Final report with conclusions and next actions
