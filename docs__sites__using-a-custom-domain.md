# Using a Custom Domain - Sites - Documentation - Carrd

Source: https://carrd.com/docs/sites/using-a-custom-domain

Final URL: https://carrd.com/docs/sites/using-a-custom-domain

Carrd
DOCUMENTATION
SITES
Using a Custom Domain

Requires Pro Standard or higher

Carrd sites can be published to .carrd.co URLs, custom domains, and custom subdomains. To publish a site to a custom domain (such as domain.ext), follow the steps below.

The custom domain must be registered before you can use it on Carrd. If you haven't registered the domain yet, you can generally do so at any domain provider (such as Cloudflare, Namecheap, or Porkbun).

Click Publish

Set Action to Publish to a custom domain.

Enter the domain name exactly as you want it to appear in the address bar (either domain.ext or www.domain.ext). The version you don't use will automatically forward to the other; in other words, using domain.ext will automatically redirect www.domain.ext to it (and vice versa).

Scroll down a bit to locate the site's DNS records. These will "point" the domain to the Carrd site and usually need to be set up over at your domain provider. For most domains, you'll be asked to add the following records:

An A record pointing @ to the target IP address shown (eg. xxx.xxx.xxx.xxx)
A CNAME record pointing www back to the bare domain (eg. domain.ext)

Not sure how to do this? Select your domain provider for specific instructions:

(Other providers: 1&1 IONOS, Amazon Route 53, Hover, Namesilo, Network Solutions, OVHcloud)

Back at Carrd, click Publish Changes

You're done ... almost. The domain now needs to initialize, which is an automatic process that can take up to an hour to complete (though it's usually a lot faster than that). Once initialized, you'll be able to access the site using the custom domain you just set up (and do so via SSL).

Note: If your dashboard still lists the domain as "(initializing)" after an hour, please refer to the troubleshooting page or simply get in touch for assistance.

HomeTermsPrivacyContact

© Carrd Inc. All rights reserved.

## Page links

- [Carrd](https://carrd.com/)
- [https://carrd.com/docs/sites/using-a-custom-domain#menu](https://carrd.com/docs/sites/using-a-custom-domain#menu)
- [https://carrd.com/login](https://carrd.com/login)
- [https://carrd.com/signup](https://carrd.com/signup)
- [https://carrd.com/docs](https://carrd.com/docs)
- [https://carrd.com/docs/general/changelog](https://carrd.com/docs/general/changelog)
- [https://carrd.com/pro](https://carrd.com/pro)
- [https://carrd.com/contact](https://carrd.com/contact)
- [https://carrd.com/docs/sites/using-a-custom-domain#menu](https://carrd.com/docs/sites/using-a-custom-domain#menu)
- [DOCUMENTATION](https://carrd.com/docs)
- [SITES](https://carrd.com/docs/sites)
- [Pro Standard](https://carrd.com/docs/pro/plans#pro-standard)
- [custom subdomains](https://carrd.com/docs/sites/using-a-custom-subdomain)
- [Cloudflare](https://www.cloudflare.com/products/registrar/)
- [Namecheap](https://www.namecheap.com/)
- [Porkbun](https://porkbun.com/)
- [https://carrd.com/docs/sites/using-a-custom-domain#cloudflare](https://carrd.com/docs/sites/using-a-custom-domain#cloudflare)
- [https://carrd.com/docs/sites/using-a-custom-domain#enom](https://carrd.com/docs/sites/using-a-custom-domain#enom)
- [https://carrd.com/docs/sites/using-a-custom-domain#gandi](https://carrd.com/docs/sites/using-a-custom-domain#gandi)
- [https://carrd.com/docs/sites/using-a-custom-domain#godaddy](https://carrd.com/docs/sites/using-a-custom-domain#godaddy)
- [https://carrd.com/docs/sites/using-a-custom-domain#google-domains](https://carrd.com/docs/sites/using-a-custom-domain#google-domains)
- [https://carrd.com/docs/sites/using-a-custom-domain#iwantmyname](https://carrd.com/docs/sites/using-a-custom-domain#iwantmyname)
- [https://carrd.com/docs/sites/using-a-custom-domain#namecheap](https://carrd.com/docs/sites/using-a-custom-domain#namecheap)
- [https://carrd.com/docs/sites/using-a-custom-domain#namecom](https://carrd.com/docs/sites/using-a-custom-domain#namecom)
- [https://carrd.com/docs/sites/using-a-custom-domain#porkbun](https://carrd.com/docs/sites/using-a-custom-domain#porkbun)
- [https://carrd.com/docs/sites/using-a-custom-domain#squarespace](https://carrd.com/docs/sites/using-a-custom-domain#squarespace)
- [1&1 IONOS](https://www.ionos.com/help/index.php?id=408)
- [Amazon Route 53](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/rrsets-working-with.html)
- [Hover](https://help.hover.com/hc/en-us/articles/217282457-How-to-Edit-DNS-records-A-AAAA-CNAME-MX-TXT-SRV-)
- [Namesilo](https://www.namesilo.com/support/v2/articles/domain-manager/dns-manager#:~:text=You%20can%20modify%20the%20DNS,records%20associated%20with%20your%20domain.)
- [Network Solutions](https://partners.networksolutions.com/en_US/help/how-to/update-Advanced-DNS.html)
- [OVHcloud](https://help.ovhcloud.com/csm/en-gb-dns-edit-dns-zone?id=kb_article_view&sysparm_article=KB0039608)
- [SSL](https://carrd.com/docs/sites/setting-up-ssl)
- [get in touch](https://carrd.com/contact)
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
