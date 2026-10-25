# Contributing to Prep Club Study Resources

Thank you for your interest in contributing to the **Prep Club Study Resources** repository! This repository is curated to help MBA aspirants systematically prepare for CAT, XAT, SNAP, NMAT, CMAT, IIFT, GMAT, and other management entrance examinations.

To maintain clean repository hygiene, consistent navigation, and legal compliance, please adhere to the following guidelines.

---

## 1. Directory Structure & Placement Guidelines

Always place materials into their designated high-level category and subfolder:

```
prep-club-study-resources/
├── Subject-Specific-Prep/
│   ├── QA/                          # Quantitative Aptitude notes, formula books & problem sets
│   ├── VARC/                        # Verbal Ability & Reading Comprehension resources
│   ├── LRDI/                        # Logical Reasoning & Data Interpretation sets
│   ├── English/                     # Vocabulary, essays, general English
│   ├── Grammar/                     # Grammar rules, Wren & Martin, sentence correction
│   └── Static-GK/                   # Static General Knowledge compilations & yearbooks
│
├── Exam-Papers-and-PYQs/
│   ├── CAT-PYQs/                    # CAT Previous Year Papers & slot-wise solutions
│   ├── XAT/                         # XAT past papers, Decision Making (DM) sets
│   ├── SNAP-PYQs/                   # SNAP past papers and mock tests
│   ├── IIFT-Papers/                 # IIFT historical entrance question papers & keys
│   ├── CMAT/                        # CMAT official slot papers and solutions
│   ├── GMAT/                        # GMAT official guides and section reviews
│   ├── MAH-CET-Past-Papers/         # Maharashtra CET actual papers and memory tests
│   ├── NMAT/                        # NMAT official guides, memory-based questions & mocks
│   ├── PYQs-Anshuman/               # Curated multi-exam question paper collections
│   └── OMETs-and-Banking-Practice/  # Banking and other management entrance test sets
│
├── Coaching-Institute-Materials/
│   ├── IMS-Materials/               # IMS preparation modules & test sheets
│   ├── TIME-Material/               # T.I.M.E. study booklets and exercises
│   ├── Cracku-Formula/              # Cracku cheat-sheets and theorem compilations
│   ├── CL-Practice-Sheets/          # Career Launcher practice exercises & CDC mocks
│   ├── EduShastra/                  # EduShastra official section guides
│   ├── Takshzila/                   # Takshzila concept books & question banks
│   ├── Trishna-Knowledge-System/    # Trishna CAT guides (QA, DILR, VARC)
│   └── Unacademy/                   # Topic-wise revision sheets & practice tests
│
└── Authors-and-Reading-Material/
    ├── Arun-Sharma/                 # Works & references by Arun Sharma
    ├── Nishit-Sinha/                # Works & references by Nishit K. Sinha
    ├── LOKESHVA/                    # Critical reasoning, VA, and RC material by Lokesh Sharma
    └── Good-Reads-eBooks/           # Non-academic recommended reading list for GD/PI & vocabulary
```

---

## 2. File Naming Conventions

To keep Git history clean, cross-platform friendly, and easy to search from the terminal:

- **Use hyphens (`-`) instead of spaces** for all newly added folders and files.
  - ✅ `CAT-2022-Slot-1-Question-Paper.pdf`
  - ❌ `CAT 2022 Slot 1 Question Paper (1).pdf`
- **Be descriptive and include relevant metadata**:
  - Year, Slot/Shift, Subject/Section, and Source (if applicable).
  - Example: `XAT-2023-Decision-Making-Official-Solutions.pdf`
- **Avoid trailing underscores and messy copy artifacts**:
  - ❌ `NMAT_` or `CL NMAT Mock1 explainations (1).pdf`
  - ✅ `NMAT-Mock-01-Explanations.pdf`

---

## 3. Important: Copyright and Compliance Checklist

Before committing or submitting a pull request, ensure you have reviewed:

1. **Third-Party Copyright**: Coaching institute proprietary study materials, commercial published textbooks (e.g., McGraw-Hill, Pearson), and paid mock test series are subject to copyright.
2. **Repository Visibility**: If you are sharing materials that have commercial restrictions, keep your repository **private**. Do not publish copyrighted material into a public GitHub repository.
3. **Redact Sensitive Information**: Ensure any personal student portal IDs, registration roll numbers, watermark details, or personal emails are removed from PDFs or annotations before uploading.

---

## 4. Git Hygiene & Large Files

- **File Size Limit**: GitHub enforces a strict **100 MB per file limit** and recommends keeping repositories under **1 GB**.
- **Avoid Large Archives**: Avoid uploading `.zip` or `.rar` bundles exceeding 50 MB. Prefer uploading individual organized PDFs or hosting heavy media on external drives with links in `Resources-Index.md`.
- **Operating System Artifacts**: Keep `.gitignore` updated to prevent committing `Thumbs.db`, `.DS_Store`, or temporary files.

---

## 5. Submitting Changes

1. Fork or branch from `main`.
2. Place files into the appropriate directory following the naming standard.
3. Update `Resources-Index.md` with entries for the newly added files.
4. Commit with a clear message:
   ```bash
   git add .
   git commit -m "docs: add CAT 2023 Slot 1-3 solved papers with answer keys"
   ```
5. Push to your branch and open a Pull Request.
