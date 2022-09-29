# React Coding Challenge

## Goal
To provide a Single-page application that allows user to get insights about there client and planning information.
  * The page shall have all the insights,data and filtering options provided.
  * The page shall manage 100k records efficently.

## Requirements:
  * The page shall show all the data that is provided in planning.json(=100K rows) in a table view
  * The page shall have provision to some kpi regarding the distrbution of data
    * Distribution of operating unit
    * Distribution of grade
    * Distribution of office city
    * Distribution of Labels
  * There page shall have filtering and sorting of the columns.

## Datamodel
```
ID : unique integer and required
Original ID : unique string and required
Talent ID: string and optional
Talent Name : string and optional
Talent Grade:  string and optional
Booking Grade: string and optional
Office City: string and optional
Office Postal Code:string and required
Job Manager Name: string and optional
Job Manager ID: string and optional
Total Hours: integer and required
Start Date: datetime and required
End Date: datetime and required
Client Name: string and optional
Client ID:unique string and required
Required Skills: list of dict and optional
Optional Skills: list of dict and optional
Excluded Skills: list of dict and optional
IS Core Team:boolean
Is Unassigned:boolean
```
## Tech stack
React and Node

for any additional quires on task please feel free to mail sundara.amancharla@aspaara.com
