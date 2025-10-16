# Effects-on-the-Fuel-Efficiency-of-Popular-Car-Brands
This project analyzes how various vehicle attributes influence highway fuel efficiency. Using multiple linear regression modeling, we identify which factors — such as engine displacement, cylinder count, drive type, and fuel type — most strongly affect miles per gallon (MPG) performance across popular car brands.

## Project Overview
Fuel efficiency remains a key consideration when consumers purchase a vehicle. The goal of this analysis was to determine which mechanical and design variables are most predictive of highway MPG using publicly available vehicle data.

## Methodology
**Dataset:** MPG dataset (vehicle fuel economy data from multiple brands)  
**Response variable:** `hwy` – highway miles per gallon  
**Predictors:**
- `displ` – engine displacement (liters)  
- `cyl` – cylinder count  
- `class` – vehicle class  
- `drv` – drive type (FWD, RWD, 4WD)  
- `fl` – fuel type  

**Model type:** Multiple Linear Regression  
**Software:** R (Quarto document)  
**Statistical Outputs:**
- Adjusted R² = 0.7671  
- Model p-value = 2.2e-16  

## Key Findings
- **Cylinder count** and **engine displacement** are the most significant predictors of highway fuel efficiency.  
- As either variable increases, MPG decreases — confirming that smaller engines with fewer cylinders perform best in highway conditions.  
- Vehicle class and drive type had secondary but noticeable effects.  

## Visualizations
The project includes diagnostic plots and visualizations such as:
- Residual vs. fitted values  
- Normal Q-Q plot  
- Highway MPG distribution by vehicle class  
- Scatterplots of `displ` vs. `hwy` with regression trendlines

## Files
