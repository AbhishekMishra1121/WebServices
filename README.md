# WebServices
Salesforce Webservices Assignments   


#1=>
Self Dispatch Of WO
Requirement : When a technician click on Self Dispatch SFM from WO object, It will allow user to create Event for that WO, Event should be automatically assigned to the technican according to current logged in user.
              And update the field in WO as dispatch status to assigned and technician should be populated with current logged in technician.
SFM name: Self Dispatch
Object Used : WO and Servicemax Event.
User can see or enter the value to the following Field:
1. WO -Account,Order Status, WO number
2. Servicemax Event - Subject(WO + Account Name of WO),StartDate,End Date(All are mandatory)
Start date should be todays date and end date will be 4 hours later.
Write code useing web services.
