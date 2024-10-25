# EaglerCraftX Server

## Credits
Original Project: Lax1Dude
<br>
If you get a plugin you want us to add, make a fork then upload it to the CORRECT plugin folder. Afterwards, make a merge request. We will tell why or why not it was added.
<br>
## Setup Guide
Welcome to the EaglercraftX server project! Here is how you can setup your very own eaglercraft server:
<br>
<br>
First, go to the top of the repo and click on code > codespaces > create codespace
<br>
Next, download the [latest] server.jar file at [MC Utils](https://mcutils.com/api/server-jars/paper/1.21.1/download) and add it to the server folder (make sure the "s" in server is lowercase)
<br>
now you have your own free server instance to host eaglercraft. Next you need to run the setup commands:
<br>
<br>
create 2 terminal tabs and paste in the following snipits:
<br>
<br>
first tab: `cd server && ./start.sd` (use`./start.sd` if you want to start it again in the same terminal)
<br>
<br>
second tab: `cd bungee && sudo java -jar bungee.jar` (use `sudo java -jar bungee.jar` to start it again in the same terminal)
<br>
<br>
Now go to the ports area and forward (and make public) ports `25565`, `8081` and `19132`
<br>
Your eaglercraft server is setup!
<br>
!!DO NOT USE THE RESTART COMMAND, IT WILL BREAK THE TERMINAL!!
