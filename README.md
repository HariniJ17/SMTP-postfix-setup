# SMTP Service Setup using Postfix & Mailx

This project demonstrates how to set up an SMTP service on a CentOS virtual machine using Postfix and Mailx.

🔰 Objective

To configure a basic email sending service on Linux that uses Gmail’s SMTP relay to send emails from the command line.

🧰 Tools Used

Postfix – Mail Transfer Agent (MTA)

Mailx / BSD-Mailx – Command-line email utility

CentOS – Linux distribution

Nano – For editing configuration files

Log tools – For monitoring mail logs

✅ Steps Followed


Installed all necessary packages for Postfix and Mailx.

Configured Postfix to use Gmail's SMTP server for sending emails.

Created a secure file to store SMTP credentials.

Updated the main Postfix configuration file.

Restarted the Postfix service to apply changes.

Sent test emails from the command line.

Verified successful mail delivery using system logs.

📌 Outcome

The SMTP service was successfully set up. Emails were sent from the VM to an external Gmail address using Postfix and Mailx with proper authentication and security settings.
