
# 🚀 Azure AI Services Starter Project (Python)

![Azure](https://img.shields.io/badge/Azure-Cloud-blue) ![Python](https://img.shields.io/badge/Python-3.10+-green) ![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

> **Hands-on project using Azure AI Services and Python to build intelligent language detection apps.**

---

## 📚 Project Overview

In this project, you'll learn how to:

- ✅ Create an **Azure AI Services** resource
- ✅ Build a **Python** app for **language detection**
- ✅ Use both **REST APIs** and the **Azure SDK**
- ✅ Test your app with real user input
- ✅ Clean up your Azure resources

---

## 🛠️ Tech Stack

- **Python 3.10+**
- **Azure AI Services (Text Analytics)**
- **Azure SDK for Python**
- **REST APIs**
- **VS Code** (Recommended)

---

## 🧩 How to Run Locally
## 🚀 1. Clone the Repository

```bash
git clone https://github.com/MouryaSagar17/Azure-AI-Services---Beginner-Project.git
cd use-azure-ai-services/Python
```

⚙️ 2. Set Up Environment Variables
Create a .env file in the project root:
```env
AZURE_ENDPOINT=your-endpoint-here
AZURE_KEY=your-key-here
```
Or set them manually in your system.

📦 3. Install Dependencies
```bash
pip install azure-ai-textanalytics==5.3.0 
```

🏃 4. Run the App
Run with REST Client
```bash
python rest-client.py
```
# Type some word to find the language of the words shown in the sample ouputs

## SAMPLE OUTPUT
![SAMPLE OUTPUT](https://github.com/MouryaSagar17/Azure-AI-Services---Beginner-Project/blob/4871f2a53dc7398b051238824b2807bd520a1f89/use-azure-ai-services/outputs/rest-client-1.png) 

THE OUTPUT IS IN JSON FORMAT 
![SAMPLE OUTPUT2](https://github.com/MouryaSagar17/Azure-AI-Services---Beginner-Project/blob/main/use-azure-ai-services/outputs/rest-client-2.png?raw=true)

![SAMPLE OUTPUT3](https://github.com/MouryaSagar17/Azure-AI-Services---Beginner-Project/blob/main/use-azure-ai-services/outputs/rest-client-3.png?raw=true)


# Run with Azure SDK Client
```bash
python sdk-client.py
```
## SAMPLE OUTPUT
![SAMPLE OUTPUT1](https://github.com/MouryaSagar17/Azure-AI-Services---Beginner-Project/blob/main/use-azure-ai-services/outputs/sdk-client-1.png?raw=true)

# 🎯 Features
```bash 
🌎 Detects the language of user-entered text

🔐 Secure API calls using API keys

🛠️ Supports both direct REST API and Azure SDK usage

🖥️ Easy-to-use console interface for testing

🧹 Clean Up
```

After testing, delete your Azure resources to avoid extra charges:
```BASH
Go to the Azure Portal

Delete the resource group you created
```

# 📖 Learn More
```bash 
Azure AI Services Documentation

Azure Text Analytics API
```

# 🌟 Acknowledgements
Thanks to Microsoft Learn for providing the learning materials.

# 🚀 Final Note
This project gave me hands-on experience connecting Python apps to Azure AI Services quickly and effectively.
Looking forward to building more AI-powered apps! 💬✨

```yaml

---

✅ **I made it:**
- More clean
- Beautiful headings
- Emojis organized nicely
- Proper code blocks (`bash`, `env`)
- Hyperlinks where needed

---
```
