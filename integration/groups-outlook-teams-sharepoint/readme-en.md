# Microsoft 365 Groups, Outlook, Teams and SharePoint

## Core Concept

The central element behind the integration between Outlook, Teams, and SharePoint is the **Microsoft 365 Group**.

```text
Microsoft 365 Group
│
├─ Outlook
│   ├─ Group Mailbox
│   ├─ Conversations
│   └─ Calendar
│
├─ SharePoint
│   └─ SharePoint Site
│
└─ Teams (optional)
    ├─ Team
    └─ Channels
```

Most of the integration between Outlook, Teams, and SharePoint exists because all three platforms use the same Microsoft 365 Group.

---

# Microsoft 365 Groups

A Microsoft 365 Group can exist with:

- Outlook
- SharePoint
- Team (optional)

Therefore:

```text
Microsoft 365 Group
├─ Outlook
├─ SharePoint
└─ (No Team)
```

is a valid configuration.

This is also valid:

```text
Microsoft 365 Group
├─ Outlook
├─ SharePoint
└─ Teams
```

---

# Relationship Between Teams and Microsoft 365 Groups

## Team → Microsoft 365 Group

A standard Microsoft Team has an associated Microsoft 365 Group.

```text
Team
│
├─ Microsoft 365 Group
├─ SharePoint
└─ Members
```

Therefore:

- Every standard Team has a Microsoft 365 Group.
- Every standard Team has a SharePoint site.
- Team members and Group members are shared.

## Microsoft 365 Group → Team

The reverse relationship is not mandatory.

A Microsoft 365 Group can exist without a Team.

```text
Microsoft 365 Group
├─ Outlook
├─ SharePoint
└─ (No Team)
```

---

# Relationship Between SharePoint and Microsoft 365 Groups

## When a Microsoft 365 Group Is Created

When a Microsoft 365 Group is created, the following resources are automatically provisioned:

```text
Microsoft 365 Group
├─ Outlook
└─ SharePoint Site
```

Therefore:

✅ Every Microsoft 365 Group has an associated SharePoint site.

---

## When a SharePoint Site Is Created

The relationship does not always work in reverse.

Some SharePoint sites are connected to a Microsoft 365 Group:

```text
SharePoint Site
├─ Microsoft 365 Group
└─ Team (optional)
```

However, independent SharePoint sites can also exist.

Therefore:

✅ Every Microsoft 365 Group has SharePoint.

❌ Not every SharePoint site has a Microsoft 365 Group.

---

# Public and Private Groups

A group can be:

```text
Public
```

or

```text
Private
```

regardless of whether it has a Team.

Examples:

```text
Public + Team
Public + No Team
Private + Team
Private + No Team
```

---

# Outlook Groups

In Outlook Web, users can typically see:

```text
Groups
```

This section usually contains the groups of which the user is a member.

Users may also see:

```text
Discover Groups
```

which displays discoverable groups within the organization.

---

# Joining a Group

If a group has an associated Team:

```text
Join Group
↓
Become a Group Member
↓
Become a Team Member
```

because membership is shared.

---

# Microsoft 365 Group Email Address

A Microsoft 365 Group can have an email address such as:

```text
sales@company.com
projectx@company.com
hr@company.com
```

When sending an email:

```text
user
  ↓
group@company.com
```

the message is delivered to the group mailbox.

It can be accessed through:

```text
Outlook
└─ Groups
    └─ Conversations
```

---

# Teams Channel Email Address

A Teams channel can have its own email address.

Example:

```text
general.xxxxx@amer.teams.ms
```

This is not the Microsoft 365 Group email address.

It is the channel-specific email address.

When sending an email to that address:

```text
user
  ↓
channel email
```

the content is published in the channel.

---

# Group Email vs Channel Email

## Group Email

```text
sales@company.com
```

Destination:

```text
Outlook
└─ Group
    └─ Conversations
```

---

## Channel Email

```text
general.xxxxx@amer.teams.ms
```

Destination:

```text
Teams
└─ Channel
    └─ Post
```

---

# Group Email vs Teams Post

Conceptually, both can be used to communicate with the same audience.

## Email

```text
Outlook
└─ Conversations
```

## Teams

```text
Teams
└─ General
```

However, they are different systems:

- Email lives in Outlook.
- Posts live in Teams.

They are not the same conversation.

---

# Group Visibility

Not all users can see all groups.

Typically:

```text
User
↓
Can see groups where they are a member
```

Users may also discover public groups or groups configured to allow join requests.

---

# Not Finding a Group in Outlook

It is not correct to assume:

```text
Group does not appear in Outlook
↓
Microsoft 365 Group does not exist
```

The only safe conclusion is:

```text
The group does not appear in my current Outlook experience
```

The group may still exist.

Possible reasons include:

- The user is not a member.
- Visibility restrictions.
- Tenant configuration.
- The group is hidden in Outlook.

---

# Mental Model

```text
Microsoft 365 Group
│
├─ Outlook
│   ├─ Mailbox
│   ├─ Conversations
│   └─ Calendar
│
├─ SharePoint
│   └─ Site and Documents
│
└─ Teams (optional)
    ├─ Team
    └─ Channels
```

Most Microsoft 365 collaboration services are connected through this object.

---

# Key Rules

```text
Every standard Team
    ↓
Has a Microsoft 365 Group

Every Microsoft 365 Group
    ↓
Has a SharePoint Site

Not every Microsoft 365 Group
    ↓
Has a Team

Not every SharePoint Site
    ↓
Has a Microsoft 365 Group
```
