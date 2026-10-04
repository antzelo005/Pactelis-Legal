# Pactelis public legal and support pages

This repository contains only public Pactelis legal and support pages for Pactelis Whiteboard. The application source repository remains private. No application source, user boards, databases, internal logs, credentials, or private application Git history belong here.

## Pages

- Home: https://antzelo005.github.io/Pactelis-Legal/
- Privacy policy: https://antzelo005.github.io/Pactelis-Legal/privacy/
- Support information: https://antzelo005.github.io/Pactelis-Legal/support/

The site uses plain HTML and a local stylesheet. It has no framework, JavaScript, analytics, tracking scripts, cookies set by site code, external fonts, forms, payment embeds, or build dependencies. GitHub provides hosting under its own privacy practices.

## GitHub Pages deployment

1. Keep **this repository** public. Keep the separate Pactelis Whiteboard application repository private.
2. In this repository's **Settings → Pages**, choose **Deploy from a branch**.
3. Select **main** and **/ (root)**, then save.
4. Enable **Enforce HTTPS** if it is not already enabled.
5. Wait for the Pages deployment to finish and check all three URLs above, including the stylesheet and navigation links.

The `.nojekyll` file tells Pages to serve the static files without Jekyll processing. Future commits to `main` deploy the updated pages. The same branch/root configuration can be set through GitHub's Pages API. No application repository visibility change or source publication is required.

## Files

- `index.html` — public landing page.
- `privacy/index.html` — application privacy policy, last updated October 4, 2026.
- `support/index.html` — existing behavior and voluntary-support information.
- `assets/styles.css` — responsive, local styling, including print layout.
- `.nojekyll` — static Pages configuration.
- `README.md` — repository purpose, deployment, and maintenance.

## Public privacy/support contact

The verified public privacy/support contact for Pactelis Whiteboard is [pactelis.gr@gmail.com](mailto:pactelis.gr@gmail.com). The privacy and support pages link to this address. The existing Buy Me a Coffee URL is a voluntary contribution link, not a designated privacy/support channel.

Review the policy when application behavior changes, update its date, and keep the content accurate. Use the deployed privacy HTTPS URL in the Store listing once verified. This repository does not perform Store submission, certification, application tagging, or release automation.

## Publication boundary

Publish only the six files listed above and future explicitly intended public website/legal files. Inspect staged changes before each push. Keep development screenshots and validation tooling outside this repository. Never copy the application's `.git` directory, source projects, manifests, boards, database files, secrets, keys, certificates, logs, local filesystem paths, personal documents, or test data into this repository.
