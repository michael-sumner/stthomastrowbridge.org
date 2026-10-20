# Platform assessment: WordPress or Squarespace

ChurchEdit is out (cost of multi-user permissions, restricted design). The church chose WordPress over Squarespace. Research date 2026-10-19. Prices and plan limits change, so confirm on the vendor's own page before buying.

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
| Running cost | Hosting that includes updates, backups and security at about £7 a month including VAT (church's figure, provider to be confirmed) | Subscription, with a July 2026 price rise reported. Sources disagree on current figures |
| Lock-in | Lowest, you own the files | Moderate, limited export |

## Recommendation: WordPress

The church chose WordPress. It beats Squarespace on contributor permissions, accessibility control, cost and ecosystem. The weakness is maintenance, so five conditions apply. Status on 2026-10-20:

| # | Condition | Status |
|---|---|---|
| 1 | Two named people can run updates and restore a backup | **Met.** Paul Edwards and Michael Sumner |
| 2 | Logins and hosting account belong to the PCC | **Met.** PCC holds them. Michael Sumner sets up the hosting under the PCC's account |
| 3 | Hosting with daily backups, updates and security, at modest cost | **Met in principle.** Michael Sumner sets up hosting and migrates from ChurchEdit. About £7 a month including VAT. Confirm the provider, backup retention and whether a staging copy is included |
| 4 | One accessible block theme, no page builders, fewer than ten plugins, ChurchSuite embedded not rebuilt | Open |
| 5 | One-page hand-over note | Open |

No paid care plan is needed. The earlier £25 a month figure is withdrawn: updates, backups and security are covered by the hosting.

## Migration from ChurchEdit

Michael Sumner sets up the hosting and migrates. The plan, in order:

1. Confirm who owns the domain `stthomastrowbridge.org` and where it is registered. The registrant must be the PCC, with a named second contact.
2. Set up hosting under the PCC's account. Create WordPress with the chosen theme. Keep it on a temporary address while building.
3. Build the home page and Plan Your Visit first (copy in `08`), then the rest of the structure in `03`.
4. Embed ChurchSuite calendar and room bookings.
5. Put the redirect map from `03` in place, so old addresses still work on day one.
6. Test: keyboard-only, a free accessibility check, phone, the ChurchSuite embeds.
7. Switch the domain's DNS to the new host. Keep ChurchEdit running for one overlap period, then cancel it.

Key-person note: two named maintainers (Paul Edwards, Michael Sumner) meets the condition, but Michael sets it up. The hand-over note (condition 5) is what keeps the church safe if either steps back. Write it as part of the build.

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
- [Twenty Twenty-Two accessibility-ready (WP Tavern)](https://wptavern.com/twenty-twenty-two-is-the-first-default-block-theme-to-get-tagged-as-accessibility-ready)
- [Do Squarespace sites meet WCAG (BOIA)](https://boia.org/blog/do-squarespace-sites-meet-wcag-requirements)
- [WordPress accessibility guide (Deque)](https://www.deque.com/blog/wordpress-accessibility/)
