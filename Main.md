Using this Document you would be able to find the geolocation of any wifi using nearby printers

Tools used:-
1) Shodan.io
2) wiggle.net
3) openstreeetmap.org (for better viewing of the maps)

Using shodan.io dorking we can find the Vulnarable printers that can be attacked.

http.title:"HP color" country:"IN" (http title would be hp and then list all the india)

Usually in HP printers there is no credentials just type in the ip and login the printer.

RESULTS- https://www.shodan.io/search?query=http.title%3A%22HP+color%22+country%3A%22IN%22

Then skip over to networking tab to see the options on the side which says wireless configuration

RESULTS- http://140.142.102.130/set_config_network_Wireless.html?tab=Networking&menu=NetWireless

You'll see several wifi network names under network name (SSID) now copy any one of the SSID then paste it in wiggle.net

i selected the Matt Long's Wi-Fi Network for testing purpose now go to advance search on wiggle.net and paste the ssid in the blank

RESULTS- https://wigle.net/search?ssid=Matt%20Long%27s%20Wi-Fi%20Network

then click on map and you'll get the pinpoint location of the wifi in range of that printer


pretty less used trick but very cool..:p
