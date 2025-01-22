# Real Estate Market Analysis  

## Project Description  
This project analyzes data from the Yandex.RealEstate service, containing a historical archive of apartment listings in Saint Petersburg and its neighboring areas. The objective is to learn how to determine the market value of properties and identify the factors that influence pricing. Additionally, the project aims to establish parameters for building an automated system to detect anomalies and fraudulent activities.  

## Objectives  
1. Learn to determine the market value of real estate properties.  
2. Identify key factors that influence apartment pricing.  
3. Define parameters for an automated system to track anomalies and fraudulent activities.  

## Dataset Description  
The dataset includes two types of data for each property:  
1. **User-input data:** Details provided by the property owner (e.g., description, price).  
2. **System-generated data:** Information derived from mapping tools (e.g., distance to the city center, airport, parks, and water bodies).  

### Key Columns  
- **price**: Listing price of the property.  
- **total_area**: Total area of the property in square meters.  
- **rooms**: Number of rooms in the property.  
- **floor**: Floor number of the apartment.  
- **cityCenters_nearest**: Distance to the city center in meters.  
- **airports_nearest**: Distance to the nearest airport in meters.  
- **parks_nearest**: Distance to the nearest park in meters.  
- **water_bodies_nearest**: Distance to the nearest water body in meters.  
- **is_apartment**: Whether the property is classified as an apartment (True/False).  
- Additional fields provided in the dataset.  

## Steps of Analysis  
1. **Data Overview**:  
   - Explore the dataset for structure, completeness, and anomalies.  
   - Check for missing values, duplicates, and errors.  

2. **Data Preprocessing**:  
   - Clean the dataset by addressing missing values and correcting errors.  
   - Compute additional metrics (e.g., price per square meter).  
   - Add relevant columns for analysis.  

3. **Data Analysis**:  
   - Identify factors that influence real estate pricing.  
   - Analyze correlations between property features and pricing.  
   - Define thresholds to detect anomalies and potential fraud.  

4. **Conclusion**:  
   - Summarize key findings and recommendations for the automated system.  

## Tools Used  
- **Programming Language**: Python  
- **Libraries**: pandas, numpy, matplotlib, seaborn  

## Key Findings  
- Will be updated upon completion of analysis.  

## Author  
This project was completed as part of the Data Science course.  

