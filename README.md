# transfer_id_pub
log into ssh host with username &amp; password + transfer your ssh key to authorised_hosts

This bash script is intended for use on OSX or Linux hosts.

It will do the following by unser interaction:

- generate a public ecdsa 521 bit public key in your .ssh directory, if it does not exist
- ask you for the remote user name
- aks you for the remote host name
- uses ssh to login to the remote host and ask for the password
- transfers the .ssh/id_ecdsa.pub key to the remote host 
- stays logged in and gives you a prompt to start working :-)

Copyright: Stefan Pielmeier, Aalborg, Denmark, 2020

License: MIT, see file LICENSE (may not be removed)
