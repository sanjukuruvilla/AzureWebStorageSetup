# Azure Storage Setup for Static Website Deployment

This guide walks you through the process of configuring Azure Storage for hosting a static website.

## Overview

This repository contains step-by-step instructions for setting up Azure Storage to host a static website. By following these instructions, you'll be able to create a storage account, enable the static website feature, upload your website files, and configure the necessary settings for deployment.

## Table of Contents

1. [Prerequisites](#prerequisites)
2. [Setup Instructions](#setup-instructions)
3. [Usage](#usage)
4. [Contributing](#contributing)

## Prerequisites

Before you begin, ensure you have the following:

- Azure account with sufficient permissions to create storage accounts.
- Access to the Azure web portal.

## Setup Instructions

1. **Login to Azure Portal**:
   - Sign in to your Azure account using the Azure web portal.

2. **Navigate to Storage Accounts**:
   - Go to the Azure Storage Accounts service.

3. **Create a New Storage Account**:
   - Click "Storage accounts".
   - Click "Add" to create a new storage account.
   - Fill in the required details such as account name, resource group, location, etc.
   - Choose the "StorageV2" account kind and "General Purpose V2" performance.
   - Enable the "Static website" option under the "Settings" tab and specify the index and error documents.
   - Click "Review + create" and then "Create" to create the storage account.

4. **Wait for Deployment**:
   - Wait for the deployment to finish.

5. **Refresh and Go to Resource**:
   - Click "Refresh".
   - Click "Go to resource".

6. **Enable Static Website**:
   - Click "Static website".
   - Click "Enabled".

7. **Configure Website Settings**:
   - Once the storage account is created, navigate to it in the Azure portal.
   - Go to the "Static website" section under the "Settings" tab.
   - Note down the primary endpoint URL provided.
   - Upload your website files (including the index.html file) to the $web container within your storage account using Azure Storage Explorer or Azure CLI.

8. **Set Index Document**:
   - Click "Containers".
   - Click "$web".
   - Click "Upload" and upload your index.html file.
   - Click the "Index document name" field and type "index.html".
   - Click "Save".

9. **Access Your Website**:
   - Copy the Primary endpoint URL.
   - Switch to a new browser tab and paste the URL to access your website.

## Usage

Follow the provided instructions to configure Azure Storage for hosting your static website. Feel free to customize the website content and settings as needed.

## Contributing

Contributions to this repository are welcome! If you find issues or have suggestions for improvements, please open an issue or submit a pull request.
