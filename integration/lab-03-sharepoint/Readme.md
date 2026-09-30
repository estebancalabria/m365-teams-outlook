# LAB 3 — Teams, SharePoint and OneDrive File Storage

## Objective

In this lab, you will learn how files are stored and shared across Microsoft Teams, SharePoint, and OneDrive.

You will learn how to:

* Upload files to a Teams channel.
* Identify where channel files are stored in SharePoint.
* Understand the relationship between Teams channels and SharePoint folders.
* Share files from OneDrive.
* Compare files stored in OneDrive and files stored in SharePoint.
* Identify the actual storage location of a file by examining its URL.
* Explore file version history.
* Understand how updates affect shared files.
* Compare attaching files from a local computer versus attaching files from OneDrive.

---

## Scenario

Your team is collaborating on a project using Microsoft Teams.

The team needs to understand:

* Where Team files are stored.
* How Teams uses SharePoint for channel documents.
* How OneDrive differs from SharePoint storage.
* How version history works when files are updated after being shared.
* How Teams behaves when files are attached in channel conversations and replies.

---

# Part 1 — Explore the Team Structure

## Step 1 — Open Microsoft Teams

1. Open Microsoft Teams.
2. Sign in with your Microsoft 365 account if required.
3. Select **Teams** from the navigation menu.

---

## Step 2 — Open the Team

1. Locate the Team assigned by your instructor.
2. Expand the Team.
3. Review the available channels.

Example:

```text
General
Marketing
Finance
```

---

## Step 3 — Open the Shared Files Area

1. Select the **General** channel.
2. Open the **Shared** or **Files** tab.
3. Review the existing files.

---

## Step 4 — Upload a File From Your Computer

1. Select **Upload**.
2. Select **Files**.
3. Choose a file from your local computer.
4. Upload the file.
5. Wait for the upload to complete.

Record the file name.

---

## Step 5 — Open the SharePoint Location

1. Remain in the channel.
2. Open the **Shared** or **Files** tab.
3. Select **Open in SharePoint**.

A SharePoint site will open.

---

## Step 6 — Locate the Uploaded File

1. Open the **Documents** library.
2. Locate the **General** folder.
3. Open the folder.
4. Find the file that you uploaded from Teams.

Observe that the uploaded file exists in:

```text
Documents
└── General
```

---

## Step 7 — Understand the Structure

Observe the relationship between Teams and SharePoint.

Teams:

```text
Team
├── General
├── Marketing
└── Finance
```

SharePoint:

```text
Documents
├── General
├── Marketing
└── Finance
```

Standard Teams channels are typically represented as folders inside the SharePoint Documents library.

---

## Verification 1

Answer the following questions:

* Which channel did you upload the file to?
* Which SharePoint folder contains the file?
* Do the channel name and folder name match?
* Is the file visible in both Teams and SharePoint?

---

# Part 2 — Create and Share a File from OneDrive

## Step 8 — Open OneDrive

1. Open OneDrive.
2. Select **New**.
3. Create a new Word document.

Name the document:

```text
Lab Version Test.docx
```

---

## Step 9 — Add Initial Content

Add the following text:

```text
Version 1
Created during the lab.
```

Save the document.

---

## Step 10 — Share the File in Teams

1. Return to Microsoft Teams.
2. Open the **General** channel.
3. Select **Posts**.
4. Create a new post.
5. Attach the file from **OneDrive**.
6. Publish the post.

---

## Step 11 — Identify the File Location

1. Open the file from the post.
2. Open the file location.
3. Examine the URL.

Example:

```text
https://tenant-my.sharepoint.com/...
```

Observe that the URL contains:

```text
-my.sharepoint.com
```

This indicates that the file is stored in OneDrive.

---

## Verification 2

Answer the following questions:

* Was the file uploaded from OneDrive or from your local computer?
* Is the file stored in OneDrive?
* Is the file stored in the Team's SharePoint Documents library?
* What evidence supports your answer?

---

# Part 3 — Update the Shared File

## Step 12 — Modify the Document

Reopen the Word document.

Add:

```text
Version 2
Added after sharing.
```

Save the document.

---

## Step 13 — Reopen the Link from Teams

1. Return to the channel post.
2. Open the same document again using the original link.

Observe the content.

You should now see:

