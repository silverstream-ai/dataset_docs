# Task

**Owner Finder Exploration and Free Trial Signup**

As a potential customer,
I explore the Owner Finder product and sign up for a free trial,
so that I can evaluate its features for obtaining owner contacts and improve my sales efficiency.

**Success definition:** Given I am on the Openmart homepage and I have reviewed the available products
When I click on the Owner Finder link and then the Try for free link
Then I should arrive on the Owner Finder product page to view its features and subsequently be redirected to the sign-up page.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.openmart.com/

https://www.openmart.com/

**Content (before/after):** 

```
RootWebArea Openmart: Automate SMB Sales Research at Scale, focused, url='https://www.openmart.com/'
	dialog Cookie Consent Prompt, modal=False
		StaticText We use essential cookies to make our site work. With your consent, we may also use non-essential cookies to improve user experience and analyze website traffic. By clicking “Accept,” you agree to our website's cookie use as described in our
		[55] link Cookie Policy, center=(621,1019)
		StaticText . You can change your cookie settings at any time by clicking “
```
<details><summary>Show more</summary>

```
		[56] link Preferences, center=(1019,1019)
		StaticText .”
		[58] button Preferences, center=(1285,1009)
		[59] button Decline, center=(1452,1009)
		[60] button Accept, center=(1618,1009)
	banner
		[68] link home, center=(379,39), url='https://www.openmart.com/'
			image logo, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/6724319567afcbb10436819a_Group%205%20(4).svg'
		navigation
			[73] button Products, center=(537,39), expanded=False, hasPopup='menu'
			[81] link Customers, center=(645,39), url='https://www.openmart.com/#section-reviews'
			[82] link Blogs, center=(730,39), url='https://www.openmart.com/blog'
			[83] link Wall of love, center=(820,39), url='https://www.openmart.com/wall-of-love'
		[85] link Login, center=(1552,39), url='http://app.openmart.com/'
	main
		heading Find newly opened local businesses
		paragraph
			StaticText Join 100+ leading SMB tech companies to do sales more efficiently :)
		[98] link Book a demo, center=(960,558), url='https://www.openmart.com/#'
		image
		image Local Business Intelligence Search, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/66e4a19263d3f7fd7a8f23ed_Group%25201000005699-p-1080.png'
		image Backed by YCombinator, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/66e4a19263d3f7fd7a8f244d_Frame%25201000004993-p-500.png'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/66e4a19363d3f7fd7a8f247b_image%252028-p-500.png'
		image Featured by Forbes, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/66e4a19263d3f7fd7a8f2460_Frame%201000004992.png'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/6734fb89fa42aa5da446b614_produt%20of%20the%20day.png'
		StaticText TRUSTED BY MORE THAN 100+ SMB TECH COMPANIES
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c40fb2137a2a75e7f4b82_Whatnot2.svg'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c40fc89ef36fc13002e38_ali.png'
		image clipboard health, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c3cdb0f0d0a60da0e2d2f_clipboard%20health.png'
		image snackpass, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c3cdb8d4f507a73ba09dd_snackpass.svg'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c40fc418af7ad253401b6_boosrly%202.png'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c40fb2137a2a75e7f4b82_Whatnot2.svg'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c40fc89ef36fc13002e38_ali.png'
		image clipboard health, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c3cdb0f0d0a60da0e2d2f_clipboard%20health.png'
		image snackpass, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c3cdb8d4f507a73ba09dd_snackpass.svg'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c40fc418af7ad253401b6_boosrly%202.png'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c40fb2137a2a75e7f4b82_Whatnot2.svg'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c40fc89ef36fc13002e38_ali.png'
		image clipboard health, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c3cdb0f0d0a60da0e2d2f_clipboard%20health.png'
		image snackpass, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c3cdb8d4f507a73ba09dd_snackpass.svg'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c40fc418af7ad253401b6_boosrly%202.png'
		heading Easily find qualified leads
		paragraph
			StaticText Skip the lengthy research. Tell us how you qualify leads, and our AI will do the rest!
		image
		heading AI Leads Finder
		paragraph
			StaticText Enter custom criteria such as annual revenue and geographic location to find qualified leads.
		image
		heading Maps search engine
		paragraph
			StaticText Maps search designed specifically for sales.
		image
		heading Connect with Your CRM
		paragraph
			StaticText Deduplicate leads from your CRM to ensure new results.
		image
		heading Custom Enrichments
		paragraph
			StaticText Add custom enrichments to get more in-depth information on your leads.
		heading Use cases
		tablist, orientation='horizontal'
			tab Leads scraping from all sites, selected=True
				image
			tab Leads qualification, selected=False
				image
			tab Local business data, selected=False
				image
			tab Leads enrichment, selected=False
				image
		tabpanel Leads scraping from all sites
			image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/677f0a8b1f373f2a02b601b4_Frame%201000005255-2.svg'
		heading Here's what our users are saying
		paragraph
			StaticText Join hundreds of the world’s leading growth, sales, and marketing teams—like Clipboard Health, Alibaba, Whatnot, and Snackpass—to sell to the lower mid-market more efficiently.
		tablist, orientation='horizontal'
			tab, selected=True
				image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/677f06c127700621e4d692df_clipboardlogo.png'
			tab, selected=False
				image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/677f074a89065b48403e966e_boostlytransparent.png'
			tab, selected=False
				image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/677f07d41104ac5c3606016d_whatnotlogo-p-500.png'
			tab, selected=False
				image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/677f07fbc7b5cf92614acd66_42logo.svg'
		tabpanel
			image
			paragraph
				StaticText Openmart has revolutionized our outreach strategy! We previously spent spent hundred of man hours identifying decision makers which has been reduced by over 50% with Openmart's decision maker contacts.
			paragraph
				StaticText -
				strong
					StaticText Calvin Bulzoni
				StaticText .
				StaticText Sales Operations at Clipboard Health
		heading Plans for teams of all sizes
		paragraph
			StaticText No matter where you are in your growth or the world, Openmart is designed to save you time and money
		image
		heading Scale Plan
		paragraph
			StaticText For those looking for intent signals and access to owner contacts
		StaticText $999
		StaticText /mo
		StaticText Billed annually
		link Get Started, url='https://www.openmart.com/#'
		image
		StaticText 30,000 credits per month (for verified email, enrichments, export)
		image
		StaticText 5 AI filters for high-quality leads
		image
		StaticText 1M+ business information globally, including decision maker contacts
		image
		strong
			StaticText Signal-based selling tools
		image
		strong
			StaticText Newly opened businesses
		image
		strong
			StaticText 3 Platform Users
		image
		strong
			StaticText CRM Integration
		image
		heading Custom
		paragraph
			StaticText Custom signals based on your needs
		StaticText Contact Us
		StaticText Billed annually
		link Get Started, url='https://www.openmart.com/#'
		image
		strong
			StaticText Everything in Scale Plan
		image
		strong
			StaticText Pre-open businesses (select geographies)
		image
		strong
			StaticText Ad Spend Signals
		image
		strong
			StaticText Hiring Signals
		image
		strong
			StaticText Spot Trending Businesses
		image
		strong
			StaticText Dedicated line with founders
		heading Try Openmart for free
		paragraph
			StaticText Join hundreds of the world’s leading growth, sales, and marketing teams—like Clipboard Health, Alibaba, Whatnot, and Snackpass—to sell to the lower mid-market more efficiently.
		form Email Form
			textbox Enter email, required
			button Try for free
		heading FAQs
		StaticText How do I sign up and get access to Openmart?
		image
		link Get Started, url='https://app.openmart.com/register'
		StaticText Do you provide free trials?
		image
		paragraph
			StaticText Yes.
		link Get Started, url='https://app.openmart.ai/register?code=FREE_7_DAYS_TRIAL'
		StaticText Is a credit card required to sign up for Openmart's free trial?
		image
		paragraph
			StaticText Yes, a credit or debit card is required to sign up for Openmart's free trial. This allows us to verify your account's authenticity and prevent fraud.
		StaticText What's a "Verified" email?
		image
		paragraph
			StaticText After enriching decision maker emails they will either be labeled as "verified" or "unknown". "Verified" emails are emails that have been checked by our system and that it can be delivered. "Unknown"emails are ones that are not able to be fully verified but are able to be delivered to around 80% of the time.
		StaticText How do we verify emails and phone numbers for leads?
		image
		paragraph
			StaticText Email and phone numbers are verified by cross-referencing a number of different data vendors.
		StaticText How can I find more information on my leads? e.g. find dental clinics that are closed on Saturdays.
		image
		paragraph
			StaticText There are 2 ways to do that:
			StaticText ‍
			StaticText 1. Use AI leads finder and input filtering criteria.  e.g. "closed on Saturdays"
			StaticText 2. Use the "add enrichment" function in your leads list to return custom data.
		StaticText Why are there fewer results in my list even though I exported a lot of them?
		image
		paragraph
			StaticText When you export from the AI Leads Finder, the total number of leads is sometimes just an estimate rather than an exact count.
		link logo, url='https://www.openmart.com/'
			image logo, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/6724319567afcbb10436819a_Group%205%20(4).svg'
		link Product Hunt Product of the Day, url='https://www.producthunt.com/products/openmart'
			image Product Hunt Product of the Day, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/66e4a19363d3f7fd7a8f2532_top-post-badge.svg'
		link Featured by TechCrunch, url='https://techcrunch.com/2024/08/21/openmart-wants-to-make-it-easier-for-enterprises-to-sell-to-local-businesses/'
			image Featured by TechCrunch, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/66e4a19663d3f7fd7a8f267f_ddddddddd.png'
		StaticText Products
		link Owner Finder, url='https://www.openmart.com/products/owner-finder'
		link Monitoring, url='https://www.openmart.com/products/monitoring'
		link Prospecting, url='https://www.openmart.com/products/prospecting'
		link Enrichments, url='https://www.openmart.com/products/enrichments'
		StaticText Company
		link About, url='https://www.ycombinator.com/companies/openmart'
		link News, url='https://techcrunch.com/2024/08/21/openmart-wants-to-make-it-easier-for-enterprises-to-sell-to-local-businesses/'
		link Wall of love, url='https://www.openmart.com/wall-of-love'
		StaticText Resources
		link Pricing, url='https://www.openmart.com/pricing'
		link Blog, url='https://www.openmart.com/blog'
		strong
			StaticText INFORMATION
		link FAQs, url='https://www.openmart.com/faqs'
		link sales@openmart.com, url='mailto:sales@openmart.com'
			strong
		emphasis
			StaticText Copyright © OpenMart 2024. All Rights Reserved.
		link Privacy Policy, url='https://www.openmart.com/privacy-policy'
			emphasis
		link Terms & Conditions, url='https://www.openmart.com/terms-of-use'
			emphasis
		link, url='https://www.linkedin.com/company/openmartai/'
			image
		link, url='https://x.com/openmartai'
			image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/658e948ced55ff3bccca3fd2_Social%20Icons4.svg'
	generic
		[c] dialog Intercom live chat, center=(1876,1036), modal=False, title=Intercom live chat
```
</details>



