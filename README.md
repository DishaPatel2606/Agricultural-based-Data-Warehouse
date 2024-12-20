# Agricultural-based-Data-Warehouse
This project focuses on designing and implementing a data warehouse for precision farming and sustainable agriculture. It integrates data from various sources like IoT devices, weather stations, and market databases into a centralized system to enable data-driven decision-making for farmers, policymakers, and agribusinesses.


Data Warehouse Schema


Fact Tables
Production Fact: Tracks crop production, prices, and total sales.

Input Usage Fact: Records resource usage (e.g., water, fertilizers) and costs.

Weather Fact: Captures temperature, rainfall, humidity, and soil moisture.


Dimension Tables

Crop Dimension: Details crop types, seasons, and market demand.

Farmer Dimension: Captures farmer profiles and farm sizes.

Location Dimension: Tracks geographic data for fields and facilities.

Facility Dimension: Provides data on storage and processing units.

Staff Dimension: Includes labor management data.

Date Dimension: Supports time-based analysis (daily, monthly, yearly).

Buyer/Seller Dimensions: Details buyers and sellers in the supply chain.

Field Dimension: Tracks soil type, location, and occupation.


Queries

Revenue Analysis: Total sales by crop type, revenue per field, and buyer-seller performance.

Production Trends: Seasonal patterns and monthly production trends.

Resource Efficiency: Average resource usage and cost per unit of yield.

Weather Impact on Crops: Correlation between weather and crop yield/price.

Crop Yield Analysis: Average yield by farmer and identification of underperforming locations.

