
# **TaxMate — Your AI-Powered Personal Tax Assistant**

Every year during tax season, most of us transform into detectives — digging through Gmail, scrolling through old WhatsApp threads, and opening ancient folders just to find that one missing Form 16.
Tax terms start sounding like spells (HRA! 80C! 80D!), deadlines pop out of nowhere, and one tiny mismatch is enough to receive a dramatic “We need to talk” email from the IT department.

It shouldn’t be this hard.
So, I built **TaxMate** — an AI-first, document-driven tax assistant designed to make the filing process effortless, accurate, and stress-free.

<img width="128" height="285" alt="Screenshot_1763632871" src="https://github.com/user-attachments/assets/59b20ad6-1604-4d22-8aa0-8749a8a0eb7f" />
<img width="128" height="285" alt="Screenshot_1763632889" src="https://github.com/user-attachments/assets/83441631-e662-4bec-bc3f-566a66285bfd" />
<img width="128" height="285" alt="Screenshot_1763632894" src="https://github.com/user-attachments/assets/2ce44e78-a269-4c01-86ea-f08e861d2f17" />
<img width="128" height="285" alt="Screenshot_1763632903" src="https://github.com/user-attachments/assets/30fe9af7-61b6-4187-93f9-32d93a662c45" />
<img width="128" height="285" alt="Screenshot_1763632912" src="https://github.com/user-attachments/assets/c401a9bc-afcd-4528-8a20-7586af3cdc3f" />
<img width="128" height="285" alt="Screenshot_1763632914" src="https://github.com/user-attachments/assets/6d2b7289-8f29-41be-98eb-5382487a93bf" />
<img width="128" height="285" alt="Screenshot_1763632919" src="https://github.com/user-attachments/assets/d612275d-b8ae-47fb-8460-cb4f40715d08" />

<br><br>

**Medium Blog:** [Link](https://medium.com/@samyuktha1262/taxmate-building-an-ai-powered-personal-tax-assistant-for-india-38b159e459d8)

---

# 🚀 **What Is TaxMate?**

TaxMate is an **AI-powered, mobile-first tax assistant** that reads your documents, builds your tax summary, tracks deadlines, and prepares your ITR draft — all without making you fill long, confusing forms.

It’s not just a tax app.
It’s your **personal tax partner**.

---

# ✨ **Key Features**

## 🧾 **AI Document Upload & Extraction**

Upload Form 16, payslips, 26AS, rent receipts, investment proofs, medical bills, donation receipts, capital gains statements, and more.
TaxMate extracts everything with Gemini 2.0 Flash + OCR:

* Income
* Deductions
* TDS
* Employer/PAN data
* Investments
* Tax credits

No manual entry. No errors.

---

## 📊 **Smart Tax Summary**

A clean, automatically built summary of:

* Income
* Section-wise deductions
* TDS
* Refund / Payable
* Old vs New regime comparison
* Document-wise breakdown

Exportable as a beautiful PDF.

---

## 💬 **Chat With Your Taxes**

A conversational AI assistant that actually understands your documents.

Ask:

* “Why is my refund lower this year?”
* “Am I eligible for HRA?”
* “What am I missing to complete my filing?”

Instant, context-aware, simple explanations.

---

## 📝 **Auto-Filing (ITR Draft)**

TaxMate prepares a ready-to-review ITR draft:

* Personal info
* Income details
* Deductions
* TDS summary
* Recommended ITR form

It also performs **consistency checks** (TDS mismatch, PAN errors, missing entries, etc.).

---

## 🔍 **Live Tax Insights & Health Score**

A dynamic insights feed that identifies:

* Savings opportunities (80C/80D/NPS/HRA)
* Risks (missing proofs, mismatches, undeclared income)
* Deadlines
* Smart alerts (critical within 3 days)

Plus a **100-point Tax Health Score**.

---

## 📅 **Deadline Reminders & Calendar Sync**

Automatically sync important dates:

* Advance tax
* Proof submission
* ITR filing
* Rent receipts
* Investment cut-offs

Stay compliant without trying.

---

## 📍 **Nearby CA Finder**

Using Google Places API, TaxMate helps you:

* Find Chartered Accountants around you
* View distance, ratings, contact info
* Share your tax summary instantly

When you need real human help, it’s one tap away.

---

## 📁 **Secure Document Vault**

Your entire tax life — neatly organized and stored securely:

* Upload
* View
* Delete
* Filter
* Preview PDFs

Backed by Firebase Storage & Firestore.

---

# 🧠 **How It Works — Architecture Overview**

TaxMate uses a modern AI + cloud architecture:
<img width="2319" height="1770" alt="mermaid-diagram-2025-11-20-152149" src="https://github.com/user-attachments/assets/313acea0-80dd-47ce-9be8-55cf7f7dd769" />


### **Frontend**

* Flutter (iOS + Android)

### **Backend**

* FastAPI (Python)
* PDF parsing (PyMuPDF)
* PDF generation (ReportLab)
* Image processing (Pillow)

### **AI Layer**

* Gemini 2.0 Flash (document analysis + chat)
* Google Vision OCR

### **Data Layer**

* Firebase Firestore
* Firebase Storage
* Firebase Auth + App Check

### **Integrations**

* Google Places API
* Device Calendar

---

# 🔥 **Why TaxMate Matters (Right Now)**

* India has **40M+ salaried filers** every year
* Government digitization is accelerating
* AI can now understand tax documents better than humans
* People want automation, simplicity, and clarity
* Existing tax apps still depend on manual entry

TaxMate is built for this moment — combining AI, usability, and compliance into one seamless experience.

---

