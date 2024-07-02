# E-Commerce_Analytics-Project

* ABSTRACT-
In this project, we will analyze and segment the customers of an e-commerce company by using the RFM approach. 
This will enable the e-commerce company to optimize their retention and acquisition strategies.

* ANALYSIS APPROACH
  1. Data Preprocessing & Cleaning- Clean and pre-process the data, ensuring consistent formatting and handling missing values.
  2. Exploratory Data Analysis
  3. Feature Selection

RFM Analysis
The RFM model considers three key customer behavior aspects:
Recency: How recently a customer has flown with the airline (Time Since Last Flight is recommended here)
Frequency: How often a customer flies with the airline (Number of Flights Booked)
Monetary Value: Total amount spent on flights within the timeframe (CLV)
By calculating these values for each customer, we can gain insights into their purchase habits.

4. Model Generation & Evaluation
K-Means clustering is an unsupervised learning technique that groups customers with similar RFM characteristics into distinct clusters. The Elbow Method was used to determine the optimal number of clusters (k) for segmentation.

Here, k=6 is chosen to segment the customers into distinct groups.

5. Segments Interpretation
   
According to the table above, we have three user clusters/segments:

![image](https://github.com/Diksha-06/E-Commerce_Analytics-Project/assets/105701051/4a5ea6be-e0dd-4779-ba38-d99c6eddba2a)

The analysis reveals 4 distinct customer segments:

Diamond - High-Value Frequent Customers. These are the most valuable customers. They purchase frequently and spend considerably (High Frequency, High Monetary Value, Less Recency)

Gold - Occasional Customers. These customers purchase frequently but might be potential high-value customers(Low Frequency, Moderate Recency, Moderate Monetary Value).

Platinum - These are high-spending customers with less frequency (Moderate Frequency, High Monetary Value, High Recency).

Silver - Customers with less frequency & recency (Moderate Frequency, Moderate Monetary Value, Moderate Recency).

* Actionable Steps-
We will create a customized promotion strategy for each cluster based on the understanding of the above clusters, as follows:

Diamond: There is no need to overwhelm them with vouchers/promotions (this saves us money), but we can optimize/leverage some kind of loyalty points to keep them around.

Gold & Platinum: We need to increase the frequency and monetary value of this segment. We can accomplish this by providing vouchers in the form of cashback (to enable repeat purchases), with a high eligibility threshold.

Silver: Our top priority is to get them transacting with us again after they've been churned for a while. To encourage them to do so, we could offer one or two large-benefit vouchers. This goes hand in hand with a steady stream of push notifications.
