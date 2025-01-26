# Security

## Authentication

This above architecture does not allow an obvious method of user authentication. Without this authentication any actor could access services in my homelab. This prevents significant security and usability risks. I am exploring a number of potential solutions.

#### CloudFlare Access

CloudFlare supports multiple types of authentication for up to 50 users on the free plan.

#### Opensense Router Login

OPNsense may have tools availble to support basic auth or other forms of authentication. More research is needed...

#### Devoted NGINX server with Basic Auth

This would require setting up another device in my homelab.