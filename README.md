# MC_Scheduling
#### The first thing you want is a MC server jar
i would recommend using these links:

### I recommend installing your server in an empty folder for ease, but normal is also fine(linux/mac)
(i don't use windows)

#### Linux/Macos = https://fabricmc.net/use/server/
#### windows = https://fabricmc.net/wiki/player:tutorials:server:windows

follow the steps and DRY RUN THE SERVER FIRST

After the dry run you will have a server.properties file

enable rcon=true

rcon password = [set your pass]
You may use the default rcon port, but my .sh file uses :25575, but i ***reccomend*** keeping your port the same and just changing the port num in the sh file.

you also want to enable-query=true just for the sake and because it can help debugging and checking connectability to the server in LAN & wordlwide(if you wan to play with friends)
### for auto turn on and off
next i would reccomend you install my .sh file(works in bash/zsh, **not** windows)

you will need to install crontab for the sh run scheduling(tutorials are available soo many places, just a simple command

then put the start.sh and stop.sh in your desired times

then wait....


or you could run the server and play before the next day


..
yup.
