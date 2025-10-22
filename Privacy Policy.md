Privacy Policy for Facebook App Credential Wizard

Effective Date: October 22, 2025

This Privacy Policy explains how the Facebook App Credential Wizard (“the Tool”) collects, uses, and protects information during its operation.

1. Information Collected

The Tool may collect or temporarily handle the following information:

App Credentials: App ID, App Secret, and Redirect URI used to authenticate with Facebook.

Access Tokens: Obtained via OAuth to allow access to your Facebook app’s data.

Scope Permissions: Records of which Facebook permissions were granted or denied.

Important: The Tool does not collect or transmit any Facebook user personal data beyond what is authorized through the OAuth token. It does not store user passwords or other sensitive Facebook account information.

2. How Information is Used

The information collected is used solely to:

Facilitate OAuth authentication with Facebook.

Save credentials and access tokens locally for repeated use.

Track granted or denied permissions to inform the developer.

All data is stored locally on your machine in a JSON file (by default in src/auth/creds/fb.json). The Tool does not send credentials or tokens to any external servers.

3. Data Sharing

The Tool does not share your credentials, access tokens, or app data with any third party.

All stored information remains on your local device unless you choose to share it.

4. Security

Access tokens and credentials are stored with restricted file permissions to prevent unauthorized access.

No encryption beyond file permissions is applied, so keep your local machine secure.

Avoid sharing the credentials file or including it in public repositories.

5. User Responsibilities

By using the Tool, you agree to:

Only use it for Facebook apps that you own or have explicit permission to manage.

Keep your credentials secure and do not expose them publicly.

Ensure your use complies with Facebook Platform Policies.

6. Changes to This Policy

We may update this privacy policy from time to time. Users are encouraged to review this document periodically.

7. Contact

For questions regarding this Privacy Policy, you can contact the developer at:
[Your Email / GitHub Link]
