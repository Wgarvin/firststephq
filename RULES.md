# First Step HQ: house rules (read before every change)

What it is: a national site that teaches people how to start and run a small U.S. business.
The path is: 1) form the business, 2) stay in good standing, 3) payroll, 4) books.

Voice and copy
- Teach and advise. Plain English. Short. No filler, no throat-clearing, no "In this guide we will...".
- Say what to do, why it matters, and the common mistake. Then stop.
- National site. The homepage never mentions a single state. No state-by-state launch.
- No owner name or personal story anywhere on the site.

Recommendations and affiliates
- Any category that recommends a product or service shows AT LEAST 3 options with honest pros and cons.
  Never just the highest-paying program.
- Affiliate disclosure is ONE line in the footer:
  "We may earn a commission from some links, at no cost to you."
- Affiliate links are placeholders until approved: use href="#" data-affiliate="<program>" and rel="sponsored nofollow".

State facts
- Every state-specific fact (fees, forms, deadlines, agencies) comes from data/states/<slug>.json,
  which is researched from official .gov sources. Never invent or estimate a state fact.
  If a field is null, the page says "Check with the state" and links the official source.

Design
- Match yourjobadvisor.com. Use assets/site.css tokens: paper #f8f7f2, brand teal #1d6255,
  ink #152d37, muted #5a6c66, line #d7ded5, gold focus ring #e5ad5b. Font: Inter, system-ui fallback.

Hidden until launch (do not change without explicit approval from Bill)
- Every response sends header "X-Robots-Tag: noindex, nofollow".
- Every page has <meta name="robots" content="noindex, nofollow">.
- /robots.txt is "User-agent: *\nDisallow: /". No sitemap.xml.

Legal line
- Footer and a top note: "Not legal, tax, or accounting advice."
