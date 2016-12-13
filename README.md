TO START THE UBUNTU SSH Session
Go to 
https://console.cloud.google.com/home/dashboard?project=udacitystage5&utm_source=free-trial-2&utm_medium=email&utm_campaign=ft-welcome&utm_content=W1&pli=1
Go to COMPUTE ENGINE
Check off "ubuntu-trusty" and press "Start" if not already running
After it starts press the "SSH" text under "Connect"
An ubuntu shell will open



TO CONNECT TO TOURNAMENT TABLE THROUGH POSTGRES SQL ENGINE FROM SSH SHELL
sudo –s
sudo -u postgres psql postgres
/c tournament
/dt





