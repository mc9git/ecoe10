# ECOE10
OpenSSH Authentication through Kerberos.

# Requirements 
- 3 GNU/Linux machines with Kerberos 5 installed (preference for Ubuntu Server LTS 18.04 or Debian 9)
- Machine 1: The KDC Server
- Machine 2: OpenSSH Application Server
- Machine 3: OpenSSH Application Client
- All the machines must be clock sycronized

# Environment
- 3 virtual machines on Oracle's VM VirtualBox

- KDC Server:  	host: kdcserver.ecoe10
		network: 10.0.2.10/24

- App Server:	host: sshserver.ecoe10 
		network: 10.0.2.11/24 

- App Client:	host: sshclient.ecoe10
		network: 10.0.2.12/24

*The environment should be changed according to the user's needs or preferences.
