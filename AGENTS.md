# FLOHMAXX publishing

The permanent employee and QR-code URL is https://olafjanssen-oss.github.io/flohmarkt-Kasse/kasse.html.

For each user-authorized release, update kasse.html with the tested full application and preserve its stable-update notification. Update both its release constant and version.json release together. Keep release-specific testversion-NNN.html files as archives when useful. Do not replace index.html unless requested. Never automatically reload the app during a checkout. Keep the existing localStorage key and data schema compatible so updates preserve local data. Verify published content and GitHub Pages deployment. Report actual-device tests separately from simulations.
