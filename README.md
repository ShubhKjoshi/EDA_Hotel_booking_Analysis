# EDA_Hotel_booking_Analysis
Data Analysis on Hotel booking data

We are provided with a hotel bookings dataset.

Out main objective is perform EDA on the given dataset and draw useful conclusions about general trends in hotel bookings and how this data can govern the hotel bookings.

# Dataset
We are given a hotel bookings dataset. This dataset contains booking information for a city hotel and a resort hotel. It contains the following features:

- hotel: Name of hotel ( City or Resort)
- is_canceled: Whether the booking is canceled or not (0 for no canceled and 1 for canceled)
- lead_time: time (in days) between booking transaction and actual arrival.
- arrival_date_year: Year of arrival
- arrival_date_month: month of arrival
- arrival_date_week_number: week number of arrival date.
- arrival_date_day_of_month: Day of month of arrival date
- stays_in_weekend_nights: No. of weekend nights spent in a hotel
- stays_in_week_nights: No. of weeknights spent in a hotel
- adults: No. of adults in single booking record.
- children: No. of children in single booking record.
- babies: No. of babies in single booking record. 
- meal: Type of meal chosen 
- country: Country of origin of customers (as mentioned by them)
- market_segment: What segment via booking was made and for what purpose.
- distribution_channel: Via which medium booking was made.
- is_repeated_guest: Whether the customer has made any booking before(0 for No and 1 for 
                     Yes)
- previous_cancellations: No. of previous canceled bookings.
- previous_bookings_not_canceled: No. of previous non-canceled bookings.
- reserved_room_type: Room type reserved by a customer.
- assigned_room_type: Room type assigned to the customer.
- booking_changes: No. of booking changes done by customers
- deposit_type: Type of deposit at the time of making a booking (No deposit/ Refundable/ No refund)
- agent: Id of agent for booking
- company: Id of the company making a booking
- days_in_waiting_list: No. of days on waiting list.
- customer_type: Type of customer(Transient, Group, etc.)
- adr: Average Daily rate.
- required_car_parking_spaces: No. of car parking asked in booking
- total_of_special_requests: total no. of special request.
- reservation_status: Whether a customer has checked out or canceled,or not showed 
- reservation_status_date: Date of making reservation status.


Total number of rows in data: 119390

Total number of columns: 32



# Summary :

Hotel industry is a very volatile industry, and the bookings depend on variety of factors such
as type of hotels, seasonality, days of week and many more. This makes analysing the
patterns available in the past data more important to help the hotels plan better. Using the
historical data, hotels can perform various campaigns to boost the business. We have the
booking records based on two hotel types 'City' hotel and 'Resort' hotel.
As a first step we explored through all the files in the dataset to understand the rubrics and
content of dataset that we have. This dataset has a lot of columns such as 'Average daily
rate', 'cancellations', etc. Now we will select the columns which we will be analysing.
After going through the data, we knew which columns will be needed for analysis. Some
columns form the dataset had null values. We can't analyse the data which has null values.
So, we replaced the null values with zero, mean etc. We also removed the duplicate data
present in the dataset. We dropped dome columns which are not necessary and added some
columns by combining or manipulating the data from other existing columns. After
preparing and cleaning the dataset we started analysing the data.
For booking orders, we found that city hotel has a greater number of bookings than resort

hotel. To be precise city hotel has 61% bookings and resort hotel has 39% bookings. Most
number of guests were present in both hotels in May, June, July, August.
For full stay, most common stay length is less than 4 days and generally people prefer City
hotel for short stay, but for long stays, Resort Hotel is preferred. For country, most guests
come from Portugal and other guests are from western European countries. For agent, agent
no. 9 has made the most no. of bookings.
For cancellations, city hotel has more % of cancellations than resort hotel. Both the hotels
combined has 4% of repeated guests. Customer retention rate is very low for both the
hotels.
For average daily rate, it is constant for city hotel whereas it is more fluctuating for resort
hotel.
Resort hotels have more average daily rate than city hotel in July and august months.
Average daily price per person also varies in the same way as average daily rate.
Most guests prefer room types A, D, E. But room types H, G, F give better average daily
rate. Waiting period for booking is also more for city hotels. It means city hotels are busier
than resort hotels.
From the analysis we can conclude that there are lot of things which can be taken into
consideration and hotels should make necessary changes according to the analysis. Both the
hotels need to target western European countries as they generate more revenue. Hotels need
to work on customer retention as it is very low. People tend to prefer resort hotels for longer
stays and city hotels for short stays. Overall Average daily rate of City hotel is slightly
higher than Resort hotel and no. of bookings of City hotel is also higher than Resort hotel.
Hence, City hotel is making more revenue. For customers, generally the longer stays (more
than 15 days) can result in better deals in terms of low average daily rate. Couples are the
most common guests for hotels; hence hotels can plan services according to couples.


# Conclusion:

(1) Around 60% bookings are for City hotel and 40% bookings are for Resort hotel, therefore City Hotel is busier than Resort hotel. Also the overall adr of City hotel is slightly higher than Resort hotel.
(2) Mostly guests stay for less than 5 days in hotel and for longer stays Resort hotel is preferred.
(3) Both hotels have significantly higher booking cancellation rates and very few guests less than 4 % return for another booking . 
(4) Most of the guests came from european countries, with most of guests coming from Portugal.
(5) Guests use different channels for making bookings out of which most preferred way is TA/TO.
(6) July- August are the most busier and profitable months for both of hotels. 
(7) Couples are the most common guests for hotels, hence hotels can plan services according to couples needs to increase revenue.
(8) For customers, generally the longer stays (more than 15 days) can result in better deals in terms of low adr.
And many more conclusions.
