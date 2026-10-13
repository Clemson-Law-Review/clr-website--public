<p align="center">
  <a href="https://clemsonlawreview.org">
    <img src="CLR-images/CLR--wordmark-on-white-1600x300.png" alt="Clemson Law Review" width="640">
  </a>
</p>

# Clemson Law Review website

The Clemson Law Review is an independent, student-edited legal journal. Its website, [clemsonlawreview.org](https://clemsonlawreview.org), is built and run by the Review's own editors. This repository describes that site for anyone who is curious how it works: what it does, how it is put together, and the free resources it relies on.

**This repository does not contain the website's code, configuration or secrets.** Those are kept in a private repository.

## The Review's two titles

- **Clemson Law Review**: articles, notes, essays and interviews in numbered issues, starting with Volume I, Issue I (December 2025). Cited as Cʟᴇᴍ. L. Rᴇᴠ.
- **Clemson Law Review Online**: case summaries of recent decisions, published on a rolling basis and numbered by volume and page. Cited as Cʟᴇᴍ. L. Rᴇᴠ. Oɴʟɪɴᴇ.

## About this repository

This repository and its README were created by [Claude](https://claude.com), an AI assistant made by Anthropic, for efficiency. **Because it was written by an AI, take everything here with a grain of salt; it may be inaccurate or out of date.**

## Features

Everything the site does, by area.

### For readers

**Case summaries (Clemson Law Review Online)**
- Case Summaries page with a **Large** view (newest summary featured with its one-line summary, then a grid) and a **Condensed** table view (case, citation, court, date, authors, PDF; 100 per page). The choice is kept in the address and remembered.
- Court filter tabs, and a page for each court.
- Each summary shows its court, docket, decision date, authors and editors, its permanent Online citation ([volume] Cʟᴇᴍ. L. Rᴇᴠ. Oɴʟɪɴᴇ [page] ([year])) and any parallel citations ("Also reported as").
- **Linked citations:** every full case citation in the text and footnotes links quietly to the opinion in a free public case-law database, with a card showing court, date and parallel citations. Citations such as *Marbury v. Madison*, 5 U.S. (1 Cranch) 137 (1803), link, and so do short forms (*Id.*, "Marbury, 5 U.S. at 177").
- **Judge cards:** "Chief Justice Marshall", "Justice Paterson", "Justice Chase" and similar link to the judge's profile, with a hover card (portrait, seat, appointment, career, education) on computers and a short card on phones.
- **Laws:** citations to statutes, regulations and the Constitution link to the official text, with a card on hover or tap showing the section heading and where it sits in the code. Covers the U.S. Code, the C.F.R., the Federal Register, public laws, the Statutes at Large, the U.S. Constitution, the South Carolina Code, Florida Statutes and other states' codes. A **Laws cited** page lists every law the site cites, with the pieces that cite each one.

**The journal (Clemson Law Review)**
- **Volumes & Issues** register: volume tabs, a title and author filter, and every issue with its pieces and citations. Lists the Online volumes too, with how to cite.
- **Issue pages:** cover, "From the Editor", contents grouped by type with Read / PDF / Copy citation, previous and next issue, and an All issues menu.
- **Piece pages** for articles, notes, essays and interviews, with subtitle, authors, pages, abstract and the issue they belong to.

**On every piece**
- Bluebook **citation box** with a copy button; Cʟᴇᴍ. L. Rᴇᴠ. set in large and small caps.
- **Download PDF** of the piece, and **Download issue PDF** when the issue has one.
- **Footnote previews:** hover to preview, click to pin.
- Copyright line (authors keep copyright; interviews are © Clemson Law Review) and the Review's disclaimer.
- **Report an error:** a link beside Download PDF, a box after the citation, and a button over selected text.
- Optional extra button beside Download PDF (for example a link to the author's own site).

**Contributors and the masthead**
- **Contributor profiles:** portrait, bio, affiliation, research interests, roles at the Review (current and past), links, ORCID, and every published piece as a citation card. "Bio provided by [Name]." note under bios.
- **Masthead page:** current board by section, featured Editors-in-Chief with photos and bios, an Emeritus dropdown and Past Members. Names link to contributor pages.
- Featured contributors list that can be placed on any page.

**Finding things**
- **Site search** that also finds people (a People card per matching contributor or masthead member) and every piece they wrote, and finds pieces by the laws they cite ("4 U.S.C. § 1").
- **Smarter "Page not found":** reads the mistyped address and suggests the closest summaries, pieces, pages, contributors, courts or issues.
- **Court Calendar** in the header: U.S. Supreme Court and S.C. Supreme Court dates, with case names, refreshed live.
- Old addresses from the Review's first (Wix) site redirect to their new pages.

**Look and feel**
- Clemson purple and orange, with "Clemson" in orange in the wordmark.
- **Dateline** across the top: today's date, the volume and "Cite as" for the page you're on, and Calendar · Dark · Search links.
- **Light and dark mode**, remembered per reader.
- Built for phones, with its own phone masthead and menus.
- **Home Screen app:** a slim "Add to your Home Screen" bar on phones, an app icon and name, and a purple top bar when installed.

**Forms**
- **Contact** and **Submissions** forms (submissions get a reference number like CLR-2026-014), plus Report an error.
- Spam protection and optional copies to the sender.

### For staff

**Publishing**
- **Publish from Word:** up to 20 `.docx` files at once become case summaries or journal pieces, with headings, formatting and footnotes, plus a report of anything to check. Works best with the Review's Word templates.
- **Import a whole issue** from one Word file: the issue and every piece in its contents, with types, authors, pages, subtitles, author notes and footnotes. Re-uploading updates the same pieces.
- Staff Writers submit for review; Senior Editors and up publish or **send back with a note**.
- Publishing checklist before anything goes live.
- `Published: <date>` line in a Word file keeps an older piece's original date.

**Case summary desk**
- Columns for Planned, Drafting, In review and Scheduled.
- **Plan a summary:** look the case up, pick the writer, editor and due date, and optionally email the writer a blank summary in the Review's Word format.
- Publish **now, on a date, or hold**. Reminders for summaries due soon or late.
- Online page numbers are given when a summary goes live and **never change**; a read-only list shows each volume.

**Issues**
- **Issue Builder:** plan pieces (working title, type, authors, due date), fill plans from Word, reorder, number pages, choose the lead piece, attach the issue PDF and cover.
- **Release states:** on hold, scheduled or released. Hidden issues stay off the site, search, sitemaps and the API. Private preview for signed-in staff.
- **Word round trip:** download the issue (or one piece) as a `.docx` in the journal's format, edit it, upload it, and review the changes before applying.

**Editing**
- **Layout editor:** edit an issue or piece on pages laid out like the journal, with paragraph styles, small caps and self-numbering footnotes.
- **Word-style editor** in the browser, with Editing, Suggesting (track changes) and Viewing modes and a preview before applying.
- The WordPress block editor with a **Publication details** sidebar (case details, authors, editors, PDFs, extra button).

**Case data** (with a free case-law database key)
- **Look up the case** from its docket or citation and compare court, date, docket and name, with **Use** buttons.
- Parallel citations added automatically and rechecked weekly until a U.S. Reports page appears.
- One-line summary drafts from the syllabus.
- **Citation check** on every save or import, with plain-language problems ("Name differs", "Matched by name", a suggested fix for swapped digits), slip opinions handled.
- A list of published summaries whose details disagree with the case-law database.
- Editors can correct or turn off any judge card, and look up judges on every published summary at once.
- Stays within the database's request limits, pausing and resuming on its own.

**Laws**
- Citations to statutes, regulations and the Constitution are recognized, checked against official sources and flagged when a section does not exist or has been repealed or moved.
- Short forms ("§ 1", "Id. § 1") point to the last code cited, as in 4 U.S.C. § 1 (Flag; stripes and stars on).
- A **Laws** panel in the editor, and a choice of linking to a free legal reference site or the official government sites.

**PDFs**
- **Automatic PDFs** for every summary (in the writers' Word-template format, with Online page numbers and running head) and every journal piece (in the issue's format), with standard download names.
- **Published PDFs are locked:** the first PDF of a published piece is its published edition. Updating one is a deliberate step with warnings, an optional **Corrected [date]** mark and the original kept public.
- Whole-issue PDFs attached in Issue Builder; a Writer's PDF kept as an admin-only record.

**People**
- Contributors with quick add, profile fields, featured flag, bio-note switch and **ORCID** (link, compare and sync).
- **Masthead dashboard:** drag to reorder, edit in place, photos, featured editors, past members, page settings.
- **Roster spreadsheet** upload, or automatic **sync** from the Review's document storage; only names, roles, statuses and years are read, and protected edits are kept.
- Staff accounts with Law Review roles: Staff Writer, Senior Editor, Editor in Chief.

**CLR Control**
- A staff control panel for phones and computers, installable as its own Home Screen app.
- **Today:** what needs you (reviews, sent-back pieces, due summaries, ORCID changes, backups, policy updates, new versions), your drafts, the current issue, the court calendar and site status.
- Publish, Review, Summaries, Issues, People, Readers, Insights, History and Site screens; each person sees only what their role allows. Changes are logged under Recent activity.

**Safety nets**
- **History and undo:** every change (pieces, issues, contributors, settings, accounts, deleted files) kept for a year, with Undo, Redo and conflict checks.
- **Encrypted nightly off-site backups** with checkpoints before risky actions, alerts, restore of single items, files or the whole database, restore drills, and a standalone restore tool.
- **Updates from GitHub:** new versions appear in the WordPress dashboard; a checkpoint is taken first and the page cache is emptied afterward.

### Search engines and indexing
- Google Scholar tags on every piece, including a per-article PDF link for pieces in an issue PDF.
- SEO plugin integration: ScholarlyArticle structured data with the real authors, pages, ISSN and copyright holder; contributor pages as profiles; automatic focus keyphrases for summaries; featured contributors in `llms.txt`.
- ISSN fields for both titles, shown in the footer, PDFs and structured data once assigned.

### Privacy and analytics
- **Reader statistics** kept on the site: visits, readers, reading time, scroll depth, PDF downloads, citation copies, sources, countries and institutions, devices, site searches, broken links and crawlers.
- **Recordings and heatmaps** (clicks, scroll, attention, rage and dead clicks, errors), stored on the site.
- Privacy protections are built into how readers are counted. The site's Privacy Policy explains them.
- Optional third-party analytics tools, which respect browser privacy signals where set.
- **Privacy Policy and Terms of Use** generated from the site's settings and kept in step with them.

### Site management
- Settings for journal names and citation forms, ISSNs, contact email, disclaimer, Home Screen bar, forms and analytics.
- **Update page wording** replaces chosen pages with the latest default text (the old text stays in Revisions).
- Sample content that can be added and removed in one click.
- Look, layout and menus editable in the Site Editor; the Law Review blocks can go on any page.

## How it is built

The site is a WordPress site made of two custom pieces:

- a **block theme** for the look and templates, and
- a **publishing plugin** that holds everything specific to a law review: content types, citations, PDFs, Word import, the Issue Builder, the masthead, search and indexing.

Content lives in the plugin so it survives any redesign. The site needs WordPress 6.6 or newer.

Releases are published with GitHub Releases and installed from the WordPress dashboard. The major version number marks the site generation: the Review's first site was on Wix, so this one is generation 2.

## Credits

The site relies on free and open resources, and we are grateful for them: free public case-law and legal-data services, official government sources for federal and state law, public court calendars, and the open-source libraries that power PDFs and the Word-style editor.

## Terms of use

The information in this repository is shared so that people can learn how the Review's website works. You may read it and learn from it. You may not use it maliciously. In particular, do not use anything here to:

- attack, disrupt, probe for weaknesses in, or gain unauthorized access to the Review's website, accounts, backups or services;
- impersonate the Review, its editors, its staff or its contributors, or mislead readers about who is behind a message or website;
- phish, spam, harass or collect personal information about the Review's staff, contributors or readers;
- copy the Review's name, logos, wordmarks or published content in a way that suggests you are the Review or that it endorses you.

The Review's name, logos and wordmarks, and the pieces it publishes, belong to the Review and its authors. Nothing in this repository grants a license to use them. This repository is provided as is, with no warranty of any kind, and it may be inaccurate or out of date.
