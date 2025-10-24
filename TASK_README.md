# [backend] Notifications service — EPIC-002

**Jira Key**: MAK-72
**Jira URL**: https://softserveinc-genailab-prometheus.atlassian.net/browse/MAK-72
**Epic**: No Epic
**Type**: Task
**Priority**: Medium

**Assignee**: Unassigned

## Description
Design and implement notifications service to deliver in-app notifications for relevant events (task created/edited/assigned/completed, comments, attachments). Provide event ingestion hooks from core services, queue processing, and delivery to real-time channel (websocket/SSE). Persist unread/read state.

## Acceptance Criteria
1. Given a supported event, When it occurs, Then a notification is created and delivered in-app in real-time
2. Given a user opens notifications, When an item is viewed, Then it is marked read and state persists

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