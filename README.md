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
- NagaHarshaSree  - Supporter
- Nazeeb - Supporter

---

## 📸 Screenshots

![WhatsApp Image 2025-06-21 at 10 01 58_d0e5b22d](https://github.com/user-attachments/assets/a9a46aba-45c1-4653-86e3-8d4911ecb74c)
![WhatsApp Image 2025-06-21 at 10 02 22_40b98fb1](https://github.com/user-attachments/assets/4dfc1bce-496c-4f72-8f4d-d46ddb3122bd)
![WhatsApp Image 2025-06-21 at 10 03 16_2f464229](https://github.com/user-attachments/assets/3959a12c-7b54-42e5-a2bc-d42d905c278f)




---

## 📜 License

This is a sample project for learning purposes. Feel free to modify and use it in your own PDI!

# Laptop-Request-Catalog-Item-ServiceNow-
