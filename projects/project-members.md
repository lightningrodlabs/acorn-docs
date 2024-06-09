# Project Members

Project Members are displayed via their **avatars** throughout that Project. You are able to see a Project Member's name by hovering over their avatar. You can [Invite others to a Project](invite-members-to-a-project.md) to become a Member that Project.

{% hint style="warning" %}
Currently you **won't be able to remove any existing Members** from a Project you are a member of. Any other existing Project Members are also able to invite others to that Project.
{% endhint %}

### Project Member Status

There are three types of Status for a Project Member:&#x20;

#### Self Assigned Status

Displayed as colored dots on the corner of Project Member avatars. Any Project Member can assign themselves a Status to appear wither **Online** (green), **Away** (yellow), or **Offline** (grey) to the other Project Members.&#x20;

The default self-assigned Status is Online (green). To change your Self-Assigned Status at any time, click on your avatar on top right corner of the screen and select **Change Status** option from the menu to see the Status option and click the one you want.

![Changing your Self-Assigned Status](<../.gitbook/assets/Screen Shot 2022-07-05 at 6.04.10 PM.png>)

#### Connectivity Status

A Project Member is either **Connected** or **Disconnected** from the Project at any given moment. This connectivity Status depends on whether the Project Member has the app open and active (with connected Websocket), and that if they are connected to the Internet.&#x20;

The Connectivity Status is automatically detected by the app. If a Project Member is Disconnected, their avatar will display at a lower opacity level.

#### Public Key Association Status (Ghost Members)

At the moment when you migrate your Project data to [a newer version of the app](../about-acorn/updating-the-app.md) (which currently needs to be done manually), the Project Members previously assigned to any Outcomes of that project will be **Ghosted**. That means **their metadata is dissociated from their Public Key** which identifies them as a real person.&#x20;

A Ghost Project Member avatar is displayed as at a lower opacity with hatch pattern on the Outcomes they where assigned to.

Ghost members are now claimable after updating the app to a new version. The app will automatically associate your Public Key with your ghost member profile upon launching the new version of the app.

{% hint style="info" %}
You can remove any unclaimed Ghost Members that are on the [Assignees Lists](../outcomes/assignees.md) of an Outcome. However you won't be able to add a Ghost Member back as an Assignee.
{% endhint %}

{% hint style="info" %}
In the future there will be a more automated app updating process which will prevent the users from having to migrate their project data manually and having to inviting back each member to that project. This automation will also prevent most of the cases that cause the Ghosted Member situation.
{% endhint %}
