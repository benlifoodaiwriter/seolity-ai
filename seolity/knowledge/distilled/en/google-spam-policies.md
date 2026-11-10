---
title: Google spam policies: what to avoid and how to stay compliant
lang: en
topic: content
tags: content, spam, eeat, cloaking, link-spam, scaled-content, affiliate, redirects, hacked-sites
sources: https://developers.google.com/search/docs/essentials/spam-policies
updated: 2026-11-10
generated: knowledge-builder
---

# Google spam policies: what to avoid and how to stay compliant

Google's spam policies describe deceptive or manipulative practices that can cause a site to rank lower or be removed from web search results, through automated systems or manual actions. Knowing them helps WordPress and WooCommerce sites avoid risky tactics and use legitimate alternatives such as qualified links, original content and honest redirects.

## Cloaking, redirects and hidden content

- Avoid showing search engines different content than users see (for example, inserting text or keywords only when the requesting user agent is a search engine), because this is cloaking and misleads users.
- If JavaScript or images make content hard for search engines to access, follow Google's recommendations for making that content accessible to search engines and users rather than serving different versions.
- Paywalls and gated content are not cloaking if Google can see the full gated content just like a person with access, and you follow Google's Flexible Sampling guidance.
- Avoid sneaky redirects that send search engines one kind of content and users something significantly different, or that send only mobile or only desktop users to an unrelated spam domain.
- Use redirects for legitimate purposes such as moving a site to a new address, consolidating several pages into one, or sending logged-in users to an internal page. The test is whether the redirect is meant to deceive users or search engines.
- Avoid hidden text and links, such as white text on a white background, text behind an image, CSS positioning text off-screen, font size or opacity of 0, or linking a single small character.
- Accordions, tabs, sliders, tooltips and screen-reader-only text that improves accessibility are acceptable ways to show and hide content, because they serve user experience and do not violate the policy.

## Keyword stuffing and doorway pages

- Write naturally and avoid repeating the same words or phrases so often that the text sounds unnatural, because that is keyword stuffing.
- Avoid blocks of text listing cities and regions you want to rank for, and avoid lists of phone numbers that add no substantial value.
- Avoid creating multiple sites, domains or near-identical pages targeted at specific queries, regions or cities that funnel users to one page, because these are doorway abuse.
- Prefer a clearly defined, browseable site hierarchy over many substantially similar pages that resemble search results pages.
- Avoid generating pages whose only purpose is to funnel visitors into the actual useful part of a site.

## Links: buying, selling and user-generated links

- Avoid buying or selling links for ranking purposes, including exchanging money, goods or services for links, or sending a product in exchange for a link.
- Avoid excessive reciprocal link exchanges, partner pages created only for cross-linking, and automated programs that create links to your site.
- Add rel="sponsored" or rel="nofollow" to the <a> tag for paid, sponsored or advertising links so they do not pass ranking credit; qualified links are not a policy violation.
- Avoid keyword-rich or hidden links in widgets distributed across sites, widely distributed footer or template links, and low-quality directory or bookmark links.
- Avoid guest posts, advertorials or press releases on other sites that contain optimized anchor text and pass ranking credit in exchange for payment.
- Do not require a link as part of a Terms of Service or contract without letting the third-party content owner qualify the outbound link.
- Protect public areas such as comments, forums and uploads from spam, because user-generated spam (comment spam, spammy forum posts, spammy accounts or uploaded files) can harm your site, and owners are often unaware of it.

## Scaled, scraped and thin content

- Avoid generating many pages mainly to manipulate rankings. Using generative AI or other tools to produce many pages without adding value for users is scaled content abuse, however the content is created.
- Avoid stitching together content from different pages, scraping feeds or search results, or synonymizing and translating other sites' content without adding value.
- Avoid creating multiple sites to hide the scaled nature of content, and avoid pages whose content makes little sense to a reader but contains search keywords.
- If you host scaled-abuse content on your site, exclude it from Search.
- Do not republish or lightly modify other sites' content without original content or value, and do not build sites that merely embed or compile third-party media with no substantial added value.
- On affiliate pages, do not copy product descriptions and reviews directly from the merchant. Add value through price information, original reviews, rigorous testing and ratings, product or category navigation and comparisons.
- Avoid cookie-cutter affiliate sites or templates whose same or similar content is replicated across a site, multiple domains or languages.

## Site reputation, expired domains and third-party content

- Avoid publishing third-party content on your site mainly to benefit from your site's established ranking signals, because this can violate the site reputation policy.
- Third-party content is fine when it is genuinely integrated: consistent design and UX, quality in line with the main site, clear authorship and editorial responsibility, and not identical to content on many other sites.
- Clearly disclose the commercial character of sponsored or affiliate content, identify the author and responsible editor, and make the section reachable through the site's navigation.
- User-generated content areas, syndicated news, press release services, editorial columns and affiliate links with proper link treatment are not considered inconsistent with the policy.
- Avoid buying an expired domain and repurposing it primarily to host low-value content that manipulates rankings, for example affiliate content on a former government site.
- If part of your site is affected, you are notified in the Manual actions report and Search Console message center, and you can address the issue or file a reconsideration request.

## Security, malicious behavior and misleading functionality

- Secure your site and check regularly for hacked content such as injected code, injected pages, hidden links or text, and conditional redirects that depend on referrer, user agent or device.
- Fix hacked sites promptly, because hackers often use cloaking to make the hack harder for the owner to notice.
- Avoid hosting malware or unwanted software, and check that downloadable binaries on your site are not inadvertently classed as malware.
- Avoid back button hijacking, which manipulates browser history or other functionality so users cannot immediately return to the previous page.
- Do not build pages that claim to offer a tool or service (such as a generator, PDF merge or timer) but deliver deceptive ads or nothing.
- Do not impersonate businesses, display false business information or publish fake customer support details, because scam and fraud content is filtered from results.

## Other risks and policy circumvention

- Do not send automated queries to Google, such as scraping results for rank checking, without express permission, because it violates the spam policies and Terms of Service.
- Do not create new subdomains, subdirectories or sites to continue violating policies, because circumvention can lead to losing eligibility for features such as Top Stories and Discover, or to more of the site being removed.
- Respect copyright and other legal removal processes, because a significant volume of valid removal requests against a site can lead to demotion of its other content.

Source: https://developers.google.com/search/docs/essentials/spam-policies
