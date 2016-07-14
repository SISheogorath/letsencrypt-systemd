Lets Encrypt automation with Systemd
=========

All details of the setup can you read in my blog post:
https://www.shivering-isles.com/lets-encrypt-renew-all-your-certs-using-systemd/

Important notice
----------------

This setup requires an already installed apache2 or nginx server.
So don't forget to setup apache2 or nginx along with this role.

Role Variables
--------------

All variables have a default value but `letsencrypt_email` and `letsencrypt_domains` are very important.

Variabales:
* letsencrypt_email: The E-Mail you use to register your certificates
* letsencrypt_setup_path: The path where the certbot is installed to.
* letsencrypt_domains: The domains that are registered on setup.

License
-------

CC-BY
