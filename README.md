# Capstone-Project-I: The Film Industry In Asia
 
# Objective
Since 2012, the box office grosses in China and Japan appear to be showing consistent growth over time. As such, these markets would be of interest to the film industries. However, it isn't clear which factors are behind the box office grosses. Is the growth driven by increasing attendance or increasing ticket prices? The goal of this project is to use statistical analysis and machine learning to identify the underlying patterns and driving forces behind the box office in these countries.

# Target Audience
This study would benefit the film industry and its partners. By understanding the causes of box office growth, the film industry could adjust its business practices to promote and maintain this growing market. If the study shows that a rising box office gross is driven by increasing attendance, then the industry should increase the number of screens and market to a wide audience to make the film more accessible to consumers. Conversely, if growth is driven by ticket price, then the industry should focus on catering towards a more niche audience, providing premium services, or raising ticket prices.

# The Data
The main box office dataset was obtained from Kaggle.com. This dataset contains information on annual grosses, number of tickets sold, number of screens, and ticket prices for both China and Japan from 2012 to 2016. Furthermore, this dataset was supplemented with additional information to adjust for purchasing power parity (PPP), population, and wage. 

# Approach
1. Data wrangling in Microsoft Excel condenses the seperate datasets into two CSV files representing China and Japan. 
2. The data set was uploaded in Jupyter notebook where they are converted into dataframes
3. Using the matplotlib and seaborn libraries, the dataset was visualized using line graphs, bar graphs, and color mapping
4. Inferential statistics tested the validitiy of the trends found in the visualization. Independent T-Test compared the separate variables between the two countries. Pearson correlation identify the variables that correlate with box office. 
5. Machine learning tests results of the inferential statistics and deduces possible trends
