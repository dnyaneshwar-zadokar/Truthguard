🛡️ TruthGuard — Fake News Detection & Verification Tool
TruthGuard is an AI-powered web platform designed to detect and verify fake news & misinformation.
It analyzes content using Natural Language Processing (NLP) and Transformer-based models, and provides confidence/credibility insights, explainable outputs, and an enterprise-grade dashboard + admin panel.

✅ Infosys Springboard 6.0 Internship Project
👨‍💻 Created by: Dnyaneshwar Zadokar

🚀 Key Features
🔍 AI-Powered Content Analysis
Supports Text Analysis and URL Analysis
Detects misinformation and classifies content as:
✅ Reliable
⚠️ Suspicious
❌ Fake
Provides confidence score and credibility score
🧠 Explainable AI
Highlights suspicious words/phrases
Provides insights like:
Credibility score
Sensationalism score
Sentiment indicator
📊 Analytics Dashboard
Total analyses summary
Reliable/Suspicious/Fake counts
Classification distribution chart
Monthly trend chart
Recent analysis activity
🧑‍💼 Admin Panel (Enterprise Ready)
Manage system users (roles, status, logins)
Monitor all analyses in real-time
Advanced filters: classification, user, date range
Export analysis logs:
CSV
JSON
🤖 TruthBot Assistant
Interactive AI assistant for:
credibility explanation
misinformation awareness
report understanding
🧩 System Workflow
User → Preprocessing → NLP → Classifier → Claim Verification → Dashboard

🛠️ Technologies Used
✅ NLP
Tokenization
Stopword Removal
Lemmatization (spaCy, NLTK)
Named Entity Recognition (NER)
Dependency Parsing
✅ Machine Learning / Deep Learning
Transformer Models:
BERT
RoBERTa
DistilBERT
Fine-tuning for classification
✅ Fact Verification APIs
Google Fact Check Tools API
PolitiFact API
✅ Backend
Flask / FastAPI
JWT Authentication
Docker Deployment
✅ Database
SQL / NoSQL
📌 Modules Implemented
Authentication & Authorization (JWT, Role-based Access)
Content Input (Text / URL)
Preprocessing Pipeline
AI Detection Engine (Transformers)
Claim Verification Module
Explainability & Insights Layer
Report Generation
Dashboard + History Tracking
Admin Panel Management
🗄️ Database Schema (Simplified)
USERS → ANALYSES → ANALYSIS_RESULTS
ANALYSES → ENTITIES_EXTRACTED
ANALYSES → VERIFICATION_RESULTS
📸 Screenshots
Add screenshots in a folder named screenshots/ and update links below:

Module	Preview
Home Page	screenshots/home.png
Analyze Page	screenshots/analyze.png
User Dashboard	screenshots/dashboard.png
Analysis History	screenshots/history.png
Admin Dashboard	screenshots/admin-dashboard.png
Manage Users	screenshots/manage-users.png
⚙️ Installation & Setup
(Update this section based on your actual project setup.)

1️⃣ Clone the repo
git clone https://github.com//truthguard.git cd truthguard

2️⃣ Install dependencies

pip install -r requirements.txt 3️⃣ Run the application

python app.py ✅ Sample Output Input Text: “During the COVID-19 pandemic, numerous false claims spread…”

Output Result:

Classification: Suspicious

Confidence: 68.2%

Credibility Score: 4.5/10

Sentiment: -0.54

Verification: Partially matched with fact-check sources

Highlighted phrases:

“false claims spread”

“could be wiped out”

“kill coronavirus”

📈 Future Enhancements Browser extension for real-time verification

Social media monitoring integration

Multi-modal fake detection (image/video)

More low-resource language support

Continuous model retraining with live datasets

👨‍💻 Author Dnyaneshwar Zadokar 📌 Infosys Springboard 6.0 Internship Project
