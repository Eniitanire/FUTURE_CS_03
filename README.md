FUTURE_CS_03: Secure File Sharing System </br>
 About the Task

In this project, I developed a Secure File Sharing System that allows users to upload and download files safely while ensuring data confidentiality, integrity, and proper key management. The system encrypts each file using AES-256 (Galois Counter Mode) before storage, and decrypts it securely when a user downloads it.
The aim was to simulate real-world data protection mechanisms used in sectors such as healthcare, legal, and enterprise environments, where sensitive data sharing requires strong encryption and controlled access.

## PROJECT WORKFLOW:
1. I created a Flask web portal for file upload and download.
2. I implemented AES-GCM encryption for file confidentiality and integrity protection.
3. I generated a unique 256-bit key per file and wrapped it using a system MASTER_KEY.
4. I stored encrypted files and wrapped keys securely in local storage and an SQLite database.
5. I tested end-to-end upload/download functionality to confirm successful encryption and decryption.
6. I added a styled front-end (HTML + CSS) for user interaction.

Skills Gained

-1. Data Encryption and Cryptography (AES-GCM) </br>
2. Web Application Development (Flask Framework) </br>
3. Secure Key Management </br>
4. Backend Integration and Testing </br>
5. Security Documentation and Architecture Design </br>

Tools used
Python (Flask Framework), Cryptography Library, SQLite Database, Visual Studio Code, Miniconda (for environment setup), and MS Word (for documentation).

