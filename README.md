# EDA_Hotel_Booking_Analysis

# **Project Summary -**
Analysis of hotel bookings associated data is essential for all the hospitality commerce. The study gives the various aspects of booking behavior by the customers and provides the root map for improving the business.
The provided data have been categorized in City hotel and Resort hotel for deep understanding about the features.
The project deeds have been divided as following sections:
1.	Problem statement
2.	Business objectives
3.	Knowing the data
4.	Understanding the variables
5.	Data wrangling
6.	Data Visualization, Storytelling & Experimenting with charts 
7.	Conclusion

# **Problem Statement**

The most of the hotel industries facing challenges for predicting the influential parameters for customer bookings, most demand periods , less booking periods and how to improve the bookings.
This EDA project address the solution of following problems faced by the hotel industry
1.	Which are the months more demand for rooms and which are the month’s business need to be improved?
2.	Which meal types mostly preferred by the customer and which meal will be given less preference?
3.	What are the agents are active and inactive for booking the room?
4.	What are most preferred distribution channel by the customers?
5.	Which country customers are mostly visited and which country customers need to be attracted for more?
6.	What is the cancelation rate for both city hotel and resort hotel?
7.	What is the percentage of cancelation of repeated guests and new guests?
8.	Which year booking percentage will be more?
9.	Which months booking cancelations are more?
10.	How long most of the guests stay in city hotel and resort hotel?
11.	Which room types are mostly preferred by the customers?
12.	Which distribution channels did early bookings?
13.	What are the correlations between each variable?
14.	What is the relations between total people stayed and average daily rate value?

#### ** Business Objective**
The main objectives of this EDA project are discover and analyze the given data for finding the various influencing factors of hotel bookings. The study results will be utilized for business improvement.


Variable Description

*   Hotel: H1= Resort Hotel, H2= City Hotel
*   is_canceled : If the booking was canceled(1) or not(0)
*   lead_time : Number of days that elapsed between the entering 
*   date of the booking into the PMS(Property Management System) and the arrival date
*   arrival_date_year : Year of arrival date.
*   arrival_date_month : Month of arrival date.
*   arrival_date_week_number : Week number for arrival date.
*   arrival_date_day_of_month: Which day of the months guest is arriving.
*   stays_in_weekend_nights: Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel.
*   stays_in_week_nights: Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel.
*   adults : Number of adults.
*   children : Number of children.
*   babies : Number of babies.
*   meal: kind of meal opted for.
*   country : Country code.
*   market_segment: Through which channel hotels were booked.
*   distribution_channel : How the customer accessed the stay- Corporate Booking/Direct/TA.TO
*   is_repeated_guest : The values indicating if the booking name was from a repeated guest (1) or not (0).
*   previous_cancellations : Was there a cancellation before.
*   previous_bookings_not_canceled : Count of previous bookings not cancelled.
*   reserved_room_type : Code of room type reserved.
*   assigned_room_type : Code for the type of room assigned to the booking.
*   booking_changes : Count of changes made to booking.
*   deposit_type : Deposit type.
*   agent : If the booking happens through agents or not.
*   company : If the booking happens through companies, the company ID that made the booking or responsible for paying the booking.
*   days_in_waiting_list : Number of days the booking was on the waiting list before the confirmation to the customer.
*   customer_type : Booking type like Transient – Transient-Party – Contract – Group.
*   adr : Average Daily Rates that described via way of means of dividing the sum of all accommodations transactions using entire numbers of staying nights.
*   required_car_parking_spaces : How many parking areas are necessary for the customers.
*  total_of_special_requests : Total unique requests from consumers.
*  reservation_status: The last status of reservation, assuming one of three categories: Canceled – booking was cancelled by the customer; Check-Out;No-Show. 
*  reservation_status_date: The last status date.

