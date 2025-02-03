# Task

**Contact Us Form Completion**

As a prospective customer,
I initiate contact with SkyLink,
so that I can inquire about their corporate travel services.

**Success definition:** Given I have accessed the SkyLink homepage and am considering their services
When I click on the 'Get in touch' button and fill out the contact form with my first name
Then I should be directed to the Contact Us page with a form displayed, and my first name should be pre-filled in the form.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.tryskylink.com/

https://www.tryskylink.com/#product

**Content (before/after):** 

```
RootWebArea SkyLink, focused, url='https://www.tryskylink.com/'
	banner
		[20] link home, center=(440,58), url='https://www.tryskylink.com/'
			image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a43_image%20(6).png'
		navigation
```
<details><summary>Show more</summary>

```
			[23] link Product, center=(606,58), url='https://www.tryskylink.com/#product'
			[24] link Security, center=(721,58), url='https://www.tryskylink.com/#security'
			[25] link About Us, center=(842,58), url='https://www.tryskylink.com/#about'
		[30] link Get in touch, center=(1460,58), url='https://www.tryskylink.com/contact-us'
	heading An AI Corporate Travel Agent right in your travelers’ pocket
	paragraph
		StaticText SkyLink integrates with your existing systems to automate booking and non-booking workflows from simple to complex.
	[49] link Get in touch, center=(960,638), url='https://www.tryskylink.com/contact-us'
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a42_Group%2014315.svg'
	heading Developed for the World's Most Sophisticated Corporate Travel Programs
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/66622a6d1561e0a9649b83a7_Group%2014324%20(1).svg'
	heading The Best Corporate Travel Experience for Your People
		strong
	paragraph
		StaticText Chat with
		strong
			StaticText SkyLink
		StaticText just like you would with an agent
	paragraph
		StaticText Book and manage travel right from your messaging application, within seconds
	paragraph
		StaticText Personalize to your  loyalty and travel preferences, every time.
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a0a_Group%2014300.svg'
	paragraph
		StaticText Auto-optimized options to nudge travelers to cost effective options while meeting their objectives
	paragraph
		StaticText Reduce call volume to your TMC saving your people time and you money
	paragraph
		StaticText Automatically implement travel policies, reducing procedural confusion and approval/expense workflows.
	StaticText Personalize to your  loyalty and travel preferences, every time.
	heading SkyLink sits right inside your MS Teams and Slack channels
		strong
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/66622b0607e7c151603830b6_Group%2014325.svg'
	heading SkyLink natively integrates into the following systems:
		strong
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6662128d0bac81fafd649749_Group%2014316.svg'
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/666212985031a77e73466ab9_Mask%20group%20(5).svg'
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/666212a2c0b8bbb658085735_SLA-Slack-from-Salesforce-logo-COLOR-RGB%201.svg'
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/666212aa5031a77e73467a87_pngwing%201.svg'
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/666212b3804001f211abfc40_Subtract.svg'
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/666212bd731c262893c38991_g10.svg'
	paragraph
		StaticText Don’t see what you are looking for? Reach out - we are always adding integrations and would love to hear your preferences
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a36_wave%20(1).svg'
	heading SkyLink is always working to exceed established data security best practices.
		strong
	paragraph
		StaticText We currently maintain the following certifications for our security policies and frameworks. Please contact us to learn more about how we protect you and your travelers' data.
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6662295b6a6959096f6c3512_Group%2014324.svg'
	StaticText SOC2 I
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6662295b6a6959096f6c3512_Group%2014324.svg'
	StaticText SOC2 II
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a1f_Group%2073.svg'
	StaticText Data Privacy
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a20_Group%2073%20(1).svg'
	StaticText Data Privacy
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a21_Group%2073%20(2).svg'
	StaticText Data Privacy
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a22_Group%2073%20(3).svg'
	StaticText Data Privacy
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a35_wave.svg'
	group
		heading About Us
		paragraph
			StaticText SkyLink is Built By Travelers, for Travelers
		image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a18_Rectangle%203469423.svg'
		link, url='https://www.linkedin.com/in/atyab/'
			image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a27_Vector%20(1).svg'
		StaticText Atyab Bhatti
		StaticText Cofounder and CEO
		list
			listitem
				ListMarker •
				StaticText Y Combinator, McKinsey, Malwarebytes
			listitem
				ListMarker •
				StaticText UIUC alum
		image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a39_Mask%20group%20(3).svg'
		image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a29_Rectangle%203469424.png'
		link, url='https://www.linkedin.com/in/kushmaheshwari/'
			image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a27_Vector%20(1).svg'
		StaticText Kush Maheshwari Cofounder and CTO
		list
			listitem
				ListMarker •
				StaticText Y Combinator, Electronic Arts, Skillshare, Rubrik
			listitem
				ListMarker •
				StaticText UIUC alum
		image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a3d_Group%2014294.png'
		image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a2a_Rectangle%203469426.png'
		link, url='https://www.linkedin.com/in/doug-anderson-0a819b4/'
			image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a27_Vector%20(1).svg'
		StaticText Doug Anderson
		list
			listitem
				ListMarker •
				StaticText Former CEO, American Express Global Business Travel
			listitem
				ListMarker •
				StaticText Former CEO, Carlson Wagonlit Travel (CWT)
		image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a3e_Group%2014293.png'
		image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a2b_Rectangle%203469425.png'
		link, url='https://www.linkedin.com/in/john-snyder-0542656/'
			image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a27_Vector%20(1).svg'
		StaticText John Snyder
		list
			listitem
				ListMarker •
				StaticText Former CEO, BCD
			listitem
				ListMarker •
				StaticText 30+ years corporate travel experience
		image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a3c_Mask%20group%20(4).svg'
	contentinfo
		link, url='https://www.tryskylink.com/#'
			image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a19_Mask%20group.svg'
		paragraph
			StaticText © 2024 Jarvis Industries, Inc. All Rights Reserved
		StaticText Company
		link Home, url='https://www.tryskylink.com/'
		link Product, url='https://www.tryskylink.com/#product'
		link Security, url='https://www.tryskylink.com/#security'
		link About Us, url='https://www.tryskylink.com/#about'
		StaticText Resources
		link Terms of Service, url='https://www.tryskylink.com/legal/terms-of-service'
		link Privacy, url='https://www.tryskylink.com/legal/privacy-policy'
```
</details>



