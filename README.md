# tabletrack-web

The website of **TableTrack** (`com.olderwold.gm`): what the app is, its privacy policy and its
child safety standards. Plain HTML and one stylesheet in `site/`, no build step.

| Page | URL |
|---|---|
| Home | https://tomkoptel.github.io/tabletrack-web/ |
| Privacy policy | https://tomkoptel.github.io/tabletrack-web/privacy.html |
| Child safety standards | https://tomkoptel.github.io/tabletrack-web/child-safety.html |

`.github/workflows/pages.yml` deploys `site/` to GitHub Pages on every push to `main` and daily.
GitHub pauses scheduled workflows in a repository with no activity for 60 days; re-enable it in
the Actions tab if that happens.

Preview locally: `python3 -m http.server -d site 8000`, then open http://localhost:8000.

The images come from the app's repository: the marks from `store/icons/`, the screenshots from
the Play listing (`androidApp/src/main/play`). The privacy policy and the child safety page are
the URLs given to Google Play and the App Store; change them with the app, not apart from it.
