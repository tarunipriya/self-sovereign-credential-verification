# Self-Sovereign Academic Credential Verification System

## 📌 Overview
This project proposes a blockchain-based system using Algorand to securely store and verify academic certificates. Universities upload certificates as unique hashes, students can access and share them, and recruiters can verify them instantly using a QR code. This ensures certificates cannot be faked or changed and makes verification fast and reliable.

---

## 🚀 Proposed Solution
We propose a blockchain-based system using Algorand to securely store and verify academic certificates. Universities upload certificates as unique hashes, students can access and share them, and recruiters can verify them instantly using a QR code.

---

## 🧩 System Architecture
The system consists of four main components:

- **Frontend (React):** User interface for University, Student, and Recruiter  
- **Backend (Node.js / Flask):** Handles certificate processing and API requests  
- **Blockchain (Algorand):** Stores certificate hashes securely  
- **Storage (IPFS / Firebase):** Stores certificate files (optional)  

### 🔁 Architecture Flow
Frontend → Backend → Blockchain (Algorand) → Storage  
Recruiter → QR Scan → Fetch from Blockchain → Verification  

---

## 🔄 Process Flow
1. University uploads certificate  
2. System generates hash  
3. Hash stored on blockchain  
4. Student accesses certificate  
5. QR code generated  
6. Recruiter scans QR  
7. System verifies certificate from blockchain  

---

## ✨ Features
- Secure certificate issuance  
- Blockchain-based tamper-proof storage  
- Student-controlled credential access  
- QR code-based instant verification  
- Certificate revocation support  

---

## 🛠️ Tech Stack
- **Blockchain:** Algorand  
- **Smart Contracts:** PyTeal / TEAL  
- **Frontend:** React.js  
- **Backend:** Node.js / Flask  
- **Wallet:** Pera Wallet  
- **Storage:** IPFS / Firebase  
- **Tools:** QR Code Generator  

---

## 💰 Estimated Cost
- Development Cost: Minimal  
- Blockchain Cost: Low (Algorand Testnet)  
- Hosting: Free/Low-cost (Vercel/Firebase)  

---

## 🔮 Future Scope
- Integration with universities and institutions  
- Mobile application support  
- Global credential verification system  
- AI-based fraud detection  

---

## 📷 MVP (Prototype)
- Certificate upload interface  
- Student dashboard  
- QR-based verification  

---

## 📎 Links
- GitHub Repository: 
- MVP Link: Prototype under development  

---

## 📌 Status
Hackathon Prototype (In Progress)
