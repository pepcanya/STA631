NAME: Josep Canyadell

Class: STA631

## PORFTOLIO DETAILS:

The following files are the ones that were created during the class of
Statistical Modeling and Regression. 
The file contains several files that prove and show the knowledge acquired
during this class.

You should see the following files, and different datasets used to perform the tasks:

- pepcanyadell.md
- activity02.Rmd
- activity03.Rmd
- Simple Linear Regression for General Audience.Rmd
- mini-competition.Rmd
- stock_prediction.Rmd


The first file is called: pepcanyadell.md

This was the first activity done during class. Several R Markdown functions 
were used and it was very helpful to get started with the differnt ways of 
writing in R in order to make it more visual and understandable for the 
audience. 

The second file is called: activity02.Rmd:

This code snippet involves analyzing data related to students' study hours and their exam scores. It starts by loading necessary tools, or packages, to work with the data effectively. The dataset contains information about how many hours students studied and the scores they achieved. The goal is to uncover any potential connection between study hours and scores. Visualizations are created to better understand the data: histograms provide insights into the distribution of study hours and scores, while a scatter plot illustrates the relationship between the two variables. Additionally, the code calculates the "sum of squared residuals" to assess how well a line fits the scatter plot, indicating the model's predictive accuracy. Furthermore, a linear regression model is constructed, acting as a mathematical rulebook that predicts scores based on study hours. This model is trained using the dataset, and its output provides numerical insights into the relationship between study hours and scores. In essence, this code snippet guides us through the process of exploring and interpreting the connection between study hours and exam scores, combining visualizations and mathematical models to gain a comprehensive understanding.

The third file is called: activity03.Rmd:


In this coding adventure, I'm like a detective exploring car data. First, I gather special tools (packages) to help me understand the data better. Then, I dive into a collection of car facts that include things like how far cars can go on a gallon of gas, how strong their engines are, and how heavy they are. I make pictures that show how these car facts are connected, like connecting dots to see patterns. Using a clever trick called "multiple linear regression," I try to figure out if one car fact can help predict another. It's like guessing if knowing the engine strength and weight can help guess how much gas a car needs. To make things even more interesting, I create a fancy 3D picture that shows the relationships between these car facts. It's like arranging toy cars to help us see how they're related. Overall, I'm solving the mystery of car data and turning it into useful knowledge.


The third file is called: Simple Linear Regression for General Audience.Rmd

I decided to work on my own in this project in order to practice Simple Linear Regression, but
also to provide the results in a different way in order to show it to General audience or to 
people that are not necessary experts in the field.
In this project, we embark on a computational exploration of iris flower data, aiming to decipher relationships between different attributes. Through a carefully crafted code, we lay the groundwork by ensuring we have the right tools available. We then introduce the iris dataset, unveiling intricate details about the sizes of various flower parts. Our goal is to uncover whether we can accurately predict the length of one part based on the width of another, a task approached with the aid of mathematical models. The code efficiently generates visual representations, presenting dots on a graph and drawing lines to establish predictive patterns. The outcomes of our analysis provide valuable insights, revealing the extent to which one attribute can anticipate changes in another. However, the code also highlights the limitations of our predictions, signaling instances where our assumptions might not hold true. This project underscores the dynamic interplay between mathematics, data, and visualization, guiding us in understanding the intricate relationships within the natural world.


The fourth file is called: mini-competition.Rmd

This project was done during class with a group and we were asked to predict future inventory needs for various products using the dataset inventory. Our goal was to create predictive models for each unique product to forecast the number of items sold in future weeks. 
We aimed to create predictive models for individual products to anticipate their sales in upcoming weeks. Our exploration began with converting weekly sales into monthly data, categorizing them as sold or not. We then split the data into training and testing sets and built a logistic regression model to predict sales, factoring in the month and product. Notably, December and June showed significant sales decreases from the previous year, while sales fluctuations ranged widely across products. Visualizations, such as a grouped bar plot, illuminated sales predictions with a 75% confidence threshold, helping us identify consistent sales trends and spikes. Looking ahead, we aspire to refine the model further to achieve higher accuracy, which will be crucial for efficient stock management and meeting customer demands during peak sales periods. Overall, this project empowered us to employ data-driven insights to navigate sales trends, optimize inventory management, and establish a foundation for informed decision-making in stock control.


