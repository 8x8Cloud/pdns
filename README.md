# pdns
A test case of the flow of code for pdns pipe backend deployments

# Problem statement
Deploy [PowerDNS](https://doc.powerdns.com/md/) on two environments (dev and staging) with a custom pipe backend. 

# Requirements
* A development environment (all in one) suitable to run on a laptop utilizing containers.
* A staging instance deployed in AWS.
* Both environments should leverage the same configuration management code (of your choice) for configuration.
* Use this github repository to maintain and deploy the code to all environments.
* Custom [pipe backend](https://doc.powerdns.com/md/authoritative/backend-pipe/) implementing a new DNS record type of your choice. 
* PDNS Statistics should be available from external world.

# Bonus
* Sucessful test cases initiate code promotion to staging
* Implement the GEO dns record type, different results when sourcing from North America or Europe.
* Leverage AWS Cloud Formation to initialize secondary environments (i.e. staging)

# Presentation
Present your work to our team via screen sharing session. Talk about the approach you took. Demo updating the code or configuration. 


