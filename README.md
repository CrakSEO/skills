# CrakSEO skills

Agent skills that **connect your agent to CrakSEO's remote MCP servers** for SEO research, Search Console and URL indexing. Works with Claude Code, Codex, Cursor and other clients that load `SKILL.md`.

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

| Skill | MCP URL | Use when |
| --- | --- | --- |
| [`crakseo-seo`](skills/crakseo-seo/SKILL.md) | `https://crakseo.com/mcp/seo` | SEO Tools: Keyword Research, SERP, Backlinks & Rank Tracking |
| [`crakseo-serp-api`](skills/crakseo-serp-api/SKILL.md) | `https://crakseo.com/mcp/serp-api` | SERP API: Live Google Search Results |
| [`crakseo-keyword-research`](skills/crakseo-keyword-research/SKILL.md) | `https://crakseo.com/mcp/keyword-research` | Keyword Research: Search Volume, Keyword Difficulty & CPC |
| [`crakseo-backlinks`](skills/crakseo-backlinks/SKILL.md) | `https://crakseo.com/mcp/backlinks` | Backlink Checker: Backlinks, Referring Domains & Anchor Text |
| [`crakseo-rank-tracker`](skills/crakseo-rank-tracker/SKILL.md) | `https://crakseo.com/mcp/rank-tracker` | Google Rank Checker: Keyword Rankings & Rank Tracking |
| [`crakseo-site-audit`](skills/crakseo-site-audit/SKILL.md) | `https://crakseo.com/mcp/site-audit` | SEO Site Audit: Technical SEO Checker & Page Speed |
| [`crakseo-local-seo`](skills/crakseo-local-seo/SKILL.md) | `https://crakseo.com/mcp/local-seo` | Local SEO: Google Maps Rank Checker & Business Profile Ratings |
| [`crakseo-ai-visibility`](skills/crakseo-ai-visibility/SKILL.md) | `https://crakseo.com/mcp/ai-visibility` | AI Search Visibility: Brand Mentions in ChatGPT, Perplexity & AI Overviews |
| [`crakseo-url-indexing`](skills/crakseo-url-indexing/SKILL.md) | `https://crakseo.com/mcp/url-indexing` | URL Indexing: IndexNow, Index Checker & Force Indexing |
| [`crakseo-search-console`](skills/crakseo-search-console/SKILL.md) | `https://crakseo.com/mcp/search-console` | Free Google Search Console & Bing Webmaster Tools |

Each skill tells the agent to **add the matching remote MCP** if it is not already connected, then call CrakSEO tools instead of scraping or guessing.

Setup guides: https://docs.crakseo.com/quickstarts/claude-code · https://docs.crakseo.com/seo-mcp/connect

## License

MIT
