# CiscoPacketTracer_RIPv2
Express Guide to Cisco Packet Tracer Guide</br>
</br>
Dynamic Routing - RIPv2 Routing </br>
</br>
Contents for basic configure RIPv2 Routing</br> 
</br>
The topology diagram below shows several networks connected by three Routers.</br>
In the Packet Tracer activity, all connected ports are already configured with their IP Address and Subnet Mask. The PC’s are also configured with their Default Gateway.</br>
</br>
India_Router has three connected networks:</br>
172.16.1.0</br>
100.1.1.0</br>
150.1.1.0</br>
France_Router has three connected networks:</br>
192.168.1.0</br>
150.1.1.0</br>
200.1.1.0</br>
UK_Router has three connected networks:</br>
10.1.1.0</br>
100.1.1.0</br>
200.1.1.0</br>
---------------------------------------------
Verify Configuration or Check Configuration </br>
</br>
Use the Show IP Route command to verify the configuration:</br>
</br>
1.	Click India_Router0>CLI</br>
2.	Type the following syntax to view your configuration:</br>
Router> enable	</br>
Router# show ip route</br>
3.	Your result should look similar to configuration:</br> 
Note: The addresses will be different from your output</br>
</br>
Alterantive </br>
</br>
Use   PING   in command prompt</br>
