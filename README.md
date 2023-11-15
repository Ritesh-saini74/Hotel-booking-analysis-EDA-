# Hotel-booking-analysis-EDA-

Problem Statement: 

For this project we will be analyzing Hotel Booking data. This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces.

Hotel industry is a very volatile industry and the bookings depends on above factors and many more

The main objective behind this project is to explore and analyze data to discover important factors that govern the bookings and give insights to hotel management which can perform various campaigns to boost the business and performance.

Project Summary:

In this dataset ,There are 119390 rows and 32 columns in which Hotel Booking comprises of two types of hotels i.e City Hotel and Resort Hotel.
All the columns are divided into three dtypes :-Object,Float64 and int64.
In this project, we have divided the data manipulation workflow into three different categories i.e. Data Collection ,Data cleaning and manipulation and EDA(Exploratory Data Analysis)

This datasheet does have duplicate as well as null values.There are total of 31994 duplicate values and four columns have missing values.The maximum number of missing values are from "Company" column then followed by "Agent" ,"Country" and "Children" columns.The "Children" columns conists of only 4 null values while "Company"column consists of 112593 null values.the total no of rows are 119390 and columns are 32 .

In this dataset,there are both duplicates and missing values available.So,we have to deal with that and as a result we have replaced the null and missing values and also have dropped the duplicate values.

We have found that there were some rows in which the combining values of adults,babies and childrens was 0 so this simply means there were no guests as 0 indicates presence of none.So,there were no bookings made.So,as a result ,We simply dropped the rows where combining values of adults,babies and children columns was 0.

The data type of 'reservation_status_date' column was object type so it was changed to date type format for better use. There were two new columns that was added, one is 'total_people' and other is 'total_stay'

Before visualizing any type of data from the data set we need to do data wrangling.So, For that, we have checked the null value of all the columns.So,after completing the process of data visualisation,we moved to the data visualization part.

Then,we have started the data visualisation part. In the data visualization process,we have used various charts and have dived deep understanding the graphs to catch the proper insights that gives the business outcomes.So,visualisations has been done to get the proper insights from the data that will ultimately boost the businesses.

Then,we have also used the corelation matrix to get the relaionships between the different columns

Thus,we have Explored and analyzed the data to discover important factors that govern the bookings .

Conclusion:

City hotels are the most preferred hotel type by the guests.So, We can say that City hotels are the busiest hotel in comparision to the resort hotel.

The average ADR of city hotels is higher as compared to the resort hotels. So,it can be said that these City hotels are generating more revenue than the resort hotels.

The total stay of guests is directly proportional to the adr.So,higher the days of stay ,the higher will be adr and revenue as well.

The percentage of repeated guests is very low. Only 3.9 % people had revisited the hotels. Rest 96.1 % were new guests.So, retention rate is much low.

The percentage of required car parking spaces is very low .This means less car parking spaces don't affect the business much.Most of the customers (91.6%) do not require car parking spaces.

Among different types of meals,BB( Bed & Breakfast) is the most preferred type of meal by the guests.So,Guests loved to opt for this meal type.

'Direct' and 'TA/TO' have almost equally contribution in adr in both type of hotels i.e. 'City Hotel' and 'Resort Hotel'.While,GDS has highly contributed in adr in 'City Hotel' type.

Optimal stay length in both the hotel types(City and Resort Hotel) is less than 7 days. Usually people stay for a week.So,after 1 week ,the optimal stay length decined drastically.

Most number of bookings have taken place in the month of July and August.July and August are the favourite months of guests to visit different places.

The mostly used distribution channel for booking is "TA/TO". 79.1 % bookings were made through TA/TO (travel agents/Tour operators). While calculating adr across different month,it is found that for Resort hotel , ADR is high in the months of June,July,August as compared to City Hotels.

Almost 1/4 th of the total bookings is cancelled. Approx ,27.5 % bookings have got cancelled out of all the bookings.

Majority of the guests have shown interest in the room type 'A'.Room type 'A' is the most preferred room type.
