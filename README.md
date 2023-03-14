# All You Need To Know About the United Nations Sustainable Development Goals.

![](https://github.com/becomingtechsis/United-Nations-Sustainable-Development-Goals-2021/blob/main/UNO%2017%20sdgs.jpg)

## Introduction
The Sustainable Development Goals (SDGs), also known as the Global Goals, are a collection of seventeen interlinked objectives adopted by the United Nations in 2015 as a universal call to action to end poverty, protect the planet, and ensure that by 2030 all people enjoy peace and prosperity. 
I created a custom theme using the color palette of the [United Nations Sustainable Development Goals ](https://unstats.un.org/sdgs)

## Dataset 
The data is from the UN’s Sustainable Development Goals, specifically focusing on the indicators they are measuring. 
- This visualization uses 3 datasets.
1.	SDG Indicator Data.
2.	Color palette and image info.
3.	json theme file.

## Data Visualization
Using the [Hex Color Picker browser extension](https://chrome.google.com/webstore/detail/hex-color-picker/eamkimleiebmdpifljjfilhbaehclahg/related?hl=en) for Chrome, I gathered the hex codes for each of the 17 SDGs. Thereafter, I used the [PowerBI.Tips theme generator](https://themes.powerbi.tips/themes/palette) to create a custom theme.  

![](https://github.com/becomingtechsis/United-Nations-Sustainable-Development-Goals-2021/blob/main/color%20palatte.png)

Proceeded to downloaded the template as a JSON file and uploaded it to the Power BI desktop. 
```json
{
  "name": "My New Theme",
  "dataColors": [
    "#e5233d",
    "#dda73a",
    "#4da147",
    "#c7212f",
    "#ef402d",
    "#28bde5",
    "#fbc412",
    "#a31c44",
    "#f16d31"
  ],
  "visualStyles": {}
}
```
Sourcing for the report images URLs,  
- I got the URL for each of the SDG icons for the [primary image](https://github.com/becomingtechsis/United-Nations-Sustainable-Development-Goals-2021/blob/main/UNO%20SDG%20Colors%20and%20Images.xlsx)
- Grabbed a secondary image directly from the PDF annual report.
- Used postimages.org to turn screenshots into image URLs.
Then I set the data type of my image columns to Image URL.

# Dashboard
Link to the  [Power BI Dashboard](https://github.com/becomingtechsis/United-Nations-Sustainable-Development-Goals-2021/blob/main/UNO%20SVG%202021.pbix)

# Preview
![](https://github.com/becomingtechsis/United-Nations-Sustainable-Development-Goals-2021/blob/main/Home%20page.png)
![](https://github.com/becomingtechsis/United-Nations-Sustainable-Development-Goals-2021/blob/main/poverty.png)

For my goals selector, I used the Collage by Cloudscope custom visual. While for the secondary image (the large image associated with each goal) I used the Simple Image custom visual. Did some custom formatting to make the background colors match the color associated with the SDG goal.
