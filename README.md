# Stop Ubuntu From Asking for Your sudo Password

1. Launch a terminal window and enter the following command:

```bash
sudo visudo
```

2. The command prompt will ask for your password, enter it one last time.
3. The configuration file will open in a text editor, most likely nano, scroll down to the end of the document and add the following line:  

```bash
<user_name> ALL=(ALL) NOPASSWD: ALL
```
4. Save and Close. Done!!!
