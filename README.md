# Jaryn Weinel's portfolio

A small static portfolio for GitHub Pages. The home page introduces the projects. Each project can have a separate page with its purpose, implementation, screenshots, and results.

## Files

- `index.html`: introduction, project list, education, work history, and contact details.
- `projects/fiberscout/index.html`: FiberScout project page.
- `assets/site.css`: shared layout, colors, and mobile styles.
- `assets/`: selected project media and a verification summary.
- `assets/Jaryn-Weinel-Resume.pdf`: downloadable resume.
- `.nojekyll`: tells GitHub Pages to serve these files directly.

There are no packages to install and no database. The pages work without JavaScript.

## Preview

From this directory, run `python -m http.server 4175 --bind 127.0.0.1` and open http://127.0.0.1:4175.

## Add another project

1. Create `projects/your-project/index.html`, using the FiberScout page as a starting point.
2. Keep the shared stylesheet link and update the title, description, headings, and contents.
3. Add an article to the Projects section of `index.html` and link it to the new page.
4. Add only the screenshots and files you intend to make public.
5. Check the links and preview the result before committing and pushing.

## Resume information

Education, employment dates and duties, track and cross country participation, and contact information were supplied by Jaryn on September 16, 2026. The project bullets use the verified FiberScout implementation and test results. The skills list describes tools used in the project rather than claiming an unsupported level of proficiency. Update the website and PDF together when details change.

## GitHub Pages

The public repository is `Jaryn2/jaryn2.github.io`, at https://jaryn2.github.io. GitHub Pages publishes the root directory of the `codex/portfolio` branch. Pushing to that branch starts a new deployment.

The FiberScout application is a separate project. This portfolio links to its existing public research demo and includes a local saved-scenario walkthrough. It does not run the account API.

## Media and project claims

The screenshots and walkthrough come from the FiberScout verification artifacts and use fictional scenario inputs. The map includes its U.S. Census source attribution. The video is a paced sequence of interface captures, not a continuous recording or a timed user study.

Automated results are recorded in `assets/fiberscout-verification.json`. Do not change the counts or deployment status unless new evidence supports the change.

## September 24 project update

Stockroom, Import Desk, and Source Notes each have a project page with real local screenshots, a stack explanation, a code guide, and a passing GitHub Actions run. These pages are static walkthroughs. Their Java/Python backends are not hosted on GitHub Pages. The main resume download is the software engineering version featuring Stockroom and FiberScout. The new code lives in separate public repositories linked on each page.
