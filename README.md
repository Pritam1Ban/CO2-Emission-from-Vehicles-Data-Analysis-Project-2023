# CONTENT

This dataset captures the details of how CO2 emissions by a vehicle can vary with the different features. The dataset has been taken from Canada Government official open data website. This is a compiled version. This contains data over a period of 7 years.
There are total 7385 rows and 12 columns. There are few abbreviations that has been used to describe the features. I am listing them out here. The same can be found in the Data Description sheet.

### Model

4WD/4X4 = Four-wheel drive
AWD = All-wheel drive
FFV = Flexible-fuel vehicle
SWB = Short wheelbase
LWB = Long wheelbase
EWB = Extended wheelbase

### Transmission

A = Automatic
AM = Automated manual
AS = Automatic with select shift
AV = Continuously variable
M = Manual
3 - 10 = Number of gears

### Fuel type

X = Regular gasoline
Z = Premium gasoline
D = Diesel
E = Ethanol (E85)
N = Natural gas

### Fuel Consumption

City and highway fuel consumption ratings are shown in litres per 100 kilometres (L/100 km) - the combined rating (55% city, 45% hwy) is shown in L/100 km and in miles per gallon (mpg)

### CO2 Emissions

The tailpipe emissions of carbon dioxide (in grams per kilometre) for combined city and highway driving

---

### Calculation of Fuel Consumption:

1st row data:

Fuel Consumption in City = 9.9 Liter/ 100Km,

Fuel Consumption in Highway = 6.7 Liter/ 100Km,

Fuel Consumption Combo (55% of City + 45% of Hwy) = 8.5 Liter/ 100Km,

CO2 emission Rate Combo = 19.6 Kg/ 100Km.

---

# ACKNOWLEDGEMENTS

