**Simple Password Manager**

This Python program serves as a basic password manager, its functionality is to allow users to store and retrieve passwords for their account. It employs the Fernet symmetric encryption algorithm from the `cryptography` library to encrypt and decrypt passwords.

### How to Use:

1. **Installation:**
   - Have Python in your system
   - Install the `cryptography` library if you haven't already with:
     pip install cryptography
    

2. **Running the Program:**
   - Clone or download the repository.
   - Open a terminal or command prompt and navigate to the directory containing the program files.
   - Run the program by executing the Python script:
     python password_manager.py

3. **Functionality:**
   - Upon running the program, you will be asked to enter a master password. This password is for encrypting and decrypting your stored passwords.
   - You have two main modes of operation: **view** and **add**.
     - **View:** Allows you to view all stored usernames and their corresponding decrypted passwords.
     - **Add:** Lets you add a new username and password pair to the storage. The password will be encrypted before being stored.

4. **Security:**
   - The program uses the Fernet symmetric encryption algorithm. IT IS NOT SAFE FOR USE!
   - Your master password is vital for decrypting your passwords.

