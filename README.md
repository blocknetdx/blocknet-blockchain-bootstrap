# blocknet-blockchain-bootstrap

This repository contains the bootstrap chain files for the Blocknet blockchain. Using these files helps shorten the amount of time it takes to sync the wallet since you don't need to sync the blockchain from scratch.

---

## Instructions
If you have never ran the Blocknet wallet, follow the first set of directions below. If you have already ran the Blocknet wallet before, follow the second set of directions below.

#### If you have *already* ran the Blocknet wallet:

Video Tutorials: [Windows](https://www.youtube.com/watch?v=66o0fQ0sHxQ) | [MacOS](https://www.youtube.com/watch?v=kTJ-YBdHrtM)

1. Download the [latest bootstrap files](https://github.com/blocknetdx/blocknet-blockchain-bootstrap/releases/download/v1.0/BlocknetDX.zip).
1. Find the downloaded *BlocknetDX.zip* file and double-click. This will unzip the file and show a folder named *BlocknetDX*.
1. Close and quit the Blocknet wallet if it is running.
1. Navigate to your OS's respective data directory.

	1. For Windows: `C:\Users\[YourUsername]\AppData\Roaming\BlocknetDX\`
		1. Or paste `%appdata%\Roaming\BlocknetDX\` into the file explorer path field
	1. For MacOS: `~/Library/Application Support/BlocknetDX/`
		1. Open Finder and in the program menu select *Go* > *To Folder* and enter the above path.
	1. For Linux: `~/.blocknetdx/`
1. Remove all files and folders **EXCEPT** for *wallet.dat*, *blocknetdx.conf*, *xbridge.conf* (may not have this file), *servicenode.conf*, and the `backups/` folder. Again, **DO NOT** delete the *wallet.dat* file as it contains the private keys for your funds. Deleting this file will result in loss of funds.
1. Inside the downloaded *BlocknetDX* folder there are `blocks/` and `chainstate/` folders. Move these 2 folders into the Blocknet wallet's data directory that you just removed files from.
1. If you do not have the [latest Blocknet wallet](https://github.com/blocknetdx/blocknet/releases/latest), download and install it.
1. Run the wallet and syncing should begin at the bootstrap's last block.

#### If you have *never* ran the Blocknet wallet:

1. Download the [latest bootstrap files](https://github.com/blocknetdx/blocknet-blockchain-bootstrap/releases/download/v1.0/BlocknetDX.zip).
1. Find the downloaded *BlocknetDX.zip* file and double-click. This will unzip the file and show a folder named *BlocknetDX*.
1. Move the *BlocknetDX* folder to your OS's respective data directory.

	1. For Windows: `C:\Users\[YourUsername]\AppData\Roaming\`
		1. Or paste `%appdata%\Roaming\` into the file explorer path field
	1. For MacOS: `~/Library/Application Support/`
		1. Open Finder and in the program menu select *Go* > *To Folder* and enter the above path.
	1. For Linux: `~/`
		1. **Note**: For Linux you must rename the *BlocknetDX* folder to `.blocknetdx`
1. Download the [latest Blocknet wallet](https://github.com/blocknetdx/blocknet/releases/latest).
1. Install and run the wallet. Syncing should begin at the bootstrap's last block.
