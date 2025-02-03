# Task

**Book a Demo Request**

As a potential customer,
I request a demo for the service,
so that I can understand how Strada's Phone AI agents can help my insurance business.

**Success definition:** Given I am on the Strada homepage and I want to learn more about their services
When I click on the 'Book demo' button, fill in my email address, and click 'Book demo' again to submit my request
Then I should see a message confirming that my demo request is being processed.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.getstrada.com/

https://www.getstrada.com/

**Content (before/after):** 

```
RootWebArea Strada | Phone AI agents for insurance, focused, url='https://www.getstrada.com/'
	banner
		[37] link home, center=(385,36), url='https://www.getstrada.com/'
			image, url='https://cdn.prod.website-files.com/642f3c4b127a6c282750acb1/65330a5d2becd649f9caad4a_strada_white_small.svg'
		navigation
```
<details><summary>Show more</summary>

```
	main
		image, url='https://cdn.prod.website-files.com/642f3c4b127a6c282750acb1/673543ad1e500c8638111b74_yc-logo-round.svg'
		StaticText Backed by Y Combinator
		heading Phone AI agents for insurance
			strong
		paragraph
			StaticText Conversational agents that handle phone calls 24/7 for brokers, agencies, and MGAs.
		form Email Form
			[81] textbox Enter email, center=(604,529), contenteditable=True, required, type=email
			[82] button Book demo, center=(821,529), contenteditable=True, type=submit
		image, url='https://cdn.prod.website-files.com/642f3c4b127a6c282750acb1/6735468e009048b8a3821d8e_ring.svg'
		StaticText Lead qualification
		StaticText Prioritize high value leads
		[101] link, center=(684,657), url='https://www.getstrada.com/#'
			image
		StaticText Renewals
		StaticText Increase retention rates
		[118] link, center=(1065,657), url='https://www.getstrada.com/#'
			image
		StaticText Customer support
		StaticText 24/7 with zero hold time
		[135] link, center=(1447,657), url='https://www.getstrada.com/#'
			image
		StaticText Use Cases
		heading Scale with reliable, accurate and humanlike AI
		StaticText Inbound calls
		image
		paragraph
			StaticText Lead qualification and customer support. Answer 100% of your calls.
		StaticText Outbound calls
		image
		paragraph
			StaticText Funnel re-engagement, renewals, collections.
		StaticText Transfers & scheduling
		image
		paragraph
			StaticText Warm transfer to human agents or schedule a callback.
		StaticText Workflows
		image
		paragraph
			StaticText Automate actions in your CRM and internal systems.
		StaticText Integrations
		heading Connected to your tools
		list
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/652f12a7194f8c2f114af952_hubspot.svg'
				StaticText Hubspot
				StaticText CRM
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/65b1b3213ee194e29c2997cd_salesforce.svg'
				StaticText Salesforce
				StaticText CRM
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/67564a751a56371c868ed6d4_dialpad.svg'
				StaticText Dialpad
				StaticText Contact Center
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/672aac159d7adbc8edb83b7f_talkdesk.svg'
				StaticText Talkdesk
				StaticText Contact Center
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/65b1b35ff53b196d6f4712a6_slack.svg'
				StaticText Slack
				StaticText Messaging
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/65affc54a2a606227aa4839c_zendesk.svg'
				StaticText Zendesk
				StaticText Support
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/660b71053d2aa9315e9afa5f_rest-api-130x130.svg'
				StaticText Custom API
				StaticText Various
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/65076d869d60b1182ec9bf20_plus.svg'
				StaticText More
				StaticText Various
	contentinfo
		link Logo link, url='https://www.getstrada.com/'
			image Logo link, url='https://cdn.prod.website-files.com/642f3c4b127a6c282750acb1/652568a19553563a85d049b8_All_470x120%20White.svg'
		StaticText Follow us
		link LinkedIn, url='https://www.linkedin.com/company/getstrada/'
		link Twitter, url='https://twitter.com/stradaHQ'
		link, url='https://www.getstrada.com/reset-password'
		link, url='https://www.getstrada.com/access-denied'
		link, url='https://www.getstrada.com/user-account'
		image, url='https://cdn.prod.website-files.com/642f3c4b127a6c282750acb1/6768b92b06432a90051ee963_soc2-vanta.svg'
		StaticText © 2024 Strada API, Inc.
		link Privacy Policy, url='https://www.getstrada.com/legal/privacy-policy'
		link Terms, url='https://www.getstrada.com/legal/terms'
```
</details>



