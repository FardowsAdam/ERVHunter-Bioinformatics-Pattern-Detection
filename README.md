# 🧬 ERVHunter — Endogenous Retrovirus Detection Tool

ERVHunter is a Python-based bioinformatics tool for detecting Endogenous Retrovirus (ERV) signatures in human DNA sequences. The pipeline analyzes genomic regions to identify LTR pairs, PBS motifs, and PPT regions, then scores and predicts potential ERV locations.

This project combines computer science, pattern-matching algorithms, and genomics research.

---

## 🎯 Features

✔ Sliding-window ERV pattern detection  
✔ Fuzzy-match LTR discovery (with mismatch tolerance)  
✔ PBS & PPT motif identification  
✔ GC-content and feature-based scoring  
✔ ERV region prediction with confidence score  
✔ Automatic report & visualization generation  
✔ Export to CSV / JSON / BED for genome browsers

---

## 🧪 Biological Markers Detected

ERVHunter searches for viral “fingerprints” including:

- LTR — Long Terminal Repeat pairs
- PBS — Primer Binding Site motifs
- PPT — Polypurine Tract signals

These patterns help identify ancient viral fossils preserved in the human genome.

---

## 📂 Project Structure

| File | Description |
|------|-----------|
| `ERVHunter.ipynb` | Main ERV detection pipeline |
| `test_region.fa` | DNA region used for analysis |
| `erv_analysis_chr6.png` | Visualization output |
| `erv_results_chr6.csv` | Predicted ERV regions |
| `erv_results_chr6.json` | Structured results export |
| `erv_results_chr6.bed` | Genome browser annotations |

---

## 🚀 How to Run

### 1️⃣ Install dependencies

```bash
pip install -r requirements.txt
