## Indian-Airlines-Ticket-Price
#### Objective
As an aviation enthusiast, I always look forward to flying whenever I plan to travel. Since the Covid-19 pandemic ended, aviation market began to recover slowly from rock bottom ticket prices in peak of pandemic. With the war in Ukraine and rise in ATF prices, ticket prices have been through the roof reaching new high. As a result of this, I decided to do an exploratory data analysis for ticket prices to better understand the factors affecting them in India. I aim to answer questions like No. of flights available across India, Ticket availability across different class, Price range across different class, etc. Check out the project <a href= "https://github.com/dagarmohit272/Indian-Airlines-Ticket-Price-/blob/main/Indian%20Airlines%20Ticket%20Price%20EDA%20by%20Mohit.ipynb">here</a>. Here we have performed EDA on dataset using Python in Jupyter notebook
#### About the dataset
Data is gathered from the Kaggle and considered as secondary data. The dataset includes details on the ticket booking alternatives available through the website "Easemytrip" for flights between India's top 6 metro areas. The cleaned dataset contains 11 characteristics and 300261 datapoints. Data was gathered in two stages: for business class tickets and for economy class tickets. The site provided a total of 300261 unique flight booking possibilities. 50 days of data were gathered, from February 11 to March 31 of 2022.
#### Power BI Visualization Dashboard
Click <a href= "https://github.com/dagarmohit272/Indian-Airlines-Ticket-Price-/blob/main/Indian%20Airline%20Ticket%20Price%20Dashboard%20snapshot.png">here</a> to view dashboard snapshot

Using Power BI Dashboard one can quickly get to know ticket prices between different cities flying with different airlines in different classes along with flight duration.
#### Conclusion
- 'Air Asia' offers the cheapest flight tickets while flying Economy class while 'Air India' is cheapest while flying Business class.
- Booking tickets 3-7 weeks before travel will be cheaper than buying them within 3 weeks of travel as prices rise rapidly in 2-20 days period. Tickets can be cheap when bought just 1 day before however they might not be as cheap as when bought more than 3 weeks before
- Ticket price grow linearly with duration of flight peaking when duration of flight reaches 20 hours. However due to some outliers they again fall for for flights with duration of more than 20 hours. Relation can be approximated by 2nd degree curve
- Flight departing late at night and arriving early morning or late at night are cheapest.
- Flight prices increase with increase in number of stops.
Delhi offers the cheapest flights while Hyderabad is most expensive city to fly
