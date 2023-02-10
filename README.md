# EDA-Hotel_Booking

## Introduction

This repository contains an exploratory data analysis (EDA) of hotel booking data. The objective of this project is to gain insights into the hotel booking trends and patterns, such as the busiest times of the year, the most popular destinations, and the factors that influence the prices of hotel rooms.

## Problem Statement

There is a lack of insight into customer booking behavior, resulting in poor occupancy rates and revenue. The problem statement is to analyze customer booking data to identify patterns and trends in customer behavior, and use this information to inform decisions that will increase occupancy rates and revenue for the hotel.It mentions the lack of insight into customer booking behavior and it's negative impact, measurable as it mentions about poor occupancy rate and revenue, and actionable as it proposed to analyze data, identify patterns and trends and use that information to make decision.

## Contents

- eda_hotel_booking.ipynb - Google Colab Notebook containing the EDA

## Dependencies

The following packages are required to run the code in this repository:

- pandas
- numpy
- matplotlib
- seaborn

## Conclusion

This project provides a basic overview of hotel booking trends and patterns. The insights gained from this EDA can be used by hotel owners and managers to make informed decisions about pricing, promotions, and inventory management. Further analysis can be performed to gain deeper insights and make more accurate predictions.

The following insights were gained from the analysis:

- City Hotel had higher bookings (61.13%) than Resort Hotel (38.87%), but also had double the number of cancellations (15,000 compared to 7,500).

- The most popular meal option among customers was Bed and Breakfast (BB), followed by Half Board (HB) and Self Catering (SC). Full Board (FB) was the least preferred option.

- The lead time (time between booking and arrival) had a median of 50, with 25% below 10 and 25% above 25. The maximum lead time was 737, with the majority (50%) between 10 and 125.

- In 2015, the number of guests arrived at the Resort Hotel was slightly higher than the City Hotel. In 2016 and 2017, the City Hotel had more bookings, with 25,000 and 20,000 respectively, compared to 15,000 and 11,000 at the Resort Hotel.

- The majority of bookings came from Online Travel Agencies (OTA) (59.06%) and a small percentage from Direct bookings (13.506%). Aviation, Complementary, and Corporate made up a much smaller percentage.

- The majority of night stays (70%) came from customers who chose the No Deposit option, with 15% from Refundable Deposit and 25% from Non-refund Deposit. The density of stays was higher for 3 to 5 nights for all deposit types.

- The country with the highest average stay was FRO (11 nights), with the lowest being ASM, BFA, COM, DJI, HND, MDG, and MLI (1 night).

- Agent 9 had the most bookings (28,759), followed by Agent 240 (13,028), while Agents 14, 7, and 250 had lower bookings (3,349, 3,300, and 2,779 respectively).

- Room type A had the highest number of stays, with room types B, C, E, F, H, and G having lower stays, and room type D having moderate stays. Room types L and P had the least number of stays.

- The cancellation rate was highest for the "Transient" customer type (0.301059), followed by the "Contract" (0.163109), "Transient-Party" (0.152383), and "Group" (0.099265).

- Average Daily Rate decreased with an increase in total nights stayed. Customer preference for car parking was low, with most choosing hotels with 0 parking spaces.

- The maximum stay for BB customers was 15 nights, for FB was 55 nights, for HB was 70 nights, and for SC was 58 nights.

- The months with the highest bookings were August and July (more than 10,000), while the months with the lowest were January, November, and December (below 5,000).

- The cancellation rate was highest for customers who chose the Non-refund Deposit type. Customers who chose No Deposit and Refundable Deposit had equal chances of cancelling.

- Customers who arrived in July and August tended to stay longer, while those who arrived in January and February stayed the least number of nights.

- The majority of bookings came from the Transient and Transient-Party customer types.