```
RootWebArea Strada | Phone AI agents for insurance, focused, url='https://www.getstrada.com/'
	alert Please fill out this field., atomic
	banner
		[37] link home, center=(385,36), url='https://www.getstrada.com/'
			image, url='https://cdn.prod.website-files.com/642f3c4b127a6c282750acb1/65330a5d2becd649f9caad4a_strada_white_small.svg'
```
<details><summary>Show more</summary>

```
		navigation
	main
		image, url='https://cdn.prod.website-files.com/642f3c4b127a6c282750acb1/673543ad1e500c8638111b74_yc-logo-round.svg'
		StaticText Backed by Y Combinator
		heading Phone AI agents for insurance
			strong
		paragraph
			StaticText Conversational agents that handle phone calls 24/7 for brokers, agencies, and MGAs.
		form Email Form
			[81] textbox Enter email, center=(604,529), contenteditable=True, focused, required, type=email
			[82] button Book demo, center=(821,529), contenteditable=True, type=submit
		image, url='https://cdn.prod.website-files.com/642f3c4b127a6c282750acb1/6735468e009048b8a3821d8e_ring.svg'
		StaticText Lead qualification
		StaticText Prioritize high value leads
		[101] link, center=(684,657), url='https://www.getstrada.com/#'
			image
		StaticText Renewals
		StaticText Increase retention rates
		[118] link, center=(1065,657), url='https://www.getstrada.com/#'
			image
		StaticText Customer support
		StaticText 24/7 with zero hold time
		[135] link, center=(1447,657), url='https://www.getstrada.com/#'
			image
		StaticText Use Cases
		heading Scale with reliable, accurate and humanlike AI
		StaticText Inbound calls
		image
		paragraph
			StaticText Lead qualification and customer support. Answer 100% of your calls.
		StaticText Outbound calls
		image
		paragraph
			StaticText Funnel re-engagement, renewals, collections.
		StaticText Transfers & scheduling
		image
		paragraph
			StaticText Warm transfer to human agents or schedule a callback.
		StaticText Workflows
		image
		paragraph
			StaticText Automate actions in your CRM and internal systems.
		StaticText Integrations
		heading Connected to your tools
		list
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/652f12a7194f8c2f114af952_hubspot.svg'
				StaticText Hubspot
				StaticText CRM
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/65b1b3213ee194e29c2997cd_salesforce.svg'
				StaticText Salesforce
				StaticText CRM
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/67564a751a56371c868ed6d4_dialpad.svg'
				StaticText Dialpad
				StaticText Contact Center
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/672aac159d7adbc8edb83b7f_talkdesk.svg'
				StaticText Talkdesk
				StaticText Contact Center
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/65b1b35ff53b196d6f4712a6_slack.svg'
				StaticText Slack
				StaticText Messaging
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/65affc54a2a606227aa4839c_zendesk.svg'
				StaticText Zendesk
				StaticText Support
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/660b71053d2aa9315e9afa5f_rest-api-130x130.svg'
				StaticText Custom API
				StaticText Various
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/65076d869d60b1182ec9bf20_plus.svg'
				StaticText More
				StaticText Various
	contentinfo
		link Logo link, url='https://www.getstrada.com/'
			image Logo link, url='https://cdn.prod.website-files.com/642f3c4b127a6c282750acb1/652568a19553563a85d049b8_All_470x120%20White.svg'
		StaticText Follow us
		link LinkedIn, url='https://www.linkedin.com/company/getstrada/'
		link Twitter, url='https://twitter.com/stradaHQ'
		link, url='https://www.getstrada.com/reset-password'
		link, url='https://www.getstrada.com/access-denied'
		link, url='https://www.getstrada.com/user-account'
		image, url='https://cdn.prod.website-files.com/642f3c4b127a6c282750acb1/6768b92b06432a90051ee963_soc2-vanta.svg'
		StaticText © 2024 Strada API, Inc.
		link Privacy Policy, url='https://www.getstrada.com/legal/privacy-policy'
		link Terms, url='https://www.getstrada.com/legal/terms'
```
</details>

**Reasoning for action:** Clicking on the 'Book demo' button is the initial crucial step in requesting a demo. By doing so, it allows me to access the email input form that I need to fill out to proceed with submitting my request for a demo. This action advances the task by moving me to the next necessary step to achieve confirmation of my demo request.

**Action:** click(82) # Click on the 'Book demo' button to explore further.

