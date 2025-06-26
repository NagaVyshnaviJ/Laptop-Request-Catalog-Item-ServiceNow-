# 💻 ServiceNow Laptop Request Catalog Item

This project is a ServiceNow Catalog Item called **Laptop Request**, built on a PDI (Personal Developer Instance). It allows employees to request laptops with clear dynamic fields and guided form behavior.

---

## 🚀 Features

- Easy-to-use form with dynamic fields
- Option to request additional accessories
- UI Policies and Client Scripts to show/hide fields
- Modular code and reusable logic
- Fully exportable via Update Sets

---

## 📂 Project Structure

| Folder                  | Purpose |
|-------------------------|---------|
| `update_sets/`          | Contains exported XML of update sets |
| `client_scripts/`       | JavaScript logic for form behavior |
| `ui_policies/`          | Markdown description of UI policies |
| `catalog_item_config/`  | Configuration notes and variables list |
| `screenshots/`          | Screenshots of form and setup |

---

## 🧪 Variables Used

| Label                  | Type             | Name                     | Order |
|------------------------|------------------|---------------------------|--------|
| Laptop Model           | Single Line Text | `laptop_model`           | 100    |
| Justification          | Multi Line Text  | `justification`          | 200    |
| Additional Accessories | Checkbox         | `additional_accessories` | 300    |
| Accessories Details    | Multi Line Text  | `accessories_details`    | 400    |

---

## 🔁 Import Instructions

To test this project on your own PDI:

1. Go to **Retrieved Update Sets** in your ServiceNow instance.
2. Click **Import Update Set from XML**
3. Upload `update_sets/laptop_request_update_set.xml`
4. Preview and Commit the Update Set

---

## 👩‍💻 Team Members

- Vyshnavi Jayanthi – Developer & Designer
- Naga HarshaSree
- Nazeeb 

---

## 📸 Screenshots

!![WhatsApp Image 2025-06-21 at 10 01 58_944e2c71](https://github.com/user-attachments/assets/a444b9d6-5cad-4fae-8ac1-9aeed382fa4d)
![WhatsApp Image 2025-06-21 at 10 02 22_bcc7f91e](https://github.com/user-attachments/assets/dcb05afa-96f7-4ad6-8874-c75b0d2456da)
![WhatsApp Image 2025-06-21 at 10 03 16_160db76b](https://github.com/user-attachments/assets/8ba9b4c2-1345-4450-baf5-a58789a5f467)




---

## 📜 License

This is a sample project for learning purposes. Feel free to modify and use it in your own PDI!

