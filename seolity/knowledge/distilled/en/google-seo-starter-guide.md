---
title: Google SEO Starter Guide: Core On-Page and Site Basics
lang: en
topic: on-page
tags: on-page, content, site-architecture, canonicalization, title-links, snippets, images, internal-linking
sources: https://developers.google.com/search/docs/fundamentals/seo-starter-guide
updated: 2026-11-10
generated: knowledge-builder
---

# Google SEO Starter Guide: Core On-Page and Site Basics

Overview of the most common and effective SEO improvements: helping Google find and render content, organizing URLs, creating useful people-first content, and shaping titles, snippets and images. It also lists myths not worth prioritizing, so effort goes where it matters.

## Crawling, indexing and rendering

- Check whether the site is already indexed by searching with the site: operator before doing discovery work; if results appear, the site is in the index.
- Do let Google access the same resources as a user's browser (such as CSS and JavaScript) because hiding them can prevent Google from understanding pages and ranking them well.
- Verify how Google sees a page with the URL Inspection Tool in Search Console.
- If page content varies by visitor location, make sure you are satisfied with what Google sees from its crawler location, which is generally the US.
- Submit a sitemap listing the URLs you care about if you want to, but it is not required; many CMSes create one automatically, and promoting the site comes first.
- Use the documented methods to block crawling or indexing for files, directories or whole sections you do not want in search results.
- Allow time before judging changes: some take hours and others months, so wait a few weeks before assessing the impact and then iterate if needed.

## URL structure and duplicate content

- Use descriptive URLs with words useful to users (e.g. /pets/cats.html) instead of random identifiers, because URL words can appear as breadcrumbs in results.
- On sites with more than a few thousand URLs, group topically similar pages in directories so Google can learn how often each directory changes and crawl accordingly.
- Make each piece of content reachable through one URL where possible, to avoid confusing users and wasting crawl resources.
- Redirect non-preferred duplicate URLs to the URL that best represents the content; if you can't redirect, use the rel="canonical" link element.
- Don't panic about duplicate content: it is not a spam violation or a manual action trigger, and Google picks a canonical automatically if you don't. Copying other people's content is a different matter.
- Don't reorganize a working site in a rush; search engines will likely understand pages as they are, and structure improvements pay off mainly long term on larger sites.

## Content quality

- Prioritize compelling, useful content; it likely influences search presence more than any other suggestion in the guide.
- Write text that is easy to read and well organized, free of spelling and grammar mistakes, split into paragraphs and sections with headings.
- Create unique content from your own knowledge; don't copy others in part or in full, or simply rehash what is already published.
- Review published content regularly and update it, or delete it if it is no longer relevant.
- Write helpful, reliable, people-first content and cite expert or experienced sources to show expertise.
- Anticipate the different terms that beginners and experts use for the same topic (e.g. "charcuterie" vs. "cheese board"), but don't worry about covering every variant because Google's language matching can relate pages to queries without exact terms.
- Avoid ads or interstitials that distract users or make the content hard to read or use.

## Links

- Link to relevant pages on your own and other sites, because links are how Google discovers most new pages and they give users and search engines context.
- Write descriptive anchor text so users and search engines understand what the linked page contains before visiting.
- Add nofollow or a similar annotation to links to resources you don't trust but still want to reference, to avoid being associated with them.
- Make sure your CMS automatically adds nofollow or a similar annotation to links in user-generated content such as comments and forum posts, which also discourages spammers.
- Promote the site through social media, community engagement, advertising, newsletters (with permission) and offline materials with your URL, but don't overdo it, since excessive promotion can fatigue people and be seen as manipulation.

## Title links and snippets

- Write page titles that are unique to the page, clear, concise and an accurate description of the content; they feed the <title> element, which Google uses for title links.
- Where useful, include the site or business name, the business location and what the page offers in the title.
- Check that your CMS turns the titles you write into <title> elements; most do so automatically.
- Remember that snippets come from the page's actual content, so put the key information in the visible text.
- Write a meta description that is short (one or two sentences), unique to the page and covers its most relevant points, knowing Google may occasionally use it as the snippet.

## Images and video

- Use sharp, clear, high-quality images so users can judge whether an image matches what they want.
- Place images near text relevant to them (e.g. a yarn shop photo in that shop's review section) so Google can understand the image in context.
- Add short, descriptive alt text through the alt attribute of the img element (or the CMS image description field) to explain how the image relates to the content.
- For videos, embed them on a standalone page near relevant text, and write descriptive titles and descriptions.

## Myths not to prioritize

- Don't add the keywords meta tag; Google Search doesn't use it.
- Avoid keyword stuffing, including variations, because it tires users and violates Google's spam policies.
- Choose domain names and URL paths for business and marketing reasons; keywords in them have hardly any ranking effect beyond appearing in breadcrumbs.
- Pick a TLD for country targeting only if relevant (e.g. .ch for Switzerland); otherwise Google doesn't care which TLD you use.
- Don't aim for a magic word count; content length alone doesn't matter for ranking, and writing naturally with varied words gives more chances to match queries.
- Choose subdomains or subdirectories based on what suits your business, not on SEO assumptions.
- Don't obsess over heading order or count: semantic order helps screen readers but doesn't matter to Google Search, and if you feel there are too many headings, there probably are.
- Don't treat PageRank/links as the only signal, since Google uses many ranking signals, and don't treat E-E-A-T as a ranking factor.

Source: https://developers.google.com/search/docs/fundamentals/seo-starter-guide
