# Product Development reference

## Tools
1. https://gamma-technology.atlassian.net/jira/your-work 
2. Microsoft Teams
3. Github

## Jira process workflow for PM
1. PM creates backlog tickets
2. PM starts the sprint with backlog ticket after retrospective meeting with team
3. PM assigns the ticket to individual team member
4. Team presents demo at end of the sprint

## Jira Process workflow for Developer/Designer
1. Checks the assigned ticket and update status from Todo -> in progress
2. Updates the start date in the ticket and set story point
3. After task completion assigns the ticket for QA/review for peer review , in progress -> in review , change assign to reviewer
4. After peer review done -> closes the ticket.

## Git Process workflow
1. Dev/Designer creates new branch based on ticket number eg: `{type-of-request}/{ticket-number}:{ticket-description}` assigned in Jira, eg: `Feat/HKR-2:api-implementation`
2. After task is done , creates PR and assign team memeber for peer review
3. After review, squash and merge will be triggered

### Type of request
``` 
Feature - Feat
Fix - Fix
Work in progress - Wip
```

