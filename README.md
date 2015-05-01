# mtgicons

An adaption of the mtg icons as a vector font for use in apps, websites, etc. 

- All of the icons are contained within two files, which results in better performance for your site.
- The icons scale to any size, which is perfect for displaying on mobile, tablet and desktop.

# Usage

You can link directly to mtgicons by including the following file in your HTML &lt;head&gt; tag.

	<link rel="stylesheet" href="https://cdn.rawgit.com/jninnes/mtgicons/v1.1.4/dist/mtgicons.css" />

Then in your HTML file, the following markup:
  
	<!-- A white mana symbol -->
	<i class="mtg mana-w"></i>
	<!-- A 5 mana symbol -->
	<i class="mtg mana-5"></i>
	<!-- A white phyrexian mana symbol -->
	<i class="mtg phyrexian-w"></i>
	<!-- A r/g hybrid mana symbol -->
	<i class="mtg hybrid-rg"></i>
	<!-- A tap symbol -->
	<i class="mtg tap"></i>
	<!-- Dragons of Tarkir expansion symbol -->
	<i class="mtg dragons-of-tarkir"></i>

Produces the following output:

<img src="https://rawgit.com/jninnes/mtgicons/v1.1.4/src/svg/A01%20-%20Colored%20Mana%20-%20White.svg" height="30" width="30" />
<img src="https://rawgit.com/jninnes/mtgicons/v1.1.4/src/svg/B05%20-%20Colorless%20Mana%20-%20Five.svg" height="30" width="30" />
<img src="https://rawgit.com/jninnes/mtgicons/v1.1.4/src/svg/D01%20-%20Phyrexian%20Mana%20-%20White.svg" height="30" width="30" />
<img src="https://rawgit.com/jninnes/mtgicons/v1.1.4/src/svg/C07%20-%20Hybrid%20Mana%20-%20Red%20or%20Green.svg" height="30" width="30" />
<img src="https://rawgit.com/jninnes/mtgicons/v1.1.4/src/svg/E05%20-%20Tap%20Symbol%20-%20Post%208th%20Edition.svg" height="30" width="30" />
<img src="https://rawgit.com/jninnes/mtgicons/v1.1.4/src/svg/B2109%20-%20Dragons%20of%20Tarkir%20-%20Common.svg" height="35" width="35">

Add a rarity overlay to an expansion icon like so:

	<!-- Dragons of Tarkir expansion symbol, uncommon -->
	<i class="mtg dragons-of-tarkir uncommon"></i>
	<i class="mtg dragons-of-tarkir rare"></i>
	<i class="mtg dragons-of-tarkir mythic"></i>

See https://cdn.rawgit.com/jninnes/mtgicons/v1.1.4/demo/demo.html for the complete list of available icons!

# Building from source

Requires Node.js, uses NPM to run the build

	// run the build
	npm run build
  
	// run the build, and rebuild everything on change
	npm run watch
	// run the build, and rebuild less files on change
	npm run watch:less

	// testing using backstop JS is under development, but can be run with
	npm run test

# Contributions

Many thanks to 

- BaconCatBug 
- White Dragon
- Goblin Hero
- Skibulk
- Baka-Neku
- Qanadhar 
- Poopski

for the original SVG icons that have been used here.

# Legal stuff

Wizards of the Coast, Magic: The Gathering, and their logos are trademarks of Wizards of the Coast LLC in the United States and other countries. © 2015 Wizards. All Rights Reserved.

This repository is not affiliated with, endorsed, sponsored, or specifically approved by Wizards of the Coast LLC. 
