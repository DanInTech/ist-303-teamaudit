# Project ist-303-teamaudit

## Group Members: Daniel Perez

Part A:
### Come up with a concept for your application.
Bot that reviews workshop attendance list everyday and opens a waitlist if it detects that we are close to the limit of the regular registration

### Identify all the relevant project stakeholders.
Department Directors
SUpervisor
Graduate fellows
Workshop attendees

### Create an initial set of project requirements expressed as user stories. User stories must have estimates
of completion times.

Title: Create repository and evironment
Description: The software will need a repository and environment to live in
Time: 25 min

Title: Create web scraper
Description: The software will have to check the registration website for all the workshops listed in a text file inside the repository, for each workshop it should identify if the event is in the future, and if the event is almost full (max attendees -1 or 2)
Time: 2 hours

Title: Activate waitlist
Description: The software will activate a waitlist and deactivate in-person list when the conditions are met
- Wrokshop happens in the future
- registration is almos full
- Waitlist is not activated
Save changes
Time: 2 hours

Title: Create worker
Description: Creation of a worker or github action that executes the code everyday to verify the status of the waitlists. Dependind on the solutions this may need the implementation of a server
Time: 10 hours

Title: communicate if actions were taken
Description: Optionally, If any action was taken, the system could inform users ideally via email.
Title: 3 hours


