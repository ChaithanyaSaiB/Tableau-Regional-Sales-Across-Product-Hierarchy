# Tableau-Regional-Sales-Across-Product-Hierarchy

## Project Overview
This dashboard visualizes regional sales across a product hierarchy using the Superstore dataset. It includes a product hierarchy with right-aligned members, sorted levels, and region colors from a preset Tableau palette. Min/max value lines are shown as thin black lines with white borders for a clean look. A segment filter is also included for interactive analysis.

## Requirements Met
- **Dashboard Size:** 600px by 800px.
- **Product Hierarchy:** Includes both Category and Sub-Category.
- **Right-Align Hierarchy:** Each member in the hierarchy is right-aligned.
- **Sort Hierarchy:** Levels are sorted in descending order by the sum of sales.
- **Color Palette:** Region colors are assigned using a built-in Tableau palette.
- **Min/Max Lines:** Lines show the range from the lowest to the highest value in the hierarchy. These lines are thin black lines with white borders, positioned between horizontal grid lines.
- **Segment Filter:** A Segment filter is included for data interactivity.
- **Dataset:** Superstore dataset.

## Where to find the Problem Webpage

You can view the Workout Wednesday problem webpage: 

[Regional Sales Across Product Hierarchy by Luke Stanke](https://workout-wednesday.com/workoutwednesday-week-6-regional-sales-across-the-product-hierarchy/)

## How to View the Dashboard

You can view the completed dashboard on my Tableau Public profile:

[View Dashboard on Tableau Public](https://public.tableau.com/views/RegionalSalesAcrossProductHierarchy_17181474795450/RegionalSalesAcrossProductHierarchy?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link)

### Step-by-Step Instructions

1. **Download the Dataset:**
   - Get the Superstore dataset from [Data.World](https://data.world).

2. **Setup Tableau:**
   - Open Tableau and connect to the Superstore dataset.

3. **Create the Product Hierarchy:**
   - Drag `Category` and `Sub-Category` to create a hierarchy in the Data pane.
   - Right-align each member in the hierarchy.

4. **Sort the Hierarchy:**
   - Sort each level in descending order by the sum of sales.

5. **Create the Connected Dot Plot:**
   - **Create Dots:**
     - Drag `SUM([Sales])` to Columns.
     - Drag the hierarchy (Category and Sub-Category) to Rows.
     - Change the mark type to Circles.
     - Add the `Region` dimension to the Color card.

6. **Assign Region Colors Using the Hue Circle Palette:**
   - In the Color card, edit colors and choose the Hue Circle palette.
   - Click "Assign Palette" to automatically distribute distinct colors across regions.
   - Tableau uses the number of distinct members to assign colors that are as far apart as possible, providing a unique and informative color distribution.

7. **Add Black Borders to the Circles:**
   - Set the border color to black on the Color card.

8. **Create Lines to Connect Dots:**
   - Duplicate the `SUM([Sales])` pill on Columns to get a second marks card.
   - Change the mark type of the second marks card to Line.
   - Drag the `Region` dimension to the Path card to connect dots within each category.
   - Set a dual axis and synchronize axes.
   - Set the color of the lines to black and make them as thin as possible.
   - Drag the first green pill to the other side to ensure the line marks card is above the circle marks card, placing lines in the background.

9. **Set Row Banding:**
   - Use the formatting pane to add row banding to your visualization for better readability.

10. **Sorting Category and Subcategory:**
    - Right click on `Category` pill on Rows shelf and select sort in drop down options.
    - In the pop up menu, select sort by as field and sort order as descending.
    - Similarly do for even `Subcategory` to get expected sort order

11. **Format Gridlines and Final Touches:**
    - Format gridlines and other visual elements to meet the requirements.

12. **Create the Dashboard:**
    - Set the dashboard size to 600px by 800px.
    - Ensure all elements meet the formatting requirements and are placed correctly.


### Connect with Me
- [Tableau Public Profile](https://public.tableau.com/app/profile/chaithanya.sai.bommavaram/vizzes)
- [LinkedIn](https://www.linkedin.com/in/csbommavaram/)
