# file-integrity-lab
cybersecurity lab that demonstrates file integrity monitoring using SHA-256 hashing. Includes scripts to generate baseline hashes, simulate tampering, and compare results with documented evidence.
# 🔐 File Integrity Monitoring Lab (SHA-256)

This project demonstrates a simple but essential cybersecurity concept: **file integrity monitoring**.  
By generating a baseline hash of a file, simulating tampering, and re-hashing, you can detect unauthorized changes immediately.

---

## 🚀 What I Learned
- How to generate SHA-256 hashes with `shasum`
- How to detect file tampering by comparing baseline vs. modified hashes
- How to document evidence for auditing and reporting

---

## 🛠️ Tools Used
- **macOS Terminal**
- **shasum** (built into macOS for hashing)
- **Git & GitHub** (for documentation and version control)

---

## 📂 Steps Performed
1. **Created a test file**
   ```bash
   echo "This is a secure file." > secure.txt
