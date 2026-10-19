# Platform assessment: WordPress or Squarespace

ChurchEdit is out (cost of multi-user permissions, restricted design). Decision here is WordPress against Squarespace. Research date 2026-10-19. Prices and plan limits change, so confirm on the vendor's own page before buying.

## What the church needs

1. Church office edits without a developer.
2. Several people with different permissions.
3. ChurchSuite calendar and room bookings embed cleanly (iframes today). Online giving may follow.
4. Photo-led, accessible (WCAG 2.2 AA), fast on phones.
5. Survives a volunteer leaving. The builder of the last site has moved county.

## Comparison

| Criterion | WordPress (self-hosted, open source) | Squarespace |
|---|---|---|
| Office editing | Good with a block theme and a trimmed admin menu | Easiest of the two |
| Multi-user permissions | Built in (Administrator, Editor, Author, Contributor), no per-user fee | Basic plan caps at two contributors including the owner. Core and above lift the cap (sources agree on the cap, confirm which plan lifts it) |
| ChurchSuite embeds | Works | Works through code blocks, confirm the plan includes it |
| Design freedom and menus | Highest, wide menus possible | Good within templates, no plugins or extensions |
| Free tools and community | Very large, many free plugins | Closed ecosystem |
| Maintenance | You own updates, backups, security | Included |
| Key-person risk | Highest unless two named maintainers | Low |
| Accessibility | "Accessibility-ready" theme tag exists, but it is a minimum check. Page builders (Elementor, Divi, Beaver Builder) often produce failing markup | No claim that every template meets WCAG, test each one |
| Running cost | Free hosting exists for registered UK charities (several providers). Paid care plans about £25 a month for updates, backups and security | Subscription, with a July 2026 price rise reported. Sources disagree on current figures |
| Lock-in | Lowest, you own the files | Moderate, limited export |

## Recommendation: WordPress, with conditions

Your preference holds up on contributor permissions, accessibility control, cost and ecosystem. The weakness is maintenance and who does it. Go with WordPress if all five are true:

1. Two named people can run updates and restore a backup, and one is not you alone.
2. Logins and hosting account belong to the PCC (the charity), not to an individual.
3. Hosting is either a charity-free host with daily backups or a care plan at around £25 a month. Check backup retention and whether there is a staging copy.
4. One accessibility-ready block theme. Avoid page builders. Fewer than ten plugins. ChurchSuite embedded, not rebuilt.
5. A one-page hand-over note: where the site lives, who has access, how to update, how to restore.

If condition 1 or 2 cannot be met, Squarespace is the safer choice, even with less freedom.

## On "AI-ready"

AI assistants help with both. For WordPress they help write plugin-free fixes, content and checks. They do not replace a backup, a staging copy or a named maintainer, and a change that nobody reviews can break the site. Use AI to speed up work, not to replace the hand-over note.

## Pilot before committing (about one day each)

Build only the home page and Plan Your Visit page on each. Give the church office two real tasks: change this Sunday's service time, add a photo. Then compare on:

- Did the office find it easy? (Ask the church administrator.)
- Does the ChurchSuite calendar render on a phone?
- Does a free accessibility check (axe or WAVE) pass, plus a keyboard-only test?
- Annual cost with the permissions needed.

## Sources

- [Squarespace Pricing Guide 2026 (Outfy)](https://outfy.com/blog/squarespace-pricing)
- [Squarespace pricing 2026 (Startups UK)](https://startups.co.uk/websites/squarespace-pricing/)
- [Squarespace Basic plan guide (JPK Design Co)](https://www.jpkdesignco.com/blog/squarespace-basic-plan-review)
- [Free hosting for charities (Brixly)](https://brixly.uk/free-hosting-for-charities)
- [Free charity hosting (Spire Hosting)](https://spirehosting.co.uk/free-charity-web-hosting/)
- [WordPress maintenance for charities (WebsiteHelper)](https://www.websitehelper.co.uk/wordpress-maintenance-for-charities/)
- [Twenty Twenty-Two accessibility-ready (WP Tavern)](https://wptavern.com/twenty-twenty-two-is-the-first-default-block-theme-to-get-tagged-as-accessibility-ready)
- [Do Squarespace sites meet WCAG (BOIA)](https://boia.org/blog/do-squarespace-sites-meet-wcag-requirements)
- [WordPress accessibility guide (Deque)](https://www.deque.com/blog/wordpress-accessibility/)
