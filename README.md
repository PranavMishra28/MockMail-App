# MockMail - Kotlin Email Client

MockMail is a Kotlin-based email client designed to make email debugging easy and efficient. By integrating Mockmail's virtual SMTP server, developers can simulate email sending without actually delivering emails to their intended recipients. Instead, all outgoing emails are captured in a single virtual inbox, allowing for comprehensive testing and debugging.

## Features
- **Virtual SMTP Server Support**: Easily configure Mockmail’s virtual SMTP server to capture all outgoing emails in one inbox, regardless of the recipient.
- **Compose & Send**: Create and send emails within the app; all outgoing emails are routed to the virtual inbox.
- **Inbox & Sent Management**: View inbox and sent emails with organized lists, making debugging and tracking sent emails simple.
- **Drafts Support**: Save incomplete emails as drafts for later editing and sending.
- **Multiple Accounts**: Seamlessly switch between multiple email accounts.
- **Formatting Options**: Includes basic text formatting like bold, italic, and underline for message customization.

## Installation
1. Clone this repository:
   ```git clone https://github.com/yourusername/mckmail.git ```
2. Open the project in Android Studio.
3. Configure your virtual SMTP server credentials from Mockmail in the settings.
4. Build and run the app on an Android emulator or physical device.

## Usage
1. Login: Enter your email credentials and virtual SMTP server information to start.
2. Compose Email: Click "Compose" to create a new email. Emails sent will be routed to the virtual inbox, regardless of the recipient.
3. Manage Emails: Access inbox, sent emails, or drafts from the sidebar.
4. Debugging: Review all sent emails in the virtual inbox to test delivery and email content.
   
## Tech Stack
- Kotlin: Core programming language
- Android SDK: Base framework for the application
- Mockmail Integration: For virtual SMTP server and email debugging
- Material Design Components: Provides a clean, user-friendly UI
  
## License
This project is licensed under the MIT License.
