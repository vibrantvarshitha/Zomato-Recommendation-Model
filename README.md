

# Zomato Recommendation Model








![zomato-online-order](https://github.com/anishkatoch/Zomato-Recommendation-Model/assets/130006013/cbae261d-585f-44dc-a298-3620df9be28f)










**Zomato, a pioneering Indian multinational restaurant aggregator and food delivery company, was established in 2008 with its headquarters in Gurugram, Haryana, India. Originally conceived as a restaurant review and discovery platform, Zomato has rapidly evolved into a trailblazing food tech enterprise.**

**Through relentless innovation, a technology-driven approach, and an unwavering commitment to customer satisfaction, Zomato has emerged as a dominant force in the dynamic food delivery and restaurant landscape. Continually pushing boundaries, Zomato's comprehensive services have reshaped the way people explore, order, and enjoy culinary experiences.**



<br>
<br>

# <img src="https://user-images.githubusercontent.com/106439762/181935629-b3c47bd3-77fb-4431-a11c-ff8ba0942b63.gif" width="48" height="48"> **User's Manual**

| Files| Description |
| -------------   | ------------- |
| **Zomato_model_Scrapping**  | This folder contains the ipynb code of the Web scrapping.  |
| **Zomato Data** | This file contain the  scraped data in Excel format. |
| **Zomato CSV**  | This file contain the  scraped data in CSV format. |
| **Zomato_ML_Project_Location_Prediction** | This folder contains the code of model building. |  
| **Linear Model Streamlit**  | This folder contains the code of ML model through Linear Regression.  |
| **mine**  | This folder contains the code of making the webpage that is both backend and frontend .  |
| **ZOMATO_MODEL_PPT**  | This file contain the presentation on this project using power point.  |

<br>







# Problem Statement 




In the bustling world of dining and culinary exploration, Zomato stands as a beacon of convenience and choice. However, amidst the vast array of restaurants, cuisines, and user preferences, a challenge arises - how to assist users in making informed dining decisions that align with their tastes, budgets, and locations? This project delves into the realm of data-driven solutions to address this challenge. By utilizing web scraping and machine learning techniques, the project seeks to curate a personalized dining experience for Zomato users in Bangalore. The challenge is to develop an effective recommendation system that considers various factors like average price, popular cuisines, and user feedback. The primary objective is to empower users with insightful recommendations that guide them to the perfect dining destination, enhancing their overall Zomato experience.







# Aimed to solve




This project aspires to revolutionize the way users discover and choose dining options in Bangalore through data-driven insights and recommendations. By harnessing data scraping and machine learning, the aim is to provide users with tailored suggestions that cater to their preferences, budgets, and locations. The project seeks to simplify the decision-making process for users while promoting local restaurants, cuisines, and exceptional dining experiences. Ultimately, it strives to make dining choices more personalized, convenient, and enjoyable, thereby enhancing the overall Zomato user experience in Bangalore's vibrant food scene.




# <img src="https://user-images.githubusercontent.com/106439762/181937125-2a4b22a3-f8a9-4226-bbd3-df972f9dbbc4.gif" width="48" height="48" > Quick Start

1.  **Data Scraping**: Used Python with libraries like Selenium and BeautifulSoup to scrape data from the Zomato website. The scraped data was then saved in a structured format.


2.  **Data Cleaning and Preprocessing**: Performed data cleaning and preprocessing using Python's data manipulation libraries, such as NumPy and Pandas. This step involved handling missing values, correcting data inconsistencies, and ensuring the data is in a clean and usable form.


3.  **Power BI Data Transformation**: Utilized Power BI to connect to the MySQL database and fetched the required data for analysis. In Power BI, the data was transformed using Power Query to ensure it aligns with the visualization requirements.


4.  **Dashboard Creation**: Designed an interactive dashboard in Power BI, using the transformed data, to visualize key insights into the West Bengal elections. The dashboard included visualizations and reports related to candidate information, constituency distribution, candidate demographics, political party affiliations, and other relevant details
    
<br>





# INPUT

![image](https://github.com/anishkatoch/Zomato-Recommendation-Model/assets/130006013/5335c919-0bcb-44f6-819d-ff8fd13ae8b8)
![image](https://github.com/anishkatoch/Zomato-Recommendation-Model/assets/130006013/27fedbf0-b70b-47d2-bbf8-a7e0f5d7524f)



# FINDINGS

![image](https://github.com/anishkatoch/Zomato-Recommendation-Model/assets/130006013/750bdc75-e478-4c2b-839b-a24aff8f4dd0)



# FEEDBACK

![image](https://github.com/anishkatoch/Zomato-Recommendation-Model/assets/130006013/75b0c89e-c754-4c18-ac11-5544a0b50d34)






# ANALYSIS



### 1. Average Price
- Our model calculates the average price range for dining at different restaurants in Bangalore. This helps users plan their budget for a meal out.



### 2. Popular Cuisine
- We identify the most popular cuisines in Bangalore based on user reviews and restaurant data. This feature allows users to explore and discover new culinary experiences.



### 3. Most Popular Restaurant
- We highlight the top-rated and most popular restaurant in Bangalore. Users can trust this recommendation for an exceptional dining experience.



### 4. Cuisine Details
- For each restaurant, we provide information about the cuisine it serves. Users can easily find out which cuisines are available at their preferred dining spot.



### 5. Popular Restaurants by Cuisine
- Users can explore restaurants that serve their preferred cuisine. We recommend the best places to enjoy a specific type of food based on user preferences.



### 6. Recommended Price
- Our model suggests an appropriate price range for dining based on the user's input preferences. This ensures that users can find restaurants that match their budget.



### 7. Recommended Location
- We recommend dining locations in Bangalore based on the user's preferred location and cuisine. This feature helps users find restaurants that are conveniently situated.



<br>

# Conclusion

- In our endeavor to enhance the dining experience in Bangalore, our Zomato recommendation model offers a valuable array of features.
- Features include calculating average price ranges, identifying popular cuisines, showcasing top-rated restaurants, and providing cuisine details.
- Our model equips users with essential information for a memorable meal outing.
- Personalized recommendations for price range and location simplify finding the perfect dining spot aligned with user preferences.
- Whether you're a local connoisseur of Bangalore's culinary scene or a visitor exploring its gastronomic delights, our model aims to be your trusted companion.


<br>
<br>
   
#  <img src=https://user-images.githubusercontent.com/106439762/178803205-47a08ce7-2187-4f96-b301-a2b68690619a.gif width="48" height="48" > Limitations
   
* Not enough data about users or items, making it difficult to give accurate recommendations.
* Struggle with updates in real-time, like new user preferences or changing item availability.
* Handle sensitive user data, so we need to prioritize privacy.
* Not enough information about certain items, especially those that are not popular or niche.
* Make recommendations more understandable and transparent.
* Better ways to measure recommendation system performance.


#  <img src=https://user-images.githubusercontent.com/106439762/178803205-47a08ce7-2187-4f96-b301-a2b68690619a.gif width="48" height="48" > Future Work
  
 * Alternative data sources 
 * Adapt and update recommendations in real time.
 * Privacy-preserving techniques
 * Fill missing values by analyzing patterns in user-item interactions to estimate the unknown values.
 * Build trust and understanding and take user feedback into account.
 * Explore new evaluation metrics that consider user satisfaction, diversity, or long-term engagement

#  <img src=https://user-images.githubusercontent.com/106439762/178803205-47a08ce7-2187-4f96-b301-a2b68690619a.gif width="48" height="48" > Challenges
- Not enough data about users or items, making it difficult to give accurate recommendations.
- Struggle with updates in real-time, like new user preferences or changing item availability.
- Handle sensitive user data, so we need to prioritize privacy.
- Not enough information about certain items, especially those that are not popular or niche.
- Make recommendations more understandable and transparent.
- Better ways to measure recommendation system performance.

- MODIFIED APP- https://miniature-space-parakeet-7v7qj7wwvpg53p4q4-8501.app.github.dev/

