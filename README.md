# AI for Meta-Science Hackathon

A minimal, responsive static website for the Stockholm hackathon, 10–17 November 2026. No runtime dependencies, JavaScript, external fonts, or build step.

Live: https://ai4metascience-hackathon.stockholm.ai/

Vercel project: https://vercel.com/stockholm-ai1/ai4metascience-hackathon

## Preview locally

With Node.js 20 or newer:

```sh
npm run dev
```

Open http://localhost:3000. Set `PORT` to use another port.

## Deploy to Vercel

The site is deployed to the `ai4metascience-hackathon` project in the **stockholm-ai1** Vercel team, with `ai4metascience-hackathon.stockholm.ai` attached. The included `vercel.json` selects the `public` directory with no framework or build command.

To publish an update from an authenticated Vercel CLI:

```sh
npx vercel --prod --scope stockholm-ai1
```

Only `public/` is published; original source assets and development scripts remain outside the deployment output.

Automatic GitHub deployments are not connected yet: Vercel requires a GitHub Login Connection for the account. Add that connection in Vercel, then connect `Stockholm-AI/ai4metascience-hackathon` in the project's Git settings to enable deployment on push. The current deployment was published directly with the CLI.

## Content

- `public/index.html`: event copy, dates, prize, and all three candidate task briefs.
- `public/styles.css`: responsive layout, colours, and typography.
- `public/assets/`: partner logos and the original downloadable task PDF.
- Registration: https://luma.com/6b08hj2b (currently a kick-off waitlist).
- Task source: `AI4MetaScience_Hackathon_Tasks.pdf` in this repository. The task requirements and success criteria are summarised on the page; the PDF is also available in full.

Event details were checked against the supplied Luma screenshot and [the Luma event](https://luma.com/6b08hj2b). Partner links: [Stockholm AI](https://www.stockholm.ai/), [AI for Meta-Science](https://ai4metascience.org/), [Sweden AI Factory](https://swedenaifactory.se/), and [Berget AI](https://berget.ai/).

The brief does not specify a submission URL, team-size limits, judging criteria, or participation eligibility. Those are not invented on the site; add confirmed instructions when available. The kick-off waitlist status is static copy and should be updated if registration changes.
