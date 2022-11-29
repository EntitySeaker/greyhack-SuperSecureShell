# greyhack-SuperSecureShell
This program will allow users to have AES encryption for their servers.
This military grade encryption is used in real life and can not be cracked even by the most experienced players.

## How to use
1. Put encode.src on your server inside the /server directory.<br>

2. Edit decode.src and put your Encryption_key on line 340, compile decode.src to decode.bin on your server inside the /server directory.<br>

3. In the directory /server/conf on your server you will find a file called sshd.conf, open this file and set "encryption_enabled" to true.<br>

4. Edit ssh.src and put a different Encryption_key from step 2 on line 416, compile ssh.src to ssh on your host computer inside the /bin directory (replace if asked).<br>

5. To add a server to your server list simply type "ssh add IP_OF_THE_SERVER Encryption_key_from_step_2".<br>

6. Now you can connect to your server like you normally would through either ssh or Map.exe.
