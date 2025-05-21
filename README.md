# 🔍 Data Extension Search (Cloud Page Template for Salesforce Marketing Cloud)

**Created by [zentriQ](https://zentriq.io)** – Your experts for Salesforce Marketing Cloud.

This Cloud Page allows you to search Data Extensions by name within your Marketing Cloud instance and view:
- The Name
- The CustomerKey
- The Folder ID and full folder path
- A direct link to each Data Extension (in MC UI)

---

## 🚀 Live Preview

Feel free to test the tool in a secure environment:

👉 [Live Demo](https://your-cloud-page-url.cloud/page?auth_flg1=*aztt5Q482*Y) 
*(Includes basic password protection – see below for how to change it)*
*(Enter zentriq as DE Name to get results)*

---

## 📁 Files included

- `de_search_Page.html` – Complete Cloud Page code including AMPscript + SSJS + WSProxy usage
- Example search input + result table UI
- Auth logic (via query parameter) to limit access

---

## 🔐 Basic Security

This page includes a **simple password protection** using a query parameter.

```text
?auth_flg1=*aztt5Q482*Y
```

You can change the password on **line 16** of the AMPscript section:
```ampscript
SET @password = "*aztt5Q482*Y"
```

For production usage, we strongly recommend:
- Replacing this with IP whitelisting or login-based authentication
- Hiding Cloud Page URLs behind authenticated services

---

## ⚠️ Licensing & Usage

This tool is shared under the **Creative Commons BY-ND 4.0 license**:

- ✅ You may use, share, and implement the page
- ❌ You may **not** remove or alter the zentriQ logo or visual design without written permission
- ✅ Credit to [zentriQ](https://zentriq.io) must remain visible

**We encourage use and customization** – but please **respect the design and attribution**.  
If you’d like a custom version, feel free to [contact us](mailto:business@zentriq.de).

---

## ✨ Why we built this

At **zentriQ**, we believe in hands-on, smart solutions for Salesforce Marketing Cloud.  
This tool is part of our commitment to supporting the community with practical assets.

---

## 🛠 Need help?

Want to integrate this in your org securely or build on top of it?  
Reach out to us:

📧 business@zentriq.de  
🌐 [zentriq.io](https://zentriq.io)

---
