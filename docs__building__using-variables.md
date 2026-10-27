# Using Variables - Building - Documentation - Carrd

Source: https://carrd.com/docs/building/using-variables

Final URL: https://carrd.com/docs/building/using-variables

Carrd
DOCUMENTATION
BUILDING
Using Variables

Requires Pro Plus or higher

Variables make it possible to incorporate dynamic content into a site's text, link URLs, form values and more. A variable is generally made up of a name and an optional fallback value:

{{name|fallback}}

The name portion of the variable is the unique name associated with the content (or value) you're trying to include, while the fallback portion is an optional fallback in case the value is blank or the variable doesn't exist. For example, the variable {{url.name}} in the following line of text:

Welcome, {{url.first_name}}!

... will be expanded to the value of url.first_name, which in this case is the first_name URL parameter:

Welcome, Cayce!

Similarly the variable {{url.first_name|friend}} will also be expanded to the contents of the first_name URL parameter, but if it's blank or doesn't exist it'll instead be expanded to the fallback value friend:

Welcome, friend!
Supported Variables

Below is a list of all variables currently supported by Carrd. Variables with a Global scope can be used anywhere variables are supported. All other variables can only be used within their defined scopes.

Some variables require a user interaction before they can expand. For example, form variables such as {{email}}, {{form01.email}}, or {{form01_response.confirmation_id}} will only expand after the user has submitted that specific form.
Scope	Variable	Description
Global	{{url.parameter_name}}	

Contents of the parameter_name URL parameter. Common uses include appending UTM parameters (such as utm_source and utm_medium) to outgoing links, and dynamically populating form fields with default values.


Global	{{client.date}}	

Client's local date in numeric format (eg. 1/3/22).


Global	{{client.time}}	

Client's local time in HH:MM format (eg. 12:34 PM)


Global	{{client.fulldate}}	

Client's local date in string format (eg. January 3, 2022).


Global	{{client.fulltime}}	

Client's local time in HH:MM:SS format (eg. 12:34:56 PM).


Global	{{client.timestamp}}	

Alias of client.utc_timestamp.


Global	{{client.utc_date}}	

UTC date in numeric format (eg. 1/3/22).


Global	{{client.utc_time}}	

UTC time in HH:MM format (eg. 12:34 PM)


Global	{{client.utc_fulldate}}	

UTC date in string format (eg. January 3, 2022).


Global	{{client.utc_fulltime}}	

UTC time in HH:MM:SS format (eg. 12:34:56 PM).


Global	{{client.utc_timestamp}}	

UTC time as a Unix timestamp (eg. 1641213240).


Global	{{form.fieldId}}	

Expands to the value of the last submitted form's fieldId field. Requires Export variables to be enabled on the form.


Global	{{form_response.key}}	

Expands to the value of key from the last submitted form's most recent endpoint response. Requires both Export variables and Return endpoint respones to be enabled on the form.

Responses with multilevel keys are automatically flattened. For example, {{form_response.foo_bar_baz}} will expand to the value of the response key foo.bar.baz.


Global	{{formId.fieldId}}	

Expands to the value of formId's fieldId field. Requires Export variables to be enabled on formId.


Global	{{formId_response.key}}	

Expands to the value of key from formId's most recent endpoint response. Requires both Export variables and Return endpoint respones to be enabled on formId.

Responses with multilevel keys are automatically flattened. For example, {{formId_response.foo_bar_baz}} will expand to the value of the response key foo.bar.baz.


Contact Form	{{name}}	

Value of this form's Name field.


Contact Form	{{email}}	

Value of this form's Email field.


Contact Form	{{message}}	

Value of this form's Message field.


Contact Form	{{company}}	

Value of this form's Company Name field.


Contact Form	{{phone}}	

Value of this form's Phone Number field.


Contact Form	{{subject}}	

Value of this form's Subject field.


Contact Form	{{consent}}	

Value of this form's Require Consent field.


Signup Form	{{email}}	

Value of this form's Email field.


Signup Form	{{fname}}	

Value of this form's First Name field (or Name field if using a single name field).


Signup Form	{{lname}}	

Value of this form's Last Name field.


Signup Form	{{company}}	

Value of this form's Company Name field.


Signup Form	{{phone}}	

Value of this form's Phone Number field.


Signup Form	{{consent}}	

Value of this form's Require Consent field.


Custom Form	{{fieldId}}	

Value of this form's fieldId field.

Supported Elements

Variables are currently supported by the following elements:

Element Type	Where
Buttons	
Labels
Link URLs

Embed	
Code

Form	
Button labels
"On Complete" messages, URLs, and code
"On Success" messages, URLs, and code
"On Failure" messages, URLs, and code
"On Submit" event code
"On Success" event code
"On Failure" event code
(Custom) Input values
(Custom) Input labels

Gallery	
Alternate Text
Captions
Link URLs

Icons	
Link URLs

Image	
Alternate Text
Link URLs

Links	
Labels
Link URLs

List	
Items

Table	
Headings
Rows

Text	
Content
HomeTermsPrivacyContact

© Carrd Inc. All rights reserved.

## Page links

- [Carrd](https://carrd.com/)
- [https://carrd.com/docs/building/using-variables#menu](https://carrd.com/docs/building/using-variables#menu)
- [https://carrd.com/login](https://carrd.com/login)
- [https://carrd.com/signup](https://carrd.com/signup)
- [https://carrd.com/docs](https://carrd.com/docs)
- [https://carrd.com/docs/general/changelog](https://carrd.com/docs/general/changelog)
- [https://carrd.com/pro](https://carrd.com/pro)
- [https://carrd.com/contact](https://carrd.com/contact)
- [https://carrd.com/docs/building/using-variables#menu](https://carrd.com/docs/building/using-variables#menu)
- [DOCUMENTATION](https://carrd.com/docs)
- [BUILDING](https://carrd.com/docs/building)
- [Pro Plus](https://carrd.com/docs/pro/plans#pro-plus)
- [URL parameter](https://support.google.com/google-ads/answer/6277564?hl=en)
- [anywhere variables are supported](https://carrd.com/docs/building/using-variables#supported-elements)
- [URL parameter](https://carrd.com/docs/sites/using-utm-parameters)
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
