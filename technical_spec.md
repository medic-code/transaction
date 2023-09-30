# Technical Spec

## Solution Description 

See readme.md for one line description

## High level architecture 
Frontend: Vanilla JS web page 
1. Minimal interactivity
2. Easier to setup and deal with
3. Less bulky than React for such a small project

Backend/API:
TrueLayer API - third party dependancy to access personal bank account
1. No need for creating a custom API at present
2. Given API responses gives access to 90 days it may not be necessary to store the data in a database in minimal case
2.1 Will need to implement a solution that stores transactions securely - perhaps only locally rather than deploying

## Presentation Layer
### User stories

1. To show my income each month so that I can track incomings each month
2. To show my outgoings each month so that I can track outcomes each month
3. To show my outgoings in categories of spending so that I can see where money is being used over time
4. To update outgoings and incomings as they occur so that I can automate transaction gathering
5. I want to see the total balance each month so that I can track financial status

### Wireframes + prototypes
### Error Handling

## Business Logic 

## Data Models
Not applicable at present see High level architecture

## Test Plan
1. Stick to one or two e2e tests
2. May be too few components for integration tests
3. Unit tests for simple components given how simple the project is.
4. Minimal scenario matrix

## Deployment 
1. Locally hosted given sensitive nature of the data
2. Depending on future could do something more securely online or just allow others to setup locally instead.
