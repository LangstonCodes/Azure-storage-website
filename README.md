# Azure-storage-website
Create a storage website with Microsoft Azure

# 🚀 Azure Static Website Setup Guide

This guide walks you through creating and hosting a static website on **Azure Storage**.

---

## 1️⃣ Create a Storage Account

1. Log in to the [Azure Portal](https://portal.azure.com/)
2. Click **Create a resource**
3. Select **Storage account**
4. Choose your **subscription** and **resource group**
5. Enter a **unique storage account name**
6. Select a **region**
7. Leave default settings
8. Click **Review + Create**, then **Create**

---

## 2️⃣ Enable Static Website Hosting

1. Open your **storage account**
2. Select **Static website** from the left menu
3. Toggle **Enabled**
4. Set the following:
   - 🏠 **Index document name:** `index.html`
   - ⚠️ **Error document path (optional):** `404.html`
5. Click **Save changes**
6. Copy the **Primary endpoint URL** — this will be your live website URL

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
4. Confirm the upload

---

## 5️⃣ View the Live Website 🌍

1. Go back to **Static website**
2. Open the **Primary endpoint URL**
3. Your website should now be live!
