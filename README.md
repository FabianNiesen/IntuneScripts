# IntuneScripts
Fork of Greg Nottage Intune Scripts by Fabian Niesen (InfrastrukturHelden.de / InfrastructureHeroes.org)
This is a framework for software packaging and automated upload to Intune. 

I will use this repository to provide additional Software examples. And maybe in future will add some mor functions and features. I have some ideas in mind, I just need to find some time.
Next step is implement the use of Versions and create a SCCM script to use the same sources for SCCM Applications.

# How to use it
To add a program to your Intune, you just need to run one script:

Upload-IntuneWin.ps1 -userName Admin.User@intune-tenant.com -packagePath "Dell Command Configure 4.6.0"

# Disclaimer
This repository includes Dell Tools. Iwork4Dell, but this is a personal project without any relation or support from Dell.

This script is supported as it is, usage is on your own risk. I recommend you check the code carfully and test ist before used in production.
