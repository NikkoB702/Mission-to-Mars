# Mission-to-Mars

## Deliverable 1

##### Scrape titles and preview text from Mars News

Using Splinter and Beautiful Soup we were asked to scrape the [Mars News] (https://redplanetscience.com/) website. Specifically, scrape the title and preview text and optionally store the scraped data in either a JSON file or a MongoDB database.

## Deliverable 2

##### Scrape and analyze Mars weather data

Using our original webscraping dependencies as well as Pandas and Matplotlib we were asked to scrape the [Mars Temperature Data] (https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html) and answer the following questions;
  
  * How many months exist on Mars?
  * How many Martian (and not Earth) days worth of data exist in the scraped dataset?
  * What are the coldest and the warmest months on Mars (at the location of Curiosity)?
  * Which months have the lowest and the highest atmospheric pressure on Mars? 
  * About how many terrestrial (Earth) days exist in a Martian year? That is, in the time that Mars circles the Sun once, how many days elapse on Earth?
  
  We were then asked to export our DataFrame into a CSV file.
  
## Our findings
  
##### How many months exist on Mars?
   * 12
    
 ![Month_snap](https://user-images.githubusercontent.com/80132877/202784608-b892152d-753e-44f1-b3ab-dd774a5ccace.png)


##### How many Martian (and not Earth) days worth of data exist in the scraped dataset?
  * 1967

![Martian_days_snap](https://user-images.githubusercontent.com/80132877/202784877-6bbc49c8-943c-45ad-98da-87f1a9018d33.png)


##### What are the coldest and the warmest months on Mars (at the location of Curiosity)?
  * Coldest month is the 3rd month, warmest month is the 8th month

![Avg_monthly_temps_snap](https://user-images.githubusercontent.com/80132877/202785543-09a63b38-fe37-4f5c-ab43-6759c1e893bc.png)

![Monthly_min_temp](https://user-images.githubusercontent.com/80132877/202785590-7a676a22-b545-4e78-a70f-09072839aa55.png)


##### Which months have the lowest and the highest atmospheric pressure on Mars? 
  * Lowest pressure is the 6th month, highest pressure is the 9th month

![Pressure](https://user-images.githubusercontent.com/80132877/202785839-f11964a8-3e5f-469f-aa5d-751d889d1b2b.png)


##### About how many terrestrial (Earth) days exist in a Martian year? That is, in the time that Mars circles the Sun once, how many days elapse on Earth?
  * 687 Earth days for every Martian year

![Time_lapse](https://user-images.githubusercontent.com/80132877/202786025-703755b0-d7f1-48ac-b11d-ab99430f96de.png)
