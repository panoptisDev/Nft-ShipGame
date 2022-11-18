# ShipGame
## Ship NFT game with game actions taken on chain.
## Mumbai deployed contract: https://mumbai.polygonscan.com/address/0x45CBbAB77f9CCDA242a65c65191A9c50AC704fF3
contract: 0x45CBbAB77f9CCDA242a65c65191A9c50AC704fF3

This game is playable on the polygon network in its beta v2.0 stage at https://www.shipwars.net/

Uses the contract **ShipGame/contracts/ship.sol** deployed to the polygon network to create a free-for-all war game that can be played entirely on the blockchain.

**ShipGame/src/components/** holds the jsreact components which allow the game to be played in a more understandable manner with an informative UI to enchance the user experince.

An overview of the minting page shown here:
<img width="942" alt="shipwarsminter" src="https://user-images.githubusercontent.com/38538941/192224133-49a2582a-484d-4c2b-a817-aa6f646912a7.png">


Along with an image of the active game page once a user's ship has been minted (and they have fired, choosing a target to attack):
<img width="947" alt="shipmain" src="https://user-images.githubusercontent.com/38538941/184683560-b6c273c1-c676-4f19-bb5a-e8fb99cc4078.png">

Additional visual tools can be seen on the page and here, showcasing the ocean activity feed keeping track of recent ocean events:
<img width="491" alt="shipactivity" src="https://user-images.githubusercontent.com/38538941/184683841-6a3e2dfa-ab8a-438f-8c20-34a4ad11d247.png">



Truffle v5.1.39 (core: 5.1.39)\
Solidity - 0.8.15 (solc-js))\
Node v11.12.0\
Web3.js v1.2.1
---

Ship War Information
RETURN TO GAME
What is Ship Wars?
Ship Wars is a smart contract strategy wargame. It exists and is played entirely on contract. Players mint a ship and attempt to sink other players' ships. When a player sinks another ship, they earn Matic immediately as a reward. When a player is sunk, they can immediately mint again as the game is on-going. During this beta the multiplier will be .9x or ".9 to 1". Meaning every ship sank will return 90% of your cost to mint. For example: Sink one ship at a 1 Matic mint cost, you now have won .9 Matic, sink two ships, you now have 1.8 Matic and on it goes until you are sunk yourself and mint again. During the beta this 10% will be added to a prize pool and used for free-to-play events.


How to Play:
1. Navigate to Shipwars.net

2. Connect your wallet.

3. Choose your stats and mint a ship.

i. You will have 5 stat points to allocate into Health, Accuracy, or Damage.

ii. Cost to mint a ship is 1 Matic (which funds the prize pool for the game.)

4. Now that your ship is minted the game is on! Other players can now see you and begin shooting.

i. In the upper left corner you will see your Ship Stats based on how you allocated during minting. This comes in the form of Health, Accuracy, and Damage. In the bottom center of this box you will see your ship’s number.

ii. Look at the Ocean Overview. This area displays all of the ships that are currently attackable in the game.

iii. Look at Latest Ocean Activity to see the most recent activity (e.g., who took the last shot, did that shot hit, did that shot miss, was a ship sunk, etc.)

iv. You will see an input field; enter the ship number of the ship you wish to attack then select “FIRE”. This will initiate a Transaction (Tx) on the blockchain. When MetaMask pops up, confirm the Tx. There is an 18 block reload time starting from the moment your tx is confirmed. This allows time for activity to update on the blockchain. When you Fire at an opponent their stats will appear in the upper right-hand corner of your screen under Target Stats.

Note: When you sink an opponent's ship you are awarded the prize money immediately.


FAQ
1. What is Layer 2 (aka L2)?

"Layer 2 (L2) is a collective term to describe a specific set of Ethereum scaling solutions. A layer 2 is a separate blockchain that extends Ethereum and inherits the security guarantees of Ethereum." - ethereum.org

2. What is Polygon?

Polygon is a Layer 2 on the Ethereum blockchain. You can access it by adding the Polygon network to your Metamask wallet. “Polygon believes in Web3 for all. Polygon is a decentralized Ethereum scaling platform that enables developers to build scalable user-friendly dApps with low transaction fees without ever sacrificing on security.” Learn more about Polygon at https://polygon.technology/

3. Why is Ship Wars using a Layer 2 like Polygon?

Unlike many “blockchain” games which utilize aspects of the blockchain but exist mostly on backend infrastructure, Ship Wars exists entirely on contract. The smart contract IS the backend. This means every action on the chain requires a transaction. If this were done on Ethereum’s Mainnet the game would simply be too expensive to play. By using an L2 like Polygon, we get incredibly low Tx fees with all the security and benefits of the Ethereum blockchain.

4. How do I add the Polygon network to my Metamask wallet?

Follow the steps in this article: Add Polygon Network

5. What is MATIC? How do I get it?

Polygon(MATIC) is the primary cryptocurrency of the Polygon network and is the token we will be using for our game. This means you will need to acquire MATIC. The absolute easiest way is to buy ETH, navigate to Opensea, click on the wallet icon and bridge MATIC over to Polygon directly. Explained Here.

Another easy way is to navigate to the Polygon bridge and bridge your ETH over.

Once your ETH has been bridged over, you’ll want to swap it for MATIC at a trusted exchange such as Sushiswap.

*This is not a comprehensive list of ways to purchase or acquire MATIC, but just a few to get you started.
