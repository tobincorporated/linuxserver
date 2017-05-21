# Secure Linux Server Project

## Vitals
``` 
IP: http://34.209.129.75/
Ports available:
* SSH: 2200
* HTTP: 80
* NTP: 123
```
## Server Setup
No remote root access  
No remote password login. Users must use access key  
'grader' user created with the following properties:
* Password: 'grader'
* Superuser Priveleges
* Access Key (Included with submission)  

SSH port changed from 22 to 2200  
Timezone set to UTC  
Apache2 server running Zachary Tobin's Item Catalog Project with PostgreSQL  

## Software installed  
In addition to the software that was installed on server creation, the following software was installed:  
* Git
* Apache2
* WSGI 
* Python packages:  
  * pip  
  * Flash  
  * SQLAlchemy  
  * Psycopg  
  * OAuth2 Client  