**Change Description:** After clicking the 'Book demo' button, the textbox for entering the email became focused, and an alert was triggered prompting the user to fill out the required email field.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://www.getstrada.com/

https://www.getstrada.com/

**Content (before/after):** 

```
RootWebArea Strada | Phone AI agents for insurance, focused, url='https://www.getstrada.com/'
	alert Please fill out this field., atomic
	banner
		[37] link home, center=(385,36), url='https://www.getstrada.com/'
			image, url='https://cdn.prod.website-files.com/642f3c4b127a6c282750acb1/65330a5d2becd649f9caad4a_strada_white_small.svg'
```
<details><summary>Show more</summary>

```
		navigation
	main
		image, url='https://cdn.prod.website-files.com/642f3c4b127a6c282750acb1/673543ad1e500c8638111b74_yc-logo-round.svg'
		StaticText Backed by Y Combinator
		heading Phone AI agents for insurance
			strong
		paragraph
			StaticText Conversational agents that handle phone calls 24/7 for brokers, agencies, and MGAs.
		form Email Form
			[81] textbox Enter email, center=(604,529), contenteditable=True, focused, required, type=email
			[82] button Book demo, center=(821,529), contenteditable=True, type=submit
		image, url='https://cdn.prod.website-files.com/642f3c4b127a6c282750acb1/6735468e009048b8a3821d8e_ring.svg'
		StaticText Lead qualification
		StaticText Prioritize high value leads
		[101] link, center=(684,657), url='https://www.getstrada.com/#'
			image
		StaticText Renewals
		StaticText Increase retention rates
		[118] link, center=(1065,657), url='https://www.getstrada.com/#'
			image
		StaticText Customer support
		StaticText 24/7 with zero hold time
		[135] link, center=(1447,657), url='https://www.getstrada.com/#'
			image
		StaticText Use Cases
		heading Scale with reliable, accurate and humanlike AI
		StaticText Inbound calls
		image
		paragraph
			StaticText Lead qualification and customer support. Answer 100% of your calls.
		StaticText Outbound calls
		image
		paragraph
			StaticText Funnel re-engagement, renewals, collections.
		StaticText Transfers & scheduling
		image
		paragraph
			StaticText Warm transfer to human agents or schedule a callback.
		StaticText Workflows
		image
		paragraph
			StaticText Automate actions in your CRM and internal systems.
		StaticText Integrations
		heading Connected to your tools
		list
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/652f12a7194f8c2f114af952_hubspot.svg'
				StaticText Hubspot
				StaticText CRM
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/65b1b3213ee194e29c2997cd_salesforce.svg'
				StaticText Salesforce
				StaticText CRM
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/67564a751a56371c868ed6d4_dialpad.svg'
				StaticText Dialpad
				StaticText Contact Center
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/672aac159d7adbc8edb83b7f_talkdesk.svg'
				StaticText Talkdesk
				StaticText Contact Center
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/65b1b35ff53b196d6f4712a6_slack.svg'
				StaticText Slack
				StaticText Messaging
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/65affc54a2a606227aa4839c_zendesk.svg'
				StaticText Zendesk
				StaticText Support
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/660b71053d2aa9315e9afa5f_rest-api-130x130.svg'
				StaticText Custom API
				StaticText Various
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/65076d869d60b1182ec9bf20_plus.svg'
				StaticText More
				StaticText Various
	contentinfo
		link Logo link, url='https://www.getstrada.com/'
			image Logo link, url='https://cdn.prod.website-files.com/642f3c4b127a6c282750acb1/652568a19553563a85d049b8_All_470x120%20White.svg'
		StaticText Follow us
		link LinkedIn, url='https://www.linkedin.com/company/getstrada/'
		link Twitter, url='https://twitter.com/stradaHQ'
		link, url='https://www.getstrada.com/reset-password'
		link, url='https://www.getstrada.com/access-denied'
		link, url='https://www.getstrada.com/user-account'
		image, url='https://cdn.prod.website-files.com/642f3c4b127a6c282750acb1/6768b92b06432a90051ee963_soc2-vanta.svg'
		StaticText © 2024 Strada API, Inc.
		link Privacy Policy, url='https://www.getstrada.com/legal/privacy-policy'
		link Terms, url='https://www.getstrada.com/legal/terms'
```
</details>



