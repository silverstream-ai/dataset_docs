# Task

**User Journey for Octolane AI Pricing**

As a potential customer interested in Octolane AI,
I understand the pricing structure and plans available,
so that I can select the best subscription option that fits my needs.

**Success definition:** Given I am on the Octolane AI homepage
When I click on the 'Pricing' link
Then I should be directed to the Pricing page and see available plans including 'Best Friend' and 'Enterprise'.
And when I click on 'Get started today' for the Best Friend plan,
Then I should see the Stripe checkout page with subscription details and payment options.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.octolane.com/

https://www.octolane.com/about

**Content (before/after):** 

```
RootWebArea Octolane AI, focused, url='https://www.octolane.com/'
	banner
		navigation Main
			list
				listitem
```
<details><summary>Show more</summary>

```
					[104] link, center=(840,36), url='https://www.octolane.com/'
						image
				listitem
					[107] link About, center=(952,36), url='https://www.octolane.com/about'
				listitem
					[109] link Pricing, center=(1032,36), url='https://www.octolane.com/pricing'
				listitem
					[111] link Log in, center=(1114,36), url='https://www.octolane.com/auth/sign-in'
	region Notifications alt+T
	region What AI Salesforce should have been
		heading What AI Salesforce should have been
		paragraph
			StaticText Instead of a system of records,
			StaticText Octolane AI is a system of actions
		[122] link Book Demo, center=(960,476), url='https://form.octolane.com/df48522e-515f-417b-9faf-d622f4735a75'
			button Book Demo
		list
			listitem
				image Customer - Arc, url='https://www.octolane.com/assets/logos/arc.svg'
			listitem
				image Customer - Mintlify, url='https://www.octolane.com/assets/images/mintlify.svg'
			listitem
				image Customer - Helicone AI, url='https://www.octolane.com/assets/images/helicone.svg'
			[137] listitem, center=(483,553)
				image Customer - Growpay, url='https://www.octolane.com/_next/image?url=%2Fassets%2Flogos%2Fgrowpay_logo.png&w=64&q=75'
			[140] listitem, center=(607,553)
				image Customer - Octane Security, url='https://www.octolane.com/assets/images/octane.svg'
			[143] listitem, center=(731,553)
				image Customer - Fondo, url='https://www.octolane.com/_next/image?url=%2Fassets%2Flogos%2Ffondo.png&w=64&q=75'
			[146] listitem, center=(855,553)
				image Customer - Retail Ready AI, url='https://www.octolane.com/_next/image?url=%2Fassets%2Flogos%2Fretailreadyai.png&w=64&q=75'
			[149] listitem, center=(979,553)
				image Customer - Rebill, url='https://www.octolane.com/assets/logos/rebill.svg'
			[152] listitem, center=(1103,553)
				image Customer - Retell AI, url='https://www.octolane.com/assets/logos/retellai.svg'
			[155] listitem, center=(1227,553)
				image Customer - Upsolve AI, url='https://www.octolane.com/_next/image?url=%2Fassets%2Flogos%2Fupsolveai.webp&w=64&q=75'
			[158] listitem, center=(1351,553)
				image Customer - Momentic AI, url='https://www.octolane.com/assets/logos/momenticai.svg'
		region Hero Image of the website
			image A preview of the Octolane web app, url='https://www.octolane.com/_next/image?url=%2Fassets%2Fimages%2Fscreenshot1.jpg&w=3840&q=75'
	textbox Tech startup doing gen ai at sf.. value='Tech startup growing fast seed stage at SF', disabled=True
	button AI Search
	button Tech startup growing fast seed stage at SF
	button Companies working on advanced ai search less than 3 years old
	figure
		image Two employees working with computers, url='https://www.octolane.com/_next/image?url=%2Fassets%2Fimages%2F6.webp&w=640&q=75'
		Figcaption
			StaticText Our team hard at work
	figure
		image At Y Combinator office, url='https://www.octolane.com/_next/image?url=%2Fassets%2Fimages%2F9.webp&w=640&q=75'
		Figcaption
			StaticText At Y Combinator office
	figure
		image Picture of the Fraumunster Zurich, url='https://www.octolane.com/_next/image?url=%2Fassets%2Fimages%2F3.webp&w=640&q=75'
		Figcaption
			StaticText Meetings and moments that matter.
	figure
		image Team having a break in the lunch room, url='https://www.octolane.com/_next/image?url=%2Fassets%2Fimages%2F10.webp&w=640&q=75'
		Figcaption
			StaticText Our friend Bisco is the best!
	figure
		image Person with headphones, url='https://www.octolane.com/_next/image?url=%2Fassets%2Fimages%2F11.webp&w=640&q=75'
		Figcaption
			StaticText Perfect playlist for late night coding sessions
	figure
		image Picture of a party with confetti, url='https://www.octolane.com/_next/image?url=%2Fassets%2Fimages%2Fbatch.webp&w=1920&q=75'
		Figcaption
			StaticText Our YC W24 batch is the best batch!
	region Our Vision
		heading Our Vision
		paragraph
			StaticText Every other CRM on the market previously built a
			strong
				StaticText system of records
			StaticText , that changes now. Instead of a system of records, now it’s possible to build a
			strong
				StaticText system of actions
			StaticText thanks to AI.
		paragraph
			StaticText Octolane is building AI-first Salesforce. Our software does a lot more than just storing customer data. It predicts your next actions and takes care of that for you. It uses AI to find the best customers, does lead scoring, reaches out to them and closes them. You can also generate any forecasts or reports from thousands of data points with one click or natural language command. You can communicate with hundreds of customers at the same time and predict their next actions.
		paragraph
			StaticText Customers are switching from HubSpot to us after spending thousands of dollars on their implementation.
		paragraph
			StaticText We are using AI to automate writing many of the integrations that keep customers locked into Salesforce and then we are going to take all of their customers too. Killing Salesforce is a $300 billion market cap opportunity that is just waiting for someone to finally grab it.
		paragraph
			StaticText Also, no one works at Salesforce office after 4pm and I am here at our office on a Saturday afternoon on boarding a series B customer while fixing our scalability issues and my co-founder is not gonna sleep until we fix every single GitHub issues. I asked him to go to sleep because he is tired, but he is just not gonna do it. He is built different.
		paragraph
			StaticText Why?
		paragraph
			StaticText Because we don’t have enough. Our dream companies are still their clients. My co-founder and I are best friends for 10+ years and we are first generation immigrant. I dropped out of Duke from a full scholarship program to do things that seems impossible and to help others.
		paragraph
			StaticText Today, at this very moment, we are going through once in a lifetime opportunity and the industry is moving faster than we can possibly imagine.
		paragraph
			StaticText Who wouldn’t jump on this rocket ship?
		paragraph
			StaticText – Octolane Team
		link View Open Roles, url='https://app.withrapha.com/job/369?r=ddca0a9f-d55f-4b64-9075-971e44dfcb18'
			button View Open Roles
	contentinfo
		paragraph
			StaticText Email our team for early access to one@octolane.com
		StaticText “You need three things to create a successful startup: to start with good people, to make something customers actually want, and to spend as little money as possible.” ― Paul Graham
		StaticText Backed by
		StaticText ·
		StaticText Y Combinator
		heading Product
		list Quick links Product
			listitem
				link Enterprise, url='https://www.octolane.com/pricing'
			listitem
				link Pricing, url='https://www.octolane.com/pricing'
			listitem
				link Docs, url='https://docs.octolane.com/'
		heading Social
		list Quick links Resources
			listitem
				link Twitter, url='https://twitter.com/octolane_ai'
			listitem
				link LinkedIn, url='https://www.linkedin.com/company/octolane'
		heading Company
		list Quick links Company
			listitem
				link About, url='https://www.octolane.com/about'
			listitem
				link Status, url='https://status.octolane.com/'
			listitem
				link Security, url='https://www.octolane.com/security'
		heading Legal
		list Quick links Legal
			listitem
				link Privacy, url='https://www.octolane.com/privacy-policy'
			listitem
				link Terms, url='https://www.octolane.com/terms'
			listitem
				link Subprocessors, url='https://www.octolane.com/subprocessor'
			listitem
				link DPA, url='https://drive.google.com/file/d/10_KYVEw1p7UlhuvFIP6oFQd_ZOT4Ix-0/view?usp=sharing'
		paragraph
			StaticText ©
			StaticText 2025
			StaticText Octolane AI, Inc. All rights reserved.
		StaticText All systems operational
	alert, atomic
```
</details>



