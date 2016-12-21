# democratia.ch
This is the working in progress for a protoype that that will allow foreign people in Switzerland to express their opinion on popular initatives and referendums. Additionally the system will also allow Swiss citizens that are between 16 and 18 years old to express their opition as well.
The system will allow to "vote" on simple yes/no questions such as the ones used in popular initiatives and referendums. 

## Authentication
A user that wants to create a new account will have to provide an e-mail address, password and a digital copy of his residence permit. The residency permit is neccessary to make sure that not everybody can create an account. 
The account will not be created immediately. Rather two referees will indepdendently check the validity of the residence permit and copy the data from the permit into the system. Only if the recorded data of both referees match a new account will be created. 

## Data privacy
As soon as an account has been confirmed all personal data can be deleted. Only statistical demographic data will be kept (birthyear, gender, ...). The demographic data will not be enough to identify a person. 
The data from the permit will be used to create a hash that will prevent people from creating multiple accounts. 

## Data publication
Each registered vote will be published publicly directly in an anonymous fashion. This will allow the user check that his vote has been registered correctly in the system. 
The direct publication would allow everyone to calculate the current standings of the voting process. To prevent this each vote will be accompanied by a certain number of deception votes. Deception votes are automatically generated and at can at first not be distinguished from regular votes. Only when the voting process is over it will be revealed which votes are real and which are deceptions.
The yes/no count of the deception votes will follow a fixed statistical distribution. The distribution will be set at the beginning of the voting process. How the votes are distributed will be revealed when the voting is over. This will allow to check whether the deception votes follow this distribution or if they have been tampered with. 
