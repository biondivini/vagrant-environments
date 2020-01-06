# vagrant-environments
Some vagrant samples to setup development and test environments.

bionic-mysql use just vagrant resources.

```
 _______________  
|               |  
| Ubuntu: MySql |  
|_______________|
```
bionic-php-mysql use vagrant, as well puppet (as configuration management) and ansible (as provisioner).
```
 _________________      _________________
|                 |    |                 |
| Ubuntu: Ansible | -->|  Ubuntu: MySQL  |
|_________________|    |_________________|
 ^ 
 | 
 | 
Windows:HOST
 |
 |
 v______________
|               |
| Ubuntu: PHP   |
|  + Puppet     |
|_______________|
```