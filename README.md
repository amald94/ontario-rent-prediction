# ontario-rent-prediction

<img src="https://i.ibb.co/wShF3QK/toronto-154805.jpg"/>

# Ontario house rent prediction
***
### Can you suggest house rent in ontario cities to new comers ?

**House rent in ontario especially in GTA gets even harder at scale**, considering the new immigrants in ontario, based on their preference lets try to predict prices in different cities.

**Kijiji**, Kijiji is an online classified advertising service that operates as a centralized network of online communities, organized by city and urban region, for posting local advertisements. 

In this project I scraped some datas from kijiji to build a dataset for training my ML model, which will help new comers to get an overall idea about the rent in a city based on their input. lets say if someone wants to move to Mississauga in a private room or shared basis, this model will predict the expected range of rent in the city based on the input.

**Recommendation**, City Recommendation will also be developed within this project to give the user some suggestions on cheapest nearby city to look for house rentals. -> Future Work :))


### Dataset Features

Since the dataset is scraped from kijiji website, I made some features that I think is relevent to this project and I tried to keep it minimal as possible.

- **Title**: Title of the advertisement
- **Description** : Description of the advertisement
- **Features** : Features of the advertisement. ( furnished or not, pet friendly or not etc)
- **Location** : Location of the property
- **Price** : Rent in CAD
- **Ddate Posted** : Posted date of the advertisement
- **URL** : advertisement url
