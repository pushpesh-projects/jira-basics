# jira-basics

## JIRA query to see open issues which are assigned to you and have a status other than "Done"

´´´
assignee = currentUser() AND status != Done
´´´

## JIRA query to see open issues which are created by you and have a status other than "Done"

´´´
reporter = currentUser() AND status != Done
´´´
