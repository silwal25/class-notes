## Configure switch ports at the physical layer
- Just as a network card in a pc can have specific conditions such as duplex and speed set, so too a switch 


## Duplex and speed
- The defauilt setting for both duplex and speed for swuitch ports on cusco catalyst 2960 and 3560 switches is auto
- the 10/100/1000 ports operate in either hald or full diloex mode when they are set to 10 or 100 Mb/s  but when they are set to 1000 Mb/s they operate in full duplex ode
- all fiber optic ports such as 100BASE-FX ports, operate onlu at one preset speed and are always full duplex

## Switch security
- There are different methods that can be used to secure a switch
- SSH is a much better method used to securely manage the switch from a remote location
- secure shell SSH is a protocol that provides a secire connection between two decices

## Secure remote access
- telnet is an older protocol that used insecure plaintext transmission of both the login authentication and the data transmitted between the communication devices

## Configuring ssh
- configure terminal
- ip domain-anme cisco.com
- crypto key geratate rsa

## Security concers in lan
- Any frame sent by a host to other is forwared to port 2 of the switch and not broadcasted out every port
- MAC address tables are limited in size
- MAC flooding attacks make use of limitations to overwhelm the switch with fake 