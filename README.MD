      PGP Key Manager Script


This script securely stores keywords by creating an encrypted PGP-like key file and also provides a way to decode Base64 encoded strings


1. How It Works
Input Keywords:

The script prompts you to enter up to three keywords. These keywords are securely embedded within the key file.
Generate a Secure Key File:

The script creates a secure key file named password.key, embedding your keywords in a PGP-like format, making it difficult for unauthorized users to extract the information.
Decode Base64 Strings:

The script includes a utility to decode Base64 encoded strings, allowing you to convert encoded data back into its original format.
Important Notes
Security of password.key:

The password_1.key file contains your encrypted keywords. It is crucial to store this file in a secure location, as anyone with access to it may potentially retrieve your keywords if they can reverse-engineer the format.
Script Limitations:

While the script generates and stores encrypted data, it uses a simple PGP-like format intended for demonstration purposes. For truly secure encryption, consider using established cryptographic libraries and standards.
.
Run the Script:

open CMD/BASh command line and, Navigate to the Folder/Directory and paste the following command 
python app.py
Enter Your Keywords:

1. When prompted, input up to three keywords that you want to securely store.
Secure Key File Created:

2. The script generates password.key, storing your keywords in an encrypted format. Keep this file safe.
Decode Base64 Strings:

3. Enter Base64 encoded strings when prompted to decode them into plain text.



