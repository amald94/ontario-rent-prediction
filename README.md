# ontario-rent-prediction

<img src="https://i.ibb.co/wShF3QK/toronto-154805.jpg"/>

# Ontario house rent prediction

### Can you suggest house rent in Ontario cities to newcomers?

**House rent in Ontario especially in GTA gets even harder at scale**, considering the new immigrants in Ontario, based on their preference lets try to predict prices in different cities.

**Kijiji**, Kijiji is an online classified advertising service that operates as a centralized network of online communities, organized by city and urban region, for posting local advertisements. 

In this project, I scraped some data from Kijiji to build a dataset for training my ML model, which will help newcomers to get an overall idea about the rent in a city based on their input. let's say if someone wants to move to Mississauga in a private room or shared basis, this model will predict the expected range of rent in the city based on the input.

**Recommendation**, City Recommendation will also be developed within this project to give the user some suggestions on the cheapest nearby city to look for house rentals. -> Future Work :))


### Dataset Features

Since the dataset is scraped from the Kijiji website, I made some features that I think are relevant to this project and I tried to keep it minimal as possible.

- **Title**: Title of the advertisement
- **Description** : Description of the advertisement
- **Features** : Features of the advertisement. ( furnished or not, pet friendly or not etc)
- **Location** : Location of the property
- **Price** : Rent in CAD
- **Ddate Posted** : Posted date of the advertisement
- **URL** : advertisement url