The data has been taken and compiled from the below Canada Government official link
[https://open.canada.ca/data/en/dataset/98f1a129-f628-4ce4-b24d-6f16bf24dd64#wb-auto-6](https://open.canada.ca/data/en/dataset/98f1a129-f628-4ce4-b24d-6f16bf24dd64#wb-auto-6)

# QUESTIONS

From Kaggle following questions were asked:

1. Determine or test the influence of different variables on the emission of CO2.
2. What are the most influencing features that affect the CO2 emission the most?
3. Will there be any difference in the CO2 emissions when Fuel Consumption for City and Highway are considered separately and when their weighted variable interaction is considered?

---

# DATA EXPLORATION QUERIES

### General Queries:

1. Identify the factors affecting CO2 emissions.
2. What are the Top CO2 emissioning Fuel Types rates in Kg/ 100Km unit in City, Highway, and Combined?
3. What are the Top Fuel Consumming Fuel Type in Liter/ 100Km rates in City, Highway, and Combined?
4. What are the Top CO2 emission rates in Kg/ 100Km unit in City, Highway, and Combined per Make?
5. What are the Top CO2 emission rates in Kg/ 100Km unit in City, Highway, and Combined per Model?
6. What are the Top CO2 emission rates in Kg/ 100Km unit in City, Highway, and Combined per Vehicle_Class?
7. What are the Top CO2 emission rates in Kg/ 100Km unit in City, Highway, and Combined per Engine_Type?
8. What are the Top CO2 emission rates in Kg/ 100Km unit in City, Highway, and Combined per Cylinders?
9. What are the Top CO2 emission rates in Kg/ 100Km unit in City, Highway, and Combined per Transmission?
10. What are the Top Fuel Consumption rates in liter/ 100Km unit in City, Highway, and Combined per Make?
11. What are the Top Fuel Consumption rates in liter/ 100Km unit in City, Highway, and Combined per Model?
12. What are the Top Fuel Consumption rates in liter/ 100Km unit in City, Highway, and Combined per Vehicle_Class?
13. What are the Top Fuel Consumption rates in liter/ 100Km unit in City, Highway, and Combined per Engine_Size?
14. What are the Top Fuel Consumption rates in liter/ 100Km unit in City, Highway, and Combined per Cylinders?
15. What are the Top Fuel Consumption rates in liter/ 100Km unit in City, Highway, and Combined per Transmissions?
16. Total CO2 Production Rate Data.
17. Fuel Consumption Rate Data.

### Specific Queries:

1. Following are the Queries regarding Top 4 CO2 producing factors,

* What are Top 4 CO2 producing Makers in City?
* What are Top 4 CO2 producing Makers in Highway?
* What are Top 4 CO2 producing Makers in Combined Places?
* What are Top 4 CO2 producing Models in City?
* What are Top 4 CO2 producing Models in Highway?
* What are Top 4 CO2 producing Models in Combined Places?
* What are Top 4 CO2 producing Vehicle_Classes in City?
* What are Top 4 CO2 producing Vehicle_Classes in Highway?
* What are Top 10 CO2 producing Vehicle_Classes in Combined Places?
* What are Top 4 CO2 producing Engine_Sizes in City?
* What are Top 4 CO2 producing Engine_Sizes in Highway?
* What are Top 4 CO2 producing Engine_Sizes in Combined Places?
* What are Top 4 CO2 producing Cylinders in City?
* What are Top 4 CO2 producing Cylinders in Highway?
* What are Top 4 CO2 producing Cylinders in Combined Places?
* What are Top 4 CO2 producing Transmissions in City?
* What are Top 4 CO2 producing Transmissions in Highway?
* What are Top 4 CO2 producing Transmissions in Combined Places?

2. Following are the Queries regarding Top 4 Fuel Consuming factors,

* What are Top 4 Fuel Burning Makers in City?
* What are Top 4 Fuel Burning Makers in Highway?
* What are Top 4 Fuel Burning Makers in Combined Places?
* What are Top 4 Fuel Burning Models in City?
* What are Top 4 Fuel Burning Models in Highway?
* What are Top 4 Fuel Burning Models in Combined Places?
* What are Top 4 Fuel Burning Vehicle_Classes in City?
* What are Top 4 Fuel Burning Vehicle_Classes in Highway?
* What are Top 4 Fuel Burning Vehicle_Classes in Combined Places?
* What are Top 4 Fuel Burning Engine_Sizes in City?
* What are Top 4 Fuel Burning Engine_Sizes in Highway?
* What are Top 4 Fuel Burning Engine_Sizes in Combined Places?
* What are Top 4 Fuel Burning Cylinders in City?
* What are Top 4 Fuel Burning Cylinders in Highway?
* What are Top 4 Fuel Burning Cylinders in Combined Places?
* What are Top 4 Fuel Burning Transmissions in City?
* What are Top 4 Fuel Burning Transmissions in Highway?
* What are Top 4 Fuel Burning Transmissions in Combined Places?

---

# Observations & Insights:

Based on the above questions, we get the following answers from the Analysis,

1. **The Factors are:** 																Fuel Type, Makers, Model Types, Vehicles_Class Types, Engine Types, Cylinder Types, Transmission Types, along with the places where the fuel is burnt, ie City, Highway, and mix of both (City:Highway= 55:45).
2. **CO2 Emission Basic Details:**  												**Avg CO2 Emission Rate:** 25.62 Kg/ 100Km, Minimum CO2 Emission Rate: 10.80 Kg/ 100Km, Maximum CO2 Emission Rate: 48.80 Kg/ 100Km.
   **Total CO2 Emitted in City:** 2099.23 Kg, Total CO2 Emitted in Hwy: 2928.78 Kg, Total CO2 Emitted in Combined: 2400.47 Kg.
   **CO2 emitted in City from X-Fuel:** 1420 Kg (Max, 67.64% of total), CO2 emitted in Hwy from X-Fuel: 1180 Kg (Max, 40.28% of total), CO2 emitted in Combined from X-Fuel: 1040 Kg (Max, 43.32% total).
   **CO2 emitted in Combined from Z-Fuel:** 1230 Kg (2nd Max, 58.59%), CO2 emitted in Combined from Z-Fuel: 1180 Kg (2nd Max, 40.28%), CO2 emitted in Combined from Z-Fuel: 1040 Kg (2nd Max, 43.324%).
   There is a ***difference of 829.55 Kg of More CO2 production*** on the *Highway than the City*.
3. **Fuel Consumption Basic Details:**

   **Fuel Consumed in City:** 14,187.40 Liter, Fuel Consumed in Highway: 10,109.40 Liter, Fuel Consumed in Combined: 12,356.80 Liter.

   **Fuel Consumed in City from X-Type:** 6140 Liter (Max, 43.27%), Fuel Consumed in Hwy from X-Type: 5390 Liter (Max, 53.32%), Fuel Consumed in Combined from X-Type: 4470 Liter (Max, 36.174%).

   **Fuel Consumed in City from Z-Type:** 5870 Liter (2nd Max, 41.374%), Fuel Consumed in Hwy from Z-Type: 5390 Liter (2nd Max, 53.32%), Fuel Consumed in Combined from Z-Type: 4080 Liter (2nd Max, 33.02%).

There is ***difference of 4078 Liter more Fuel Consumed*** in the *City than on the Highway*.

4. **Makers Analysis:**
   Total no of Makers is 39. Ford and Chevrolet are the **top two makers** that produce maximum amount of CO2 (in Kg/ lt), and consume maximum amount of Fuel (in Lt/ 100Km).

| Top Makers | CO2 (Kg/ Lt)                                            | Fuel (Lt/ 100Km)                                              | Fuel Type                                                        |
| ---------- | ------------------------------------------------------- | ------------------------------------------------------------- | ---------------------------------------------------------------- |
| FORD       | 1. City: 169,<br />2. Highway: 233,<br />3. Combo: 192. | 1. City: 1.31K,<br />2. Highway: 0.96K,<br />3. Combo: 1.15K. | 1. X Type: 74.33%,<br />2. E Type: 24.60%,<br />3. Z Type: 1.27% |
| Chevrolet  | 1. City: 161,<br />2. Highway: 228,<br />3. Combo: 185. | 1. City: 1.30K,<br />2. Highway: 0.92K,<br />3. Combo: 1.13K. | 1. Z Type: 50.39%,<br />2. X Type: 42.26%,<br />3. E Type: 7.35% |

5. **Model Analysis:** Total 663 Models. **Top two models** are F150 FFV 4X4 and F150 FFV for producing max CO2 (in Kg/ lt), and consuming max Fuel (in Lt/ 100Km).

| Models       | CO2 (Kg/ Lt)                                         | Fuel (Lt/ 100Km)                                        | Fuel Type                                  |
| ------------ | ---------------------------------------------------- | ------------------------------------------------------- | ------------------------------------------ |
| F150 FFV 4X4 | 1. City: 14,<br />2. Highway: 18,<br />3. Combo: 16. | 1. City: 149,<br />2. Highway: 112,<br />3. Combo: 132. | 1. X Type: 51.69%,<br />2. E Type: 48.31%. |
| F150 FFV     | 1. City: 14,<br />2. Highway: 19,<br />3. Combo: 16. | 1. City: 143,<br />2. Highway: 106,<br />3. Combo: 126. | 1. X Type: 51.67%,<br />2. E Type: 48.33%. |

6. **Vehicle Class:** Total 16 types of vehicle classes. Mid-Size and Compact are the two types of vehicle classes that produce max CO2 (in Kg/ lt), and consumes max Fuel (in Lt/ 100Km).

| Vehicle Class | CO2 (Kg/ Lt)                                             | Fuel (Lt/ 100Km                                            | Fuel Type                                  |
| ------------- | -------------------------------------------------------- | ---------------------------------------------------------- | ------------------------------------------ |
| Mid-Size      | 1. City: 345,<br />2. HighwayL: 478,<br />3. Combo: 393. | 1. City: 1878,<br />2. Hihgway: 1341,<br />3. Combo: 1636. | 1. Z Type: 67.74%,<br />2. X Type: 36.73%. |
| Compact       | 1. City: 355,<br />2. Highway: 506,<br />3. Combo: 408.  | 1. City: 2053,<br />2. Highway: 1429,<br />3. Combo: 1770. | 1. X Type: 49%,<br />2. Z Type: 43.26%.    |

7. **Engine Size:** Total 7 types of engines are available. 2.00 and 3.60 are two types of Engine that produce max CO2 (in Kg/ lt), and consumes max Fuel (in Lt/ 100Km).

| Engine Size | CO2 (Kg/ Lt)                                              | Fuel (Lt/ 100Km                                               | Fuel Type                                                            |
| ----------- | --------------------------------------------------------- | ------------------------------------------------------------- | -------------------------------------------------------------------- |
| 2.00 size   | 1. City: 320,<br />2. Highway: 441,<br />3. Combo: 364.   | 1. City: 1.63K,<br />2. Highway: 1.18K,<br />3. Combo: 1.43K. | 1. Z Type: 49.40%,<br />2. X Type: 41.64%.                           |
| 3.60 size   | 1. City: 167,<br />2. Highway: 247, <br />3. Combo: 196. | 1. City: 1.36K,<br />2. Highway: 0.93K,<br />3. Combo: 1.17K. | 1. X Type: 66.09%,<br />2. E Type: 23.68%,<br />3. Z Type:  10.23%. |

8. **Cylinders:** Total 7 types of cylinders are available. Type - 4 and Type - 6 are the two types of Cyilnders that produce max CO2 (in Kg/ lt), and consumes max Fuel (in Lt/ 100Km).

| Cylinders | CO2 (Kg/ Lt)                                             | Fuel (Lt/ 100Km)                                              | Fuel Type                                                          |
| --------- | -------------------------------------------------------- | ------------------------------------------------------------- | ------------------------------------------------------------------ |
| Type - 4  | 1. City: 859,<br />2. Highway: 1153,<br />3. Combo: 968. | 1. City: 4.15K,<br />2. Highway: 3.08K,<br />3. Combo: 3.67K. | 1. X Type: 64.77%,<br />2. Z Type: 31.25%.                         |
| Type - 6  | 1. City: 692,<br />2. Highway: 982,<br />3. Combo: 797.  | 1. City: 4.84K,<br />2. Highway: 3.42K,<br />3. Combo: 4.20K. | 1. X Type: 45.96%,<br />2. Z Type: 39.31%,<br />3. E Type: 10.79%. |

9. **Transmission:** Total Transmission types are 22. A6 and AS6 are the two types of transmissions that produce max CO2 (in Kg/ lt), and consumes max Fuel (in Lt/ 100Km).

| Transmission | CO2 (Kg/ Lt)                                            | colFuel (Lt/ 100Km)                                           | Fuel Type                                                             |
| ------------ | ------------------------------------------------------- | ------------------------------------------------------------- | --------------------------------------------------------------------- |
| A6           | 1. CIty: 420,<br />2. Highway: 587,<br />3. Combo: 481. | 1. City: 3.19K,<br />2. Highway: 2.27K,<br />3. Combo: 2.78K. | 1. X Type: 57.56% ,<br />2. E Type: 21.84%,<br />3. Z Type: 19.28%.  |
| AS6          | 1. City: 371,<br />2. Highway: 525,<br />3. Combo: 427. | 1. City: 2.42K,<br />2. Hihgway: 1.74K,<br />3. Combo: 2.11K. | 1. X Type: 69.14%,<br />2. Z Type: 23.89%,<br />3. E Type: 6.56%.     |
