# URL Types - Building - Documentation - Carrd

Source: https://carrd.com/docs/building/url-types

Final URL: https://carrd.com/docs/building/url-types

Carrd
DOCUMENTATION
BUILDING
URL Types

Carrd supports linking any button, icon, or other "linkable" element to the following types of URLs:

Site	https://domain.ext/path/	Open an external site, optionally with one or more flags.
Email	mailto:user@domain.ext	Compose a new message to user@domain.ext using the browser's default email app (if available).
Phone	tel:0005551234	Place a call to 0005551234 using the browser's default phone app (if available).
sms:0005551234	Compose a new message to 0005551234 using the browser's default SMS app (if available).
skype:username	Place a Skype call to username (if available).
Browser	browser:back	Go back a page in the browser's history.
browser:forward	Go forward a page in the browser's history.
browser:top	Scroll to the top of the current page.
browser:print	Launch the browser's print dialog.
browser:none	Do nothing. Usually combined with an "On Click" event.
Section	#section-name	Open the section section-name, optionally with one or more flags.
section:next	Open the next section.
section:previous	Open the previous section.
section:first	Open the first section.
section:last	Open the last section.
Scroll Point	#scrollpoint-name	Scroll to the scroll point scrollpoint-name
scrollpoint:next	Scroll to the next scroll point.
scrollpoint:previous	Scroll to the previous scroll point.
scrollpoint:first	Scroll to the first scroll point.
scrollpoint:last	Scroll to the last scroll point.
Clipboard	clipboard:text	Display a dialog allowing the user to copy text to their device clipboard.
Copy	copy:text	Immediately copy text to the user's device clipboard.
File	file:name	Link to the site file associated with name (for example, file:vcard.vcf).
Flags

Flags can be used to change how certain types of URLs behave when linked. They can be included by appending || to the end of the URL followed by a comma-separated list of flags:

https://domain.ext/path/||flag,flag,…

For example, the following indicates the site URL https://vaporware.ext should be opened in a new tab:

https://vaporware.ext||blank

The following flags are currently supported:

Flag	URL Types	Description
blank	Site, Section	Opens the URL in a new tab.
nofollow	Site	Indicates the link to the URL does not imply an endorsement of its content.
noopener	Site	Indicates the URL should not have access to the browser context that opened it.
noreferrer	Site	Indicates the URL should not know the site was its referrer.
me	Site	Indicates the URL is also owned by the site containing the link.
license	Site	Indicates the URL describes the license applicable to the content of the site.
terms	Site	Indicates the URL describes the terms of service applicable to the site.
privacy	Site	Indicates the URL describes the privacy policy applicable to the site.
hreflang=xx	Site	Indicates the language of the URL, where xx is the two-letter language code.
HomeTermsPrivacyContact

© Carrd Inc. All rights reserved.

## Page links

- [Carrd](https://carrd.com/)
- [https://carrd.com/docs/building/url-types#menu](https://carrd.com/docs/building/url-types#menu)
- [https://carrd.com/login](https://carrd.com/login)
- [https://carrd.com/signup](https://carrd.com/signup)
- [https://carrd.com/docs](https://carrd.com/docs)
- [https://carrd.com/docs/general/changelog](https://carrd.com/docs/general/changelog)
- [https://carrd.com/pro](https://carrd.com/pro)
- [https://carrd.com/contact](https://carrd.com/contact)
- [https://carrd.com/docs/building/url-types#menu](https://carrd.com/docs/building/url-types#menu)
- [DOCUMENTATION](https://carrd.com/docs)
- [BUILDING](https://carrd.com/docs/building)
- [flags](https://carrd.com/docs/building/url-types#flags)
- ["On Click" event](https://carrd.com/docs/building/using-advanced-settings)
- [section](https://carrd.com/docs/building/using-sections)
- [flags](https://carrd.com/docs/building/url-types#flags)
- [scroll point](https://carrd.com/docs/building/using-scroll-points)
- [site file](https://carrd.com/docs/sites/customizing-site-files)
- [language code](https://en.wikipedia.org/wiki/List_of_ISO_639_language_codes)
- [General](https://carrd.com/docs/general)
- [Sites](https://carrd.com/docs/sites)
- [Building](https://carrd.com/docs/building)
- [Overview](https://carrd.com/docs/building/overview)
- [Basics](https://carrd.com/docs/building/basics)
- [Keyboard Shortcuts](https://carrd.com/docs/building/keyboard-shortcuts)
- [URL Types](https://carrd.com/docs/building/url-types)
- [Background](https://carrd.com/docs/building/background-element)
- [Page](https://carrd.com/docs/building/page-element)
- [Columns](https://carrd.com/docs/building/organizing-elements-into-columns)
- [Sections](https://carrd.com/docs/building/using-sections)
- [Videos](https://carrd.com/docs/building/adding-videos)
- [Audio](https://carrd.com/docs/building/adding-audio)
- [Scroll Points](https://carrd.com/docs/building/using-scroll-points)
- [Widgets](https://carrd.com/docs/building/adding-widgets)
- [Custom Code](https://carrd.com/docs/building/embedding-custom-code)
- [IFRAMEs](https://carrd.com/docs/building/embedding-iframes)
- [Markdown](https://carrd.com/docs/building/formatting-with-markdown)
- [Mobile Optimization](https://carrd.com/docs/building/optimizing-elements-for-mobile)
- [Element Styles](https://carrd.com/docs/building/using-element-styles)
- [Advanced Settings](https://carrd.com/docs/building/using-advanced-settings)
- [Mobile View](https://carrd.com/docs/building/using-mobile-view)
- [Section View](https://carrd.com/docs/building/using-section-view)
- [Variables](https://carrd.com/docs/building/using-variables)
- [Troubleshooting](https://carrd.com/docs/building/troubleshooting)
- [Forms](https://carrd.com/docs/forms)
- [Account](https://carrd.com/docs/account)
- [Pro](https://carrd.com/docs/pro)
- [Home](https://carrd.com/)
- [Terms](https://carrd.com/terms)
- [Privacy](https://carrd.com/privacy)
- [Contact](https://carrd.com/contact)
