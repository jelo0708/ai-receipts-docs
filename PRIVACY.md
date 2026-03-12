# Privacy Policy for AI Receipts to Excel

Your privacy is a core principle of "AI Receipts to Excel" App. We believe your financial data belongs to you. This policy explains how we handle your information.

## 1. Local Processing
When you use the Local Processing mode , all receipt processing happens **entirely on your device**.
*   Images are scanned using Apple's Vision framework natively on your iOS device.
*   Data extraction (dates, amounts, merchants) is performed locally.
*   We **do not** upload your receipt images or extracted data to any servers when using this mode.

## 2. AI Processing
If you choose to use Jarvis Mode for higher accuracy, the following applies:
*   The App sends your receipt image to our secure proxy server (managed via Cloudflare Workers). This is to ensure security in API usage.
*   The proxy forwards the image to Microsoft Azure Document Intelligence for advanced OCR.
*   The processed data is returned to your device so it can be structured into a spreadsheet for you.
*   **Data Retention:** Images are processed in-memory and are **not stored** on our servers or by Microsoft Azure after the extraction is complete.

## 3. Third-Party Services (Google Drive & OneDrive)
If you use the optional Import features:
*   **Google Drive:** The App uses the `drive.readonly` scope. This is used **only** to allow you to browse and select images/PDFs from your own drive. We do not access, store, or share any other files in your Google Drive.
*   **OneDrive:** Similar to Google Drive, access is limited to the selection of files for import.
*   **Credentials:** Your login credentials for these services are never seen or stored by us; they are handled securely by the respective platform's authentication systems.

## 4. Data Storage
All your collections and scanned receipts are stored in the App's **Documents** directory on your device. This data is visible to you in the Apple **Files** app. We do not have access to this data unless you explicitly choose to export it.

## 5. Feedback and Support
If you choose to send feedback within the App, your message and diagnostic logs are sent via a secure webhook to our support team. These logs contain code debug technical information but do not include your receipt images or financial data.

## 6. Contact Us
For any questions regarding this privacy policy, please contact us via the feedback tool within the App.
