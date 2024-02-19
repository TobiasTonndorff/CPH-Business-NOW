we want to explore different possibilities of creating a "ticket-like" system like Service-Now for handeling tickets for different departments in a big
company. the system is going to include a web interface for the users to create tickets and a backend for storing and updating the states of current tickets and store user information for optimizing work flow.

## Features

- [ ] Users can create tickets
- [ ] Employees can handle tickets
- [ ] Users can see the status of their tickets
- [ ] Employees can see the status of all tickets for their department
- [ ] Admins can see the status of all tickets for all departments
- [ ] Admins can create new departments
- [ ] Admins can create new employees
- [ ] Admins can create new users
- [ ] Admins can assign employees to departments
- [ ] Users within a given department can assign tickets to employees within that department
- [ ] Users can change the assigned department of a ticket


## what entities are we going to have?

- [ ] Users
- [ ] Employees
- [ ] Departments
- [ ] Tickets
- [ ] Dashboards


## whats can a ticket be?

-[ ] A ticket is a broader term for different types of requests, such as:
    - [ ] Incident
    - [ ] Service Request
    - [ ] Change Request
    - [ ] Problem
    - [ ] Access Request
    - [ ] Other

## what are the different statuses a ticket can have?

- [ ] Open
- [ ] In Progress
- [ ] On Hold
- [ ] Closed
- [ ] Reopened
- [ ] Cancelled
- [ ] Resolved
- [ ] Pending
- [ ] Pending User info
- [ ] Waiting for Customer
- [ ] Waiting for Third Party
- [ ] Waiting for Change
- [ ] Waiting for Problem
- [ ] Waiting for Access
- [ ] Waiting for Approval


## Tickets also have different priorities on a scale from 1 to 5:

- [ ] 1 - Critical
- [ ] 2 - High
- [ ] 3 - Medium
- [ ] 4 - Low
- [ ] 5 - Planning


## Each department has a catalog of service items that can be requested by the users: example a servicedesk:

- [ ] Standard PC support
        - [ ] New PC
        - [ ] PC repair
        - [ ] PC upgrade
        - [ ] PC reimage
        - [ ] PC software installation
        - [ ] PC software removal

- [ ] Network drive access
        - [ ] New network drive
        - [ ] Network drive access removal
        - [ ] Network drive access change


# Users within a given department can create tickets and then choose a service through the catalog of service items of their department.
# for better categorization.
