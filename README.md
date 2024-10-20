# Content:

This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, among other things. It is ideal for exploratory data analysis (EDA) or get started in building predictive models!

# Problem Statements:

**1. Comparison of Hotel Type and Type of stay**

    1. Which type of hotels preferred by peoples ?
    
    2. Which type of stay prefrered by peoples in week days and week ends?

![image](https://github.com/user-attachments/assets/f4b5017a-be7a-42c9-a3cd-c169ef8e909f)

   **Insights:**

     * Generally resort hotels have low customers than city hotels for week and weekend nights
     * Week nights have high population for both hotel types than weekend nights

![image](https://github.com/user-attachments/assets/d5ccbeb8-808a-4b9d-9fac-69a5a1a785ca)

   **Insight:**

     * In any given week, most people sleep in a city hotel than resort hotel



**2. Customer type for the hotel types**

    Which customers prefers which type of hotel?

![image](https://github.com/user-attachments/assets/d1f7789a-19d0-448b-9ac2-c6b0406b2202)


   **Insights:**

       * Transient customers form the majority of customers for both hotel types while Group customers the least
       * These transient customers and Transient-Party customers prefer City Hotels.
       * Majority of the contract and group customers prefer resort hotel


    
**3. Lead time comparison among different hotels types** 

(Lead time is the number of days that elapsed between the entering date of the booking into the PMS and the arrival date)

    1. To determine the average lead time for each hotel type.
   
    2. To identify any significant differences in lead time between different hotel types.
   
    3. To assess the booking behavior and planning horizon of guests based on hotel type.

![image](https://github.com/user-attachments/assets/1017005c-09e7-4f4b-b742-f6b8df6d55ef)


   **Insigts:**

     * The T-statistic value of -10.13 indicates a substantial difference in lead times between the hotel types. The very low value (p<0.05) confirms this significant difference. We conclude that lead times between hotel types vary.

     * This indicates varying booking patterns and customer behaviors have an influence of how far in advance guests book/reserve their stays in city and resort hotels



**4. Customers with highest lead times for hotel types**

![image](https://github.com/user-attachments/assets/7a965e8d-5265-4601-87b8-5dbcdf94d0a8)



**5. Mean lead times for difefrent customers**

![image](https://github.com/user-attachments/assets/61a9aebc-b9d2-465e-83ac-5de36f6ecb38)



**6. Reservation Status**

    Examine the distribution of reservation statuses for each hotel type.

 ![image](https://github.com/user-attachments/assets/0792d394-81f9-4cc4-a984-e47955044243)

   **Insights:**

        * Both hotel types have significant amount of chekouts but was high in City hotels
        * Both hotel types have lower no-show cases.
        * City hotels have more cancellations

**7. Compare customer type and reservation for different hotel type**
   
    The objective is to analyze and compare the relationship between customer type and reservation status for each hotel type

![image](https://github.com/user-attachments/assets/2725afd6-de0b-4a38-93e1-e1f6bd21ef9c)


**8. Deposit and reservation status**
   
    The objective is to compare the relationship between deposit type and reservation status for each hotel type to understand how deposit policies affect reservation outcomes

![image](https://github.com/user-attachments/assets/2bd5f676-1455-4042-bb6c-07fd4629090d)


**9. Room Type Preferences**

    Examine the distribution of reserved room types for City Hotel and Resort Hotel to understand guest preferences.

**10. Average days in waiting list**

![image](https://github.com/user-attachments/assets/451390a6-a253-4767-a42b-7bab4df0269c)

   **Insights**

        * It takes less time to get confirmation for booking from resort hotel than city hotel

**11. Average daily rate (ADR)**
ADR is Average Daily Rate as defined by dividing the sum of all lodging transactions by the total number of staying nights

     1. To determine the average daily rate for each hotel type.
    
     2. To identify any significant differences in ADR between different hotel types.

 ![image](https://github.com/user-attachments/assets/6c7c2aaa-91db-4e01-bb55-da198dc625b3)

 ![image](https://github.com/user-attachments/assets/24579432-5256-4555-b778-556f81f9910c)

 


   **Insight:**

        * The T-statistic is 30.7 while p<0.05. This indicates a highly significant difference in ADR between City and Resort Hotel. Therefore, the average pricng per night varies significantly betweebn the hotel types.


**12. Customer Type and ADR**

    The objective is to compare the Average Daily Rate (ADR) between different customer types for each hotel type (City Hotel and Resort Hotel) to analyze pricing differences based on customer categories.

  ![image](https://github.com/user-attachments/assets/b8f1fa70-b3e0-4b75-8b3c-ca797efc93ee)

   **Insights**

        * Generally, ADR is quite high for City Hotel for all customer types
        

**13. ADR and meal type**

    The objective is to compare the Average Daily Rate (ADR) for different meal plans (Undefined/SC – no meal package; BB – Bed & Breakfast; HB – Half board (breakfast and one other meal – usually dinner); FB – Full board (breakfast, lunch and dinner)) offered by hotels for each hotel type (City Hotel and Resort Hotel) to understand pricing differences related to meal inclusions.

![image](https://github.com/user-attachments/assets/386ee857-6eca-43f3-aa3b-f3d795a0520a)


**14. Average Daily rate when parking is required**

![image](https://github.com/user-attachments/assets/9ecfa71b-fc1d-4ab5-a2ab-9fba20956432)



**15. Time Series Analysis**

     * Arrival day of month

![image](https://github.com/user-attachments/assets/e0340393-bda3-4800-8206-a47532f93f1f)

    * Arrival by week number
    
![image](https://github.com/user-attachments/assets/d6cb6a5c-1973-4420-9e59-41b8a35a6edc)


    * Arrivals during a month

![image](https://github.com/user-attachments/assets/69941934-0215-4cad-ba8d-e14e7710c956)


    * How ADR behaves during a year

![image](https://github.com/user-attachments/assets/6c5d10b9-6ce7-4a72-914b-c5aaacc0f8ae)


   **Insights:**

        * Resort Hotels exhibit seasonal demand, likely driven by tourism trends, which causes significant variation in ADR.
        * City Hotels seem to cater to a more consistent customer base, perhaps business travelers or urban tourists, leading to steadier ADR values.
