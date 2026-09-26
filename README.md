<center><img scr= "THT/Screenshot202026-09-2620090531.jpg"></img></center>

# THT(Food Delivery Times)
  Project ini bertujuan melihat performace dari data "Food Delivery Times" untuk mengetahui faktor -faktor apa saja yang mempengaruhi lama sebentarnya wakktu pengantaran.

## Sumber data
Data didapatkan dari [Food Delivery Times di Kaggle](https://www.kaggle.com/datasets/denkuznetz/food-delivery-time-prediction)

## Business Questions
1. Faktor apa saja yang memengaruhi waktu pengiriman?
2. Apakah jarak memengaruhi waktu pengiriman?
3. Bagaimana lalu lintas dan cuaca berkaitan dengan waktu pengiriman?
4. Seberapa akurat model tersebut dalam memprediksi waktu pengiriman?

## Data Preparation
Data Cleaning :
- Check information data
- Check missing value
- Check data duplicated
  
Data Trasformation :
Filling empty colomns 
- weather,traffic_level,time_of_day with (mode)
-  Courier_experience_yrs with (mean)

Featuring Engingeering :
Create new colums 
- Total_delivery_time
- Distance_category
- Preparation_ratio

Output :

- Total Data 1000 , 12 colums
- missing value : 0
- data duplicate : 0
- Ready for Explore
