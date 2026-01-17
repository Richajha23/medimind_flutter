# medimind_flutter
**MediMind** is a personal medical safety app that stores health history and uses AI to warn users about unsafe medicines, duplicate drugs, and allergy conflicts—without diagnosing or prescribing.

---

## 🧩 Problem It Solves

1. People forget past medicines  
2. Prescriptions get lost  
3. Duplicate medicines are taken unknowingly  
4. Allergy reactions due to missing history  
5. Dangerous drug interactions  
6. Emergency situations without medical info  
7. No clear next step after a warning  

---

## 1️⃣ Secure Authentication

**What it does:**  
- Login via phone/email OTP  

**Tech:**  
- Flutter UI  
- Firebase Authentication  

**Learn:**  
- OTP flows  
- Session handling  

---

## 2️⃣ Personal Health Profile

**What it stores:**  
- Allergies  
- Chronic conditions  
- Basic info (age, gender – optional)  

**Tech:**  
- Flutter forms  
- Firestore  

**Learn:**  
- Data validation  
- Firestore CRUD  

---

## 3️⃣ Medicine Vault

**What it does:**  
- Store current & past medicines  
- Manual entry  

**Tech:**  
- Flutter lists  
- Firestore collections  

**Learn:**  
- State management  
- Data modeling  

---

## 4️⃣ Prescription Upload

**What it does:**  
- Upload image/PDF  
- Extract medicine names  

**Tech:**  
- Firebase Storage  
- OCR (ML Kit / Cloud Vision)  

**Learn:**  
- File upload  
- OCR APIs  

---

## 5️⃣ AI Safety Warnings (KEY FEATURE)

**What AI does:**  
- Detect duplicate medicines  
- Detect allergy conflicts  
- Detect known interactions  

**What AI does NOT do:**  
- Diagnose  
- Prescribe  
- Suggest dosage  

**Tech:**  
- Rule-based logic  
- Drug interaction datasets  
- Cloud Functions  

**Learn:**  
- Basic NLP  
- Conditional logic  
- AI boundaries  

---

## 6️⃣ Emergency Medical Summary

**What it does:**  
- One-page medical info  
- Share via OTP or QR  

**Tech:**  
- Flutter UI  
- Secure sharing logic  

**Learn:**  
- Access control  
- Temporary tokens  

---

## ➕ Supporting Feature (Phase 2)

**Nearby Pharmacy Locator**  

**Why:**  
- Gives real-world next step after safety alert  

**When it appears:**  
- ONLY after safety alert  

**Tech:**  
- Geolocator  
- Google Maps Flutter  
- Google Places API  

**Learn:**  
- Location permissions  
- Map widgets  
- External APIs 

---

## 🛠️ Tech Stack (Final)

### 🧱 Frontend

**Flutter**  
- UI, State management, Forms, Navigation, Maps  

**Learn:**  
- Provider / Riverpod  
- Widget lifecycle  

### 🍎 Xcode Simulator

**Purpose:**  
- iOS testing only  

**You do NOT need to learn:**  
- Swift  
- iOS native dev  

### ☁️ Backend

**Firebase**  
- Authentication, Firestore, Storage, Cloud Functions  

**Learn:**  
- NoSQL schema design  
- Secure rules  
- Serverless logic  

### 🧠 AI (Controlled)

**What you need:**  
- OCR usage  
- Rule-based warnings  
- Simple text matching  

**What you don’t:**  
- Deep learning  
- Model training  
- Math-heavy ML  

### 🌐 APIs

- Google Places API (pharmacies)  
- OCR APIs  
- Optional drug interaction datasets  

---

## 🧪 MVP vs Phases

**MVP (Must build):**  
- Auth  
- Health profile  
- Medicine vault  
- Prescription OCR  
- Safety warnings  
- Emergency summary  

**Phase 2:**  
- Nearby pharmacy locator  

---

## 🎤 How to Explain MediMind (Interview Ready)

> “MediMind is a personal medical safety app that stores health history and uses AI to warn users about unsafe medicines, duplicate drugs, and allergy conflicts—without diagnosing or prescribing.”