```
RootWebArea Openmart: Automate SMB Sales Research at Scale, focused, url='https://www.openmart.com/'
	dialog Cookie Consent Prompt, modal=False
		StaticText We use essential cookies to make our site work. With your consent, we may also use non-essential cookies to improve user experience and analyze website traffic. By clicking “Accept,” you agree to our website's cookie use as described in our
		[55] link Cookie Policy, center=(621,1019)
		StaticText . You can change your cookie settings at any time by clicking “
```
<details><summary>Show more</summary>

```
		[56] link Preferences, center=(1019,1019)
		StaticText .”
		[58] button Preferences, center=(1285,1009)
		[59] button Decline, center=(1452,1009)
		[60] button Accept, center=(1618,1009)
	banner
		[68] link home, center=(379,39), url='https://www.openmart.com/'
			image logo, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/6724319567afcbb10436819a_Group%205%20(4).svg'
		navigation
			[73] button Products, center=(537,39), expanded=True, focused, hasPopup='menu'
			navigation Products
				[77] link Owner Finder, center=(545,91), url='https://www.openmart.com/products/owner-finder'
				[78] link Monitoring, center=(545,135), url='https://www.openmart.com/products/monitoring'
				[79] link Prospecting, center=(545,179), url='https://www.openmart.com/products/prospecting'
				[80] link Enrichments, center=(545,223), url='https://www.openmart.com/products/enrichments'
			[81] link Customers, center=(645,39), url='https://www.openmart.com/#section-reviews'
			[82] link Blogs, center=(730,39), url='https://www.openmart.com/blog'
			[83] link Wall of love, center=(820,39), url='https://www.openmart.com/wall-of-love'
		[85] link Login, center=(1552,39), url='http://app.openmart.com/'
	main
		heading Find newly opened local businesses
		paragraph
			StaticText Join 100+ leading SMB tech companies to do sales more efficiently :)
		[98] link Book a demo, center=(960,558), url='https://www.openmart.com/#'
		image
		image Local Business Intelligence Search, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/66e4a19263d3f7fd7a8f23ed_Group%25201000005699-p-1080.png'
		image Backed by YCombinator, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/66e4a19263d3f7fd7a8f244d_Frame%25201000004993-p-500.png'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/66e4a19363d3f7fd7a8f247b_image%252028-p-500.png'
		image Featured by Forbes, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/66e4a19263d3f7fd7a8f2460_Frame%201000004992.png'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/6734fb89fa42aa5da446b614_produt%20of%20the%20day.png'
		StaticText TRUSTED BY MORE THAN 100+ SMB TECH COMPANIES
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c40fb2137a2a75e7f4b82_Whatnot2.svg'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c40fc89ef36fc13002e38_ali.png'
		image clipboard health, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c3cdb0f0d0a60da0e2d2f_clipboard%20health.png'
		image snackpass, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c3cdb8d4f507a73ba09dd_snackpass.svg'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c40fc418af7ad253401b6_boosrly%202.png'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c40fb2137a2a75e7f4b82_Whatnot2.svg'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c40fc89ef36fc13002e38_ali.png'
		image clipboard health, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c3cdb0f0d0a60da0e2d2f_clipboard%20health.png'
		image snackpass, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c3cdb8d4f507a73ba09dd_snackpass.svg'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c40fc418af7ad253401b6_boosrly%202.png'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c40fb2137a2a75e7f4b82_Whatnot2.svg'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c40fc89ef36fc13002e38_ali.png'
		image clipboard health, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c3cdb0f0d0a60da0e2d2f_clipboard%20health.png'
		image snackpass, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c3cdb8d4f507a73ba09dd_snackpass.svg'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c40fc418af7ad253401b6_boosrly%202.png'
		heading Easily find qualified leads
		paragraph
			StaticText Skip the lengthy research. Tell us how you qualify leads, and our AI will do the rest!
		image
		heading AI Leads Finder
		paragraph
			StaticText Enter custom criteria such as annual revenue and geographic location to find qualified leads.
		image
		heading Maps search engine
		paragraph
			StaticText Maps search designed specifically for sales.
		image
		heading Connect with Your CRM
		paragraph
			StaticText Deduplicate leads from your CRM to ensure new results.
		image
		heading Custom Enrichments
		paragraph
			StaticText Add custom enrichments to get more in-depth information on your leads.
		heading Use cases
		tablist, orientation='horizontal'
			tab Leads scraping from all sites, selected=True
				image
			tab Leads qualification, selected=False
				image
			tab Local business data, selected=False
				image
			tab Leads enrichment, selected=False
				image
		tabpanel Leads scraping from all sites
			image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/677f0a8b1f373f2a02b601b4_Frame%201000005255-2.svg'
		heading Here's what our users are saying
		paragraph
			StaticText Join hundreds of the world’s leading growth, sales, and marketing teams—like Clipboard Health, Alibaba, Whatnot, and Snackpass—to sell to the lower mid-market more efficiently.
		tablist, orientation='horizontal'
			tab, selected=True
				image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/677f06c127700621e4d692df_clipboardlogo.png'
			tab, selected=False
				image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/677f074a89065b48403e966e_boostlytransparent.png'
			tab, selected=False
				image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/677f07d41104ac5c3606016d_whatnotlogo-p-500.png'
			tab, selected=False
				image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/677f07fbc7b5cf92614acd66_42logo.svg'
		tabpanel
			image
			paragraph
				StaticText Openmart has revolutionized our outreach strategy! We previously spent spent hundred of man hours identifying decision makers which has been reduced by over 50% with Openmart's decision maker contacts.
			paragraph
				StaticText -
				strong
					StaticText Calvin Bulzoni
				StaticText .
				StaticText Sales Operations at Clipboard Health
		heading Plans for teams of all sizes
		paragraph
			StaticText No matter where you are in your growth or the world, Openmart is designed to save you time and money
		image
		heading Scale Plan
		paragraph
			StaticText For those looking for intent signals and access to owner contacts
		StaticText $999
		StaticText /mo
		StaticText Billed annually
		link Get Started, url='https://www.openmart.com/#'
		image
		StaticText 30,000 credits per month (for verified email, enrichments, export)
		image
		StaticText 5 AI filters for high-quality leads
		image
		StaticText 1M+ business information globally, including decision maker contacts
		image
		strong
			StaticText Signal-based selling tools
		image
		strong
			StaticText Newly opened businesses
		image
		strong
			StaticText 3 Platform Users
		image
		strong
			StaticText CRM Integration
		image
		heading Custom
		paragraph
			StaticText Custom signals based on your needs
		StaticText Contact Us
		StaticText Billed annually
		link Get Started, url='https://www.openmart.com/#'
		image
		strong
			StaticText Everything in Scale Plan
		image
		strong
			StaticText Pre-open businesses (select geographies)
		image
		strong
			StaticText Ad Spend Signals
		image
		strong
			StaticText Hiring Signals
		image
		strong
			StaticText Spot Trending Businesses
		image
		strong
			StaticText Dedicated line with founders
		heading Try Openmart for free
		paragraph
			StaticText Join hundreds of the world’s leading growth, sales, and marketing teams—like Clipboard Health, Alibaba, Whatnot, and Snackpass—to sell to the lower mid-market more efficiently.
		form Email Form
			textbox Enter email, required
			button Try for free
		heading FAQs
		StaticText How do I sign up and get access to Openmart?
		image
		link Get Started, url='https://app.openmart.com/register'
		StaticText Do you provide free trials?
		image
		paragraph
			StaticText Yes.
		link Get Started, url='https://app.openmart.ai/register?code=FREE_7_DAYS_TRIAL'
		StaticText Is a credit card required to sign up for Openmart's free trial?
		image
		paragraph
			StaticText Yes, a credit or debit card is required to sign up for Openmart's free trial. This allows us to verify your account's authenticity and prevent fraud.
		StaticText What's a "Verified" email?
		image
		paragraph
			StaticText After enriching decision maker emails they will either be labeled as "verified" or "unknown". "Verified" emails are emails that have been checked by our system and that it can be delivered. "Unknown"emails are ones that are not able to be fully verified but are able to be delivered to around 80% of the time.
		StaticText How do we verify emails and phone numbers for leads?
		image
		paragraph
			StaticText Email and phone numbers are verified by cross-referencing a number of different data vendors.
		StaticText How can I find more information on my leads? e.g. find dental clinics that are closed on Saturdays.
		image
		paragraph
			StaticText There are 2 ways to do that:
			StaticText ‍
			StaticText 1. Use AI leads finder and input filtering criteria.  e.g. "closed on Saturdays"
			StaticText 2. Use the "add enrichment" function in your leads list to return custom data.
		StaticText Why are there fewer results in my list even though I exported a lot of them?
		image
		paragraph
			StaticText When you export from the AI Leads Finder, the total number of leads is sometimes just an estimate rather than an exact count.
		link logo, url='https://www.openmart.com/'
			image logo, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/6724319567afcbb10436819a_Group%205%20(4).svg'
		link Product Hunt Product of the Day, url='https://www.producthunt.com/products/openmart'
			image Product Hunt Product of the Day, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/66e4a19363d3f7fd7a8f2532_top-post-badge.svg'
		link Featured by TechCrunch, url='https://techcrunch.com/2024/08/21/openmart-wants-to-make-it-easier-for-enterprises-to-sell-to-local-businesses/'
			image Featured by TechCrunch, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/66e4a19663d3f7fd7a8f267f_ddddddddd.png'
		StaticText Products
		link Owner Finder, url='https://www.openmart.com/products/owner-finder'
		link Monitoring, url='https://www.openmart.com/products/monitoring'
		link Prospecting, url='https://www.openmart.com/products/prospecting'
		link Enrichments, url='https://www.openmart.com/products/enrichments'
		StaticText Company
		link About, url='https://www.ycombinator.com/companies/openmart'
		link News, url='https://techcrunch.com/2024/08/21/openmart-wants-to-make-it-easier-for-enterprises-to-sell-to-local-businesses/'
		link Wall of love, url='https://www.openmart.com/wall-of-love'
		StaticText Resources
		link Pricing, url='https://www.openmart.com/pricing'
		link Blog, url='https://www.openmart.com/blog'
		strong
			StaticText INFORMATION
		link FAQs, url='https://www.openmart.com/faqs'
		link sales@openmart.com, url='mailto:sales@openmart.com'
			strong
		emphasis
			StaticText Copyright © OpenMart 2024. All Rights Reserved.
		link Privacy Policy, url='https://www.openmart.com/privacy-policy'
			emphasis
		link Terms & Conditions, url='https://www.openmart.com/terms-of-use'
			emphasis
		link, url='https://www.linkedin.com/company/openmartai/'
			image
		link, url='https://x.com/openmartai'
			image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/658e948ced55ff3bccca3fd2_Social%20Icons4.svg'
	generic
		[c] dialog Intercom live chat, center=(1876,1036), modal=False, title=Intercom live chat
```
</details>

