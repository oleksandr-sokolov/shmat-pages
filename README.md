# shmat-pages

The public site for **Shmat: Cut the Exact Piece**: the landing page, the
privacy policy the stores link to, and the `app-ads.txt` file for AdMob.

Static HTML, no build step, no JavaScript. Colours follow the app's "paper and
scissors" look — kraft background, ink text, pastel paper — with Nunito for
type. Dark mode follows the visitor's system setting.

| File            | What it is                                                           |
| --------------- | -------------------------------------------------------------------- |
| `index.html`    | landing page                                                         |
| `privacy.html`  | privacy policy — the URL App Store Connect and Play Console point to |
| `uk/`           | Ukrainian versions of both pages                                     |
| `styles.css`    | the whole stylesheet                                                 |
| `assets/`       | the site icon                                                        |
| `app-ads.txt`   | authorised AdMob seller record                                       |
| `.nojekyll`     | serves the files as they are, without Jekyll processing              |

## Public URLs

- <https://oleksandr-sokolov.github.io/shmat-pages/>
- <https://oleksandr-sokolov.github.io/shmat-pages/privacy.html>
- <https://oleksandr-sokolov.github.io/shmat-pages/app-ads.txt>
- <https://oleksandr-sokolov.github.io/shmat-pages/uk/>

## app-ads.txt

AdMob looks for `app-ads.txt` at the **root of the developer website** listed
in the App Store and Google Play. A file under a sub-path such as
`/shmat-pages/app-ads.txt` is not found by the crawler, so the developer
website in the stores must be a domain (or `username.github.io`) whose root
serves this file.

## Publishing

GitHub Pages, `main` branch, root folder.
