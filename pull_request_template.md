## Summary:

Note: always start the pull requst in draft mode. Ensure that all checks (see below in the 'Checks' section) and that points in the 'Definition of Done' is completed.

Add a summary of the feature that will be integrated in the main branch. It should be ready for deployment to production.

Add a list of tasks completed if applicable and not obvious.

Add @mentions where applicable if mentioning other team members.

Links:

- Jira issue: {add url}
- Documentation: {add url}
- Deployment: { add url }

## Definition of Done

Work Items

- Jira issues are updated to correct status
- If using, hours are correctly adjusted in Jira

Documentation

- Architecture (Confluence) up to date
- Generic implementation (Confluence) up to date

Tests completed without open defects

- System integration testing (SIT) completed if PR covers user story
- Unit tests are passing
- Mock tests for integration adapters/components, where applicable

Deployment

- Applicable hand overs completed and accepted
- Feature is deployable and can be deployed with a CD pipeline
