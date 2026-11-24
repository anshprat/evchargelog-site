# evchargelog-site

Public pages for the EV Charge Log iPhone app, served by GitHub Pages from `main`
(the account custom domain sites.anshuprateek.com; anshprat.github.io/evchargelog-site/ redirects there):

- https://sites.anshuprateek.com/evchargelog-site/ — home
- https://sites.anshuprateek.com/evchargelog-site/privacy/ — privacy policy (App Store Connect "Privacy Policy URL")
- https://sites.anshuprateek.com/evchargelog-site/support/ — support (App Store Connect "Support URL")

The app links to the privacy and support pages from Settings → About (`AppLinks.swift` in the app repo).
Plain HTML and CSS, no build step. Change the "Effective" date on the privacy page when its content changes.
