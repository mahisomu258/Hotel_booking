# Hotel_booking

# Hotel Bookings Cancellations Analysis

## Description

This project analyzes hotel booking cancellations using Excel. The dataset includes various attributes such as booking dates, cancellation status, customer demographics, and more. The goal is to identify patterns and insights that can help in understanding the factors contributing to cancellations and improving hotel booking strategies.

## Dataset

The dataset used in this project contains the following columns:
- **Hotel**: Type of hotel (Resort Hotel or City Hotel)
- **IsCanceled**: Whether the booking was canceled (1) or not (0)
- **LeadTime**: Number of days that elapsed between the booking date and the arrival date
- **ArrivalDateYear**: Year of arrival date
- **ArrivalDateMonth**: Month of arrival date
- **ArrivalDateWeekNumber**: Week number of year for arrival date
- **ArrivalDateDayOfMonth**: Day of arrival date
- **StaysInWeekendNights**: Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel
- **StaysInWeekNights**: Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel
- **Adults**: Number of adults
- **Children**: Number of children
- **Babies**: Number of babies
- **Meal**: Type of meal booked
- **Country**: Country of origin
- **MarketSegment**: Market segment designation
- **DistributionChannel**: Booking distribution channel
- **IsRepeatedGuest**: Whether the booking was from a repeated guest (1) or not (0)
- **PreviousCancellations**: Number of previous bookings that were canceled by the customer prior to the current booking
- **PreviousBookingsNotCanceled**: Number of previous bookings not canceled by the customer prior to the current booking
- **ReservedRoomType**: Code of room type reserved
- **AssignedRoomType**: Code of room type assigned
- **BookingChanges**: Number of changes/amendments made to the booking
- **DepositType**: Type of deposit made for the booking
- **Agent**: ID of travel agency that made the booking
- **Company**: ID of the company that made the booking
- **DaysInWaitingList**: Number of days the booking was in the waiting list before it was confirmed to the customer
- **CustomerType**: Type of booking, assuming one of four categories: Contract, Group, Transient, and Transient-party
- **RequiredCarParkingSpaces**: Number of car parking spaces required by the customer
- **TotalOfSpecialRequests**: Number of special requests made by the customer
- **ReservationStatus**: Reservation last status, assuming one of three categories: Canceled, Check-Out, and No-Show
- **ReservationStatusDate**: Date at which the last status was set

## Analysis

The analysis in this project includes:
- **Descriptive Statistics**: Summary statistics of the dataset to understand the distribution and central tendencies of various attributes.
- **Cancellation Rates**: Calculation of cancellation rates by different attributes (e.g., by hotel type, customer type, country).
- **Lead Time Analysis**: Examination of the relationship between lead time and cancellation rates.
- **Booking Changes**: Analysis of the number of changes made to bookings and how it correlates with cancellations.
- **Special Requests**: Investigation of the impact of special requests on the likelihood of cancellations.
- **Visualization**: Charts and graphs to visualize the data and findings.

## Results

The key findings from the analysis include:
- Cancellation rates are higher for City Hotels compared to Resort Hotels.
- Bookings with longer lead times tend to have higher cancellation rates.
- Customers with more special requests are less likely to cancel their bookings.
- Repeat guests are less likely to cancel their bookings compared to new guests.

## Conclusion

The analysis provides valuable insights into the factors influencing hotel booking cancellations. These insights can help hotel management in devising strategies to reduce cancellations, such as implementing stricter cancellation policies for bookings with longer lead times or offering incentives to repeat guests.


## Usage

1. **Open the Excel file**: Open `Hotel_Bookings_Cancellations.xlsx` in Excel.
2. **Explore the data**: Review the different sheets and charts to understand the analysis.
3. **Modify or extend the analysis**: Add additional analysis or charts as needed.
