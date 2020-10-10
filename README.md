# What Fell Under the Radar? Accountability and the NYPD

## Blog Version


# Summary
My project is will focus on the 33,358 records of Propublica.org published NYPD complaint records between 1994-2020. I wanted to see if NYPD officers were being held accountable after recieving a substaintuated allegations of misconduct. The data set can be downloaded on the website https://www.propublica.org/datastore/dataset/civilian-complaints-against-new-york-city-police-officers or you can download this repository.

*After New York state repealed the statute that kept police disciplinary records secret, known as 50-a, ProPublica filed a records request with New York City’s Civilian Complaint Review Board, which investigates complaints by the public about NYPD officers. The board provided us with records about closed cases for every police officer still on the force as of late June 2020 who had at least one substantiated allegation against them. The records span decades, from September 1985 to January 2020.*

*We chose to include the basic information disclosed by the CCRB about allegations that investigators deemed unsubstantiated. Unsubstantiated means the CCRB, which has limited investigative powers, was not able to confirm that the alleged incident happened and that it violated the NYPD’s rules.*

*We also chose to include cases where an investigator found that what a civilian alleged did happen but the conduct was allowed by the NYPD’s rules. The Police Department’s guidelines often give officers substantial discretion, particularly around use of force. Those cases are classified as “exonerated.”*

*Each record in the data lists the name, rank, shield number, and precinct of each officer as of today and at the time of the incident; the age, race and gender of the complainant and the officer; a category describing the alleged misconduct; and whether the CCRB concluded the officers’ conduct violated NYPD rules.*

*All this information can help readers examine the records of officers who have been the subject of a pattern of complaints.*

# Objectives
- Are ad boosts increasing product revenue?
- Are product badges increasing product revenue?
- Does the tag count have an effect on product revenue?
- Can we predict the units sold of a product by just looking at its tag count?

# Project Steps & Further Questions:

## Data Cleaning:

- Remove duplicates or records with missing or mismatched values.
- Removing unnecessary columns. 
- Replacing certain null values with appropriate zero values.

## Data Wrangling:

- Created new columns for better analysis.
- Creating functions to help label data.
- Creating Visualizations.

## Ad Boosts:

- 584 products with ad boosts, 757 products without ad boosts.
- $37,400 average product revenue for products with ad boosts, $40,313 average product revenue for products without ad boosts.
- *Unsuccessful Products* = 45% of products use ad boosts, *Successful Products* = 41% of products use ad boosts.

## Product Badges:
- 10% of products have a product badge.
- Products with badges generate 34% more average revenue per product compared to products without badges.

## Tag Count:
- Most of the products have between 13 to 19 tags, 16 being the most popular number of tags.
- Products that have a high tag count (29, 34, 37, 41) are generating a higher average product revenue than the popular 13-19 tag range. 

## Linear Regression Model - Predicting Units Sold using Tag Count:
- I wanted to see if a linear regression model could be created in order to predict the amount of units sold of a product.
- Unfortunately due to the way the units sold were inputted in the dataset, there was no way to create an effective model to prediction.
- A more robust data set is needed for this model creation.

## Recommendations and Next Steps:
- The Ad boost service needs to be investigated even further.
- Inform the merchants on Wish about the effectiveness of product badges.
- Run some tests to see if limiting the number of tag words per product would have any effect on sales.
- More robust data is needed to implement an appropriate predication model for units sold.

# Contact Information 
- **Name:** Christian Rios-Chambi
- **Email:** crioschambi@gmail.com
- **LinkedIn:** linkedin.com/in/christian-rios-chambi/
- **Github:** github.com/criosch1
