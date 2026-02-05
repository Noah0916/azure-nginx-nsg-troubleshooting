# Azure VM Nginx Deployment & NSG Troubleshooting

## Goal
Deploy an Ubuntu VM in Azure, install Nginx using Custom Script, and make it reachable via the public IP.

## What I did
- Created Ubuntu 24.04 VM
- Used Azure Custom Script Extension to install Nginx from a GitHub-hosted script
- Verified Nginx was running on port 80 using:
