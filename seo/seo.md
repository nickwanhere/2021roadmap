# SEO

## General

- whitehat SEO
  - using standard way to increase SEO
- blackhat SEO
  - using hacky way to increase SEO which could be penalized by google
- why focus on google
  - 90% of market
- useing site: / GSC can check site SEO performance
- keyword research
  - general
  - middle
  - long tail
- SERP
  - Search Engine Result Page
  - Paid advertisements
  - Featured snippets
  - People Also Ask boxes
  - Local (map) pack
  - Knowledge panel
  - Sitelinks

## Crawling

- making sure the site can be crawled
- If Googlebot encounters an error while trying to access a site’s robots.txt file and can't determine if one exists or not, it won't crawl the site.
- GSC can config to skip parameter
- make sure important pages on navigation
- sitemap.xml
- 301 perm redirection to all link equity
- 302 temp redirection
- page got removed if
  - 4xx or 5xx
  - meta noindex
  - penalized by google
  - blocked crawling
- robot meta
  - `<meta name="robots" content="noindex, nofollow" />`
  - index/noindex
  - follow/nofollow
    - follow links within the page
  - noarchive
    - dun save cached copy
- X-Robots-Tag
  - http header
    - `<Files ~ “\/?no\-bake\/.*”> Header set X-Robots-Tag “noindex, nofollow”</Files>`

## Ranking

- Good engagement > lead to good ranking
- Focus on content, conversion rate instead of ranking focus [2]
- Backlink / Inbound affect SEO score [1]
- Internal links doesnt affect SEO score
- RankBrain [3]
  - Google AI
- Localized search
  - Relevance
  - Distance
  - Prominence
  - Reviews
  - Citations

## Keyword research

- know the intention / business goal
- questions
  - what type of product people searching for
  - who is searching for these terms
  - when they search it (seasonality)
  - how
    - what words
    - what questions they ask
    - mobile vs desktop
  - why
  - where are they located ( locally, nationally, or internationally)
  - provide the best content about subject to cultivate a community and fulfill what all those people are searching for
- Discovering keywords
  - tools
    - moz explorer https://moz.com/explorer#index
    - ahrefs https://ahrefs.com/
    - SEMrush
    - google trend
    - http://adwords.google.com/keywordplanner
    - http://answerthepublic.com/
    - https://www.spyfu.com/
    - https://keywordseverywhere.com/
  - prioritize keywords for the biggest strategic advantage
    - prioritize high-volume keywords that your competitors are not currently ranking for
    - Keywords by season e.g. “christmas box"
    - Keywords by region
  - diversify your website’s pages by optimizing each for uniquely valuable keywords
  - search volume
  - long tail > conversion better

## ON-PAGE SEO

- Content
- one comprehensive page better than multiple similar pages
- no Google penalty for duplicate content, but filter
- Cloaking , can be positive or negative
- dun do Keyword stuffing
- no Auto-generated content
- h1 is needed
- h2 - h6 need to be in order
- The more links on a page, the less equity each link can pass to its destination page. A page only has so much equity to go around.
- redirection - ideally no more than 3 and fewer than 5
- Images
  - If your image requires animation, use a GIF.
  - If you don’t need to preserve high image resolution, use JPEG (and test out different compression settings).
  - If you do need to preserve high image resolution, use PNG.
  - If your image has a lot of colors, use PNG-24.
  - If your image doesn’t have a lot of colors, use PNG-8.
- Text size
  - Google recommends 16-point font and above to minimize the need for “pinching and zooming” on mobile
  - The text color in relation to the page’s background color should also promote readability.
- Title length search engines display the first 50–60 characters
  - If you can’t get your title tag down to 60 characters without harming its readability, go longer (within reason)
- Meta description - It’s best to write meta descriptions between 150–300 characters in length
- Url - The URL is a minor ranking signal, but you cannot expect to rank on the basis of the words in your domain/page names alone
- it’s best to host on a non-dated URL
- Minimizing length, both by including fewer words in your page names and removing unnecessary subfolders, makes your URLs easier to copy and paste, as well as more clickable.
- URLs are those that can easily be read by humans
- use the hyphen character (-) to separate words in a URL
- on HTTPS to migrate to HTTP/2.
- using structured data can help enable a rich snippet to be present, but does not guarantee it.

## Audit

- Crawlability
- Indexed pages
