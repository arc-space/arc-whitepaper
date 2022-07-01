---
label: Economy
layout: default
order: 2000
---

# Token Economics

In Season 1 the main focus is on the discovery, setting up, and building, this is true for both the players and the team. As a team we wanted to include all active players as early on as possible, to this end the Minting Fees will be paid out to early adopters following the royalties payout scheme.

---
### Minting a Universe

The initial state of the universe is unknown, it is not until the first Arcian enter that the layout of the universe slowly gets revealed. 

In technical terms, the deployment and initialization of the contract will set the seeds used to generate the universe. Every time a tile gets minted this action sets its seed defined by the user's input and random values stored at the time a tile gets generated.

###### > Dividing Space

The universe is split into a hex grid with 6 different levels of detail, the result is that at the highest resolution the map has a maximum tile count of 3.469.191.817. (min: 1.982.395.324) See the table below:

| Overview  |     Per Tile |     Min Tiles |     Max Tiles | { class="compact" }
|:--------- | ------------:| -------------:| -------------:| -------------:|
| lvl 1     |            7 |             4 |             7 |       Sectors |
| lvl 2     |           19 |            76 |           133 |       Sectors |
| lvl 3     |           37 |         2.812 |         4.921 |       Sectors |
| lvl 4     |           61 |       171.532 |       300.181 |         Nodes |
| lvl 5     |           91 |    15.609.412 |    27.316.471 |        Events |
| lvl 6     |          127 | 1.982.395.324 | 3.469.191.817 |        Energy |

The first three levels are defined as sectors resulting in a maximum sector count of 5.061. With 7 administrative sectors, 133 regional sectors, and 4.921 network tiles. (min: 4/76/2.812 tiles)

Out of the 4.921 sectors, 10% will be epic, 30% are rare, and 60% common. These are targets set on a random generator so the final results might be slightly off by the time it all gets mapped out.

The network tiles are further divided into smaller tiles down to level 6. While most of these tiles are empty around 300.181 (lvl 4 - Systems) of them will contain permanent resources and 27.316.417 (lvl 5 - Events) of them will have dynamic events and resources randomly seeded onto them.

###### > Mint Sector & Nodes

The contract will automatically mint the first 7 Sectors of space. 6 Out of these 7 sectors will be sold in a public auction at the end or at the beginning of *Act 4*. 

All tiles except for tile zero within these 7 Sectors will be put up for sale, ready to be claimed and minted. As with every other Tile, the core (tile zero) will be auto-minted and owned by the contract; all sectors within the core tiles will be put up for sale to fund the team.

| Level |  Tokens |  Batch |  Near |  Near | { class="compact" }
|:----- | -------:| ------:| -----:| -----:|
| lvl 1 |       7 |      6 | 21.00 | 29.40 |
| lvl 2 |     133 |     18 |  7.00 |  9.80 |
| lvl 3 |   4,921 |     36 |  3.50 |  4.90 |
| lvl 4 | 300,181 |     60 |  2.10 |  2.94 |

* The total minting fee is paid as royalties to current token owners.
* A 30% mint fee is added for people not on the whitelist. For example level 4 sets the minting cost to 2.10 NEAR for people that are listed and 2.94 for those that pay the extra fee.

###### > Royalties and Payouts

Royalties are fees deducted from the sales price on internal and open markets. Payouts are staggered: sales in level 2 payout level 1; sales in level 3 payout level 2, and level 1; and so on.

| Level |   Type | Royalty | Payouts | { class="compact" }
|:----- | ------:| -------:| -------:|
| lvl 1 | Sector |       0 |       1 |
| lvl 2 | Sector |       1 |       1 |
| lvl 3 | Sector |       2 |       2 |
| lvl 4 | Node   |       4 |       4 |
| lvl 5 | Event  |       8 |       - |
| lvl 6 | Energy |       8 |       - |

* Events and Energy are consumable resources and where ownership expires or runs out.
* Events and Energy can be traded within the game but not on open markets as they are dynamic in nature and decay in value over time. (not supported by standard contracts)

---
### Playing the Game

To avoid decay and destruction it is advised to plan the budget carefully and manage your resources well. 

Once a home has been set your Arcian has just minimum guarantees, any extras require storage, and in this world it all costs energy. Extras include learned skills, stored information, and plenty of other trivial things we used to take for granted eons ago.

###### > Earning Energy

Within the system there are two main ways to generate Energy:
* Explore the space and extract the resources you can find.
* Maintain infrastructure used to attract and support explorers.

Side hustles like trade, construction, piracy, or even mercenary tasks are available as well. These do not generate energy, they only cause it to exchange hands.

###### > Exploring Space

Ships, drones, and probes are the tools of explorers and extractors. All require resources to be built and maintained but also energy to be operated and fly out. 

While basic exploration looking for resource nodes is cheap, identifying and securing the location might get more expensive. Flying a fleet out to harvest and protect is a small enterprise on its own.

###### > Mentaining Infrastructure

Infrastructure is built around nodes within a sector a well-maintained grid will boost the value of all nodes in the region but at the same time as infrastructures start to decay it will attract and support fewer people and values start to drop.

In general, one can build up infrastructure up to the point where local resources no longer support the energy required to maintain them. It is feasible to import energy or use storage for a temporary boost but the cost of this is exponential and impossible to maintain.

What services a region offers is highly dependent on the infrastructure built and the types of resource nodes that are around. But owners of nodes are free to build out any service they desire.

---
`Mistakes can be expensive and are not easily undone.`
