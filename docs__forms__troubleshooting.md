# Troubleshooting - Forms - Documentation - Carrd

Source: https://carrd.com/docs/forms/troubleshooting

Final URL: https://carrd.com/docs/forms/troubleshooting

Carrd
DOCUMENTATION
FORMS
Troubleshooting

Requires Pro Standard or higher

My form is getting spam submissions
New signups aren't appearing in my Mailchimp audience
I'm receiving an error when submitting my Mailchimp form
Certain required fields are showing up blank in my Mailchimp audience
Double opt-in isn't working on my MailerLite form
I'm not receiving messages from my contact form (or "Send Email" custom form)
I'm receiving an error when submitting my custom form
I'm receiving an error when submitting my "Send to Airtable" custom form
I'm receiving an error when submitting my "Send to URL" custom form
My form is getting spam submissions

All forms provide basic spam and bot mitigation measures by default. However, if your form is still receiving unwanted submissions, try switching to a different Spam Protection method (such as Cloudflare Turnstile) or if you're working with a contact form, enable its Filter messages option.

New signups aren't appearing in my Mailchimp audience

New signups can sometimes take a little while to appear in your Mailchimp audience (particularly if you've enabled double opt-in). However, if you still aren't seeing anything after 24 hours please get in touch.

I'm receiving an error when submitting my Mailchimp form

This is usually caused by an incorrect API Key or Audience ID. Double check both to ensure they match up exactly with what's shown over at Mailchimp, then try again. If the problem persists, make sure you aren't submitting your form with a "test" email (eg. test@test.com), or an email you've previously subscribed to your audience but manually deleted.

Certain required fields are showing up blank in my Mailchimp audience

If you've changed any of your audience merge tags from their defaults (for example, your First Name field's merge tag is no longer FNAME), reverting back to those defaults should allow those fields to populate correctly.

Double opt-in isn't working on my MailerLite form

If you've enabled double opt-in on your MailerLite form, you may need to also enable double opt-in for API access over at MailerLite if you haven't done so already.

I'm not receiving messages from my contact form (or "Send Email" custom form)

The messages from your form might be landing in your spam/junk folder. If that's the case, marking those messages as "not spam", or simply allowlisting all messages sent from @mail.carrd.site should address the issue. If you're still not receiving messages from your form, ensure the recipient you've assigned to your form (or if you haven't assigned an explicit recipient, your Carrd account email) is working correctly and doesn't have any deliverability issues.

I'm receiving an error when submitting my custom form
Try assigning explicit IDs to each of your fields using only letters, numbers, hyphens, and underscores.
Ensure each of your fields have unique labels and (if assigned) unique IDs as duplicates might throw things off.
If you're trying to dynamically change a Fixed Value using custom code, try using a Hidden field for that instead.
I'm receiving an error when submitting my "Send to Airtable" custom form
Verify your API Key and Base ID are both correct.
Verify Table Name is set to the exact table you're wanting to use (eg. Table1). Note that the name expected here is what's shown in the table's tab at Airtable and not what's shown at the top of the page.
Verify each of your fields' Name values match up exactly with their counterparts at Airtable – right down to their casing and spacing. Any differentiation at all will cause your form to throw an error.
Similarly, if your form uses "Select" fields, ensure their options match up exactly with their counterparts at Airtable. A simple way to do this is to omit the left-hand portion of each option; for example, instead of valueX=Some Option, just use Some Option.
I'm receiving an error when submitting my "Send to URL" custom form

Assuming your URL is otherwise functioning correctly, this can happen if it's not responding with the correct HTTP code. If that's the case, make sure your URL responds with 200 to indicate success, and any other code to indicate failure.

HomeTermsPrivacyContact

© Carrd Inc. All rights reserved.

## Page links

- [Carrd](https://carrd.com/)
- [https://carrd.com/docs/forms/troubleshooting#menu](https://carrd.com/docs/forms/troubleshooting#menu)
- [https://carrd.com/login](https://carrd.com/login)
- [https://carrd.com/signup](https://carrd.com/signup)
- [https://carrd.com/docs](https://carrd.com/docs)
- [https://carrd.com/docs/general/changelog](https://carrd.com/docs/general/changelog)
- [https://carrd.com/pro](https://carrd.com/pro)
- [https://carrd.com/contact](https://carrd.com/contact)
- [https://carrd.com/docs/forms/troubleshooting#menu](https://carrd.com/docs/forms/troubleshooting#menu)
- [DOCUMENTATION](https://carrd.com/docs)
- [FORMS](https://carrd.com/docs/forms)
- [Pro Standard](https://carrd.com/docs/pro/plans#pro-standard)
- [My form is getting spam submissions](https://carrd.com/docs/forms/troubleshooting#getting-spam)
- [New signups aren't appearing in my Mailchimp audience](https://carrd.com/docs/forms/troubleshooting#signup-mailchimp-not-showing)
- [I'm receiving an error when submitting my Mailchimp form](https://carrd.com/docs/forms/troubleshooting#signup-mailchimp-error)
- [Certain required fields are showing up blank in my Mailchimp audience](https://carrd.com/docs/forms/troubleshooting#signup-mailchimp-blank)
- [Double opt-in isn't working on my MailerLite form](https://carrd.com/docs/forms/troubleshooting#signup-mailerlite-double-optin)
- [I'm not receiving messages from my contact form (or "Send Email" custom form)](https://carrd.com/docs/forms/troubleshooting#missing-emails)
- [I'm receiving an error when submitting my custom form](https://carrd.com/docs/forms/troubleshooting#custom-error)
- [I'm receiving an error when submitting my "Send to Airtable" custom form](https://carrd.com/docs/forms/troubleshooting#custom-airtable-error)
- [I'm receiving an error when submitting my "Send to URL" custom form](https://carrd.com/docs/forms/troubleshooting#custom-url-error)
- [contact form](https://carrd.com/docs/forms/setting-up-a-contact-form)
- [get in touch](https://carrd.com/contact)
- [match up exactly with what's shown over at Mailchimp](https://carrd.com/docs/forms/setting-up-a-mailchimp-signup-form)
- [enable double opt-in for API access](https://www.mailerlite.com/help/how-to-use-double-opt-in-when-collecting-subscribers#API)
- [General](https://carrd.com/docs/general)
- [Sites](https://carrd.com/docs/sites)
- [Building](https://carrd.com/docs/building)
- [Forms](https://carrd.com/docs/forms)
- [Contact](https://carrd.com/docs/forms/setting-up-a-contact-form)
- [Signup](https://carrd.com/docs/forms/setting-up-a-signup-form)
- [Custom](https://carrd.com/docs/forms/setting-up-a-custom-form)
- [Payments](https://carrd.com/docs/forms/setting-up-payments)
- [Spam Protection](https://carrd.com/docs/forms/protecting-forms-from-spam-and-bots)
- [Troubleshooting](https://carrd.com/docs/forms/troubleshooting)
- [Account](https://carrd.com/docs/account)
- [Pro](https://carrd.com/docs/pro)
- [Home](https://carrd.com/)
- [Terms](https://carrd.com/terms)
- [Privacy](https://carrd.com/privacy)
- [Contact](https://carrd.com/contact)
