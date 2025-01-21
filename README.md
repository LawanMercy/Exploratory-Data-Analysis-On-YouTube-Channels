# Exploratory-Data-Analysis-On-YouTube-Channels

## Introduction
The "YouTube Channel" project involves the exploration and visualization of a dataset containing information about various YouTubers. This project conducts a simple EDA on YouTube channel dataset to identify trends, relationships, and outliers influencing content success, using statistical and visual analysis techniques to understand popular channels and engagement levels. This analysis aims to understand dataset structure, identify content creation trends, explore correlations, assess outliers, and provide insights into high-performing content categories like Music and Entertainment, offering recommendations for optimizing performance. The analysis is conducted using Python programming language and popular data analysis libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

### Brief Overview of the Dataset
The dataset contains 995 entries and 28 columns. It primarily includes information about YouTubers, such as:
- Rank: Position of the YouTuber in terms of popularity.
- Youtuber: Name of the YouTube channel.
- Subscribers: Number of subscribers the channel has.
- Video views: Total views the channel has received.
- Category: Content category (e.g., Music, Education).
- Uploads: Number of videos uploaded by the channel.
- Country: Country of origin of the channel.
- Created_year and created_date: Date the channel was created.
- Earnings: Estimates of monthly and yearly earnings.
- Demographic: Includes population, unemployment rate, and urban population for the country, etc.

### Data Loading and Cleaning
The project begins with loading the dataset using the Pandas library. The dataset, stored in a CSV file, includes information like rank, subscribers,video views,country, etc.To ensure data quality,initial checks are performed to identify missing values using the pd.isnull() and info() functions.

### Exploratory Data Analysis
**1.	Descriptive summary for the “uploads” feature/attribute.**

![image](https://github.com/user-attachments/assets/e4eae4cb-9f4c-48ca-a4f9-1362b1497715)

**2. Colums with Outliers**

![image](https://github.com/user-attachments/assets/6d5dc32c-5872-4336-ab3c-3b6b5ec3cd1a)


**3. One Univariate analysis (one plot) for any categorical feature/attribute of your choice.**

![image](https://github.com/user-attachments/assets/5517b8df-bdbc-4f27-b789-cfcf04145634)

**4. One Univariate analysis (One plot) for any continuous features/attribute of your choice.**

![image](https://github.com/user-attachments/assets/00c69ed7-75ce-442f-b688-48bf1ffd8337)

**5. Two Bivariate analysis (One plot) for any two features of your choice**

![image](https://github.com/user-attachments/assets/4f87bd0b-19a5-491d-b4f0-8477e59e0616)

![image](https://github.com/user-attachments/assets/1f91bcb4-5b33-4f1f-af3e-b6e967342ded)

**6. One Multivariate analysis (One plot) for any three features of your choice**

![image](https://github.com/user-attachments/assets/b05c4fb1-6d30-45ed-88ae-4ef9ba3f65eb)

**7. Correlation Heatmap**

![image](https://github.com/user-attachments/assets/3297b667-74b1-40e0-a610-962faba77e13)


 