**Reasoning for action:** I clicked on the Products button because I need to explore the offerings available on the Openmart site to find the Owner Finder product. This action is essential as it will allow me to access the specific product page where I can learn more about the Owner Finder and proceed to sign up for the free trial.

**Action:** click(73) # Click on the Products button to explore the offerings.

**Change Description:** After clicking the Products button, the navigation expanded to showcase the product offerings, which include links to Owner Finder, Monitoring, Prospecting, and Enrichments.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://www.openmart.com/

https://www.openmart.com/products/owner-finder

**Content (before/after):** 

```
RootWebArea Openmart: Automate SMB Sales Research at Scale, focused, url='https://www.openmart.com/'
	dialog Cookie Consent Prompt, modal=False
		StaticText We use essential cookies to make our site work. With your consent, we may also use non-essential cookies to improve user experience and analyze website traffic. By clicking “Accept,” you agree to our website's cookie use as described in our
		[55] link Cookie Policy, center=(621,1019)
		StaticText . You can change your cookie settings at any time by clicking “
```
<details><summary>Show more</summary>

```
		[56] link Preferences, center=(1019,1019)
		StaticText .”
		[58] button Preferences, center=(1285,1009)
		[59] button Decline, center=(1452,1009)
		[60] button Accept, center=(1618,1009)
	banner
		[68] link home, center=(379,39), url='https://www.openmart.com/'
			image logo, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/6724319567afcbb10436819a_Group%205%20(4).svg'
		navigation
			[73] button Products, center=(537,39), expanded=True, focused, hasPopup='menu'
			navigation Products
				[77] link Owner Finder, center=(545,91), url='https://www.openmart.com/products/owner-finder'
				[78] link Monitoring, center=(545,135), url='https://www.openmart.com/products/monitoring'
				[79] link Prospecting, center=(545,179), url='https://www.openmart.com/products/prospecting'
				[80] link Enrichments, center=(545,223), url='https://www.openmart.com/products/enrichments'
			[81] link Customers, center=(645,39), url='https://www.openmart.com/#section-reviews'
			[82] link Blogs, center=(730,39), url='https://www.openmart.com/blog'
			[83] link Wall of love, center=(820,39), url='https://www.openmart.com/wall-of-love'
		[85] link Login, center=(1552,39), url='http://app.openmart.com/'
	main
		heading Find newly opened local businesses
		paragraph
			StaticText Join 100+ leading SMB tech companies to do sales more efficiently :)
		[98] link Book a demo, center=(960,558), url='https://www.openmart.com/#'
		image
		image Local Business Intelligence Search, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/66e4a19263d3f7fd7a8f23ed_Group%25201000005699-p-1080.png'
		image Backed by YCombinator, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/66e4a19263d3f7fd7a8f244d_Frame%25201000004993-p-500.png'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/66e4a19363d3f7fd7a8f247b_image%252028-p-500.png'
		image Featured by Forbes, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/66e4a19263d3f7fd7a8f2460_Frame%201000004992.png'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/6734fb89fa42aa5da446b614_produt%20of%20the%20day.png'
		StaticText TRUSTED BY MORE THAN 100+ SMB TECH COMPANIES
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c40fb2137a2a75e7f4b82_Whatnot2.svg'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c40fc89ef36fc13002e38_ali.png'
		image clipboard health, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c3cdb0f0d0a60da0e2d2f_clipboard%20health.png'
		image snackpass, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c3cdb8d4f507a73ba09dd_snackpass.svg'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c40fc418af7ad253401b6_boosrly%202.png'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c40fb2137a2a75e7f4b82_Whatnot2.svg'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c40fc89ef36fc13002e38_ali.png'
		image clipboard health, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c3cdb0f0d0a60da0e2d2f_clipboard%20health.png'
		image snackpass, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c3cdb8d4f507a73ba09dd_snackpass.svg'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c40fc418af7ad253401b6_boosrly%202.png'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c40fb2137a2a75e7f4b82_Whatnot2.svg'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c40fc89ef36fc13002e38_ali.png'
		image clipboard health, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c3cdb0f0d0a60da0e2d2f_clipboard%20health.png'
		image snackpass, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c3cdb8d4f507a73ba09dd_snackpass.svg'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/674c40fc418af7ad253401b6_boosrly%202.png'
		heading Easily find qualified leads
		paragraph
			StaticText Skip the lengthy research. Tell us how you qualify leads, and our AI will do the rest!
		image
		heading AI Leads Finder
		paragraph
			StaticText Enter custom criteria such as annual revenue and geographic location to find qualified leads.
		image
		heading Maps search engine
		paragraph
			StaticText Maps search designed specifically for sales.
		image
		heading Connect with Your CRM
		paragraph
			StaticText Deduplicate leads from your CRM to ensure new results.
		image
		heading Custom Enrichments
		paragraph
			StaticText Add custom enrichments to get more in-depth information on your leads.
		heading Use cases
		tablist, orientation='horizontal'
			tab Leads scraping from all sites, selected=True
				image
			tab Leads qualification, selected=False
				image
			tab Local business data, selected=False
				image
			tab Leads enrichment, selected=False
				image
		tabpanel Leads scraping from all sites
			image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/677f0a8b1f373f2a02b601b4_Frame%201000005255-2.svg'
		heading Here's what our users are saying
		paragraph
			StaticText Join hundreds of the world’s leading growth, sales, and marketing teams—like Clipboard Health, Alibaba, Whatnot, and Snackpass—to sell to the lower mid-market more efficiently.
		tablist, orientation='horizontal'
			tab, selected=True
				image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/677f06c127700621e4d692df_clipboardlogo.png'
			tab, selected=False
				image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/677f074a89065b48403e966e_boostlytransparent.png'
			tab, selected=False
				image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/677f07d41104ac5c3606016d_whatnotlogo-p-500.png'
			tab, selected=False
				image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/677f07fbc7b5cf92614acd66_42logo.svg'
		tabpanel
			image
			paragraph
				StaticText Openmart has revolutionized our outreach strategy! We previously spent spent hundred of man hours identifying decision makers which has been reduced by over 50% with Openmart's decision maker contacts.
			paragraph
				StaticText -
				strong
					StaticText Calvin Bulzoni
				StaticText .
				StaticText Sales Operations at Clipboard Health
		heading Plans for teams of all sizes
		paragraph
			StaticText No matter where you are in your growth or the world, Openmart is designed to save you time and money
		image
		heading Scale Plan
		paragraph
			StaticText For those looking for intent signals and access to owner contacts
		StaticText $999
		StaticText /mo
		StaticText Billed annually
		link Get Started, url='https://www.openmart.com/#'
		image
		StaticText 30,000 credits per month (for verified email, enrichments, export)
		image
		StaticText 5 AI filters for high-quality leads
		image
		StaticText 1M+ business information globally, including decision maker contacts
		image
		strong
			StaticText Signal-based selling tools
		image
		strong
			StaticText Newly opened businesses
		image
		strong
			StaticText 3 Platform Users
		image
		strong
			StaticText CRM Integration
		image
		heading Custom
		paragraph
			StaticText Custom signals based on your needs
		StaticText Contact Us
		StaticText Billed annually
		link Get Started, url='https://www.openmart.com/#'
		image
		strong
			StaticText Everything in Scale Plan
		image
		strong
			StaticText Pre-open businesses (select geographies)
		image
		strong
			StaticText Ad Spend Signals
		image
		strong
			StaticText Hiring Signals
		image
		strong
			StaticText Spot Trending Businesses
		image
		strong
			StaticText Dedicated line with founders
		heading Try Openmart for free
		paragraph
			StaticText Join hundreds of the world’s leading growth, sales, and marketing teams—like Clipboard Health, Alibaba, Whatnot, and Snackpass—to sell to the lower mid-market more efficiently.
		form Email Form
			textbox Enter email, required
			button Try for free
		heading FAQs
		StaticText How do I sign up and get access to Openmart?
		image
		link Get Started, url='https://app.openmart.com/register'
		StaticText Do you provide free trials?
		image
		paragraph
			StaticText Yes.
		link Get Started, url='https://app.openmart.ai/register?code=FREE_7_DAYS_TRIAL'
		StaticText Is a credit card required to sign up for Openmart's free trial?
		image
		paragraph
			StaticText Yes, a credit or debit card is required to sign up for Openmart's free trial. This allows us to verify your account's authenticity and prevent fraud.
		StaticText What's a "Verified" email?
		image
		paragraph
			StaticText After enriching decision maker emails they will either be labeled as "verified" or "unknown". "Verified" emails are emails that have been checked by our system and that it can be delivered. "Unknown"emails are ones that are not able to be fully verified but are able to be delivered to around 80% of the time.
		StaticText How do we verify emails and phone numbers for leads?
		image
		paragraph
			StaticText Email and phone numbers are verified by cross-referencing a number of different data vendors.
		StaticText How can I find more information on my leads? e.g. find dental clinics that are closed on Saturdays.
		image
		paragraph
			StaticText There are 2 ways to do that:
			StaticText ‍
			StaticText 1. Use AI leads finder and input filtering criteria.  e.g. "closed on Saturdays"
			StaticText 2. Use the "add enrichment" function in your leads list to return custom data.
		StaticText Why are there fewer results in my list even though I exported a lot of them?
		image
		paragraph
			StaticText When you export from the AI Leads Finder, the total number of leads is sometimes just an estimate rather than an exact count.
		link logo, url='https://www.openmart.com/'
			image logo, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/6724319567afcbb10436819a_Group%205%20(4).svg'
		link Product Hunt Product of the Day, url='https://www.producthunt.com/products/openmart'
			image Product Hunt Product of the Day, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/66e4a19363d3f7fd7a8f2532_top-post-badge.svg'
		link Featured by TechCrunch, url='https://techcrunch.com/2024/08/21/openmart-wants-to-make-it-easier-for-enterprises-to-sell-to-local-businesses/'
			image Featured by TechCrunch, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/66e4a19663d3f7fd7a8f267f_ddddddddd.png'
		StaticText Products
		link Owner Finder, url='https://www.openmart.com/products/owner-finder'
		link Monitoring, url='https://www.openmart.com/products/monitoring'
		link Prospecting, url='https://www.openmart.com/products/prospecting'
		link Enrichments, url='https://www.openmart.com/products/enrichments'
		StaticText Company
		link About, url='https://www.ycombinator.com/companies/openmart'
		link News, url='https://techcrunch.com/2024/08/21/openmart-wants-to-make-it-easier-for-enterprises-to-sell-to-local-businesses/'
		link Wall of love, url='https://www.openmart.com/wall-of-love'
		StaticText Resources
		link Pricing, url='https://www.openmart.com/pricing'
		link Blog, url='https://www.openmart.com/blog'
		strong
			StaticText INFORMATION
		link FAQs, url='https://www.openmart.com/faqs'
		link sales@openmart.com, url='mailto:sales@openmart.com'
			strong
		emphasis
			StaticText Copyright © OpenMart 2024. All Rights Reserved.
		link Privacy Policy, url='https://www.openmart.com/privacy-policy'
			emphasis
		link Terms & Conditions, url='https://www.openmart.com/terms-of-use'
			emphasis
		link, url='https://www.linkedin.com/company/openmartai/'
			image
		link, url='https://x.com/openmartai'
			image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/658e948ced55ff3bccca3fd2_Social%20Icons4.svg'
	generic
		[c] dialog Intercom live chat, center=(1876,1036), modal=False, title=Intercom live chat
```
</details>



