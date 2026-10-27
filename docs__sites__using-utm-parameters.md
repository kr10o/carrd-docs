# Using UTM Parameters - Sites - Documentation - Carrd

Source: https://carrd.com/docs/sites/using-utm-parameters

Final URL: https://carrd.com/docs/sites/using-utm-parameters

Carrd
DOCUMENTATION
SITES
Using UTM Parameters

Requires Pro Standard or higher

UTM parameters are a subset of URL parameters used to track the performance of online marketing campaigns. Here's a quick summary:

utm_source
Tracks the source of the visitor (eg. google).
utm_medium
Tracks the channel of the clicked link (eg. search).
utm_campaign
Tracks the campaign associated with the visit (eg. black_friday).
utm_term
Tracks the search terms or keywords associated with the visit (eg. widget%20sale).
utm_content
Tracks the actual link clicked (eg. buy_now).

Carrd supports UTM parameters in two ways: automatically via form elements, and manually via variables.

Via Form Elements

To automatically include all detected UTM parameters with a form's submissions, enable its Collect UTM parameters option (if available). The values will then be processed based on the form's mode:

Contact
Appends UTM values to the message (eg. UTM Source: banner).
Signup: ActiveCampaign
Populates the custom text input fields UTM_SOURCE, UTM_MEDIUM, UTM_CAMPAIGN, UTM_TERM, and UTM_CONTENT with UTM values.
Signup: beehiiv
Populates the subscriber fields UTM Source, UTM Medium, and UTM Campaign with UTM values.
Signup: Brevo
Populates the text attributes UTM_SOURCE, UTM_MEDIUM, UTM_CAMPAIGN, UTM_TERM, and UTM_CONTENT with UTM values.
Signup: Buttondown
Populates the fields utm_source, utm_medium, utm_campaign, utm_term, and utm_content with UTM values.
Signup: EmailOctopus
Populates the text fields UTM Source, UTM Medium, UTM Campaign, UTM Term, and UTM Content with UTM values.
Signup: GetResponse
Populates the custom text fields utm_source, utm_medium, utm_campaign, utm_term, and utm_content with UTM values.
Signup: Ghost
Not supported.
Signup: HubSpot
Populates the custom contact properties UTM Source, UTM Medium, UTM Campaign, UTM Term, and UTM Content with UTM values.
Signup: Kit
Populates the custom fields UTM Source, UTM Medium, UTM Campaign, UTM Term, and UTM Content with UTM values.
Signup: Klaviyo
Populates the custom properties UTM Source, UTM Medium, UTM Campaign, UTM Term, and UTM Content with UTM values.
Signup: Loops
Populates the contact properties utmSource, utmMedium, utmCampaign, utmTerm, and utmContent with UTM values.
Signup: Mailchimp

Populates the text fields matching the merge tags UTM_SOURCE, UTM_MEDIUM, UTM_CAMPAI, UTM_TERM, and UTM_CONTEN with UTM values.

Merge tags for utm_campaign and utm_content are intentionally truncated to UTM_CAMPAI and UTM_CONTEN respectively to comply with Mailchimp's 10 character limit.
Signup: Mailerlite
Populates the custom fields UTM Source, UTM Medium, UTM Campaign, UTM Term, and UTM Content with UTM values.
Signup: Mailjet
Populates the string contact properties utm_source, utm_medium, utm_campaign, utm_term, and utm_content with UTM values.
Signup: Omnisend
Populates the custom properties utm_source, utm_medium, utm_campaign, utm_term, and utm_content with UTM values.
Signup: Resend
Populates the string contact properties utm_source, utm_medium, utm_campaign, utm_term, and utm_content with UTM values.
Signup: Sender
Populates the custom fields {$utm_source}, {$utm_medium}, {$utm_campaign}, {$utm_term}, and {$utm_content} with UTM values.
Signup: SendFox
Not supported.
Signup: SendGrid
Populates the custom text fields utm_source, utm_medium, utm_campaign, utm_term, and utm_content with UTM values.
Custom
Includes UTM values as fields with IDs matching their respective parameters (eg. utm_source).
Via Variables

Requires Pro Plus or higher

Like other URL parameters, the values of UTM parameters can be accessed and used via variables. For example, linking to the following URL from a button will automatically pass along the values of utm_source and utm_medium:

https://vaporware.ext/?utm_source={{url.utm_source}}&utm_medium={{url.utm_medium}}


HomeTermsPrivacyContact

© Carrd Inc. All rights reserved.

## Page links

- [Carrd](https://carrd.com/)
- [https://carrd.com/docs/sites/using-utm-parameters#menu](https://carrd.com/docs/sites/using-utm-parameters#menu)
- [https://carrd.com/login](https://carrd.com/login)
- [https://carrd.com/signup](https://carrd.com/signup)
- [https://carrd.com/docs](https://carrd.com/docs)
- [https://carrd.com/docs/general/changelog](https://carrd.com/docs/general/changelog)
- [https://carrd.com/pro](https://carrd.com/pro)
- [https://carrd.com/contact](https://carrd.com/contact)
- [https://carrd.com/docs/sites/using-utm-parameters#menu](https://carrd.com/docs/sites/using-utm-parameters#menu)
- [DOCUMENTATION](https://carrd.com/docs)
- [SITES](https://carrd.com/docs/sites)
- [Pro Standard](https://carrd.com/docs/pro/plans#pro-standard)
- [URL parameters](https://support.google.com/google-ads/answer/6277564?hl=en)
- [form elements](https://carrd.com/docs/sites/using-utm-parameters#form-elements)
- [variables](https://carrd.com/docs/sites/using-utm-parameters#variables)
- [custom text input fields](https://www.activecampaign.com/learn/guides/what-are-custom-fields)
- [text attributes](https://help.brevo.com/hc/en-us/articles/209499605-Attribute-the-different-fields-of-your-database)
- [text fields](https://help.emailoctopus.com/article/37-adding-new-fields)
- [custom text fields](https://www.getresponse.com/help/managing-contacts/working-with-custom-fields/how-do-i-create-and-use-custom-fields.html)
- [custom contact properties](https://knowledge.hubspot.com/properties/create-and-edit-properties)
- [custom fields](https://help.kit.com/en/articles/2502504-how-to-add-custom-fields-to-subscribers)
- [custom properties](https://help.klaviyo.com/hc/en-us/articles/115000250912-About-Custom-Properties#add-a-custom-property-yourself2)
- [contact properties](https://loops.so/docs/contacts/properties)
- [text fields](https://mailchimp.com/help/manage-audience-signup-form-fields/)
- [custom fields](https://help.mailerlite.com/article/show/29232-how-to-use-custom-fields)
- [string contact properties](https://documentation.mailjet.com/hc/en-us/articles/360043176353-Creating-and-Managing-Contact-Properties)
- [custom properties](https://support.omnisend.com/en/articles/1061885-custom-properties-for-contacts)
- [string contact properties](https://resend.com/docs/dashboard/audiences/properties)
- [custom fields](https://help.sender.net/knowledgebase/subscribers-management-fields/)
- [custom text fields](https://docs.sendgrid.com/ui/managing-contacts/custom-fields)
- [Pro Plus](https://carrd.com/docs/pro/plans#pro-plus)
- [variables](https://carrd.com/docs/building/using-variables)
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
