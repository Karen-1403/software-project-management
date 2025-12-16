# Online Course Registration Portal - Project Documentation

This repository contains the comprehensive project management documentation for the Online Course Registration Portal, a Software Project Management course project.

## Project Overview

A student course registration system with prerequisites, waitlists, and timetable conflict detection. Focus on rule enforcement, concurrency handling, and scalable design.

## Repository Structure

```
.
├── main.tex                    # Main LaTeX document
├── chapters/                   # Individual chapter files
│   ├── 00-cover.tex           # Cover page
│   ├── 01-abstract.tex        # Abstract
│   ├── 02-introduction.tex    # Introduction chapter
│   ├── 03-project-charter.tex # Project charter
│   ├── 04-project-constraints.tex
│   ├── 05-project-phases.tex
│   ├── 06-wbs.tex             # Work Breakdown Structure
│   ├── 07-gantt-milestones.tex
│   ├── 08-aon-critical-path.tex
│   ├── 09-pert-estimation.tex
│   ├── 10-npv-analysis.tex
│   ├── 11-cash-flow.tex
│   ├── 12-payback-roi.tex
│   ├── 13-raci-chart.tex
│   ├── 14-risk-analysis.tex
│   ├── 15-schedule-analysis.tex
│   ├── 16-cost-estimation.tex
│   └── 17-references.tex
└── images/                     # Diagrams and figures
    └── (place all images here)
```

## Building the Document

### Prerequisites

- LaTeX distribution (TeX Live, MiKTeX, or MacTeX)
- PDF viewer

### Compilation

To compile the document:

```bash
pdflatex main.tex
pdflatex main.tex  # Run twice for references and TOC
```

Or use your preferred LaTeX editor (TeXstudio, Overleaf, etc.)

## Document Specifications

- **Font**: Calibri (or similar)
- **Main Title**: 14pt, bold
- **Subtitles**: 12pt, bold  
- **Body Text**: 12pt
- **Captions**: 10pt
- **Spacing**: Single spacing, 12pt before and 6pt after paragraphs
- **Alignment**: Justified
- **Currency**: Egyptian Pound (EGP)

## Required Diagrams and Images

Create the following diagrams using MS Visio or similar professional tools and save them in the `images/` folder:

1. **university-logo.png** - Your university logo
2. **project-lifecycle.pdf** - Project phases diagram
3. **wbs-diagram.pdf** - Work Breakdown Structure visualization
4. **gantt-chart.pdf** - Complete Gantt chart from MS Project
5. **aon-diagram.pdf** - Activity-on-Node network diagram
6. **cash-flow-chart.pdf** - Cumulative cash flow chart
7. **risk-matrix.pdf** - Risk probability-impact matrix

All diagrams should be vector graphics (PDF, SVG) for best quality.

## Team Instructions

### Before Starting

1. Update the document information in `main.tex`:
   - University name
   - Faculty and department
   - Course code and name
   - Group member names and IDs
   - Academic year and semester

### Working on Chapters

1. Each team member can work on different chapter files
2. Update values marked with `[Insert...]` or `[X]`
3. Add actual data from your project planning
4. Create and add required diagrams to the `images/` folder

### Important Tasks

- [ ] Add university logo to images folder
- [ ] Create WBS diagram in MS Visio
- [ ] Create Gantt chart in MS Project
- [ ] Create AON network diagram
- [ ] Create risk probability-impact matrix
- [ ] Fill in all placeholder values (budgets, dates, durations)
- [ ] Update group member information
- [ ] Review and customize all assumptions
- [ ] Add actual cost estimates for your context
- [ ] Customize risks based on your project
- [ ] Add project-specific references

## Notes

- All costs are in Egyptian Pounds (EGP)
- Follow Egyptian academic calendar and context
- Maintain consistent formatting throughout
- Check for typos and grammatical errors
- Ensure all figures and tables are numbered and captioned
- Run plagiarism check before submission

## Course Requirements Checklist

- [x] Cover Page with all required information
- [x] Abstract
- [x] Table of Contents (auto-generated)
- [x] Introduction (Purpose, Definitions, Overview, Assumptions)
- [x] Project Charter
- [x] Time, Scope, and Cost Constraints
- [x] Project Phases
- [x] WBS to 3rd level
- [x] Gantt Chart with Milestones and Justifications
- [x] AON with Resources and Critical Path
- [x] PERT Time Estimates
- [x] NPV Analysis
- [x] Cash Flow Estimation
- [x] Payback Period and ROI
- [x] RACI Chart
- [x] Risk Analysis and Probability-Impact Matrix
- [x] ES, EF, LS, LF, Free Float, Total Float
- [x] Cost Estimation (2+ methods with justification)
- [x] References

## License

This is an academic project for educational purposes.

## Contact

For questions or issues, contact your group members:
- [Student 1 Name] - [Email]
- [Student 2 Name] - [Email]
- [Student 3 Name] - [Email]
- [Student 4 Name] - [Email]
- [Student 5 Name] - [Email]
