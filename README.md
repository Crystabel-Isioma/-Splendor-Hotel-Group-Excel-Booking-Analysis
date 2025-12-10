# Splendor Hotel Group – Excel Booking Analysis 

This project delivers a full Excel-based investigation into booking behavior, cancellation patterns, and revenue performance for Splendor Hotel Group. 
The goal was simple and direct: the hotel was experiencing consistent financial losses and wanted to understand why — and what strategic action could prevent the losses going forward.

All cleaning, transformations, pivot-table analysis, calculations, and the final dashboard were completed entirely in Microsoft Excel.

---

## Table of Contents
- Business Problem  
- Dataset Description  
- Cleaning & Preparation  
- Analytical Process  
- Key Insights  
- Dashboard  
- Files Included  
- How to Use This Project  

---

## Business Problem

Splendor Hotel Group had been losing money across multiple periods and needed clarity on what was driving the losses.Specifically, they wanted to understand:

1. *Why are we losing money?*  
2. *What can we do to stop this loss going forward?*

This project provides a clean, structured Excel workflow that converts raw booking data into actionable business intelligence.

---

## Dataset Description

The Excel workbook contains three core sheets:

### 1. *Hotel_bookings (Raw Data)*
This is the untouched source dataset containing:
- Reservation details  
- Arrival dates  
- Pricing data (including Average Daily Rate)  
- Cancellation information  
- Guest counts and booking behavior fields  

### 2. *Cleaned*
This sheet is the fully prepared version used for analysis:
- Standardized dates and formats  
- Cleaned and corrected text values  
- Numeric fields fixed  
- Added helper fields for segmentation and calculations  
- Structured layout suitable for pivot tables and dashboarding  

### 3. *Analysis*
This sheet includes:
- Pivot tables  
- Cancellation summaries  
- Revenue and estimated revenue-loss tables  
- Lead-time comparisons (0–30 days vs. over 30 days)  
- All calculations that feed into the final dashboard  

The project also contains the exported dashboard image (shg.png).

---

## Cleaning & Preparation

All preparation was performed directly in Excel. Key steps include:

- Removing empty or irrelevant rows  
- Normalizing and standardizing date formats  
- Ensuring that pricing and revenue-related fields were numeric  
- Cleaning inconsistent categorical fields (e.g., room type, cancellation labels)  
- Creating helper columns such as:  
  - Month & Year  
  - Lead-time grouping (within 30 days vs. more than 30 days)  
  - Estimated revenue loss  
  - Booking window categories  
- Organizing the data for pivot-based analysis  

This created a clean dataset strong enough for financial and operational insight.

---

## Analytical Process

The analysis focused on identifying the source of the hotel’s revenue problem. Using pivot tables and calculations, the following questions were examined:

- Which periods show the highest cancellation volume?  
- How much revenue is lost due to cancellations?  
- What booking behaviors differ between high-cancellation and low-cancellation groups?  
- How does the Average Daily Rate vary across booking windows?  
- What patterns or customer segments are responsible for the financial decline?  
- What strategy can stabilize revenue in peak seasons?

Through this process, the booking patterns became clear. The cleaned dataset and pivot tables revealed insights that were not visible in the raw data alone.

---

## Key Insights

### *1. Summer months generate strong gross revenue — but also major losses.*
The analysis showed that July and August consistently produce large revenue amounts but also extremely high cancellation-related losses. When cancellations are subtracted, the financial performance becomes negative.

### *2. Bookings made more than 30 days in advance are the main source of cancellations.*
These early bookings introduce:
- High cancellation rates  
- Lower Average Daily Rate  
- Greater financial instability  

### *3. Short-notice bookings (0–30 days) are more profitable and more reliable.*
- They cancel less often  
- They pay higher Average Daily Rate  
- They convert into actual stays more consistently  

### *4. Average Daily Rate patterns are strongly tied to booking behavior.*
Guests who book closer to their arrival date pay more and follow through more reliably than far-in-advance bookers.

### *5. A strategic overbooking approach can recover lost revenue.*
Because short-notice bookers are more stable and pay more, overbooking this group during July–August can offset the predictable losses from early cancellations.

These insights form the basis for the business recommendation.

---

## Dashboard

Below is the exported dashboard summarizing the findings visually:

![Splendor Hotel Dashboard](shg.png)

The dashboard highlights:
- Revenue and estimated revenue loss  
- Average Daily Rate behavior across booking windows  
- Cancellation patterns by month and lead-time category  
- Financial impact of long-lead vs. short-lead bookings  

---

## Files Included

- Splendor_Hotel_Group_RAW_DATA.xlsx — original raw dataset  
- Splendor_Hotel_Group.xlsx — cleaned dataset + analysis + pivot tables  
- shg.png — final dashboard image  
- README.md — full project documentation  

---

## How to Use This Project

1. Download the main Excel file (Splendor_Hotel_Group.xlsx).  
2. Review the *Hotel_bookings, **Cleaned, and **Analysis* sheets in that order.  
3. Use the dashboard image (shg.png) for a fast visual understanding of the major insights.  
4. Refer to this README as a walkthrough of:
   - Excel cleaning workflow  
   - Pivot-based analytical process  
   - Business interpretation of booking and revenue data  

---
