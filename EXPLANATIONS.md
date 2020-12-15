API's For Create,authenticate,add cities,remove Cities,retrieve cities

1.A user should be able to create an account.

https://localhost:44329/fort/CreateUser/?Name=(name)&&EmailId=(EmailID)&&PassWord=(PassWord)

2.A user should be able to authenticate with an email and password

https://localhost:44329/fort/AutheticateUser/?EmailId=(EmailID)&&PassWord=(PassWord)

3.An authenticated user should be able to add and remove their favorite cities
AddCities:
========
https://localhost:44329/fort/AddCityCountry/?EmailId=(EmailID)&&PassWord=(PassWord)&&City=(City)&&Country=(Country))
DeleteCity:
========
https://localhost:44329/fort/DeleteCities/?EmailId=(EmailID)&&PassWord=(PassWord)&&City=(City)&&Country=(Country))

4.RetriveCities:

https://localhost:44329/fort/RetrieveCities/?EmailId=(EmailID)&&PassWord=(PassWord)