```
RootWebArea SkyLink, focused, url='https://www.tryskylink.com/#product'
	banner
		[20] link home, center=(440,1022), url='https://www.tryskylink.com/'
			image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a43_image%20(6).png'
		navigation
```
<details><summary>Show more</summary>

```
			[23] link Product, center=(606,1022), url='https://www.tryskylink.com/#product'
			[24] link Security, center=(721,1022), url='https://www.tryskylink.com/#security'
			[25] link About Us, center=(842,1022), url='https://www.tryskylink.com/#about'
		[30] link Get in touch, center=(1460,1022), url='https://www.tryskylink.com/contact-us'
	heading An AI Corporate Travel Agent right in your travelers’ pocket
	paragraph
		StaticText SkyLink integrates with your existing systems to automate booking and non-booking workflows from simple to complex.
	link Get in touch, url='https://www.tryskylink.com/contact-us'
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a42_Group%2014315.svg'
	heading Developed for the World's Most Sophisticated Corporate Travel Programs
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/66622a6d1561e0a9649b83a7_Group%2014324%20(1).svg'
	heading The Best Corporate Travel Experience for Your People
		strong
	paragraph
		StaticText Chat with
		strong
			StaticText SkyLink
		StaticText just like you would with an agent
	paragraph
		StaticText Book and manage travel right from your messaging application, within seconds
	paragraph
		StaticText Personalize to your  loyalty and travel preferences, every time.
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a0a_Group%2014300.svg'
	paragraph
		StaticText Auto-optimized options to nudge travelers to cost effective options while meeting their objectives
	paragraph
		StaticText Reduce call volume to your TMC saving your people time and you money
	paragraph
		StaticText Automatically implement travel policies, reducing procedural confusion and approval/expense workflows.
	StaticText Personalize to your  loyalty and travel preferences, every time.
	heading SkyLink sits right inside your MS Teams and Slack channels
		strong
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/66622b0607e7c151603830b6_Group%2014325.svg'
	heading SkyLink natively integrates into the following systems:
		strong
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6662128d0bac81fafd649749_Group%2014316.svg'
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/666212985031a77e73466ab9_Mask%20group%20(5).svg'
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/666212a2c0b8bbb658085735_SLA-Slack-from-Salesforce-logo-COLOR-RGB%201.svg'
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/666212aa5031a77e73467a87_pngwing%201.svg'
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/666212b3804001f211abfc40_Subtract.svg'
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/666212bd731c262893c38991_g10.svg'
	paragraph
		StaticText Don’t see what you are looking for? Reach out - we are always adding integrations and would love to hear your preferences
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a36_wave%20(1).svg'
	heading SkyLink is always working to exceed established data security best practices.
		strong
	paragraph
		StaticText We currently maintain the following certifications for our security policies and frameworks. Please contact us to learn more about how we protect you and your travelers' data.
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6662295b6a6959096f6c3512_Group%2014324.svg'
	StaticText SOC2 I
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6662295b6a6959096f6c3512_Group%2014324.svg'
	StaticText SOC2 II
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a1f_Group%2073.svg'
	StaticText Data Privacy
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a20_Group%2073%20(1).svg'
	StaticText Data Privacy
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a21_Group%2073%20(2).svg'
	StaticText Data Privacy
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a22_Group%2073%20(3).svg'
	StaticText Data Privacy
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a35_wave.svg'
	group
		heading About Us
		paragraph
			StaticText SkyLink is Built By Travelers, for Travelers
		image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a18_Rectangle%203469423.svg'
		link, url='https://www.linkedin.com/in/atyab/'
			image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a27_Vector%20(1).svg'
		StaticText Atyab Bhatti
		StaticText Cofounder and CEO
		list
			listitem
				ListMarker •
				StaticText Y Combinator, McKinsey, Malwarebytes
			listitem
				ListMarker •
				StaticText UIUC alum
		image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a39_Mask%20group%20(3).svg'
		image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a29_Rectangle%203469424.png'
		link, url='https://www.linkedin.com/in/kushmaheshwari/'
			image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a27_Vector%20(1).svg'
		StaticText Kush Maheshwari Cofounder and CTO
		list
			listitem
				ListMarker •
				StaticText Y Combinator, Electronic Arts, Skillshare, Rubrik
			listitem
				ListMarker •
				StaticText UIUC alum
		image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a3d_Group%2014294.png'
		image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a2a_Rectangle%203469426.png'
		link, url='https://www.linkedin.com/in/doug-anderson-0a819b4/'
			image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a27_Vector%20(1).svg'
		StaticText Doug Anderson
		list
			listitem
				ListMarker •
				StaticText Former CEO, American Express Global Business Travel
			listitem
				ListMarker •
				StaticText Former CEO, Carlson Wagonlit Travel (CWT)
		image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a3e_Group%2014293.png'
		image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a2b_Rectangle%203469425.png'
		link, url='https://www.linkedin.com/in/john-snyder-0542656/'
			image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a27_Vector%20(1).svg'
		StaticText John Snyder
		list
			listitem
				ListMarker •
				StaticText Former CEO, BCD
			listitem
				ListMarker •
				StaticText 30+ years corporate travel experience
		image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a3c_Mask%20group%20(4).svg'
	contentinfo
		link, url='https://www.tryskylink.com/#'
			image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a19_Mask%20group.svg'
		paragraph
			StaticText © 2024 Jarvis Industries, Inc. All Rights Reserved
		StaticText Company
		link Home, url='https://www.tryskylink.com/'
		link Product, url='https://www.tryskylink.com/#product'
		link Security, url='https://www.tryskylink.com/#security'
		link About Us, url='https://www.tryskylink.com/#about'
		StaticText Resources
		link Terms of Service, url='https://www.tryskylink.com/legal/terms-of-service'
		link Privacy, url='https://www.tryskylink.com/legal/privacy-policy'
```
</details>

