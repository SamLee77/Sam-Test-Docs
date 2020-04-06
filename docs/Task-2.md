---
layout: default
title: Create Sheets and Dashboards
nav_order: 3
---

# Create Sheets and Dashboards

---

**1**. On the bottom-left side, we open our first worksheet “sheet 1”.
>![](https://github.com/cysong12/Tableau-Desktop-Public-Edition/blob/gh-pages/assets/images/create-sheets-and-dashboards-1.png "Create Sheets and Dashboards 1")

<br>

**2**. Drag one of the fields from the Dimensions panel into the canvas. For this example, we will use **[Country Name]**
>![](https://github.com/cysong12/Tableau-Desktop-Public-Edition/blob/gh-pages/assets/images/create-sheets-and-dashboards-2.png "Create Sheets and Dashboards 2")

<br>

**3**. Each dot represents a country on the map and shows its relevant information. We can add more data into the current map by dragging a field from the _Measures_ panel. For this example, we will drag the **[CO2 Per Capita]** field. All the bubbles (countries) have been resized according to the quantity of CO2 emitted. To modify the color and gradient of the bubbles, drag the **[CO2 Per Capita]** field again but this time we drag it to the **[Color]** field in the _Marks panel_. The default colors will be applied once dropped.
>![](https://github.com/cysong12/Tableau-Desktop-Public-Edition/blob/gh-pages/assets/images/create-sheets-and-dashboards-3.png "Create Sheets and Dashboards 3")

<br>

**4**. To change to a different color scheme, click on the **[Color]** field and click the <b>EDIT COLORS…</b> button. 
>![](https://github.com/cysong12/Tableau-Desktop-Public-Edition/blob/gh-pages/assets/images/create-sheets-and-dashboards-4.png "Create Sheets and Dashboards 4")

<br>

**5**. An edit color window will pop up. We can choose our custom colors by clicking on the colored box on the right side or we can choose a preset color setting by clicking on the drop down selection on “Palette:”.
>![](https://github.com/cysong12/Tableau-Desktop-Public-Edition/blob/gh-pages/assets/images/create-sheets-and-dashboards-5.png "Create Sheets and Dashboards 5")

>![Note](https://github.com/cysong12/Tableau-Desktop-Public-Edition/blob/gh-pages/assets/images/note-icon.png?raw=true "Tip") **Note**: To switch the gradient order, click on the checkbox next to “Reversed”..

<br>

**6**. Now that we are done with _sheet1_, we can name it by right-clicking the _sheet1_ label and clicking on rename. We will name it “CO2 per Capita” for this guide.
>![](https://github.com/cysong12/Tableau-Desktop-Public-Edition/blob/gh-pages/assets/images/create-sheets-and-dashboards-6.png "Create Sheets and Dashboards 6")

<br>

**7**. Now that we have made a world map with data, we will make an example of a time-series chart. Click on the button right next to the “CO2 per Capita” for a new worksheet.
>![](https://github.com/cysong12/Tableau-Desktop-Public-Edition/blob/gh-pages/assets/images/create-sheets-and-dashboards-7.png "Create Sheets and Dashboards 7")

<br>

**8**. Double-click on **[CO2 Per Capita (metres)]** field from the _Measures_ panel. This is our x-axis data for the graph. Then double-click on the **[Year]** field from the _Dimensions_ panel. This is our y-axis data for the graph. From the graph, we can observe that CO2 emissions have increased over time. Now let’s drag **[Country Name]** to the canvas. We can see now that each line represents a country by hovering your mouse over a line on the graph. Clicking on it will highlight the line to become bolder while the other lines will become opaque. Once again, we can modify the colors of the lines. We can do this by dragging the **[CO2 Per Capita (metric …)]** field from the Measures _panel_ onto **[Color]** in the _Marks_ panel. A window will pop up like before, and we can customize it the same as before by either selecting a predefined color scheme or setting your own color scheme.
>![](https://github.com/cysong12/Tableau-Desktop-Public-Edition/blob/gh-pages/assets/images/create-sheets-and-dashboards-8.png "Create Sheets and Dashboards 8")

<br>

**9**. Now that we are done with the graph, we can rename it like we did with _sheet1_. Let’s name it <b>“CO2 Emission Changes Over Time”</b>.

<br>

**10**. Lets now combine the two sheets into the dashboard. On the bottom, where the sheet labels are, click on *icon picture* to create a new dashboard.
>![](https://github.com/cysong12/Tableau-Desktop-Public-Edition/blob/gh-pages/assets/images/create-sheets-and-dashboards-10.png "Create Sheets and Dashboards 10")

<br>

**11**. We can see the sheets we have created on the left panel. Drag each of the sheets onto the canvas in whichever position order you would like. Once you have done so, we can choose the size of the dashboard on the _Size_ panel on the left side. The size will depend on where you plan to share and embed the interactive charts. We will keep it at default size for this guide. 
>![](https://github.com/cysong12/Tableau-Desktop-Public-Edition/blob/gh-pages/assets/images/create-sheets-and-dashboards-11.png "Create Sheets and Dashboards 11")

<br>

**12**. You can remove the legends by clicking on the ‘close button. We will remove it for this guide.
>![](https://github.com/cysong12/Tableau-Desktop-Public-Edition/blob/gh-pages/assets/images/create-sheets-and-dashboards-12.png "Create Sheets and Dashboards 12")

<br>

**13**. We can add more elements to the visualizations such as a title, images, and even webpages. Lets add a title to the visualization by dragging the **[Text]** field onto the top center side. An edit text window will pop up. Create whatever title you would like. Once we are satisfied with how the visualization appears, we can <b>publish it to the Tableau Public Server.</b>

>![Tip icon](https://github.com/cysong12/Tableau-Desktop-Public-Edition/blob/gh-pages/assets/images/tip-indicator.png?raw=true "Tip") **Tip**: You can always go back to the dashboard sheet during any time if you need to modify some changes.










