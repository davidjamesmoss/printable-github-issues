# Create printable task cards from GitHub Issues

Printed task cards are nice to have when reviewing and organising tasks. Plus there is the satisfaction of being able to tear them in half when they’re done.

This is a simple single-page JS app which pulls all of your issues from the GitHub REST API and creates a big, scrolling print-friendly layout.

![Screenshot](https://raw.github.com/davidjamesmoss/printable-github-issues/main/screenshot.png)

- No server needed, runs from a local file.
- Requires a [Personal Access Token](https://github.com/settings/tokens?type=beta) with read-only access to issues.
- Each task is a single page and will chop off any content which does not fit.
- Page size is set to A4 – I suggest printing two-up and cutting in half.
- For US Letter, change the width and height in the CSS for `.issue`.
- This was a quick hack to help me triage a backlog. It is unlikely to be developed further, but please do fork it if you find it useful.