**Reasoning for action:** Since the user's goal is to inquire about SkyLink's corporate travel services, the next logical step is to reach the contact page where they can presumably find more information and submit their inquiry. By clicking on the 'Get in touch' link, I am navigating to the appropriate page that should provide a contact form.

**Action:** click(23) # Click on the 'Product' link to explore the product offerings.

**Change Description:** The browser navigated to the 'Product' section of the SkyLink website, updating the URL to 'https://www.tryskylink.com/#product', which also resulted in a shift in focus of the content displayed, notably moving the positions of elements, such as navigation links and headings.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://www.tryskylink.com/#product

https://www.tryskylink.com/contact-us

**Content (before/after):** 

```
RootWebArea SkyLink, focused, url='https://www.tryskylink.com/#product'
	banner
		[20] link home, center=(440,1022), url='https://www.tryskylink.com/'
			image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a43_image%20(6).png'
		navigation
```
<details><summary>Show more</summary>

```
			[23] link Product, center=(606,1022), url='https://www.tryskylink.com/#product'
			[24] link Security, center=(721,1022), url='https://www.tryskylink.com/#security'
			[25] link About Us, center=(842,1022), url='https://www.tryskylink.com/#about'
		[30] link Get in touch, center=(1460,1022), url='https://www.tryskylink.com/contact-us'
	heading An AI Corporate Travel Agent right in your travelers’ pocket
	paragraph
		StaticText SkyLink integrates with your existing systems to automate booking and non-booking workflows from simple to complex.
	link Get in touch, url='https://www.tryskylink.com/contact-us'
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a42_Group%2014315.svg'
	heading Developed for the World's Most Sophisticated Corporate Travel Programs
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/66622a6d1561e0a9649b83a7_Group%2014324%20(1).svg'
	heading The Best Corporate Travel Experience for Your People
		strong
	paragraph
		StaticText Chat with
		strong
			StaticText SkyLink
		StaticText just like you would with an agent
	paragraph
		StaticText Book and manage travel right from your messaging application, within seconds
	paragraph
		StaticText Personalize to your  loyalty and travel preferences, every time.
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a0a_Group%2014300.svg'
	paragraph
		StaticText Auto-optimized options to nudge travelers to cost effective options while meeting their objectives
	paragraph
		StaticText Reduce call volume to your TMC saving your people time and you money
	paragraph
		StaticText Automatically implement travel policies, reducing procedural confusion and approval/expense workflows.
	StaticText Personalize to your  loyalty and travel preferences, every time.
	heading SkyLink sits right inside your MS Teams and Slack channels
		strong
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/66622b0607e7c151603830b6_Group%2014325.svg'
	heading SkyLink natively integrates into the following systems:
		strong
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6662128d0bac81fafd649749_Group%2014316.svg'
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/666212985031a77e73466ab9_Mask%20group%20(5).svg'
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/666212a2c0b8bbb658085735_SLA-Slack-from-Salesforce-logo-COLOR-RGB%201.svg'
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/666212aa5031a77e73467a87_pngwing%201.svg'
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/666212b3804001f211abfc40_Subtract.svg'
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/666212bd731c262893c38991_g10.svg'
	paragraph
		StaticText Don’t see what you are looking for? Reach out - we are always adding integrations and would love to hear your preferences
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a36_wave%20(1).svg'
	heading SkyLink is always working to exceed established data security best practices.
		strong
	paragraph
		StaticText We currently maintain the following certifications for our security policies and frameworks. Please contact us to learn more about how we protect you and your travelers' data.
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6662295b6a6959096f6c3512_Group%2014324.svg'
	StaticText SOC2 I
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6662295b6a6959096f6c3512_Group%2014324.svg'
	StaticText SOC2 II
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a1f_Group%2073.svg'
	StaticText Data Privacy
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a20_Group%2073%20(1).svg'
	StaticText Data Privacy
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a21_Group%2073%20(2).svg'
	StaticText Data Privacy
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a22_Group%2073%20(3).svg'
	StaticText Data Privacy
	image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a35_wave.svg'
	group
		heading About Us
		paragraph
			StaticText SkyLink is Built By Travelers, for Travelers
		image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a18_Rectangle%203469423.svg'
		link, url='https://www.linkedin.com/in/atyab/'
			image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a27_Vector%20(1).svg'
		StaticText Atyab Bhatti
		StaticText Cofounder and CEO
		list
			listitem
				ListMarker •
				StaticText Y Combinator, McKinsey, Malwarebytes
			listitem
				ListMarker •
				StaticText UIUC alum
		image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a39_Mask%20group%20(3).svg'
		image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a29_Rectangle%203469424.png'
		link, url='https://www.linkedin.com/in/kushmaheshwari/'
			image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a27_Vector%20(1).svg'
		StaticText Kush Maheshwari Cofounder and CTO
		list
			listitem
				ListMarker •
				StaticText Y Combinator, Electronic Arts, Skillshare, Rubrik
			listitem
				ListMarker •
				StaticText UIUC alum
		image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a3d_Group%2014294.png'
		image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a2a_Rectangle%203469426.png'
		link, url='https://www.linkedin.com/in/doug-anderson-0a819b4/'
			image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a27_Vector%20(1).svg'
		StaticText Doug Anderson
		list
			listitem
				ListMarker •
				StaticText Former CEO, American Express Global Business Travel
			listitem
				ListMarker •
				StaticText Former CEO, Carlson Wagonlit Travel (CWT)
		image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a3e_Group%2014293.png'
		image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a2b_Rectangle%203469425.png'
		link, url='https://www.linkedin.com/in/john-snyder-0542656/'
			image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a27_Vector%20(1).svg'
		StaticText John Snyder
		list
			listitem
				ListMarker •
				StaticText Former CEO, BCD
			listitem
				ListMarker •
				StaticText 30+ years corporate travel experience
		image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a3c_Mask%20group%20(4).svg'
	contentinfo
		link, url='https://www.tryskylink.com/#'
			image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a19_Mask%20group.svg'
		paragraph
			StaticText © 2024 Jarvis Industries, Inc. All Rights Reserved
		StaticText Company
		link Home, url='https://www.tryskylink.com/'
		link Product, url='https://www.tryskylink.com/#product'
		link Security, url='https://www.tryskylink.com/#security'
		link About Us, url='https://www.tryskylink.com/#about'
		StaticText Resources
		link Terms of Service, url='https://www.tryskylink.com/legal/terms-of-service'
		link Privacy, url='https://www.tryskylink.com/legal/privacy-policy'
```
</details>



