## Active Directory Domain Services Certificate Authority Notes and Setup

Notes:
- The job of a certificate authority is to assist in validating the identity of different websites and devices before administering digital certificates to them
- A certificate authority takes the user’s public key and information and then creates a digital certificate
- The certificate is signed by the CA with its private key
- The user can present the signed certificate to a server, who can then trust that the user is who they claim to be
- A Root CA is a certificate authority that can be used to issue other certificates

Free web certificate authorities:
- Let’s Encrypt
- ZeroSSL
- Cloudflare
- SSL for Free

Setup:
- Log into domain controller with administrator privileges
- Open Server Manager, click Manage, and select Add Roles and Features
- In Server Roles, select Active Directory Certificate Services
- Make sure Certification Authority and Certification Authority Web Enrollment are both checked
- Click next and install
- Open AD CS Configuration and click next
- Check the boxes for Certification Authority and Certification Authority Web Enrollment and click next
- Select Enterprise CA and click next
- Select Root CA and click next
- Select Create a new private key and click next
- Keep default options for the rest of the options and click Configure to finish