# 🧾 Project Raseed – AI-Powered Receipt Manager & Financial Assistant

Project Raseed is a smart, AI-driven personal assistant built to digitize, organize, and analyze receipts directly within Google Wallet. It helps users track expenses, categorize spending, receive reminders, and optimize financial decisions through a seamless mobile and web experience.

---

## 🚀 Features

- 📸 **Multimodal Receipt Ingestion**  
  Upload receipts via photo, video, or live stream. OCR + Gemini models extract line-item details in any language.

- 🧠 **AI-Powered Categorization & Insights**  
  Auto-categorizes expenses (Needs, Luxury, Subscriptions, etc.) and offers savings suggestions (Ghost Expenses, Trends).

- 🛍️ **Smart Grocery & Shopping Lists**  
  Generates frequently bought items and shopping suggestions based on past receipts.

- 🔔 **Intelligent Reminders**  
  - Return/replacement deadlines for e-commerce
  - Loan/premium/insurance due reminders
  - Subscription renewals

- 🧾 **IT Return Ready**  
  Lists eligible items for tax deductions at year-end.

- 💬 **Voice Assistant + Query Chatbot**  
  Ask in any language:  
  _“Do I have detergent for this week?”_,  
  _“How much did I spend on dining last month?”_

- 💼 **Google Wallet Passes**  
  Generate dynamic Wallet Passes for shopping lists, budget reports, tax documents, and expense summaries.

- 🔗 **Offline Receipt Sync**  
  Auto-upload receipts when internet connection is restored.

- 👥 **Group Expense Separation**  
  Ideal for managing shared expenses on trips, projects, and events.

---

## 🧰 Tech Stack

| Layer         | Technologies                                                                 |
|---------------|-------------------------------------------------------------------------------|
| **Frontend**  | React (Web), Flutter (Mobile)                                                |
| **Backend**   | Firebase Functions, Node.js (Cloud Run optional)                             |
| **AI/ML**     | Gemini 1.5 Pro, Vertex AI, Gemma                                              |
| **Storage**   | Firebase Storage                                                             |
| **Database**  | Firestore (NoSQL)                                                            |
| **Notifications** | Firebase Cloud Messaging (FCM), Cloud Scheduler                        |
| **APIs**      | Google Wallet API, Calendar API, Gmail API, Maps API                         |

---

## 🖥️ Screens & Mockups

- 📲 **Main Screen**: Upload receipts, view expense trends  
- 🧾 **Receipt View**: Line item breakdown  
- 💬 **Chatbot View**: Natural language queries  
- 📈 **Spending Dashboard**: Insights, ghost expenses, budget alerts  
- 💳 **Wallet Pass Generator**: Auto-create passes with item details

(*Mockups available in `/ui-mockups/` folder*)

---

## 🛠 Getting Started

### 📋 Prerequisites

- Node.js (v16+)
- Firebase CLI
- Flutter SDK (for mobile)
- Google Cloud Project with Wallet API enabled
- Vertex AI + Gemini API access

---

### 🔧 Setup

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/project-raseed.git
