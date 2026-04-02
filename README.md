How to run the server from a pc.

1.21.81 bedrock ps4 mcv3.12

***************************
GAME INSTALL AND PATCHING**
***************************

On the ps4 move the provided xml file into the data/goldhen/patches/xml 

GOLDHEN INSTALL PART.
Use the location above and install the patches.
enable game patch plugin option under plugin settings
update patch archive if you want but it is not needed for this
select patch selection to installed games only to save some memory


PS4 CHEATS MANAGER PART
go to the patches tab and look for minecraft
selecy it and enable the following
 
enable user switced to microsoft always
playform xbox 
sony MP restrictions bypass

*
V1 AND V2 ARE OPTIONAL.
(If enabled do not disable it may cause save data corruption)
*

save and exit then proceed with the steps below.


***************************
SERVER INSTALL BELOW HERE**
***************************

after downloading and moving the download into a folder you created(Any name)


click on the bedrock server.zip to extract it in the folder 

(Linux)
when inside the bedrock created folder (bedrock-server-x.x.x) inside here there should be a file called bedrock_server run it once to get the required files 
needed for the server to work.
(WINDOWS HAS EXE AND THIS DOES NOT NEED TO BE DONE AS THE EXE WILL DO IT FOR YOU)


when that is done you can go into the folder with all the server files you just created and open a command line(LINUX) and type LD_LIBRARY_PATH. ./bedrock_server
*You can go into the server.properties text file and change the name and dec what will show when the server pops up.

recommended settings for server prop to prevent spamming.
LINE 31    Online-mode= false(SENSE A XBOX MS ACCOUNT CANNOT BE USED THIS XUID CHECK HAS TO BE TURNED OFF)
LINE 126   CHAT-RESTRICTION=DISABLED(chat causes game and server crashing disable to prevent this)
LINE 64    Idle time out =default is 30 I change it to 120 or 0
LINE 72    Level name map1 to map999 for map changing without deleting
LINE 41-45 if port fails change the last number(Go up by X ammount)

Server name color system.
§ 1 - Dark Blue
§ 4 - Dark Red
§ a - Green
§ c - Red
§ e - Yellow
§ l - Bold
§ n - Underline
§ r - Reset (clears previous formatting).



when the server is loaded and running the way you want it to be you can now get your friends in.
(Make sure they have the patches installed and working.)

give them this command and tell them to save it as a .bat file

They need to download phantom CLI link is near the bottom of this doc.

*phantom-windows -server(x.x.x.x :1913X)                
                      your external ip: server port number ipv4/6
						(Server hoster)

						
***************************
Notice:
***************************
If you pick a different server you can use any public server on 1.21.81.X
some mod servers can work to but I have never attempted.
use aternos if you want a custom server with an easier install...
***************************

when they have that added to a text doc with notepad or notepad++ save it as a .bat file using all files.
(Have them save this file in a safe place as they will need it every time they join the server)



You can use playit.gg for ease of use but as far as I am aware it is not a requirement




FINAL NOTE:
MAKE SURE YOU DO NOT HAVE THE SAME NAMES ON THE PS4 SYSTEMS FOR THE USERS JOINING OR YOU WILL GET AN ALREADY IN THE SERVER ERROR.
Names on the profiles on the ps4 or any system needs to be different.
using a whitelist can help control this issue.
(This is due to no auth bc xuid does not work on modded ps4 systems)





links you need for server setup

LINUX SERVER
https://www.minecraft.net/bedrockdedicatedserver/bin-linux/bedrock-server-1.21.81.2.zip

WINDOWS SERVER
https://www.minecraft.net/bedrockdedicatedserver/bin-win/bedrock-server-1.21.81.2.zip



xml patch file 
https://mega.nz/file/ZKdwDbbJ#8g-3bVtS_sIFOXXJsViIX5IndPkKNL5pgB0IKFKIARU



(GOLDHEN CAN DO THIS TO U DONT NEED THIS.)
Ps4 cheat app
https://github.com/bucanero/PS4CheatsManager/releases/tag/v1.2.2



FOR FRIENDS TO JOIN(FREE)
https://github.com/jhead/phantom/releases


I did not feel comfortable sharing this file.
I dont want no issues so I am playing it safe.



server list
https://jars.vexyhost.com/


