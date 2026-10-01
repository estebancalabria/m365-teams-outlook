
# Microsoft 365 Collaboration Ecosystem and Service Integrations

This repository documents how the main Microsoft 365 collaboration services relate to one another and how they integrate.

## Objectives

- Understand the primary purpose of each service.
- Identify how the services differ.
- Understand how they integrate.
- Recognize where content is stored.
- Understand how Microsoft 365 Copilot uses information according to the user's permissions.

> **Key idea:** Microsoft 365 is not a set of isolated applications. Outlook, Teams, SharePoint, OneDrive, and Copilot form a connected ecosystem based on identity, permissions, membership, and storage.

---

## Collaboration ecosystem overview

### Microsoft 365 Groups

Provides shared membership and connected resources for other services. It is not an application, but a layer for organizing membership and access.

### Outlook

- Email.
- Calendars.

### Microsoft Teams

- Channels.
- Posts.
- Chats.
- Meetings.

### SharePoint

- Sites and pages.
- Shared libraries.

### OneDrive

- Personal files.
- Individual ownership.

### Microsoft 365 Copilot

Acts as an intelligence layer that works across information the user is already authorized to access.

---

## Microsoft 365 Groups

Microsoft 365 Groups is a shared membership and resource container, not a standalone application.

- One membership list can be reused by Outlook, Teams, SharePoint, and Planner.
- Every group includes a group mailbox, a shared calendar, and a SharePoint team site.
- Groups can be public or private.
- A group can exist without an associated Teams team.

**Key distinction:** the group is the membership and resource container; applications provide the experiences built on top of it.

