#  IT Support Copilot Automation Agent

This project is a Tier-1 IT Support automation solution built using **Microsoft Copilot Studio**. It leverages **Retrieval-Augmented Generation (RAG)** to provide real-time solutions from internal documentation and automates ticket triage.

##  Live Demo
You can interact with the agent here:

https://m365.cloud.microsoft/chat/?titleId=T_3faac9b8-6473-b8b5-7cbf-bd81f7cecfcf&source=embedded-builder

---

##  Standard Operating Procedures (Internal Knowledge)
The agent is trained on the following SOPs to ensure company-approved troubleshooting:

### 1. Account & Password Security
* **Objective:** Securely reset user credentials.
* **Process:** Verify identity via manager -> Access Entra ID -> Issue temporary password -> Force reset on next login.

### 2. Network Connectivity Troubleshooting
* **Objective:** Resolve Wi-Fi and VPN drops.
* **Process:** Toggle hardware Wi-Fi switch -> Forget and Rejoin "Corporate_Secure" -> Check DNS settings -> Escalate to Network Team if site-wide.

### 3. PC Performance & Optimization
* **Objective:** Fix "Slow Computer" complaints.
* **Process:** Check Task Manager for high-resource apps -> Run Disk Cleanup -> Check for pending Windows Updates -> Verify RAM utilization.

### 4. VPN Configuration Guide
* **Objective:** Ensure secure remote access.
* **Process:** Verify GlobalProtect/Cisco status -> Check internet stability -> Validate MFA token -> Reinstall VPN profile if corrupted.

### 5. Printer & Hardware Setup
* **Objective:** Map corporate printers and resolve paper jams.
* **Process:** Verify IP address -> Check Print Spooler service -> Install latest manufacturer drivers -> Test print page.

---

## Technical Architecture
* **Platform:** Microsoft Copilot Studio
* **Data Storage:** SharePoint Online (SOP Library)
* **Logic:** Conditional Branching & AI-Interpretation
* **Style:** Monochromatic Tech Aesthetic (Charcoal & Electric Blue)

##  Project Structure
* `/docs` - Contains full PDF versions of SOPs.
* `/flowcharts` - Logic diagrams for troubleshooting paths.
* `/screenshots` - Agent interface and logic nodes.


##  Project Documentation & Knowledge Base
The intelligence of this Copilot is driven by a structured library of Standard Operating Procedures (SOPs). These documents are indexed for **RAG (Retrieval-Augmented Generation)**, allowing the agent to provide accurate, document-backed support.

| Document Title | Type | Description |
| :--- | :---: | :--- |
https://acrobat.adobe.com/id/urn:aaid:sc:EU:612a03a6-edcf-4947-9a4b-6a285dc92075| PDF/MD | High-level overview of the agent's logic and system flow. |
https://acrobat.adobe.com/id/urn:aaid:sc:EU:2e02f386-73a8-4479-b515-12ef7f4e4ddc| SOP | Step-by-step security protocol for credential recovery. |
https://acrobat.adobe.com/id/urn:aaid:sc:EU:7888a129-1468-4ac4-abbb-0e4a683e0782| SOP | Diagnostic flow for Wi-Fi, VPN, and DNS connectivity. |
https://acrobat.adobe.com/id/urn:aaid:sc:EU:6c260f7d-bc9c-41cf-ba09-26ecc4859179| SOP | Procedures for resolving lag and high resource utilization. |
https://acrobat.adobe.com/id/urn:aaid:sc:EU:8f50138e-5474-4530-a1e7-d577cd9632f0| SOP | Setup and troubleshooting for corporate printers/scanners. |
https://acrobat.adobe.com/id/urn:aaid:sc:EU:4a2e225b-f3b8-43ca-a019-8b99b6c996d6| SOP | Multi-factor authentication enrollment and recovery steps. |

> **Note:** All SOP documents follow a standard technical writing format: Objective, Scope, Step-by-Step Instructions, and Escalation Path.
>
> "Analyze the user's issue and output a table with: Category (Hardware/Software/Network/Access), Priority (Low/Medium/High), Recommended Team, and a Brief Summary."

---

##  Core Workflows
1. **The Troubleshooting Assistant:** Guided menu for internet, PC speed, and login issues.
2. **The Knowledge Retrieval (RAG):** Natural language search through indexed SOPs.
3. **The Ticket Triage:** Automated classification of user input for helpdesk routing.

##  Core Workflows & Logic
Before a user ever speaks to a technician, the Copilot guides them through these engineered paths.

### Troubleshooting Flow: Slow Computer
<img width="738" height="556" alt="image" src="https://github.com/user-attachments/assets/d4842b7e-8d36-490c-9276-175d9c848654" />

<img width="817" height="543" alt="image" src="https://github.com/user-attachments/assets/1abd858e-faf2-40ce-8708-035f8d08b6ba" />

##  Potential Business Impact
* **30% Reduction** in manual Tier-1 ticket volume.
* **0s Response Time** for common troubleshooting queries.
* **24/7 Availability** for remote and global teams.

##  Conclusion
This project demonstrates the transition from traditional IT Support to **Intelligent Systems**. By automating the "low-hanging fruit" of technical support, organizations can allow their technical talent to focus on high-level infrastructure and security.


