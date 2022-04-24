# Surfs_up
**Overview**: For this challenge, a company was planning no opening a surf shop in Oahu, Hawaii. We were asked to provide information on temperature trends in Oahu before opening the surf shop. Specifically, the temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round. 

## Requirements and Details of the Analysis

1. Using Python, Pandas functions and methods, and SQLAlchemy, we are to filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June. and December. The data set available is for years 2010 to 2017. We’ll then convert those temperatures to a list.

<img width="1045" alt="Screen Shot 2022-04-24 at 3 46 19 PM" src="https://user-images.githubusercontent.com/98235755/164993853-b23eea9a-1e9f-4b5c-a15d-8a5bdc817e40.png">

<img width="1023" alt="Screen Shot 2022-04-24 at 3 46 33 PM" src="https://user-images.githubusercontent.com/98235755/164993861-1691dc3a-7812-4f44-9aae-12501e6039cc.png">

2. Create a DataFrame from the lists. 


<img width="687" alt="Screen Shot 2022-04-24 at 3 47 59 PM" src="https://user-images.githubusercontent.com/98235755/164993924-4977d396-e60e-4e26-8d69-d262e988ad7c.png">


<img width="704" alt="Screen Shot 2022-04-24 at 3 48 29 PM" src="https://user-images.githubusercontent.com/98235755/164993931-0a9a412f-a605-4c52-affb-624d4ea40f92.png">



4. Generate the summary statistics.


<img width="742" alt="Screen Shot 2022-04-24 at 3 48 58 PM" src="https://user-images.githubusercontent.com/98235755/164993947-511eb40f-a12f-4bcf-a0f1-d7552ee924d8.png">


<img width="831" alt="Screen Shot 2022-04-24 at 3 49 08 PM" src="https://user-images.githubusercontent.com/98235755/164993951-41f618c5-2bc6-42a6-8f7e-0ba08431c342.png">

5. Additional analysis of precipitation in June and December were done. 

<img width="318" alt="Screen Shot 2022-04-24 at 4 23 04 PM" src="https://user-images.githubusercontent.com/98235755/164995087-990b5abc-e544-431b-8219-9726d43b5c61.png">


<img width="396" alt="Screen Shot 2022-04-24 at 4 23 50 PM" src="https://user-images.githubusercontent.com/98235755/164995106-a3e4d1d6-2062-4a3a-a2f9-840acf851abe.png">



## Results of the Analysis

1. Note that the data has more June recorded temperature than December because the dataset only goes up to 08/2017, hence missing not having any December 2017 data. Despite that, in my opinion given there were atleast 6 years of data, the summary and conclusions provided below still is a good representation of the analysis results.

2. Based on the statistical summary , June has a warmer average temperature of 74.94 vs. December's average of 71.04. Additionally, June's min-max temperatures are 64-85 than December's 56-83. 

3. Additional analyses of Oahu's June and December precipitation data showed some interetsting finding. The graphs shows that it rained more in the months of June than December. However, the amount of rain (when it rained) were higher in the month of December (ave. of .216) than June's .136). Relatively, the min-max precipitation for Dec was .00-6.42 and June's was .00-4.43. I believe that this is due to lower denominator (ie days it rained) in the month of December that the ave precipitation measurement becomes higher - "when it rains, it pours" as they say seems to be a perfect definition of the December month data.

Summary:
Overall, I think it is still worth investing in the surf and icecream shop in Oahu. I would recommend also offering some hot drinks for months that were a bit chilly. 
