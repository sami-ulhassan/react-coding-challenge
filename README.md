# React Coding Challenge

## Goal

The goal is to create a simple single-page application that allows a user to get
insights into client and planning information.

* The page shall have all the insights, data and filtering options provided.
* The page shall manage 10k records efficently.

## Requirements

Within the application, it should be possible to

* browse all the data that is provided in `planning.json` in a detailed view
  (for example table view).
* get an overview of the data with some statistics, for at least the
  following attributes:
  * booking grade
  * office city
  * skills
  * industry
* drill down into subsets by means of filtering and sorting.

## Data Model

* ID: integer (unique, required)
* Original ID: string (unique, required)
* Talent ID: string (optional)
* Talent Name: string (optional)
* Talent Grade: string (optional)
* Booking Grade: string (optional)
* Operating Unit: string (required)
* Office City: string (optional)
* Office Postal Code: string (required)
* Job Manager Name: string (optional)
* Job Manager ID: string (optional)
* Total Hours: float (required)
* Start Date: datetime (required)
* End Date: datetime (required)
* Client Name: string (optional)
* Client ID: string (required)
* Industry: string (optional)
* Required Skills: array of key-value pair (optional)
* Optional Skills: array of key-value pair (optional)
* Is Unassigned: boolean

## Tech Stack

* JavaScript or TypeScript
* React
* Node (if required)

## Submission

* Please fork the project, commit and push your implementation and add
  `sundara.amancharla@aspaara.com` as a contributor.
* Please also update the README with any additional details or steps that are
  requried to run your implementation.

For any additional questions on the task please feel free to email
`sundara.amancharla@aspaara.com`.