```
RootWebArea SkyLink | Contact Us, focused, url='https://www.tryskylink.com/contact-us'
	banner
		[20] link home, center=(440,58), url='https://www.tryskylink.com/'
			image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a43_image%20(6).png'
		navigation
```
<details><summary>Show more</summary>

```
			[23] link Product, center=(819,58), url='https://www.tryskylink.com/#product'
			[24] link Security, center=(934,58), url='https://www.tryskylink.com/#security'
			[25] link About Us, center=(1054,58), url='https://www.tryskylink.com/#about'
		[30] link Get in touch, center=(1460,58), url='https://www.tryskylink.com/contact-us'
	heading Get in Touch
	paragraph
		StaticText If you have any questions or would like to learn more about our Please submit this form to get in contact with us. We look forward to connecting with you!
	StaticText REQUIRED*
	form Email Form 2
		StaticText First Name*
		[47] textbox Enter First Name, center=(768,525), contenteditable=True, required, type=text
		StaticText Last Name*
		[50] textbox Enter Last Name, center=(1152,525), contenteditable=True, required, type=text
		StaticText Email*
		[53] textbox Enter your Email, center=(768,643), contenteditable=True, required, type=email
		StaticText Phone*
		[56] textbox Enter your Phone, center=(1152,643), contenteditable=True, required, type=tel
		StaticText Company Website*
		[59] textbox Enter Company Website, center=(768,761), contenteditable=True, type=text
		StaticText Title*
		[62] textbox Enter your Title, center=(1152,761), contenteditable=True, type=text
		StaticText Comments*
		[65] textbox Message / Comments, center=(960,924), contenteditable=True
		[66] button Send Message, center=(768,1051), contenteditable=True, type=submit
	contentinfo
		link, url='https://www.tryskylink.com/contact-us#'
			image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a19_Mask%20group.svg'
		paragraph
			StaticText © 2024 Jarvis Industries, Inc. All Rights Reserved
		StaticText Company
		link Home, url='https://www.tryskylink.com/'
		link Product, url='https://www.tryskylink.com/#product'
		link Security, url='https://www.tryskylink.com/#security'
		link About Us, url='https://www.tryskylink.com/#about'
		StaticText Resources
		link Terms of Service, url='https://www.tryskylink.com/legal/terms-of-service'
		link Privacy, url='https://www.tryskylink.com/legal/privacy-policy'
```
</details>

