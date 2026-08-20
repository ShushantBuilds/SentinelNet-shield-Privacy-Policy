# Privacy Policy for SentinelNet Shield

**Effective Date:** August 20, 2026

## Introduction and Single Purpose
This Privacy Policy governs the collection, handling, storage, and sharing of user data by the SentinelNet Shield Chrome Extension. 

**Single Purpose Statement:** SentinelNet Shield is designed exclusively to protect users during online shopping by analyzing transaction risks, evaluating checkout links for fraud, and providing an AI-driven webpage context assistant. All data collection and processing are strictly limited to providing and improving this single purpose.

## 1. Data Collection (What We Collect)
To provide real-time e-commerce protection, we request the narrowest permissions necessary (`activeTab`, `scripting`, `tabs`). We only collect data when you actively use the extension:
*   **Current Tab URLs:** We temporarily read the URL of your active tab to detect if you are on an e-commerce checkout page and to run fraud checks. We **do not** collect or track your general Web History.
*   **Website Content (DOM Text):** When you activate the AI chatbot, we extract the visible text of that specific active tab to provide contextual answers about merchant policies or potential scams.
*   **User Chat Inputs:** We collect the specific questions or prompts you type into the SentinelNet Shield chatbot.
*   **Transaction Parameters:** We collect structural, non-identifying transaction data (such as scaled time, scaled amounts, and anonymized PCA vectors V1-V28) present on the page to calculate risk probability.

## 2. Data Handling (How We Use Your Data)
Your data is handled strictly to operate the extension's core security features:
*   **Fraud Detection:** Transaction parameters and URLs are actively processed through our Random Forest machine learning model to generate an instant fraud risk percentage.
*   **Contextual AI Assistance:** The active webpage's text and your chat inputs are processed to generate personalized chatbot responses, deep purchase insights, and contract breakdowns.
*   **Live Web Intelligence:** Checkout URLs are analyzed using live search scraping to verify merchant credibility and detect unknown phishing links.

## 3. Data Storage and Retention
We handle your data with strict retention limits:
*   **Secure Backend Storage:** User accounts, authentication states, and session preferences are securely stored on our dedicated Django backend servers. We do not use Chrome's local storage API for this data.
*   **Ephemeral Processing:** Webpage content (DOM text) and transaction parameters are processed in real-time. They are discarded immediately after the AI response or risk score is generated and are **not** stored permanently on our servers.
*   **Data Retention:** Your account data is retained only for as long as you maintain an active account with SentinelNet Shield.

## 4. Data Sharing and Third-Party Services
We do not process AI requests locally. To power our features, we share necessary prompt data, specific webpage text, and URLs with the following secure third-party providers:
*   **Google Gemini:** Processes webpage text and user prompts to power the context-aware AI chatbot.
*   **Mistral AI:** Processes transaction context to generate AI-based purchase insights.
*   **Tavily:** Processes checkout URLs to perform live web scraping and verify merchant reputation.

*Data is shared with these services solely to return the requested analytics. We **do not** share your data for advertising, marketing, or tracking purposes.*

## 5. No Sale of User Data
We completely prohibit the sale of user data. We do not transfer, use, or sell your personal data to third parties, advertising platforms, data brokers, or information resellers. Your data is never used to determine credit-worthiness or for lending purposes.

## 6. User Access and Data Deletion
You have the right to access, correct, or delete your data at any time. 
*   **How to delete your data:** You may request the total deletion of your account and associated session data by emailing us at the contact address below. 
*   Deleting your data will permanently remove your account from our Django backend.

## 7. Data Security
All data transmitted between your browser, our Django backend, and our third-party AI providers is encrypted in transit using industry-standard HTTPS. Our servers utilize encryption at rest to protect your authentication state and preferences.

## Contact Us
If you have any questions, concerns, or wish to submit a data deletion request, please contact us at:
*   **Email:** shushant19102000@gmail.com
*   **Website:** https://www.shushant.me
