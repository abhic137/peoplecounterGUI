# peoplecounterGUI

image refreance
```
docker pull pavan0077/people-counting-gui:V1
```
steps to start the file:
```
sudo docker-compose up -d
```
password:
```
vncpassword
```
Inspect the port and address
```
sudo docker logs people-counter-people-counting-gui-1
```
```
sudo docker logs <image-name>
```
Access the application
```
use HTML Client
```
noVNC HTML client started:
	=> connect via http://172.18.0.2:6901/?password=...
 ```
Ctrl + Right click on HTML link
```
## APP
download the IPwebcam app from the pa store and go the start server option to get the first link 
## INSIDE THE CONTIAINER
go to the people counting folder and go to mylib folder and edit the config.py folder with the link that we get from the ip webcam from the phone.
to run the code use the command bash run.sh
