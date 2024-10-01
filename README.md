# dalo22
daloradius 2.2 instalacion debian12 por script y modificado

## Instalacion de daloradius, version instalable por medio de script 
```
apt install sudo -y

wget -qO - https://raw.githubusercontent.com/lirantal/daloradius/master/setup/install.sh | bash

git clone https://github.com/Fibored/dalo22.git
```


```
\mv /root/dalo22/radiusd.conf /etc/freeradius/3.0/radiusd.conf
\mv /root/dalo22/default /etc/freeradius/3.0/sites-enabled/default
\mv /root/dalo22/access_period.conf /etc/freeradius/3.0/mods-config/sql/counter/mysql/access_period.conf
\mv /root/dalo22/quotalimit.conf /etc/freeradius/3.0/mods-config/sql/counter/mysql/quotalimit.conf
\mv /root/dalo22/eap /etc/freeradius/3.0/mods-available/eap
\mv /root/dalo22/radutmp /etc/freeradius/3.0/mods-enabled/radutmp
```
\mv /root/dalo22/quotalimit.conf /etc/freeradius/3.0/mods-config/sql/counter/mysql/quotalimit.conf

