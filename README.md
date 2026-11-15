# Bank Loan Management System - Software Engineering Project Documentation

**Course:** CIC-357 Software Engineering Lab  
**Academic Degree:** Bachelor of Technology (B.Tech) - Information Technology  
**Institution:** Maharaja Agrasen Institute of Technology (MAIT)  
**Department:** Department of Information Technology  
**Address:** PSP Area, Sector 22, Rohini, New Delhi – 110085  

---

## 1. Project Overview

This repository contains the complete, academically rigorous Software Engineering Project Documentation package for the **Bank Loan Management System**, formulated in strict accordance with the university syllabus and the official Software Engineering Lab File (`CIC-357`).

As specified in the curriculum, this is an **exhaustive software analysis, design, and documentation project**. It covers all phases of the Software Development Life Cycle (SDLC) prior to coding, including problem formulation, requirement engineering, structured analysis, object-oriented design, database architecture, software testing, project estimation, project scheduling, and risk management.

---

## 2. Deliverables Summary

| Deliverable | Format | File Path | Description |
|---|---|---|---|
| **Full Project Report (PDF)** | PDF | `Report/Project_Report.pdf` | 105-page publication-grade compiled academic report with embedded diagrams and styled tables |
| **Full Project Report (DOCX)** | DOCX | `Report/Project_Report.docx` | Fully editable Microsoft Word document with native headings, styles, and embedded figures |
| **Full Project Report (Markdown)** | Markdown | `Report/Project_Report.md` | Source Markdown file (~193 KB, 2,380 lines, 199 structured sections) |
| **Individual Vector Diagrams** | SVG | `Diagrams/*.svg` | 17 individual scalable vector graphics for printing or presentation slides |
| **Individual Raster Diagrams** | PNG | `Diagrams/*.png` | 17 high-resolution raster images for document embedding and visual review |
| **Editable Diagram Sources** | MMD | `Diagrams/mermaid_sources/*.mmd` | 17 editable Mermaid source text files for live editing in Mermaid Live Editor |
| **Complete Submission Archive** | ZIP | `../Bank_Loan_Management_System.zip` | Consolidated zip archive ready for email or online LMS submission |

---

## 3. Directory Structure

```
Bank_Loan_Management_System/
│
├── README.md                                  # Project overview and submission instructions
│
├── Report/                                    # Final compiled project documentation
│   ├── Project_Report.pdf                     # Submission-ready 105-page PDF document
│   ├── Project_Report.docx                    # Fully editable Word document
│   └── Project_Report.md                      # Complete raw Markdown text
│
└── Diagrams/                                  # All project architectural and UML diagrams
    ├── activity_diagram.png                   # Figure 3.11: Activity Diagram (Raster)
    ├── activity_diagram.svg                   # Figure 3.11: Activity Diagram (Vector)
    ├── class_diagram.png                      # Figure 3.8: Class Diagram (Raster)
    ├── class_diagram.svg                      # Figure 3.8: Class Diagram (Vector)
    ├── collaboration_diagram.png              # Figure 3.13: Collaboration Diagram (Raster)
    ├── collaboration_diagram.svg              # Figure 3.13: Collaboration Diagram (Vector)
    ├── component_diagram.png                  # Figure 3.14: Component Diagram (Raster)
    ├── component_diagram.svg                  # Figure 3.14: Component Diagram (Vector)
    ├── deployment_diagram.png                 # Figure 3.15: Deployment Diagram (Raster)
    ├── deployment_diagram.svg                 # Figure 3.15: Deployment Diagram (Vector)
    ├── dfd_level_0.png                        # Figure 3.2: Context-Level DFD (Level 0) (Raster)
    ├── dfd_level_0.svg                        # Figure 3.2: Context-Level DFD (Level 0) (Vector)
    ├── dfd_level_1.png                        # Figure 3.3: First-Level DFD (Level 1) (Raster)
    ├── dfd_level_1.svg                        # Figure 3.3: First-Level DFD (Level 1) (Vector)
    ├── dfd_level_2.png                        # Figure 3.4: Second-Level DFD (Level 2) (Raster)
    ├── dfd_level_2.svg                        # Figure 3.4: Second-Level DFD (Level 2) (Vector)
    ├── er_diagram.png                         # Figure 3.6: Entity-Relationship Diagram (Raster)
    ├── er_diagram.svg                         # Figure 3.6: Entity-Relationship Diagram (Vector)
    ├── flowchart.png                          # Figure 3.1: Problem Flowchart (Raster)
    ├── flowchart.svg                          # Figure 3.1: Problem Flowchart (Vector)
    ├── gantt_chart.png                        # Figure 7.1: Project Gantt Schedule (Raster)
    ├── gantt_chart.svg                        # Figure 7.1: Project Gantt Schedule (Vector)
    ├── object_diagram.png                     # Figure 3.9: Object Diagram Snapshot (Raster)
    ├── object_diagram.svg                     # Figure 3.9: Object Diagram Snapshot (Vector)
    ├── pert_chart.png                         # Figure 7.2: PERT / CPM Network Diagram (Raster)
    ├── pert_chart.svg                         # Figure 7.2: PERT / CPM Network Diagram (Vector)
    ├── sequence_diagram.png                   # Figure 3.12: Sequence Diagram (Raster)
    ├── sequence_diagram.svg                   # Figure 3.12: Sequence Diagram (Vector)
    ├── state_chart.png                        # Figure 3.10: State-Chart Diagram (Raster)
    ├── state_chart.svg                        # Figure 3.10: State-Chart Diagram (Vector)
    ├── structure_chart.png                    # Figure 3.5: System Structure Chart (Raster)
    ├── structure_chart.svg                    # Figure 3.5: System Structure Chart (Vector)
    ├── use_case_diagram.png                   # Figure 3.7: Use Case Diagram (Raster)
    ├── use_case_diagram.svg                   # Figure 3.7: Use Case Diagram (Vector)
    │
    └── mermaid_sources/                       # Original editable diagram source files
        ├── activity_diagram.mmd
        ├── class_diagram.mmd
        ├── collaboration_diagram.mmd
        ├── component_diagram.mmd
        ├── deployment_diagram.mmd
        ├── dfd_level_0.mmd
        ├── dfd_level_1.mmd
        ├── dfd_level_2.mmd
        ├── er_diagram.mmd
        ├── flowchart.mmd
        ├── gantt_chart.mmd
        ├── object_diagram.mmd
        ├── pert_chart.mmd
        ├── sequence_diagram.mmd
        ├── state_chart.mmd
        ├── structure_chart.mmd
        └── use_case_diagram.mmd
```

