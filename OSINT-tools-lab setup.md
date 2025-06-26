sudo apt install git
sudo apt install python3-pip
sudo apt install snapd
sudo snap install cherrytree
sudo apt install terminator


	- Install brave browser -- very useful during private investigations over Internet (uses TOR)
		sudo apt install curl
		sudo curl -fsSLo /usr/share/keyrings/brave-browser-archive-keyring.gpg https://brave-browser-apt-release.s3.brave.com/brave-browser-archive-keyring.gpg
		echo "deb [signed-by=/usr/share/keyrings/brave-browser-archive-keyring.gpg] https://brave-browser-apt-release.s3.brave.com/ stable main"|sudo tee /etc/apt/sources.list.d/brave-browser-release.list
		sudo apt update
		sudo apt install brave-browser
		sudo brave-browser --no-sandbox

	- Install Macchanger -- 
		sudo macchange --random ens33
	

	- Migret Installation  -- for username search
		sudo python3 -m pip install maigret
		sudo miagret -a deepanshu --html
		
	- Twitter OSINT
		sudo python3 -m pip install waybacktweets   --- for deleted tweets
		https://intelx.io/tools?tab=twitter   -- basic twitter search
		https://privacywatch.app/
		
	- Sherlock -- username and email ID search for Social Media
		sudo python3 -m pip install sherlock-project
		
	- MetaDetective -- this is a web crawler -- really helpful when investigating the hate speeches, phishing, fake news, etc. 
		sudo apt install exiftool
		sudo python3 -m pip install MetaDetective

	- holehe -- email ID OSINT
		sudo python3 -m pip install holehe
		
	- audacity -- for audio OSINT (especially for digital forensics)
		sudo apt install audacity
		
	- onionshare -- to transfer files securely over internet
		install TOR browser
		use ubuntu-software → search onionshare → connect TOR
		
	- HTTTrack -- for completely copying the website -- very useful during investigations related to websites 
		sudo apt-get install webhttrack 
		open HTTPTrack
		
	- Keepassxc   -- for password storage
		https://keepassxc.org/download/#linux
		sudo add-apt-repository ppa:phoerious/keepassxc
		sudo apt update
		sudo apt install keepassxc
		
	- Spiderfoot -- complete OSINT package -- very very useful
		sudo git clone https://github.com/smicallef/spiderfoot.git
		sudo docker buld . -t spidertfoot
		sudo docker run --rm -d -p 5001:5001 --name spiderfoot spiderfoot
		
	- FIrefox plugins -- very critical 	
			- Wayback machine --- very critical for snapshots and look for archived pages, helpful during investigations.
					https://addons.mozilla.org/en-US/firefox/addon/wayback-machine_new/  
			
			- Video Download helper
				https://addons.mozilla.org/en-US/firefox/addon/video-downloadhelper/
				
			- Netcraft -- protection against phishing and malicious sites
				https://addons.mozilla.org/en-US/firefox/addon/netcraft-toolbar/
		
			- Multi account container - very useful plugin for sock puppets switch during investigations. As it provides a different container for each search tab.
				https://addons.mozilla.org/en-US/firefox/addon/multi-account-containers/
			
			- Resurrect pages -- very important to checked for the deleted pages, broken links, etc.
				https://addons.mozilla.org/en-US/firefox/addon/resurrect-pages/
				
			-  Screenshot 
				https://addons.mozilla.org/en-US/firefox/addon/screenshot-capture-annotate/
	 
			- Shodan
				https://addons.mozilla.org/en-US/firefox/addon/shodan-addon/
				
			- DNS Analytics
				https://addons.mozilla.org/en-US/firefox/addon/ip-address-and-domain-info/
			
			- User-Agent Switcher 
				https://addons.mozilla.org/en-US/firefox/addon/uaswitcher/
				
			- Search by image firefox plugin
				https://addons.mozilla.org/en-US/firefox/addon/search_by_image/

			- Instant Data scrapper  (only chrome or brave)
				https://chromewebstore.google.com/detail/instant-data-scraper/ofaokhiedipichpaobibbnahnkdoiiah
			

	- Some important websites 
		https://www.spydialer.com/
		https://intelx.io/
		https://haveibeenpwned.com/
		https://dehashed.com/
		https://publicrecords.searchsystems.net/
		https://whatsmyname.app/
		https://obsidian.md/download

		
	