### About the dataset
The dataset consists of a hotel industry based details. The dataset contains 119390 rows and 32 columns. The following columns have the null values such as children, country, agent and company. The duplicate values in the dataset have been counted as 31994. The aim is to explore and analyze the data. The results will be supported for the business improvement.

### Manipulations done and insights found?  in the data
*   The copy of data set was made for analysis.
*   All the duplicated rows in the dataset were deleted.
*   The company column was dropped due to 94% of null values. 
*   All the null values were replaced with other corresponding values
*   The data types of children and agent columns were changed with integer.
*   Two separate data frames such as city hotel and resort hotel have been created for analysis

## **Solution to Business Objective**

The following suggetions are provided to the client to achieve the business objective.
1.	is_repeated guest and previous bookings not canceled has strong correlation. It shows that the repeated guests are not more likely to cancel their bookings.
2.	There is a positive correlation between lead time and total stay 
3.	stays_in_week_nights has a high correlation  with stays_in_weekend_nights.
4.	During the months at low arrivals of guest some discount and offers can give to increase the arrivals.During high arrivals months price can be increased for profit.
5.	Most liked meal type was identified.They can prepare more quantity of meals.Less prefered meal can be prepared in less quantity.
6.	More active agents can be motivated by some complements and it will lead the improvement of booking in less active agents also
7.	Corporate booking are less.It can be improved by various strategical plans.
8.	Based on top ten country people hotels can attract the people by giving their traditional foods and they can arrange interiors in their country styles.New stragy can be followed to attract the customer from less visiting countries.
9.	From the total cancelation city hotel has the more percentage of cancelation of booking.The reasons for cancelation can be analysed and it will lead the reduction of cancelation.
10.	The cancelations from new guests are 99%. the reasons for cancelations can be analysed and it can be reduced.
11.	In the year of 2016 and 2017 resort hotel bookings are less percentage.It can be improved by marketing strategies.
12.	The months of april,may,june,july,august the cancelations are more.It can be rectified by some remedial activities.
13.	In resort hotel duration of stays are less.Most of stays 1 night stay only.Duration of stay need to be improved in resort hotels.
14.	Most of the customer like to stay in A type room and next D type room.Other types of rooms have the less preferences.
15.	Most early bookings done by TA/TO channel.Corporate channel have the less early bookings and it need to be improved.
16.	TA/TO channel waiting time can be reduced by appropriate methods
17.	Based on the correlation relations of variables root map for business improvement will be identified
18.	The pattern of adr value has been identified and it will be used for business growth

# **Conclusion**

This project offers the most useful findings to improve the hotel industry business.
The following conclusions are summarized from this study:
1.	It is identified that the guest arrivals are more on august, July, may months and very low on November, December, January months.
2.	The BB type meal mostly preferred by customers and FB type meal very few people only preferred.
3.	The agents 9, 240 are more active and the agents 14, 7,250,241 are moderate active. The remaining agents are very low active for booking.
4.	The most of the customer accessed booking through TA.TO and least customer accessed through corporate booking.
5.	Most guests arrived from PRT country and following that GEBR, FRA, ESP and DEU are top five countries of most guests arrivals.
6.	City hotel has the more cancelations compared to resort hotel.
7.	The 99% cancelations were done by new guests and 1% cancelations were done by repeated guests.
8.	In the year 2016 and 2017 percentage of booking of city hotel is 63% and resort hotel is 37%.
9.	The months of April, may, June, July, august the cancelation percentage is more.
10.	In resort hotel 20% stays in 1 night and in city hotel 40% of stays in 3 nights.
11.	In resort hotel 55% booking on room type A and in city hotel 111% of preferences on A type room
12.	Most of the early bookings have done by TA/TO distribution channel and less early bookings are done by corporate channel.
13.	TA/TO channel average waiting time is more than other channel and corporate channel has the least average waiting time.
14.	Repeated guest and previous bookings not canceled has the strong correlation. It shows that the repeated guests are not more likely to cancel their bookings.
15.	The average daily rate value increases when the number of people increases.

































































