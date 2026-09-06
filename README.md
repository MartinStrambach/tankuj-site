# tankuj-site

The public pages of **Tankuj**, the Czech fuel-price app for iPhone and CarPlay: the support
page and the privacy policy that its App Store listing links to. GitHub Pages serves the
`main` branch at <https://martinstrambach.github.io/tankuj-site/>.

| Page | Czech | English |
|------|-------|---------|
| Support | [`/cs/podpora/`](https://martinstrambach.github.io/tankuj-site/cs/podpora/) | [`/en/support/`](https://martinstrambach.github.io/tankuj-site/en/support/) |
| Privacy policy | [`/cs/soukromi/`](https://martinstrambach.github.io/tankuj-site/cs/soukromi/) | [`/en/privacy/`](https://martinstrambach.github.io/tankuj-site/en/privacy/) |

Plain HTML and one stylesheet, no build step; `.nojekyll` keeps GitHub from running Jekyll.
A push to `main` is live within a minute or two.

The App Store listing points at these four URLs (`support_url.txt` and `privacy_url.txt`
per locale in the app's repository), so moving or renaming a page means changing the
listing too. The privacy policy carries an effective date in its first line; bump it when
the policy's substance changes.

Questions about the app: open an issue here or write to martin.strambach@gmail.com.
