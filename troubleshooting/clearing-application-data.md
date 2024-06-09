---
description: >-
  How to reset your application data, and perform a 'factory reset'. Warning:
  this is a destructive action.
---

# Clearing Application Data

With Acorn, all your data lives on your device.&#x20;

There are a couple of reasons you may wish to delete your application data:&#x20;

1. You want to delete the identity and data associated with it
2. You don't have any important data, and you want to recover the application from a faulty state that it is in

If you want to 'factory reset' and delete all of your application data, **notably this includes the private key which represents your identity among your peers**, then you can easily do so.&#x20;

The  instructions differ slightly depending on your operating system.&#x20;

{% hint style="info" %}
Note: if you are an advanced user and are running multiple Acorn versions side-by-side, DO NOT follow these instructions as they will delete data for ALL Acorn versions.&#x20;
{% endhint %}

Depending on your operating system, all of your Acorn application data lives in one of these folders:

* `%APPDATA%\acorn` on Windows
* `$XDG_CONFIG_HOME/acorn` or `~/.config/acorn` on Linux
* `~/Library/Application Support/acorn` on macOS

{% hint style="info" %}
If you are on MacOS, it may be difficult to navigate to this folder from the Finder. If you are not comfortable with the command line, you can use the Finder application and then navigate to the application menu "Go -> Go to Folder..." and then `fill in` "`~/Library/Application Support/acorn" and press Enter.`&#x20;
{% endhint %}

{% hint style="danger" %}
To delete all your data, including your identity (keys): delete the application data folder from your system, by at least moving it to the trash.&#x20;
{% endhint %}

Having deleted your data, the next time you start the application you will be prompted to fill in details about your profile once again, with a fresh start.
