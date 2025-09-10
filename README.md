# 🔍 Accessibility Analyzer

A comprehensive **web accessibility analyzer** that helps developers identify and fix accessibility issues on websites and HTML content.  
Built with modern web technologies and powered by **axe-core** for industry-standard accessibility testing.

---

## ✨ Features

- **URL Analysis** – Analyze any website for accessibility issues  
- **HTML Analysis** – Test raw HTML content directly (no publishing required)  
- **WCAG Compliance** – Automated checks against **WCAG 2.1 AA standards**  
- **Detailed Reports** with:  
  - Compliance scores  
  - Issue severity breakdown  
  - Fix instructions + code examples  
  - WCAG reference mappings  
  - Estimated effort for fixes  
- **Visual Dashboard** – Interactive charts & statistics  
- **History Tracking** – Save and retrieve past analyses *(optional MongoDB integration)*  
- **Responsive Design** – Works on desktop, tablet, and mobile  

---

## 🛠️ Tech Stack

### Backend
- **Node.js** – Server runtime  
- **Express.js** – Web framework  
- **axe-core** – Accessibility engine  
- **JSDOM** – DOM parsing & manipulation  
- **MongoDB** *(optional)* – Persistent storage for history  
- **Mongoose** – MongoDB object modeling  

### Frontend
- **React** – UI library  
- **Custom Hooks** – State management & API integration  
- **Responsive CSS** – Mobile-first design  

---

## 🚀 Live Demo
- **Frontend**: [Your Frontend URL]  
- **Backend API**: [Your Render URL]  
- **API Health Check**: [Your Render URL]/api/health  

---

## 📋 Prerequisites
Make sure you have the following installed:
- **Node.js** `v16.0.0+`  
- **npm** `v8.0.0+`  
- **MongoDB** *(optional, required for history tracking)*  

---

## 📊 Features in Detail

### 🔗 URL Analysis
- Fetches HTML content from any public URL  
- Analyzes static HTML structure for accessibility issues  
- Provides detailed violation reports with fix suggestions  
- Generates WCAG 2.1 compliance scores  

### 📝 HTML Analysis
- Direct analysis of HTML fragments or full documents  
- Perfect for **development testing** before publishing  
- Real-time feedback on accessibility issues  

### 📈 Reporting Dashboard
- **Compliance Score** – Overall accessibility percentage  
- **Severity Breakdown** – Issues categorized by impact level  
- **Issue Distribution** – Problems grouped by category *(Visual, Navigation, Forms, ARIA)*  
- **Detailed Violations** – Each issue includes:  
  - Description & impact  
  - Affected user groups  
  - Step-by-step fix instructions  
  - Code examples  
  - WCAG reference links  

---

## 📦 Installation & Setup

```bash
# Clone repository
git clone https://github.com/yourusername/accessibility-analyzer.git
cd accessibility-analyzer

# Install dependencies
npm install

# Start backend
cd backend
npm start

# Start frontend
cd frontend
npm start
