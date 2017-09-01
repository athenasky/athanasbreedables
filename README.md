## Features

* Display breedables, valuable Pokémon (e.g., shinies or RNGs), or your NFT collection
* Faster loading than sharing a Google Sheets document
* Filter Pokémon by generation, gender ratio, Poké Ball, Egg Group, shinyness, etc.
* Search for Pokémon by name (thanks to [Armienn](https://github.com/Armienn))
* Generate a Reddit table to share just the Pokémon you want

## How to Use

### Preparation

1. Create a copy of this [spreadsheet](https://docs.google.com/spreadsheets/d/1djWEDpw4w0aLrurcnxkLupkzfB1Gw0_SHB8zZWY3Sts/edit?usp=sharing) (`File > Make a Copy…`).
  * Be careful with the 1st row (headers) of each sheet! Read the [FAQ](https://github.com/richi3f/pokemon-trading-spreadsheet/blob/master/FAQ.md#faq) before renaming or removing any column.
  * Name your sheets in the following format "FT:Name of my sheet", "LF:Name of another sheet" or "NFT:Yet another sheet". They will be sorted by the script.
  * You may duplicate the "TEMPLATE" sheets (up to a maximum of 8 tabs).
  * Do not move or rename the "CONFIG" or "DB" sheets.
2. Fill in "CONFIG" tab and start adding your Pokémon.
3. Make your spreadsheet public (`File > Publish to the web…`).

See [Demo](#demo) below if you're unsure of how to fill the spreadsheet and read the [**FAQ**](https://github.com/richi3f/pokemon-trading-spreadsheet/blob/master/FAQ.md#faq) to learn some cool tricks.

### Method 1: Beginner

Find the ID of your spreadsheet and paste it at the end of this link: `https://pokemon-trading-spreadsheet.tumblr.com/?spreadsheet-id`

Example: `https://pokemon-trading-spreadsheet.tumblr.com/?1P9wMb9e0YbhcOua9RQeRCJjllf_L77uV-7i4Q0Yor0o`

That's it! Share the resulting link with your potential trade partners.

### Method 2: Advanced

Use any of the following methods if you want a custom URL or want to make changes to the script/styling.

#### Method 2A: Tumblr

1. Create a new Tumblr blog and go to `Account > Edit Appearance > Edit theme > Edit HTML`.
2. Copy [this](https://raw.githubusercontent.com/richi3f/pokemon-trading-spreadsheet/master/tumblr_theme.html) and then click `Update Preview` followed by `Save`.
3. Edit the Theme Options with your spreadsheet's ID and personal information.
4. Go to `Advanced Options` and set `Use default mobile theme` to false.
5. Click `Exit` and you're set to share your Tumblr link.

Do note that Tumblr's Preview does not work with this theme. You will not be able to see your Pokémon while the theme is being applied.

#### Method 2B: GitHub Pages

1. Clone this repository.
2. Edit `config.js` with your spreadsheet's ID and personal information.
3. Publish ~~or perish~~ (go to `Settings` and set the `Source` to `master branch` under the GitHub Pages header).

#### Method 2: How to Update

This is only for those using **Method 2**. If you're using Mehtod 1, any changes here will be reflected automatically.

If there's been an update, you will need to replace files on your end with the new ones. For Tumblr users, this means copying again the [theme](https://raw.githubusercontent.com/richi3f/pokemon-trading-spreadsheet/master/tumblr_theme.html). Those using GitHub Pages will have to download the files I have edited and upload them to their repository.

## Demo

[Google Document](https://docs.google.com/spreadsheets/d/1P9wMb9e0YbhcOua9RQeRCJjllf_L77uV-7i4Q0Yor0o/edit?usp=sharing) → [Result](https://richi3f.github.io/pokemon-trading-spreadsheet/)
