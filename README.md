# blocknet-blockchain-bootstrap

This repository contains the bootstrap chain files for the Blocknet blockchain. Using these files helps shorten the amount of time it takes to sync the wallet since you don't need to sync the blockchain from scratch.

---

## Instructions
If you have never ran the Blocknet wallet, follow the first set of directions below. If you have already ran the Blocknet wallet before, follow the second set of directions below.

#

If you __have never ran__ the Blocknet wallet:

1. Download the [latest bootstrap files](https://github.com/BlocknetDX/blocknet-blockchain-bootstrap/releases).
1. Find the downloaded *BlocknetDX.zip* file and double-click. This will unzip the file and show a folder named *BlocknetDX*.
1. Move the *BlocknetDX* folder to your OS's respective data directory.

	1. For Windows: `C:\Users\[YourUsername]\AppData\Roaming\`
		1. Or paste `%appdata%\Roaming\` into the file explorer path field
	1. For MacOS: `~/Library/Application Support/`   
	1. For Linux: `~/`
		1. **Note**: For Linux you must rename the *BlocknetDX* folder to `.blocknetdx`
1. Download the [latest Blocknet wallet](https://github.com/BlocknetDX/BlockDX/releases/latest).
1. Install and run the wallet. Syncing should begin at the bootstrap's last block.

#

If you __have already ran__ the Blocknet wallet:

1. Download the [latest bootstrap files](https://github.com/BlocknetDX/blocknet-blockchain-bootstrap/releases).
1. Find the downloaded *BlocknetDX.zip* file and double-click. This will unzip the file and show a folder named *BlocknetDX*.
1. Close and quit the Blocknet wallet if it is running.
1. Navigate to your OS's respective data directory.

	1. For Windows: `C:\Users\[YourUsername]\AppData\Roaming\BlocknetDX\`
		1. Or paste `%appdata%\Roaming\BlocknetDX\` into the file explorer path field
	1. For MacOS: `~/Library/Application Support/BlocknetDX/`
	1. For Linux: `~/.blocknetdx/`
1. Remove the `blocks/` and `chainstate/` folders. **DO NOT** remove any other files.
1. Inside the downloaded *BlocknetDX* folder there are `blocks/` and `chainstate/` folders. Move these 2 folders into the Blocknet wallet's data directory that you just removed the other `blocks/` and `chainstate/` folders from.
1. If you do not have the [latest Blocknet wallet](https://github.com/BlocknetDX/BlockDX/releases/latest), download and install it.
1. Run the wallet and syncing should begin at the bootstrap's last block.


