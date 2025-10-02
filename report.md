# Task 7: Identifying and Removing Suspicious Browser Extensions

### **Objective**
The objective of this task was to learn how to spot and remove potentially harmful browser extensions to improve browser security.

### **Tools Used**
* Google Chrome Web Browser

### **1. Audit Process**
I began by navigating to the Chrome extension manager (`chrome://extensions`) to review all installed extensions. For each extension, I evaluated its purpose and clicked "Details" to carefully inspect the permissions it requested and its site access level.

### **2. Findings and Actions Taken**

#### **"Before" State of Browser Extensions**
At the start of the audit, the following extensions were installed. This list served as the baseline for the security review.

* [Insert your "Before" screenshot here - like Screenshot (218).png]

#### **Permission Analysis of Key Extensions**
Several extensions required high-level permissions, which were analyzed for legitimacy:

* **AdBlock & MetaMask:** Both request permission to "Read and change all your data on all websites". For an ad blocker that needs to modify webpage content and a crypto wallet that needs to interact with dApps, these permissions are necessary for their core functionality. They are from reputable developers and were deemed safe.

* **Canvas downloader. Find and export.** This extension also requested to "read and change all your data on websites". This is potentially excessive for a tool that should only need to interact with the "Canvas" website. An extension with overly broad permissions can be a security risk.

* **Always active Window - Always Visible:** The utility of this extension was reviewed. Since it is not used frequently, it was identified as unnecessary. Unused extensions can become a security risk if they are abandoned by the developer and no longer receive security updates.

#### **Extensions Removed**
Based on the analysis, the following extensions were removed to improve security and reduce browser clutter:

* **Extension Name:** Canvas downloader. Find and export.
    * **Reason for Removal:** This extension was identified as having potentially excessive permissions. A more privacy-focused alternative could be sought if the functionality is required.

* **Extension Name:** Always active Window - Always Visible
    * **Reason for Removal:** This extension was identified as unnecessary and unused. Removing unused extensions is a key security best practice.

#### **"After" State of Browser Extensions**
After removing the identified extensions, the browser is more secure and less cluttered.

* **(IMPORTANT: Please remove the extensions listed above and take a final screenshot of your updated extension list to insert here)**

### **3. Research: How Malicious Extensions Cause Harm**
Browser extensions can pose significant security risks because they operate with a high level of privilege within the browser. Malicious extensions can:

* **Steal Data & Passwords:** They can log everything you type, including usernames, passwords, and credit card numbers.
* **Inject Adware:** Insert unwanted advertisements and pop-ups into the websites you visit.
* **Browser Hijacking:** Secretly change your default search engine or homepage to a malicious or ad-filled site.
* **Track Browsing History:** Record every website you visit and sell this data to third-party advertisers or malicious actors.

### **4. Conclusion and Best Practices**
This task highlighted the importance of regularly managing browser extensions to maintain security and privacy. Key best practices for safely installing and managing extensions include:

* **Install from Official Stores Only:** Only use the official Chrome Web Store or other trusted browser marketplaces.
* **Review Permissions Carefully:** Before installing, always check what permissions an extension is requesting[cite: 10]. Be suspicious of permissions that seem excessive for the extension's function.
* **Audit Regularly:** Periodically review your installed extensions and remove any you no longer use or recognize.