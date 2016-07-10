Lets Encrypt automation with Systemd
=========

All details of the setup can you read in my blog post:
https://www.shivering-isles.com/lets-encrypt-renew-all-your-certs-using-systemd/

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Variabales:
* letsencrypt_email: The E-Mail you use to register your certificates
* letsencrypt_setup_path: The path where the certbot is installed to.
* letsencrypt_domains: The domains that are registered on setup.

License
-------

CC-BY
