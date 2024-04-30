# New York City Airbnb Data Analysis

Welcome to the New York City Airbnb Data Analysis project! This project aims to analyze the vibrant Airbnb market in New York City, one of the world's top destinations for travelers. The high demand for temporary lodging ranges from a few nights to several months. We will explore this dynamic market by integrating data from multiple file types, providing insights into pricing, room types, and reviews.

## Project Description

In this project, we examine the New York Airbnb market using data from the year 2019. Our analysis involves data from three different file types:
- **CSV (.csv)**
- **Tab-Separated Values (.tsv)**
- **Excel (.xlsx)**

These formats are commonly used for storing tabular data. Our dataset includes information on Airbnb listing prices, locations, room types, host details, and review dates.

## Data Files

1. **Price and Location Data (`data/airbnb_price.csv`)**
   - `listing_id`: Unique identifier for each listing.
   - `price`: Nightly price of the listing in USD.
   - `nbhood_full`: Borough and neighborhood where the listing is located.

2. **Room Type Data (`data/airbnb_room_type.xlsx`)**
   - `listing_id`: Unique identifier for each listing.
   - `description`: Description of the listing.
   - `room_type`: Type of room offered (Shared rooms, Private rooms, Entire homes/apartments).

3. **Review Data (`data/airbnb_last_review.tsv`)**
   - `listing_id`: Unique identifier for each listing.
   - `host_name`: Name of the listing host.
   - `last_review`: Date when the listing was last reviewed.

## Objectives

- **Price Analysis**: Understand the pricing landscape across different neighborhoods.
- **Room Type Distribution**: Analyze the availability of different types of rooms.
- **Host Activity**: Study the relationship between host activity and listing reviews.

## Tools and Libraries Used

- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical operations.
