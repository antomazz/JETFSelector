# JETFSelector
A simple interface to select and query ETF information from the website [JustEtf.com](https://www.justetf.com/en/)

## Requirements
In order to use JETFSelector you need to install the [GUI Layout Toolbox](https://it.mathworks.com/matlabcentral/fileexchange/27758-gui-layout-toolbox), available in the Matlab file exchange (also available from the Add On library directly from within Matlab).

## How to use 
After installing GUI Layout Toolbox, you just need to navigate within the main folder of JETFSelector and launch the script JETFSelector.m
The tool will connect to the JustEtf website to download the list of all available ETF, ETC and ETN. Few filter options are available to easily identify the assets of interest. 
The user can therefore select one or more assets in in the dual list object. Clicking on Apply, the code will exit the interface and return a structure of structures, whose fields are the selected ETF isins. Each ETF structure instead contains the main asset downloaded from [JustEtf.com](https://www.justetf.com/en/).

![Screenshot 2024-03-17 173720](https://github.com/amazzola90/JETFSelector/assets/107709367/db0dec57-2da0-4673-9c77-3a4dc0ca0ba8)

A search bar is also available to search for assets using a key word present in the name, or the asset isin or ticker.

![Screenshot 2024-03-17 180459](https://github.com/antomazz/JETFSelector/assets/107709367/442227ae-fa75-49df-9f35-f900c6185df2)


## Acknowledgements
This work was inspired by the public repository of theperu available [here](https://github.com/theperu/justETF-complete-ETF-scraper).
