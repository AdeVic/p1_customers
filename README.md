## Read Me


#### Required Software
Here, jupyter notebook is needed to run this analysis
The following libraries should be installed on the jupyter notebook
    * Pandas 
    * Numpy
    * Matplotlib
    * Seaborn
    

#### List of files included in the project
The following files are in this project: 
    1. p1_customers.ipynb
    2. p1_customers.xlsx

#### Data Cleaning 
    1. Cleanliness issues
        * The Customer_Segment, Store_Number and Responded_to_Last_Catalog were changed from object to category
        
    2. Tidiness issues
        * The state variable is not important for this analysis and was dropped 

#### Catalog Demand
* This dataset contains the record of cutomers of 10 local stores in Colorado and their average sales for a period of 8 years
* The aim of this visualization is to find prdictor variables that may help increase the average sales of the store
> The dataset contains the following variables:
    
    1. Name: The name of the customers 
    2. Customer_Segment: The category the customer belongs to
    3. Customer_ID: The unique identification number of the customer
    4. Address: The address of the customer
    5. City: Customer's city
    7. Statte: Customer's state
    8. ZIP: Customer's zip code
    9. Avg_Sale_Amount: Average sale from transactions
    10. Store_Number: The store's unique number
    11. Responded_to_Last_Catalog: Whether customer responded to catalog or not
    12. Avg_Num_Products_Purchased: The average number of products purchased by customers 
    13. #_Years_as_Customer: How long a customer have been buying from the store

> In this dataset, there are four categories of customer segment:
    
    1. Store Mailing List              
    2. Loyalty Club Only                
    3. Credit Card Only                
    4. Loyalty Club and Credit Card   
    
  
#### Summary of Findings
    1. The store mailing list has the highest number of transaction while the loyalty club and credit card has the lowest
    2. Denver has the highest number of transactions while Lone tree has the lowest number of transactions
    3. The distribution of average sale is right skewed, showing that there is posibility of outlier on the right. The average sale is between 0 to 1000
    4. The stores with the highest customers is in the following order; from highest to lowest: (100, 105, 106, 101, 104, 107, 103, 108, 109 and 102)
    5. There are few people that responds to catalog and the average sale is higher among those that did not respond to catalog


#### Key Insights 
    1. Getting more customers into the loyalty and credit card category will really increase the stores sales