```
RootWebArea Octolane AI, focused, url='https://www.octolane.com/about'
	banner
		navigation Main
			list
				listitem
```
<details><summary>Show more</summary>

```
					[104] link, center=(840,36), url='https://www.octolane.com/'
						image
				listitem
					[107] link About, center=(952,36), focused, url='https://www.octolane.com/about'
				listitem
					[109] link Pricing, center=(1032,36), url='https://www.octolane.com/pricing'
				listitem
					[111] link Log in, center=(1114,36), url='https://www.octolane.com/auth/sign-in'
	region Notifications alt+T
	main
		region Building the AI CRM we always wanted, because why settle for less when you can have it all?
			heading Building the AI CRM we always wanted, because why settle for less when you can have it all?
		figure
			image Two employees working with computers, url='https://www.octolane.com/_next/image?url=%2Fassets%2Fimages%2F6.webp&w=640&q=75'
			Figcaption
				StaticText Our team hard at work
		figure
			image At Y Combinator office, url='https://www.octolane.com/_next/image?url=%2Fassets%2Fimages%2F9.webp&w=640&q=75'
			Figcaption
				StaticText At Y Combinator office
		figure
			image Picture of the Fraumunster Zurich, url='https://www.octolane.com/_next/image?url=%2Fassets%2Fimages%2F3.webp&w=640&q=75'
			Figcaption
				StaticText Meetings and moments that matter.
		figure
			image Team having a break in the lunch room, url='https://www.octolane.com/_next/image?url=%2Fassets%2Fimages%2F10.webp&w=640&q=75'
			Figcaption
				StaticText Our friend Bisco is the best!
		figure
			image Person with headphones, url='https://www.octolane.com/_next/image?url=%2Fassets%2Fimages%2F11.webp&w=640&q=75'
			Figcaption
				StaticText Perfect playlist for late night coding sessions
		figure
			image Picture of a party with confetti, url='https://www.octolane.com/_next/image?url=%2Fassets%2Fimages%2Fbatch.webp&w=1920&q=75'
			Figcaption
				StaticText Our YC W24 batch is the best batch!
		region Our Vision
			heading Our Vision
			paragraph
				StaticText Every other CRM on the market previously built a
				strong
					StaticText system of records
				StaticText , that changes now. Instead of a system of records, now it’s possible to build a
				strong
					StaticText system of actions
				StaticText thanks to AI.
			paragraph
				StaticText Octolane is building AI-first Salesforce. Our software does a lot more than just storing customer data. It predicts your next actions and takes care of that for you. It uses AI to find the best customers, does lead scoring, reaches out to them and closes them. You can also generate any forecasts or reports from thousands of data points with one click or natural language command. You can communicate with hundreds of customers at the same time and predict their next actions.
			paragraph
				StaticText Customers are switching from HubSpot to us after spending thousands of dollars on their implementation.
			paragraph
				StaticText We are using AI to automate writing many of the integrations that keep customers locked into Salesforce and then we are going to take all of their customers too. Killing Salesforce is a $300 billion market cap opportunity that is just waiting for someone to finally grab it.
			paragraph
				StaticText Also, no one works at Salesforce office after 4pm and I am here at our office on a Saturday afternoon on boarding a series B customer while fixing our scalability issues and my co-founder is not gonna sleep until we fix every single GitHub issues. I asked him to go to sleep because he is tired, but he is just not gonna do it. He is built different.
			paragraph
				StaticText Why?
			paragraph
				StaticText Because we don’t have enough. Our dream companies are still their clients. My co-founder and I are best friends for 10+ years and we are first generation immigrant. I dropped out of Duke from a full scholarship program to do things that seems impossible and to help others.
			paragraph
				StaticText Today, at this very moment, we are going through once in a lifetime opportunity and the industry is moving faster than we can possibly imagine.
			paragraph
				StaticText Who wouldn’t jump on this rocket ship?
			paragraph
				StaticText – Octolane Team
			link View Open Roles, url='https://app.withrapha.com/job/369?r=ddca0a9f-d55f-4b64-9075-971e44dfcb18'
				button View Open Roles
	contentinfo
		paragraph
			StaticText Email our team for early access to one@octolane.com
		StaticText “You need three things to create a successful startup: to start with good people, to make something customers actually want, and to spend as little money as possible.” ― Paul Graham
		StaticText Backed by
		StaticText ·
		StaticText Y Combinator
		heading Product
		list Quick links Product
			listitem
				link Enterprise, url='https://www.octolane.com/pricing'
			listitem
				link Pricing, url='https://www.octolane.com/pricing'
			listitem
				link Docs, url='https://docs.octolane.com/'
		heading Social
		list Quick links Resources
			listitem
				link Twitter, url='https://twitter.com/octolane_ai'
			listitem
				link LinkedIn, url='https://www.linkedin.com/company/octolane'
		heading Company
		list Quick links Company
			listitem
				link About, url='https://www.octolane.com/about'
			listitem
				link Status, url='https://status.octolane.com/'
			listitem
				link Security, url='https://www.octolane.com/security'
		heading Legal
		list Quick links Legal
			listitem
				link Privacy, url='https://www.octolane.com/privacy-policy'
			listitem
				link Terms, url='https://www.octolane.com/terms'
			listitem
				link Subprocessors, url='https://www.octolane.com/subprocessor'
			listitem
				link DPA, url='https://drive.google.com/file/d/10_KYVEw1p7UlhuvFIP6oFQd_ZOT4Ix-0/view?usp=sharing'
		paragraph
			StaticText ©
			StaticText 2025
			StaticText Octolane AI, Inc. All rights reserved.
		StaticText All systems operational
	alert, atomic
```
</details>