**Access:** [Open Microsoft 365 Groups](https://outlook.cloud.microsoft/groups/home)

---

## Outlook

Outlook is the email and calendar experience for personal and group communication.

- The personal mailbox and personal calendar belong to the user.
- The group mailbox and group calendar belong to the Microsoft 365 Group.
- **My Groups** displays the groups the user has joined.
- **Discover Groups** displays public groups available to join.

**Key distinction:** personal resources belong to the user, while group resources belong to the Microsoft 365 Group.

**Access:** [Open Outlook](https://outlook.cloud.microsoft/)

---

## Microsoft Teams

Microsoft Teams is the workspace for conversations, meetings, and day-to-day collaboration.

- It brings together channels, posts, chats, and online meetings.
- Every standard team is backed by a Microsoft 365 Group.
- Channel files are stored in the connected SharePoint site.

**Key distinction:** Teams provides the interface for conversations and meetings; membership and shared files rely on Microsoft 365 Groups and SharePoint.

**Access:** [Open Microsoft Teams](https://teams.cloud.microsoft/)

---

## SharePoint

SharePoint is the platform that stores and publishes shared organizational content.

- It includes team sites, communication sites, document libraries, pages, and lists.
- Every Microsoft 365 Group has a connected SharePoint team site.
- Only group-connected sites inherit Microsoft 365 Group membership.

**Key distinction:** group-connected team sites and standalone sites are both SharePoint sites, but only group-connected sites inherit group membership.

**Access:** [Open SharePoint](https://www.microsoft365.com/launch/sharepoint)

---

## OneDrive

OneDrive is personal storage for an individual user's working files.

- Files are owned by the user and shared through explicit invitation.
- It is built on SharePoint technology, but it is not a shared team location.
- Content intended for the entire group should be stored in SharePoint.

> **OneDrive:** my files.  
> **SharePoint:** our files.

**Access:** [Open OneDrive](https://www.microsoft365.com/launch/onedrive)

---

## Microsoft 365 Copilot

Microsoft 365 Copilot works across information the user is already permitted to open.

### Authorized context Copilot can use

- Outlook.
- Teams.
- SharePoint.
- OneDrive.
- Calendars.
- Meetings.

### What Copilot does

- Summarizes, drafts, and compares authorized content.
- Works across information from several services in a single request.
- Identifies actions, decisions, and follow-ups.

### What Copilot does not do

- It does not grant access to information the user cannot open.
- It does not replace Outlook, Teams, SharePoint, or OneDrive.
- It does not create a separate copy of organizational content.

**Key distinction:** content location, organization, and permissions determine the context available to Copilot.

**Access:** [Open Microsoft 365 Copilot](https://m365.cloud.microsoft/chat)

---

## Other Microsoft 365 products

- **Microsoft Planner:** task management through plans, buckets, and assignments shared with Groups and Teams.
- **Microsoft Forms:** surveys, quizzes, and questionnaires shared through Teams, Outlook, and SharePoint.
- **Microsoft OneNote:** shared notebooks for collaborative notes in Teams and SharePoint.
- **Microsoft Loop:** collaborative workspaces with components that remain synchronized across Teams and Outlook.
- **Microsoft Stream:** video in Microsoft 365, stored in SharePoint or OneDrive depending on ownership.
- **Microsoft Viva Engage:** communities and organization-wide conversations that complement Outlook and Teams.

---

# Service integrations

## Microsoft 365 Groups and Outlook

- Microsoft 365 Groups provide a shared identity for a team or community.
- Each Microsoft 365 Group includes a group email address and a shared mailbox.
- Emails sent to the group address can be delivered to group members.
- Members can read and participate in group conversations from Outlook.
- Groups can be public or private.
- Public groups can be discovered by users in the organization.
- Users can join public groups.

## Microsoft 365 Groups and Calendar

- Each Microsoft 365 Group includes a shared calendar.
- Group members can view events in the group calendar.
- Group members can create and manage events in the group calendar.
- Group calendar events are visible to group members.
- Inviting a group to an event adds the event to the calendars of the group members.
- Group calendars help coordinate shared activities.

## Microsoft 365 Groups and Teams

- Each Teams team is associated with a Microsoft 365 Group.
- Team membership is based on Microsoft 365 Group membership.
- Adding a member to a team adds the user to the associated group.
- Removing a member from a team removes the user from the associated group.
- Team owners are also owners of the associated group.
- Microsoft 365 Groups provide the membership foundation for Teams.
- Changes to group membership are reflected in the team.

## Microsoft 365 Groups and SharePoint

- Each Microsoft 365 Group includes a SharePoint team site.
- Group members receive access to the associated SharePoint site.
- SharePoint site permissions are based on group membership.
- Adding or removing group members updates access to the site.
- Documents and content stored in the site are shared with group members.
- SharePoint provides the collaborative content workspace for the group.

## Outlook and Teams

- Outlook and Teams share the same Microsoft 365 calendar.
- Teams meetings can be scheduled from Outlook.
- Teams meetings created in Outlook appear in Teams.
- Meeting invitations and updates are delivered through Outlook.
- Users can join Teams meetings directly from Outlook.
- Outlook and Teams provide a unified meeting and scheduling experience.

## Outlook, SharePoint, and OneDrive

- Emails can include links to files stored in SharePoint and OneDrive.
- Users can share files from SharePoint and OneDrive directly from Outlook.
- Permissions can be managed when sharing links from Outlook.
- Recipients can collaborate on shared documents without exchanging email attachments.
- Updates are reflected automatically because the content remains in SharePoint or OneDrive.
- Outlook helps distribute and collaborate on content stored in Microsoft 365.

## Teams, SharePoint, and OneDrive

- Files shared in Teams channels are stored in SharePoint.
- Files shared in Teams chats are stored in OneDrive.
- Users can collaborate on documents directly from Teams.
- Changes become available to authorized users in real time.
- Teams provides an interface for accessing content stored in SharePoint and OneDrive.
- Permissions are managed through the underlying SharePoint and OneDrive storage.

## Copilot and the ecosystem

- Copilot works across the content and conversations the user is already allowed to open.
- In Outlook, it summarizes email threads and drafts replies from mailbox content.
- In Teams, it summarizes meetings and chat conversations.
- In SharePoint and OneDrive, it analyzes documents the user can access.
- Group membership and site permissions determine what content Copilot can use.
- Copilot adds an intelligence layer without creating new copies of the content.

---

# Integration summary matrix

| Services | Integration |
|---|---|
| Microsoft 365 Groups + Outlook | Group email and group mailbox |
| Microsoft 365 Groups + Teams | Shared membership |
| Microsoft 365 Groups + SharePoint | Connected team site |
| Microsoft 365 Groups + OneDrive | No direct relationship |
| Microsoft 365 Groups + Calendar | Shared group calendar |
| Outlook + Teams | Meetings and communication |
| Outlook + SharePoint | Document links |
| Outlook + OneDrive | Cloud attachments |
| Teams + SharePoint | Channel file storage |
| Teams + OneDrive | Chat file storage |
| SharePoint + OneDrive | Shared storage technology |

---

# Key rules to remember

## Structure

- Every standard Teams team has a Microsoft 365 Group.
- Every standard Teams team has one or more connected SharePoint sites.
- Every Microsoft 365 Group has a connected SharePoint team site.
- Not every Microsoft 365 Group has a Teams team.
- Not every SharePoint site has a Microsoft 365 Group.

## Storage

- OneDrive is primarily used for personal files.
- SharePoint is primarily used for shared organizational files.
- Teams chat files and Teams channel files use different storage models.
- Group email and channel email are different concepts.

## Calendars and Copilot

- The personal calendar and group calendar are different.
- Enabling a Teams meeting does not automatically invite all group members.
- Copilot only uses information the user is authorized to access.
- Other Microsoft 365 products extend the collaboration ecosystem.

---

# Mental model

1. **Microsoft 365 Groups** organizes shared membership and connected resources.
2. **Outlook** provides email and calendars.
3. **Teams** provides conversations, chats, and meetings.
4. **SharePoint** stores shared organizational content.
5. **OneDrive** stores personal working files.
6. **Copilot** uses available context according to existing permissions.

## Summary

- Groups organizes membership.
- Applications provide the experiences.
- SharePoint and OneDrive store the content.
- Copilot works across authorized context.
- Permissions determine what each user can open and what information Copilot can use.
