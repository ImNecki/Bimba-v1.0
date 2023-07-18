1. What is "Bimba"?
Bimba is program for remote manipulation of clients (RMOC).

2. what are the benefits of the program?
This may be required by the company. For example: you can find out what an employee does during work.

3. How to use it?
1 - download it from GitHub.
2 - open "host_config.json" and change configuration. Save your changes and copy to Client/host_config.json
3 - open Bimba.exe
4 - Copy all from "Client" and paste to any computer. Open client.exe or client (console).exe
5 - Have fun!

4. Сommand list:
-----base------
clear - clear console
exit - quit from program
-----RMOC------
client -i - show client list and client count
client -w start (index) - start watching client camera
client -w stop (index) - stop watching client camera
client -s start (index) - start watching client screen
client -s stop (index) - stop watching client screen
-----Sending data------
send (message) - send message all clients
sendto (index) (message) - send message to client by index
-----Vidstream server------
stream /start - start vidstream server
stream /stop - stop vidstream server
