# [backend] Task filtering API — EPIC-001-007

**Jira Key**: MAK-69
**Jira URL**: https://softserveinc-genailab-prometheus.atlassian.net/browse/MAK-69
**Epic**: No Epic
**Type**: Task
**Priority**: Medium

**Assignee**: Unassigned

## Description
Implement list endpoint with query parameters to filter by status, assignee, and priority. Support multiple filters, pagination, and session persistence via query serialization.

## Acceptance Criteria
1. Given filter params, When I request the task list, Then only matching tasks are returned
2. Given no filters, When requested, Then the full list is returned with default sorting

## Implementation Checklist
- [ ] Review Jira ticket and requirements
- [ ] Implement functionality
- [ ] Add unit tests
- [ ] Add integration tests
- [ ] Update documentation
- [ ] Manual testing
- [ ] Code review ready

## Jira Status Tracking
- Current Jira Status: To Do
- Update Jira status as development progresses
- Move to 'In Review' when PR is ready
- Move to 'Done' when merged and deployed