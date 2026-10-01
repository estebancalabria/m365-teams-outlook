# LAB — Understanding Microsoft 365 Groups, Outlook, Teams and SharePoint

## Objective

Understand how Microsoft 365 Groups connect Outlook, Teams and SharePoint.

---

## Part 1 — Explore Microsoft 365 Groups in Outlook

* [BROWSER] https://outlook.cloud.microsoft/
    * [LEFT NAVBAR] Groups

Review:

* My Groups
* Discover Groups

Observe:

* Groups you belong to.
* Groups available for discovery.
* Public Groups.
* Private Groups.
* Join options.
* Request to Join options.

Observe the difference between groups that you belong to and groups that are only discoverable.

---

## Part 2 — Explore Teams

* [BROWSER] https://teams.microsoft.com/
    * [LEFT NAVBAR] Teams
        * [TEAM] Select a Team

Review:

* Team name
* Channels

Examples:

* General
* Marketing
* Finance

Observe:

* Teams are organized into channels.
* Teams provide chat-based collaboration.
* A standard Team is backed by a Microsoft 365 Group.
* A Team may exist even when its Microsoft 365 Group is not easily discoverable from Outlook.

---

## Part 3 — Compare Outlook and Teams Communication

### Outlook

* [BROWSER] https://outlook.cloud.microsoft/
    * [LEFT NAVBAR] Groups

Review:

* Conversations

### Teams

* [BROWSER] https://teams.microsoft.com/
    * [LEFT NAVBAR] Teams
        * [TEAM] Select a Team
            * [CHANNEL] General
                * [TAB] Posts

Review:

* Channel conversations
* Replies
* Threads

Observe:

* Outlook uses Conversations.
* Teams uses Posts.
* Both provide communication capabilities.
* They are different communication experiences.

---

## Part 4 — Explore Team Files

* [BROWSER] https://teams.microsoft.com/
    * [LEFT NAVBAR] Teams
        * [TEAM] Select a Team
            * [CHANNEL] General
                * [TAB] Files

Review:

* Shared documents
* Shared files

Observe:

* Teams exposes documents directly inside the channel.
* Team files are shared with the team members.

---

## Part 5 — Open SharePoint

* [BROWSER] https://teams.microsoft.com/
    * [LEFT NAVBAR] Teams
        * [TEAM] Select a Team
            * [CHANNEL] General
                * [TAB] Files
                    * [BUTTON] Open in SharePoint

Review:

* SharePoint site
* Document library
* Folders
* Shared files

Observe:

* Teams channel files are stored in SharePoint.
* Teams uses SharePoint as its document repository.

---

## Part 6 — Explore Channel Email Addresses

* [BROWSER] https://teams.microsoft.com/
    * [LEFT NAVBAR] Teams
        * [TEAM] Select a Team
            * [CHANNEL] General
                * [MENU] ...
                    * [OPTION] Get email address

Review:

* Channel email address

Example:

* general.xxxxx@amer.teams.ms

Observe:

* Channels can have their own email address.
* A Channel email address is different from a Microsoft 365 Group email address.

---

## Part 7 — Understand the Relationships

Review the following concepts:

### Microsoft 365 Group

* Outlook
* SharePoint
* Teams (optional)

Observe:

* Every Microsoft 365 Group has SharePoint.
* A Microsoft 365 Group may or may not have Teams.

### Standard Team

* Microsoft 365 Group
* SharePoint Site

Observe:

* Every standard Team has a Microsoft 365 Group.
* Every standard Team has a SharePoint Site.
* Team membership is based on Microsoft 365 Group membership.

---

## Part 8 — Understand Visibility

Review the following scenario:

* A user can see a Team.

The same user may not be able to discover:

* The Microsoft 365 Group.
* The Group email address.
* The Group in Outlook.

Observe:

* Group visibility depends on membership.
* Group visibility depends on tenant configuration.
* Not finding a Group in Outlook does not automatically prove that the Group does not exist.

---

## Key Concepts Learned

* Microsoft 365 Groups connect Outlook, SharePoint and optionally Teams.
* Every Microsoft 365 Group has a SharePoint Site.
* Not every Microsoft 365 Group has a Team.
* Every standard Team has a Microsoft 365 Group.
* Every standard Team has a SharePoint Site.
* Not every SharePoint Site has a Microsoft 365 Group.
* Outlook displays both My Groups and Discover Groups.
* Discover Groups may contain Groups that the user is not a member of.
* Team membership is based on Microsoft 365 Group membership.
* Teams channel files are stored in SharePoint.
* Teams uses SharePoint as its document repository.
* Outlook Conversations and Teams Posts are different communication experiences.
* Group Email and Channel Email are different concepts.
* A Channel Email address can publish content into a Teams channel.
* A Team may exist even when its Microsoft 365 Group is not easily discoverable from Outlook.
* Not finding a Group in Outlook does not prove that the Group does not exist.

---

## Architecture Summary

### Microsoft 365 Group

* Outlook
* SharePoint
* Teams (optional)

### Standard Team

* Microsoft 365 Group
* SharePoint Site

### Group Communication

* Group Email
* Outlook Conversations

### Team Communication

* Channel Email
* Teams Posts
