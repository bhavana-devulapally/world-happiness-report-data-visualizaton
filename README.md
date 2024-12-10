# world-happiness-report-data-visualizaton

Here's a well-structured and polished README based on the content you've provided. This version includes sections on the **Project Overview**, **Visualizations**, **Key Insights**, **Data and Methodology**, and **Resources**. You can enhance this further by linking images and project files in the relevant sections:

---

# World Happiness Report Visualization

## Project Overview

This project aims to explore the relationship between various factors (such as GDP, life expectancy, freedom to make life choices, corruption perceptions, and social support) and happiness scores across different countries and regions from 2015 to 2023. By utilizing data visualization techniques, this project presents insights into how these factors evolve over time and influence global happiness levels.

The visualizations are created using Python libraries, including **Matplotlib**, **Seaborn**, and **Folium**, in Google Colab. These visualizations showcase trends, relationships, and disparities in happiness scores across different regions and countries.

## Visualizations

### **Figure 1: Yearly Happiness Scores for Well-Known Countries (2015–2023)** - *HeatMap*

This heatmap visualizes the yearly happiness scores of several well-known countries from 2015 to 2023. Each row represents a country, with a color gradient from yellow (lower happiness scores) to red (higher happiness scores). This visualization allows us to observe how happiness scores have evolved over the years for each country, and compare trends across countries.

- **Insight**: Countries like Denmark, Australia, and the Netherlands consistently maintain high happiness scores, staying in the red zone (above 6.5) throughout the years.

![image](https://github.com/user-attachments/assets/f0845ee3-4199-4b05-9215-ae80242a1109?raw=true&width=5)


---

### **Figure 2: Average Happiness Score Over the Years by Region** - *Line Plot*

This line graph illustrates the variation in average happiness scores across different global regions from 2015 to 2023. It highlights regional disparities, with Western and North American regions consistently scoring higher, while regions such as Africa and South Asia have struggled to achieve higher happiness levels.

- **Insight**: Western and North American countries are at the top of the happiness spectrum, whereas African and South Asian countries face challenges in improving their happiness scores.

![image](https://github.com/user-attachments/assets/5ea29203-b307-4607-90df-c0436696b6c8)


---

### **Figure 3: Changes in Health Life Expectancy in Countries (2015–2023)** - *Map Plot*

This map visualization represents the change in health life expectancy across the globe from 2015 to 2023. A color gradient from purple (decrease) to yellow (increase) signifies the degree of change. 

- **Insight**: Sub-Saharan Africa faces significant setbacks in health life expectancy, while other regions like Europe continue to make progress.

![image](https://github.com/user-attachments/assets/c34f998f-0994-41c6-b909-d82463d63feb)


---

### **Figure 4: Plot Between Healthy Life Expectancy and Happiness Score** - *Regression Plot*

This regression plot demonstrates the relationship between healthy life expectancy and happiness scores. The positive correlation suggests that countries with longer healthy life expectancy tend to have higher happiness scores.

- **Insight**: A clear positive relationship is observed, indicating that higher life expectancy contributes to increased happiness.

![image](https://github.com/user-attachments/assets/84aac85d-696e-40a8-a749-595c79fc5a9b)


---

### **Figure 5: Impact of Freedom to Make Life Choices and Healthy Life Expectancy on Happiness** - *Bubble Plot*

This bubble plot explores how the freedom to make life choices (x-axis), happiness score (y-axis), and healthy life expectancy (represented by bubble size) interact with each other. Larger bubbles represent countries with both high freedom and longer life expectancy, which are also happier.

- **Insight**: Countries with greater freedom and longer life expectancies tend to be happier, emphasizing the role of these factors in societal well-being.

![image](https://github.com/user-attachments/assets/6b1c4129-4968-48e2-8225-95abc6fd8811)


---

### **Figure 6: Plot Between GDP per Capita and Happiness Score** - *Bubble Plot*

This plot illustrates the relationship between GDP per capita and happiness scores, with a color gradient reflecting happiness levels. The strongest clustering occurs in the upper-right quadrant, where countries with both high GDP and high happiness scores are concentrated.

- **Insight**: Economic prosperity plays a significant role in enhancing happiness.

![image](https://github.com/user-attachments/assets/9dd54f01-82a0-4914-a2e8-506890c05bde)


---

### **Figure 7: Distribution of Perception of Corruption by Year** - *Violin Plot*

This violin plot visualizes the changes in corruption perceptions across the years. The plot shows an intensifying trend, with a noticeable widening of the violins post-2020, indicating increased corruption perceptions and growing polarization in public sentiment.

- **Insight**: The widening and rising medians of the violins signal a growing perception of corruption and a more polarized public opinion over time.

![image](https://github.com/user-attachments/assets/ed50a96e-c4d1-4a58-ad79-a330b9690fe2)


---

### **Figure 8: Visualization of the Top Happiest Countries Having High Life Expectancy and High Social Support** - *Point Density Plot*

This global map shows the interplay between happiness, life expectancy, GDP, and social support. It emphasizes Europe as a hub where all these factors converge, with North America linking economic prosperity to happiness and South America highlighting strong social support.

- **Insight**: Happiness tends to be higher in regions where economic stability, health, and social support are prioritized.

![image](https://github.com/user-attachments/assets/8ef63fb2-d607-4ac9-a1f9-e5cbd4867e5c)


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
- **Life Expectancy**
- **Corruption Perceptions**

The visualizations were created using Python libraries including **Matplotlib**, **Seaborn**, and **Folium** in Google Colab.

### Code Links:
- [GitHub Repository](https://github.com/Puisque/hawaii_airbnb_data_visualization)
- [Google Colab Link](https://drive.google.com/file/d/1tNUM2eyOofeMI5wQK9Kq7WVY8swcPCWC/view?usp=drive_link)

## Conclusion

The analysis and visualizations presented in this report shed light on the factors that contribute to global happiness. Through a combination of geographical, economic, and health-related data, this report provides a holistic view of how countries' happiness levels have evolved and how they are influenced by different factors. 

By focusing on increasing healthy life expectancy, reducing corruption, improving GDP, and providing individuals with more freedom in making life choices, countries can continue to improve happiness scores and quality of life for their citizens.

