# Zomato Analysis

## collectData.py
collectData.py makes use of the Zomato API to request information and store it in zomato_data.csv.

An API key is required to run the program.
[Request Zomato API Key here](https://developers.zomato.com/api) 

User needs to input 
- Location
- Sort
- Order

The requested data will be formatted into a DataFrame and stored in zomato_data.csv.

Reading the .csv file from the program after writing into it leads to an error. Just open the .csv file, save it, exit it and run the program again.

## zomato_data.csv

This .csv file contains information about 1500 restaurants in Bangalore.

The columns of the .csv file are
- Restaurant ID
- Restuarant name
- Average cost for two
- Cuisines offered at the restaurant
- Location of the restuarant
- Price range
- Rating
