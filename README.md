# Cookie Consent Block List

There are plenty of block lists like [OISD](https://oisd.nl), [StevenBlack](https://github.com/StevenBlack/hosts) to help you block ads, trackers, spyware, malware, and all the other crap on the internet. You can use those lists with a [DNS blocker](#dns-blockers).

GDPR has lead to something more annoying than Ad Popups from the 90s: Cookie Consent Popups. 

There are a few services around that help companies with GDPR/CCPA/Cookie Consent. These make it easy and cheap to comply to laws and regulations, so a lot of companies have decided to outsource their cookie and privacy management to these companies, such as Clym.io, Cookielaw.org, Cookiebot.com etc.

Blocking these cookie consent providers means the Cookie Consent popup fails to load, means you don't have to search for those tiny little "Deny All"/"Reject All/Save My Choice" buttons through a dozen different menus before you can actually see the content of the site.

Important note: This doesn't block any cookies and doesn't ensure your privacy in any way, it just prevents the popup to load from those services.

Enjoy the internet without Cookie Consent Popups. (and please use the other lists to block the actual cookies, trackers, etc. for your privacy).

You can add this list to your DNS blocker: https://github.com/PatrickHeneise/cookie-consent-blocklist/blob/main/consent-block.txt

I'll update the list when I come accross other cookie consent providers. Feel free to [open a PR](https://github.com/PatrickHeneise/cookie-consent-blocklist/pulls) if I missed one.

### DNS Blockers

There are several ways to implement these block lists. **Bonus feature**: by using a DNS blocker in your network, you block **all cookies, trackers, cookie consent screens etc. on all your devices in all of your apps**. It's not just a browser extension that works in one browser on one device.

- DIY, advanced, but immediate results (only on your computer): modify the `/etc/hosts` file on your computer
- DIY: [Raspberry Pi](http://raspberrypi.com) & [PiHole](https://pi-hole.net)
- DIY: Raspberry Pi & [AdGuard Home](https://adguard.com/en/adguard-home/overview.html)
- Out of the box: [Firewalla](https://firewalla.com)
- Online and immediate results (no hardware required): [NextDNS](http://nextdns.io)

#### Thanks

Photo by <a href="https://unsplash.com/@vyshnavibisani?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Vyshnavi Bisani</a> on <a href="https://unsplash.com/s/photos/cookie?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