---

## 4. University Lab Experiments Covered

The project report completely satisfies and expands upon every experiment in the official lab curriculum:

| Experiment No. | Experiment Title in Syllabus | Report Section / Chapter | Key Contents & Deliverables |
|---|---|---|---|
| **Experiment 1** | Problem Statement Identification | Section B (Chapter 1) | Background, existing manual limitations, problem statement, objectives, scope, feasibility |
| **Experiment 2** | Requirement Analysis & SRS | Section C (Chapter 2) | Full IEEE 830 SRS, 18 Functional Requirements, 8 NFRs, external interfaces, use case specs |
| **Experiment 3** | Function-Oriented Modeling | Section D (Chapter 3) | Context DFD (Level 0), Level 1 DFD, Level 2 DFD (Process 2.0), Modular Structure Chart |
| **Experiment 4** | Entity-Relationship (ER) Modeling | Section D & E (Ch 3 & 4) | ER Diagram (6 entities, full attributes, PK/FK, cardinality, participation constraints) |
| **Experiment 5** | User View Analysis (Use Case Modeling)| Section D (Chapter 3) | Use Case Diagram (3 actors, 19 use cases, `<<include>>`, `<<extend>>`, boundary) |
| **Experiment 6** | Static Structural Modeling | Section D (Chapter 3) | Class Diagram (9 classes, visibility, inheritance, associations) and Object Diagram snapshot |
| **Experiment 7** | Dynamic Behavioral Modeling | Section D (Chapter 3) | State-Chart Diagram (8 lifecycle states) and Activity Diagram (3-swimlane workflow) |
| **Experiment 8** | Behavioral Interaction Modeling | Section D (Chapter 3) | Sequence Diagram (synchronous messages, alt/loop frames) and Collaboration Diagram |
| **Beyond Exp 1** | System Flowchart Design | Section D (Chapter 3) | Algorithmic Problem Flowchart from customer onboarding to final loan closure |
| **Beyond Exp 2** | Extended ER Modeling & Normalization | Section E (Chapter 4) | Relational Schema, Data Dictionary, 1NF/2NF/3NF formal normalization proofs, sample rows |
| **Experiment 11**| Software Testing Documentation | Section F (Chapter 5) | Testing strategy, levels, Black-box EP/BVA techniques, 22 comprehensive test cases |
| **Experiment 12**| Function Point Analysis Estimation | Section G (Chapter 6) | Full Albrecht/IFPUG FPA calculation (EI, EO, EQ, ILF, EIF, 14 GSCs, VAF, FP = 191.4) |
| **Experiment 13**| Project Scheduling & Tracking | Section H (Chapter 7) | 4-level WBS, Activity duration/precedences, Gantt Chart, PERT Network, CPM Critical Path |

---

## 5. Instructions for Student Submission

Before final submission to your faculty evaluator:

1. **Open `Report/Project_Report.docx`** in Microsoft Word.
2. Locate the bracketed placeholders on the **Cover Page**, **Certificate**, **Declaration**, and **Acknowledgement**:
   - `[Student Name]` $\rightarrow$ Replace with your full name.
   - `[University Roll Number]` $\rightarrow$ Replace with your university roll number.
   - `[Semester]` $\rightarrow$ Replace with your current semester (e.g., *5th Semester* or *6th Semester*).
   - `[Faculty Name]` $\rightarrow$ Replace with your designated faculty guide / project mentor.
   - `[Academic Session]` $\rightarrow$ Replace with your current academic session (e.g., *2025–2026*).
3. If you make any text edits in Word, update the Table of Contents by right-clicking on it and selecting **Update Field $\rightarrow$ Update entire table**.
4. Save the file and export it to PDF using **File $\rightarrow$ Export $\rightarrow$ Create PDF/XPS**.
5. Both the `.docx` and `.pdf` files are completely formatted according to university standards (A4, 1-inch margins, standard fonts, numbered headings, figure/table captions).
