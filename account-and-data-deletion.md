---
layout: default
title: Account and Data Deletion
permalink: /account-and-data-deletion/
nav_order: 6
---

_Last updated: September 21, 2026_

Pocket KGS does not operate a separate account system. It signs you in to an account hosted and controlled by the KGS Go Server.

## Delete data stored by the app

To remove Pocket KGS data from your Android device:

1. Open Android **Settings**.
2. Select **Apps**, then **Pocket KGS**.
3. Select **Storage & cache**.
4. Select **Clear storage** (wording varies by device), or uninstall Pocket KGS.

This removes Pocket KGS preferences, its locally stored KGS client identifier, and cached avatars from the device. Pocket KGS requests that Android not back up its app-private data.

If you saved a KGS password through Android Credential Manager, remove it separately using the password manager or credential provider you selected. Clearing Pocket KGS data does not necessarily remove that provider's copy.

Clearing local data or uninstalling does **not** delete your KGS account, messages, games, profile, or other information held by KGS.

## Delete a KGS account and server-side data

KGS's published [account-deletion instructions](https://www.gokgs.com/help/Accounts.html) state that a registered account is deleted automatically after six consecutive months without login, or after two years for a KGS Plus subscriber, and that this is the only available deletion method. KGS also states that games remain accessible in its archives after the account expires.

Because the Pocket KGS developer does not control the KGS servers, the developer cannot directly delete a KGS account or KGS-held data. Questions about KGS-held data should be directed to [admin@gokgs.com](mailto:admin@gokgs.com).

## Current limitation

Pocket KGS currently allows a guest user to begin KGS registration, but KGS does not expose an immediate deletion operation for the app to call. Pocket KGS therefore cannot immediately delete a KGS account or its associated server-side data.
