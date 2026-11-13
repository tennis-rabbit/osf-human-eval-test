# osf-human-eval-test

Test deployment of a clinician rating interface: a rater reads a patient record and three
blinded responses, rates each response on five statements (1 = strongly disagree … 5 = strongly
agree) and ranks the three.

This repository holds the **built site only** (static files). It is a **test site**: ratings
collected here are never pooled with a study round.

## Deploy

GitHub Pages serves the files as they are: **Settings → Pages → Source: Deploy from a branch →
`main` / `(root)`**. There is no build step in this repository.

## Where ratings go

The site is built either with no backend (answers stay in the rater's browser) or pointed at a
database created for testing only. It is never pointed at a database that holds a live round.
