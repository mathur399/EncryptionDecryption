# EncryptionDecryption

1. Image Encryption/Decryption:
 ->The program allows users to select an image file via a file chooser dialog.
->Users input a numeric key, which is used to XOR each byte of the image data, effectively encrypting or decrypting the image.

2. User Interface:
 ->The application has a graphical user interface (GUI) with a button to open an image file and a text field to input the encryption/decryption key.
 ->When the button is clicked, the selected image file is processed with the provided key, and the result is saved back to the file.

3. Key Components:
 ->JFileChooser: To select the image file.
 ->JTextField: To input the encryption/decryption key.
 ->JButton: To trigger the encryption/decryption process.
 ->FileInputStream/FileOutputStream: To read and write the image file data.
