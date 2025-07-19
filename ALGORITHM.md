# 📌 Algorithm: Gmail Account Creator using Python and Selenium

## 🎯 Objective:
To automate the process of creating a Gmail account using Selenium WebDriver in Python, designed for **educational and testing** purposes only.

---

## 🔄 Step-by-Step Algorithm:

### 🔹 Step 1: Open Gmail Signup Page
- 🌐 Launch browser using Selenium WebDriver (e.g., Chrome)
- 🔗 Navigate to: `https://accounts.google.com/signup`

---

### 🔹 Step 2: Fill Form Fields
- 📝 Enter **First Name**
- 📝 Enter **Last Name**
- 👤 Choose and enter a **Username**
- 🔐 Set **Password** and confirm it

---

### 🔹 Step 3: Handle CAPTCHA (Manual Step)
- ⚠️ CAPTCHA must be **solved manually** (not automatable)
- ⏸️ Script waits or pauses for user input

---

### 🔹 Step 4: Verify Phone Number
- 📱 Enter a **valid mobile number**
- 🔢 Enter the **OTP** received via SMS (manually)

---

### 🔹 Step 5: Provide Personal Information
- 📧 Enter **Recovery Email** *(optional)*
- 📅 Select **Date of Birth**
- 🚻 Choose **Gender**

---

### 🔹 Step 6: Accept Terms & Submit
- ✅ Accept **Terms and Conditions**
- 📨 Click **Create Account / Next** to proceed

---

### 🔹 Step 7: Login to Verify Account
- 🔐 Navigate to [Gmail Login](https://mail.google.com/)
- 🔑 Enter created credentials
- 🎉 Confirm successful account creation

---

## ⚠️ Notes:
- 🔒 CAPTCHA and OTP verification **cannot be bypassed programmatically** and require human input.
- ✅ This automation is intended **strictly for demo/testing purposes**.

