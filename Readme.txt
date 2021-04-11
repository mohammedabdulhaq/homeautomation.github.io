products used:

1.NodeMCu 
2.Relay
3.LED Bulb
4.someJumper Wires
5.Mobile Phone


procedure:

1.Install Blynk app "https://play.google.com/store/apps/details?id=cc.blynk&hl=en_IN&gl=US"
2.In Blynk App creat a new project 
	a.you can put any name 
	b.select board as NodeMCu
	c.Connection Type As WI-Fi
3.log in with Facebook so that you will get an Email containing Token Number !!!Important!!!
4.then click on + button and add a Button 
	a.click on created button and set output as D3
	b.Mode as switch
5.connect the nodeMcu to pc
6 open arduino IDE go to file, then go to preferences, then from their copy the path of IDE
7.past the path in mypc path bar and press enter(for better understanding see the images which is attached in the github repository)
8.past the contents of libraries and tools respectively in the folders of IDE close the ide
9.open arduino IDE select the port & board(ESP8266), then upload the given code given in file named as "ESP8266_Standalone.ino"
10.connet all the connection as per the circuit diagram
11.for further you can see the video 
*************************************************************************
!!!!Warning as your doing this project with high Voltages Be Careful!!!!!
*************************************************************************
