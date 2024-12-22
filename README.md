HOTEL BOOKING EDA

Objective We are provided with a hotel bookings dataset.

Our main objective is perform EDA on the given dataset and draw useful conclusions about general trends in hotel bookings and how factors governing hotel bookings interact with each other.

Dataset We are given a hotel bookings dataset. This dataset contains booking information for a city hotel and a resort hotel. 

Know your data

Dataset Information

Duplicate Values

Missing Values/Null Values

Understanding Your Variables

Check Unique Values for each variable.

Data wrangling

count that in which year of which month most number of customers arrived at hotel.

Customer type, Room type, room_comparision, Deposit_type, Is_canceled checked.

How many customer have changed their booking.

remove duplicates values

finding uniques values for each variables

Find hotel ratio Adding a two new column of total staying days,total people stays

Remove outliers by box plot. Did All th manipulation

What main questions was arising :-

Which types of customers mostly make bookings?

Which room type is in most demand and which room type generatesthe highest adr?

Which distribution channel brings betterrevenue-generatingg deals for hotels?

Which significant distribution channel has the highest cancellation percentage?

What is the trend of bookings within a month?

Which Hotel has Highest booking ratio(comparision)?

What is preferred stay length in hotel if we compare with Customer type?

In which year most booking has happened for bothe type hotels?

From which country most of the guests are coming ?

In which month most of the booking happened?

Which market segment has booked and canceled the booking?

What type of Customer has highest booking as Couples, Single, Group?

Which meal type is the most preffered meal of customers?

Finding out corelation between Different variables?

which has highet ADR?

Mainly performed using Matplotlib and Seaborn library and the following graph and plots had been used:

Bar Plot

Histogram

Scatter Plot

Pie Chart

Line Plot

Heatmap

Box Plot

Pair plot

We plot different graph (univariate and bivariate ) to make find out the last conclusion:-

Around 60% bookings are for City hotel and 40% bookings are for Resort hotel, therefore City Hotel is busier than Resort hotel. Also the overall adr of City hotel is slightly higher than Resort hotel.

Mostly guests stay for less than 5 days in hotel and for longer stays Resort hotel is preferred.

Both hotels have significantly higher booking cancellation rates and very few guests less than 3 % return for another booking in City hotel. 5% guests return for stay in Resort hotel.

Most of the guests came from european countries, with most of guests coming from Portugal.

Guests use different channels for making bookings out of which most preferred way is TA/TO.

Almost 30% of bookings via TA/TO are cancelled.

July- August are the most busier and profitable months for both of hotels.

Couples are the most common guests for hotels, hence hotels can plan services according to couples needs to increase revenue.

For customers, generally the longer stays (more than 15 days) can result in better deals in terms of low adr.

Higher lead time has higher chance of cancellation. Also, history of previous cancellations increases chances of cancellation.

Challenges

There was a lot of duplicate data.

Data was present in wrong datatype format.

Choosing appropriate visualization techniques to use was difficult.

A lot of null values were there in the dataset.