```
RootWebArea Owner Finder, focused, url='https://www.openmart.com/products/owner-finder'
	dialog Cookie Consent Prompt, modal=False
		StaticText We use essential cookies to make our site work. With your consent, we may also use non-essential cookies to improve user experience and analyze website traffic. By clicking “Accept,” you agree to our website's cookie use as described in our
		[54] link Cookie Policy, center=(621,1019)
		StaticText . You can change your cookie settings at any time by clicking “
```
<details><summary>Show more</summary>

```
		[55] link Preferences, center=(1019,1019)
		StaticText .”
		[57] button Preferences, center=(1285,1009)
		[58] button Decline, center=(1452,1009)
		[59] button Accept, center=(1618,1009)
	banner
		[67] link home, center=(379,39), url='https://www.openmart.com/'
			image logo, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/6724319567afcbb10436819a_Group%205%20(4).svg'
		navigation
			[72] button Products, center=(537,39), expanded=False, hasPopup='menu'
			[80] link Customers, center=(645,39), url='https://www.openmart.com/#section-reviews'
			[81] link Blogs, center=(730,39), url='https://www.openmart.com/blog'
			[82] link Wall of love, center=(820,39), url='https://www.openmart.com/wall-of-love'
		[84] link Login, center=(1552,39), url='http://app.openmart.com/'
	main
		heading Get owner contacts in seconds
		image
		image
		image
		image
		image
		paragraph
			strong
				StaticText 4.8
			StaticText /5 with 100+ reviews
		[111] link Try for free, center=(450,599), url='https://app.openmart.com/register?code=FREE_3_DAYS_TRIAL&plan=SHOW_ALL_PLANS'
		[112] link Book a demo, center=(612,599), url='https://www.openmart.com/products/owner-finder#'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/675ff695b48984e4331c758c_image-png_4UhFsdMQF9wBOjP5UXBp-p-1080.png'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/675c06c6d8f41f496c51ebc1_hero-grid.svg'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/675c06c6091590353e9b3ac1_hero-elipses.svg'
		heading Streamlined mobile data from leading providers
		paragraph
			StaticText Achieve unmatched data quality with our comprehensive approach:
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/675c2374e1cc7d0f978f0493_providers-p-800.png'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/675c2375b17f28fb732d0f00_providers-elipse.svg'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/675c26e807c84f9e0c3ba23c_icon.svg'
		StaticText Comprehensive data
		paragraph
			StaticText Get the most reliable mobile data from top providers. Our process ensures quality and up-to-date data.
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/675c26e807c84f9e0c3ba23c_icon.svg'
		StaticText Verified call accuracy
		paragraph
			StaticText Use our tools to check and improve phone data. Get better results with verified contact information.
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/675c26e807c84f9e0c3ba23c_icon.svg'
		StaticText Fill data gaps
		paragraph
			StaticText Fix incomplete or old CRM data automatically. Keep your contact lists current and complete.
		heading Mobile finder
		paragraph
			StaticText We integrate data from top mobile providers and proprietary sources to deliver accurate mobile numbers. Clean your pipeline and boost conversion rates with reliable contact data.
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/675c06c7714406fbdf1a0675_finder-p-800.png'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/675c06c641ccc9d0275ede4c_Group%201000005604.svg'
		StaticText empowering decisions
		StaticText with trusted mobile data
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/675c06c684b8732370da2194_Group%201000005605.svg'
		heading Unlock owner insights with mobile finder
		paragraph
			StaticText With waterfall engineering, we integrate data from top mobile providers and proprietary sources, delivering unparalleled accuracy and precision. Simplify your decision-making process with data you can trust.
		image
		StaticText Smart name detection
		paragraph
			StaticText Find accurate owner details pulled from news, social media, and other official sources. Get verified information you can trust.
		image
		StaticText Advanced waterfall engineering
		paragraph
			StaticText Combine data from top mobile providers and our own databases. Get precise data that fits your business needs.
		image
		StaticText Real-time Updates
		paragraph
			StaticText Never deal with old data again. We keep your CRM fresh with the latest information.
		image
		StaticText Data protection
		paragraph
			StaticText We protect your data with top security measures. Your information stays safe and private.
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/675c06c6091590353e9b3abe_elipses.svg'
		heading Try Openmart for free
		paragraph
			StaticText Join hundreds of the world’s leading growth, sales, and marketing teams—like Clipboard Health, Alibaba, Whatnot, and Snackpass—to sell to the lower mid-market more efficiently.
		form Email Form
			textbox Enter email, required
			button Try for free
		heading FAQs
		StaticText How do I sign up and get access to Openmart?
		image
		link Get Started, url='https://app.openmart.com/register'
		StaticText Do you provide free trials?
		image
		paragraph
			StaticText Yes.
		link Get Started, url='https://app.openmart.ai/register?code=FREE_7_DAYS_TRIAL'
		StaticText Is a credit card required to sign up for Openmart's free trial?
		image
		paragraph
			StaticText Yes, a credit or debit card is required to sign up for Openmart's free trial. This allows us to verify your account's authenticity and prevent fraud.
		StaticText What's a "Verified" email?
		image
		paragraph
			StaticText After enriching decision maker emails they will either be labeled as "verified" or "unknown". "Verified" emails are emails that have been checked by our system and that it can be delivered. "Unknown"emails are ones that are not able to be fully verified but are able to be delivered to around 80% of the time.
		StaticText How do we verify emails and phone numbers for leads?
		image
		paragraph
			StaticText Email and phone numbers are verified by cross-referencing a number of different data vendors.
		StaticText How can I find more information on my leads? e.g. find dental clinics that are closed on Saturdays.
		image
		paragraph
			StaticText There are 2 ways to do that:
			StaticText ‍
			StaticText 1. Use AI leads finder and input filtering criteria.  e.g. "closed on Saturdays"
			StaticText 2. Use the "add enrichment" function in your leads list to return custom data.
		StaticText Why are there fewer results in my list even though I exported a lot of them?
		image
		paragraph
			StaticText When you export from the AI Leads Finder, the total number of leads is sometimes just an estimate rather than an exact count.
		link logo, url='https://www.openmart.com/'
			image logo, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/6724319567afcbb10436819a_Group%205%20(4).svg'
		link Product Hunt Product of the Day, url='https://www.producthunt.com/products/openmart'
			image Product Hunt Product of the Day, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/66e4a19363d3f7fd7a8f2532_top-post-badge.svg'
		link Featured by TechCrunch, url='https://techcrunch.com/2024/08/21/openmart-wants-to-make-it-easier-for-enterprises-to-sell-to-local-businesses/'
			image Featured by TechCrunch, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/66e4a19663d3f7fd7a8f267f_ddddddddd.png'
		StaticText Products
		link Owner Finder, url='https://www.openmart.com/products/owner-finder'
		link Monitoring, url='https://www.openmart.com/products/monitoring'
		link Prospecting, url='https://www.openmart.com/products/prospecting'
		link Enrichments, url='https://www.openmart.com/products/enrichments'
		StaticText Company
		link About, url='https://www.ycombinator.com/companies/openmart'
		link News, url='https://techcrunch.com/2024/08/21/openmart-wants-to-make-it-easier-for-enterprises-to-sell-to-local-businesses/'
		link Wall of love, url='https://www.openmart.com/wall-of-love'
		StaticText Resources
		link Pricing, url='https://www.openmart.com/pricing'
		link Blog, url='https://www.openmart.com/blog'
		strong
			StaticText INFORMATION
		link FAQs, url='https://www.openmart.com/faqs'
		link sales@openmart.com, url='mailto:sales@openmart.com'
			strong
		emphasis
			StaticText Copyright © OpenMart 2024. All Rights Reserved.
		link Privacy Policy, url='https://www.openmart.com/privacy-policy'
			emphasis
		link Terms & Conditions, url='https://www.openmart.com/terms-of-use'
			emphasis
		link, url='https://www.linkedin.com/company/openmartai/'
			image
		link, url='https://x.com/openmartai'
			image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/658e948ced55ff3bccca3fd2_Social%20Icons4.svg'
	[414] button Open Intercom Messenger, center=(1876,1036)
		image
		image
```
</details>

