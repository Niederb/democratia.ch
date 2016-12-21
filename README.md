# democratia.ch
Prototype for a web portal that allows foreign people in Switzerland to express their opinion on popular initatives and referendums. Additionally the system will also allow Swiss citizens that are between 16 and 18 years old to express their opition as well.

## Authentication
A user that wants to create a new account will have to provide an e-mail address, password and a digital copy of his residence permit. The account will not be created immediately. Rather two referees will indepdendently check the validity of the residence permit and copy the data from the permit into the system. Only if the recorded data of both referees match a new account will be created. 

## Data privacy
As soon as an account has been confirmed all personal data can be deleted. Only statistical demographic data will be kept (birthyear, gender, ...). The demographic data will not be enough to identify a person. 
The data from the permit will be used to create a hash that will prevent people from creating multiple accounts. 

## Data publication
