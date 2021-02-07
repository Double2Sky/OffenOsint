##### OffenOsint Virtual Machine
##### Format .OVA / VirtualBox
##### About 11.3 Gb
This virtual machine image is intended for open source offensive reconnaissance. The iso image of the kali linux NetInstall operating system is taken as a basis. Other required packages were installed manually. The image includes the following packages.
+ Review:https://codeby.net/media/obzor-sborki-osint-dlja-razvedki-v-seti.173/
- Ver 1.0 https://drive.google.com/file/d/1TNskYu8AyXPTaE7twb4jdRRQQPprLUl5/view?usp=sharing osint / 22
- Ver 2.0 https://yadi.sk/d/rosAsOUMKodM9w root / 22
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
- macchanger
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
- Ghost recon
- Phoneinfoga
- Maryam
- Magma osint
- Cignotrack
- DNSkron
- Dork eye
- Vaile
- TiDos-Framework
- Red_Hawk
- InfoSploit
- Recon Spider
- Investigo
- WhatsMyName
## Other tools can be found in the ~ /OsintTools 
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
- Social-Analyzer
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

## Also pay attention to the aliases in ~ / .zshrc
- alias py = 'python'
- alias py3 = 'python3'
- alias uu = 'apt update && apt upgrade -y'
- alias apt = 'sudo apt'
- alias docker = 'sudo docker'
- alias docker-compose = 'sudo docker-compose'
- alias synaptic = 'sudo synaptic'

+ Login: osint
+ Password: 22
+ https://drive.google.com/file/d/1TNskYu8AyXPTaE7twb4jdRRQQPprLUl5/view?usp=sharing 

Machine update, tools added:
- OSINT-SAN.
- Parse Hub
- YaSeeker.
- Open Semantic Search. Containers already deployed, startup icon on top panel. Don't forget to start docker.service.
- Working from root
+ Login: root
+ Password: 22 
+ https://yadi.sk/d/rosAsOUMKodM9w
- Over 27 GB

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

	r3con1z3r -h
	raccoon -h
	arachnid -h
	gobuster -h
	gosint -h
	goca -h
	gospider -h
	lazygrandma -h
	maigret #nickname

	cd ~/OsintTools/53R3N17Y
	./serenity --help

	cd ~/OsintTools/deluxe
	python3 deluxe.py -h

	cd ~/OsintTools/FinalRecon
	python3 finalrecon.py -h

	cd ~/OsintTools/scriptnOsint
	./osint -h

	cd ~/OsintTools/snoop/
	snoop -h

	cd ~/OsintTools/sitedorks/
	python3 sitedorks.py -h

	cd ~/OsintTools/URLextractor/
	./extractor -H

	docker pull simplysecurity/simplyemail
	docker run --rm -ti simplysecurity/simplyemail -h

	cd ~/OsintTools/social-analyzer
	sudo docker build -t social-analyzer . && sudo docker run -p 9005:9005 -it social-analyzer

	export PORT=80
	docker pull searx/searx
	docker run --rm -d -v ${PWD}/searx:/etc/searx -p $PORT:8080 -e BASE_URL=http://localhost:$PORT/ searx/searx

	docker pull jas9reet/grawler
	docker run -d -p 8080:80 jas9reet/grawler

	cd ~/OsintTools/iKy
	docker-compose up --build
