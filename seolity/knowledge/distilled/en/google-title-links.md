---
title: Influencing Title Links in Google Search Results
lang: en
topic: meta
tags: meta, ctr, serp, title, title-link, og:title, h1
sources: https://developers.google.com/search/docs/appearance/title-link
updated: 2026-11-10
generated: knowledge-builder
---

# Influencing Title Links in Google Search Results

Title links are often the main information users rely on to decide which result to click. Google generates them automatically from several sources, but well-written <title> elements and clear on-page headings strongly influence the result and reduce the chance that Google rewrites your title.

## Write good <title> elements

- Do specify a <title> element on every page of the site, because it is the primary source Google uses for title links.
- Do write descriptive, concise titles. Avoid vague descriptors such as "Home" for a home page or "Profile" for a person's profile page, because they tell users nothing about the content.
- Avoid unnecessarily long or verbose titles. There is no length limit for a <title> element, but Google truncates title links as needed, typically to fit the device width.
- Avoid keyword stuffing in titles (e.g. "Foobar, foo bar, foobars, foo bars"). A few descriptive terms can help, but repeating the same words does not help users and can make the result look spammy.
- Do not include flight price information in <title> elements, because Google will likely not show prices in title links for flight pages; flight prices change too quickly to match the landing page.

## Make titles unique and accurate

- Do give every page a distinct <title> that describes that page's content. Avoid titling many pages identically (e.g. "Cheap products for sale" on every commerce page), because users cannot tell the results apart.
- Avoid long boilerplate titles that differ by only one piece of information, because they contain a lot of uninformative text.
- Do update titles dynamically to reflect actual page content, e.g. mention "video" or "lyrics" only on pages that actually contain video or lyrics.
- Do keep titles accurate to the page content. If the <title> does not reflect what the page is about, Google may replace it with a better title link.
- Do update titles when recurring pages change (e.g. a year in an admissions page title). Obsolete titles may be overridden by the date in the visible page title.
- Do ensure each page in a series (e.g. TV seasons) has a distinguishing element in its title, such as the season number, rather than identical titles.
- Do not leave a title half-empty (e.g. "| Site Name"); Google will fall back to headings or other prominent text.

## Branding in titles

- Do use extra descriptive branding text (e.g. a tagline) mainly in the home page title.
- Do brand other pages concisely by adding only the site name at the beginning or end of the <title>, separated by a delimiter such as a hyphen, colon or pipe, because repeating a long tagline on every page looks repetitive when several pages appear for the same query.
- Be aware that for domain-level site names, Google may omit the site name from the title link if it duplicates the site name already shown in the search result.

## Make the main title clear on the page

- Do make the main page title distinctive and the most prominent text on the page, for example with a larger font and by placing it in the first visible <h1> element.
- Avoid giving multiple headings the same visual weight or heading level, because Google may then use the first heading as the title link, which may not be the one you intend.
- Remember Google builds title links from several sources: <title> content, the main visual title, heading elements such as <h1>, og:title meta tags, other large and prominent text, other on-page text, anchor text on the page, text in links pointing to the page, and WebSite structured data. Keep these consistent with your intended title.

## Language and writing system

- Do write the <title> in the same language and writing system (script) as the primary page content. For example, a Hindi page should have a Hindi title, not an English or Latin-transliterated one.
- Be aware that if the title's language or script does not match the page's primary content, Google may choose different text as the title link.
- For Persian-language pages, this means writing the <title> in Persian script rather than in English or transliterated Latin characters.

## Crawling, indexing and updates

- Be careful about blocking pages with robots.txt. Blocking crawling may not prevent indexing, and if Google cannot access the content it relies on off-page content such as anchor text from other sites to generate the title link.
- Use the noindex rule, not robots.txt, to prevent a URL from being indexed.
- Allow time for changes to appear: Google must recrawl and reprocess the page, which may take a few days to a few weeks. You can request a recrawl after making changes.
- If a title link is modified in search results, check whether the page has one of the common issues Google adjusts for; if not, consider whether the displayed title may better fit the query. Google cannot manually change title links for individual sites.

Source: https://developers.google.com/search/docs/appearance/title-link
