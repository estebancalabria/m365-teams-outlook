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

## Part 2 — Explore a Team

* [BROWSER] https://teams.microsoft.com/
    * [LEFT NAVBAR] Teams
        * [TEAM] Select a Team

Review:

* Team name
* Available channels

Examples:

* General
* Marketing
* Finance

Observe:

* Teams are organized into channels.
* A Team can exist even when its Microsoft 365 Group is not easily discoverable from Outlook.
* Standard Teams are backed by Microsoft 365 Groups.

---

## Part 3 — Explore Channel Conversations

* [BROWSER] https://teams.microsoft.com/
    * [LEFT NAVBAR] Teams
        * [TEAM] Select a Team
            * [CHANNEL] General
                * [TAB] Posts

Review:

* Posts
* Replies
* Conversations

Observe:

* Teams provides communication through channel posts.
* Teams conversations are different from Outlook group experiences.

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

* Files are exposed directly inside Teams.
* Team members collaborate on the same files.

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
* Channel folders

Observe:

* Teams files are stored in SharePoint.
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

* Channels can have their own email addresses.
* A Channel email address is different from a Microsoft 365 Group email address.

---

## Part 7 — Understand the Relationships

Review the following concepts:

### Microsoft 365 Group

Contains:

* Outlook
* SharePoint
* Teams (optional)

Observe:

* Every Microsoft 365 Group has a SharePoint site.
* A Microsoft 365 Group may or may not have a Team.

### Standard Team

Includes:

* Microsoft 365 Group
* SharePoint Site

Observe:

* Every standard Team has a Microsoft 365 Group.
* Every standard Team has a SharePoint Site.

---

## Part 8 — Understand Visibility

Review the following scenario:

A user can see a Team.

The same user may not be able to easily discover:

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
* Outlook group experiences and Teams channel experiences are different.
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

### Communication Through Groups

* Group Email
* Outlook Group Experience

### Communication Through Teams

* Channel Email
* Teams Posts