**Reasoning for action:** I need to complete the user story that requires understanding the pricing structure and plans available. Therefore, clicking the 'Pricing' link is the necessary step to navigate to the appropriate page where I can access the details of the available subscription options.

**Action:** click(107) # Click on the About link to learn more about the company.

**Change Description:** The browser navigated to the 'About' page of the Octolane website, changing the URL to 'https://www.octolane.com/about' and allowing access to a new region with content about the company's vision and activities, while the 'About' link in the navigation is now focused.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://www.octolane.com/about

https://www.octolane.com/pricing

**Content (before/after):** 

```
RootWebArea Octolane AI, focused, url='https://www.octolane.com/about'
	banner
		navigation Main
			list
				listitem
```
<details><summary>Show more</summary>

```
					[104] link, center=(840,36), url='https://www.octolane.com/'
						image
				listitem
					[107] link About, center=(952,36), focused, url='https://www.octolane.com/about'
				listitem
					[109] link Pricing, center=(1032,36), url='https://www.octolane.com/pricing'
				listitem
					[111] link Log in, center=(1114,36), url='https://www.octolane.com/auth/sign-in'
	region Notifications alt+T
	main
		region Building the AI CRM we always wanted, because why settle for less when you can have it all?
			heading Building the AI CRM we always wanted, because why settle for less when you can have it all?
		figure
			image Two employees working with computers, url='https://www.octolane.com/_next/image?url=%2Fassets%2Fimages%2F6.webp&w=640&q=75'
			Figcaption
				StaticText Our team hard at work
		figure
			image At Y Combinator office, url='https://www.octolane.com/_next/image?url=%2Fassets%2Fimages%2F9.webp&w=640&q=75'
			Figcaption
				StaticText At Y Combinator office
		figure
			image Picture of the Fraumunster Zurich, url='https://www.octolane.com/_next/image?url=%2Fassets%2Fimages%2F3.webp&w=640&q=75'
			Figcaption
				StaticText Meetings and moments that matter.
		figure
			image Team having a break in the lunch room, url='https://www.octolane.com/_next/image?url=%2Fassets%2Fimages%2F10.webp&w=640&q=75'
			Figcaption
				StaticText Our friend Bisco is the best!
		figure
			image Person with headphones, url='https://www.octolane.com/_next/image?url=%2Fassets%2Fimages%2F11.webp&w=640&q=75'
			Figcaption
				StaticText Perfect playlist for late night coding sessions
		figure
			image Picture of a party with confetti, url='https://www.octolane.com/_next/image?url=%2Fassets%2Fimages%2Fbatch.webp&w=1920&q=75'
			Figcaption
				StaticText Our YC W24 batch is the best batch!
		region Our Vision
			heading Our Vision
			paragraph
				StaticText Every other CRM on the market previously built a
				strong
					StaticText system of records
				StaticText , that changes now. Instead of a system of records, now it’s possible to build a
				strong
					StaticText system of actions
				StaticText thanks to AI.
			paragraph
				StaticText Octolane is building AI-first Salesforce. Our software does a lot more than just storing customer data. It predicts your next actions and takes care of that for you. It uses AI to find the best customers, does lead scoring, reaches out to them and closes them. You can also generate any forecasts or reports from thousands of data points with one click or natural language command. You can communicate with hundreds of customers at the same time and predict their next actions.
			paragraph
				StaticText Customers are switching from HubSpot to us after spending thousands of dollars on their implementation.
			paragraph
				StaticText We are using AI to automate writing many of the integrations that keep customers locked into Salesforce and then we are going to take all of their customers too. Killing Salesforce is a $300 billion market cap opportunity that is just waiting for someone to finally grab it.
			paragraph
				StaticText Also, no one works at Salesforce office after 4pm and I am here at our office on a Saturday afternoon on boarding a series B customer while fixing our scalability issues and my co-founder is not gonna sleep until we fix every single GitHub issues. I asked him to go to sleep because he is tired, but he is just not gonna do it. He is built different.
			paragraph
				StaticText Why?
			paragraph
				StaticText Because we don’t have enough. Our dream companies are still their clients. My co-founder and I are best friends for 10+ years and we are first generation immigrant. I dropped out of Duke from a full scholarship program to do things that seems impossible and to help others.
			paragraph
				StaticText Today, at this very moment, we are going through once in a lifetime opportunity and the industry is moving faster than we can possibly imagine.
			paragraph
				StaticText Who wouldn’t jump on this rocket ship?
			paragraph
				StaticText – Octolane Team
			link View Open Roles, url='https://app.withrapha.com/job/369?r=ddca0a9f-d55f-4b64-9075-971e44dfcb18'
				button View Open Roles
	contentinfo
		paragraph
			StaticText Email our team for early access to one@octolane.com
		StaticText “You need three things to create a successful startup: to start with good people, to make something customers actually want, and to spend as little money as possible.” ― Paul Graham
		StaticText Backed by
		StaticText ·
		StaticText Y Combinator
		heading Product
		list Quick links Product
			listitem
				link Enterprise, url='https://www.octolane.com/pricing'
			listitem
				link Pricing, url='https://www.octolane.com/pricing'
			listitem
				link Docs, url='https://docs.octolane.com/'
		heading Social
		list Quick links Resources
			listitem
				link Twitter, url='https://twitter.com/octolane_ai'
			listitem
				link LinkedIn, url='https://www.linkedin.com/company/octolane'
		heading Company
		list Quick links Company
			listitem
				link About, url='https://www.octolane.com/about'
			listitem
				link Status, url='https://status.octolane.com/'
			listitem
				link Security, url='https://www.octolane.com/security'
		heading Legal
		list Quick links Legal
			listitem
				link Privacy, url='https://www.octolane.com/privacy-policy'
			listitem
				link Terms, url='https://www.octolane.com/terms'
			listitem
				link Subprocessors, url='https://www.octolane.com/subprocessor'
			listitem
				link DPA, url='https://drive.google.com/file/d/10_KYVEw1p7UlhuvFIP6oFQd_ZOT4Ix-0/view?usp=sharing'
		paragraph
			StaticText ©
			StaticText 2025
			StaticText Octolane AI, Inc. All rights reserved.
		StaticText All systems operational
	alert, atomic
```
</details>



