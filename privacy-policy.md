---
layout: page
title: Privacy Policy
description: This is the Privacy Policy for this website.
nav-menu: true
show_tile: false
---

{% capture markdown %}

Effective Date: October 22, 2025 snurftech.com

This Privacy Policy explains how SnurfTech ("I," "me," or "my") collects, uses, and shares information when you visit or use my website, https://snurftech.com. It also details your privacy rights and how I comply with data protection regulations, including through the use of cookies and third-party scripts.

## 1. Information I Collect

I collect information primarily through automated technologies like cookies and external scripts. I do not directly collect personal identifying information (PII) like names, emails, or phone numbers unless you explicitly contact me via the provided email address.

The types of data collected are:

### A. Usage and Analytics Data

This data is collected to measure, analyze, and improve the performance of my website. It includes:

|Type of Information|What it Includes|
|:------------------|:---------------|
|Device and Browser Information|IP address (anonymized), operating system, browser type, and screen resolution.|
|User Behavior|Pages viewed, time spent on pages, navigation paths, and referring website addresses.|
|Geographic Data|General, non-specific location based on anonymized IP address.|

### B. Consent Preferences

I collect and store your explicit preferences regarding the use of non-essential cookies.

## 2. Cookies and Tracking Technologies

I use cookies and other similar tracking technologies (like browser localStorage) on my website.

### A. What Are Cookies?

A cookie is a small text file stored on your device (computer, tablet, or mobile) when you visit a website. These technologies are widely used to make websites work efficiently and to provide reporting and functionality. Cookies can be "persistent" (remain on your device for a set period) or "session" (expire when you close your browser).

### B. How I Use Cookies and Storage Methods

I use cookies and similar storage methods for two primary purposes:

|Type|Name|Provider|Purpose|Storage Method|Duration|
|:---|:---|:-------|:------|:-------------|:-------|
|Strictly Necessary|klaro|snurftech.com|Stores your cookie consent preferences and ensures website security/functionality.|Cookie|30 days|
|Analytics/Performance|\_ga|Google Analytics|Distinguishes unique users and expires if a user does not return.|Cookie|Up to 2 years|
|Analytics/Performance|\_ga\_<GA4_MEASUREMENT_ID>|Google Analytics|Used to persist session state.|Cookie|Up to 2 years|
|Analytics/Performance|\_gid|Google Analytics|Used to track unique users within a single day.|Cookie|24 hours|

> The exact names and number of cookies may change over time.

## 3. Third-Party Services and Data Processing

My website integrates with or relies on third-party services that may collect, process, or store data.

### A. Analytics Provider (Data Processor)

I use Google Analytics 4 (GA4) to track website traffic and user behavior. This is an Analytics/Performance service.

- Data Processed: User behavior, session data, device data, and anonymized IP address (see [Section 1.A](#a-usage-and-analytics-data)).
- Purpose: To measure the success of content, track website performance, and improve the overall user experience.
- Consent: I require your explicit consent to use these cookies.

For more information on how Google processes data, please review [Google’s Privacy & Terms](https://policies.google.com/technologies/partner-sites).

### B. Third-Party Libraries and Scripts

My website utilizes third-party JavaScript libraries to enhance functionality.

|Library/Script|Purpose|Data Processed|
|:-------------|:------|:-------------|
|Marked.js|To efficiently render rich-text content from Markdown files for a better user experience.|Marked.js is an open-source, client-side library and does not inherently collect or transmit any personal data from your device back to the developer or any third party. Its function is purely to process text format within your browser.|

## 4. Legal Basis for Processing

I only process your data when I have a legal basis to do so, primarily:

- Legitimate Interests: Processing data collected via Strictly Necessary Cookies is required for the technical operation and security of the website.
- Consent: Processing data collected via Analytics/Performance Cookies (GA4) is based on your explicit, opt-in consent.

## 5. Your Rights and Choices

### A. Consent Management (Cookies)

Under data protection laws like the GDPR, I must obtain your explicit consent before setting any non-essential cookies.

- Cookie Settings: When you first visit, you are presented with a cookie banner allowing you to Accept all, Reject non-essential, or Manage Preferences.
- Withdrawal of Consent: You can change or withdraw your consent at any time by clicking on the button with a cookie icon (or equivalent text) that is permanently available at the footer of my website.

### B. Browser Settings

You can manage cookies through your web browser settings to block, delete, or view cookies from my site. Blocking all cookies may impact the functionality of the website as strictly necessary cookies will also be affected.

- [Cookie settings in Chrome](https://support.google.com/chrome/answer/95647)
- [Cookie settings in Firefox](https://support.mozilla.org/en-US/kb/enable-and-disable-cookies-website-preferences)
- [Cookie settings in Internet Explorer](https://www.google.com/search?q=https://support.microsoft.com/en-us/windows/delete-and-manage-cookies-168dab11-0753-043d-7c16-ede59475ba6e)
- [Cookie settings in Safari](https://www.google.com/search?q=https://support.apple.com/guide/safari/manage-cookies-and-website-data-sfri11471/mac)

## 6. Updates to this Policy

I may update this Privacy Policy from time to time to reflect changes to my data practices, the services I use, or for legal or regulatory reasons. The updated policy will be posted on this page with a new "Effective Date."

## 7. Contact Me

If you have any questions or concerns about this Privacy Policy, your data, or my use of cookies, please contact me at:

Email: contact@snurftech.com

{% endcapture %}

<!-- Main -->
<div id="main" class="alt">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h1>Privacy Policy</h1>
		</header>

{{ markdown | markdownify }}

</div>
</section>
