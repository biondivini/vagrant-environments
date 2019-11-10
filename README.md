# vagrant-environments
Some vagrant samples to setup development and test environments.
# MySQL
## Access and Security
### Assimetric keys
Generating public/private rsa key pair
$ ssh-keygen -t rsa
### Database
#### Database address
Change de configuration to
bind-address		= 0.0.0.0
#### Database user
user: dev
password: pass