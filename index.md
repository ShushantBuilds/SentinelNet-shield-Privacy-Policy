**Effective Date:** August 24, 2026

## Introduction
This Privacy Policy governs the collection, handling, storage, and sharing of user data by the **SentinelNet Shield** Chrome Extension. 

**Single Purpose Statement:** SentinelNet Shield is designed exclusively to protect users during online shopping by analyzing transaction risks, evaluating checkout links for fraud, and providing an AI-driven webpage context assistant. All data collection and processing are strictly limited to providing and improving this single security purpose.

---

## 1. Data Collection
To provide real-time e-commerce protection, we request the narrowest Chrome permissions necessary (`activeTab`, `scripting`, `tabs`). We only collect data when you actively click on and interact with the extension. We collect:

* **Current Tab URLs:** We temporarily read the URL of your active tab to detect if you are on an e-commerce checkout page and to run domain fraud checks.
* **Website Content (DOM Text):** When you actively trigger a scan or ask the AI chatbot a question, we extract the visible text of that specific active tab to analyze merchant policies or potential scams.
* **User Input:** We collect the specific text prompts you type into the SentinelNet Shield safety chatbot.
* **Transaction Parameters:** We securely extract structural, non-identifying transaction data (such as scaled time, scaled amounts, and anonymized PCA vectors V1-V28) present on the page to calculate a mathematical risk probability.

*Note: We do not track, collect, or monitor your general Web History or background browsing activity.*

## 2. Data Handling (Usage)
Your data is handled strictly to operate the extension’s core security features. We use your data in the following ways:

* **Fraud Detection:** Transaction parameters and URLs are actively processed through our remote Random Forest machine learning model to generate an instant fraud risk percentage.
* **Contextual AI Assistance:** The active webpage’s text and your chat inputs are processed to generate personalized chatbot responses, purchase insights, and contract breakdowns.
* **Live Web Intelligence:** Checkout URLs are analyzed using live web scraping to verify merchant credibility and detect newly registered phishing links.

## 3. Data Storage
We adhere to strict data minimization and retention policies:

* **No Local Browser Storage:** This extension does not request or utilize the Chrome `storage` API permission. No data is stored locally on your device by the extension.
* **Ephemeral Processing:** Webpage content (DOM text) and transaction parameters are processed in real-time. They are discarded immediately after the AI response or risk score is generated and are **not** stored permanently on our servers.
* **Backend Storage:** User accounts, authentication states, and session preferences are securely stored on our dedicated, encrypted Django backend servers. 
* **Data Retention:** Your account data is retained only for as long as you maintain an active account with SentinelNet Shield.

## 4. Data Sharing
We do not process AI requests locally. To power our security features, we securely transmit necessary prompt data, specific webpage text, and URLs to the following verified third-party providers via encrypted HTTPS:

* **Google Gemini API:** Processes webpage text and user prompts to power the context-aware AI chatbot.
* **Mistral AI API:** Processes transaction context to generate AI-based purchase insights.
* **Tavily API:** Processes checkout URLs to perform live web scraping and verify merchant reputation.

Data is shared with these services solely to return the requested analytics to you.

## 5. Limited Use Disclosure & Prohibition of Sale
We completely prohibit the sale or misuse of user data. 

* **No Sale of Data:** We do not transfer, use, or sell your personal data to third parties, advertising platforms, data brokers, or information resellers. Your data is never used to determine credit-worthiness or for lending purposes.
* **Limited Use:** The extension's use and transfer of information received from Google APIs to any other app will adhere to the Chrome Web Store User Data Policy, including the Limited Use requirements.

## 6. User Access and Data Deletion
You have the right to access, correct, or delete your data at any time.

* **How to delete your data:** You may request the total deletion of your account and associated session data by emailing us at the contact address below. 
* Deleting your data will permanently remove your account and configuration preferences from our secure backend infrastructure.

## 7. Data Security
All data transmitted between your browser, our backend servers, and our third-party AI providers is encrypted in transit using industry-standard HTTPS/TLS. Our servers utilize encryption at rest to protect your authentication state and preferences.

---

## Contact Us
If you have any questions, concerns, or wish to submit a data deletion request, please contact the developer at:
* **Email:** shushant19102000@gmail.com
* **Website:** [https://www.shushant.me](https://www.shushant.me)
