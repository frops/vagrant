Vagrant
=======

Virtual machine for Yii2 shop boilerplate

####GET STARTED
* ```git clone git@github.com:SanderLi/vagrant.git```
* ```cd ./vagrant```
* ```mkdir sql```
* copy your shop.sql file into ./sql/shop.sql
* ```vagrant up```
* add to your hosts file (/etc/hosts)
``` 
192.168.56.101 shop.dev 
192.168.56.101 admin.shop.dev 
``` 


#### REQUIREMENTS
* Virtualbox (https://virtualbox.org)
* Vagrant (http://www.vagrantup.com/)



#### ABOUT
#####MySQL

Db host: localhost

| User | Password |
| ------------- | -----:|
| root   | root |
| yii2shop | boilerplate |

#####PHP

version: 5.5

