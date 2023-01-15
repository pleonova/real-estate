# Silicon Valley Real Estate
[A real estate heat map of Silicon Valley (2021 & 2022)](https://public.tableau.com/app/profile/paula/viz/RealEstateAnalysisHeatMap-SiliconValley/1HouseSalesSqftLotSize)

[<img alt="Interactive Tableau Heat Map Visualization" width="400px" src="https://github.com/pleonova/real-estate/blob/main/Screenshots/sold_houses_sqft_lot_size2022.png" />](https://public.tableau.com/app/profile/paula/viz/RealEstateAnalysisHeatMap-SiliconValley/1HouseSalesSqftLotSize)


## Features

**Color: Sale Price**<br/>
Click on multiple colors in the key to highlight the houses in the map.
- Colors are coded in increments of $200K
- The values shown in the key is the minimum value (so if it shows $1M then it means that the houses highlighted will be from $1M to $1.2M)
- Select multiple colors by holding down your mouse (or the Shift button)
- Use lasso to select houses in a particular region and update the bar chart below

**Bubble Size: Square Foot Radius - 2 Types**<br/>
Explore how big the house is relative to the lot size.
- The outer faint circle represents the lot square footage
- The inner dark circle represents the house square footage

**Bubble Tooltip**<br/>
On hover, see details about the home including bedrooms, square footage and address.
- Click on the bubble to see direct link to the house on redfin (use this to quickly navigate to the site in a new tab to look at photos and other details about the property)

**Filters: Sale Price and Date**<br/>
Narrow down the date range and the price of homes
- Filter the the date range for underlying data to view different time periods
- Update the price range
- *Tip: The markets change frequently, so looking at how the last three months performed is probably most helpful as well as a general yearly trend (summer tends to be higher priced homes, while winter has fewer homes for sale).*

**Filters: Number of Beds, Bathrooms**<br/>
- Filter homes based on how many bedrooms and/or bathrooms they have

**Bar Chart: Monthly Aggregate Sales (with Median and Average)**<br/>
- All the houses are ordered from highest to lowest each month including a Median cost as well as Average.
- Clicking on any one home will in the bar chart will highlight it on the map (click on a white space in the bar graph to remove the temporary filter and see all the homes again)

**Filter: Favorites**<br/>
If you have an account on Redfin, you can favorite houses and visualize them.
- Download file from Redfin includes a field for your favorites which can be displayed exclusively on the map
- Ability to highlight your favorites while keeping the other homes on the map



## Upload your own data

Redfin makes this pretty straightforward and all you need to do is download a csv. You can go to their support article [here](https://support.redfin.com/hc/en-us/articles/360016476931-Downloading-Data-), but it is honestly just a few clicks. Just note that they have a limit on how far in data you can go and how much you can download in one go.<br/>

[Screenshots of steps below](https://github.com/pleonova/real-estate/blob/master/UploadYourData)

1) Download CSV from Redfin.
2) Download Tableau Workbook or make a copy if you have a free Tableau Public account. You can also install a free 14-day trial (or just use a Tableau Public installation that you can only save by posting data to Tableau Public).
3) Go to **Data Source** tab at the bottom left and drag your files into the *Need more Data?* region.
4) Remove the old data source *redfin_2021_* under **Connections** on the top left.
5) Drag and drop your file(s). If more than one, hover the next one over the old one so you can do a UNION between the files.
6) Go to **#1 House Sales & Sqft/Lot Size** and update the *Sold Date* filter! Do not forget to do this, otherwise you will not see any of your data.
7) Lastly, hover over the disbtribution chart at the bottom and sort the prices.
8) Explore your own data!