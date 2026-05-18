---
layout: default
title: Chill Code Privacy Policy
---

# Chill Code Privacy Policy

Last updated: 2026-05-18

This policy describes the Chill Code Android app, which is focused on
remote IDE companion sessions.

## Data The App Processes

Chill Code may process remote connection links, IDE host or endpoint
information, project names and paths, source file content shown or edited
through a remote session, terminal input and output, run output, Git status and
diff metadata, AI chat prompts and responses when the connected IDE exposes AI
features, and remembered pairing identifiers or secrets stored on the device.

## Storage

Remembered remote pairing material is stored locally on the Android device and
protected with Android Keystore-backed encryption. App backups are disabled, so
pairing material, preferences, project paths, and other local app state are not
included in Android cloud backup or device transfer.

The current remote connection flow is designed to connect the mobile app to the
user's chosen IDE companion session. It does not require a developer-operated
backend for the app-to-IDE session.

## Sharing And Third Parties

Remote session data is exchanged with the IDE companion session selected by the
user. If the IDE session exposes AI features, AI prompts and responses may be
handled by the AI provider configured in that IDE. The mobile app does not
choose that AI provider directly.

Chill Code does not sell user information or share it for advertising,
marketing, analytics, or unrelated third-party use. Project and session data is
exchanged only to operate the user-started companion session with the selected
IDE, subject to the IDE-configured AI handling described above.

## Permissions

Chill Code uses Internet access to connect to the IDE companion session.

Chill Code may request notification permission so it can show active remote
session status, session controls, and long-running background work. Declining
notification permission does not block manual remote connection.

Chill Code uses foreground service and data sync capabilities to keep an active
remote session visible and controllable while background work is running.

## User Controls

Users can end a remote session from the app or the IDE, decline notification
permission, clear Android app data, or uninstall the app to remove local
remembered-pair data from the device.

## Contact

Chill Flex Productions  
chill.flex.productions@gmail.com
