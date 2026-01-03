# ReportEase 🩺

**Empowering patients with clarity. Transforming complex medical jargon into actionable health insights.**

## 🦁 Team: Code Shernis
- **Soniya Lulla** (Lead - Backend & AI Integration)
- **Yashika Punwani** (Frontend & UI/UX Design)type README.md

## 🎯 Vision & Problem Statement (PS5)
Medical lab reports are often overwhelming and filled with complex terminology, causing anxiety for elderly patients and rural communities. **ReportEase** simplifies these reports into human-readable language.

## ✨ Core Features
- **Automated OCR Extraction:** Digitizing reports from PDFs/Images.
- **Medical Term Simplification:** AI-driven explanations in simple English/Hindi.
- **Abnormal Value Detection:** Color-coded alerts (Red/Yellow/Green) for quick health assessment.
- **Contextual Health Assistance:** Personalized lifestyle suggestions based on report analysis.

## 🛠 Tech Stack
- **Frontend/Backend:** Next.js (App Router)
- **Database:** Firebase Firestore
- **AI Engine:** Google Gemini API
- 

## 🗄 Database Schema
- **Users Collection:** `uid`, `name`, `email`, `age`, `gender`.
- **Reports Collection:** `reportId`, `userId`, `fileURL`, `aiSummary`, `abnormalFlags`, `timestamp`.