```
RootWebArea Octolane AI, focused, url='https://www.octolane.com/pricing'
	banner
		navigation Main
			list
				listitem
```
<details><summary>Show more</summary>

```
					[104] link, center=(840,36), url='https://www.octolane.com/'
						image
				listitem
					[107] link About, center=(952,36), url='https://www.octolane.com/about'
				listitem
					[109] link Pricing, center=(1032,36), focused, url='https://www.octolane.com/pricing'
				listitem
					[111] link Log in, center=(1114,36), url='https://www.octolane.com/auth/sign-in'
	region Notifications alt+T
	paragraph
		StaticText The right price for the One
	heading Best Friend
	paragraph
		StaticText $1000
		StaticText /month
	paragraph
		StaticText The perfect plan if you're just getting started with our product.
	list
		[487] listitem, center=(736,528), inner_text=Unlimited Seats
			StaticText Unlimited Seats
		[489] listitem, center=(736,564), inner_text=Full Featured AI CRM
			StaticText Full Featured AI CRM
		[491] listitem, center=(736,600), inner_text=5000 Company Enrichment
			StaticText 5000 Company Enrichment
		[493] listitem, center=(736,636), inner_text=2000 Email Sending
			StaticText 2000 Email Sending
		[495] listitem, center=(736,672), inner_text=Real-time Email & Calendar Sync
			StaticText Real-time Email & Calendar Sync
		[497] listitem, center=(736,708), inner_text=2000 Contact Enrichment
			StaticText 2000 Contact Enrichment
		[499] listitem, center=(736,744), inner_text=100 Lead Identify
			StaticText 100 Lead Identify
		[501] listitem, center=(736,780), inner_text=PostHog, Segment & Slack Integrations
			StaticText PostHog, Segment & Slack Integrations
		[503] listitem, center=(736,816), inner_text=CEO & CTO Support 24/7
			StaticText CEO & CTO Support 24/7
	[505] link Get started today, center=(736,888), url='https://buy.stripe.com/4gw9DS2H18hV4Fi8wA'
	heading Enterprise
	paragraph
		StaticText Never Gonna Give You Up
		StaticText /month
	paragraph
		StaticText Everything in Best Friend, plus:
	list
		[513] listitem, center=(1184,574), inner_text=API Access
			StaticText API Access
		[515] listitem, center=(1184,610), inner_text=Unlimited Company & Contact Enrichment
			StaticText Unlimited Company & Contact Enrichment
		[517] listitem, center=(1184,646), inner_text=Unlimited Lead Identify
			StaticText Unlimited Lead Identify
		[519] listitem, center=(1184,682), inner_text=HubSpot and Salesforce Integrations
			StaticText HubSpot and Salesforce Integrations
		[521] listitem, center=(1184,718), inner_text=SAML and SSO
			StaticText SAML and SSO
		[523] listitem, center=(1184,754), inner_text=SOC-2 Compliance
			StaticText SOC-2 Compliance
		[525] listitem, center=(1184,790), inner_text=CEO & CTO Support 24/7
			StaticText CEO & CTO Support 24/7
	[527] link Get started today, center=(1184,862), url='https://jl1zzmzlaee.typeform.com/to/oC8zpNzM'
	contentinfo
		paragraph
			StaticText Email our team for early access to one@octolane.com
		StaticText “You need three things to create a successful startup: to start with good people, to make something customers actually want, and to spend as little money as possible.” ― Paul Graham
		StaticText Backed by
		StaticText ·
		StaticText Y Combinator
		heading Product
		list Quick links Product
			listitem
				link Enterprise, url='https://www.octolane.com/pricing'
			listitem
				link Pricing, url='https://www.octolane.com/pricing'
			listitem
				link Docs, url='https://docs.octolane.com/'
		heading Social
		list Quick links Resources
			listitem
				link Twitter, url='https://twitter.com/octolane_ai'
			listitem
				link LinkedIn, url='https://www.linkedin.com/company/octolane'
		heading Company
		list Quick links Company
			listitem
				link About, url='https://www.octolane.com/about'
			listitem
				link Status, url='https://status.octolane.com/'
			listitem
				link Security, url='https://www.octolane.com/security'
		heading Legal
		list Quick links Legal
			listitem
				link Privacy, url='https://www.octolane.com/privacy-policy'
			listitem
				link Terms, url='https://www.octolane.com/terms'
			listitem
				link Subprocessors, url='https://www.octolane.com/subprocessor'
			listitem
				link DPA, url='https://drive.google.com/file/d/10_KYVEw1p7UlhuvFIP6oFQd_ZOT4Ix-0/view?usp=sharing'
		paragraph
			StaticText ©
			StaticText 2025
			StaticText Octolane AI, Inc. All rights reserved.
		StaticText All systems operational
	alert, atomic
```
</details>

**Reasoning for action:** I clicked on the 'Pricing' link (109) in the navigation menu because the user story requires me to understand the pricing structure and plans available for Octolane AI. By doing this, I will be taken to the Pricing page, which is essential to check for the plans that include 'Best Friend' and 'Enterprise', fulfilling the user's goal.