**Reasoning for action:** I clicked on the 'Get in touch' button because it is the designated method for initiating communication with SkyLink regarding their corporate travel services. This action directly leads to the Contact Us page, where I can fill out the required contact form. This is a crucial step in advancing towards the user goal of inquiring about their services.

**Action:** click(30) # Click on the 'Get in touch' button to explore contact options.

**Change Description:** After clicking the 'Get in touch' button, the browser navigated to the 'Contact Us' page, where the header changed to 'Get in Touch' and a form was displayed with fields for user input such as name, email, and comments.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://www.tryskylink.com/contact-us

https://www.tryskylink.com/contact-us

**Content (before/after):** 

```
RootWebArea SkyLink | Contact Us, focused, url='https://www.tryskylink.com/contact-us'
	banner
		[20] link home, center=(440,58), url='https://www.tryskylink.com/'
			image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a43_image%20(6).png'
		navigation
```
<details><summary>Show more</summary>

```
			[23] link Product, center=(819,58), url='https://www.tryskylink.com/#product'
			[24] link Security, center=(934,58), url='https://www.tryskylink.com/#security'
			[25] link About Us, center=(1054,58), url='https://www.tryskylink.com/#about'
		[30] link Get in touch, center=(1460,58), url='https://www.tryskylink.com/contact-us'
	heading Get in Touch
	paragraph
		StaticText If you have any questions or would like to learn more about our Please submit this form to get in contact with us. We look forward to connecting with you!
	StaticText REQUIRED*
	form Email Form 2
		StaticText First Name*
		[47] textbox Enter First Name, center=(768,525), contenteditable=True, required, type=text
		StaticText Last Name*
		[50] textbox Enter Last Name, center=(1152,525), contenteditable=True, required, type=text
		StaticText Email*
		[53] textbox Enter your Email, center=(768,643), contenteditable=True, required, type=email
		StaticText Phone*
		[56] textbox Enter your Phone, center=(1152,643), contenteditable=True, required, type=tel
		StaticText Company Website*
		[59] textbox Enter Company Website, center=(768,761), contenteditable=True, type=text
		StaticText Title*
		[62] textbox Enter your Title, center=(1152,761), contenteditable=True, type=text
		StaticText Comments*
		[65] textbox Message / Comments, center=(960,924), contenteditable=True
		[66] button Send Message, center=(768,1051), contenteditable=True, type=submit
	contentinfo
		link, url='https://www.tryskylink.com/contact-us#'
			image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a19_Mask%20group.svg'
		paragraph
			StaticText © 2024 Jarvis Industries, Inc. All Rights Reserved
		StaticText Company
		link Home, url='https://www.tryskylink.com/'
		link Product, url='https://www.tryskylink.com/#product'
		link Security, url='https://www.tryskylink.com/#security'
		link About Us, url='https://www.tryskylink.com/#about'
		StaticText Resources
		link Terms of Service, url='https://www.tryskylink.com/legal/terms-of-service'
		link Privacy, url='https://www.tryskylink.com/legal/privacy-policy'
```
</details>



