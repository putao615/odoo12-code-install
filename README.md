This cript is based on the install script from Yenthe666 (https://github.com/Yenthe666/InstallScript), I just has some modify for Odoo12. Which is only tested on Ubuntu16.04, but I think it is working well on 14.04 and 18.04.

Installation Steps:
1. Download the script.
sudo wget https://raw.githubusercontent.com/putao615/odoo12-install-script/12.0/odoo12-install.sh
2. Add run right to the script.
sudo chmod +x odoo12-install.sh
3. Execute the script and which will be finished automatically.
./odoo12-install.sh


TIPS: Due to chinese internet envirenment, I redirect LESS respository to a chinese address, please remove "--registry=https://registry.npm.taobao.org" and just keep "sudo npm install -g less" if you are not live in china.
sudo npm install -g less --registry=https://registry.npm.taobao.org
