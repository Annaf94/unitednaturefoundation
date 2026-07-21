# United Nature Foundation — Website (flat structure)

Every page is now a single self-contained HTML file — CSS and JS are built directly into each page, so there are no css/ or js/ subfolders to worry about anymore.

## Files
- index.html — Home
- our-story.html — Our Story
- canopy-crew.html — Canopy Crew
- unf-projects.html — UNF Projects
- donate.html — Donate
- join-now.html — Join Now
- pathways.html, power.html, pedal.html — project placeholder pages

## How to upload to GitHub
1. Go to your repo -> Add file -> Upload files
2. Select/drag all 9 .html files plus README.md at once -- since there are no folders involved, there's nothing for GitHub to lose this time
3. This will OVERWRITE the old versions of files with the same name -- that's expected, it fixes the broken ones
4. Delete the old css and js folders (and the projects folder) from your repo afterwards, since they're no longer used -- click into each one on GitHub and use the "..." menu to delete
5. Commit, then Vercel will auto-redeploy

## Still using placeholder images
Photo spots still show green gradient blocks with descriptive labels (e.g. "hero photo -- toucan in rainforest canopy"). Ask Claude when you're ready to swap in real images.
