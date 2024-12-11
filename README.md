# World Happiness Records Data Visualizaton


## Introduction

The project aims to explore the relationship between various factors (such as GDP, life expectancy, freedom to make life choices, corruption perceptions, and social support) and happiness scores across different countries and regions from 2015 to 2023. By utilizing data visualization techniques, the project presents insights into how these factors evolve over time and influence global happiness levels. 

The visualizations are created using Python libraries, including **Matplotlib**, **Seaborn**, and **Folium**, in Google Colab. These visualizations showcase trends, relationships, and disparities in happiness scores across different regions and countries.

## Visualizations

## Data Overview

<img width="566" alt="image" src="https://github.com/user-attachments/assets/b037fa4b-66d0-4508-ba4f-455208cd63a2">


### **Figure 1: Yearly Happiness Scores for Well-Known Countries (2015–2023)** - *HeatMap*

This heatmap visualizes the yearly happiness scores of several well-known countries from 2015 to 2023. Each row represents a country, with a color gradient from yellow (lower happiness scores) to red (higher happiness scores). This visualization allows us to observe how happiness scores have evolved over the years for each country, and compare trends across countries.

- **Insight**: Countries like Denmark, Australia, and the Netherlands consistently maintain high happiness scores, staying in the red zone (above 6.5) throughout the years.

<img width="425" alt="image" src="https://github.com/user-attachments/assets/7f47f426-29e6-4953-8e3f-835e2b0f5d53">

---

### **Figure 2: Average Happiness Score Over the Years by Region** - *Line Plot*

This line graph illustrates the variation in average happiness scores across different global regions from 2015 to 2023. It highlights regional disparities, with Western and North American regions consistently scoring higher, while regions such as Africa and South Asia have struggled to achieve higher happiness levels.

- **Insight**: Western and North American countries are at the top of the happiness spectrum, whereas African and South Asian countries face challenges in improving their happiness scores.

![image](https://github.com/user-attachments/assets/22620b77-60cc-4bb5-a44c-749b76228578)



---

### **Figure 3: Changes in Health Life Expectancy in Countries (2015–2023)** - *Map Plot*

This map visualization represents the change in health life expectancy across the globe from 2015 to 2023. A color gradient from purple (decrease) to yellow (increase) signifies the degree of change. 

- **Insight**: Sub-Saharan Africa faces significant setbacks in health life expectancy, while other regions like Europe continue to make progress.

![image](https://github.com/user-attachments/assets/0370cb43-8caa-4e35-aeff-86d6666125ce)




---

### **Figure 4: Plot Between Healthy Life Expectancy and Happiness Score** - *Regression Plot*

The analysis shows that happiness strongly correlates with social support, healthy life expectancy, and freedom, while generosity has a weaker link. This highlights the importance of social and economic factors in shaping happiness.

- **Insight**: A clear positive relationship is observed, indicating that higher life expectancy, freedom to make life choices, social support  contributes to increased happiness.

![image](https://github.com/user-attachments/assets/b2e3ed44-397f-415a-9313-b4a389ca6219)





---

### **Figure 5: Impact of Freedom to Make Life Choices and Healthy Life Expectancy on Happiness** - *Bubble Plot*

This bubble plot explores how the freedom to make life choices (x-axis), happiness score (y-axis), and healthy life expectancy (represented by bubble size) interact with each other. Larger bubbles represent countries with both high freedom and longer life expectancy, which are also happier.

- **Insight**: Countries with greater freedom and longer life expectancies tend to be happier, emphasizing the role of these factors in societal well-being.

![image](https://github.com/user-attachments/assets/4cb2e769-929f-4075-a6eb-8f61e6f626fb)


---

### **Figure 6: Plot Between GDP per Capita and Happiness Score** - *Bubble Plot*

This plot illustrates the relationship between GDP per capita and happiness scores, with a color gradient reflecting happiness levels. The strongest clustering occurs in the upper-right quadrant, where countries with both high GDP and high happiness scores are concentrated.

- **Insight**: Economic prosperity plays a significant role in enhancing happiness.

![image](https://github.com/user-attachments/assets/5287773e-069d-4bd1-abcf-dbd33470a47e)



---

### **Figure 7: Distribution of Perception of Corruption by Year** - *Violin Plot*

This violin plot visualizes the changes in corruption perceptions across the years. The plot shows an intensifying trend, with a noticeable widening of the violins post-2020, indicating increased corruption perceptions and growing polarization in public sentiment.

- **Insight**: The widening and rising medians of the violins signal a growing perception of corruption and a more polarized public opinion over time.

![image](https://github.com/user-attachments/assets/b5e185f2-a5c2-4322-bc43-5fc1a868e3aa)



---

### **Figure 8: Visualization of the Top Happiest Countries Having High Life Expectancy and High Social Support** - *Point Density Plot*

This global map shows the interplay between happiness, life expectancy, GDP, and social support. It emphasizes Europe as a hub where all these factors converge, with North America linking economic prosperity to happiness and South America highlighting strong social support.

- **Insight**: Happiness tends to be higher in regions where economic stability, health, and social support are prioritized.

![image](https://github.com/user-attachments/assets/31d3bd77-4257-4cea-a27b-0933f3efc6ba)




---

## Key Insights

- **Healthy Life Expectancy**: An increase in healthy life expectancy is strongly associated with higher happiness scores across the globe. Countries that have improved their public health systems tend to report higher levels of happiness.
  
- **Economic Prosperity**: There is a clear link between high GDP per capita and happiness scores. Countries with higher economic output tend to have better overall happiness outcomes.
  
- **Freedom to Make Life Choices**: Greater personal freedom correlates with higher happiness scores, suggesting that autonomy plays a crucial role in well-being.
  
- **Corruption**: The perception of corruption has increased over the years, highlighting the challenges in building trust and fostering societal well-being.
  
- **Regional Disparities**: Western and North American regions consistently rank high in terms of happiness, while regions like Sub-Saharan Africa and South Asia face greater challenges in achieving higher happiness scores.

## Data and Methodology

The data used for this analysis was sourced from the Kaggle Global Happiness datasets, which include metrics such as:

- **Happiness Scores**
- **GDP per capita**
- ** Healthy Life Expectancy**
- **Corruption Perceptions**
- **Freedm to make life choices**
- **Generosity**

I plotted the visualizations using Python libraries including **Matplotlib**, **Seaborn**, and **Folium** in Google Colab.

### Code Links:
- [GitHub Repository](https://github.com/bhavana-devulapally/world-happiness-report-data-visualizaton/)
- [Google Colab Link](https://drive.google.com/file/d/1tNUM2eyOofeMI5wQK9Kq7WVY8swcPCWC/view?usp=drive_link)

## Conclusion

The analysis and visualizations presented above shed light on the factors that contribute to global happiness. Through a combination of geographical, economic, and health-related data, this report provides a holistic view of how countries happiness levels have evolved and how they are influenced by different factors. 

By focusing on increasing healthy life expectancy, reducing corruption, improving GDP, and providing individuals with more freedom in making life choices, countries can continue to improve happiness scores and quality of life for their citizens.

