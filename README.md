# MacOS Services

These are a collection of services for MacOS. To install, download the contents of each *.workflow from this repo. Then, copy the *.workflow file to your ~/Library/Services folder
e.g. `cp ~/Downloads/Decrypt\ file.workflow ~/Library/Services`

## Encrypt file.workflow
This will encrypt a selected file with a passphrase of your choosing using AES-256, once copied to your ~/Library/Services folder.
To use, right-click on a **file** (this will not work on folders) and choose "Encrypt file"
A pop-up dialoge will prompt for a passphrase (can be anything, just remember it), then create an encrypted file, appeneded with a .encrypted extension. This is for your information only and can be removed.

## Decrypt file.workflow
Does the opposite of the Encyrpt file.workflow.
To use, right-click on the file you wish to decrypt (using the encrypt workflow above), and click "Decrypt file"
A pop-up dialoge will prompt for the passphrase you chose earlier. The file will be decrypted and appeneded *.decrypted. This is for your information and the extension can be removed.

## Get Checksums.workflow
This will generate MD5, SHA, and SHA-256 checksums for a file.
To use, copy the install to your ~/Library/Services folder, then right-click on a **file** (will not work on folders), click "Get Checksums", and a pop-up dialogue will appear with the checksums.
