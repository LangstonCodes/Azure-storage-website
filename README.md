# Azure-storage-website

Watch me build this lab here! https://www.loom.com/share/ce80e91f9e64451cbbe404df2d6607e7

Create a storage website with Microsoft Azure

# 🚀 Azure Static Website Setup Guide

This guide walks you through creating and hosting a static website on **Azure Storage**.

---

## 1️⃣ Create a Storage Account

1. Log in to the [Azure Portal](https://portal.azure.com/)
2. Click **Create a resource**
3. <img width="1679" height="841" alt="Screenshot 2025-12-30 at 6 11 08 PM" src="https://github.com/user-attachments/assets/cfabbf25-5358-496a-9830-2af54e2fae92" />

4. Select **Storage account**
5. Choose your **subscription** and **resource group**
6. Enter a **unique storage account name**
7. Select a **region**
8. Leave default settings
9. Click **Review + Create**, then **Create**

---

## 2️⃣ Enable Static Website Hosting

1. Open your **storage account**
2. Select **Static website** from the left menu
3. Toggle **Enabled**
<img width="1680" height="840" alt="Screenshot 2025-12-30 at 6 41 21 PM" src="https://github.com/user-attachments/assets/7a980ae7-9c5a-4cfd-be88-f61870d47b96" />

5. Set the following:
   - 🏠 **Index document name:** `index.html`
   - ⚠️ **Error document path (optional):** `404.html`
   - <img width="1678" height="840" alt="Screenshot 2025-12-30 at 6 41 37 PM" src="https://github.com/user-attachments/assets/23a99c3b-b08e-45ac-b22b-f1a84bafb255" />

6. Click **Save changes**
7. Copy the **Primary endpoint URL** — this will be your live website URL

---

## 3️⃣ Create the Website File

1. Create a file named `index.html`
2. Add your HTML content
3. Save the file

---

## 4️⃣ Upload Files to Azure

1. Open **Containers**
2. Select the **$web** container
3. Upload your `index.html` file
4. <img width="1678" height="840" alt="Screenshot 2025-12-31 at 1 59 30 PM" src="https://github.com/user-attachments/assets/f1d76d9f-9cbb-4930-9a70-dd5cc7873a0a" />

5. Confirm the upload

---

## 5️⃣ View the Live Website 🌍

1. Go back to **Static website**
2. Open the **Primary endpoint URL**
3. Your website should now be live!
