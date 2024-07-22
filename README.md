# Hotel-Booking-Analysis-EDA-project

# Problem Statement
Have you ever wondered when the best time of the year to book a hotel room is ? or the optimal length of stay in order to get the best daily rate? What if you wanted to predict whether or not a hotel was likely to recieve a disproportionately high number of special requests ? This hotel booking dataset can help you explore those questions! This data contains booking information of city hotel and resort hotel, and includes information such as when the booking was made, length of stay the number of adult, children, babies etc.

# Define Your Business Objective?
Discovering the important factors and that govern bookings and explore and analysis the data for business output.

# 1. Knowing the Data
a) After looking over the dataset, here are some following observations:

b) This Dataset contains 119390 rows and 32 columns.

c) In the data there are 31994 duplicates values, which must be dropped.

d) In the entire dataset there are nearly less null values, but some of the columns contain more than 10% of null values.

e) Agent column holds more than 20% of the missing value and can be taken care properly as it is an important column and does not hold much missing values.

f) On the otherside the column Company holds more than 90% of the missing values and is of no use as it contain greater number of null values. I must drop this column afterwards while analysing the dataset.

These are some of the conclusion which i have come until now after going through the dataset.

# 2. Understanding Your Variables
## Variables Description

hotel - Name of the hotel (Resort an dcity hotel)

is_canceled - if the booking was cancelled (1) or not cancelled (0)

lead_time - Number of days that elapsed between the entering date of the booking into the PMS and the arrival date.

arrival_date_year - year of the arrival date.

arrival_date_month - month of the arrival date.

arrival_date_week_number - week number of the arrival date.

arrival_date_day_of_month - day of arrival date

stays_in_weekend_nights - number of weekend nights guest stayed or booked the hotel. (Saturday and Sunday)

stays_in_week_nights - number of week nights guest stays or booked the hotel.(Monday to Saturday)

adults - number of adults among guests.

children - number of childrens among the guests.

babies - number of babies amaong the guests.

meal - kinds of meal opted for to the guests.

country - Country code.

market_segment - which segment customers belong to.

distribution_channel - name of the booking distribution channel, The term 'TA'means Travel Agents & 'TO' means Tour Operators.

is_repeated_guest -If the booking was done by the repeated guest (1) or not (0)

previous_cancellations - number of previous booking that was cancelled by the customer prior to the current booking.

previous_bookings_not_canceled - number of previous booking not cancelled by the customer prior to the current booking.

reserved_room_type - code of room type reserved.

assigned_room_type - code of room type assigned.

booking_charges - number of charges made to the booking.

deposit_type - charges deposited by the guest.

agent - ID of the agent that made the booking.

company - ID of the company that made the booking.

days_in_waiting_list - number of days the booking was in the waiting list.

customer_type - type of customers, assuming the following categories.

adr - Average daily rate.

required_car_parking_spaces - number of car parking space required to park a car.

total_of_special_requests - number of special request made by the cusromers.

reservation_status - Reservation status

reservation_status_date - Date at which the last reservation date was updated.

# 3. Data Wrangling

## Manipulation and insights found by me are as follows :

There were four column with the null values, so i have replaced the null values with 'zero', and 'other', and dropped the column 'company because there was a handfull of null value

This dataset also contains some duplicate values, so i dropped them.

The data type of 'reservation_status_date' is changed from object type format to date type format.

Two new columns were added in the dataset, that is 'total_stays' and 'total_people'.

We found that there were some rows in which the combining values of adults, babies and children was 0 so this simply means, there were no guests as 0 indicates presence of none. So, there were no bookings made so as result, we dropped the rows where combining values of adults, babies and children columns was 0.

# 4. Solution to Business Objective

## Business adjectives attained as follows :

To attain high growth and more success, hotel business need to flourish and for that few things which need to consider is high revenue generation, customers satisfaction and employee retention.

We are able to achieve the same by showing the client which are high in revenue generation by using various charts and graphs distribution.

Enhancing the revenue adopted distribution of which type room are most preffered and reserved and which are the months suitable for visitors.

We have also found that arouses preference in different categories like most liked meal type, optimal stay length facilities required by customers like car parking spaces etc. So, all these insights ultimately add to have a better planning for growth and higher revenue.

So. preparing well by using and understanding these useful outcomes, the client can be well prepared in advance so that minimum grivences would be faced by clients in long run and would help in further enhancement of their hospitality and service.

Ask for feedback often from the guest visiting the hotels so that the quality can be upgraded to the next level to increase more guests.

Periodically throw offers to attract the old customers so as to increase the no of repeated guests.

# Conclusion

City Hotel seems to be more preferred among travellers and it also genrates more revenue & profit.

Most number of bookings are made in July and August as compared rest of the months.

Room Type A is the most preffered room type among travellers.

Most of the guest stays for 1-4 days in the hotels.

City Hotel retains more number of guests.

Around one-fourth of the total bookings gets canceled. More cancellation of bookings.

New guest tends to cancel bookings more than repeated customers.

Lead time, number of days in waiting list or assignation of reserved room to customers does not affect cancellation of bookings.

Corporate has the most percentage of repeated guest while TA/TO has the least whereas in the case of cancelled bookings TA/TO has the most percentage while Corporate has the least.

The length of the stay decreases as ADR increases probably to reduce the cost.









