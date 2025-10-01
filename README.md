# 🛒 InversionesJL22 – WooCommerce Customizations

Advanced WooCommerce customizations for invoice automation, QR-based workflows, and role-based store management.

---

## 🌍 Overview

This case study demonstrates how WooCommerce can be extended to meet specific business requirements. The project included:
- Custom invoice templates for thermal printers  
- QR-based order completion flow  
- Granular role-based permissions for actions and visibility  
- Exportable reports (PDF/Excel)  
- SKU auto-generation for new products  
- AJAX-based workflow updates and restrictions  

These enhancements improved security, efficiency, and operational control for a Colombian client’s WooCommerce store.

---

## ✨ Features

- 🧾 Custom invoice templates for 80mm thermal printers  
- 📊 Exportable order reports (PDF & Excel)  
- 🔐 Role-based restrictions (actions, visibility, transitions)  
- 📦 SKU auto-generator for new products  
- 📱 QR scanning → automatic order completion  
- 🚫 Restricted actions (no trash, limited state changes)  
- ⚡ AJAX-based workflow updates without page reload  

---

## 🛠 Tech Stack

- **Platform:** WordPress + WooCommerce  
- **Language:** PHP  
- **Reports:** WooCommerce PDF Invoices & Packing Slips (customized)  
- **Frontend:** HTML, CSS, JS (WordPress admin + templates)  
- **Export:** FPDF / Excel (WooCommerce integration)  

---

## 📂 Project Structure

```text
plugins/
 └── woocommerce-pdf-invoices-packing-slips
themes/
 └── woodmart-child/
     ├── templates/
     │   └── Factura80mm/   # Custom invoice template
     ├── functions.php
     ├── styles.css
     └── inc/
         ├── integrations/
         │   ├── enqueue.php
         │   ├── sku-generator.php
         │   └── yith.php
         ├── order/
         │   ├── change-shipping-method.php
         │   ├── custom-status.php
         │   └── transition-status.php
         ├── report/
         │   ├── html-shipping.php
         │   └── pdf-shipping.php
         └── roles/
             ├── config.php
             └── order-visibility.php
```

---

## 📸 Showcase

_(Screenshots, GIFs, or demo videos will be added here)_

---

## 📖 Case Study

This project was delivered to a Colombian client requiring stricter control over WooCommerce orders and documents. By combining PDF invoice customization, QR code automation, and role-based restrictions, the store achieved a more secure and efficient workflow.

---

## 📈 Learnings & Insights

- WooCommerce can be deeply customized without modifying core files
- Role-based workflows significantly reduce operational errors
- QR code integration enables seamless real-time order handling

---

## 📜 License

This repository is provided for documentation and case study purposes only. No production code is included.
