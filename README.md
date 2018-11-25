# Food For Good
## Abstract
In this project, we are going to dig deeply into the several pieces of information we have about the products that are registered in the open food fact dataset. Our goal is to identify the impact of the food products that we consume on the Human Health, focusing on two categories: the pollution generated by the products, through the carbon footprint, and the  composition of the food we eat, based on the different macros these different types of food provide and also on their micros.


## Dataset

Open Food Facts: https://world.openfoodfacts.org/data

We chose to work on the CSV dataset. It sized only 1.7Gb and after doing a quick research, we concluded that exploring it locally and using Pandas is perfectly doable even if it could take some time.

After downloading and exploring the dataset, that contained roughly 700 000 lines and 173 columns, we found that the NaN values are prevalent (all the columns have at least one NaN value in them and some of them are all empty). So we needed to decide how to deal with them, but this would depend on the side of the dataset that we want to study because we cannot remove all the NaNs. Instead, we can only drop them after deciding on the important column of each step.

After analysing the dataset, and thinking about what is doable and what is not, we decided to direct our study to the Human Health, focusing on two categories: the pollution generated by the products, through the carbon footprint, and the  composition of the food we eat. 

## Research questions
We came up with a first plan:
### A- Carbon Footprint/pollution
What are the goods that have the highest carbon footprint? How do we calculate the carbon footprint? What do we include? 
Correlation between meat/protein and carbon footprint ?
Highest plastic users for food packaging ?

### B-  Quality of food 
- How are the products grades distributed on the nutrition scale (A to E)? Are there more products with good or bad scores?
- What are the worst ingredients used in everyday products? (carcinogens ingredients, products that contain palm oil, etc) Are they prevalent?
- Which products contribute to malnutrition? How much sugar do we eat ? (sodium, additifs) differentiated by countries.
- How does food quality change over the years ?

### C- Correlation between Carbon Footprint and Quality of food

## A list of internal milestones until project milestone 3(December 16th)

- Sight the data and improve our analysis.
- Classify the quality of the food.
- Continue exploring the data using some good visualization tools.