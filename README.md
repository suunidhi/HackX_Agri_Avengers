# AgriDirect – Transparent QR-Verified Agri Marketplace

## Problem Statement
India’s agricultural sector faces persistent challenges including inefficiency, lack of transparency, and unfair value distribution.  
- Small and natural farmers earn less due to multiple intermediaries.  
- Consumers cannot verify the authenticity of organic produce.  
- There is limited traceability in the supply chain.  
- Poor market forecasting leads to high post-harvest wastage.  

**Example:**  
In Maharashtra’s Sangli district, turmeric farmers earn ₹90–161/kg in mandis, while the same product sells for ₹270–400/kg in retail markets — a 150–200% markup with no traceable verification.  

---

## Solution Overview
**AgriDirect** is an **AI-integrated, QR-based AgriTech marketplace** designed to connect verified natural farmers directly with consumers, ensuring complete transparency, trust, and fairness in the agricultural supply chain.

### Key Features
- **QR-Based Verification:**  
  Each verified farmer receives a unique QR code linked to certifications, cultivation details, and farm location. Consumers can scan the QR to view verified information and trace the entire farm-to-table journey.

- **AI-Driven Dynamic Pricing:**  
  Uses real-time AI algorithms to ensure equitable pricing for farmers and consumers, balancing market demand and supply.

- **Community Pre-Booking:**  
  Allows bulk or group orders directly from farmers, reducing wastage and stabilizing prices.

- **Secure Marketplace:**  
  Built with Node.js, Express.js, and MongoDB for encrypted, real-time transactions.

- **Smart Recommendations:**  
  AI-powered modules predict demand and suggest crops for optimal yield and market suitability.

- **Blockchain-Ready Framework:**  
  Designed for future integration of tamper-proof, end-to-end traceability.

**Vision:**  
To build a digitally empowered, transparent, and sustainable agricultural ecosystem that bridges the gap between natural farmers and conscious consumers.

---

## Tech Stack

| Component | Technology Used |
|------------|-----------------|
| **Frontend** | React.js, HTML5, CSS3, JavaScript |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB |
| **AI & Analytics** | Python, Flask (for dynamic pricing & recommendations) |
| **Authentication** | QR.js for code generation & verification |
| **Hosting / Cloud** | AWS / Render |
| **Version Control** | Git & GitHub |

---

## Installation Steps

### Prerequisites
- Node.js & npm installed  
- MongoDB running locally or on a cloud instance  
- Python (optional, if AI module is to be run locally)

### Steps
1. **Clone the repository:**
   ```bash
   git clone https://github.com/<your-username>/AgriDirect.git
   cd AgriDirect
2. **Install dependencies:**
   ```bash
   npm install


3. **Set up environment variables (.env):**
   ```bash
   MONGO_URI=your_mongodb_connection_string
   PORT=5000


4. **Run the backend server:**
   ```bash

   node server.js


5. **Run the frontend (if using React):**
   ```bash
   cd client
   npm start


6. **Access the application:**
   ```bash
   Visit http://localhost:3000

### Usage

1. Farmer Registration:
   Farmers register, upload certifications, and get verified using AI-backed validation.

2. QR Code Generation:
   A unique QR code is assigned, linking to verified farm data and product details.

3. Marketplace Access:
   Consumers scan the QR code to verify authenticity and purchase products directly from farmers.

4. AI Dynamic Pricing:
   Prices are automatically balanced using AI models to ensure fairness and prevent exploitation.

5. Community Pre-Booking:
   Enables consumers to collectively pre-order crops, reducing wastage and supporting farmers.

6. Future Scope:
   Blockchain integration for tamper-proof records, voice-based support for rural farmers, and multilingual accessibility.

### Screenshots
| Screenshot                                                                      | Description               |
| ------------------------------------------------------------------------------- | ------------------------- |
| ![Homepage](https://suunidhi.github.io/HackX_Agri_Avengers/public/image/homepage.png)              | AgriDirect Homepage       |
| ![Farmer Dashboard](https://suunidhi.github.io/HackX_Agri_Avengers/public/image/farmerdashboard.png) | Verified Farmer Dashboard |
| ![QR Verification](https://suunidhi.github.io/HackX_Agri_Avengers/public/image/qr-verification.png)         | QR Verification Page      |



### Team Details

**Team Name**: Agri_Avengers
**Institution**: MBIT, Gujarat
**Department**: Computer Engineering
**Faculty Mentor**: Prof. Sreeja P

| Name              | Role                        | Contact         |
| ----------------- | --------------------------- | --------------- |
| **Shikha Shah**   | Frontend & Integration      | +91 78029 19053 |
| **Khushi Rana**   | Backend & Database          | +91 91064 53981 |
| **Dhrupesh Rana** | AI Model & Cloud Deployment | +91 63551 30271 |

### Impact

**Economic**: Enhances farmer income by up to 40% through direct sales.

**Social**: Builds trust via transparency and QR-based verification.

**Environmental**: Reduces post-harvest waste by 20–30% using predictive analytics.

**Sustainability**: Aligns with SDGs 2 (Zero Hunger), 8 (Decent Work), and 12 (Responsible Consumption).

### References

1. Agrimp – Agri Marketplace Reference

2. KisanKonnect – Case Study on Farm-to-Consumer Models

3. ScienceDirect – AI in Agriculture Research Paper (2021)

4. ResearchGate – Indian Farmer, Middlemen and APMC Study

5. Times of India – Farmer Profit Margins (2024)


---

✅ **Next Steps in VS Code**
1. Create a new file: `README.md`
2. Paste the above Markdown text.
3. Save it.
4. Run:
   ```bash
   git add README.md
   git commit -m "Added detailed README with problem, solution, and setup"
   git push origin main