```
RootWebArea Strada | Phone AI agents for insurance, focused, url='https://www.getstrada.com/'
	banner
		[37] link home, center=(385,36), url='https://www.getstrada.com/'
			image, url='https://cdn.prod.website-files.com/642f3c4b127a6c282750acb1/65330a5d2becd649f9caad4a_strada_white_small.svg'
		navigation
```
<details><summary>Show more</summary>

```
	main
		image, url='https://cdn.prod.website-files.com/642f3c4b127a6c282750acb1/673543ad1e500c8638111b74_yc-logo-round.svg'
		StaticText Backed by Y Combinator
		heading Phone AI agents for insurance
			strong
		paragraph
			StaticText Conversational agents that handle phone calls 24/7 for brokers, agencies, and MGAs.
		form Email Form
			[81] textbox Enter email value='example@example.com', center=(604,529), contenteditable=True, focused, required, type=email
			[82] button Book demo, center=(821,529), contenteditable=True, type=submit
		image, url='https://cdn.prod.website-files.com/642f3c4b127a6c282750acb1/6735468e009048b8a3821d8e_ring.svg'
		StaticText Lead qualification
		StaticText Prioritize high value leads
		[101] link, center=(684,657), url='https://www.getstrada.com/#'
			image
		StaticText Renewals
		StaticText Increase retention rates
		[118] link, center=(1065,657), url='https://www.getstrada.com/#'
			image
		StaticText Customer support
		StaticText 24/7 with zero hold time
		[135] link, center=(1447,657), url='https://www.getstrada.com/#'
			image
		StaticText Use Cases
		heading Scale with reliable, accurate and humanlike AI
		StaticText Inbound calls
		image
		paragraph
			StaticText Lead qualification and customer support. Answer 100% of your calls.
		StaticText Outbound calls
		image
		paragraph
			StaticText Funnel re-engagement, renewals, collections.
		StaticText Transfers & scheduling
		image
		paragraph
			StaticText Warm transfer to human agents or schedule a callback.
		StaticText Workflows
		image
		paragraph
			StaticText Automate actions in your CRM and internal systems.
		StaticText Integrations
		heading Connected to your tools
		list
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/652f12a7194f8c2f114af952_hubspot.svg'
				StaticText Hubspot
				StaticText CRM
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/65b1b3213ee194e29c2997cd_salesforce.svg'
				StaticText Salesforce
				StaticText CRM
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/67564a751a56371c868ed6d4_dialpad.svg'
				StaticText Dialpad
				StaticText Contact Center
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/672aac159d7adbc8edb83b7f_talkdesk.svg'
				StaticText Talkdesk
				StaticText Contact Center
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/65b1b35ff53b196d6f4712a6_slack.svg'
				StaticText Slack
				StaticText Messaging
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/65affc54a2a606227aa4839c_zendesk.svg'
				StaticText Zendesk
				StaticText Support
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/660b71053d2aa9315e9afa5f_rest-api-130x130.svg'
				StaticText Custom API
				StaticText Various
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/65076d869d60b1182ec9bf20_plus.svg'
				StaticText More
				StaticText Various
	contentinfo
		link Logo link, url='https://www.getstrada.com/'
			image Logo link, url='https://cdn.prod.website-files.com/642f3c4b127a6c282750acb1/652568a19553563a85d049b8_All_470x120%20White.svg'
		StaticText Follow us
		link LinkedIn, url='https://www.linkedin.com/company/getstrada/'
		link Twitter, url='https://twitter.com/stradaHQ'
		link, url='https://www.getstrada.com/reset-password'
		link, url='https://www.getstrada.com/access-denied'
		link, url='https://www.getstrada.com/user-account'
		image, url='https://cdn.prod.website-files.com/642f3c4b127a6c282750acb1/6768b92b06432a90051ee963_soc2-vanta.svg'
		StaticText © 2024 Strada API, Inc.
		link Privacy Policy, url='https://www.getstrada.com/legal/privacy-policy'
		link Terms, url='https://www.getstrada.com/legal/terms'
```
</details>

**Reasoning for action:** Filling in the email field is essential to move forward with the demo request process. Since the email field is required to submit the form, providing a valid format as a placeholder (example@example.com) permits the next action of clicking the 'Book demo' button to proceed the request. This step significantly advances the task, as it sets up the necessary information for me to submit the demo booking.

**Action:** fill(81, 'example@example.com') # Fill in the email field with a placeholder email address.

**Change Description:** The email input field in the form was filled with the placeholder email address 'example@example.com', updating its value from empty to reflect the new content, while the field remained focused and retained its required status.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://www.getstrada.com/

