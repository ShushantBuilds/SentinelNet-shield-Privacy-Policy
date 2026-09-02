**Effective Date:** September 2, 2026

**Single Purpose Statement:** SentinelNet Shield provides AI-powered checkout protection against e-commerce fraud and phishing. It achieves this by analyzing transaction risks and providing a contextual AI assistant when explicitly invoked by the user. 

## 1. User Data Collection
In version 1.0.2, we have strictly limited our access by requesting only the `activeTab` and `scripting` permissions. We collect the following specific data types as defined by the Chrome Web Store:
*   **Website Content:** When you actively open the extension, we temporarily read the visible text (DOM) of your active checkout tab using the `activeTab` and `scripting` permissions to provide context for the AI.
*   **Authentication Information:** We collect the username and passcode you use to log into the extension.
*   **Personal Communications:** We collect the chat prompts you type into the AI chatbot.
*   **Transaction Parameters:** We collect anonymized structural page data (e.g., scaled time, amounts, PCA vectors).

*(Note: We no longer collect Web History or background tab URLs, as global host permissions and tab tracking have been removed.)*

## 2. User Data Handling
Your data is strictly handled to support our single purpose:
*   **Authentication Information** is used solely to log you into your SentinelNet Shield account.
*   **Website Content and Personal Communications** are processed through our AI providers to generate fraud warnings, contract breakdowns, and contextual answers.
*   **Transaction Parameters** are processed through our Random Forest ML model to calculate real-time fraud risk scores.

## 3. User Data Storage
We minimize data storage to protect your privacy:
*   **Backend Storage:** Authentication Information and user account preferences are securely stored on our encrypted Django backend servers. 
*   **No Local Chrome Storage:** We do not utilize the Chrome `storage` API to store data locally on your device.
*   **Ephemeral Processing:** Website Content, Personal Communications, and Transaction Parameters are processed in real-time and immediately discarded. They are never permanently stored on our servers.
*   **Retention:** Account data is retained only while you maintain an active account.

## 4. User Data Sharing
We do not process AI queries locally. To function, we share specific data with secure, verified third parties:
*   **Google Gemini API:** Receives Website Content and Personal Communications to power the chatbot.
*   **Mistral AI API:** Receives Website Content to generate purchase insights.
*   **Tavily API:** Receives the active page URL (only when the extension is manually invoked) for live merchant reputation scraping.

## 5. Limited Use and Prohibition of Sale
We do not sell, rent, or trade your data to third parties, advertising networks, or data brokers. The extension's use and transfer of information received from Google APIs to any other app will strictly adhere to the Chrome Web Store User Data Policy, including the Limited Use requirements.

## 6. Data Access and Deletion
You may request the total deletion of your account, Authentication Information, and associated preferences at any time. Deleting your data will permanently remove your account from our Django infrastructure. To request deletion, contact us using the details below.

## 7. Data Security
All data transmitted between your browser, our backend, and third-party APIs is encrypted using industry-standard HTTPS/TLS.

**Contact Us**
Email: shushant19102000@gmail.com
Website: https://www.shushant.me