```
RootWebArea SkyLink | Contact Us, focused, url='https://www.tryskylink.com/contact-us'
	banner
		[20] link home, center=(440,58), url='https://www.tryskylink.com/'
			image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a43_image%20(6).png'
		navigation
```
<details><summary>Show more</summary>

```
			[23] link Product, center=(819,58), url='https://www.tryskylink.com/#product'
			[24] link Security, center=(934,58), url='https://www.tryskylink.com/#security'
			[25] link About Us, center=(1054,58), url='https://www.tryskylink.com/#about'
		[30] link Get in touch, center=(1460,58), url='https://www.tryskylink.com/contact-us'
	heading Get in Touch
	paragraph
		StaticText If you have any questions or would like to learn more about our Please submit this form to get in contact with us. We look forward to connecting with you!
	StaticText REQUIRED*
	form Email Form 2
		StaticText First Name*
		[47] textbox Enter First Name value='John', center=(768,525), contenteditable=True, focused, required, type=text
		StaticText Last Name*
		[50] textbox Enter Last Name, center=(1152,525), contenteditable=True, required, type=text
		StaticText Email*
		[53] textbox Enter your Email, center=(768,643), contenteditable=True, required, type=email
		StaticText Phone*
		[56] textbox Enter your Phone, center=(1152,643), contenteditable=True, required, type=tel
		StaticText Company Website*
		[59] textbox Enter Company Website, center=(768,761), contenteditable=True, type=text
		StaticText Title*
		[62] textbox Enter your Title, center=(1152,761), contenteditable=True, type=text
		StaticText Comments*
		[65] textbox Message / Comments, center=(960,924), contenteditable=True
		[66] button Send Message, center=(768,1051), contenteditable=True, type=submit
	contentinfo
		link, url='https://www.tryskylink.com/contact-us#'
			image, url='https://cdn.prod.website-files.com/6648ce4b1bfe7458ebef186a/6648ce4b1bfe7458ebef1a19_Mask%20group.svg'
		paragraph
			StaticText © 2024 Jarvis Industries, Inc. All Rights Reserved
		StaticText Company
		link Home, url='https://www.tryskylink.com/'
		link Product, url='https://www.tryskylink.com/#product'
		link Security, url='https://www.tryskylink.com/#security'
		link About Us, url='https://www.tryskylink.com/#about'
		StaticText Resources
		link Terms of Service, url='https://www.tryskylink.com/legal/terms-of-service'
		link Privacy, url='https://www.tryskylink.com/legal/privacy-policy'
```
</details>

**Reasoning for action:** By filling in the First Name field with 'John', I am taking a crucial step towards completing the contact form as specified in the acceptance test. This action directly addresses the requirement of pre-filling my first name in the form which is part of successfully initiating the inquiry with SkyLink. Once this field is filled, the next step will be to review or fill any other required fields before submitting the form.

**Action:** fill('47', 'John') # Fill in the First Name field with 'John'.

**Change Description:** The First Name field in the form was filled with the value 'John', updating its state to display 'John' as the current input, while the field remained focused.

**Screenshot before:****Screenshot after:**---

