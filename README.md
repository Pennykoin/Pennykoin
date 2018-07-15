Prereqs on Ubuntu:
     Ubuntu 16.04.4 LTS. (Known issue with 17.10)
     
     apt install screen make cmake build-essential libboost-all-dev pkg-config libssl-dev libzmq3-dev libunbound-dev libsodium-dev libminiupnpc-dev libreadline6-dev libldns-dev

    
After running make, the pkdaemon, pkgateway, and pkwallet files will be located in /build/release/src. 

You will need to download copy of the blockchain from from [here](https://github.com/Pennykoin/Pennykoin/releases/download/1/may22BC.zip) 
 to your PennyKoin data directory (%AppData%\pennykoin on Windows or ~/.pennykoin fold on Linux).
 
Start pkdaemon and allow it to sync the rest of the blockchain. Once you get the SYNCRONIZED OK message, you can start pkwallet. 


