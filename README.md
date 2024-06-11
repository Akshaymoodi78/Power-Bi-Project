
## Data Manipulation and reporting in Power Bi.

### Aim of the project:
The aim is to construct a consolidated and interactive PowerBI report that will allow Zomato to quickly assess the required data.

#### Steps followed:
- Step 1 : Importing the Data.
Imported the data from all available Excel files.

- Step 2 : Data Transformation.
Corrected the City column names:

1.“Sí£o Paulo” → “São Paulo”  
2.“Cedar Rapids/Iowa City” → “Cedar Rapids”   
3.“ÛÁstanbul” → “Istanbul”  
Ensured the city name isn't ambiguous.

- Step 3: Removed Unused Columns.
Removed any columns that aren't being used.

- Step 4: Created Restaurant Columns.
Created two columns to display the Restaurant Name and Restaurant Address.

- Step 5: Created a Cuisines Table.
Made a separate table for the list of cuisines that each restaurant serves.

- Step 6: Created Unique Country-Code Table.
Ensured the Country-Code table includes only unique and non-blank values.

- Step 7: Added Rating Color Column using DAX.
Added a Rating color column with the following format:
Above 4.5 → Dark Green  
4 to 4.4 → Green.

- Step 8: Created list of Measures using DAX.
1.Restaurant count  
2.Average cost  
3.Average rating  
4.Cuisine count  
5.Create Continent Column

- Step 9: 
Created a new column in the Country Code table named “Continent” with values mapped to countries   (e.g., ''Africa – South Africa'').

#### Problem Statement:
1. Derive data on the total number of restaurants worldwide, including continents, countries, and cities and View data on a global scale with the capacity to drill down to a granular level.



![Screenshot 2024-06-11 132810](https://github.com/Akshaymoodi78/Power-Bi-Project/assets/117290590/3de1f2f8-2e2c-4a15-a608-ada6405565ac)

2. Derive data on the restaurants with the highest average customer ratings.



![Screenshot 2024-06-11 133325](https://github.com/Akshaymoodi78/Power-Bi-Project/assets/117290590/1338b1d9-067f-4b9f-a084-4965d41beb9c)

3. Derive data on the restaurants with the highest average customer ratings and discover the restaurants with the lowest average costs.



![Screenshot 2024-06-11 133631](https://github.com/Akshaymoodi78/Power-Bi-Project/assets/117290590/00e15291-f08b-4143-b2d6-4f59c5c5b9c4)       

4. Create the following measures in the appropriate tables 

a. Restaurant count  
![Screenshot 2024-06-11 134128](https://github.com/Akshaymoodi78/Power-Bi-Project/assets/117290590/dea3d6b0-45f8-4969-991b-1cfb6892ae4d)


b. Average cost 
![Screenshot 2024-06-11 134031](https://github.com/Akshaymoodi78/Power-Bi-Project/assets/117290590/5458d74f-01ad-4153-b5e8-7808f60f8558)

c. Average rating 
![Screenshot 2024-06-11 134231](https://github.com/Akshaymoodi78/Power-Bi-Project/assets/117290590/6b2347bf-4f31-4a38-92c1-a50362355e76)


d. Cuisine count  
![Screenshot 2024-06-11 134351](https://github.com/Akshaymoodi78/Power-Bi-Project/assets/117290590/34433761-6da3-4d32-bf08-c7831dc09c1a)


Over all measures : 
![Screenshot 2024-06-11 133916](https://github.com/Akshaymoodi78/Power-Bi-Project/assets/117290590/a8fae7b4-bf7c-4b8b-b88d-f3ce4e4bd986)







