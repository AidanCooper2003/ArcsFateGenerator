This is for use with [CardMaker v.1.3.0.0](https://github.com/nhmkdev/cardmaker/releases/tag/v.1.3.0.0)

This cmp file and provided csv files used in CardMaker will let you quickly prototype entire fates for [Arcs: The Blighted Reach](https://ledergames.com/products/arcs-the-blighted-reach-campaign-expansion)
This uses files provided by Leder Games [here](https://ledergames.com/blogs/news/arcs-the-official-development-kit).

You must install the fonts Neue Kabel (body text) and FM BolyarPro (title text). FM BolyarPro is a paid font, but OPTICopperplate is an acceptable alternative. (Although it will require you to change all missing fonts in CardMaker)

In order to use, after filling in the csv files with your card data, go to file, export project to images, check "override layout file name formats" and put the following into file name format: "@[fatecode]_@[cardnum]_#L"

There are still some inconsistincies between these and the actual cards (namely indents, text centered around symbols, and occassional spacing issues), but overall it should be far quicker than making them manually.

Some notes:
- Booklets cover cards that go in the rules booklet that aren't edicts (laws, summit, etc.)
- Types of Objective Cards: Single (Consistent objective) RangeUp/RangeDown (Different for each player count) Grand (Grand Ambitions)
- Misc cards are not implemented (e.g. Doctrine, Economy, Monopoly, etc.)
- Since I originally made this for personal use, the files inconsistently use backgrounds with bleed and edited without bleed. 
- 
