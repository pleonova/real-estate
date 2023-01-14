# Silicon Valley Real Estate
[A real estate heat map of Silicon Valley (2021)](https://public.tableau.com/app/profile/paula/viz/RealEstateAnalysisHeatMap-SiliconValley/1HouseSalesSqftLotSize)

[<img alt="Interactive Tableau Heat Map Visualization" width="400px" src="https://github.com/pleonova/real-estate/blob/main/Screenshots/sold_houses_sqft_lot_size2.png" />](https://public.tableau.com/app/profile/paula/viz/RealEstateAnalysisHeatMap-SiliconValley/1HouseSalesSqftLotSize)


## Features

**Color: Sale Price**
Click on multiple colors in the key to highlight the houses in the map.
- Colors are coded in increments of $200K
- The values shown in the key are the minimum value (so if it shows $1M then it means that the houses highlighted will be from $1M till $1.2M)
- You can select multiple colors by holding down your mouse (or the Shift button)
- You can also use a lasso to select houses in a particular region and update the bar chart below

**Bar Chart: Monthly Aggregate Sales (with Median and Average)**
Use the filters to select homes you are interested to see the Median prices. 
- Bottom of Dashboard #2 shows all the houses including the Median (more informative) and the average
- Clicking on any one home will in the bar chart will highlight it on the map (click on a white space in the bar graph to remove the temporary filter and see all the homes again)

**Bubble Size: Square Foot Radius - 2 Types**
Explore how big the house is relative to the lot size.
- The outer faint circle represents the lot square footage
- The inner dark circle represents the house square footage

**Bubble Tooltip**
On hover, you can see details about the home including address and a hyperlink to house on redfin.com
- Some tooltips will include a direct link to the house on redfin (use this to quickly navigate to the site to look at photos and other details about the property)

**Filters: Number of Beds, Bathrooms
Use these filters to better understand costs based on your requirements.
- Filter homes based on how many bedrooms and/or bathrooms they have

**Filters: Sale Price and Date**
Narrow down the date range and the price of homes 
- Filter the the date range for underlying data to view different time periods
- *Tip: The markets change frequently, so looking at how the last three months performed is probably most helpful as well as a general yearly trend (summer tends to be higher priced homes, while winter has fewer homes for sale).*

**Filter: Favorites**
(If you have an account on Redfin, you can favorite houses)
- Downlaod file includes a field for your favorites which can be displayed exclusively on the map
- Ability to highlight your favorites while keeping the other homes on the map



## Upload your own data

Redfin makes this pretty straightforward and all you need to do is download a csv. You can go to their support article [here](https://support.redfin.com/hc/en-us/articles/360016476931-Downloading-Data-), but it is honestly just a few clicks. Just note that they have a limit on how far in data you can go and how much you can download in one go.
