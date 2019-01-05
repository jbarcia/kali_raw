# kali_raw
A quick and easy way to deploy Kali on a system exposed to the internet, with DUO push for 2FA.

# Play Configuration
When setting up a new system, there are some things to be aware of:

**Primary User Account**
- The username for the primary user, or the system owner, the ‘root’ account will be denied SSH access. 
> `rawbox_owner: "username"`
- Primary user/owner’s public key for SSH access
> `rawbox_owner_pubkey: "ssh-rsa … "`
- Email address of the primary user / system owner
> `email: "username@email.com"`


**Domain**
- FQDN for the system
>`domain: "domin.com"`

**DUO**
- DUO iKey value from DUO management panel
> `duo_ikey: ""`
- DUO secret key value from DUO management panel	
> `duo_skey: ""`
- DUO host value from DUO management panel
> `duo_host: ""`