**Reasoning for action:** By clicking the Owner Finder link, I advanced the task by moving directly to the product page dedicated to Owner Finder. This is crucial because it allows me to explore the specific details and features of this product, which is essential for the user's goal of assessing Owner Finder for obtaining owner contacts. It sets the stage for the next actions, like identifying the 'Try for free' option.

**Action:** click(77) # Click on the Owner Finder link to explore this specific product.

**Change Description:** After clicking the Owner Finder link, the browser navigated to a new page titled 'Owner Finder', where the main content now focuses on features related to obtaining owner contacts and the value of mobile data for sales efficiency, replacing the previous page's general sales automation information. The navigation menu has also updated to reflect the new product context, while the cookie consent dialog remains present.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://www.openmart.com/products/owner-finder

https://app.openmart.com/register?code=FREE_3_DAYS_TRIAL&plan=SHOW_ALL_PLANS

**Content (before/after):** 

```
RootWebArea Owner Finder, focused, url='https://www.openmart.com/products/owner-finder'
	dialog Cookie Consent Prompt, modal=False
		StaticText We use essential cookies to make our site work. With your consent, we may also use non-essential cookies to improve user experience and analyze website traffic. By clicking “Accept,” you agree to our website's cookie use as described in our
		[54] link Cookie Policy, center=(621,1019)
		StaticText . You can change your cookie settings at any time by clicking “
```
<details><summary>Show more</summary>

