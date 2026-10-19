# Consultant brief: St Thomas' Trowbridge website refresh

Scope: content and structure plan only. No build, no visual design, no platform change yet.
Crawl date: 2026-10-19 (39 pages, see `crawl/INDEX.md`).

## 1. The one-line problem

The site is written for people who already attend. The church wants to grow with younger families, and its best door in (Parent and Toddlers, kind people) is invisible on the site.

## 2. Who the site must serve

Rough age mix from the church (not measured): 15% young families, 20% aged 45 to 65, 65% aged 65 or over.

| Audience | Share of congregation | What they need in the first 30 seconds | Current site |
|---|---|---|---|
| Young families and playgroup parents | 15% | When, where, what happens with my children, will I be welcome, is it safe | Buried in three different pages, no faces, no photos |
| Regulars aged 65+ | 65% | This week's news, service times, calendar, large readable text, a phone number | Works, but out of date in places and menu labels are unclear |
| Regulars aged 45 to 65 | 20% | Groups, giving, rotas, watching a service online | Spread across "Church life" |
| Weddings, baptisms, funerals | Not members | Who to contact, what it costs, what to expect | Thin pages, link out to Church of England |
| Room hirers | Not members | Rooms, availability, price, how to book | ChurchSuite booking calendar plus leaflet, works |
| Parish and diocese, schools, partners | Small | Safeguarding contacts, Who's who | Fine |

Warning on evidence: the 2017 survey had 19 replies and only 4 were from people under 65. It says nothing about young families. Treat the age mix as a working assumption and measure it (section 6).

## 3. Strategy: two doors, one site

1. **Door one: "New here?"** Written for a parent who has never been to church. Plan Your Visit, Families, faces, quotes.
2. **Door two: "Already part of us?"** Weekly news, calendar, sermons, groups. Always one click from the home page, in large type.

Neither door removes anything the 65+ majority relies on. That is how you grow without a fight: every current task stays within one click, and every old address redirects.

## 4. The playgroup insight

People started coming because the playgroup people were kind. The site does not say this anywhere.

- Parent and Toddlers (Mondays in term time, 10 to 11.45am at Holy Trinity, up to 40 children) deserves its own page and a home page card.
- Show real faces (with consent, never identifiable children without parental consent). Add two or three short quotes from playgroup parents.
- Say plainly what happens next: "Many of our families first met us at Parent and Toddlers. Sunday groups for 0 to 18 run alongside the service."
- Add a "How did you hear about us?" prompt on the contact form and a card on Sundays so you can see whether this works.

Open question for the church: Holy Trinity is described to us as venue and summer services only, yet the crawl shows Parent and Toddlers, The Island (Tuesday after school) and Trowbridge Women's Shed meeting there. The Holy Trinity page must reflect what truly happens.

## 5. Brand and logos (placeholders for now)

- Public name: **St Thomas' Church Trowbridge**. It matches the domain and what people search for.
- Legal name goes in the footer only: *The Parochial Church Council of the Parish of St Thomas the Apostle, Trowbridge* plus registered charity number (church to supply).
- The vicar's three-logo idea is held as three placeholder slots: `logo-main` (St Thomas'), and two sub-marks for the other churches. Layout reserves the space, no artwork commissioned yet. Decide after the church answers which three logos are meant.
- Recommendation: one strong main mark in the header. Sub-marks appear only on each church's own page, so the header is not three competing logos.

## 6. Handling strong opinions

The church's own requirements note says it well: take account of different views without being unduly swayed by strong opinions. Practical way to do that:

1. Agree the **test** before the content: does this serve a named audience? If not, it goes (Paul Edwards' minimum-requirements principle).
2. Name one **content owner** per section and one **final decider** for the site.
3. Keep a **decision log** (what, who, why) so settled issues stay settled.
4. Show two or three **sample layouts**, not a blank page. Opinions get concrete and shorter.
5. Run a **short new survey** (paper at the door, link on the weekly news, QR on the playgroup noticeboard) with three questions: what did you come to the website for, did you find it, what is missing. Include playgroup parents.
6. Put a **"where things have moved" box** in the weekly news for four weeks after launch. Regulars hate lost things more than ugly things.
7. Check site analytics (if the platform offers them) for what is actually used, and let that outrank anyone's impression.

## 7. Marketing presence beyond the site (secretary's item 2)

Quick wins, roughly in order of effort:

1. Google Business Profile for each church: St Thomas', St John's, Holy Trinity (venue). Correct hours, photos, link to Plan Your Visit.
2. A Church Near You: confirm entries are current for all three churches (already linked from the site).
3. Facebook page and groups: pinned post with Sunday time and Parent and Toddlers.
4. YouTube: tidy playlists, add a short "welcome to St Thomas'" video of the building and people.
5. Local listings for Parent and Toddlers (Wiltshire family information, local parenting groups) and school newsletters.
6. A card or QR code in the playgroup, linking to Plan Your Visit.

## 8. Platform and hosting (secretary's item 3)

Decision comes after the structure is agreed. Criteria in order:

1. The church office can edit it without a developer.
2. Several people can have logins with different permissions (Paul's requirement).
3. ChurchSuite calendar, bookings and any future giving embed in cleanly.
4. Accessible by default (WCAG 2.2 AA), mobile first.
5. Low, predictable running cost and no single-volunteer dependency (Andrew Palmer built and rebuilt it, estimated 60 hours).

Current platform is ChurchEdit (footer: "Powered by Church Edit"). Default recommendation: stay unless the plan in `03` cannot be built on it. Unknown for now: whether ChurchEdit supports multi-level permissions and wider menus. Ask the provider two questions before any migration discussion.

ChurchSuite today: calendar on `/whats-on/` and room bookings on `/about-us/rooms-for-hire/` are embedded iframes. Giving is not on ChurchSuite. If the ChurchSuite admins set up online giving, the Give page becomes a one-button page with Gift Aid text.

## 9. Accessibility rules for this audience

- Body text at least 18px, line length under 75 characters, strong contrast.
- Phone number and Sunday time visible without scrolling on every page.
- Menus: plain words, no catchy labels (2017 survey: "Connect with God" was catchy but not clear). Wide drop-downs (Isaac and Paul both asked for this).
- Weekly news readable on the page, not only as a PDF download.
- Every PDF has a text alternative or summary.
- Print-friendly Plan Your Visit page, because 65+ members hand it to friends.
