# tankuj-site

The public pages of **Tankuj**, the Czech fuel-price app for iPhone and CarPlay: the support
page and the privacy policy that its App Store listing links to. GitHub Pages serves the
`main` branch at <https://martinstrambach.github.io/tankuj-site/>.

| Page | Czech | Slovak | German | Croatian | Slovenian | Polish | English |
|------|-------|--------|--------|----------|-----------|--------|---------|
| Support | [`/cs/podpora/`](https://martinstrambach.github.io/tankuj-site/cs/podpora/) | [`/sk/podpora/`](https://martinstrambach.github.io/tankuj-site/sk/podpora/) | [`/de/hilfe/`](https://martinstrambach.github.io/tankuj-site/de/hilfe/) | [`/hr/podrska/`](https://martinstrambach.github.io/tankuj-site/hr/podrska/) | [`/sl/podpora/`](https://martinstrambach.github.io/tankuj-site/sl/podpora/) | [`/pl/pomoc/`](https://martinstrambach.github.io/tankuj-site/pl/pomoc/) | [`/en/support/`](https://martinstrambach.github.io/tankuj-site/en/support/) |
| Privacy policy | [`/cs/soukromi/`](https://martinstrambach.github.io/tankuj-site/cs/soukromi/) | [`/sk/sukromie/`](https://martinstrambach.github.io/tankuj-site/sk/sukromie/) | [`/de/datenschutz/`](https://martinstrambach.github.io/tankuj-site/de/datenschutz/) | [`/hr/privatnost/`](https://martinstrambach.github.io/tankuj-site/hr/privatnost/) | [`/sl/zasebnost/`](https://martinstrambach.github.io/tankuj-site/sl/zasebnost/) | [`/pl/prywatnosc/`](https://martinstrambach.github.io/tankuj-site/pl/prywatnosc/) | [`/en/privacy/`](https://martinstrambach.github.io/tankuj-site/en/privacy/) |

Plain HTML and one stylesheet, no build step; `.nojekyll` keeps GitHub from running Jekyll.
A push to `main` is live within a minute or two.

The German pages are the app's pages for Austria, the German-speaking country the app has
prices for. The Polish pages are for a country with no prices at all: their reader is a
driver fuelling across the Czech or Slovak border or on the way south, and they say so.
German, Croatian, Slovenian and Polish are the only privacy policies that describe the
Firebase analytics and crash reporting the released app sends; **the Czech, Slovak and
English pages still say the app has no analytics and must be brought in line.**

The App Store listing points at these URLs (`support_url.txt` and `privacy_url.txt`
per locale in the app's repository), so moving or renaming a page means changing the
listing too. The privacy policy carries an effective date in its first line; bump it when
the policy's substance changes.

Questions about the app: open an issue here or write to martin.strambach@gmail.com.
