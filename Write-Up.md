Abstract

The purpose of this project is to investigate which NYC MTA station has the highest foot traffic during the morning (6am - 10am) and evening (4pm - 7pm) rush hour periods for New York Marketing Firm (NYMF). Their goal is to purchase ten advertisement spaces to maximize potential consumer exposure for a new product designed by a healthcare technology company. I extracted six months (7/31/21-1/28/22) worth of data from the MTA and leveraged individual turnstile traffic data against two 4 hour timeblocks and created multiple representative visualizations. 

Design

The New York Marketing Firm (NYMF) has been hired by Feel to help promote their new product, Emote, a wearable device that allows people to share their psychological state/emotions with a medical provider to improve diagnosis accuracy and treatment efficiency. Since most people use the NYC MTA on a daily basis, they figured it would be a smart move to explore that avenue for a way to increase sales. 

Data

I sourced 6-months worth of MTA traffic data from the NYC MTA Turnstile. The total data set includes 5,458,607 entries separated by 4 hour timeblocks starting from 3am as well as eleven categories: C/A, UNIT, SCP, STATION, LINENAME, DIVISION, DATE, TIME, DESC, ENTRIES, EXITS. Description for each category can be found on the [MTA Site](http://web.mta.info/developers/resources/nyct/turnstile/ts_Field_Description.txt).

Algorithms

1. Extracted MTA turnstile data and imported it into DB Broswer for SQLite
2. Created a SQLAlchemy engine that bridges the SQLite database to the Python database
3. Performed in depth data cleaning and analysis within Pandas
4. Created visualization representations of the data using Matplotlib

View full python code on my [GitHub](https://github.com/tesung/EDA-Project/blob/main/Project_Code.ipynb)

Tools

1. Jupyter Lab and SQLite for data manipulation
2. Python Pandas for data cleaning and analysis
3. Python Matplotlib for data visualization 
4. Github for code upload/sharing

Communication

[Presentation slide deck](https://github.com/tesung/EDA-Project/blob/main/PresentationSlideDeck.pdf)


