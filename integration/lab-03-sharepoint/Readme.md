# LAB — Teams, SharePoint and OneDrive File Storage

<br>

## Objective

<br>

In this lab, you will learn how files are stored and shared across Microsoft Teams, SharePoint, and OneDrive.

<br>

You will learn how to:

<br>

* Upload files to a Teams channel.
* Identify where channel files are stored in SharePoint.
* Understand the relationship between Teams channels and SharePoint folders.
* Share files from OneDrive.
* Compare files stored in OneDrive and files stored in SharePoint.
* Identify the actual storage location of a file by examining its URL.
* Explore file version history.
* Understand how updates affect shared files.

<br>

---

<br>

## Scenario

<br>

Your team is collaborating on a project using Microsoft Teams.

<br>

The team needs to understand:

<br>

* Where Team files are stored.
* How Teams uses SharePoint for channel documents.
* How OneDrive differs from SharePoint storage.
* How version history works when files are updated after being shared.

<br>

---

<br>

# Part 1 — Explore the Team Structure

<br>

## Step 1 — Open Microsoft Teams

<br>

1. Open Microsoft Teams.
<br>
2. Sign in with your Microsoft 365 account if required.
<br>
3. Select **Teams** from the navigation menu.
<br>

---

<br>

## Step 2 — Open the Team

<br>

1. Locate the Team assigned by your instructor.
<br>
2. Expand the Team.
<br>
3. Review the available channels.
<br>

For example:

<br>

```text
General
Marketing
Finance
```

<br>

---

<br>

## Step 3 — Open the Shared Files Area

<br>

1. Select the **General** channel.
<br>
2. Open the **Shared** or **Files** tab.
<br>
3. Review the existing files.
<br>

---

<br>

## Step 4 — Upload a File From Your Computer

<br>

1. Select **Upload**.
<br>
2. Select **Files**.
<br>
3. Choose a file from your local computer.
<br>
4. Upload the file.
<br>
5. Wait for the upload to complete.
<br>

Record the file name.

<br>

---

<br>

## Step 5 — Open the SharePoint Location

<br>

1. Remain in the channel.
<br>
2. Open the **Shared** or **Files** tab.
<br>
3. Select **Open in SharePoint**.
<br>

A SharePoint site will open.

<br>

---

<br>

## Step 6 — Locate the Uploaded File

<br>

1. Open the **Documents** library.
<br>
2. Locate the **General** folder.
<br>
3. Open the folder.
<br>
4. Find the file that you uploaded from Teams.
<br>

Observe that the uploaded file exists in:

<br>

```text
Documents
└── General
```

<br>

---

<br>

## Step 7 — Understand the Structure

<br>

Observe the relationship between Teams and SharePoint.

<br>

Example:

<br>

```text
Team
├── General
├── Marketing
└── Finance
```

<br>

SharePoint:

<br>

```text
Documents
├── General
├── Marketing
└── Finance
```

<br>

Standard Teams channels are typically represented as folders inside the SharePoint Documents library.

<br>

---

<br>

## Verification 1

<br>

Answer the following questions:

<br>

* Which channel did you upload the file to?
* Which SharePoint folder contains the file?
* Do the channel name and folder name match?
* Is the file visible in both Teams and SharePoint?

<br>

---

<br>

# Part 2 — Create and Share a File from OneDrive

<br>

## Step 8 — Open OneDrive

<br>

1. Open OneDrive.
<br>
2. Select **New**.
<br>
3. Create a new Word document.
<br>

Name the document:

<br>

```text
Lab Version Test.docx
```

<br>

---

<br>

## Step 9 — Add Initial Content

<br>

Add the following text:

<br>

```text
Version 1
Created during the lab.
```

<br>

Save the document.

<br>

---

<br>

## Step 10 — Share the File in Teams

<br>

