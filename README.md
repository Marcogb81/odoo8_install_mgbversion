# odoo8_install_mgbversion

Hello,
This is a little subversion of script to install Odoo V8.0 in Ubuntu 14.04.

1. Install Virtual Box
2. Download Ubuntu 14.04
3. Install .ISO of Ubuntu in Virtual Box
4. End install the OS
5. Enter to OS
6. Received actualizations for Ubuntu
7. Not actualice to Ubuntu 16
8. Download Script
9. Open Terminal
10. Write " sudo sh Odoo_install.sh"
11. wait untill all be installed
12. Reset the OS
13. Open Firefox
14. go to: http://127.0.0.1:8069
15. Create data base
16. And from here you can install and manage modules or create your own modules

Don't worry, be happy.

Lil' tips by comand line in /opt/odoo/odoo-server$ :

a)  sudo /etc/init.d/odoo-server start

b)  sudo /etc/init.d/odoo-server stop

c) sudo reboot /etc/init.d/odoo-server  (good!)

When close automatically the administrators sessión just:

1) usr: admin

2) pswrd: password_of_db

How create your own module(muahahaha):

1) cd /opt/odoo/odoo-server

2) python odoo.py scaffold "module_name" /opt/odoo/modulos/

Explain:

1) scaffold : command who creates basic structure for Odoo's modules

2) "module_name" : name of the module, Ex. "Academy"

3) /opt/odoo/modulos/ : place where will create the structures of the module

4) especific example: sudo python odoo.py scaffold Academy /opt/odoo/modulos/
 
- In this part I recomend use two tools for work properly with archives:

- Bluefish editor for Linux

- SPE Stani's Python Editor for porperly Pythonic way for developing

- Do not give me the congrats, just pay my beers.

Long live and prosper!
