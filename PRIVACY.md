# FancyFences Privacy Policy

Effective date: 2026-07-18

FancyFences is a macOS desktop organization utility by VAIDLABS. This policy
describes the data behavior of the FancyFences app in the repository state used for
the `1.0.0` Mac App Store release candidate.

## Summary

FancyFences does not collect, sell, share, or track personal data. FancyFences does not
include advertising, analytics, account login, third-party tracking SDKs, or
custom telemetry.

## Data Stored Locally

FancyFences stores app data locally on the user's Mac so it can organize desktop
spaces and restore app state. Local app data can include:

- Fence names, positions, display settings, and layout profiles.
- Security-scoped bookmarks for folders the user explicitly selects.
- Cached file and folder metadata used to display user-selected folders.
- Rule settings, app preferences, and theme settings.
- StoreKit entitlement cache for the FancyFences Pro purchase state.

These records are stored in the app container on the user's Mac. FancyFences does
not transmit this local app data to VAIDLABS.

## User Files

FancyFences works with files and folders selected by the user. Managed fences move
dropped files into user-selected backing folders, while portal fences display
existing user-selected folders. When removing a fence, the user can leave its
backing folder in place or move its contents to default storage first. FancyFences
never deletes the user's files as part of removing a fence. Deleting an item from
inside FancyFences moves that item to the system Trash.

FancyFences uses Apple's App Sandbox and security-scoped bookmarks to access only
folders selected by the user or otherwise permitted by macOS.

## Purchases

FancyFences uses Apple StoreKit for the FancyFences Pro non-consumable In-App
Purchase. Purchase processing, receipts, refunds, and Apple account information
are handled by Apple. FancyFences stores only the local purchase entitlement state
needed to unlock paid features.

## Required-Reason APIs

FancyFences uses file timestamp APIs to display user-selected files and folders and
to support user-granted folder organization. The app privacy manifest declares
the required reasons used by the app.

## Contact

Support and privacy requests should use the public FancyFences support URL:

https://github.com/VaidLabs/DeskOrg-Docs/issues
