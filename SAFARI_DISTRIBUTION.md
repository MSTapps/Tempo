# Tempo Safari Distribution Notes

Apple supports Safari Web Extension distribution through App Store Connect's Safari Web Extension Packager and through Xcode-based packaging.

## Recommended Path

Use the Safari Web Extension Packager in App Store Connect.

Requirements:

- Apple Developer Program membership for MSTapps
- App Store Connect access
- Store metadata
- Privacy details
- Extension package
- App Store product page assets

## Local Testing

For full local Safari testing, use macOS with Safari. Xcode is still useful for deeper local development and debugging.

## Current Blocker

This Windows workspace cannot complete live Safari installation testing.

How to change that:

- Use App Store Connect's Safari Web Extension Packager for packaging, or
- Use a Mac with Safari and Xcode for local package conversion/testing.

Official Apple documentation:

- https://developer.apple.com/documentation/safariservices/packaging-and-distributing-safari-web-extensions-with-app-store-connect
- https://developer.apple.com/documentation/safariservices/distributing-your-safari-web-extension
