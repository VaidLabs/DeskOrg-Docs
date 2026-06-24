# DeskOrg Support

DeskOrg support is published in this public documentation repository:

https://github.com/VaidLabs/DeskOrg-Docs

For help with DeskOrg, TestFlight feedback, bug reports, or feature requests,
open an issue at:

https://github.com/VaidLabs/DeskOrg-Docs/issues

Before requesting help, include:

- DeskOrg version and build number.
- macOS version.
- Whether the issue happens with managed fences, portal fences, Settings, or
  purchase restore.
- Steps to reproduce the issue.
- Screenshots or screen recordings when useful, with private file names removed.

Common checks:

- If DeskOrg cannot access a folder, open Settings, select the affected fence,
  and reselect the folder so macOS can refresh folder permission.
- If a menu bar icon is missing, quit DeskOrg from Activity Monitor and launch
  the current build again from Finder or Xcode.
- If a file does not move as expected, confirm whether the fence is a managed
  fence or a portal fence. Managed fences use a DeskOrg-created backing folder.
  Portal fences show an existing folder chosen by the user.

Do not attach private files, personal documents, receipts, or App Store account
details to a public support request. For purchase problems, include the visible
DeskOrg purchase status text and whether Restore Purchases was attempted.
