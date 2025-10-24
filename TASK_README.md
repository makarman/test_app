# [backend] Comments API & realtime — EPIC-001-006

**Jira Key**: MAK-67
**Jira URL**: https://softserveinc-genailab-prometheus.atlassian.net/browse/MAK-67
**Epic**: No Epic
**Type**: Task
**Priority**: Medium

**Assignee**: Unassigned

## Description
Implement endpoints to add/list comments on tasks with author and timestamp. Integrate real-time delivery (websocket or SSE) for new comments; notify subscribers.

## Acceptance Criteria
1. Given project members, When they post comments to a task, Then comments persist with author/timestamp and are delivered in real-time
2. Given a task, When comments are listed, Then ordering is chronological and paginated

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