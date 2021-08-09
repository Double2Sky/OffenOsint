##### OffenOsint Virtual Machine
##### Format .OVA / VirtualBox
##### About 11.3 Gb / 27 Gb / 13,5 Gb
This virtual machine image is intended for open source offensive reconnaissance. The iso image of the kali linux NetInstall operating system is taken as a basis. Other required packages were installed manually. The image includes the following packages.
+ Review: https://codeby.net/media/obzor-sborki-osint-dlja-razvedki-v-seti.173/
+ On Xss.is: https://www.xss.is/threads/48937/
- Ver 1.0 https://bit.ly/3deMAg0 osint / 22
- Ver 2.0 https://bit.ly/3qxkQZE root / 22
- Ver 3.0 https://bit.ly/3A5vyKW root / 22
# From the native repository:
- dnsenum
- dnsmap
- dnsrecon
- nmap
- maltego
- netdiscover
- sslyze
- dmitry
- nikto
## Additionally installed is the Argos script https://github.com/SOsintOps/Argos which includes many useful tools for open source intelligence:
- Amass
- Sublist3r
- Photon
- TheHarvester
- Instalooter
- Instaloader
- ElasticSearch-Crawler
- Eyewhitness
- Httrack
- Metagoofil
- Recon-ng
- Sherlock
- Spiderfoot
- Twint
## The most powerful and efficient tools have shortcuts located on the vertical panel:
- badKarma
- GhostRecon
- Phoneinfoga
- Maryam
- MagmaOsint
- Cignotrack
- DNSkron
- Dork-eye
- TiDos-Framework
- Red_Hawk
- InfoSploit
- ReconSpider
- Investigo
- WhatsMyName
## Other tools:
- Serenity
- Buster
- deluxe
- Evine
- Fast Google Dork Scan
- FinalRecon
- Gasmask
- Ghunt
- Gobuster
- Goca
- Goohak
- Gorecon
- Gosint
- Holehe
- Iky
- Infoga
- LazyGrandma
- Lulzbuster
- Metaforge
- Mosint
- NameChk
- Nullinux
- Nullscan
- OneForAll
- OSINT_SPY
- OSIRA
- Pidrila
- ScriptnOsint
- Search4
- seosint
- SimplyEmail
- SiteBroker
- Sitedorks
- Snoop
/- Social-Analyzer
- Striker
- uDork
- URLextractor
- Vault
- wayback-machine-downloader
- waybackpack
- waybackurls
- WhatBreach
- WhatsMyName
- Zen
- The metasearch image searx is present.
## The following tools are additionally installed from the PyPi repository:
- R3con1z3r
- Raccoon-Scanner
- Arachnid-spider
## Instructions on how to run some of the tools, as well as tools that run in docker containers, can be found in the note on the desktop.
## Supporting tools:
- AutoVPN
- Anonsurf-GUI
- Google-earth
- Miro
- Gephi
- Aleph Data Desktop
- Visual Studio Code
- Dockstation
- Iridium-Browser - the panel has a set of related tabs
- Tor-Browser
## Terminals: Guake and QTerminal

## Also pay attention to the aliases in ~ /.zshrc
- alias py = 'python'
- alias py3 = 'python3'
- alias uu = 'apt update && apt upgrade -y'

+ Login: osint
+ Password: 22
+ https://drive.google.com/file/d/1TNskYu8AyXPTaE7twb4jdRRQQPprLUl5/view?usp=sharing 

Machine update, tools added (V2):
- OSINT-SAN.
- Parse Hub
- YaSeeker.
- Open Semantic Search. Containers already deployed, startup icon on top panel. Don't forget to start docker.service.
- Working from root

+ Login: root
+ Password: 22 
+ https://yadi.sk/d/rosAsOUMKodM9w
- Over 27 GB

Machine update, tools added (V3):
- Legion
- sn1per
- Reconftw
- WikiLeaker
- Spiderpig
- Gitleaks
- Getallurls
- Metasploit-Framework

+ Login: root
+ Password: 22 
+ https://drive.google.com/file/d/1st3tA6RsdhwlR8-DmuRTWYo4JCfQoUdJ/view?usp=sharing
- Over 13.5 Gb

For update some tools in terminal:
- # powerup

Run some tools In terminal:

	zen -h
	waybackurls #url
	whatbreach -h
	waybackpack -h 
	vault
	udork -h
	striker @domain#
	search4 -u #username
	oneforall #domain# run
	nullscan -H
	nullinux -h
	buster -e #email
	evine
	fgds #domain
	gasmask -h
	goohah #domain
	holehe -h
	infoga -h
	lulzbuster -s #url
	mosint -e #email
	namechk #username
	nicknamefinder
	seosint #domain
	osint -h
	snoop -h
	sitedorks -h
	wiki
	spiderpig
	reconftw

	r3con1z3r -h
	raccoon -h
	arachnid -h
	gobuster -h
	gosint -h
	goca -h
	gospider -h
	lazygrandma -h
	maigret #nickname

	cd ~/opt/53R3N17Y
	./serenity --help

	cd ~/opt/deluxe
	python3 deluxe.py -h

	cd ~/opt/FinalRecon
	python3 finalrecon.py -h

	cd ~/opt/scriptnOsint
	./osint -h

	cd ~/opt/snoop/
	snoop -h

	cd ~/opt/sitedorks/
	python3 sitedorks.py -h

	cd ~/opt/URLextractor/
	./extractor -H

	docker pull simplysecurity/simplyemail
	docker run --rm -ti simplysecurity/simplyemail -h

	cd ~/opt/social-analyzer
	sudo docker build -t social-analyzer . && sudo docker run -p 9005:9005 -it social-analyzer

	export PORT=80
	docker pull searx/searx
	docker run --rm -d -v ${PWD}/searx:/etc/searx -p $PORT:8080 -e BASE_URL=http://localhost:$PORT/ searx/searx

	docker pull jas9reet/grawler
	docker run -d -p 8080:80 jas9reet/grawler

	cd ~/opt/iKy
	docker-compose up --build