1. Return to Microsoft Teams.
<br>
2. Open the **General** channel.
<br>
3. Select **Posts**.
<br>
4. Create a new post.
<br>
5. Attach the file from **OneDrive**.
<br>
6. Publish the post.
<br>

---

<br>

## Step 11 — Identify the File Location

<br>

1. Open the file from the post.
<br>
2. Open the file location.
<br>
3. Examine the URL.
<br>

Example:

<br>

```text
https://tenant-my.sharepoint.com/...
```

<br>

Observe that the URL contains:

<br>

```text
-my.sharepoint.com
```

<br>

This indicates that the file is stored in OneDrive.

<br>

---

<br>

## Verification 2

<br>

Answer the following questions:

<br>

* Was the file uploaded from OneDrive or from your local computer?
* Is the file stored in OneDrive?
* Is the file stored in the Team's SharePoint Documents library?
* What evidence supports your answer?

<br>

---

<br>

# Part 3 — Update the Shared File

<br>

## Step 12 — Modify the Document

<br>

Reopen the Word document.

<br>

Add:

<br>

```text
Version 2
Added after sharing.
```

<br>

Save the document.

<br>

---

<br>

## Step 13 — Reopen the Link from Teams

<br>

1. Return to the channel post.
<br>
2. Open the same document again using the original link.
<br>

Observe the content.

<br>

You should now see:

<br>

```text
Version 1
Created during the lab.

Version 2
Added after sharing.
```

<br>

---

<br>

## Verification 3

<br>

Answer the following questions:

<br>

* Did the Teams message automatically update to the latest version?
* Does the original link open the current file?
* Is a separate copy created when the file is modified?

<br>

---

<br>

# Part 4 — Explore Version History

<br>

## Step 14 — Open Version History

<br>

1. Return to OneDrive.
<br>
2. Locate the document.
<br>
3. Select the ellipsis (**...**).
<br>
4. Select **Version History**.
<br>

Review the available versions.

<br>

---

<br>

## Step 15 — Review Earlier Versions

<br>

Open the oldest available version.

<br>

Review the content.

<br>

You should find an earlier version that contains:

<br>

```text
Version 1
Created during the lab.
```

<br>

Review the modification date and time associated with the version.

<br>

---

<br>

## Step 16 — Compare Versions

<br>

Compare Version 1 and Version 2.

<br>

Observe:

<br>

* Version number.
* Date and time.
* Content changes.

<br>

---

<br>

## Verification 4

<br>

Answer the following questions:

<br>

* Does OneDrive maintain version history?
* Can you view previous versions of the file?
* Does the Teams message point to a specific version?
* Does the Teams message always open the latest version?

<br>

---

<br>

# Key Concepts

<br>

## Files Uploaded from a Local Computer

<br>

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

<br>

Result:

<br>

✅ File stored in the Team's SharePoint site.

<br>

---

<br>

## Files Shared from OneDrive

<br>

```text
OneDrive
    ↓
Shared Link
    ↓
Teams Post
```

<br>

Result:

<br>

✅ File remains in OneDrive.

<br>

✅ Teams stores a link to the file.

<br>

---

<br>

## Version History

<br>

```text
Version 1
      ↓
Shared in Teams
      ↓
Version 2
      ↓
Version 3
```

<br>

The Teams post points to the same file.

<br>

The link always opens the current version.

<br>

Previous versions can be viewed through Version History.

<br>

---

<br>

# Lab Completed

<br>

You have successfully:

<br>

* Explored the relationship between Teams and SharePoint.
* Uploaded a file from a local computer.
* Verified where Teams channel files are stored.
* Identified the relationship between Teams channels and SharePoint folders.
* Shared a document from OneDrive.
* Verified the storage location of a shared file.
* Modified a shared document after publishing it.
* Explored version history.
* Compared OneDrive storage and SharePoint storage.
* Verified how Teams references shared files.

<br>

**Teams, SharePoint, and OneDrive work together to provide file storage, collaboration, sharing, and version management across Microsoft 365.**
