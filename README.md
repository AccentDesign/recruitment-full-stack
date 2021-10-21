# Accent Design Web Developer Technical Test

Thanks for taking the time to to our full-stack coding test. The challenge has two parts:

1. a task to create a web application that queries an API and displays the information received.
2. some follow-up questions

----

Feel free to spend as much or as little time as you'd like, as long as the following have been met:

- Your implementation works as described in the task, retrieving results from our API, but can use an approach and language of your choice.

----

One of Accent's major clients manages property 'For Sale' boards for estate agents across the UK. For this test, we have made an API that you will use to get information about properties managed by a specified estate agent, including the address of each property, the type of board at the property and the board's current status. We'd like you to use the PropertiesByCustomer endpoint that is documented at http://boarderectors-api.accentstaging.co.uk/swagger.

As an example, http://boarderectors-api.accentstaging.co.uk/agents/ACC001/properties returns a list of properties managed by Accent Estate Agents, who have the customer code 'ACC001', including current board types and statuses.

## Task

- Displays the following information about each property managed by the customer, by querying our API:
  - Property Address
  - Erected Board Type
  - Total Fee Charged
- Apply a levy to the fee charged for certain properties
  - For properties which have an erected board type of "sold", a levy of 7.5% must be applied to the total fee charged before it is displayed
  - For those with "sale agreed", a 4% levy should be applied
- Shows "grand total" of the fees charged for the properties

## Design

It's up to you how you want to display the results. We are looking for an example of full stack web development so please keep this in mind when considering the front-end.

## Client Implementation

You can use any frontend libraries you feel comfortable with or just go native and keep it simple. 

## Submission Guidelines

- Please submit your program by sending a zip file to jobs@accentdesign.co.uk.
- The zip file should be named {yourname}.zip, and should itself contain the project folder with your submission with clear running instructions.
- The zip file should contain the FOLLOW-UP.md file with answers to the follow-up questions.
- The zip file should **not** include non production code e.g. `node_modules` folder etc.
- Please let us know when you've uploaded your solution.
