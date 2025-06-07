🏥 Medico-Legal Record Management System (MLRMS)
A secure, intelligent, and scalable system to manage, summarize, and analyze medico-legal records using modern web technologies and AI.

📌 Overview
The  Medico-Legal Record Management System (MLRMS)  is designed to automate and secure the handling of sensitive medical and legal records. It supports role-based access, intelligent document classification, anomaly detection, and audit logging. This system is intended for hospitals, forensic departments, and legal-medical consultants.

🚀 Key Features
1. 🔐 Role-Based Access Control
  - Admin, Medical Officer, Legal Officer, Forensic Expert
  - Custom permission levels
2. 📁 Document Management
  - Upload `.pdf`, `.docx`, `.txt`, scanned documents
  - Auto-organized storage and metadata tagging
3. 🧠 AI Integration
  - Medical Relevance Detection  for uploaded text-based files
  -  AI-based Summarization  of lengthy medico-legal documents
  -  Anomaly Detection  in records using ML models
4.  🧾  Audit Logging 
  - Tracks actions: upload, delete, share, view
  - Ensures legal compliance and transparency
5.  🔗  Secure Sharing 
  - OTP and expiration-based access links

🛠️ Tech Stack
| Layer      | Technology                     |
|------------|--------------------------------|
| Frontend   | React Native                   |
| Backend    | Node.js + Express.js           |
| Database   | MySQL                          |
| AI Models  | TensorFlow / Keras / Scikit-learn |
| Authentication | JWT                        |

📂 Project Structure
medico-legal-record-management/
│
├── client/    React Native mobile app
├── server/    Node.js backend (APIs)
├── ml_models/    AI & ML models (summarization, anomaly, classifier)
├── database/    SQL schema and seed data
├── docs/    API usage guide and module explanation
└── README.md    Project documentation
🧪 How to Run the Project
     1. Clone the Repository
```bash
git clone https://github.com/your-username/medico-legal-record-management.git
cd medico-legal-record-management  
     2. Install Backend Dependencies
bash
Copy code
cd server
npm install
3. Run Backend Server
bash
Copy code
npm start
4. Install Frontend Dependencies
bash
Copy code
cd ../client
npm install
5. Start Frontend App
bash
Copy code
npm start
6. Setup Database
Import database/schema.sql into your MySQL server
Configure credentials in server/config/db.js

🤖 AI Modules
1.	Medical Relevance Classifier
2.	Accepts .txt, .pdf, .docx formats
3.	Filters non-medical records
4.	Summarization
5.	Uses NLP (BERT-based) to auto-summarize documents
6.	Anomaly Detection
7.	Highlights inconsistencies using Isolation Forest

📌 Use Cases
1.	Hospitals managing medico-legal cases
2.	Forensic departments
3.	Legal teams in medical institutions
4.	Healthcare data analytics & compliance