```
		[55] link Preferences, center=(1019,1019)
		StaticText .”
		[57] button Preferences, center=(1285,1009)
		[58] button Decline, center=(1452,1009)
		[59] button Accept, center=(1618,1009)
	banner
		[67] link home, center=(379,39), url='https://www.openmart.com/'
			image logo, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/6724319567afcbb10436819a_Group%205%20(4).svg'
		navigation
			[72] button Products, center=(537,39), expanded=False, hasPopup='menu'
			[80] link Customers, center=(645,39), url='https://www.openmart.com/#section-reviews'
			[81] link Blogs, center=(730,39), url='https://www.openmart.com/blog'
			[82] link Wall of love, center=(820,39), url='https://www.openmart.com/wall-of-love'
		[84] link Login, center=(1552,39), url='http://app.openmart.com/'
	main
		heading Get owner contacts in seconds
		image
		image
		image
		image
		image
		paragraph
			strong
				StaticText 4.8
			StaticText /5 with 100+ reviews
		[111] link Try for free, center=(450,599), url='https://app.openmart.com/register?code=FREE_3_DAYS_TRIAL&plan=SHOW_ALL_PLANS'
		[112] link Book a demo, center=(612,599), url='https://www.openmart.com/products/owner-finder#'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/675ff695b48984e4331c758c_image-png_4UhFsdMQF9wBOjP5UXBp-p-1080.png'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/675c06c6d8f41f496c51ebc1_hero-grid.svg'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/675c06c6091590353e9b3ac1_hero-elipses.svg'
		heading Streamlined mobile data from leading providers
		paragraph
			StaticText Achieve unmatched data quality with our comprehensive approach:
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/675c2374e1cc7d0f978f0493_providers-p-800.png'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/675c2375b17f28fb732d0f00_providers-elipse.svg'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/675c26e807c84f9e0c3ba23c_icon.svg'
		StaticText Comprehensive data
		paragraph
			StaticText Get the most reliable mobile data from top providers. Our process ensures quality and up-to-date data.
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/675c26e807c84f9e0c3ba23c_icon.svg'
		StaticText Verified call accuracy
		paragraph
			StaticText Use our tools to check and improve phone data. Get better results with verified contact information.
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/675c26e807c84f9e0c3ba23c_icon.svg'
		StaticText Fill data gaps
		paragraph
			StaticText Fix incomplete or old CRM data automatically. Keep your contact lists current and complete.
		heading Mobile finder
		paragraph
			StaticText We integrate data from top mobile providers and proprietary sources to deliver accurate mobile numbers. Clean your pipeline and boost conversion rates with reliable contact data.
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/675c06c7714406fbdf1a0675_finder-p-800.png'
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/675c06c641ccc9d0275ede4c_Group%201000005604.svg'
		StaticText empowering decisions
		StaticText with trusted mobile data
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/675c06c684b8732370da2194_Group%201000005605.svg'
		heading Unlock owner insights with mobile finder
		paragraph
			StaticText With waterfall engineering, we integrate data from top mobile providers and proprietary sources, delivering unparalleled accuracy and precision. Simplify your decision-making process with data you can trust.
		image
		StaticText Smart name detection
		paragraph
			StaticText Find accurate owner details pulled from news, social media, and other official sources. Get verified information you can trust.
		image
		StaticText Advanced waterfall engineering
		paragraph
			StaticText Combine data from top mobile providers and our own databases. Get precise data that fits your business needs.
		image
		StaticText Real-time Updates
		paragraph
			StaticText Never deal with old data again. We keep your CRM fresh with the latest information.
		image
		StaticText Data protection
		paragraph
			StaticText We protect your data with top security measures. Your information stays safe and private.
		image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/675c06c6091590353e9b3abe_elipses.svg'
		heading Try Openmart for free
		paragraph
			StaticText Join hundreds of the world’s leading growth, sales, and marketing teams—like Clipboard Health, Alibaba, Whatnot, and Snackpass—to sell to the lower mid-market more efficiently.
		form Email Form
			textbox Enter email, required
			button Try for free
		heading FAQs
		StaticText How do I sign up and get access to Openmart?
		image
		link Get Started, url='https://app.openmart.com/register'
		StaticText Do you provide free trials?
		image
		paragraph
			StaticText Yes.
		link Get Started, url='https://app.openmart.ai/register?code=FREE_7_DAYS_TRIAL'
		StaticText Is a credit card required to sign up for Openmart's free trial?
		image
		paragraph
			StaticText Yes, a credit or debit card is required to sign up for Openmart's free trial. This allows us to verify your account's authenticity and prevent fraud.
		StaticText What's a "Verified" email?
		image
		paragraph
			StaticText After enriching decision maker emails they will either be labeled as "verified" or "unknown". "Verified" emails are emails that have been checked by our system and that it can be delivered. "Unknown"emails are ones that are not able to be fully verified but are able to be delivered to around 80% of the time.
		StaticText How do we verify emails and phone numbers for leads?
		image
		paragraph
			StaticText Email and phone numbers are verified by cross-referencing a number of different data vendors.
		StaticText How can I find more information on my leads? e.g. find dental clinics that are closed on Saturdays.
		image
		paragraph
			StaticText There are 2 ways to do that:
			StaticText ‍
			StaticText 1. Use AI leads finder and input filtering criteria.  e.g. "closed on Saturdays"
			StaticText 2. Use the "add enrichment" function in your leads list to return custom data.
		StaticText Why are there fewer results in my list even though I exported a lot of them?
		image
		paragraph
			StaticText When you export from the AI Leads Finder, the total number of leads is sometimes just an estimate rather than an exact count.
		link logo, url='https://www.openmart.com/'
			image logo, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/6724319567afcbb10436819a_Group%205%20(4).svg'
		link Product Hunt Product of the Day, url='https://www.producthunt.com/products/openmart'
			image Product Hunt Product of the Day, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/66e4a19363d3f7fd7a8f2532_top-post-badge.svg'
		link Featured by TechCrunch, url='https://techcrunch.com/2024/08/21/openmart-wants-to-make-it-easier-for-enterprises-to-sell-to-local-businesses/'
			image Featured by TechCrunch, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/66e4a19663d3f7fd7a8f267f_ddddddddd.png'
		StaticText Products
		link Owner Finder, url='https://www.openmart.com/products/owner-finder'
		link Monitoring, url='https://www.openmart.com/products/monitoring'
		link Prospecting, url='https://www.openmart.com/products/prospecting'
		link Enrichments, url='https://www.openmart.com/products/enrichments'
		StaticText Company
		link About, url='https://www.ycombinator.com/companies/openmart'
		link News, url='https://techcrunch.com/2024/08/21/openmart-wants-to-make-it-easier-for-enterprises-to-sell-to-local-businesses/'
		link Wall of love, url='https://www.openmart.com/wall-of-love'
		StaticText Resources
		link Pricing, url='https://www.openmart.com/pricing'
		link Blog, url='https://www.openmart.com/blog'
		strong
			StaticText INFORMATION
		link FAQs, url='https://www.openmart.com/faqs'
		link sales@openmart.com, url='mailto:sales@openmart.com'
			strong
		emphasis
			StaticText Copyright © OpenMart 2024. All Rights Reserved.
		link Privacy Policy, url='https://www.openmart.com/privacy-policy'
			emphasis
		link Terms & Conditions, url='https://www.openmart.com/terms-of-use'
			emphasis
		link, url='https://www.linkedin.com/company/openmartai/'
			image
		link, url='https://x.com/openmartai'
			image, url='https://cdn.prod.website-files.com/658be563adc727c27b27070b/658e948ced55ff3bccca3fd2_Social%20Icons4.svg'
	[414] button Open Intercom Messenger, center=(1876,1036)
		image
		image
```
</details>