**Action:** click(109) # Click on the Pricing link to learn about the pricing structure of Octolane AI.

**Change Description:** The browser navigated from the 'About' page to the 'Pricing' page of Octolane AI, updating the URL to 'https://www.octolane.com/pricing' and displaying new content that includes different pricing plans and features such as 'Best Friend' and 'Enterprise' plans.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://www.octolane.com/pricing

https://buy.stripe.com/4gw9DS2H18hV4Fi8wA

**Content (before/after):** 

```
RootWebArea Octolane AI, focused, url='https://www.octolane.com/pricing'
	banner
		navigation Main
			list
				listitem
```
<details><summary>Show more</summary>

```
					[104] link, center=(840,36), url='https://www.octolane.com/'
						image
				listitem
					[107] link About, center=(952,36), url='https://www.octolane.com/about'
				listitem
					[109] link Pricing, center=(1032,36), focused, url='https://www.octolane.com/pricing'
				listitem
					[111] link Log in, center=(1114,36), url='https://www.octolane.com/auth/sign-in'
	region Notifications alt+T
	paragraph
		StaticText The right price for the One
	heading Best Friend
	paragraph
		StaticText $1000
		StaticText /month
	paragraph
		StaticText The perfect plan if you're just getting started with our product.
	list
		[487] listitem, center=(736,528), inner_text=Unlimited Seats
			StaticText Unlimited Seats
		[489] listitem, center=(736,564), inner_text=Full Featured AI CRM
			StaticText Full Featured AI CRM
		[491] listitem, center=(736,600), inner_text=5000 Company Enrichment
			StaticText 5000 Company Enrichment
		[493] listitem, center=(736,636), inner_text=2000 Email Sending
			StaticText 2000 Email Sending
		[495] listitem, center=(736,672), inner_text=Real-time Email & Calendar Sync
			StaticText Real-time Email & Calendar Sync
		[497] listitem, center=(736,708), inner_text=2000 Contact Enrichment
			StaticText 2000 Contact Enrichment
		[499] listitem, center=(736,744), inner_text=100 Lead Identify
			StaticText 100 Lead Identify
		[501] listitem, center=(736,780), inner_text=PostHog, Segment & Slack Integrations
			StaticText PostHog, Segment & Slack Integrations
		[503] listitem, center=(736,816), inner_text=CEO & CTO Support 24/7
			StaticText CEO & CTO Support 24/7
	[505] link Get started today, center=(736,888), url='https://buy.stripe.com/4gw9DS2H18hV4Fi8wA'
	heading Enterprise
	paragraph
		StaticText Never Gonna Give You Up
		StaticText /month
	paragraph
		StaticText Everything in Best Friend, plus:
	list
		[513] listitem, center=(1184,574), inner_text=API Access
			StaticText API Access
		[515] listitem, center=(1184,610), inner_text=Unlimited Company & Contact Enrichment
			StaticText Unlimited Company & Contact Enrichment
		[517] listitem, center=(1184,646), inner_text=Unlimited Lead Identify
			StaticText Unlimited Lead Identify
		[519] listitem, center=(1184,682), inner_text=HubSpot and Salesforce Integrations
			StaticText HubSpot and Salesforce Integrations
		[521] listitem, center=(1184,718), inner_text=SAML and SSO
			StaticText SAML and SSO
		[523] listitem, center=(1184,754), inner_text=SOC-2 Compliance
			StaticText SOC-2 Compliance
		[525] listitem, center=(1184,790), inner_text=CEO & CTO Support 24/7
			StaticText CEO & CTO Support 24/7
	[527] link Get started today, center=(1184,862), url='https://jl1zzmzlaee.typeform.com/to/oC8zpNzM'
	contentinfo
		paragraph
			StaticText Email our team for early access to one@octolane.com
		StaticText “You need three things to create a successful startup: to start with good people, to make something customers actually want, and to spend as little money as possible.” ― Paul Graham
		StaticText Backed by
		StaticText ·
		StaticText Y Combinator
		heading Product
		list Quick links Product
			listitem
				link Enterprise, url='https://www.octolane.com/pricing'
			listitem
				link Pricing, url='https://www.octolane.com/pricing'
			listitem
				link Docs, url='https://docs.octolane.com/'
		heading Social
		list Quick links Resources
			listitem
				link Twitter, url='https://twitter.com/octolane_ai'
			listitem
				link LinkedIn, url='https://www.linkedin.com/company/octolane'
		heading Company
		list Quick links Company
			listitem
				link About, url='https://www.octolane.com/about'
			listitem
				link Status, url='https://status.octolane.com/'
			listitem
				link Security, url='https://www.octolane.com/security'
		heading Legal
		list Quick links Legal
			listitem
				link Privacy, url='https://www.octolane.com/privacy-policy'
			listitem
				link Terms, url='https://www.octolane.com/terms'
			listitem
				link Subprocessors, url='https://www.octolane.com/subprocessor'
			listitem
				link DPA, url='https://drive.google.com/file/d/10_KYVEw1p7UlhuvFIP6oFQd_ZOT4Ix-0/view?usp=sharing'
		paragraph
			StaticText ©
			StaticText 2025
			StaticText Octolane AI, Inc. All rights reserved.
		StaticText All systems operational
	alert, atomic
```
</details>



```
RootWebArea Octolane AI, focused, url='https://buy.stripe.com/4gw9DS2H18hV4Fi8wA'
	banner
		image Octolane AI logo, url='https://stripe-camo.global.ssl.fastly.net/4b7576a94a1e73913d23c5ca3d84178795f1d11a2c5ee66bb0371403795ccdb9/68747470733a2f2f66696c65732e7374726970652e636f6d2f66696c65732f4d44423859574e6a64463878543031554e57744d5a54684d4f5856485458563066475a6662476c325a56396e516d745252566f33616b68695a6d686e62577870536e64515744427053557730306d4c4d356a6f4f61'
		StaticText Back
	StaticText Subscribe to Best Friend
```
<details><summary>Show more</summary>

