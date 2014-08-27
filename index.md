### 645 Broadway Systems Information

On this web is all the information and links to manage hardware and software associated with the equipment on the premises of 645 Broadway - Kebler/Yocom Residence.

Information on how to edit the content of this website is [here](edit.md)

-----------

### Equipment IPs and information

#### Wan

One can figure out the outside the WAN (outside) IP address for the network by visiting [this](http://whatismyipaddress.com/) website from within the network.   Since a static IP has not been bought it can possibly change but ** as of 8/2014 it is 208.100.170.115 **.  A change in this address would require a change in all links in the remotelogins.md page.   

####  Advanced IP scanner

Installed on the Master is a program Advanced IP Scanner which will find active devices on the network.   This is the output from [ipscanner](iplist.html) as on 8-2014

#### Usernames and Passwords

The usernames and passwords for all logins of the system are securely stored in the dgk-rsk.kdbx keepass database which is autoopened from either Richard's or David's personal databases.  The password to open this database can be found there if need be (shouldn't need to know it unless you are trying to open it directly from the master).  Using keefox with firefox makes logging in automatic.

#### List of Equipment

IP address column links take to you local (192.168.0.x) logins.  See remote logins page for those equipment accessible from outside the house.   Links in the name column take you to a corresponding page of further detailed information.

| IPAddress (login)		     | Name (more info)          |  Desciption	| Location|
| ------------- |:--------------|:--------------|:--------------|	
| [192.168.0.1](http://192.168.0.1)| [Elf-Basement](elf-basement.md)      |Gateway Router- Cisco Valet|Basement|	
| [192.168.0.2](https://192.168.0.2) | [Master](master.md)      |Cloud Sever|Basement|		
| [192.168.0.2](https://192.168.0.2:6547)  | [UPS](master.md) |APC UPS Accessed via Master Port 6547 Sever|Basement|		
| 192.168.0.3   | [5000 LC](5000lc.md)      |Litetouch/Savant Lighting System - See notes for access|Basement|
| [192.168.0.5:3000](http://192.168.0.5:3000)   | [Tekmar](tekmar.md)      |House Radient Heating System|Basement|
| [192.168.0.6](http://192.168.0.6) | ELF-Studio |Wireless Access Point-Linksys EA4500|Studio|
| [192.168.0.7](http://192.168.0.7) | ELF-Main  |Wireless Access Point-Engenius ECB600 |Kitchen|
| [192.168.0.8](http://192.168.0.8) | ELF-Front |Wireless Access Point-Linksys SmartWifi -EA3500|Studio|
| [192.168.0.5:8081](http://192.168.0.5:8081)  | PowerStrip |Remote Access Power Strip - port 8081 |Rack|
| [192.168.0.13](http://192.168.0.13) | Printer |HP Envy 110 |Laundry Room|