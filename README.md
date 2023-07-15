# FlipkartWebScrapingUsingPython

# Web Scraping Using Python and Visualizing Flipkart shopping website(India)
![websraping](https://github.com/DurgeshwariNaikwade/FlipkartWebScrapingUsingPython/assets/96798708/9fcb2837-cbf6-4f4c-8294-ca854cc5858f)


I scraped laptop data from the Flipkart shopping site using Python and conducted exploratory data analysis (EDA) and visualization on the extracted data.

To begin, I used Python's web scraping libraries, such as **BeautifulSoup and requests**, to extract laptop information from the Flipkart website. This involved retrieving the relevant HTML elements, such as the laptop title, price, rating and operating system from the webpage's source code.

Once the data was successfully scraped, I proceeded to perform data cleaning and EDA on the dataset. This involved analyzing and summarizing the extracted laptop information to gain insights and understand the underlying patterns. I explored various aspects of the data, such as the distribution of laptop prices, the most common brands or models, and the relationship between ratings and prices.

To better understand the data, I employed data visualization techniques. By utilizing libraries like Matplotlib or Seaborn, I created visual representations such as bar graphs and box chart. 


Based on the findings from the EDA and visualization conducted on the scraped laptop data, the following observations were made:

1. Price vs Rating Bar Chart:
    - The bar chart comparing laptop prices and ratings revealed that laptops with a rating of 5 generally have higher prices compared to others.
    - Laptops with a rating of 4.9 offer a good balance between high ratings and relatively lower prices, making them an attractive option for those seeking laptops with good ratings at a more affordable price.
    - The cheapest laptops in the dataset typically have a rating of 3.8, indicating that lower-priced options may have slightly lower ratings.
    
![Price vs rating](https://github.com/DurgeshwariNaikwade/FlipkartWebScrapingUsingPython/assets/96798708/1537fb95-f49e-408c-818a-71a547c4431e)

    
2. Box Plot for Price:
    - The box plot for the price column indicated the presence of numerous outliers in the upper range of prices.
    - The graph showed a right-skewed distribution, suggesting that the majority of laptops fall within lower price ranges, while a few higher-priced outliers significantly impact the overall distribution.
    
![price-boxplot](https://github.com/DurgeshwariNaikwade/FlipkartWebScrapingUsingPython/assets/96798708/bc946513-39ee-4dcc-a175-8e5af916c4da)


These findings provide valuable insights into the relationship between laptop prices and ratings, as well as the distribution of prices within the dataset. By considering these observations, potential buyers can make informed decisions based on their preferences for ratings, pricing, and the presence of outliers in the laptop market.




.


References :

https://www.youtube.com/watch?v=XVv6mJpFOb0&t=860s

https://medium.com/analytics-vidhya/web-scraping-with-eda-and-visualization-using-python-a496ddf5f98e

https://towardsdatascience.com/web-scraping-indeed-com-e5591790736d

[https://nbviewer.org/github/rowandl/portfolio/blob/master/Webscraping Indeed.com/Webscraping Indeed.ipynb](https://nbviewer.org/github/rowandl/portfolio/blob/master/Webscraping%20Indeed.com/Webscraping%20Indeed.ipynb)