```
	StaticText $1,000.00
	StaticText per
	StaticText month
	list
		[68] listitem, center=(690,281), inner_text=Best Friend
Billed monthly
$1,000.00
			StaticText Best Friend
			StaticText Billed monthly
			StaticText $1,000.00
	[49] span, center=(690,162), inner_text=Subscribe to Best Friend
	StaticText Subtotal
	StaticText $1,000.00
	LabelText
		[109] textbox, center=(575,378), autocomplete=off, contenteditable=True, type=text
	StaticText Total due today
	StaticText $1,000.00
	main
		[a] IframePresentational Secure express checkout frame, center=(1230,113), title=Secure express checkout frame
		separator, orientation='horizontal'
		paragraph
			StaticText Or pay another way
		LabelText
			StaticText Email
		[158] textbox Email, center=(1230,239), autocomplete=email, contenteditable=True, type=text
		heading Payment method
		list
			listitem
				radio, checked='false'
				image, url='https://js.stripe.com/v3/fingerprinted/img/card-ce24697297bd3c6a00fdd2fb6f760f0d.svg'
				StaticText Card
				button Pay with card
			listitem
				radio, checked='false'
				image, url='https://js.stripe.com/v3/fingerprinted/img/payment-methods/icon-pm-cashapp-981164a833e417d28a8ac2684fda2324.svg'
				StaticText Cash App Pay
				button Pay with Cash App
		[243] checkbox Save my info for 1-click checkout with Link Securely pay on Octolane AI and everywhere Link is accepted., center=(1060,472), checked=, contenteditable=True, type=checkbox
		image
		LabelText
			StaticText Save my info for 1-click checkout with Link
			StaticText Securely pay on Octolane AI and everywhere Link is accepted.
		image US, url='https://js.stripe.com/v3/fingerprinted/img/FlagIcon-US-858b47c5a50311ee27ec390dd06d3b67.svg'
		[251] div, center=(1244,503), inner_text=Securely pay on Octolane AI and everywhere Link is accepted.
		[249] div, center=(1244,473), inner_text=Save my info for 1-click checkout with Link
		[262] combobox value='United States (+1)', center=(1062,546), contenteditable=True, expanded=False, hasPopup='menu', inner_text=Afghanistan (+93)
Albania (+355)
Algeria (+213)
Andorra (+376)
Angola (+244)
Anguilla (+1)
Antigua & Barbuda (+1)
Argentina (+54)
Armenia (+374)
Aruba (+297)
Ascension Island (+247)
Australia (+61)
Austria (+43)
Azerbaijan (+994)
Åland Islands (+358)
Bahamas (+1)
Bahrain (+973)
Bangladesh (+880)
Barbados (+1)
Belarus (+375)
Belgium (+32)
Belize (+501)
Benin (+229)
Bermuda (+1)
Bhutan (+975)
Bolivia (+591)
Bosnia & Herzegovina (+387)
Botswana (+267)
Brazil (+55)
British Indian Ocean Territory (+246)
British Virgin Islands (+1)
Brunei (+673)
Bulgaria (+359)
Burkina Faso (+226)
Burundi (+257)
Cambodia (+855)
Cameroon (+237)
Canada (+1)
Cape Verde (+238)
Caribbean Netherlands (+599)
Cayman Islands (+1)
Central African Republic (+236)
Chad (+235)
Chile (+56)
China (+86)
Colombia (+57)
Comoros (+269)
Congo - Brazzaville (+242)
Congo - Kinshasa (+243)
Cook Islands (+682)
Costa Rica (+506)
Côte d’Ivoire (+225)
Croatia (+385)
Curaçao (+599)
Cyprus (+357)
Czechia (+420)
Denmark (+45)
Djibouti (+253)
Dominica (+1)
Dominican Republic (+1)
Ecuador (+593)
Egypt (+20)
El Salvador (+503)
Equatorial Guinea (+240)
Eritrea (+291)
Estonia (+372)
Eswatini (+268)
Ethiopia (+251)
Falkland Islands (+500)
Faroe Islands (+298)
Fiji (+679)
Finland (+358)
France (+33)
French Guiana (+594)
French Polynesia (+689)
Gabon (+241)
Gambia (+220)
Georgia (+995)
Germany (+49)
Ghana (+233)
Gibraltar (+350)
Greece (+30)
Greenland (+299)
Grenada (+1)
Guadeloupe (+590)
Guam (+1)
Guatemala (+502)
Guernsey (+44)
Guinea (+224)
Guinea-Bissau (+245)
Guyana (+592)
Haiti (+509)
Honduras (+504)
Hong Kong SAR China (+852)
Hungary (+36)
Iceland (+354)
India (+91)
Indonesia (+62)
Iraq (+964)
Ireland (+353)
Isle of Man (+44)
Israel (+972)
Italy (+39)
Jamaica (+1)
Japan (+81)
Jersey (+44)
Jordan (+962)
Kazakhstan (+7)
Kenya (+254)
Kiribati (+686)
Kosovo (+383)
Kuwait (+965)
Kyrgyzstan (+996)
Laos (+856)
Latvia (+371)
Lebanon (+961)
Lesotho (+266)
Liberia (+231)
Libya (+218)
Liechtenstein (+423)
Lithuania (+370)
Luxembourg (+352)
Macao SAR China (+853)
Madagascar (+261)
Malawi (+265)
Malaysia (+60)
Maldives (+960)
Mali (+223)
Malta (+356)
Martinique (+596)
Mauritania (+222)
Mauritius (+230)
Mayotte (+262)
Mexico (+52)
Moldova (+373)
Monaco (+377)
Mongolia (+976)
Montenegro (+382)
Montserrat (+1)
Morocco (+212)
Mozambique (+258)
Myanmar (Burma) (+95)
Namibia (+264)
Nauru (+674)
Nepal (+977)
Netherlands (+31)
New Caledonia (+687)
New Zealand (+64)
Nicaragua (+505)
Niger (+227)
Nigeria (+234)
Niue (+683)
North Macedonia (+389)
Norway (+47)
Oman (+968)
Pakistan (+92)
Palestinian Territories (+970)
Panama (+507)
Papua New Guinea (+675)
Paraguay (+595)
Peru (+51)
Philippines (+63)
Poland (+48)
Portugal (+351)
Puerto Rico (+1)
Qatar (+974)
Réunion (+262)
Romania (+40)
Russia (+7)
Rwanda (+250)
Samoa (+685)
San Marino (+378)
São Tomé & Príncipe (+239)
Saudi Arabia (+966)
Senegal (+221)
Serbia (+381)
Seychelles (+248)
Sierra Leone (+232)
Singapore (+65)
Sint Maarten (+1)
Slovakia (+421)
Slovenia (+386)
Solomon Islands (+677)
Somalia (+252)
South Africa (+27)
South Korea (+82)
South Sudan (+211)
Spain (+34)
Sri Lanka (+94)
St. Barthélemy (+590)
St. Helena (+290)
St. Kitts & Nevis (+1)
St. Lucia (+1)
St. Martin (+590)
St. Pierre & Miquelon (+508)
St. Vincent & Grenadines (+1)
Suriname (+597)
Svalbard & Jan Mayen (+47)
Sweden (+46)
Switzerland (+41)
Taiwan (+886)
Tajikistan (+992)
Tanzania (+255)
Thailand (+66)
Timor-Leste (+670)
Togo (+228)
Tokelau (+690)
Tonga (+676)
Trinidad & Tobago (+1)
Tristan da Cunha (+290)
Tunisia (+216)
Turkey (+90)
Turkmenistan (+993)
Turks & Caicos Islands (+1)
Tuvalu (+688)
Uganda (+256)
Ukraine (+380)
United Arab Emirates (+971)
United Kingdom (+44)
United States (+1)
Uruguay (+598)
Uzbekistan (+998)
Vanuatu (+678)
Vatican City (+39)
Venezuela (+58)
Vietnam (+84)
Wallis & Futuna (+681)
Western Sahara (+212)
Yemen (+967)
Zambia (+260)
Zimbabwe (+263)
			group A
				option Afghanistan (+93), selected=False
				option Albania (+355), selected=False
				option Algeria (+213), selected=False
				option Andorra (+376), selected=False
				option Angola (+244), selected=False
				option Anguilla (+1), selected=False
				option Antigua & Barbuda (+1), selected=False
				option Argentina (+54), selected=False
				option Armenia (+374), selected=False
				option Aruba (+297), selected=False
				option Ascension Island (+247), selected=False
				option Australia (+61), selected=False
				option Austria (+43), selected=False
				option Azerbaijan (+994), selected=False
			group Å
				option Åland Islands (+358), selected=False
			group B
				option Bahamas (+1), selected=False
				option Bahrain (+973), selected=False
				option Bangladesh (+880), selected=False
				option Barbados (+1), selected=False
				option Belarus (+375), selected=False
				option Belgium (+32), selected=False
				option Belize (+501), selected=False
				option Benin (+229), selected=False
				option Bermuda (+1), selected=False
				option Bhutan (+975), selected=False
				option Bolivia (+591), selected=False
				option Bosnia & Herzegovina (+387), selected=False
				option Botswana (+267), selected=False
				option Brazil (+55), selected=False
				option British Indian Ocean Territory (+246), selected=False
				option British Virgin Islands (+1), selected=False
				option Brunei (+673), selected=False
				option Bulgaria (+359), selected=False
				option Burkina Faso (+226), selected=False
				option Burundi (+257), selected=False
			group C
				option Cambodia (+855), selected=False
				option Cameroon (+237), selected=False
				option Canada (+1), selected=False
				option Cape Verde (+238), selected=False
				option Caribbean Netherlands (+599), selected=False
				option Cayman Islands (+1), selected=False
				option Central African Republic (+236), selected=False
				option Chad (+235), selected=False
				option Chile (+56), selected=False
				option China (+86), selected=False
				option Colombia (+57), selected=False
				option Comoros (+269), selected=False
				option Congo - Brazzaville (+242), selected=False
				option Congo - Kinshasa (+243), selected=False
				option Cook Islands (+682), selected=False
				option Costa Rica (+506), selected=False
				option Côte d’Ivoire (+225), selected=False
				option Croatia (+385), selected=False
				option Curaçao (+599), selected=False
				option Cyprus (+357), selected=False
				option Czechia (+420), selected=False
			group D
				option Denmark (+45), selected=False
				option Djibouti (+253), selected=False
				option Dominica (+1), selected=False
				option Dominican Republic (+1), selected=False
			group E
				option Ecuador (+593), selected=False
				option Egypt (+20), selected=False
				option El Salvador (+503), selected=False
				option Equatorial Guinea (+240), selected=False
				option Eritrea (+291), selected=False
				option Estonia (+372), selected=False
				option Eswatini (+268), selected=False
				option Ethiopia (+251), selected=False
			group F
				option Falkland Islands (+500), selected=False
				option Faroe Islands (+298), selected=False
				option Fiji (+679), selected=False
				option Finland (+358), selected=False
				option France (+33), selected=False
				option French Guiana (+594), selected=False
				option French Polynesia (+689), selected=False
			group G
				option Gabon (+241), selected=False
				option Gambia (+220), selected=False
				option Georgia (+995), selected=False
				option Germany (+49), selected=False
				option Ghana (+233), selected=False
				option Gibraltar (+350), selected=False
				option Greece (+30), selected=False
				option Greenland (+299), selected=False
				option Grenada (+1), selected=False
				option Guadeloupe (+590), selected=False
				option Guam (+1), selected=False
				option Guatemala (+502), selected=False
				option Guernsey (+44), selected=False
				option Guinea (+224), selected=False
				option Guinea-Bissau (+245), selected=False
				option Guyana (+592), selected=False
			group H
				option Haiti (+509), selected=False
				option Honduras (+504), selected=False
				option Hong Kong SAR China (+852), selected=False
				option Hungary (+36), selected=False
			group I
				option Iceland (+354), selected=False
				option India (+91), selected=False
				option Indonesia (+62), selected=False
				option Iraq (+964), selected=False
				option Ireland (+353), selected=False
				option Isle of Man (+44), selected=False
				option Israel (+972), selected=False
				option Italy (+39), selected=False
			group J
				option Jamaica (+1), selected=False
				option Japan (+81), selected=False
				option Jersey (+44), selected=False
				option Jordan (+962), selected=False
			group K
				option Kazakhstan (+7), selected=False
				option Kenya (+254), selected=False
				option Kiribati (+686), selected=False
				option Kosovo (+383), selected=False
				option Kuwait (+965), selected=False
				option Kyrgyzstan (+996), selected=False
			group L
				option Laos (+856), selected=False
				option Latvia (+371), selected=False
				option Lebanon (+961), selected=False
				option Lesotho (+266), selected=False
				option Liberia (+231), selected=False
				option Libya (+218), selected=False
				option Liechtenstein (+423), selected=False
				option Lithuania (+370), selected=False
				option Luxembourg (+352), selected=False
			group M
				option Macao SAR China (+853), selected=False
				option Madagascar (+261), selected=False
				option Malawi (+265), selected=False
				option Malaysia (+60), selected=False
				option Maldives (+960), selected=False
				option Mali (+223), selected=False
				option Malta (+356), selected=False
				option Martinique (+596), selected=False
				option Mauritania (+222), selected=False
				option Mauritius (+230), selected=False
				option Mayotte (+262), selected=False
				option Mexico (+52), selected=False
				option Moldova (+373), selected=False
				option Monaco (+377), selected=False
				option Mongolia (+976), selected=False
				option Montenegro (+382), selected=False
				option Montserrat (+1), selected=False
				option Morocco (+212), selected=False
				option Mozambique (+258), selected=False
				option Myanmar (Burma) (+95), selected=False
			group N
				option Namibia (+264), selected=False
				option Nauru (+674), selected=False
				option Nepal (+977), selected=False
				option Netherlands (+31), selected=False
				option New Caledonia (+687), selected=False
				option New Zealand (+64), selected=False
				option Nicaragua (+505), selected=False
				option Niger (+227), selected=False
				option Nigeria (+234), selected=False
				option Niue (+683), selected=False
				option North Macedonia (+389), selected=False
				option Norway (+47), selected=False
			group O
				option Oman (+968), selected=False
			group P
				option Pakistan (+92), selected=False
				option Palestinian Territories (+970), selected=False
				option Panama (+507), selected=False
				option Papua New Guinea (+675), selected=False
				option Paraguay (+595), selected=False
				option Peru (+51), selected=False
				option Philippines (+63), selected=False
				option Poland (+48), selected=False
				option Portugal (+351), selected=False
				option Puerto Rico (+1), selected=False
			group Q
				option Qatar (+974), selected=False
			group R
				option Réunion (+262), selected=False
				option Romania (+40), selected=False
				option Russia (+7), selected=False
				option Rwanda (+250), selected=False
			group S
				option Samoa (+685), selected=False
				option San Marino (+378), selected=False
				option São Tomé & Príncipe (+239), selected=False
				option Saudi Arabia (+966), selected=False
				option Senegal (+221), selected=False
				option Serbia (+381), selected=False
				option Seychelles (+248), selected=False
				option Sierra Leone (+232), selected=False
				option Singapore (+65), selected=False
				option Sint Maarten (+1), selected=False
				option Slovakia (+421), selected=False
				option Slovenia (+386), selected=False
				option Solomon Islands (+677), selected=False
				option Somalia (+252), selected=False
				option South Africa (+27), selected=False
				option South Korea (+82), selected=False
				option South Sudan (+211), selected=False
				option Spain (+34), selected=False
				option Sri Lanka (+94), selected=False
				option St. Barthélemy (+590), selected=False
				option St. Helena (+290), selected=False
				option St. Kitts & Nevis (+1), selected=False
				option St. Lucia (+1), selected=False
				option St. Martin (+590), selected=False
				option St. Pierre & Miquelon (+508), selected=False
				option St. Vincent & Grenadines (+1), selected=False
				option Suriname (+597), selected=False
				option Svalbard & Jan Mayen (+47), selected=False
				option Sweden (+46), selected=False
				option Switzerland (+41), selected=False
			group T
				option Taiwan (+886), selected=False
				option Tajikistan (+992), selected=False
				option Tanzania (+255), selected=False
				option Thailand (+66), selected=False
				option Timor-Leste (+670), selected=False
				option Togo (+228), selected=False
				option Tokelau (+690), selected=False
				option Tonga (+676), selected=False
				option Trinidad & Tobago (+1), selected=False
				option Tristan da Cunha (+290), selected=False
				option Tunisia (+216), selected=False
				option Turkey (+90), selected=False
				option Turkmenistan (+993), selected=False
				option Turks & Caicos Islands (+1), selected=False
				option Tuvalu (+688), selected=False
			group U
				option Uganda (+256), selected=False
				option Ukraine (+380), selected=False
				option United Arab Emirates (+971), selected=False
				option United Kingdom (+44), selected=False
				option United States (+1), selected=True
				option Uruguay (+598), selected=False
				option Uzbekistan (+998), selected=False
			group V
				option Vanuatu (+678), selected=False
				option Vatican City (+39), selected=False
				option Venezuela (+58), selected=False
				option Vietnam (+84), selected=False
			group W
				option Wallis & Futuna (+681), selected=False
				option Western Sahara (+212), selected=False
			group Y
				option Yemen (+967), selected=False
			group Z
				option Zambia (+260), selected=False
				option Zimbabwe (+263), selected=False
		image
		[522] textbox Phone number, center=(1230,545), autocomplete=tel, contenteditable=True, required, type=tel
		[530] button, center=(1230,577), type=button
			image
		[540] button Subscribe, center=(1230,633), inner_text=Subscribe
Processing..., type=submit
			image
			image
			image
		StaticText By confirming your subscription, you allow Octolane AI to charge you for future payments in accordance with their terms. You can always cancel your subscription.
		StaticText By clicking
		StaticText Subscribe
		StaticText , you agree to the Link
		[565] link Terms, center=(1345,749), url='https://link.com/terms'
		StaticText and
		[566] link Privacy Policy, center=(1228,766), url='https://link.com/privacy'
		StaticText .
	contentinfo
		[592] link Powered by Stripe, center=(1169,848), inner_text=Powered by , url='https://stripe.com/'
			image Stripe
		[598] link Terms, center=(1269,850), url='https://stripe.com/legal/end-users'
		[600] link Privacy, center=(1321,850), url='https://stripe.com/privacy'
```
</details>

**Reasoning for action:** I identified the 'Get started today' link associated with the Best Friend plan. Clicking this link is a crucial step in fulfilling the user's task because it allows them to proceed to the next phase of the subscription process. Once clicked, it should lead me to the Stripe checkout page, providing the user with necessary information about the subscription and payment options, which aligns perfectly with their goal to understand the pricing structure and select the appropriate subscription.

**Action:** click(505) # Click on the 'Get started today' link for the Best Friend plan to see the sign-up process.

**Change Description:** After the action was taken, the browser navigated from the Octolane AI pricing page to a Stripe checkout page for the 'Best Friend' subscription plan, displaying the subscription details, pricing, and options for payment methods.

**Screenshot before:****Screenshot after:**---