```text
Version 1
Created during the lab.

Version 2
Added after sharing.
```

---

## Verification 3

Answer the following questions:

* Did the Teams message automatically display the latest version?
* Does the original link open the current file?
* Is a separate copy created when the file is modified?

---

# Part 4 — Explore Version History

## Step 14 — Open Version History

1. Return to OneDrive.
2. Locate the document.
3. Select the ellipsis (**...**).
4. Select **Version History**.

Review the available versions.

---

## Step 15 — Review Earlier Versions

Open the oldest available version.

Review the content.

You should find an earlier version that contains:

```text
Version 1
Created during the lab.
```

Review the modification date and time associated with the version.

---

## Step 16 — Compare Versions

Compare Version 1 and Version 2.

Observe:

* Version number.
* Date and time.
* Content changes.

---

## Verification 4

Answer the following questions:

* Does OneDrive maintain version history?
* Can you view previous versions of the file?
* Does the Teams message point to a specific version?
* Does the Teams message always open the latest version?

---

# Part 5 — Compare Local Files and OneDrive Files in a Channel Reply

## Step 17 — Create a Channel Conversation

1. Return to the **General** channel.
2. Create a new post.

Example:

```text
File Storage Test
```

3. Publish the post.

---

## Step 18 — Attach a File from Your Computer

1. Open the post.
2. Select **Reply**.
3. Attach a file from your local computer.
4. Send the reply.

---

## Step 19 — Verify Storage of the Local File

1. Open the attached file.
2. Open its location.
3. Notice where the file is stored.
4. Open the channel's **Shared** or **Files** tab.
5. Open **Open in SharePoint**.
6. Browse to:

```text
Documents
└── General
```

Locate the file.

Record the URL.

Example:

```text
https://tenant.sharepoint.com/sites/ProjectTeam/...
```

---

## Step 20 — Attach a File from OneDrive

1. Return to the same conversation.
2. Reply again.
3. Attach a file from **OneDrive**.
4. Send the reply.

---

## Step 21 — Verify Storage of the OneDrive File

1. Open the attached file.
2. Open the file location.
3. Examine the URL.

Example:

```text
https://tenant-my.sharepoint.com/...
```

Observe that the file remains in OneDrive.

---

## Step 22 — Compare the Two Attachments

Compare both files.

File attached from local computer:

```text
Computer
    ↓
Teams Channel
    ↓
SharePoint
    ↓
Documents/General
```

File attached from OneDrive:

```text
OneDrive
    ↓
Shared Link
    ↓
Teams Reply
```

Answer the following questions:

* Which file appears in Documents/General?
* Which file remains in OneDrive?
* Which URL contains `-my.sharepoint.com`?
* Which URL contains `/sites/`?
* Are both files visible inside the Teams conversation?
* Are both files stored in the same location?

---

# Key Concepts

## Files Uploaded from a Local Computer

```text
Teams
    ↓
Channel
    ↓
SharePoint Site
    ↓
Documents
    ↓
General
```

Result:

✅ File stored in the Team's SharePoint site.

---

## Files Shared from OneDrive

```text
OneDrive
    ↓
Shared Link
    ↓
Teams Post
```

Result:

✅ File remains in OneDrive.

✅ Teams stores a link to the file.

---

## Teams Channels and SharePoint

```text
Teams Channel
        ↓
SharePoint Folder
```

Example:

```text
General
    ↓
Documents/General
```

---

## Version History

```text
Version 1
      ↓
Shared in Teams
      ↓
Version 2
      ↓
Version 3
```

The Teams post points to the same file.

The link always opens the current version.

Previous versions can be viewed through Version History.

---

# Lab Completed

You have successfully:

* Explored the relationship between Teams and SharePoint.
* Uploaded a file from a local computer.
* Verified where Teams channel files are stored.
* Identified the relationship between Teams channels and SharePoint folders.
* Shared a document from OneDrive.
* Verified the storage location of a shared file.
* Modified a shared document after publishing it.
* Explored version history.
* Compared files attached from a local computer and from OneDrive.
* Verified how Teams references shared files.
* Identified storage locations using SharePoint and OneDrive URLs.

**Teams, SharePoint, and OneDrive work together to provide file storage, collaboration, sharing, and version management across Microsoft 365.**
