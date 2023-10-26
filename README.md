# HTBhelper

An organized framework built with bash designed for the Hack The Box platform.  

![mainscreen](https://github.com/B4MNsec/HTBhelper/assets/89555622/5123f183-3290-48a8-b548-757871632219) 



How To Use the Hack The Box Helper Script;

1.) Create your free account at https://hackthebox.com 

2.) Download your lab.ovpn VPN file 

3.) Create a Directory for the script before cloning (I prefer to have it on my /Desktop)
      
      example command;       #mkdir HTBhelper 

4.) Move your newly downloaded .ovpn file from HTB to the directory you just created.
      
      example command;       #mv lab_username.ovpn -t /Desktop/HTBhelper 
      *The .ovpn file will need to be named "lab.ovpn" in order for the script to find it*
      example command;       #mv lab_username.ovpn lab.ovpn

5.) Clone the HTBhelper Repository to your machine. First Navigate to the directory created just for the script.
      
      example command;        #cd /Desktop/HTBhelper 
                              #git clone https://github.com/B4MNsec/HTBhelper

6.) When ready to use the script make sure that you are in the created directory or at least know the exact pathname to launch from.
      
      example command;         #bash HTBhelper.sh 


                              
![connectedIP](https://github.com/B4MNsec/HTBhelper/assets/89555622/cd6f31c5-7a8f-462a-82c6-5ef577318ac5)


If you have successfully created and downloaded your HTB vpn certificate and moved it to the correct directory you will now be able to 
quick connect to the HTB vpn servers from the helper script as well as view your connected tun0 IP address (see above photo for reference)

Upon exiting the script you will be asked if you would like to preserve the VPN state or close the connection. 

There is plenty of room and variations to customize the notes/copy pasta section as one may see fit. 

![enumtips](https://github.com/B4MNsec/HTBhelper/assets/89555622/f5f48d32-191f-4c7a-b286-cd5e5008687e)

