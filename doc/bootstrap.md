### Bootstrap the Blockchain Synchronization

Normally the Bitcoinfiat client will download the transaction and network information, called the blockchain, from the network by syncing with the other clients. This process can take quite some time as the DEV Blockchain is growing bigger and bigger for each day. Luckily there is a safe and fast way to speed up this process. We'll show you how to bootstrap your blockchain to bring your client up to speed in just a few simple steps.

### Requirements

- A fresh install of the Bitcoinfiat client software.

### Download the blockchain via BitTorrent

Download the .dat file here [bootstap.dat](https://bootstraps.infernopool.com/DEV/bootstrap.dat) 

### Importing the blockchain
Exit the Bitcoinfiat client software if you have it running. Be sure not to have an actively used wallet in use. We are going to copy the download of the blockchain to the Bitcoinfiat client data directory. You should run the client software at least once so it can generate the data directory. Copy the downloaded bootstrap.dat file into the Bitcoinfiat data folder.

**For Windows users:**
Open explorer, and type into the address bar:

	%APPDATA%\BitcoinfiatCore
    
This will open up the data folder. It should look like the image below. Copy over the bootstrap.dat from your download folder to this directory.

**For OSX users:**
Open Finder by pressing Press [shift] + [cmd] + [g] and enter:

	~/Library/Application Support/BitcoinfiatCore/
    
**For Linux users:**
The directory is hidden in your User folder. Go to:

	~/.BitcoinfiatCore/
    
### Importing the blockchain
Now start the Bitcoinfiat client software. It should show "Importing blocks from disk" 

Wait until the import finishes. The client will download the last days not covered by the import. Congratulations you have successfully imported the blockchain!
