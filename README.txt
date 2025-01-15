======================================================================
                         README.txt
======================================================================

Welcome to the collection of security-related tools. This suite contains 
several Python programs for encryption, password strength checking, 
keylogging, packet sniffing, and image encryption/decryption. These 
tools are intended for educational purposes and should only be used 
in ethical and legal environments where you have explicit permission 
to monitor or manipulate data.

The following programs are included:

1. **Caesar Cipher Program**
2. **Image Encryption and Decryption Program**
3. **Password Strength Checking Tool**
4. **Keylogger Program**
5. **Packet Sniffer Tool**

----------------------------------------------------------------------

                       Prerequisites
----------------------------------------------------------------------

Before running the programs, ensure you have the following libraries installed:

- **Pillow (PIL)** for image manipulation
- **NumPy** for numerical operations
- **Pynput** for capturing keyboard events
- **Scapy** for packet sniffing
- **Matplotlib** for graphical visualizations
- **re, os, sys, time** for various system operations

Install the necessary libraries via `pip`:

```bash
pip install Pillow numpy pynput scapy matplotlib
1. Caesar Cipher Program
Description: Encrypts and decrypts messages using a Caesar Cipher with a user-provided shift value.

Usage:

Run the program.
Choose 'e' for encryption or 'd' for decryption.
Input the message to encrypt or decrypt.
Provide a positive integer shift value.
The program will return the transformed message.
Dependencies:

Python 3.x
Warning:

The Caesar Cipher is a very basic encryption technique and should not be used for securing sensitive information. It is educational in nature and vulnerable to simple cryptanalysis.
-------------------------------------------------------------------------Sources:--------------------------------------------------------------
GitHub
Google

2. Image Encryption and Decryption Program
Description: Encrypts and decrypts images using an XOR operation with a key. It uses the Pillow library (PIL) and NumPy.

Usage:

Run the program.
Choose the operation (encrypt/decrypt).
Provide the image file (PNG format) and the encryption key (integer 0-255).
The result is saved as encrypted_image.png or decrypted_image.png.
Requirements:

Python 3.x
PIL (Pillow)
NumPy
Warning:

Image encryption using XOR is not secure for protecting sensitive data. XOR encryption is easily reversible and should only be used for educational purposes. It does not provide adequate protection for real-world scenarios.
Sources:

GitHub
Google
3. Password Strength Checking Tool
Description: This tool evaluates the strength of a password by checking several criteria and provides suggestions for improvement.

Usage:

Run the program.
Input a password to check its strength.
Select options to check strength, view suggestions, or examine complexity.
Criteria:

Length (minimum 8 characters)
Contains numbers, uppercase and lowercase letters
Contains special characters
Warning:

This tool is not foolproof and may not catch all weak passwords. It should not be relied upon as the sole security measure for password protection.
Sources:

GitHub
Google
4. Keylogger Program
Disclaimer: This program is designed for educational purposes and should only be used with explicit permission on systems you own or have consent to monitor.

Usage:

Accept the disclaimer to proceed.
Enter the duration for logging keystrokes.
The keystrokes are saved in a log file named keylogger_log.txt.
Menu options:

View log file path
Display log file contents in terminal
Learn about keylogger-related ethical and legal issues
Quit the program
Important Warning:

This program can capture sensitive data such as passwords. It should be used responsibly and only in ethical, legal environments. Unauthorized use can violate privacy laws and result in severe legal consequences.
Sources:

GitHub
Google
5. Packet Sniffer Tool
Description: Captures network packets based on specified protocols (TCP, UDP, or both). Displays and saves packet details in a text file. Allows for graphical analysis of captured data.

Usage:

Run the script.
Accept the disclaimer.
Choose the protocol and duration of sniffing.
Captured packets are saved in packet_sniffer_results.txt.
Dependencies:

Python 3.x
Scapy
Matplotlib
Warning:

This tool can capture sensitive network data, including passwords and other confidential information. Ensure you have explicit permission to capture packets on the network you are monitoring. Unauthorized packet sniffing can be illegal.
---------------------------------------------------------------------Sources:-----------------------------------------------------------
GitHub
Google


Important Notes:

Ensure you have explicit permission to use these tools on any system or network.
The use of these tools for malicious, unethical, or illegal activities is prohibited.
The author is not responsible for any damages or misuse of the tools.

Thank you for using these educational tools!

                         Author
----------------------------------------------------------------------

Created by: Gautham P Kini  
GitHub: https://github.com/Gautham0925  
LinkedIn: https://www.linkedin.com/in/gautham-p-k-62aa68291/

Acknowledgments:  
- **Pillow (PIL)** for image manipulation  
- **NumPy** for numerical operations  
- **Pynput** for capturing keyboard events  
- **Scapy** for packet sniffing  
- **Matplotlib** for graphical visualizations  
- **re, os, sys, time** for various system operations  

                      License
----------------------------------------------------------------------

This project is licensed under the MIT License.

Copyright (c) 2025 Alva's Institute of engineering and technology

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
