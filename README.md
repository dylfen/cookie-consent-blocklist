Expanding on:
[PatrickHeneise/cookie-consent-blocklist](https://github.com/PatrickHeneise/cookie-consent-blocklist)

This list can be used to block cookie banner popup on DNS level, so you don’t need Adblock software. 
The list should work with AdGuardHome, Pi-Hole, Blocky, Ferrous DNS and probably more :)

Rules for what ends on the list:
- Only block what is necessary to stop the popup without breaking the site.
- Target subdomain like cmp. and consent., otherwise block CMP-vendors website domain eg. cookierocks.com had the script in what looked like a Wordpress upload.
- CMP vendors’ website is not the target, only the domain that is responsible for popup is.


You can help by fork + pull request with a description of what website you get the cookie banner popup.