```
RootWebArea Openmart AI - Sign up, focused, url='https://app.openmart.com/register?code=FREE_3_DAYS_TRIAL&plan=SHOW_ALL_PLANS'
	image Openmart, url='https://app.openmart.com/logoV2.svg'
	heading Welcome!
	[52] button Continue with Google, center=(360,416), type=button
		image
```
<details><summary>Show more</summary>

```
	StaticText OR
	StaticText Enter the credentials to create a new account
	StaticText Email address
	StaticText *
	[65] textbox john@mail.com, center=(360,567), contenteditable=True, type=email
	StaticText Password
	StaticText *
	[71] textbox ************, center=(360,645), contenteditable=True, type=password
	[72] button Create account, center=(360,707), type=submit
	paragraph
		StaticText Have an account?
		[75] link Sign in, center=(298,750), url='https://app.openmart.com/login'
	paragraph
		StaticText By creating an account, you agree to our
		[78] link Terms, center=(433,783), url='https://www.openmart.com/terms-of-use'
		StaticText and
		link Privacy statement, url='https://www.openmart.com/privacy-policy'
		StaticText .
	image register, url='https://hmeigaqpfpoqhfhylxgb.supabase.co/storage/v1/render/image/public/openmart_public/images/login/sign-up-graphic.png?width=1080&quality=75&resize=contain'
	StaticText Trusted by teams at:
	image brands, url='https://hmeigaqpfpoqhfhylxgb.supabase.co/storage/v1/render/image/public/openmart_public/images/login/brands.png?width=640&quality=75&resize=contain'
	alert, atomic
```
</details>

**Reasoning for action:** By clicking on the 'Try for free' link (index 111), I am initiating the process required to access the registration page for the Owner Finder product. This step is crucial because it directly addresses the user's goal of evaluating the product's features for obtaining owner contacts. This action moves me closer to completing the user story by allowing the potential customer to transition from information gathering on the product page to actually signing up for the trial.

**Action:** click(111) # Click on the Try for free link to explore the registration process.

**Change Description:** After clicking the 'Try for free' link, the browser navigated from the Owner Finder product page to the sign-up page for Openmart AI, where the user is now prompted to create an account by entering their email and password, along with options to continue with Google or sign in if they already have an account.

**Screenshot before:****Screenshot after:**---

