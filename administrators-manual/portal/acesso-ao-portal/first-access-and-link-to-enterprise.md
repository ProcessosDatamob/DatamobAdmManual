# First Access and Link to Enterprise

When the product **Datamob Enterprise** is activated for a company, the following tasks are performed by the system to enable the company's administrator user to access the Portal:

* Creation of credentials for the Administration Portal;
* Sending a welcome e-mail containing credentials and a link to access the Administration Portal.

To access the Administration Portal, follow the steps described in this section.

1. Go to \<EnderecoPorduto> to view the Portal access screen. Preferably use a Google Chrome browser with the most up-to-date version.
2. Fill in the "E-mail" and "Password" fields with the access credentials you received in the welcome e-mail.
3.  Enter the new password in the designated field.\
    As you type, the screen will display the rules the password must meet:

    * At least 1 uppercase letter (A-Z)
    * At least 1 lowercase letter (a-z)
    * At least 1 number (0-9)
    * At least 1 special character (such as !, @, #, $)
    * Must be between 8 and 30 characters long

    Each rule will be shown in green as it is fulfilled.
4. Click “Continue” to confirm the information and access the Portal.
5. After clicking Continue, you will be directed to the screen below, where you must enter the email and password set in the previous step:
6. In the next step, the user will need to confirm the company details. The company information confirmation screen will appear only on the first access and is shown in the figure below.
7. Confirm the Company Name and Email:
8. Create a password
9. Re-enter the password to confirm it
10. Check the box to agree to the Privacy Policy and Terms of Use
11. Click the "Next" button
12. The following screen will appear, prompting you to enter the Token that will be sent to the email provided:

{% hint style="info" %}
**NOTE**\
The confirmation email is an automated message and may be identified as spam by your email provider. If you haven't received it, please also check your spam folder.
{% endhint %}

If you haven't received the token by email, you can request it to be sent again by clicking on the "Resend code" option, located just above the "Confirm" button.

After this confirmation, the system will open the screen to "Create Administrator Account."

At this stage, a company-owned domain account will be requested to establish the link with Android Enterprise. By using a company-owned domain, the company can access advanced features of Google’s Better Together program in future versions. It is necessary to provide a company-owned domain account with Google Cloud Identity configured.

Example: @company.com

If the user provides a corporate email account containing Cloud Identity, the system will proceed with the normal flow. If the user provides an account without Cloud Identity configured, the following information will be displayed:

* **Sign up with a work email:** With this option, you can make another attempt to enter a corporate email (e.g., name@company.com) that has Google Cloud Identity configured. Click “Try again with a work email” to go back and enter a valid corporate email address.
* **Purchase a company domain:** If your company does not yet have its own domain (e.g., company.com) and a corresponding corporate email, you can acquire a new domain. Click “Purchase a domain” to be directed to a domain registration service, where you can buy a domain for your company and then use an associated email for registration.
* **Sign up for Android only:** If you plan to manage only Android devices, you can create a managed Google Play account suite using a personal email. Click “Sign up” to proceed with registration using a personal email, limiting management solely to Android devices.

{% hint style="info" %}
**NOTE**

It is important to highlight that Google does not accept GSuite accounts, so it is recommended to create a standard account for the company (e.g., companyname@google.com).
{% endhint %}

After selecting one of the three options above, follow the next steps to complete the Android Enterprise linking process.

On Google Play screen, use the "Sign In" button to log into the account, or, if you don't have an account, you can create a new one.

If you need to create a Google account, additional information will be requested on the "Contact Details" screen.

Read the Managed Google Play guidance information and enter the details of the company representative who will serve as the official data protection contact, as well as the representative for the European Union. Both fields can be completed with the same company contact. This information can be managed later in under the "Companies" menu, submenu "Company Information."

The "Contact Details" screen is shown below.

After confirming the details, the screen will display the message, "Congratulations! Your company has been successfully registered with Android Enterprise."

Click "Ok" to begin configuring the necessary settings to manage your company's devices.
