I got a PEM file to an AWS server from an employer. 

Permissions 0664 for 'yourKey.pem' are too open.
It is required that your private key files are NOT accessible by others.
This private key will be ignored.
bad permissions: ignore key: yourKey.pem
Permission denied (publickey).

This is resolved with 

chmod 400 yourKey.pem

https://stackoverflow.com/a/9270753/45963