https://www.getstrada.com/

**Content (before/after):** 

```
RootWebArea Strada | Phone AI agents for insurance, focused, url='https://www.getstrada.com/'
	banner
		[37] link home, center=(385,36), url='https://www.getstrada.com/'
			image, url='https://cdn.prod.website-files.com/642f3c4b127a6c282750acb1/65330a5d2becd649f9caad4a_strada_white_small.svg'
		navigation
```
<details><summary>Show more</summary>

```
	main
		image, url='https://cdn.prod.website-files.com/642f3c4b127a6c282750acb1/673543ad1e500c8638111b74_yc-logo-round.svg'
		StaticText Backed by Y Combinator
		heading Phone AI agents for insurance
			strong
		paragraph
			StaticText Conversational agents that handle phone calls 24/7 for brokers, agencies, and MGAs.
		form Email Form
			[81] textbox Enter email value='example@example.com', center=(604,529), contenteditable=True, focused, required, type=email
			[82] button Book demo, center=(821,529), contenteditable=True, type=submit
		image, url='https://cdn.prod.website-files.com/642f3c4b127a6c282750acb1/6735468e009048b8a3821d8e_ring.svg'
		StaticText Lead qualification
		StaticText Prioritize high value leads
		[101] link, center=(684,657), url='https://www.getstrada.com/#'
			image
		StaticText Renewals
		StaticText Increase retention rates
		[118] link, center=(1065,657), url='https://www.getstrada.com/#'
			image
		StaticText Customer support
		StaticText 24/7 with zero hold time
		[135] link, center=(1447,657), url='https://www.getstrada.com/#'
			image
		StaticText Use Cases
		heading Scale with reliable, accurate and humanlike AI
		StaticText Inbound calls
		image
		paragraph
			StaticText Lead qualification and customer support. Answer 100% of your calls.
		StaticText Outbound calls
		image
		paragraph
			StaticText Funnel re-engagement, renewals, collections.
		StaticText Transfers & scheduling
		image
		paragraph
			StaticText Warm transfer to human agents or schedule a callback.
		StaticText Workflows
		image
		paragraph
			StaticText Automate actions in your CRM and internal systems.
		StaticText Integrations
		heading Connected to your tools
		list
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/652f12a7194f8c2f114af952_hubspot.svg'
				StaticText Hubspot
				StaticText CRM
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/65b1b3213ee194e29c2997cd_salesforce.svg'
				StaticText Salesforce
				StaticText CRM
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/67564a751a56371c868ed6d4_dialpad.svg'
				StaticText Dialpad
				StaticText Contact Center
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/672aac159d7adbc8edb83b7f_talkdesk.svg'
				StaticText Talkdesk
				StaticText Contact Center
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/65b1b35ff53b196d6f4712a6_slack.svg'
				StaticText Slack
				StaticText Messaging
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/65affc54a2a606227aa4839c_zendesk.svg'
				StaticText Zendesk
				StaticText Support
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/660b71053d2aa9315e9afa5f_rest-api-130x130.svg'
				StaticText Custom API
				StaticText Various
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/65076d869d60b1182ec9bf20_plus.svg'
				StaticText More
				StaticText Various
	contentinfo
		link Logo link, url='https://www.getstrada.com/'
			image Logo link, url='https://cdn.prod.website-files.com/642f3c4b127a6c282750acb1/652568a19553563a85d049b8_All_470x120%20White.svg'
		StaticText Follow us
		link LinkedIn, url='https://www.linkedin.com/company/getstrada/'
		link Twitter, url='https://twitter.com/stradaHQ'
		link, url='https://www.getstrada.com/reset-password'
		link, url='https://www.getstrada.com/access-denied'
		link, url='https://www.getstrada.com/user-account'
		image, url='https://cdn.prod.website-files.com/642f3c4b127a6c282750acb1/6768b92b06432a90051ee963_soc2-vanta.svg'
		StaticText © 2024 Strada API, Inc.
		link Privacy Policy, url='https://www.getstrada.com/legal/privacy-policy'
		link Terms, url='https://www.getstrada.com/legal/terms'
```
</details>



```
RootWebArea Strada | Phone AI agents for insurance, focused, url='https://www.getstrada.com/'
	banner
		[37] link home, center=(385,36), url='https://www.getstrada.com/'
			image, url='https://cdn.prod.website-files.com/642f3c4b127a6c282750acb1/65330a5d2becd649f9caad4a_strada_white_small.svg'
		navigation
```
<details><summary>Show more</summary>

