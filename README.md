# EL Nonso Niche Finder

A YouTube niche research tool for faceless and Shorts creators. It finds which niches are pulling views right now, spots new channels breaking through, and uses Google Gemini to turn winning videos into ready-to-use video prompts.

Everything runs in your browser. There is no server, no install and no build step, and your API keys never leave your computer.

## Features

- **Niche Scanner:** scan keywords for the top recent videos and get a 0–100 opportunity score built from demand (views per day), outlier rate, small-channel share and new-channel share. Gemini can suggest niche keywords for you.
- **Rising New Channels:** young channels from your scans that are growing fast.
- **Channel Deep-Dive:** paste any channel URL to see its outlier videos, upload pace and Shorts share.
- **AI Prompt Studio:** Gemini writes titles, hooks, voiceover scripts, scene-by-scene prompts for AI visual tools (Veo, Sora, Kling, Runway, Midjourney and more), thumbnail prompts and SEO. It can also do niche analysis, channel breakdowns and batches of Shorts.
- **CSV export** of any niche's videos.

## Getting started

1. Download `index.html` and open it in Chrome or Edge, or use the GitHub Pages link if it's enabled for this repo.
2. Open **Settings** and paste:
   - a **YouTube Data API v3** key from [Google Cloud Console](https://console.cloud.google.com/). Enable "YouTube Data API v3", create an API key, and restrict it to that API. Leave application restrictions on *None*, or add a website restriction for your GitHub Pages URL if you host it.
   - a **Gemini** API key from [Google AI Studio](https://aistudio.google.com/apikey).
3. Click **Save & test keys**, then start scanning.

Keys are stored only in your browser's local storage.

## Quota

The YouTube API gives 10,000 units a day. One keyword scan costs about 102 units and a channel deep-dive about 3. Quota resets at midnight Pacific Time.

## Note on faceless content

YouTube may demonetize mass-produced or reused content. The AI prompts are written to add original value (story, facts, insight), so fact-check claims before you publish.

## License

MIT
