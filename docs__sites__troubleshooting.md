# Troubleshooting - Sites - Documentation - Carrd

Source: https://carrd.com/docs/sites/troubleshooting

Final URL: https://carrd.com/docs/sites/troubleshooting

Carrd
DOCUMENTATION
SITES
Troubleshooting
I'm getting a "Not Found" message when I visit my site
I'm using a custom domain/subdomain but my site either doesn't load, loads inconsistently, loads very slowly, or is still listed as "(initializing)" after an hour
My site uses a custom domain but it's only accessible via domain.ext not www.domain.ext (or vice-versa)
I'm getting a "Not Secure" message when I visit my site via a custom domain/subdomain
I'm getting a "Not Secure" message when I visit www.domain.ext but not domain.ext (or vice-versa)
My meta tags aren't showing up properly or at all
I'm trying to transfer one of my sites to another user but it's not working
I changed my share image but it's still showing the old one on Twitter, Facebook, etc.
I'm using Cloudflare but when I turn it on my site gets stuck in a redirect loop
I set my language to your_language_here but some content (like Timer labels) is still in English
When I view my site on mobile via a custom domain it only shows the desktop version
I'm getting a "Not Found" message when I visit my site

If you just published the site to a brand new custom domain or subdomain (or moved your domain/subdomain to another site) it'll usually take about 10-15 minutes for it to go live. However, if the site still isn't working after a few hours please get in touch as there's probably something else going on.

If you're still seeing this despite not making any domain/subdomain-related changes (or if you're just using a .carrd.co URL), then it's possible the site was taken offline due to a terms of use violation, in which case please contact us.

I'm using a custom domain/subdomain but my site either doesn't load, loads inconsistently, loads very slowly, or is still listed as "(initializing)" after an hour

This usually means your domain/subdomain's DNS records aren't configured properly. Head on over to your domain provider and check for the following:

If you're using a domain, make sure the A records and CNAME record are in place and pointing where they should (and if you're using a subdomain, ensure the same for its A records).

Check for and remove any conflicting records. In the case of a domain, there should only be two A records for @ (pointing to the addresses Carrd gave you), and a single record for www (a CNAME pointing to your bare domain). In the case of a subdomain, there should only be two A records for your subdomain.

Remove any AAAA (IPv6) records for @ as these are not needed.

Ensure the following domain services are disabled on your domain (unless you've enabled them for very specific reasons and know what you're doing):

Domain parking
URL or domain redirection
URL or domain masking
URL or domain forwarding

Note that any changes you make to your DNS records may take up to an hour to propagate so it may be a little while before things begin working as they should. However, if you're still having issues after an hour please get in touch.

My site uses a custom domain but it's only accessible via domain.ext not www.domain.ext (or vice-versa)

Usually means you're missing a DNS record. Head on over to your domain provider and make sure your domain's A and CNAME records are both in place and pointing where they should.

I'm getting a "Not Secure" message when I visit my site via a custom domain/subdomain

If you just published the site to a brand new custom domain or subdomain (or moved your domain/subdomain to another site), an SSL certificate will usually be issued within an hour.

However, if it's still not working after an hour or two, follow the same procedures as above then get in touch so we can get the site back into the SSL queue.

I'm getting a "Not Secure" message when I visit www.domain.ext but not domain.ext (or vice-versa)

Usually means an SSL certificate was issued for the site before its domain's DNS records were fully in place. Please get in touch and we'll issue a brand new certificate that covers both forms of your domain.

My meta tags aren't showing up properly or at all

Make sure you're entering them in the expected format and not pasting in entire <meta> tags.

I'm trying to transfer one of my sites to another user but it's not working

This generally happens for one of the following reasons:

Recipient email isn't linked to an active account, in which case they simply need to create one.
Recipient doesn't have any free site slots left on their account, which they can remedy by either deleting unused sites or simply upgrading their plan.
Recipient's plan doesn't have the features used by the site; for example, the recipient is on Pro Standard but the site uses a custom form which is only available on Pro Plus or higher. If you're sure the recipient is on the correct plan, double check the site for other plan features you may have used inadvertently (eg. Advanced Settings) and try again.
I changed my share image but it's still showing the old one on Twitter, Facebook, etc.

