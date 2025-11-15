This is "malicious" .desktop file based on the TTPs of APT36.

When opened, this file will do two things:
Create a decoy text file in /tmp and open it.
Once the decoy file is open, a reverse shell pointed to 127.0.0.1:4444

Once the reverse shell is closed, the decoy is removed to.
All important info is obfuscated using base64.

(The warning that KDE gives can be bypassed if the file has execute perms ;))

While you are free to do whatever you like with this, I must ask you to please do not modify this for malicious activites.
This was made with the intent to learn, not hurt or exploit.
