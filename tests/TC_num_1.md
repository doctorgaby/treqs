# Manual test cases 

## TestCases

A list of manual test cases of user stories and their requirements

Note1: "userstory=USnum1" refers to the ID of the user story. "requirement req=REQnum1" refers to the ID of the system requirement, traced by the user story. "testcase id=TCnum1" refers to the ID of the test case.
Note2: You can change the ID for the test cases, e.g. "id=TCnum1" can be "id=TC1", "id=TCtemp" etc. Taking into account that you keep "TC" in the beginning of the ID.

## [testcase id=TC_Show_Tickets userstory=US_Show_Tickets requirement req=REQ_See_Tickects]

Purpose: Check if a list of all tickets available for specific dates is shown when a user searches for tickets

### Setup

User should be log in 

### Scenario / Steps

1. Login to the system
2. Search for tickets from Gothenburg to Dar es Salaam
3. Add dates (3rd July - 2nd August 2019)


### Expected outcome

A list of all available flights from Gothenburg to Dar es salaam on 3rd July to 2nd August 2019

### Tear down

Verify the list of flights

## [testcase id=TC_Filter_Tickets requirement  req=REQ_Filter_Tickets story=US_Filter_Tickets]

Purpose: Check if the system can filter tickets based on price

### Setup

User should be log in 
Search for a flight for specific cities on specific dates

### Scenario / Steps

1. Login to the system
2. Search for tickets from Gothenburg to Dar es Salaam
3. Add dates (3rd July - 2nd August 2019)
4.Click filter, select filter by price


### Expected outcome

A list of all available flights from Gothenburg to Dar es salaam on 3rd July to 2nd August 2019 filtered according to price

### Tear down

Verify the list of flights are sorted by price

