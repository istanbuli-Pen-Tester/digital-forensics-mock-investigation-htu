# Digital Forensics Mock Investigation – HTU

**Summative digital forensics investigation conducted as a mock corporate case, following industry-standard forensic models, legal frameworks, and ethical principles.**

---

## Overview
This project presents a full digital forensic investigation into a simulated corporate embezzlement and kidnapping case involving:

- **Tom’s Laptop (Windows OS)**
- **Stephanie’s USB Flash Drive**

The investigation followed the **Rodney McKemmish forensic model** and adhered to forensic integrity, chain of custody, and legal admissibility principles.

---

## Investigation Scope
- File system forensics (NTFS)
- USB forensics & anti-forensics detection
- Windows OS artifacts analysis
- Timeline reconstruction
- Legal & ethical evaluation

---

## Key Technical Activities
- Hash verification (MD5 / SHA-1) to ensure evidence integrity
- Bit-stream image analysis using FTK Imager
- Manual VBR repair using hex-level analysis (HxD)
- Detection of hidden and manipulated partitions
- NTFS artifact analysis:
  - `$Recycle.Bin` ($I / $R files)
  - Jump Lists & LNK files
  - Unallocated and orphaned space
- Cross-device correlation proving USB usage on suspect laptop
- Browser history & Prefetch analysis
- Anti-forensics detection (wiped files, nulled data)

---

## Tools Used
- FTK Imager  
- HxD Hex Editor  
- JumpList Explorer & JLECmd  
- HashMyFiles  
- WinPrefetchView  
- BrowsingHistoryView  

---

## Legal & Ethical Framework
- Rodney McKemmish Model (Identification, Preservation, Analysis, Presentation)
- ISO/IEC 27037:2012 (Evidence acquisition)
- UK Computer Misuse Act 1990
- UK Data Protection Act 2018 / GDPR
- ACPO forensic principles

---

## Files
- `Forensic_Investigation_Report_Abdullah_Istanbuli.docx`  
  → Full forensic report with evidence analysis, findings, and conclusions

- `Assignment1_Forensics_Questions_Istanbuli.docx`  
  → Theoretical foundations, models, legal evaluation, and methodology

---

## Key Learnings
- Conducting court-defensible digital forensic investigations
- Identifying and countering anti-forensics techniques
- Preserving suspect rights while extracting critical evidence
- Linking multiple artifacts to establish intent and timeline
- Applying forensic work in both reactive and proactive security contexts
