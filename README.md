# musicrune

A tiny, reactive portfolio for working software and small web experiments.

**[Open the live site](https://musicrun.github.io/noo/)**

![musicrune portfolio](preview.png)

## Featured projects

- **[CS Dojo](https://github.com/musicrun/CS-Dojo)** — a tested Computer Science HL Paper 2 practice interface with question navigation, progress tracking, local saving, and answer export.
- **[Mac DeMarco Birthday Song Finder](https://github.com/musicrun/MacDemarco)** — choose a birthdate and find the matching Mac DeMarco song.
- **[Word Clock](https://github.com/musicrun/WordClock)** — a timezone-aware clock that tells the time in words.
- **[Exam Countdown](https://github.com/musicrun/exam-countdown)** — live countdown cards for every IB paper, with subject filters and a theme toggle.

The portfolio only features projects with a working public page or a verified test suite. Projects that are still being built stay out of the index.

## Run locally

Open \`index.html\` in a modern browser, or run:

\`\`\`sh
python3 -m http.server 8000
\`\`\`

## Design

The page is a small WebGL experience rather than a screenshot or a generic template. A fragment shader generates a reactive liquid signal from noise and distance fields; pointer movement bends it and scroll changes its phase. The work section uses blurred live iframes as previews, which sharpen on focus or hover and link directly to each project.

It uses semantic HTML, responsive CSS, reduced-motion support, keyboard navigation, and no build step or API keys.

The site was built with AI assistance. Every featured project links to its public source.

## License

MIT. See [LICENSE](LICENSE).

