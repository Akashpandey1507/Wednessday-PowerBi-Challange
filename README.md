# Wednessday-PowerBi-Challange
This is weekly challange

### **Introduction**
Welcome back to Work out Wednesday! This week we’re building some basic visuals and use dynamic titles to visualize gas prices in the Rocky Mountain Region of the US (where I live!) over the past 3 years from the [U.S. Energy Information Administration](https://www.eia.gov/dnav/pet/hist/LeafHandler.ashx?n=PET&s=EMM_EPM0_PTE_R40_DPG&f=W).

Be sure you’re using the June 2023 version of Power BI desktop or later for this challenge, where you can find the new card visual.

![Sample](https://github.com/Akashpandey1507/Wednessday-PowerBi-Challange/assets/124170332/9c043fa9-60de-43e5-ac72-c5b164ecf461)

### **Requirements**
  **Get and transform data**

- This week’s data comes as a good old csv file. You can find it [here](https://4lbi-my.sharepoint.com/:x:/p/shannon/ER9gxHMdba9Ag5r8M0asxa0BsegloB2FdhWwm-B8-Eqy0g?e=2cIPNa).
- Transform the data so that you have gas prices for Jan 2020 to Aug 2023.
- Build a date table. This is only required if you have the default auto date/time setting turned off.
- I love [Matt Allington’s method](https://exceleratorbi.com.au/build-reusable-calendar-table-power-query/) – I use it in almost every report I build! Keep only the columns you need.
- Create a relationship between your Gas Price and Date table.
- Create measures for: min, max, and average gas prices, and labels for the dates corresponding with the min and max prices.

  **Build visuals**

- Start by creating or downloading any images you’ll need. I created images for my card visual (min, max, and average) and for the background of my line chart.
- Add a date slicer. Quick trick, if you don’t want the ends of your date slicer to be big bubbles, turn the responsive setting to off.
- Add a new card visual. Here I used my measures for both the values and the labels.
- Add a line chart displaying average price per gallon over time. Bonus points for working in a week-over-week price visual!
- Add any other visuals that you’d like!
- Ensure that all visuals meet the minimum standards of having alt text, that the tab order in your report makes sense, and that your color choices meet the minimum standards. 

### **Dataset**
This week’s data comes from the[ U.S. Energy Information Administration](https://www.eia.gov/dnav/pet/hist/LeafHandler.ashx?n=PET&s=EMM_EPM0_PTE_R40_DPG&f=W). Download the csv for the region that interests you!
