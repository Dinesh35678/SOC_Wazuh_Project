
# Wazuh Installation Guide 🚀

Welcome to the **Wazuh Installation Guide**! This repository provides a quick and simple method to install **Wazuh 4.9**, a powerful open-source security platform for threat detection, compliance management, and incident response.

## 📖 About Wazuh
Wazuh is a free, open-source platform that provides:
- Unified security monitoring for your environment.
- Compliance automation and reporting.
- Powerful intrusion detection and analysis capabilities.

---

## 🔧 Prerequisites

Before you start the installation process, ensure the following:

1. **Operating System**: Linux-based system (e.g., Ubuntu, CentOS, or Debian).
2. **Root Privileges**: The commands require administrative permissions.

---

## 🛠️ Installation Steps

### Step 1: Run the Wazuh Installation Script
To install Wazuh 4.9, simply execute the following command in your terminal:

```bash
curl -sO https://packages.wazuh.com/4.9/wazuh-install.sh && sudo bash ./wazuh-install.sh -a
```

This command:
- Downloads the official installation script for Wazuh 4.9.
- Installs all required components, including the Wazuh Manager, Filebeat, and Elastic Stack, to get Wazuh up and running.

### Step 2: Monitor the Installation
The script will handle everything automatically. Once completed, you'll see a success message confirming the installation.

---

## 📋 Post-Installation Checklist

1. **Access the Wazuh Dashboard**:
   - Open your browser and navigate to the Wazuh Dashboard URL provided in the installation output (usually `https://<server_ip>`).
   - Default credentials:  
     - Username: `admin`  
     - Password: (provided in the installation output)

2. **Connect Agents**:
   - Add agents to monitor endpoints in your environment.  
   - Follow the Wazuh documentation for [agent registration](https://documentation.wazuh.com/current/installation-guide/installing-wazuh-agent/index.html).

---

## 🌟 Features of Wazuh
- **Threat Detection**: Identify vulnerabilities, suspicious activities, and malware.
- **Compliance Monitoring**: Ensure compliance with regulatory standards like GDPR, HIPAA, and PCI DSS.
- **Log Management**: Centralize and analyze logs from various sources.
- **Security Analytics**: Perform deep analysis using the Elastic Stack.

---

## 📚 Documentation
For detailed guidance on configuring and using Wazuh, refer to the [official documentation](https://documentation.wazuh.com/current/index.html).

---

## 🤝 Contributing
If you encounter any issues or have suggestions for improvement, feel free to open an issue or submit a pull request. Contributions are welcome! 🙌

---

## ⚠️ Disclaimer
Make sure to review and configure Wazuh components according to your organization's security policies and requirements.

---

## 📧 Support
For additional support, join the [Wazuh Community](https://wazuh.com/community/) or contact the [Wazuh Team](https://wazuh.com/contact/).

---

Enjoy securing your environment with **Wazuh 4.9**! 🎉

