# School District Analysis

## Overview
Maria is doing an analysis of a school district, and she has asked for my help. Due to the possibility of dishonesty from one of the schools, the dataset must be altered to omit ninth graders from Thomas High School. She is looking for someone that can work with the Panda’s Library to create tables for her to visualize her data. Using Python and Pandas, I am going to provide her with the requested sets of information in an easy-to-understand format.

### Results
-	The district summary is hardly changed, with less than one percent difference with the new dataset.

![Original District Summary](https://user-images.githubusercontent.com/86024575/127038716-f8dc1db1-7793-418c-bf06-66021cf5bcb7.png)

*Orignal District Summary*

![Updated District Summary](https://user-images.githubusercontent.com/86024575/127038749-beb39141-03e7-4887-9631-ecb7b03820eb.png)

*Updated District Summary*

-	The school summary has changed drastically, with roughly thirty percent drop in Thomas High School’s numbers.

![Original THS scores](https://user-images.githubusercontent.com/86024575/127042632-13cf1a90-9bae-4151-9ae7-0fd23ed8e5e6.png)

*Original Thomas High School Scores*

![Updated THS Scores](https://user-images.githubusercontent.com/86024575/127042654-ac43c474-04e8-44f1-8297-0d50e5ee7108.png)

*Updated Thomas High School Scores*

-	Replacing the ninth grader’s scores with null values brings Thomas High School down from the second highest performing spot to the eighth highest performing spot.

-	The math and reading scores by grade table now has “nan” for the ninth-grade column, but other scores are unaffected.

![Math Scores by Grade](https://user-images.githubusercontent.com/86024575/127040711-b9b494c3-20ab-465c-bfa8-4352a3c42782.png)

*Updated Math Scores by Grade*

-	Scores by school spending summary has increased in the in the $585-629 and $630-644 ranges.

![Original Scores by School Spending](https://user-images.githubusercontent.com/86024575/127041334-63ea8e6c-a0ee-4cb7-8e5e-28d821cc605e.png)

*Original Scores by School Spending*

![Updated Scores by School Spending](https://user-images.githubusercontent.com/86024575/127041383-aaefb868-1c0d-46f1-ae92-b7968c513f13.png)

*Updated Scores by School Spending*

-	Scores by school size summary has been unaffected.

![Original Scores by Size](https://user-images.githubusercontent.com/86024575/127041941-43c0e924-faf9-4a49-9151-8b34c27ccf56.png)

*Original Scores by School Size*

![Updated Scores by Size](https://user-images.githubusercontent.com/86024575/127042001-61fa8d5b-c6a1-4136-b92c-1dce1541f80a.png)

*Updated Scores by School Size*

-	Scores by school type summary has also been unaffected

![Original Scores by Type](https://user-images.githubusercontent.com/86024575/127042311-221d72da-978f-4e4d-b214-2a35ce1e8c55.png)

*Original Scores by School Type*

![Updated Scores by Type](https://user-images.githubusercontent.com/86024575/127042350-c81c18a9-d875-4e40-b260-82b76c45e8f1.png)

*Updated Scores by School Type*

### Summary
Replacing the grades of the ninth graders had the largest effect on the per school summary. However, after fixing the number of students for Thomas High School and taking the new percentage, the new numbers are not very different from the original summaries. 
