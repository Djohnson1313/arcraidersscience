<img width="1536" height="1024" alt="arc raiders science logo" src="https://github.com/user-attachments/assets/d8be07c1-d0da-4297-90ee-7cb833d5ef4b" />

# Arc Raiders Loot Deep Dive

Google Sheets Link : [Arc Raiders Item Tracker](https://docs.google.com/spreadsheets/d/1Unvls4dH4esEcWdbbjQcm2Ix8XGi0h4aEYgbZdMmKz8/edit?usp=sharing)

Creator : DJohnson1313

Date Last Updated : 12/16/2025


Game : [Arc Raiders](https://store.steampowered.com/app/1808500/ARC_Raiders/)
## Data Sources and Tools Used
- [Arc Raiders Fandom](https://arc-raiders.fandom.com/wiki/Arc_Raiders_Wiki)
  - all the data was scrapped from this site
- [Octoparse 8](https://www.octoparse.com/download?campaignid=21878410275&adgroupid=&keyword=&gad_source=1&gad_campaignid=22901936798&gbraid=0AAAAAoOLR78URCNV3w23LxOTXaCntbx4u&gclid=Cj0KCQiAubrJBhCbARIsAHIdxD-6JZzIabHsIBH-HPuFL5_fZ_RMDsCwQwUKDOfqsjhXeoIJIkbviykaAnaHEALw_wcB)
  - this is the free web scrapper I used
- [Google Sheets](https://workspace.google.com/products/sheets/)
  - where the data is collected
- [Github](https://github.com/)
  - version control as well as public updates
- [Python](https://www.python.org/)
  - coding language used for data analytics

## Contact Information
- blueshirtengineering@yahoo.com
  - use this email to send me suggestions, fixes, complaints or anything else useful to the project

# Purpose Of This Repository and Data Collection

Hey Raiders! In this repository, we will used publicly sourced data to dive deep into the interworkings of [Arc Raiders](https://store.steampowered.com/app/1808500/ARC_Raiders/) to get a better understanding of spawn rates for items based on maps, map condition and container type. This will hopefully alleviate some of the speculation regarding loot. I am aware of some similar undertakings by large youtube channels. Actually, those videos are what inspired me! Hopefully we can come together to add as much data as we can to a singular place, allowing any creator or fan of Arc Raiders to dive into the data themselves. As of right now, I will generate a single report based on the data from the community, however if this takes off, I would love to do more regular updates, maybe even weekly if theres enough activity!

## How does the Google Sheet work?

Luckily, I've made it as simple as possible. You can either type out the item you are tracking in the `Item` column, or use the dropdown arrow in the column to search for your item. `Item Rarity` and `Item Type` will auto fill for you, just add what `Map` and `Map Condiction` you found the item on, as well as how many times you searched that specific container with the specificed map condition in the `Number Of Container Checks` column. Also ensure to fill out `Container Type` to help us understand where items drop!

## Biases and potential weakpoints

Let's take a quick look into the potential biases and weakpoints that this data collection process may contain.

- Reddit Community - Bias
  - As of the most recent version of this repo, this is only being posted to reddit, meaning only raiders who also check the [R/ArcRaiders](https://www.reddit.com/r/ArcRaiders/) subreddit will be interacting with this data collection effort.
    - Solution : Eventually this repo and google sheet may be posted to other sites.
- Nightime - Bias
  - From day 1 the Arc Raiders community have been told that nightime not only increases loot spawns, but also blueprint spawns. This may cause a bias in the data where large amounts of raiders report data of found objects in overwhelming quantaties for night raids, causing an inequality in     data spread.
    - Solution : Raiders! Please try to add day data too!
- Counting - Weakpoint
  - This data will be less valuable if the number of times the container was checked is not properly counted. As of right now, the only solution is to keep count in your head or some sort of counter. I do not have an integrated solution as of this moment.
     - Solution : Open to ideas!

# Data TLDR

Here is where some analytics will be displayed once enough is sourced! See you topside raider!

## Repository Structure

```
├── README.md
└── arc_radiers_deep_dive.ipynb
```
