# EskwelaPH Updates

This repository distributes EskwelaPH desktop application updates through GitHub Releases.

## Release files

Published Windows releases contain the EskwelaPH NSIS installer, its blockmap, `latest.yml`, and version-specific release notes. Installed Windows Electron editions check this public feed without requiring a GitHub account or GitHub token.

No installer has been published yet. Initial Windows packaging and upgrade acceptance testing are still pending.

## Local data

Teacher accounts, license activation files, student records, school records, databases, backups, and private credentials do not belong in this repository or its release assets. EskwelaPH keeps school records locally on the teacher's computer.

## Updating

In a supported installed version, use **Tools → Check for Updates**. Downloading and restarting to install require the teacher's action. Release notes are included with each published version.

The private development project provides `npm run publish-update`; this distribution repository does not contain the application source or school data.