The fifth file is called stock_prediction.Rmd:

For the final project of the class I decided to analyse different stock prices and try to predict it's future price. I decided to combine both Data Science and Analytics and Finance since my undergrad was in Business Finance. I was always curious about the stock market and it was something that intrigued me since I was younger.
In this project, the primary objective was to analyze and forecast the stock prices of three prominent companies—AAPL (Apple), MSFT (Microsoft), and GOOG (Google)—spanning a two-year period. The project encompassed a structured series of steps, commencing with data collection and proceeding through exploratory data analysis, stock comparison, return computation, trend identification, regression analysis, and ultimately, forecasting.

The journey began with the collection of stock price data utilizing the "quantmod" package. Historical stock prices were fetched from January 2021 to January 2023 for the chosen companies. The data for each stock was stored in separate variables (AAPL, MSFT, GOOG) and examined using functions like head() and summary() to gain an initial understanding of the dataset. Visual representations, including line plots and candlestick charts, were generated to visualize the stock price trends.

A pivotal analysis step involved calculating daily stock returns. The diff() function was employed to compute differences between consecutive days' closing prices, and this information was utilized to assess the profitability of each stock over the specified period. The calculated returns were then displayed graphically to provide insights into the stocks' performance and correlations.

To delve deeper into identifying trends, moving averages were employed. Moving averages smooth out price data to reveal underlying patterns and potential trends. Different moving averages were applied to the stock prices, and the resulting charts visually demonstrated how these averages respond to the variations in prices.

The project then transitioned to regression analysis, where linear regression models were fitted to the stock prices against time. The relationships between stock prices and time were assessed for each company. The regression models were summarized using the summary() function, providing coefficients, p-values, and R-squared values that indicated the strength and significance of the relationships.

To enhance predictive capabilities, ARIMA (AutoRegressive Integrated Moving Average) models were introduced. These models are specifically designed for time series forecasting and were utilized to predict the next day's closing prices for each stock. The predicted values were derived using the auto.arima() function, and forecasts were presented alongside the actual stock prices to visualize the model's performance.

Concluding the analysis, the project highlighted the intricate nature of predicting stock prices. While the ARIMA models provided insights into potential future prices, they also underscored the complexities and uncertainties inherent in stock market dynamics. The importance of combining advanced data-driven techniques with domain expertise and comprehensive decision-making was emphasized.

In future endeavors, exploring more sophisticated machine learning techniques, incorporating external data sources, and engaging domain experts could further elevate the accuracy of predictions. Ultimately, the project demonstrated that while data analysis and modeling can provide valuable insights, prudent financial decisions should encompass a holistic approach that considers a wide array of factors influencing stock prices.




CONCLUSION: 


The portfolio files provided me with a wide range of insights into the world of statistical modeling and analyzing data. Through various projects, I gained a deeper understanding of how to manipulate and understand information, create helpful visualizations, and even predict future outcomes. Using R Markdown, I was able to turn complex data into easy-to-follow stories. By studying how much students study and how well they do on tests, I discovered how to predict test scores using a method called linear regression. When I explored car data, I learned how different car details are connected and can help us make predictions. Switching gears to finance, I dived into stock prices, using advanced methods like moving averages and ARIMA models to forecast future prices. Together with a group, I tackled real-world problems, like figuring out how many products a store might sell in the future. In essence, the portfolio took me on a comprehensive journey, showing me how to find meaningful insights from data and make informed decisions in various fields.

