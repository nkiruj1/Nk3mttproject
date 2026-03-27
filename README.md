# Re-Route: AI-Powered E-Waste Management for Nigeria

## 🌍 Project Overview
**Re-Route** is a mobile-first web application designed to tackle Nigeria's e-waste crisis by connecting households, repair technicians, and municipal agencies through AI-powered waste identification and geospatial routing.

**Track:** Environment & Sustainability (E-Waste Focus)  
**Location Focus:** Nigeria (Lagos/Abuja Pilot)

---

## 🚨 The Problem

Nigeria generates **over 500,000 tonnes of e-waste annually**, with no formal recycling infrastructure.

### The Crisis
- Discarded electronics (phones, laptops, fridges) are processed informally in areas like **Alaba International** and **Olusosun**
- E-waste is burned to recover copper, releasing toxic **lead, mercury, and dioxins** into air and groundwater
- Citizens lack real-time data on disposal options, leading to "junk drawer" accumulation or illegal dumping

### The Gap
**"Friction of Action"**: Users want to dispose responsibly but don't know where to go or how.

---

## 👥 The Users

### 1. Household Users (B2C)
Urban Nigerians (18–40) seeking a **10-second solution** to declutter sustainably

### 2. The "Kaba-Kaba" Repair Economy (B2B)
Local technicians and vocational schools needing spare parts and training materials

### 3. Municipal Officers (Government)
Agencies like **LAWMA** and **NESREA** tracking waste hotspots and reducing landfill contamination

---

## 🛠️ Technical Architecture

### Tech Stack
- **Frontend:** React.js (mobile-first, optimized for low-bandwidth)
- **Backend:** Node.js with Express.js
- **Database:** PostgreSQL with PostGIS for geospatial queries
- **AI Service:** Google Vision API (Label Detection)
- **Hosting:** Cloud-agnostic (AWS/GCP ready)

### Data Flow
1. User takes a photo of e-waste
2. Image is compressed and sent to backend
3. Google Vision API categorizes the waste
4. PostGIS calculates the most carbon-efficient route to nearest collection point or repair hub
5. User receives an "action plan" in **under 2 seconds**

---

## 📊 Impact Analysis

### Environmental Impact
- **Every laptop diverted from landfill:** Saves 214 kg of CO₂ (equivalent to driving from Lagos to Maiduguri)
- **One smartphone battery diverted:** Protects 60,000 liters of groundwater
- **Annual potential:** Preventing 500,000 tonnes of toxic e-waste contamination

### Economic Impact
- Supports local "Green Jobs" by directing materials to informal repair sector
- Keeps resources within Nigerian borders
- Enables vocational training through material access

### Behavioral Impact
- Moves users from "passive dumping" to "active recycling"
- Real-time impact feedback drives engagement

---

## 🚀 Scalability Roadmap

### Phase 1: MVP (Current)
- AI waste identification via Google Vision API
- Geospatial mapping to verified collection points
- Mobile-first UI for low-bandwidth areas

### Phase 2: Incentives Integration
- **Green Credits System:** Users earn electricity units (IKEDC/EKEDC) or mobile data for successful recycling
- Gamification and leaderboards

### Phase 3: Offline AI Processing
- Migration to **TensorFlow Lite** for on-device AI
- Enables functionality in areas with poor 4G connectivity

### Phase 4: Global Expansion
- **White-Label Architecture:** Adaptable for any city by updating local "Waste Logic" database
- Partnerships with municipal authorities across Africa

---

## 🤖 AI & Tool Disclosure

- **Architecture & Brief:** Brainstormed and structured with Gemini AI
- **Development:** API integration logic and boilerplate code assisted by GitHub Copilot
- **Impact Statistics:** Derived from 2024–2026 climate manufacturing data

---

## 🔗 Quick Links

- **GitHub:** [nkiruj1/Nk3mttproject](https://github.com/nkiruj1/Nk3mttproject)
- canva : https://canva.link/b7a83t1j9ye7tu6
- **License:** MIT

---

## 📝 Contributing

We welcome contributions! Please feel free to submit pull requests or open issues for bug reports and feature requests.

---

**Let's build a sustainable future for Nigeria. One e-waste item at a time.** ♻️