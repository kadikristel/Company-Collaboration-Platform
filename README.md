Documentation of use cases

**Events module**

  **1. List of all events**
  
    Role: Every authenticated user
    
    Business logic
    1. The user must be able to see the list of all added events.
    2. Following information must be shown regarding every event:
      a. Event name
      b. Event start and end date
      c. Event type
      d. Manager email
    3. By default the events must be sorted by the start date (oldest at the top of the list).
    4. The user must be able to apply sorting by the Start date, End date, Event type and Office.
    5. The user must be able to search events by name (including partial match).
    6. The user must be able to filter events by the Type, Office and Start date.
    7. The user must be able to bookmark the event.
    8. The user must be able to see all bookmarked events.

  **2. Event details**
  
    Role: Every authenticated user
    
    Business logic
    1. The user can access the events details from the list of all events by clicking to the event name.
    2. Following data must be shown regarding every event:
      a. Name
      b. Description
      c. Start date
      d. End date
      e. Link
      f. Type
      g. Office
      h. Address
    3. The empty fields must not be shown in the details view to reduce the space.

  **Department module**

   **2. Department information**
    
    Role: Every authenticated user
    
    Business logic
    1. The user must be able to open and see the detailed information of any department.
    2. The following information can be seen regarding the department:
      a. Name
      b. Description
      c. Parent department/group - if this department is a sub-department.
      d. List of Key contacts - employees of the company.
         • The user must be able to go to the employee details view by clicking on it.
      e. Contact email
      f. Contact details
      g. Office
      h. Additional documents
      i. Links specific for this department
      j. Key dates - like meeting schedule, milestones, etc.
    3. The user must see only those fields that are not empty, to reduce the space.
    
