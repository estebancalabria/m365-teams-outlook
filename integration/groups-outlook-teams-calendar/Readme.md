# Microsoft 365 Groups, Outlook, Teams and Group Calendars

## Overview

Microsoft 365 Groups are the foundation behind collaboration services in Microsoft 365.

A Microsoft 365 Group can provide:

* Outlook integration
* Group email
* Group calendar
* SharePoint site
* Teams integration (optional)

A standard Microsoft Team is backed by a Microsoft 365 Group and a SharePoint site.

---

## Understanding the Group Calendar

Each Microsoft 365 Group includes its own shared calendar.

Characteristics:

* Shared by all group members.
* Accessible to group members.
* Can contain events and meetings.
* Can be used for Teams Meetings.
* Is separate from each user's personal calendar.

---

## Group Calendar vs Personal Calendar

### Group Calendar

* Belongs to the Microsoft 365 Group.
* Shared across group members.
* Used for group activities and planning.
* Can contain events and meetings.

### Personal Calendar

* Belongs to an individual user.
* Contains the user's meetings and appointments.
* Receives meeting invitations addressed to that user.

These are different calendars.

---

## Creating an Event in the Group Calendar

When creating an event directly in the Group Calendar:

* The event is stored in the Group Calendar.
* Members can see the event from the Group Calendar.
* Invitations are not automatically sent to all members.

---

## Creating a Teams Meeting in the Group Calendar

Scenario:

* Open the Group Calendar.
* Create a new event.
* Enable **Teams Meeting**.

Result:

* A Teams meeting link is created.
* The event remains in the Group Calendar.
* Members are not automatically invited simply because Teams Meeting is enabled.

Important:

* Teams Meeting creates an online meeting link.
* Teams Meeting does not automatically distribute invitations to every group member.

---

## Inviting the Entire Group

When creating the event, you can add the Microsoft 365 Group as a Required Attendee.

Scenario:

* Create an event in the Group Calendar.
* Enable Teams Meeting.
* Add the Microsoft 365 Group as a Required Attendee.

Result:

* The meeting is associated with the Group.
* Invitations are generated for the Group.
* This is different from creating an event without attendees.

---

## Scenario A — Event Only

Create:

* Event in Group Calendar.
* Teams Meeting enabled.
* No attendees added.

Result:

* Event exists only in the Group Calendar.
* Teams link is created.
* No automatic invitation is sent to all members.

---

## Scenario B — Event with Group Invitation

Create:

* Event in Group Calendar.
* Teams Meeting enabled.
* Microsoft 365 Group added as Required Attendee.

Result:

* Teams link is created.
* The Group is invited.
* Invitations are distributed through the Group.

---

## Relationship Between Outlook, Teams and Group Calendars

### Microsoft 365 Group

Contains:

* Outlook
    * Group Email
    * Group Calendar
* SharePoint
    * Documents
* Teams (optional)
    * Team
    * Channels
    * Posts

---

### Standard Team

Contains:

* Microsoft 365 Group
* SharePoint Site

Characteristics:

* Every Standard Team has a Microsoft 365 Group.
* Every Standard Team has a SharePoint Site.
* Team membership is based on Group membership.

---

## Communication Models

### Outlook Communication

* Group Email
* Group Calendar
* Group Events

### Teams Communication

* Teams Channels
* Posts
* Channel Email Address
* Teams Meetings

---

## Channel Email vs Group Email

### Group Email

Examples:

* sales@company.com
* hr@company.com
* projectx@company.com

Purpose:

* Communicate with the Microsoft 365 Group.

---

### Channel Email

Examples:

* general.xxxxx@amer.teams.ms

Purpose:

* Publish content directly into a Teams Channel.

---

## Visibility Considerations

A user may:

* See a Team.

The same user may not necessarily be able to discover:

* The Microsoft 365 Group.
* The Group email address.
* The Group in Outlook.

Visibility depends on:

* Membership.
* Group configuration.
* Tenant configuration.

Important:

* Not finding a Group in Outlook does not prove that the Group does not exist.

---

## Key Concepts

* Microsoft 365 Groups connect Outlook, SharePoint and optionally Teams.
* Every Microsoft 365 Group includes a Group Calendar.
* Every Microsoft 365 Group has a SharePoint Site.
* Not every Microsoft 365 Group has a Team.
* Every Standard Team has a Microsoft 365 Group.
* Every Standard Team has a SharePoint Site.
* Team membership is based on Microsoft 365 Group membership.
* Group Calendars are different from Personal Calendars.
* Creating a Teams Meeting does not automatically invite every Group member.
* A Teams Meeting only creates an online meeting link.
* Group members are not automatically invited unless the Group is invited.
* Group Email and Channel Email are different concepts.
* Outlook Group experiences and Teams Channel experiences are different.
* Teams files are stored in SharePoint.
* Teams uses SharePoint as its document repository.
* A Team may exist even when its Microsoft 365 Group is not easily discoverable from Outlook.

---

## Architecture Summary

### Microsoft 365 Group

* Outlook
    * Group Email
    * Group Calendar
* SharePoint
    * Document Storage
* Teams (optional)

### Standard Team

* Microsoft 365 Group
* SharePoint Site

### Event Created in Group Calendar

* Stored in Group Calendar
* Visible to Group members
* No automatic invitation

### Event Created in Group Calendar + Group Invited

* Stored in Group Calendar
* Teams meeting link available
* Invitation sent through the Group

### Teams Communication

* Teams Channel
* Posts
* Channel Email

### Outlook Communication

* Group Email
* Group Calendar
* Group Events
