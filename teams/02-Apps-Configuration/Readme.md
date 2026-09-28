# Microsoft Teams — Core Apps Configuration

## Overview

Microsoft Teams does not always display the same applications in the left navigation bar for every user.

The available and pinned applications can depend on the organization's Teams configuration and the user's assigned app setup policy.

This document describes how to configure a Teams environment so that the **Teams** application is available and can be pinned in the Teams navigation bar.

## Teams Admin Center

Open the Microsoft Teams Admin Center:

`https://admin.teams.microsoft.com`

### 1. Check the user's policies

Go to:

**Users → Manage users → Select the user → View policies**

Verify the **App setup policy** assigned to the user.

For the default configuration, the user should have:

**Global (Org-wide default)**

### 2. Check the App setup policy

Go to:

**Teams apps → App setup policies → Global (Org-wide default)**

The **App bar** section controls the applications pinned in the Teams navigation bar.

For example, a user may have applications such as:

* Chat
* Shifts
* Activity
* Copilot
* Developer portal

The **Teams** application may not be available to pin if it has not been enabled for the organization.

### 3. Enable the Teams application

Go to:

**Teams apps → Manage apps**

Open:

**Org-wide app settings**

Check the organization-wide availability of the **Teams** application and enable it if necessary.

After enabling the application, Microsoft Teams may take some time to propagate the configuration.

### 4. Return to the App setup policy

Once the configuration has propagated, return to:

**Teams apps → App setup policies → Global (Org-wide default)**

Open **Add pinned apps** and search for:

**Teams**

If available, add it to the **App bar** and place it in the desired position.

## Important

The Teams navigation bar is **not necessarily identical for every Microsoft 365 user**.

The applications visible to a user can vary depending on:

* Organization configuration
* App availability
* App setup policies
* User configuration
* Microsoft Teams client changes
* Available Microsoft 365 services and licenses

Therefore, screenshots or training videos showing the Teams interface should be treated as **UI references rather than an exact representation of what every participant will see**.

## Example

A Teams environment may initially show:

```text
Chat
Shifts
Activity
Copilot
Developer portal
Store
```

After enabling the **Teams** application at the organization level and allowing the configuration to propagate, **Teams** can become available for the App bar configuration.

## Training Consideration

For Microsoft Teams user training, it is useful to verify the organization's Teams configuration before the session.

This is particularly important when training materials are based on screenshots or Microsoft Adoption videos, because the navigation bar can differ between tenants and users.
