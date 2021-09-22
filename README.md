# enjoy-a-day-off
Road Trip Innovation Challenge 2021
https://opendata.transport.nsw.gov.au/road-trip-innovation-challenge

*** QUICK MOCKUP ***
https://marvelapp.com/prototype/h3ie97b/screen/82186181


•	Briefly describe your solution for the Innovation Challenge. *
Name of Project:
Enjoy a day off in NSW

Purpose of the App/User Story: 
For weekender to get inspirations/ideas/suggestions for places that can be visited causally (travel without much planning and can be done day-return/a few hours)

How it works
Search POI (selected Categories only) based on radius km of a location (enter address or drop pin on map). Provide information of each POI, including address (lag/long and redirect to External Map App), facilities, (if permitted, list First Nations Place Name) etc.

Users may “check-in” the POI once they are there (by GPS). The more POI they visited, the more “rewards” they get, to encourage them to discover places they never been before. User may rate the POIs to help other user to find popular/favourable ones (when the database builds up), and for the LGA they can review the ones that has lower rating and see if there are any reasons behind and hence improve those least favourited POIs.

Initially: Categories are limited based of common categories from selected datasets
e.g. Lookout, picnic area, barbecue, playground, heritage site etc

If funded/partnered with sponsors/permitted: add businesses (e.g. businesses participated with dine and discover vouchers)

Target Audience: 
Individuals/Family/Small Group 

Rewards for user
Initially (Free Version): Collect badges/trophies when they reach a certain level (e.g. visited 10 lookouts, continuously using app for 4 weeks, shared the app to friend etc)

If funded/partnered with sponsors: Collect in-app-points and redeem gifts/discount from participating businesses.
(e.g. km travelled/steps walked/check-in at certain locations etc)

Digital Platform: 
A Website/Phone App 

•	There are two Challenge Statements. 
Which Challenge Statement(s) will your solution be addressing? *
1.	Create a digital solution that improves the tourism and road trip experience in NSW and/or 
2.	Create or enhance data related to road trips that can be published as Open Data

•	If your solution produces any data, what data can be shared openly to the public via the TfNSW Open Data Hub? *

As this Website/App will collect data from several datasets and combine to one database, the merged data/API can be exported back to Open Data Hub.
- Unified Categories from various datasets
- Collect users clicks/save as favourites/visited(checked-in) to build popularity/ratings for each POI

•	How is your solution innovative or unique? *
Most existing Apps/websites are for users who already know what they want (such as which National Park to go, or, suggesting a few days itinerary based on destination). My concept is to browse within a certain radius surrounding, and to discover 

•	How will your solution provide an improved customer experience? *
My aim is to fill the gap for weekend traveller who just want to find something to do(search by category), rather than already knowing what to do. So, the App will be heavily focus on UX, and hoping to keep it simple, easy to use, rather than wasting too much time researching different apps/websites to gather information.

•	Is your solution technically feasible? Provide details on how it is technically feasible and share examples of any previous implementations. *
I compared “NSW Rest Area” Dataset and “NSW Features of Interest” Datasets, NSW National Park App, and found that some categories are common/similar (such as “Lookout”, “Picnic Area”, “Barbecue facilities”). So initially I will be building a database merging these existing datasets only, which I believe it is completely doable. The technology I am considering will be using Graph Database to link the relationships between different datasets together.

•	Will your solution use Transport for NSW Open Data or other datasets? If so, which data sets will it use? *
NSW Rest Areas
https://opendata.transport.nsw.gov.au/dataset/nsw-rest-areas 

NSW_Features_of_Interest_Category
https://portal.spatial.nsw.gov.au/portal/apps/sites/#/home/pages/nsw-data-themes 

State Heritage Inventory
https://www.hms.heritage.nsw.gov.au/App/Item/SearchHeritageItems

NSW National Parks and Wildlife Service
https://www.nationalparks.nsw.gov.au/things-to-do 

AIATSIS - Whose Country am I on?
(If permitted, the address/location of the POI may include first Nations Place Names)
https://aiatsis.gov.au/explore/map-indigenous-australia 

Dine & Discover NSW business finder
https://mybusiness.service.nsw.gov.au/dine-and-discover/business-finder 

(Some inspirations are from: https://2kmfromhome.com)

•	What is your business model? Please explain how your idea is commercially sustainable. *
I am a part-time student studying Diploma of Websites Development (ICT50615) at Ultimo TAFE. Initially I am doing this project as a school assignment, purpose will be just for help improving the community.

•	How will you give us assurance that you can launch your solution to the public by March 30, 2022? *
My TAFE assignment is due late November 2021 so a prototype must be built by then. My TAFE teacher promised to provide ongoing support even after the course finish. 

•	Following the successful implementation of your solution, what data and insights can you share with TfNSW that can be used for analysis and future planning? *
- Users habit (click/faourites/check-in) of the POI
- Users ratings of the POI
- Unify the Name of Categories in different datasets
- Templatise columns of database if LGA/Tourism liked the way I setup with the merged data 

•	Supporting documentation (Link to Dropbox or online sharing platform)
https://github.com/karensplam/enjoy-a-day-off.git

•	Up to $25,000 is available for seed funding per team, please outline the amount you require and how you would allocate these funds. Please keep in mind that value for money is a key selection criteria. *
Initially - will be using free/open source, Free web hosting (GitHub / Pantheon) 

Further developments: 
Cost of hosting the website, SSD Storage, SSL etc
Cost of External Web Developer, Graphic Designer, Software cost etc
