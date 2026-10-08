# Profile maintenance

## Content and assets

- Edit README.md; keep professional positioning separate from an official employment title.
- assets/banner.svg is a self-contained 1200 × 320 vector using the profile palette. Keep the main name prominent; the smaller specialties also appear as readable README text on mobile. assets/section-divider.svg is decorative.
- Keep project showcases in one column. Use GitHub Markdown, safe HTML, relative local paths, and descriptive image alt text. Do not add styles, scripts, embedded SVG markup, or fixed-width tables for project cards.
- The downloader description and screenshot come from its public README and Screenshots/DarkTheme.png on main. Review them when the application changes. Its screenshot remains remote to keep this repository lightweight.
- Private case studies contain only owner-provided functional summaries. Add no internal URLs, architecture, identifiers, screenshots, or invented metrics. ERP module maturity varies.

## Credentials and contact

- Owner confirmed AZ-104, AZ-800, AZ-801, and MS-102 passed. Azure Administrator Associate is awarded and active; Windows Server Hybrid Administrator Associate is awarded, with renewal status unspecified.
- Keep MS-102 under passed exams until the qualifying prerequisite and Expert award are confirmed. Exam codes are not credentials.
- Microsoft now displays Windows Server Administrator Associate / AZ-802 on the current pathway page. Preserve the historical Windows Server Hybrid credential title as awarded; do not retroactively rename it without the owner's record.
- Microsoft 365 Administrator Expert and MS-102 are currently scheduled to retire November 30, 2026. Recheck Microsoft Learn before changing certification text.
- LinkedIn, portfolio, and email have source-only TODO placeholders. No additional links were verified from the public GitHub profile; publish email only with owner confirmation.

## Statistics and links

- Cards use [GitHub Profile Summary Cards](https://github.com/vn7n24fzkq/github-profile-summary-cards), github_dark, custom navy/cyan colors, and animation=none. Public API calls contain only the username; no private token or private-repository configuration is present.
- Cards can be cached, incomplete, or unavailable. Keep direct GitHub activity and repository fallback links. Do not copy numerical statistics into prose.
- The language card is collapsed because the public sample is small; it measures repository language distribution rather than career expertise. No contribution streak is included.
- Shields.io badges use a consistent flat-square style with text only, avoiding unsupported logo identifiers. Encode spaces, C#, ampersands, and hyphens correctly.

## Review and publish

1. Check git diff --check, parse both SVG files as XML, and verify all relative images exist.
2. Check external links return appropriate content, including SVG responses for badges/cards. An HTTP 200 alone does not guarantee useful data.
3. Render with GitHub-flavored Markdown; inspect desktop and mobile in light and dark backgrounds. Native GitHub typography can differ from a local preview.
4. Review wording, certification status, and privacy; stage only the four profile files.
5. Push the feature branch only after explicit approval, then open a pull request to main.

Certification reference pages: [Azure](https://learn.microsoft.com/en-us/credentials/certifications/azure-administrator/), [Windows Server current pathway](https://learn.microsoft.com/en-us/credentials/certifications/windows-server-hybrid-administrator/), [Microsoft 365](https://learn.microsoft.com/en-us/credentials/certifications/m365-administrator-expert/).

## Implementation validation (October 8, 2026)

- GitHub Markdown API accepted and rendered the README. Both local SVGs parsed as XML; all local image paths exist. git diff --check passed.
- Public repository/profile links, the real screenshot, all 17 Shields.io badges, and all three summary card endpoints returned HTTP 200. Badge/card responses were SVG; screenshot response was PNG. Cards were checked for common service error messages.
- Banner white and muted text contrast against the lighter navy endpoint is 16.14:1 and 6.58:1. Assets have self-contained backgrounds; README prose uses GitHub native theme colors.
- Single-column content and constrained image rendering were reviewed in source for mobile compatibility. Browser preview could not connect to the local preview server, so desktop/mobile and light/dark visual browser verification remains outstanding.
