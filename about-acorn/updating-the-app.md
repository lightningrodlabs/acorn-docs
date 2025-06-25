---
description: Automated and manual flows for updating Acorn
---

# Updating the App

## Automatic Updates

The Acorn app will automatically update if the Holochain versions remain compatible, which should be indicated by the minor release number remaining the same.

## Manual Updates

When a new Minor or Major release comes out, you will currently have to manually migrate project data from an older version.  

To update the app to the new version while keeping your projects' data, you would need to do the following:

1. _Before_ you install a new version of the app, go to the Project View and click and [export the project](../projects/export-a-project.md) in JSON format. Do this for every project's data you wanting to keep.
2. Download and Install the latest version of the app for your device from [the Acorn website](https://acorn.software/#download)
3. Run the newly installed app.
4. Depending on the release, and whether it has had 'breaking changes', you may be required to re-create a new profile.
5. Import the data for each project by clicking on [**Import a Project**](../projects/import-a-project.md) button on the Dashboard page.
6. For the shared projects, [Invite Members](../projects/invite-members-to-a-project.md) again.

{% hint style="warning" %}
**Only one person per shared project** should take responsibility for migrating that project to the new version in manual update process. Other project members should be notified, and invited to the migrated project. Note the coordination this requires.
{% endhint %}

## Updates and Personal Projects

You do not have to update to the newest release in order to access any of your personal  projects on Acorn. However, it's always recommended to update to the latest version to benefit from improved experience.
