# Call-Analysis ReadMe
## Group Name:
Project Group 7
## Section:
IEORE4501_001_2021_3
## Uni
1. Ze Yu Zhao: zz2873
2. Vivian Yang: 

## Descripion for File: Top10.ipynb



## Descripion for File: Parking.ipynb
For this file, we first examined the entire dataframe and found out that variable Zipcode is in the type of float. By converting our target zipcode 10025 into a float to match the type in the dataframe, we updated the dataframe to include incidents only in the target zipcode 10025 by using the loc function. Then we used the unique function on 'Complaint Type' to get all complaints and found out that the value associated with parking incidents is named 'Illegal Parking' in the dataframe. We used the sum function to count every 'Illegal Parking' occurence. For all incidents happened in the target zipcode, we used the count function to every 'Complaint Type' incident. Then we stored the result of total parking incidents in zipcode 10025 divided by total incidents in 10025 in a variable called 'fraction_10025'. We followed the same procedure for the entire dataframe and got the result stored in variable 'fraction'. Finally, we created a boolean variable called 'higher_parking_proportion' that take value of True when 'fraction_10025'>'fraction' and False otherwise. Final result was 'higher_parking_proportion' is False.
