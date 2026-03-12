# Data Dictionary for Ola Bookings Dataset

This document provides an overview of the Ola bookings dataset, including each column, its data type, and a brief description of what it represents.

## Columns Overview

| Column Name             | Data Type   | Description                                              |
|------------------------|-------------|----------------------------------------------------------|
| `booking_id`           | String      | Unique identifier for each booking.                      |
| `user_id`              | String      | Unique identifier for each user.                         |
| `source`               | String      | The pickup location of the ride.                         |
| `destination`          | String      | The drop-off location of the ride.                       |
| `booking_time`         | DateTime    | The time when the booking was made.                      |
| `ride_start_time`      | DateTime    | The time when the ride began.                            |
| `ride_end_time`        | DateTime    | The time when the ride ended.                            |
| `cab_type`             | String      | Type of cab booked (e.g., sedan, SUV).                  |
| `distance`             | Float       | Total distance of the ride in kilometers.                |
| `fare`                 | Float       | Total fare charged for the ride.                         |
| `cancellation_reason`  | String      | The reason for cancellation (if applicable).             |
| `trip_duration`        | Float       | Duration of the trip in minutes.                          |
| `rating`               | Float       | User's rating of the ride experience.                    |
| `payment_method`       | String      | Method used for payment (e.g., cash, card).             |

## Notes
- The dataset contains records of Ola rides booked throughout the service.
- Ensure data privacy and compliance with regulations while analyzing user information.