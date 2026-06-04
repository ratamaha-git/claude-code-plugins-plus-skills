# publishing-skills

Four composable skills that turn an AI coding agent into a platform-agnostic long-tail SEO publishing pipeline. Plan the cadence, research the topic, write the post, illustrate it, and publish to the CMS of your choice.

Platform-agnostic: ships adapters for the Ghost Admin API, WordPress REST, and any static-site generator (Hugo, Astro, Eleventy, Jekyll, Next-MDX). Any other CMS is a short adapter snippet.

## Skills

- **blog-topic-research** validates that a topic has real, verifiable search demand (People Also Ask, Reddit, Stack Overflow, GitHub issues, changelogs) before you spend tokens drafting, and hands the writer citable evidence URLs.
- **seo-blog-writer** runs the end-to-end pipeline for one post: classify, research, interlink, draft clean HTML, scrub LLM tells, AI-SEO audit, then publish through a platform adapter. Adds FAQPage, BreadcrumbList, and HowTo JSON-LD for AI-citation extractability.
- **blog-figure-svg** generates accessible SVG figures (flow diagrams, comparison bars, taxonomies, terminal mocks, OG feature cards) with screen-reader metadata, then rasterizes to compressed PNG for upload.
- **blog-editorial-calendar** is the orchestration layer: it keeps an evidence-backed backlog, picks the next topic to balance your corpus, schedules a rolling cadence, and auto-refills when the queue runs dry.

## Install

```
/plugin install AutomateLab-tech/publishing-skills
```

Or clone the repo: [AutomateLab-tech/publishing-skills](https://github.com/AutomateLab-tech/publishing-skills)

## License

MIT-0
