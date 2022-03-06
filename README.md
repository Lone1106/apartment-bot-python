# apartment-bot-python
This is a Python Selenium App that helps me apply for a new Apartment.

To make it work you need to add a second file into the main.py directory. 

e.g. data.py and this needs to contain a object like the following:

Data = {
  "plz": "the postcode of the apartment area here",
  "price": "max price of the apartment without heating costs, etc.",
  "first-name": "Your first name",
  "last-name": "Your last name",
  "email: "Your email",
  "message": "The message that should be send to the person offering the apartment",
  "adress": {
    "street": "The street where you live",
    "number": "The number of your house",
    "plz": "Postcode of your City/Village",
    "city-name": "Name of your City/Village"
    }
  }
