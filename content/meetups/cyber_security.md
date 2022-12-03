---
title: "Meetup: Cyber Security, Safety, & Privacy"
date: "12/03/2022"
tags:
- security
- tech
- privacy
- data
- documents
---
# Define/Philosophy
## Security
* Encryption.
	* In transit: TLS, VPN, End to End.
	* At rest.
## Safety
- Use your devices, network and the internet without being exposed to bad actors.
## Privacy
- Data about your communications or behaviors belong to you.
- Metadata: HIV, Suicide, political email.
- https://www.youtube.com/watch?v=pcSlowAhvUk
## Cyber/Digital
- Data, communications and behaviour.

# Risks
- Data, Digital/Physical Assets. (Hackers/Scammers)
	- Passwords, bank accounts, digital assets.
		- Rainbow tables.
		- Brute force.
		- Hashing.
	- How can this be stolen/compromised?
		- Social engineering/Phishing.
		- Hacks, local and on services you have accounts with. Hashing.
		- Malware/Trojans.
- Privacy. (Corporate manipulation, Government)
	- Spying/Tracking.
		- ISP.
			- LTE.
			- Fiber/Cable.
			- WiFi
				- Open.
				- Secure.
				- MITM.
		- Carrier.
		- DNS.
		- Tracking services + AI.
			- Facebook example.
			- Abortion.
		- Foreign actors.
			- Eufy example.
				- https://privacytools.io/guides/eufy-security-camera-privacy-scandal
			- https://www.theverge.com/2022/11/25/23478132/fcc-china-huawei-zte-hikvision-camera-telecom-authorization-ban
	- Surveillance.
		- AIrtags.
			- Airguard.
			- Tracker Detect.
		- License plate readers.
		- Bluetooth MAC readers/scanning.
		- Gun shot detection.
		- Ring Cameras + LEO.
- Mobile devices
	- Location.
		- Towers/Trilateration.
		- Cell site simulators.
			- Encryption.
		- Bluetooth/WiFi.
			- Randomization.
			- WiFi scanning.
		- Mobile Advertising Indentifier
	- Spying on communication.
		- SMS/Calls.
	- Phone components and sensors.
		- GPS.
	- Malware.
		- Does turning your phone off work?
		- Cryptomining.
			- Compromised apps.
	- Faraday?

- Ransomware.

# Attack vectors
- Cloud file hosting.
	- Google Drive.
	- iCloud.
	- Microsoft OneDrive.
	- Dropbox.
	- Encrypted? (Search)
- SMS.
	- Carriers can read your messages.
	- Carriers store your messages.
	- Messages can be recovered if deleted.
	- Encryption.
- Messangers.
	- https://cybernews.com/news/whatsapp-data-leak/
- Trackers.
- Email (plain text)
	- Protonmail outside protonmail.
- Passwords
	- Weak.
	- Reused.
	- Passwordless.
	- Multifactor.
		- Know.
		- Have.
		- Are.

# Plan
- Protect what is likely?
- https://ssd.eff.org/module/your-security-plan
- https://ssd.eff.org/module/seven-steps-digital-security

# Defense
## Easy mode
- KISS.
- Yourself.
	- Backup, not copy.
- Keep your devices updated.
	- No updates?
	- 0-Day.
- Cloud hosting.
- Android Safety
	* App firewall.
		* https://netguard.me/
	* TrackerControl
		* https://trackercontrol.org/
- Use an anti-virus/anti-malware.
- Web Browsing
	- Use a safe browser like Brave.
		- Test yours here: 
	- Use HTTPSEverywhere.
		- TLS.
	- Use uBlockOrigin.
	- Use Privacy Badger.
- Search
	- Use DDG or Brave search.
- Social
	- Don't engage.
	- Use safe social networks.
	- Increase privacy as much as possible.
- Messaging
	- Don't use SMS, Whatsapp, Telegram.
	- Use Signal.
		- https://signal.org/bigbrother/central-california-grand-jury/
- Email
	- Use Protonmail or Fastmail.
- Passwords
	- Use a password manager.
		- Lastpass.
		- 1Password
		- KeePass
		- Bitwarden
	- Don't reuse your passwords.
	- Strong passwords.
		- https://ssd.eff.org/module/animated-overview-how-make-super-secure-password-using-dice
	- Security questions.
	- 2FA.
		- https://en.wikipedia.org/wiki/SIM_swap_scam
		- https://www.yubico.com/
	- Avoid using biometrics only.
- Behaviour.
	- Opening/answering email/calls/messages.
	- What if your bank calls you?
- IOT.
	- Use safe IOT devices.

## Advanced mode
- Cloud storage.
	- Self-hosted, group hosted.
- Device updates: Advanced.
	- https://ssd.eff.org/module/choosing-your-tools
* Web browsing
	* Use TOR network.
		* https://en.wikipedia.org/wiki/Tor_(network)
		* Privacy (not complete).
		* Protest, free speech, whistle-blowers, dark web.
		* Network protocol, original packet sender is TOR exit node vs. the sender.
* Messaging
	* Verify Signal key fingerprints.
	* Use Matrix/XMPP.
		* Element.
* End Point Security.
* Email
	* Use PGP. (Publickey)
		* https://en.wikipedia.org/wiki/Pretty_Good_Privacy
		* https://en.wikipedia.org/wiki/Public-key_cryptography
		* Sessionkey + Public & Private key.
		* Dilligence.
	* Drafts?
* Internet Access
	* VPN?
		* WIreguard.
		* Logging/Audit/becomes ISP?
		* What is VPN good for?
	* TOR browser.
* Device data safety
	* Full disk encryption.
* DNS
	* AdGuardHome.
	* PiHole.
	* Safe DNS.
		* https://one.one.one.one/family/
		* https://www.quad9.net/
		* https://dns.watch/index (no logging)
		* https://www.opendns.com/setupguide/
		* https://cleanbrowsing.org/
		* https://adguard.com/en/welcome.html
* IOT
	* Block IOT devices from reaching the internet.
* Android safety
	* GrapheneOS.
	* App firewall.
		* https://netguard.me/
* Border Crossings.
	* Clean device (computer/phone) + Secure delete.
	* Hidden partition.
	* Encryption.
		* Self incrimination.
		* Asked for your password, no obligation to give it.
			* Seizure.
	* Backed up data.
	* https://ssd.eff.org/module/things-consider-when-crossing-us-border
* Network Security
	* IDS/IPS.
	* Firewall.
	* DNS.

# Closed vs. Open-Source rant
- Security through obscurity.
- Voting machine example.
- Password managers.
- Software audits.
- Patents.

# Resources
## Test your devices
- Has your email address been involved in hacking of large databases? http://haveibeenpwnd.com/
- Is your browser giving away a lot of information? (Test all of your devices) https://coveryourtracks.eff.org/
- Is your network secure? (Look for Shields up!) https://www.grc.com/default.htm
- EFF - https://ssd.eff.org/
## Safer software alternatives
- https://switching.software/
- https://www.privacytools.io/ *