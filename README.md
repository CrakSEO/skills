# CrakSEO skills

Agent skills that **connect your agent to CrakSEO's remote MCP servers** for SEO research, Search Console and URL indexing. Works with Claude Code, Codex, Cursor and other clients that load `SKILL.md`.

Skill names follow [MCP listing names](../../docs-internal/engineering/operations/mcp-listing-names.mdx): keyword-first, ending with CrakSEO.

## Install

```bash
npx skills add CrakSEO/skills
# or
npx skills add crakseo/skills
```

Claude Code plugins (MCP + skill together):

```text
/plugin marketplace add CrakSEO/crakseo-mcp-plugins
/plugin install seo-tools-by-crakseo@crakseo
```

## Skills (one per MCP)

| Skill | MCP URL | Listing name |
| --- | --- | --- |
| [`seo-tools-keyword-research-serp-backlinks`](skills/seo-tools-keyword-research-serp-backlinks/SKILL.md) | `https://crakseo.com/mcp/seo` | SEO Tools: Keyword Research, SERP, Backlinks & Rank Tracking by CrakSEO |
| [`serp-api-live-google-search-results`](skills/serp-api-live-google-search-results/SKILL.md) | `https://crakseo.com/mcp/serp-api` | SERP API: Live Google Search Results by CrakSEO |
| [`keyword-research-search-volume-cpc`](skills/keyword-research-search-volume-cpc/SKILL.md) | `https://crakseo.com/mcp/keyword-research` | Keyword Research: Search Volume, Keyword Difficulty & CPC by CrakSEO |
| [`backlink-checker-referring-domains`](skills/backlink-checker-referring-domains/SKILL.md) | `https://crakseo.com/mcp/backlinks` | Backlink Checker: Backlinks, Referring Domains & Anchor Text by CrakSEO |
| [`google-rank-checker-keyword-rankings`](skills/google-rank-checker-keyword-rankings/SKILL.md) | `https://crakseo.com/mcp/rank-tracker` | Google Rank Checker: Keyword Rankings & Rank Tracking by CrakSEO |
| [`seo-site-audit-technical-page-speed`](skills/seo-site-audit-technical-page-speed/SKILL.md) | `https://crakseo.com/mcp/site-audit` | SEO Site Audit: Technical SEO Checker & Page Speed by CrakSEO |
| [`local-seo-google-maps-rank-checker`](skills/local-seo-google-maps-rank-checker/SKILL.md) | `https://crakseo.com/mcp/local-seo` | Local SEO: Google Maps Rank Checker & Business Profile Ratings by CrakSEO |
| [`ai-search-visibility-brand-mentions`](skills/ai-search-visibility-brand-mentions/SKILL.md) | `https://crakseo.com/mcp/ai-visibility` | AI Search Visibility: Brand Mentions in ChatGPT, Perplexity & AI Overviews by CrakSEO |
| [`gsc-indexing-indexnow-force-indexing`](skills/gsc-indexing-indexnow-force-indexing/SKILL.md) | `https://crakseo.com/mcp/url-indexing` | Google Search Console Indexing: Index Checker, IndexNow & Force Indexing by CrakSEO |
| [`free-google-search-console-gsc-bing`](skills/free-google-search-console-gsc-bing/SKILL.md) | `https://crakseo.com/mcp/search-console` | Free Google Search Console (GSC) & Bing Webmaster Tools by CrakSEO |

Each skill tells the agent to **add the matching remote MCP** if it is not already connected, then call CrakSEO tools instead of scraping or guessing.

Setup guides: https://docs.crakseo.com/quickstarts/claude-code · https://docs.crakseo.com/seo-mcp/connect

## License

MIT
