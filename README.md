# DigitalClockUsingShellScript
Linux Project
It all start with the idea of watching a clock.


commands:
create a shell script

vi clock1.sh

when the file opens press i and write

#!/bin/bash

Red=$'\e[1;31m'
Green=$'\e[1;32m'
Blue=$'\e[1;34m'

while true
do
	clear
	echo $Red $(date +%T)
	sleep 1s
done	
		
    
    
type esc and write :wq to save and exit


Now its time to run it

./clock1.sh


<img align="right" alt="coding" width="400" src="https://camo.githubusercontent.com/cae12fddd9d6982901d82580bdf321d81fb299141098ca1c2d4891870827bf17/68747470733a2f2f6d69726f2e6d656469756d2e636f6d2f6d61782f313336302f302a37513379765349765f7430696f4a2d5a2e676966">

![image](https://github.com/AaravRajSIngh/DigitalClockUsingShellScript/assets/67210617/919dbaf7-d53d-4a29-ae92-bebc9cf57114)

![image](https://github.com/AaravRajSIngh/DigitalClockUsingShellScript/assets/67210617/5b8399a8-646e-4ac4-aae3-2cd4eab42bec)

