<p align=center>
    <a href="https://www.pathofexile.com/" title="Path of Exile Website">
      <img align="center" src="https://web.poecdn.com/protected/image/layout/sanctumlogo.png?v=1670373174098&key=j1DUgpyrwdlKZcGWzaFxxA" />
    </a>
</p>
<h2 align="center">Path of Exile Gem Price Collector</h2>

Contents
--------

 * [What is Path of Exile](#what-is-path-of-exile)
 * [What are gems](#what-are-gems)
 * [What does the script do](#what-does-the-script-do)
 * [What can you do with the csv file](#what-can-you-do-with-the-csv-file)
 * [What is inside the file](#where-you-can-find-the-csv-file)
 * [Google sheet example](#auto-updating-google-sheet)
 

What is Path of Exile?
--------
Path of Exile is an online Action RPG set in the dark fantasy world.

What are gems?
--------
Skill gem (known as Active Skill Gems), is an item class which grants skills to the player by placing them into an item socket.\
Skill gems have different levels and quality variants which can increase their power.

How do we make in-game profit?
--------
Gems have levels from 1 to 20 we can just level them to level 20 and sell, or we can corrupt them having the chance to make them level 21.\
We corrupt gems with vaal orbs which modifies them unpredictably. Our goal is to successfully modify the gem to become level 21 which has around 12% chance of happening but the price is significantly increased if we successfully do so.

What does the script do?
--------
This is python script using API to scrape data from https://poe.ninja/ \
It collects gem names, gem prices and saves them to a csv file

What can you do with the csv file?
--------
The csv file can be imported in sheets/excel to filter and find what are the best gems to level for in-game profit.

Where you can find the csv file?
--------
You should be able to locate it in the output folder in this directory or 
[click here](https://github.com/Vyary/poe-gem-prices/blob/main/output/gems.csv)

What is inside the file?
--------
In the file you will see a couple of rows starting with Gem Name followed by:
* Buy price: This is the base price that you will pay for the gem before leveling it
* Corrupted 20/20: This refers to a gem that has been corrupted and failed
* Success 21/20: This refers to a gem that has been corrupted and successful upgraded which increases the price tremendously
* Listed 21/20: This refers to the number of successful 21/20 gems on the trade site including offline offerings(would recommend when checking the prices in this file to keep in mind that gems with higher listing count are more likely to have a appropriate price and the profit will be more accurate)
* Vaal price: This is very specific to gems that have Vaal version. The Vaal version unlocks additional skill of the set gem
* Leveled 20/20: Price of the gem for just leveling it to level 20
* Listed L20/20: Number of listed level 20 of set gem

Auto updating google sheet:
--------
**For Leveling:**
* Filter 1: This sheet includes gems with 50%-ish profit just to level them, they are not for corruping [click here](https://docs.google.com/spreadsheets/d/1qcYu22DIwEORUYuTJNnYnxS5ceQx8y6XJhVjBai_0lI/edit#gid=1128179025&fvid=2016462890)

**For Corrupting:**
* Filter 1: Good in league start with buy price under 20, 50%-ish profit if it fails, sell price for success is set to be more than 100 and only show gems with 10 or more listings [click here](https://docs.google.com/spreadsheets/d/1qcYu22DIwEORUYuTJNnYnxS5ceQx8y6XJhVjBai_0lI/edit#gid=520131547&fvid=434671070)

* Filter 2: Great for mid league with buy price under 100, 50%-ish profit if it fails, sell price for success is set to be more than 200 and only show gems with 10 or more listings [click here](https://docs.google.com/spreadsheets/d/1qcYu22DIwEORUYuTJNnYnxS5ceQx8y6XJhVjBai_0lI/edit#gid=520131547&fvid=1816347774)

* Filter 3: Has the same settings as Filter 2 but includes awakened gems but keep in mind they take longer to level good if you don't want to buy gems often [click here](https://docs.google.com/spreadsheets/d/1qcYu22DIwEORUYuTJNnYnxS5ceQx8y6XJhVjBai_0lI/edit#gid=520131547&fvid=1324263742)


