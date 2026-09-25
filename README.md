# D2c-client
Client files for D2c Private Server
Join our small Discord server here, https://discord.gg/UWJwdUQcq

<img width="2559" height="1390" alt="Screenshot 2026-09-25 203954" src="https://github.com/user-attachments/assets/9007ae14-8fbe-4de6-a6da-173a4b2ef198" />


What is D2c? It is a small project to bring back Destiny 2 Shadowkeep as a private server for everyone to enjoy. 
Destiny 2 New Light removed a lot of the content from the game, which we paid for, and we wish to replay that said conntent again.
D2c is a reverse engineering project to rebuild the backend of the game, restore the content including all the items, missions, raids etc and bring the private server online with AAA standards. 
This includes multi server deployment, over multiple regions with high availability of game services. 

<img width="2559" height="1386" alt="Screenshot 2026-09-25 204202" src="https://github.com/user-attachments/assets/8363489e-d994-4fcc-be30-d803c5f93556" />


D2c is not Sunrise and does not contain Sunrise code in the client side. Though it does use a lot of work from the Sunrise project along with our own. 
Massive shoutout to Sunrise and Project Dawn for their contributions to the D2 reverse engineering and scripting and helping this project finish what it started 12 months ago. 


We are running a play test this weekend, you are welcome to join. Download the client, sign up (just username and password), restart the game and spawn in. 
Give us feedback on Discord or via this Git, thank you!

## How to install Destiny 2 and the D2c client. 
1) Open steam console by going to steam://nav/console
(you will need to open that in a web browser)

2) Run these two commands.
(they will download the Destiny 2 game and English language pack, you will not see the status, you can not change the download path it will download 96GB to where ever Steam is installed)

`download_depot 1085660 1085662 2210332166360342287`

`download_depot 1085660 1085661 7180122903232116872`

3) Go to your Steam install
`C:\Program Files (x86)\Steam\steamapps\content\app_1085660`
Copy the contents of the 1085662  folder into the 1085661 folder, replace the files when the conformation shows. 

4) Download our [patch file](https://github.com/Jackster/D2c-client/releases/) and replace the one in the Desinty 2 folder under
`C:\Program Files (x86)\Steam\steamapps\content\app_1085660\depot_1085661\bin\x64`

https://github.com/Jackster/D2c-client/releases/

7) Start Destiny2.exe from the main game folder
`C:\Program Files (x86)\Steam\steamapps\content\app_1085660\depot_1085661\destiny2.exe`

8) The game will load and an overlay will show, create and account, restart the game, you will now auto login.
You can access the overlay at any time by using the HOME key. 

