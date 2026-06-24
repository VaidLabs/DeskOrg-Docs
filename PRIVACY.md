# DeskOrg Privacy Policy

Effective date: 2026-06-24

DeskOrg is a macOS desktop organization utility by VAIDLABS. This policy
describes the data behavior of the DeskOrg app in the repository state used for
the `1.0.0` Mac App Store release candidate.

## Summary

DeskOrg does not collect, sell, share, or track personal data. DeskOrg does not
include advertising, analytics, account login, third-party tracking SDKs, or
custom telemetry.

## Data Stored Locally

DeskOrg stores app data locally on the user's Mac so it can organize desktop
spaces and restore app state. Local app data can include:

- Fence names, positions, display settings, and layout profiles.
- Security-scoped bookmarks for folders the user explicitly selects.
- Cached file and folder metadata used to display user-selected folders.
- Rule settings, app preferences, and theme settings.
- StoreKit entitlement cache for the Unlimited Fences purchase state.

These records are stored in the app container on the user's Mac. DeskOrg does
not transmit this local app data to VAIDLABS.

## User Files

DeskOrg works with files and folders selected by the user. Managed fences move
dropped files into user-selected backing folders. Portal fences display existing
user-selected folders. Removing a fence record does not delete its backing
folder, and deleting a file inside DeskOrg moves the file to the system Trash.

DeskOrg uses Apple's App Sandbox and security-scoped bookmarks to access only
folders selected by the user or otherwise permitted by macOS.

## Purchases

DeskOrg uses Apple StoreKit for the Unlimited Fences non-consumable In-App
Purchase. Purchase processing, receipts, refunds, and Apple account information
are handled by Apple. DeskOrg stores only the local purchase entitlement state
needed to unlock paid features.

## Required-Reason APIs

DeskOrg uses file timestamp APIs to display user-selected files and folders and
to support user-granted folder organization. The app privacy manifest declares
the required reasons used by the app.

## Contact

Support and privacy requests should use the final public DeskOrg support URL:

https://github.com/VaidLabs/DeskOrg-Docs/issues
