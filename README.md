# ECOE10
OpenSSH Authentication through Kerberos.

# Team
Ana Carolina de Campos, 34199

Rafaela Thatiana Silva, 2017018022

Renan Floriano Carvalho, 25204

Ulysses Caetano Braga, 33195



# Requirements 
- 3 GNU/Linux machines with Kerberos 5 installed (preference for Ubuntu Server LTS 18.04 or Debian 9)
- Machine 1: The KDC Server
- Machine 2: OpenSSH Application Server
- Machine 3: OpenSSH Application Client
- All the machines must be clock sycronized
- All the machines must have one common user

# Environment
- 3 virtual machines on Oracle's VM VirtualBox

- Network: 10.0.2.0/24 Gateway:10.0.2.1

- Realm name: ECOE10.UNIFEI

- KDC Server:  	host: kdcserver.ecoe10.unifei
		network: 10.0.2.4/24

- App Client:	host: sshclient.ecoe10.unifei
		network: 10.0.2.5/24

- App Server:	host: sshserver.ecoe10.unifei
		network: 10.0.2.6/24 

- Commom user: 	krbuser

*The environment should be changed according to the user's needs and preferences.

# Proof of Concept (PoC)
SSH Authentication through Kerberos [video](https://www.youtube.com/watch?v=g0WPpHPAV-0&feature=youtu.be).












