Privacy Policy for SentinelNet Shield
Effective Date: 08/08/2026

1. Introduction
This Privacy Policy governs the collection, handling, storage, and sharing of user data by the SentinelNet Shield Chrome Extension. This document is designed to ensure complete transparency and compliance with the Google Chrome Web Store Developer Program Policies.

2. Single Purpose Statement
SentinelNet Shield is designed exclusively to protect users during online shopping by analyzing transaction risks, evaluating checkout links for fraud, and providing an AI-driven webpage context assistant. All data collection and processing are strictly limited to providing and improving this single purpose.

3. Data We Collect
To provide real-time e-commerce protection and contextual AI assistance, the extension requires access to the narrowest set of data necessary. We collect the following information:

  I. Website Content (DOM Text): When the AI chatbot is activated, we extract the visible text of the active tab to provide contextual answers.

  II. Web History and URLs: We inspect the URLs of the tabs you visit strictly to detect e-commerce checkout pages and perform live web scraping for fraud checks.

  III. User Activity (Chat Inputs): We collect the specific text prompts you type into the chatbot.

  IV. Transaction Parameters: We collect structural transaction data, such as scaled time, scaled amounts, and anonymized PCA vectors (V1-V28), to calculate risk        probability scores.

4. How We Use Your Data
We always state the reasons for which we collect a user's information and limit its use to our core functionality.

  I. Fraud Detection: Transaction parameters are processed through our Random Forest machine learning model to generate an instant fraud risk percentage.

  II. AI Context & Insights: Webpage content and user prompts are used to generate personalized chatbot responses, deep purchase insights, and contract breakdowns.

  III. Merchant Verification: Checkout URLs are analyzed using live web intelligence to verify merchant credibility and detect phishing.

5. Data Storage and Retention
We explain how long we store a user's data and how it is secured.

  I. Backend Storage: User accounts, session preferences, and authentication states are securely stored on our dedicated Django backend servers, not locally via        Chrome's storage API.

  II. Retention: Data sent to our backend APIs for real-time risk analysis is processed instantly. Account data is retained only for as long as you maintain an          active account with us.

6. Data Sharing and Third-Party Services
We comprehensively disclose all parties the user data will be shared with. To power our AI features and live web intelligence, we share necessary prompt data, webpage text, and URLs with the following third-party providers:

  I. Google Gemini: Used to power the context-aware AI chatbot.

  II. Mistral AI: Used to generate AI-based purchase insights and contract analysis.

  III. Tavily: Used for live web scraping and search analysis to verify merchant reputation.

These third-party providers process the data solely to return the requested analytics and chat responses.

7. No Sale of User Data
We explicitly state whether we sell information. We completely prohibit the sale of user data. We do not transfer, use, or sell your data to third parties, advertising platforms, data brokers, or information resellers. Furthermore, your data is never used to determine credit-worthiness or for lending purposes.

8. User Access and Data Deletion
Users can check the data we have collected from them and request its deletion. You may request to access, correct, or delete your account, session preferences, and associated data at any time. To initiate a data deletion request, please contact us using the information below. Deleting your data will remove your account from our Django backend and may limit your ability to use certain features of the extension.

9. Data Security
Sensitive or personal user information is transmitted over secure connections using HTTPS. Our Django backend handles your information in a secure fashion, utilizing encryption at rest to protect your authentication state and preferences.

10. Contact Us
If you have any questions or concerns regarding this Privacy Policy or wish to submit a data deletion request, please contact us at:

Email: shushant19102000@gmail.com
Website: www.shushant.me
