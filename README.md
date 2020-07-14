CoWFC Installer
======

This script installs the CoWFC front-end and back-end from https://github.com/EnergyCube/CoWFC

✅ Support Ubuntu 14.04 & 16.04

⚠️ Experimental script for Debian (! Only VM tested !)

🔨 Contributing
-------

Please open pull requests.

🔧 Error reporting
-------

Create a new issue and communicate all informations that you can.

📝 How to use
-------

### Phase 1
`mkdir /var/www ; cd /var/www && wget https://raw.githubusercontent.com/EnergyCube/cowfc_installer/master/cowfc.sh && chmod +x cowfc.sh && ./cowfc.sh`

or

-	`mkdir /var/www`
-	`cd /var/www`
-	`wget https://raw.githubusercontent.com/EnergyCube/cowfc_installer/master/cowfc.sh`
-	`chmod +x cowfc.sh`
-	`./cowfc.sh`

⚠️ (Not recommended) If you want to install the Debian experimental version, replace all cowfc.sh with cowfc-debian.sh

### Phase 2
After system reboot : `cd /var/www && ./cowfc.sh`

or

-	`cd /var/www`
-	`./cowfc.sh`

📖 Notes
-------

This script comes in 3 phases. Each phase involves a reboot
-	Add the PHP 7.1 repo (7.3 for Debian)
-	Continue CoWFC install
-	Reboot after CoWFC install

❤️ Credits
-------
kyle95wm