```
	main
		image, url='https://cdn.prod.website-files.com/642f3c4b127a6c282750acb1/673543ad1e500c8638111b74_yc-logo-round.svg'
		StaticText Backed by Y Combinator
		heading Phone AI agents for insurance
			strong
		paragraph
			StaticText Conversational agents that handle phone calls 24/7 for brokers, agencies, and MGAs.
		form Email Form
			[81] textbox Enter email value='example@example.com', center=(604,529), contenteditable=True, required, type=email
			[82] button Please wait..., center=(828,529), type=submit
		image, url='https://cdn.prod.website-files.com/642f3c4b127a6c282750acb1/6735468e009048b8a3821d8e_ring.svg'
		StaticText Lead qualification
		StaticText Prioritize high value leads
		[101] link, center=(684,657), url='https://www.getstrada.com/#'
			image
		StaticText Renewals
		StaticText Increase retention rates
		[118] link, center=(1065,657), url='https://www.getstrada.com/#'
			image
		StaticText Customer support
		StaticText 24/7 with zero hold time
		[135] link, center=(1447,657), url='https://www.getstrada.com/#'
			image
		StaticText Use Cases
		heading Scale with reliable, accurate and humanlike AI
		StaticText Inbound calls
		image
		paragraph
			StaticText Lead qualification and customer support. Answer 100% of your calls.
		StaticText Outbound calls
		image
		paragraph
			StaticText Funnel re-engagement, renewals, collections.
		StaticText Transfers & scheduling
		image
		paragraph
			StaticText Warm transfer to human agents or schedule a callback.
		StaticText Workflows
		image
		paragraph
			StaticText Automate actions in your CRM and internal systems.
		StaticText Integrations
		heading Connected to your tools
		list
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/652f12a7194f8c2f114af952_hubspot.svg'
				StaticText Hubspot
				StaticText CRM
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/65b1b3213ee194e29c2997cd_salesforce.svg'
				StaticText Salesforce
				StaticText CRM
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/67564a751a56371c868ed6d4_dialpad.svg'
				StaticText Dialpad
				StaticText Contact Center
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/672aac159d7adbc8edb83b7f_talkdesk.svg'
				StaticText Talkdesk
				StaticText Contact Center
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/65b1b35ff53b196d6f4712a6_slack.svg'
				StaticText Slack
				StaticText Messaging
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/65affc54a2a606227aa4839c_zendesk.svg'
				StaticText Zendesk
				StaticText Support
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/660b71053d2aa9315e9afa5f_rest-api-130x130.svg'
				StaticText Custom API
				StaticText Various
			listitem
				image, url='https://cdn.prod.website-files.com/642f3c4c127a6c7eda50acde/65076d869d60b1182ec9bf20_plus.svg'
				StaticText More
				StaticText Various
	contentinfo
		link Logo link, url='https://www.getstrada.com/'
			image Logo link, url='https://cdn.prod.website-files.com/642f3c4b127a6c282750acb1/652568a19553563a85d049b8_All_470x120%20White.svg'
		StaticText Follow us
		link LinkedIn, url='https://www.linkedin.com/company/getstrada/'
		link Twitter, url='https://twitter.com/stradaHQ'
		link, url='https://www.getstrada.com/reset-password'
		link, url='https://www.getstrada.com/access-denied'
		link, url='https://www.getstrada.com/user-account'
		image, url='https://cdn.prod.website-files.com/642f3c4b127a6c282750acb1/6768b92b06432a90051ee963_soc2-vanta.svg'
		StaticText © 2024 Strada API, Inc.
		link Privacy Policy, url='https://www.getstrada.com/legal/privacy-policy'
		link Terms, url='https://www.getstrada.com/legal/terms'
```
</details>

**Reasoning for action:** I first identified that I needed to click the 'Book demo' button (element 82) after entering an email address in the textbox. This action submits the form, which is essential for registering my demo request with Strada. By completing this step, I move closer to fulfilling the user story, as it effectively conveys my intent to learn more about Strada's Phone AI agents for my insurance business.

**Action:** click(82) # Click on the 'Book demo' button to submit the email and proceed with booking the demo.

**Change Description:** After the action of clicking the 'Book demo' button, the button text changed from 'Book demo' to 'Please wait...', indicating that the email submission process is in progress.

**Screenshot before:****Screenshot after:**---

