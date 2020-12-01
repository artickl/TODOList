1) Telegram - youtube integration

	sending youtube link to telegram and receiving mp3 back
	DONE: @your_tube_bot

2) Roomba API verification and automatization 
	Info: 	need to clean up room on weekends not on a schedule, but when I leave home... such as:
		or when my phone is not connected to my wifi (for 10 min for example once a day) - benefit: can be done locally via checking who is online in WiFi network
		or when my phone is connected to my car - issue: should be run on a phone

3) Wyze API verification and automatization
	Info: 	enable motion detection when I left home
		same as Roomba, but daily...

4) verify IFTTT functional
	Info:	Roomba when I left home is not working
		Wyze - enable detection when I left home is not working either

5) Christmas train via Google
	Info: 	Rasberry Pi Zero (because I have it)
		Walmart Christmas Train 

	Idea:	start/stop train via "Ok Google, Christmas is coming! / Crhistmas is over"
	
	Benefits: 	work with Rasberry
			Wifi, Setup, GPIO, 5V Relay, may be some extra lights
			get pyton involved (local GPIO management)
			get node.js involved (web app)
			IFTTT with Google Assistant
			PS: another idea to prevent port forwarding for web is to use Telegram to make communication like:
				Google Assistant -> IFTTT -> Telegram -> Rasberry Pi
				the benefit of it, it can work at any time regardless where train is located, just need to connect wifi

6) Sales busy lights (something like this: https://www.newegg.ca/p/0Y1-00WN-00002)
	Info:	when people are on the phone or meeting you can't know about it until you asked them
		having a light on the table showing that you are busy is nice way to communicate information in advance

	Idea:	
	    REGULAR IDEA:
		get something like this: https://www.digikey.be/nl/articles/install-easy-to-see-industrial-tower-lighting-to-alert-nearby-operators
		negative: not that nice, but works, specially if buttons are on the table and ligh is above the table
		Costs: 
			CAD $24 two-color signal 12v light - https://www.amazon.ca/LUBAN-Industrial-Rotatable-Flashing-Switchable/dp/B086ZHFTTK
				or CAD $24 two-color signal 110V light - https://www.amazon.ca/LUBAN-Industrial-Rotatable-Flashing-Switchable/dp/B086ZJGMB2
			CAD $30 for buttons and enclosure - https://www.amazon.ca/TWTADE-Momentary-Emergency-Pushbutton-Assurance/dp/B07FJ79JRJ
				or CAD $17 for ON/OFF - https://www.amazon.ca/dp/B07SVCJY7Z
			CAD $5 for cables (CAT-5 can be used)
				or CAD $5 for regular 3-wire cable
			CAD ??? for 24V power adapter
				or CAD $2 regular plug for 110V light
			Benefit 
				of 12V:
					safer cabling
					remote control can be added like https://www.amazon.ca/INSMA-Wireless-Channel-Receiver-Transmitter/dp/B01CCSG2ZY
				of 110V:
					looks like cheaper (no adapter)
					less messy on the table (no power adapter, just plug to the power socket)
			TOTAL:
				24+30+ 5+15=~CAD $74
				24+17+ 5+ 2=~CAD $48

	    CRAZY IDEA:
		make something like this: https://www.partsnotincluded.com/diy-stream-deck-mini-macro-keyboard/
		complicated... but niiiiice....
		Costs:
			CAD $30 for Rasbery Pi Zero
			CAD $1 for cherry - https://www.digikey.com/en/products/detail/MX1A-11NW/CH160-ND/91134?itemSeq=346404303
				plus CAD $0.75 for keycap - https://www.amazon.com/dp/B01DMBV6BU/ref=twister_B07BYVDWQ8?_encoding=UTF8&th=1
			CAD $0.40 red LED 2V light - https://www.digikey.com/en/products/detail/XSMDK23MB/1497-1046-ND/4745861?itemSeq=346405152
				plus CAD $0.40 green LED 3V light - https://www.digikey.com/en/products/detail/XSDG23MB/1497-1042-ND/4745857?itemSeq=346405163
			CAD $? - 3D printed Case for buttons like in original post https://www.partsnotincluded.com/diy-stream-deck-mini-macro-keyboard/
			CAD $? - 3D printed cube for lights like https://www.amazon.ca/Light-Centerpiece-Cube-Lamps-White/dp/B07PCH24ZT
			CAD $5 regular low voltage 3-wire cable
			CAD $5 for USB 5V adapter
				or can be charged from computer (benefit - will be off when computer is asleep)
			Benefit:
				can be very customizable, such as:
					additional online indicator for team
					emergency indicator if somebody is trying to contact you
					music synced Chrismas lights in the office
					...
			TOTAL:
				$30+$1+$.40+$5+$5=~CAD$ 41.40 (plus 3D printing)
				time for a good reason - is priceless =) 
