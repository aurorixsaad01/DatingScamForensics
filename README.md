# DatingScamForensics
A ready, Well structured project for highSchoolStudents, for Forensics Subjects!

---

# 📌 **DatingScamForensics – Digital Forensics Demo Project**

A simple, ready-to-use digital forensics project that demonstrates how to investigate an **online dating scam** using free tools.
This project is perfect for students who need a practical cybersecurity project for exams or assignments.

---

# 🎯 **Project Goal**

To show a **complete forensic investigation workflow** on a fake dating scam case using:

* Evidence Acquisition
* Browser Artifact Analysis
* Image Metadata Inspection
* OSINT (Reverse Image Search)
* AI-Based Interpretation

All tools used are **free** and run smoothly on basic hardware.

---

# 🧰 **Tools Used (All Free)**

| Tool                     | Purpose                                     |
| ------------------------ | ------------------------------------------- |
| **FTK Imager**           | Acquire evidence & generate hashes          |
| **Autopsy**              | Browser history + image + artifact analysis |
| **ExifTool**             | Metadata analysis of scammer profile photos |
| **BrowserHistoryView**   | Quick browser artifact review               |
| **Google Lens / Yandex** | Reverse image search (OSINT)                |
| **ChatGPT**              | AI-assisted analysis of logs & metadata     |

---

# 📂 **Project Structure**

```
DatingScamForensics/
│
├── 1-Tools/                      # Contains installers (ignored on GitHub)
│
├── 2-Evidence/
│   ├── BrowserData/              # Fake browser history
│   ├── Chats/                    # Fake scam chat logs
│   ├── Images/                   # Fake profile photos
│   ├── OSINT/                    # Reverse image search results
│   └── AcquiredImages/           # E01 image + hash report (ignored on GitHub)
│
├── 3-AutopsyCase/                # Autopsy project (heavy data ignored)
│
├── 4-Analysis/
│   ├── BrowserArtifactAnalysis/
│   ├── MetadataAnalysis/
│   ├── TimelineReconstruction/
│   └── OSINTFindings/
│
├── 5-AI-Assistance/
│   ├── AI_Chat_Analysis.txt
│   ├── AI_Browser_Analysis.txt
│   ├── AI_Metadata_Analysis.txt
│   └── AI_FinalFindings.txt
│
├── 6-Documentation/
│   ├── FinalForensicReport.docx  # Main report
│   ├── CaseSummary.txt
│   └── ToolUsageSteps.docx
│
├── 7-Presentation/
│   ├── Slides.pptx               # Viva presentation
│   ├── DemoScript.txt            # What to say in exam
│   └── VivaQuestions.txt         # Q&A sheet
│
└── .gitignore                    # Ensures repo stays clean and lightweight
```

---

# 📝 **Investigation Summary**

This project simulates a dating scam investigation:

1. **Fake evidence folder created** (browser history, chats, images).
2. **FTK Imager** used to acquire evidence (E01 file + hash).
3. **Autopsy** reveals:

   * dating site activity
   * Instagram profile
   * scam email
   * money transfer link
4. **ExifTool** shows suspicious images (missing EXIF data).
5. **Google Lens/Yandex** reveal stolen profile pictures.
6. **AI analysis** identifies manipulation and fraud patterns.

The entire workflow is easy to demonstrate in 3–5 minutes during an exam.

---

# 🧠 **What Students Learn**

* How to preserve and acquire digital evidence
* How to analyze browser artifacts
* How metadata reveals identity fraud
* How OSINT helps detect stolen photos
* How AI can assist forensic interpretation
* How to document a digital investigation
* How to present a cybersecurity case clearly

---

# 🎓 **Why This Is a Great Student Project**

* Beginner-friendly
* Fully structured and realistic
* Uses only free tools
* Looks professional in exams
* Gives practical cybersecurity experience
* Easy to extend into larger projects

---

# 💡 **Possible Future Extensions**

* Memory forensics
* Mobile dating app forensics
* Automated scam detection scripts
* Chat analysis using NLP models
* Browser activity timeline visualization

---
