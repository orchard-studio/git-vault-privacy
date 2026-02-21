# Privacy Policy

**Last updated: February 21, 2026**

## Overview

GitVault ("the App") is developed by Orchard Studio. This Privacy Policy explains how the App handles your information.

## Data Collection

GitVault does **not** collect, transmit, or share any personal data with the developer or third parties. The App operates entirely on your device with the following local data storage:

### Local Data Storage

- **Repository metadata**: Repository names, URLs, branch information, and file indexes are stored in a local SQLite database on your device.
- **File content cache**: Downloaded Markdown file contents are cached locally for offline reading.
- **GitHub access tokens**: If you configure a private repository, your GitHub personal access token is stored securely in the iOS Keychain.
- **App preferences**: Settings such as theme, font size, and default branch are stored in UserDefaults (SharedPreferences).

### Network Communication

The App communicates only with the GitHub API (`api.github.com`) to:
- Fetch repository file trees
- Download file contents
- Validate repository access

All network requests are made directly from your device to GitHub's servers. No data is routed through or stored on any intermediary server.

## No Tracking

- The App does **not** use any analytics or tracking services.
- The App does **not** contain any advertising.
- The App does **not** use cookies or tracking pixels.
- The App does **not** collect device identifiers.

## In-App Purchase

The App offers a one-time Pro upgrade. Purchase transactions are handled entirely by Apple's App Store. The App only stores a local flag indicating your purchase status.

## Data Deletion

All data stored by the App can be deleted by:
- Using the "Clear Cache" feature in Settings to remove downloaded repository data
- Deleting the App from your device, which removes all local data including Keychain entries

## Children's Privacy

The App does not knowingly collect information from children under 13.

## Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be posted on this page with an updated date.

## Contact

If you have questions about this Privacy Policy, please contact us at:
- Email: orchard.studio.dev@gmail.com
