# Big_data
using AWS and google colab to ETL Amazon Reviews

# **Overview**

In this module we used Google Colab and AWS in order to filter through data of Amazon product reviews to determine if there was any bias between paid and unpaid reviews left on the product.

## **Software**

- Google Colab
- Pandas
- Pyspark
- SQL
- PGAdmin4

## Results

- **Below are some of the screenshots from different checkpoints in the module showing relevant data for our analysis with examples of some of the filters used in order to create seperate data frames and tables to hold the different relative data.**

<img width="636" alt="Screenshot 2023-03-08 at 9 29 48 AM" src="https://user-images.githubusercontent.com/114188120/223748972-d8f5873f-31dd-45bf-8fb5-f5245f3d171c.png">
<img width="435" alt="Screenshot 2023-03-08 at 9 29 54 AM" src="https://user-images.githubusercontent.com/114188120/223748974-44e9575a-8bf7-4b81-94a7-fcecc5128db7.png">
<img width="796" alt="Screenshot 2023-03-08 at 9 31 16 AM" src="https://user-images.githubusercontent.com/114188120/223748976-6b0d730e-a1f1-432f-bc7c-b6406b051b54.png">
<img width="772" alt="Screenshot 2023-03-08 at 9 56 23 AM" src="https://user-images.githubusercontent.com/114188120/223748977-977a2fa6-4f16-453c-b88d-ab617683d95e.png">
<img width="680" alt="Screenshot 2023-03-08 at 9 59 22 AM" src="https://user-images.githubusercontent.com/114188120/223748983-55291c35-2dd4-4ac6-98be-8e2ec08ddc2f.png">


# _Summary_

Based on our findings on the video game review data, the difference between paid and unpaid 5 star reviews was roughly a 12% difference. This came based on a much larger total count of reviews from unpaid patrons (roughly 40,000) where the overall percentage of 5 star reviews was around 38% as compared to the paid reviews (roughly 100) was over 50%. This would lead us to believe that there is at minimum some bias from the paid reviews that is leading to leaving higher reviews. 
