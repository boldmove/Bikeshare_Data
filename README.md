# Discover Urban Patterns and Mobility using the US Bikeshare Data Analysis Project

This project explores and analyzes bikeshare data from three major cities in the United States: **Chicago**, **New York City**, and **Washington, D.C.**. The analysis provides insights into user behavior, trip durations, and travel patterns using Python.

---

## 🚀 **Project Overview**
The `US_Bikeshare_Data.py` script is designed to:
1. Load bikeshare data for the selected city.
2. Perform interactive filtering based on the **month** and **day of the week**.
3. Calculate and display statistics for:
   - **Popular travel times**
   - **Most common stations and trips**
   - **Trip duration**
   - **User demographics** (gender and birth year when available)

---

## 📂 **Dataset**
The project uses the following datasets:
- **chicago.csv**  
- **new_york_city.csv**  
- **washington.csv**  

These files contain bikeshare trip data, including:
- Start and end times of trips
- Start and end stations
- Trip durations
- User types (Subscriber/Customer)
- Gender and birth year (only available for Chicago and New York City)

---

## 🛠️ **Features**
### **1. Interactive User Inputs**
- The script prompts the user to select a city, month, and day for data analysis.
- The filtering options include:
  - Cities: Chicago, New York City, Washington
  - Months: January through June or "All" months
  - Days: Monday through Sunday or "All" days

### **2. Statistics Computed**
- **Popular Times of Travel**
  - Most frequent month
  - Most frequent day
  - Most frequent start hour
- **Popular Stations and Trips**
  - Most common start station
  - Most common end station
  - Most common trip (start station to end station)
- **Trip Duration**
  - Total travel time
  - Average travel time
- **User Demographics**
  - Counts of user types (Subscriber/Customer)
  - Counts of gender (when available)
  - Earliest, most recent, and most common year of birth (when available)

---

## 📋 **Usage**
1. Clone the repository:
   ```bash
   git clone https://github.com/boldmove/Bikeshare_Data.git
