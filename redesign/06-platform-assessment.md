# Platform assessment: ChurchEdit, WordPress, Squarespace

Scope note: this is a decision aid, not a build plan. Prices and plan limits change, so every cost line below is a question to check, not a fact.

## What the church said it needs (from `research/source/`)

1. Church office can edit it without a developer.
2. Several people with different permissions.
3. ChurchSuite calendar and room bookings embed cleanly (they are iframes today). Giving may follow later.
4. Look good with real photos.
5. Survive a volunteer leaving. This already happened: the person who ported the last site has moved county.

## Examples you gave

Both https://www.melksham.church/ and https://stmplymouth.org.uk/ are on Squarespace (server header confirms). Both are church sites with a modern, photo-led look.

## Comparison

| Criterion | ChurchEdit (today) | WordPress | Squarespace |
|---|---|---|---|
| Office can edit | Yes | Yes, with a good block theme and a trimmed admin | Yes, visual editor, easiest of the three |
| Multi-user permissions | Costs more, restricted (your finding) | Built in: Administrator, Editor, Author, Contributor | Contributors exist. Check cost per user and role limits on the current plan |
| ChurchSuite embeds | Works | Works (iframe or embed plugin) | Works (code block, check plan includes it) |
| Design freedom, menus | Very restricted | Highest | High within templates |
| Maintenance | Provider does it | **You do it**: updates, backups, security, plugin conflicts | Provider does it |
| Key-person risk | Low | **Highest** unless two named maintainers | Low |
| Accessibility (WCAG 2.2 AA) | Unknown | Depends on theme and plugins you choose | Depends on template, mixed |
| Running cost | Rising with permissions | Hosting plus any paid theme or plugins, plus maintainer time | Subscription, rises with plan |
| Lock-in | Moderate | Lowest, you own the files | Moderate, export is limited |

## Recommendation

1. Do not choose yet. Choose after the structure in `03` is agreed, because the structure is what the platform must carry.
2. Decide on one question: **who will maintain the site in three years if you are not available?**
   - If two named people will own updates and backups: WordPress is a good fit, and the church keeps full control.
   - If not: Squarespace is safer, even though it offers less freedom.
3. If you go WordPress, keep it boring: a managed host with automatic updates and daily backups, one accessible block theme, fewer than ten plugins, ChurchSuite embedded rather than rebuilt, and a written hand-over note with logins held by the PCC.
4. Pilot before committing. Build only the home page and Plan Your Visit page in each, give the church office two real tasks (change this Sunday's time, add a photo), and compare. About one day each.
5. Move redirects with the platform. The old addresses in `03` must still work on day one.

## Questions to answer for the pilot

- Does the office editor find it easy? (Ask the administrator, Frankie Smith.)
- What does the cheapest plan with the permissions you need cost per year?
- Does the ChurchSuite calendar embed render well on a phone?
- Does a free accessibility check (axe or WAVE) pass on the pilot pages?

## Challenge

You plan to move to WordPress and you are technical, so the maintainer is likely you. Is the church comfortable with that dependency, and is there a second person who can take over?
