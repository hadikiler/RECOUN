# 🌐 RECOUN

**RECOUN** is a project focused on hacking and security. It is designed to help gather useful information about a target before initiating any hacking activities.

---

## ✨ Features

This tool provides the following capabilities for a target website:

- 🔍 **Web Paths**: Enumerates all available web paths.
- 🌐 **Active Subdomains**: Identifies subdomains along with their IPs and ports.
- 📧 **Emails & Phone Numbers**: Extracts emails and phone numbers for each subdomain.
- 🖼️ **Website Screenshot**: Captures a screenshot of the target website, saved in the `files/gowitness` directory.
- 🛠️ **Website Technologies**: Displays information about the technologies used to build the site.
- 🗂️ **WHOIS Information**: Retrieves WHOIS details for the target website.

---

## ⚙️ Installation and Using

Follow these steps to set up the tool:

1. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
2. run the command with target url, enter the url without subdomain:
   ```bash
   python main.py --url example.com

