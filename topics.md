Model
=====

* What is it? How does it work?
* Why does it exist?
* How can it go wrong?
* What can I do to be safe?


Discussion topics
======================

* Mobile app permissions
  * Permissions management on iOS devices
  * Permissions management on Android devices and what each permission means (see
	the Android ["System Permissions" documentation](http://developer.android.com/guide/topics/security/permissions.html))
  * Mobile app security architecture (high-level) on iOS
  * Mobile app security architecture (high-level) on Android
  * Demo Android/iOS app which abuses accepted permissions
  * Examples of real-world apps that abuse permissions (flashlight apps for example are known to
	abuse permissions of all kinds to make ad revenue)
* OAuth[2]/3rd-party authentication
  * OAuth[2] architecture
  * Enumerate a few common OAuth/3rd party auth providers
  * Explain what information a service has access to when you are OAuthed through a 3rd party
	provider (email, name, image, etc)
  * Demonstrate how various ACLs can be managed through the OAuth provider
* HTTPS/SSL
  * Secure HTTP architecture (certificate chains and authorities, etc)
  * How HTTPS offers end-to-end encryption and secures web browsing (especially with respect to an
	untrusted network), etc
  * CA flaws, MITM attacks, certificate spoofing, etc
  * Chrome/Firefox warnings about expired/untrusted certificates and why you should be very careful
	if you ignore them
  * How to examine/manage certificate chains and SSL certificate exceptions
  * SSL details to be aware of when browsing the web or using any web-based communications platform
* Passwords (strength, MFA, etc)
  * How login systems classically work (database with username/password, maybe could even go into
	traditional password storage using password hashes?)
  * Classicaly user sessionization?
  * What do most people think a strong password looks like? What does a strong password actually
	look like? (definitely should use the [in]famous and obligatory XKCD ["Password
	Strength"](http://xkcd.com/936/))
  * Why you shouldn't repeat passwords across different services if possible
  * Various ways to bolster user account security (login audits/history, multi-factor auth, etc)
  * The use of password "vaults" (such as LastPass)
* Online identity (certificate chains, phishing, etc)
  * How you know if the person/company you are communicating with or the website you are browsing
	is actually who you think they are (probably a bit of overlap with SSL certificates)
  * Phishing (the good-ol' death-of-a-Nigerian-king example and then maybe a much more convincing
	email from a major bank)
* Network trust (DHCP, coffee shop wi-fi exploitation)
  * How do LAN/Wi-Fi networks actually work (architecture, DHCP, etc)
  * How an attacker on a LAN attack you if you are on the same LAN
  * MITM attacks and snooping on a LAN
  * Ways to mitigate snooping and other LAN attacks (good-ol' HTTPS for secure web browsing, etc)
* Cookies (retargeting, XSS, etc)
  * What cookies are
    * Ephemeral data storage that should only be accessible by the given cookie
	domain)
  * How cookies are used
    * Ad retargeting demo
	* "Keep me logged in" demo
  * How cookies can be abused by various kinds of attacks (such as XSS)
  * Being aware that cookies may contain sensitive information and what to do

Additional notes and things to keep in mind
===========================================

* Keep things super high-level and non-technical when possible
  * I find it easier to explain some of the technical concepts metaphorically (as most of the
	concepts originated from other non-technical disciplines anyway)
* There is bound to be quite a bit of overlap between each topic, but I find it best to keep each
  discussion topic as "standalone" as possible; in other words, don't create a dependency between
  discussion topics (though I'd definitely encourage each topic to reference another if relevant)

