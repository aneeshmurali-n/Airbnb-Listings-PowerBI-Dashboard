# Airbnb-Listings-PowerBI-Dashboard
This project is a Power BI dashboard analyzing Airbnb listings in New York City. Using the NYC Airbnb Open Data from Kaggle, this dashboard provides insights into Airbnb trends across NYC neighborhoods, including listing types, locations, pricing, and review patterns. It’s a valuable tool for understanding the Airbnb market in NYC and identifying potential opportunities or patterns in listing data.

![Screenshot 2024-11-15 174356](https://github.com/user-attachments/assets/873938d3-bcc0-446b-a5cf-db8e96a14f93)
![Screenshot 2024-11-15 180734](https://github.com/user-attachments/assets/21f3fb4f-46ae-4c4d-be40-c9caee60b9a2)
![map zoom](https://github.com/user-attachments/assets/d7d2e105-362b-452b-8474-3a1b8696f3e1)

## Dashboard Features
**The Power BI dashboard is organized into multiple sections, each providing a unique insight into NYC Airbnb listings:**
* **Room Type Distribution:** A donut chart showing the percentage of listings by room type (Entire home/apt, Private room, Shared room). Helps users understand the market share of each room type in NYC.
* **Geographic Map of Listings:** This interactive map displays the locations of Airbnb listings across NYC. Users can filter listings by room type, Location, Neighbourhood, Price, Minimum Nights, and Number of Reviews, and zoom in on specific neighborhoods to see listing densities and patterns.
* **Buttons to Switch Map View:** Dark, Aerial, Road. Users can adjust the appearance of the map to visualize the exact location.      
* **Aerial and Table View Button:** for viewing the instant summary of the current data in an interactive table.  
* **Reviews vs Month:** A line chart visualizing the trend in Airbnb reviews throughout the year. Peaks and troughs may indicate seasonal patterns or trends in booking behavior.
* **Airbnb Listings by Location:** A clustered column chart showing the number of Airbnb listings in each NYC borough (Manhattan, Brooklyn, Queens, Bronx, Staten Island) with further breakdowns by room type. This chart highlights which boroughs have the highest listing counts.
* **Average Price by Neighborhood:** A bar chart displaying the average price of listings in prominent NYC neighborhoods. This can help identify the most and least expensive areas for Airbnb accommodations.
* **Listing Name by Reviews:** line and stacked column chart showing the most reviewed listings alongside their review counts, providing insights into popular listings and customer engagement.
* **Listings** A Card To show the number of listings.
* **Sliders and slicers:** for filtering data based on (Location, Neighborhood, Room Type, Minimum Nights, Number of Reviews, and Price)

## Insights:
### Total number of Airbnb Listings: 48.879K


### Room type distribution 
![image](https://github.com/user-attachments/assets/468b731c-3508-4ae5-8dcd-6806d950d993)

* The Entire home/apt room type is dominating in New York City Airbnb Listings about 51.97% (25.41k) of the total listings. This suggests that many travelers to New York City prefer to have a full apartment or house to themselves during their stay.
* Private room shows the second largest dominance with 45.66% (22.33k) of the total listings. This indicates that private rooms are also a popular option for travelers, likely due to their affordability and the opportunity to meet other travelers.
* Shared rooms are the least common room type, making up only 2.37% (1.16k) of the total listings. This suggests that shared rooms are not as popular in New York City as in other destinations.
Overall, the pie chart shows that the Airbnb market in New York City is dominated by entire homes and apartments, followed by private rooms. Shared rooms are the least common option.

### Room type distribution based on Neighbourhood Group
* #### Manhattan:
  Total Listings: 21.652k<br>
  Entire home/apt Listings: 13.2k<br>
  Private room Listings: 7.98k<br>
  Shared room Listings: 480<br>

* #### Brooklyn:
  Total Listings: 20.098k<br>
  Entire home/apt Listings: 9.56k<br>
  Private room Listings: 10.13k<br>
  Shared room Listings: 413<br>

* #### Queens:
  Total Listings: 5.666k<br>
  Entire home/apt Listings: 2.1k<br>
  Private room Listings: 3.37k<br>
  Shared room Listings: 198<br>

* #### Bronx:
  Total Listings: 1.09k<br>
  Entire home/apt Listings: 379<br>
  Private room Listings: 652k<br>
  Shared room Listings: 60<br>

* #### Staten Island:
  Total Listings: 373<br>
  Entire home/apt Listings: 176<br>
  Private room Listings: 188<br>
  Shared room Listings: 9<br>
* #### Summary:
  Manhattan: Mostly entire homes/apartments
  Brooklyn & Queens: Balanced mix of entire homes/apartments and private rooms
  Bronx: More private rooms
  Staten Island: Small number of listings, balanced mix
  This indicates that while entire homes/apartments are popular across all neighborhoods, private rooms are especially popular in Brooklyn, Queens, and Bronx, likely due to affordability and social interaction opportunities.

### The Reviews vs Month: 
![image](https://github.com/user-attachments/assets/e28f7fd1-4a0d-489b-966e-9ded1b8f45c6)

**line chart shows a clear seasonal trend in Airbnb reviews, with a significant spike in July. Here are the key insights:**
  * Peak Season in June: Reviews hit their highest point in June, suggesting a peak in bookings, likely due to summer travel. This is a prime time for hosts to adjust pricing and availability.
  * Low Activity Outside Summer: The review count remains relatively low and stable throughout the rest of the year, indicating lower booking activity during off-peak months.
  * Seasonal Demand Pattern: This trend suggests that Airbnb demand in NYC is highly seasonal, with a surge in summer, which is helpful for hosts planning for peak seasons.

### The chart shows the average price of Airbnb listings in different neighborhoods of New York City.
![Screenshot 2024-11-15 204251](https://github.com/user-attachments/assets/6053a324-3629-4d73-9f07-541ab5088749)

  * The most expensive neighborhoods: Fort Wadsworth, Woodrow, and Tribeca have the highest average prices.
  * There is a wide range of prices across neighborhoods. The most expensive neighborhood is more than 10 times more expensive than the least expensive neighborhood.

### The chart shows the number of reviews and reviews per month for various Airbnb listings.
![Screenshot 2024-11-15 205143](https://github.com/user-attachments/assets/45e63682-7ad1-4d3c-aafb-9402718475c7)
![image](https://github.com/user-attachments/assets/75e3f0a0-0391-45f6-a279-23e1954390ca)
  * Private Room has the highest number of reviews and a consistent review rate over time.
  * HOME AWAY FROM HOME  has the highest peak in reviews per month, indicating a surge in popularity at one point.
    ![image](https://github.com/user-attachments/assets/91b27375-d0f0-4732-83ac-2667c895c4a1)

### Top 10 Entire home/apt Listings in Manhattan based on review count: 
![image](https://github.com/user-attachments/assets/ba4be2bc-69f1-4dfb-a6f9-93be01404028)

### Popular 102 places in New York City Airbnb Listings based on highest review count:
![image](https://github.com/user-attachments/assets/b1ea3332-c433-4527-9223-c459390e6879)

### Remark:
With this dashboard, we can interact and find many things in the New York City Airbnb Listings so download the dashboard project file open it with powerBI and enjoy.<br>
Best Regards,<br>
Aneesh Murali Nariyampully<br>



 

  



  