Social media sites typically cache share images for improved performance so it may take a little while for them to cycle out your old image. This generally happens every 24-48 hours but be aware it may take longer on occasion.

I'm using Cloudflare but when I turn it on my site gets stuck in a redirect loop

Setting SSL to Full SSL (Strict) on Cloudflare's end should immediately fix this.

I set my language to your_language_here but some content (like Timer labels) is still in English

Unfortunately this means we don't have translations for your particular language just yet, but if you'd like to help us add them please get in touch.

When I view my site on mobile via a custom domain it only shows the desktop version

Make sure Domain Forwarding and especially Domain Masking are both turned off at your domain provider (as these will sometimes use a not-so-mobile-friendly technique to "mask" the site behind another URL) then follow these instructions to set up your domain.

HomeTermsPrivacyContact

© Carrd Inc. All rights reserved.

## Page links

- [Carrd](https://carrd.com/)
- [https://carrd.com/docs/sites/troubleshooting#menu](https://carrd.com/docs/sites/troubleshooting#menu)
- [https://carrd.com/login](https://carrd.com/login)
- [https://carrd.com/signup](https://carrd.com/signup)
- [https://carrd.com/docs](https://carrd.com/docs)
- [https://carrd.com/docs/general/changelog](https://carrd.com/docs/general/changelog)
- [https://carrd.com/pro](https://carrd.com/pro)
- [https://carrd.com/contact](https://carrd.com/contact)
- [https://carrd.com/docs/sites/troubleshooting#menu](https://carrd.com/docs/sites/troubleshooting#menu)
- [DOCUMENTATION](https://carrd.com/docs)
- [SITES](https://carrd.com/docs/sites)
- [I'm getting a "Not Found" message when I visit my site](https://carrd.com/docs/sites/troubleshooting#not-found)
- [I'm using a custom domain/subdomain but my site either doesn't load, loads inconsistently, loads very slowly, or is still listed as "(initializing)" after an hour](https://carrd.com/docs/sites/troubleshooting#dns-issues)
- [My site uses a custom domain but it's only accessible via domain.ext not www.domain.ext (or vice-versa)](https://carrd.com/docs/sites/troubleshooting#missing-record)
- [I'm getting a "Not Secure" message when I visit my site via a custom domain/subdomain](https://carrd.com/docs/sites/troubleshooting#not-secure)
- [I'm getting a "Not Secure" message when I visit www.domain.ext but not domain.ext (or vice-versa)](https://carrd.com/docs/sites/troubleshooting#not-secure-alt)
- [My meta tags aren't showing up properly or at all](https://carrd.com/docs/sites/troubleshooting#meta-tags-broke)
- [I'm trying to transfer one of my sites to another user but it's not working](https://carrd.com/docs/sites/troubleshooting#transfer-features)
- [I changed my share image but it's still showing the old one on Twitter, Facebook, etc.](https://carrd.com/docs/sites/troubleshooting#cached-share-image)
- [I'm using Cloudflare but when I turn it on my site gets stuck in a redirect loop](https://carrd.com/docs/sites/troubleshooting#cloudflare-loop)
- [I set my language to your_language_here but some content (like Timer labels) is still in English](https://carrd.com/docs/sites/troubleshooting#no-language)
- [When I view my site on mobile via a custom domain it only shows the desktop version](https://carrd.com/docs/sites/troubleshooting#mobile-frame)
- [domain](https://carrd.com/docs/sites/using-a-custom-domain)
- [subdomain](https://carrd.com/docs/sites/using-a-custom-subdomain)
- [get in touch](https://carrd.com/contact)
- [terms of use violation](https://carrd.com/docs/general/content-policy)
- [contact us](https://carrd.com/contact)
- [A records and CNAME record](https://carrd.com/docs/sites/using-a-custom-domain)
- [A records](https://carrd.com/docs/sites/using-a-custom-subdomain)
- [get in touch](https://carrd.com/contact)
- [domain](https://carrd.com/docs/sites/using-a-custom-domain)
- [subdomain](https://carrd.com/docs/sites/using-a-custom-subdomain)
- [SSL certificate](https://carrd.com/docs/sites/setting-up-ssl)
- [procedures as above](https://carrd.com/docs/sites/troubleshooting#dns-issues)
- [get in touch](https://carrd.com/contact)
- [SSL certificate](https://carrd.com/docs/sites/setting-up-ssl)
- [DNS records](https://carrd.com/docs/sites/using-a-custom-domain)
- [get in touch](https://carrd.com/contact)
- [expected format](https://carrd.com/docs/sites/setting-up-meta-tags)
- [create one](https://carrd.com/signup)
- [site slots](https://carrd.com/docs/account/understanding-site-slots)
- [upgrading their plan](https://carrd.com/docs/pro/upgrading)
- [Pro Standard](https://carrd.com/docs/pro/plans#pro-standard)
- [Pro Plus](https://carrd.com/docs/pro/plans#pro-plus)
- [Advanced Settings](https://carrd.com/docs/pro/features#advanced-settings)
- [changed my share image](https://carrd.com/docs/sites/adding-a-share-image)
- [Full SSL (Strict)](https://support.cloudflare.com/hc/en-us/articles/200170416-What-do-the-SSL-options-mean-)
- [set my language](https://carrd.com/docs/sites/setting-a-language)
- [get in touch](https://carrd.com/contact)
- [follow these instructions](https://carrd.com/docs/sites/using-a-custom-domain)
- [General](https://carrd.com/docs/general)
- [Sites](https://carrd.com/docs/sites)
- [Domains](https://carrd.com/docs/sites/using-a-custom-domain)
- [Subdomains](https://carrd.com/docs/sites/using-a-custom-subdomain)
- [SSL](https://carrd.com/docs/sites/setting-up-ssl)
- [Title and Description](https://carrd.com/docs/sites/changing-a-title-and-description)
- [Language](https://carrd.com/docs/sites/setting-a-language)
- [Timezone](https://carrd.com/docs/sites/setting-a-timezone)
- [Site Icon](https://carrd.com/docs/sites/adding-a-site-icon)
- [Share Image](https://carrd.com/docs/sites/adding-a-share-image)
- [Meta Tags](https://carrd.com/docs/sites/setting-up-meta-tags)
- [QR Code](https://carrd.com/docs/sites/generating-a-qr-code)
- [Custom Templates](https://carrd.com/docs/sites/working-with-custom-templates)
- [Redirects](https://carrd.com/docs/sites/setting-up-redirects)
- [Site Files](https://carrd.com/docs/sites/customizing-site-files)
- [Password Protection](https://carrd.com/docs/sites/adding-password-protection)
- [Local Fonts](https://carrd.com/docs/sites/serving-fonts-locally)
- [Update Frequency](https://carrd.com/docs/sites/changing-update-frequency)
- [Cloning](https://carrd.com/docs/sites/cloning)
- [Sharing](https://carrd.com/docs/sites/sharing)
- [Transferring](https://carrd.com/docs/sites/transferring)
- [Downloading](https://carrd.com/docs/sites/downloading)
- [Sitemaps](https://carrd.com/docs/sites/setting-up-a-sitemap)
- [Site Analytics](https://carrd.com/docs/sites/setting-up-site-analytics)
- [Marketing Trackers](https://carrd.com/docs/sites/setting-up-marketing-trackers)
- [UTM Parameters](https://carrd.com/docs/sites/using-utm-parameters)
- [Folders](https://carrd.com/docs/sites/working-with-folders)
- [Archiving](https://carrd.com/docs/sites/archiving-a-site)
- [Deleting](https://carrd.com/docs/sites/deleting-a-site)
- [Troubleshooting](https://carrd.com/docs/sites/troubleshooting)
- [Building](https://carrd.com/docs/building)
- [Forms](https://carrd.com/docs/forms)
- [Account](https://carrd.com/docs/account)
- [Pro](https://carrd.com/docs/pro)
- [Home](https://carrd.com/)
- [Terms](https://carrd.com/terms)
- [Privacy](https://carrd.com/privacy)
- [Contact](https://carrd.com/contact)
