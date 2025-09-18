# 🛡️ SafeScape – Smart Tourist Safety Monitoring & Incident Response System  

**Problem Statement ID:** SIH25002  
**Theme:** Travel & Tourism  
**PS Category:** Software  
**Team Name:** SafeScape  

---

## 📌 Overview  
**SafeScape** is a smart digital ecosystem that leverages **AI, Blockchain, and Geo-Fencing** to ensure real-time safety and incident response for tourists.  
It provides **secure tourist digital IDs, AI-driven anomaly detection, hybrid offline connectivity, predictive safety alerts, and authority dashboards** — ensuring quick response, trust, and peace of mind for travelers.  

---

## 🎯 Key Features  

### 🔐 Blockchain-based Digital Tourist ID  
- Tamper-proof blockchain ID issued at **airports, hotels, or check-posts**.  
- Includes **KYC (Aadhaar/Passport), itinerary, and emergency contacts**.  
- Valid only for the **trip duration**.  

### 📱 Tourist Mobile Application  
- **Panic Button** with live location sharing.  
- **Geo-fencing Alerts** for restricted/high-risk zones.  
- **AI-based Safety Score** auto-assigned (Random Forest model).  
- **Fallback AI Prediction** → if phone is switched off, shows last-seen + predicts probable movement route.  
- **Multilingual Support** (10+ Indian languages + English).  
- **AI Chatbot** for instant emergency guidance.  

### 🤖 AI-Based Anomaly Detection  
- Detects **sudden inactivity, deviation from itinerary, or unusual behavior**.  
- Generates predictive **risk maps and alerts** for authorities.  

### 🌐 Connectivity Layer (Hybrid Model)  
- **LoRaWAN** → long-range, low-power IoT communication in rural/forests.  
- **Wi-Fi Mesh** → tourists’ phones interconnect when network is weak.  
- **Bluetooth Mesh (basic fallback)** → short-range local communication.  

### 🖥️ Police & Tourism Dashboard  
- **Real-time heat maps** of tourist clusters.  
- **Role-based access** for Police, Tourism Dept., Hospitals.  
- **Priority alerts** ranked by severity (High = SOS, Medium = geofence, Low = info).  
- **Automated e-FIR generation** for missing cases.  
- **Blockchain-logged evidence** (location + timestamps).  

---

## 📊 Datasets Used  
- **NCRB Crime Data** – high-risk areas, past incidents.  
- **Tourism Dept. Records** – tourist volume & accident reports.  
- **Crowdsourced Data** – Google Maps APIs (accident-prone areas), Tripadvisor reviews.  
- **Synthetic Data** – generated for AI anomaly training.  

---

## ⚙️ Tech Stack  
- **Frontend**: Flutter  
- **Backend**: Firebase / Supabase  
- **Database**: Firebase / Supabase  
- **AI/ML**: Python (scikit-learn, TensorFlow), Random Forest, anomaly detection  
- **Blockchain**: Hyperledger / Polygon Edge (Digital ID + logs)  
- **Connectivity**: LoRaWAN, Wi-Fi Mesh, Bluetooth Mesh  

---

## 🛠️ System Process  
1. **Tourist Registration** → Blockchain-based ID generated.  
2. **Tourist Mobile App** → sends location, SOS alerts, anomaly signals.  
3. **Connectivity Layer** → data relayed via Mobile, LoRa, Wi-Fi Mesh, or Satellite SMS.  
4. **Cloud Server** → processes alerts + AI predictions.  
5. **Dashboard** → shows live clusters, heat maps, risk alerts.  
6. **Blockchain** → logs SOS, alerts, and FIR data securely.  

---

## 📅 Feasibility & Viability  

### ✅ Feasibility  
- Technically feasible with **AI, blockchain, and cloud infrastructure**.  
- Pilot deployment possible in **Northeast India, Himalayas, Goa**.  

### ✅ Viability  
- Supported by **Digital India & Smart Tourism initiatives**.  
- Can integrate with **Aadhaar & e-visa frameworks**.  
- Long-term savings via reduced crime, improved tourist trust.  

### ⚠️ Challenges (with Mitigation)  
- **Data Privacy** → End-to-end encryption + Blockchain logs.  
- **Blockchain Overhead** → Use permissioned blockchain.  
- **Tourist Adoption** → Gamified *Safety Badges* + insurance perks.  
- **Authority Training** → Simple UI + onboarding workshops.  

---

## 🌍 Impact & Benefits  
- **Enhanced Tourist Safety** → AI real-time monitoring + rapid alerts.  
- **Boost to Tourism Industry** → Safer destinations = more domestic & international visitors.  
- **Smarter Governance** → Transparent, tamper-proof, efficient tracking.  
- **National Benchmark** → Replicable **Smart Tourism Safety** model for India.  

---

## 👥 Team Roles  
- **Frontend Developer** → Mobile app + dashboard UI  
- **Backend Developer** → APIs + cloud integration  
- **AI/ML Engineer** → Anomaly detection, safety score  
- **Blockchain Developer** → Digital ID + logging  

---

## 📖 References  
1. Smart Tourist Safety with AI, Geo-Fencing & Blockchain ID  
2. ML-Based Geofencing for Movement Monitoring  
3. Role of AI & Blockchain in Sustainable Tourism  
4. Tourism Safety Monitoring with Blockchain  
