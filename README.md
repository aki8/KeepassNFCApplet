# KeepassNFC
## IMPORTANT
**This repository is used for class [PV204 Security Technologies at Masaryk University](https://is.muni.cz/auth/predmety/predmet?lang=en;setlang=en;pvysl=3141746). All meaningful improvements will be attempted to be pushed to upstream repository in June 2018.**

This readme file shall contain the elaborate description about the applet so that the user may get to know the applet to his best so as to promote the wide spread use and trust on this applet. The project is open domain therefore open to the security test and analysis alongwith reporting or modifications to patch, any security flaws, if exist. This aims for the most secure and trusted applet development in an evolved manner for the users. Hence, this project repository on the github. 

## Overview
KeepassNFC is a applet in javacard platform that it can protect the secret key of KeePass database . It was based on the project [smartcard_crypto_applet](https://github.com/nfd/smartcard_crypto_applet) and can be run on javacard platform with [JCRE](http://javacardos.com/wiki/index.php/home/index/index/model/jcre/app_name/JCRESpec01intro.html?ws=github&prj=KeepassNFC) version 2.2.x or above. KeePass is a famous software about password managerment .

KeePass is an open source password manager that aims to store passwords securely, enabling the user to keep all its sensitive password in KeePass encrypted database, which can be locked by a single Master Password (MP). Hence, the user is required to remember only that single password/key to unlock the database to retrieve his passwords and edit them.

##Compiling and Downloading
A project file(KeepassNFC.jcproj) has been created for the users of [JCIDE](http://www.javacardos.com/tools/index.html?ws=github&prj=KeepassNFC#JCIDE) .If you have already installed the [JCIDE](http://www.javacardos.com/tools/index.html?ws=github&prj=KeepassNFC#JCIDE) ,only a simple double-clicking on this file to start the development environment.
You can view ,edit,build or debug the code with [JCIDE](http://www.javacardos.com/tools/index.html?ws=github&prj=KeepassNFC#JCIDE) a powerful Javacard Integrated Development Environment.
You can use [pyApdutool](http://javacardos.com/tools/index.html?ws=github&prj=KeepassNFC#pyApduTool) to download and install the applet, please reference the [topic](http://javacardos.com/javacardforum/viewtopic.php?f=3&t=38&ws=github&prj=KeepassNFC) in the [JavaCardOS](http://javacardos.com/javacardforum/?ws=github&prj=KeepassNFC) for the operation detail. It should work on [JC30M48](http://www.javacardos.com/store/javacard-jc30m48cr.php?ws=github&prj=KeepassNFC) , the downloading and installation have been tested on this card.
