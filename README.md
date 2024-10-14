# SecureMessagingExtension
A chrome extension that uses AES-GCM encoding and a local encryption key encoded with PBKDF2 fixed salt.

To download and enable this extension:

FIRST
  Download and unzip package contents. Leave these in a folder and remember where it is.

SECOND
  Go to chrome://extensions
  Enable Developer Mode
  Click "Load Unpacked" and navigate to the unpacked zip folder. Select it.

You're Done! The extension is now operating on your device. To use the extension you need a plain text file called code.txt that you and your friends will share. code.txt must be 32 characters long and can include any uppercase, lowercase, numbers, and special characters. Spaces ' ' are NOT allowed. When you first click on the extension in your toolbar, select "Upload code.txt" and follow propmpts to upload your 32-character string file.
