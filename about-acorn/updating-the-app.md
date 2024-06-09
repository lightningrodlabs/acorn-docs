---
description: Automated and manual flows for updating Acorn
---

# Updating the App

## **Manual Update Flow (v2.1.1-alpha and older)**

For v2.1.1-alpha version and older, the process of migrating your projects' data to a new version of the app needs to be done **manually**. In addition, you would have to invite members to your shared projects again.

To update the app to the new version while keeping your projects' data, you would need to do the following:

1. _Before_ you install a new version of the app, go to the Project View and click and [export the project](../projects/export-a-project.md) in JSON format. Do this for every project's data you wanting to keep.
2. Download and Install the latest version of the app release from [Acorn's GitHub repository](https://github.com/lightningrodlabs/acorn/releases):
   * **Intel MacOS:** `.darwin-x64.zip` file
   * **M1/M2 MacOS:** `.darwin-arm64.zip` file
   * **Windows:** `.exe` file
   * **Linux:** `.AppImage` file
3. Run the newly installed app.
4. Depending on the release, and whether it has had 'breaking changes', you may be required to re-create a new profile.
5. Import the data for each project by clicking on [**Import a Project**](../projects/import-a-project.md) button on the Dashboard page.
6. For the shared projects, [Invite Members](../projects/invite-members-to-a-project.md) again.

{% hint style="warning" %}
**Only one person per shared project** should take responsibility for migrating that project to the new version in manual update process. Other project members should be notified, and invited to the migrated project. Note the coordination this requires.
{% endhint %}

## Automated Update Flow (v3.0.0-alpha and newer)

From v3.0.0-alpha onward, whenever. any update is available for Acorn you will be notified within the app and prompted to update your version to the newest release.

### Updates and Shared Projects

**If you are the first team member updating your version and migrating the project**

In this new update experience you don't need to re-invite team members to your shared project again after updating your version. The members will be each notified that a new release is available and will be prompted to update their version in order to access the migrated shared project.

If you have updated your version on a shared project, you would not see the team members that have not updated their own versions yet.&#x20;

#### **If another team member has already updated and migrated the project**

If any team member in a shared project updates their version to the newest release, any other team member will be required and prompted to updated their own apps in order access that migrated shared project.

### Updates and Personal Projects

You are not required to update to the newest release in order to access any of your personal  projects on Acorn. However, it's always recommended to update to the latest version to benefit from improved experience.

### Update Flow on Different Operating Systems

#### Update Flow on MacOS

Update Flow on MacOS is fully automated, meaning that you don't need to download the new release file from GitHub Releases - the app takes care of that for you, and migrates the project automatically (if you're the first team member updating your version), or it will sync you into the shared project that's already migrated (if another team member updated their version first).&#x20;

#### Update Flow on Windows and Linux

Currently the update flow for Windows and Linux is semi-automated. It means that you will be automatically notified by the app when a new version is available. However you would need to download the file for the newest version manually following these steps:&#x20;

1. After clicking on Update Now button you will be directed to a page with the download link.
2. Close the Acorn app before downloading the newest release file.
3. Download and Install the latest version of the app release from [Acorn's GitHub repository](https://github.com/lightningrodlabs/acorn/releases) ( `.exe` file for Windows and `.AppImage` file for Linux). Replace the older version.
4. Now open the app and you will be automatically synced to your existing shared projects on Acorn.&#x20;

{% hint style="info" %}
We have the intention to make update flow for Windows more automated like what we have done for MacOS. Stay tuned.
{% endhint %}
