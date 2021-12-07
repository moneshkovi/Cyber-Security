CompTIA Security + 4.0 Identity and Access Management
============================================================

Filename: comptia-secplussy0501-4-1-identity_and_access_management_concepts
Title: Identity and Access Managements Concepts
Subtitle: CompTIA Security+ \(SY0-501\)

4.1 Identity and Access Managements Concept
------------------------------------------------------------
* 4.1 Compare and contrast identity and access management concepts.
	+ Identification, authentication, authorization and accounting (AAA)
		- Identification
			* Presenting a claim of identity to a system \(username\)
		- Authentication
			* Checks that verify the identity claim to a system \(password\)
			*  "Who or what are you?
		- Authorization
			* Determining the actions, access level or tasks that an identity can perform within a system\(permissions\)
			* Enforcing policies
			* "What are you allowed to do?"
		- Accounting
			* Measuring the resources that authorized users consume or access
			* Logging statistics
			* "What did you do?
	+ Multifactor authentication
		- Something you know
			* Password, PIN, Secret Question
		- Something you have
			* Token, Smartcard, RFID device, Proximity card, keyfob
		- Something you are
			* Biometrics
			* Behavioral and physiological \(retinal pattern vs. voice pattern)
		- Somewhere you are
			* Restrict or Allow access based on location
			* GeoLocationing
			* travel schedule, proximity to work
			* Great for road warrior connections
				+ Traveling salesperson using mobile devices
		- Something you do
			* Keystroke Patterns, signature analysis, 
			* gait pattern\(walking\) as we get more wearables through accelerometer sensors
	+ Federation
		- Also known as federated identity management
		- A form of SSO in which two or more systems trust the identities and authentication of each other
		- MSA, Google, Facebook Login
	+ Single sign-on
		- A method in which an end user can log into a system once and does not require an additional password
		- Password vaulting
			* Password Managers like: LastPass, Norton Identity Safe
		- Federations
			* MSA, Google, Facebook Login
			* See diagram
	+ Transitive trust
		- See diagram