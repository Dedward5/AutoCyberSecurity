#Questions are:

##What is the difference between vulnerability and threat?##
A **vulnerabillity** is a "weakness" in the software or hardware that an attacker can leverage to gain access or execute malicious code. A **threat** is person
or possibly a tool which will work to exploit a vulnerabillity in order to gain access/comprimise.

##What are the requirements to compromise a device?##
Physical or Remote access e.g. the abillity to acccess a USB port physically or a level of connectivity via the internet, possibly some level of credential e.g. a PIN,
Password or certificate.

##What does root credential mean?##
A ceredital (PIN/Password) that provides read/rwite access to all areas of data, code or configuration to apply changes or exfiltrate data.

##What does reconnaissance mean?##
Gaining information about a system, person or device that you want to attack. This could be a simple as finding out a device model, reading a manual, following a person
on LinkedIn, port scanning, and wider research into vulnerabillites.

##What is misconfiguration (security)?##
Typically not setting a device securit confguraiton beyond defaults, most obvious is leaving default manufacturer passwords or unnecissary exposeure of admin interfaces
to the internet.

**What is port scanning? Can you name a few tools?**
This is using software tooling to scan the IP (or other ptotocols) address of a device/service for open "ports". Ports in IP are used to connect to specific applications
for example Webservers typically server HTTP on Port 80 HTTPS on 443, SMTP email traffic uses port 25, Windwos Remote Desktop is on port 3389.

Port Scanning Tools I can remember wihout looking are.

1. Nessus
2. Nikto
3. BurpSuite

A good list is here https://sectools.org


##How can we assess any system security?##
System secutiy can be assessed in many ways, one can be to review your configuration against a "best practice" configuration for example if an industry or regulatory body
provides a level of configuration to audit against. Peer review wihitn your own organisation is another way, although can be dependant on the review beign objective.
Use of third partes is one way an the next questions referrs to "penetration testing". Some organisations may be able to have an internal test team who "attack" thier
systems called "Red Teaming" and another in house team who defend the systems "blue team".

##What is penetration testing?##
Using tools such as the ones I listed and the ones on https://sectools.org and other attacks based on reconnessence a company can attempt to gain access to a device or
service. Some tests are (or were) called blackbox/whitebox. For Blackbox the attaker has no credentials to the system and must gain access, for WhiteBox they may have some
or all credentials. WhiteBox may be better as it tests the layers of defence more readily as it proves how easy it is for an attacker to move laterally if they gain 
any level of access.


##Why is data backup a basic requirement?##

##How can malware get access into a system?##
Via Physical access such as USB device or other service port, via email attachments, downloaded software, app stores or possibly even "supply chain attacks"
where its implanted very early on in the device lifecyce e.g. via an employee


##What do we mean by vehicle-to-vehicle/vehicle-to-infrastructure communication?##
https://www.nhtsa.gov/technology-innovation/vehicle-vehicle-communication
https://www.extremetech.com/extreme/176093-v2v-what-are-vehicle-to-vehicle-communications-and-how-does-it-work
https://www.3m.com/3M/en_US/road-safety-us/resources/road-transportation-safety-center-blog/full-story/~/what-is-vehicle-to-infrastructure-v2i-communication-and-why-do-we-need-it/?storyid=021748d7-f48c-4cd8-8948-b7707f231795

