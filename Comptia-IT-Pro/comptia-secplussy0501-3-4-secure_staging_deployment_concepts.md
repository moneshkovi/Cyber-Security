CompTIA Security + 3.0 Architecture and Design
============================================================

Filename: comptia-secplussy0501-3-4-secure_staging_deployment_concepts
Title: Secure Staging Deployment Concepts
Subtitle: CompTIA Security+ \(SY0-501\)

3.4 Secure Staging Deployment Concepts
------------------------------------------------------------
* 3.4 Explain the importance of secure staging deployment concepts
	+ Sandboxing
		- Developers can utilize the sandbox environment at their leisure \(no prior authorization is required)
		- Each Dev team member has access to their own individualized sandbox
		- The sandbox is a virutalized environment that is isolated from the dev, testing, staging and production environment
		- Each sandbox can be and most likely will be rolled back via snapshots daily
	+ Environment
		- Development
			* Dev environment differs from sandboxing in the fact that all members have access to the dev enviroment
			* Single server running both the web application and the database
		- Test \(Quality Assurance\)
			* Might be separate web server and database server
			* Closer to the production environment
			* Unit testing happens here and can possibly be moved back to the dev environment
		- Staging
			* This enviroment is a complete replica of the production environment
			* If there are 10 web app servers and 2 database servers in production then there will be the same here
			* QC can happen here where the code is executed then inspected for quality fulfillment.
			* Projects might be moved from staging back to testing
			* Product might be run in staging for a short period of time
		- Production
			* This is the final stage however bug check, performance and functionality monitoring will continue as with all software
	+ Secure baseline
	+ Integrity measurement
		- Quality Assurance - Part of quality management focused on providing confidence that quality request or standard are going to be fulfilled- positive declaration of quality fulfillment and how that process is performed - process oriented
		- Quality Control - Part of quailty management that is focused on fulfillment of the quality request - inspection of the project or product and that it has met the quality request or standard - product oriented.
		- QA focuses on preventing defects - Verification
		- QC focuses on identifying defects - Validation