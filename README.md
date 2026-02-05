
## Problem
Even though Nginx was running and listening on 0.0.0.0:80, the website was not reachable via the public IP.

## Investigation steps
1. Verified Nginx service status
2. Tested connectivity from inside the VM:
## Proof

Nginx was reachable at:
http://40.115.127.224

Script used by Azure Custom Script Extension:
https://raw.githubusercontent.com/Noah0916/azure-scripts/main/install-nginx.sh
