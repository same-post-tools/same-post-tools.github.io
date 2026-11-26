# Security

SAME Post Tools runs entirely in your web browser. Files you open are processed on your own device and are never uploaded. Each page carries a Content Security Policy that blocks outside connections and lets only the page's own scripts run.

## Use only the official address

The only official copy is **https://same-post-tools.github.io/**. Anyone can copy the pages and host a changed version elsewhere, and a changed copy could send data away. Do not open member files, rosters, or exports in a copy at any other address. The pages show a red warning band when they are opened from another web address, and hide themselves if another website shows them inside a frame. A copy you saved to your own computer and open from there is fine.

## How the pages protect what you open

- **No outside connections.** Each page's Content Security Policy blocks every connection except the events finder reading its own event list from this site.
- **Only the page's own scripts run.** The policy lists the sha256 fingerprint of each script in the page, so a script slipped into a page through a file or a link cannot run.
- **Files and exports are checked.** Files you open are checked before use; every export is checked for scripts, spreadsheet formulas, and contact details before it leaves.
- **Links go to https sites only**, and each event link shows the site it goes to.
- **The publishing account uses two-factor authentication.**

## Checking a copy

`SHA256SUMS.txt` lists the sha256 fingerprint of every published file. To check a page you downloaded, compare its fingerprint with the list for the same version:

- Mac or Linux: `shasum -a 256 index.html`
- Windows (PowerShell): `Get-FileHash index.html`
- Windows (Command Prompt): `certutil -hashfile index.html SHA256`

The list lives in this repository, so it confirms a copy matches what was published here; every change to this repository is public in its history.

## Reporting a problem

If you find a way for a page to send data off your device, run a script it should not, or accept a file or event listing that breaks it, please report it privately:

- On GitHub: the **Security** tab of this repository, then **Report a vulnerability**.
- By email: [same.post.tools@gmail.com](mailto:same.post.tools@gmail.com)

Please do not open a public issue for a security problem, and never post member names, email addresses, rosters, exports, or other personal information in an issue.

This is a volunteer project. Reports are read and answered promptly.

## What is in scope

The pages published at https://same-post-tools.github.io/ and the files in this repository. Third-party libraries inside the pages (listed in `THIRD-PARTY-NOTICES.md`) are checked against their published security advisories.
