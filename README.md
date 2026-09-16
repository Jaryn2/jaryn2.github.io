# Jaryn's portfolio

A small static portfolio for GitHub Pages. The home page introduces the projects. Each project can have a separate page with its purpose, implementation, screenshots, and results.

## Files

- `index.html`: home page and project list.
- `projects/fiberscout/index.html`: FiberScout project page.
- `assets/site.css`: shared layout, colors, and mobile styles.
- `assets/`: selected project media and a verification summary.
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

The first draft uses only the known first name and verified project details. Education, experience, contact details, and a downloadable resume will be added from the owner's supplied information. There are no invented entries or empty resume links.

## GitHub Pages

The intended repository is `Jaryn2/jaryn2.github.io`, with the default address https://jaryn2.github.io. The site files are at the repository root. Publish from the selected branch's root directory in the repository's Pages settings.

The FiberScout application is a separate project. This portfolio links to its existing public research demo and includes a local saved-scenario walkthrough. It does not run the account API.

## Media and project claims

The screenshots and walkthrough come from the FiberScout verification artifacts and use fictional scenario inputs. The map includes its U.S. Census source attribution. The video is a paced sequence of interface captures, not a continuous recording or a timed user study.

Automated results are recorded in `assets/fiberscout-verification.json`. Do not change the counts or deployment status unless new evidence supports the change.
