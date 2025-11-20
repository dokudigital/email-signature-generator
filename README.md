# DOKU Email Signature Generator

A fully responsive, Bootstrap-based **Email Signature Generator** created for DOKU.  
This tool allows users to input their personal information (name, job title, country, phone number) and then instantly generate a compliant, cross-client HTML email signature that works reliably on **Gmail**, **Outlook**, and mobile devices.

The generator uses a clean white card UI, modern form fields, Bootstrap layout, and a fully table-based email signature template to ensure maximum compatibility across email clients.

---

## 🚀 Features

### ✔ Modern Bootstrap UI  
- Clean white card layout  
- Responsive form fields  
- Fully mobile-friendly interface  

### ✔ Email-Safe HTML Signature  
- 100% table-based layout for Gmail & Outlook  
- Inline-CSS for maximum compatibility  
- Full-width table technique to fix mobile column squeezing  
- Custom DOKU disclaimer section

### ✔ Multi-Country Support  
Auto-fills country-specific office information:

| Country | Prefix | City | Website |
|--------|--------|-------|----------|
| Indonesia | +62 | Jakarta | doku.com |
| Malaysia | +60 | Kuala Lumpur | doku.com.my |
| Singapore | +65 | Singapore | doku.com.sg |

Each country dynamically updates:
- Phone prefix  
- Office address  
- City name  
- Telephone info  
- Website link  

### ✔ Live Preview  
Users can see the rendered signature instantly before copying.

### ✔ Copy & Download  
- Copy HTML to clipboard  
- Download signature as `.html`

---

## 🧩 How It Works

1. User fills out:
   - Name  
   - Job title  
   - Country  
   - Phone number  

2. Script generates:
   - The table-based HTML signature  
   - Safe inline styles  
   - Responsive layout on mobile  

3. User can:
   - Copy HTML  
   - Download `.html`  
   - Copy final signature directly from Preview into Gmail/Outlook  

---

## 📁 Project Structure


---

## 🖼 Logo

The signature uses the hosted DOKU logo:
https://raw.githubusercontent.com/dokudigital/emailsignature/refs/heads/main/logo-signature.png

Width: **760px** (auto-scaled in signature)

---

## 🛠 Technologies Used

- HTML5
- Bootstrap 5.3
- Vanilla JavaScript
- Inline-CSS (email-client safe)
- Table-based HTML for email compatibility

---

## ▶ Usage

Open the generator in a browser: https://dokudigital.github.io/email-signature-generator/


Fill the form → Click **Generate** → Copy from Preview.

---

## 📱 Email Client Compatibility

| Email Client | Status |
|--------------|--------|
| Gmail Web | ✔ Fully supported |
| Gmail Mobile | ✔ Mobile responsive via full-width table trick |
| Outlook Desktop | ✔ Works with inline CSS |
| Outlook Mobile | ✔ Stable |
| Apple Mail | ✔ Supported |
| Yahoo Mail | ✔ Supported |

---

## 🧷 Notes

- Always copy from the **Preview area**, not from the HTML textarea.  
- Re-generate after changing country to refresh office information.  
- Do not paste raw HTML directly into Gmail rich-text editor—paste the visual preview instead.

---

## 📄 License

This project is provided for internal DOKU usage.  
Distribution outside the company should follow DOKU policies.

---

## ✨ Author

Marketing DOKU.

