# Task

**Explore Privacy Policy and Download App**

As a potential Blaze payments user,
I learn about the privacy practices and explore downloading the Blaze app,
so that I can make informed decisions about using the service while accessing it conveniently.

**Success definition:** Given I am a visitor on the Blaze Payments website
When I click on the privacy policy link and then attempt to download the Blaze app
Then I should be able to view the privacy policy information and also receive clear options for downloading the app, such as a QR code and links for Google Play and the App Store.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://blaze.money/

chrome-error://chromewebdata/

**Content (before/after):** 

```
RootWebArea Blaze - Damn good payments, focused, url='https://blaze.money/'
	main
		paragraph
			StaticText We use cookies to optimise our services. Read our
			[104] link privacy policy, center=(1052,1062), url='https://privacy-policy/'
```
<details><summary>Show more</summary>

```
			StaticText .
		[105] button Deny, center=(1127,1062)
		[106] button Accept, center=(1182,1062)
		[113] link, center=(115,44), url='https://blaze.money/en'
			image
		[117] link PAYMENTS, center=(754,44), title=Blaze - Global payments, url='https://blaze.money/en'
		[119] link BUSINESS, center=(868,44), title=Blaze - For business, url='https://blaze.money/en/for-business'
		[121] link ABOUT, center=(969,44), title=Blaze - About us, url='https://blaze.money/en/about'
		[123] link CAREERS, center=(1066,44), title=Blaze - Careers, url='https://blaze.money/en/careers'
		[125] link CONTACT, center=(1172,44), title=Blaze - Contact, url='https://blaze.money/en/contact'
		StaticText En
		StaticText Es
		[131] button Download Download Blaze, center=(1820,44), inner_text=Download
			image Download Blaze, url='https://blaze.money/images/ArrowLong.svg'
		[130] div, center=(1735,44), inner_text=Es, title=Blaze - Select language
		[129] div, center=(1710,44), inner_text=En, title=Blaze - Select language
		heading GLOBAL MONEY LOCAL FEEL
		heading Blaze makes international payments made simple. Send, receive, and manage money across borders—instantly and almost free.
		[146] button Download Download Blaze, center=(116,994), inner_text=Download
			image Download Blaze, url='https://blaze.money/images/ArrowLong.svg'
		image Blaze Hero 1, url='https://blaze.money/_next/image?url=%2Fimages%2Fhome%2Fblaze-payments-slide-1.jpg&w=3840&q=75'
		image Blaze - Pay your teacher, url='https://blaze.money/_next/image?url=%2Fimages%2Fhome%2Fcase-1.png&w=3840&q=75'
		image Blaze Hero 1, url='https://blaze.money/_next/image?url=%2Fimages%2Fhome%2Fblaze-payments-slide-2.jpg&w=3840&q=75'
		image Blaze - Pay your teacher, url='https://blaze.money/_next/image?url=%2Fimages%2Fhome%2Fcase-2.png&w=1080&q=75'
		image Blaze Hero 1, url='https://blaze.money/_next/image?url=%2Fimages%2Fhome%2Fblaze-payments-slide-3.jpg&w=3840&q=75'
		image Blaze - Pay your teacher, url='https://blaze.money/_next/image?url=%2Fimages%2Fhome%2Fcase-3.png&w=1080&q=75'
		button
		button
		button
		paragraph
			StaticText We’re backed by
			image Y Combinator logo, url='https://blaze.money/images/yc-logo.svg'
			StaticText – the fund behind top companies
		image Coinbase logo, url='https://blaze.money/images/logos/yc-group/logo-coinbase.svg'
		image Coinbase logo, url='https://blaze.money/images/logos/yc-group/logo-airbnb.svg'
		image Dropbox logo, url='https://blaze.money/images/logos/yc-group/logo-dropbox.svg'
		image Stripe logo, url='https://blaze.money/images/logos/yc-group/logo-stripe.svg'
		image GitLab logo, url='https://blaze.money/images/logos/yc-group/logo-gitlab.svg'
		image Brex logo, url='https://blaze.money/images/logos/yc-group/logo-brex.svg'
		image Webflos logo, url='https://blaze.money/images/logos/yc-group/logo-webflow.svg'
		image Deel logo, url='https://blaze.money/images/logos/yc-group/logo-deel.svg'
		heading SEND MONEY AROUND THE WORLD
		paragraph
			StaticText Transfer money instantly to friends, family, or business contacts around the globe. Blaze supports 34 countries, ensuring your payments reach their destination without delay.
		heading ENJOY A SOCIAL PAYMENT EXPERIENCE
		paragraph
			StaticText See what’s up on Blaze–with Blaze’s network feed, see real-time updates of transactions and discover exciting things happening around you, like nearby events or vetted restaurants in expat hubs.
		heading PAY LIKE A LOCAL ANYWHERE
		paragraph
			StaticText Whether you're paying for a meal, buying something online, or settling up with friends, Blaze allows you to handle payments like a local, using the currency that’s most convenient.
		heading USE PAYMENT LINKS TO PAY FREELANCERS AND VENDORS
		paragraph
			StaticText Don’t worry about bank details—just create a Blaze Payment Link and share it. Request payments from clients or send funds to collaborators.
		heading NEARLY FREE TRANSFERS BETWEEN ANY GLOBAL CURRENCY
		paragraph
			StaticText Send US dollars to Mexico or Mexican Pesos to France. Use any global currency you prefer when paying friends or meeting people on the go. We use a digital US dollar as the underlying asset to ensure maximum stability and avoid currency fluctuations.
		paragraph
			link Supported countries, url='https://blaze.money/#'
			link Coming soon, url='https://blaze.money/#'
		image CAN, url='https://blaze.money/images/countries/flag-canada.svg'
		StaticText Canada
		image USA, url='https://blaze.money/images/countries/flag-usa.svg'
		StaticText United States
		image MEX, url='https://blaze.money/images/countries/flag-mexico.svg'
		StaticText Mexico
		image GUA, url='https://blaze.money/images/countries/flag-guatemala.svg'
		StaticText Guatemala
		image BLZ, url='https://blaze.money/images/countries/flag-belize.svg'
		StaticText Belize
		image HON, url='https://blaze.money/images/countries/flag-honduras.svg'
		StaticText Honduras
		image SLV, url='https://blaze.money/images/countries/flag-el-salvador.svg'
		StaticText El Salvador
		image NIC, url='https://blaze.money/images/countries/flag-nicaragua.svg'
		StaticText Nicaragua
		image CRI, url='https://blaze.money/images/countries/flag-costa-rica.svg'
		StaticText Costa Rica
		image PAN, url='https://blaze.money/images/countries/flag-panama.svg'
		StaticText Panama
		image CUB, url='https://blaze.money/images/countries/flag-cuba.svg'
		StaticText Cuba
		image DOM, url='https://blaze.money/images/countries/flag-dominican-republic.svg'
		StaticText Dominican Republic
		image HTI, url='https://blaze.money/images/countries/flag-haiti.svg'
		StaticText Haiti
		image JAM, url='https://blaze.money/images/countries/flag-jamaica.svg'
		StaticText Jamaica
		image BHS, url='https://blaze.money/images/countries/flag-bahamas.svg'
		StaticText Bahamas
		image TTO, url='https://blaze.money/images/countries/flag-trinidad-and-tobago.svg'
		StaticText Trinidad and Tobago
		image COL, url='https://blaze.money/images/countries/flag-colombia.svg'
		StaticText Colombia
		image VEN, url='https://blaze.money/images/countries/flag-venezuela.svg'
		StaticText Venezuela
		image GUY, url='https://blaze.money/images/countries/flag-guyana.svg'
		StaticText Guyana
		image SUR, url='https://blaze.money/images/countries/flag-suriname.svg'
		StaticText Suriname
		image ECU, url='https://blaze.money/images/countries/flag-ecuador.svg'
		StaticText Ecuador
		image PER, url='https://blaze.money/images/countries/flag-peru.svg'
		StaticText Peru
		image BOL, url='https://blaze.money/images/countries/flag-bolivia.svg'
		StaticText Bolivia
		image BRA, url='https://blaze.money/images/countries/flag-brazil.svg'
		StaticText Brazil
		image PAR, url='https://blaze.money/images/countries/flag-paraguay.svg'
		StaticText Paraguay
		image CHI, url='https://blaze.money/images/countries/flag-chile.svg'
		StaticText Chile
		image ARG, url='https://blaze.money/images/countries/flag-argentina.svg'
		StaticText Argentina
		image URU, url='https://blaze.money/images/countries/flag-uruguay.svg'
		StaticText Uruguay
		paragraph
			StaticText DOWNLOAD APP
		link, url='https://blaze.money/en'
			image
		link Payments, url='https://blaze.money/en'
			paragraph
		link Business, url='https://blaze.money/en/for-business'
			paragraph
		link About, url='https://blaze.money/en/about'
			paragraph
		link Careers, url='https://blaze.money/en/careers'
			paragraph
		link Contact, url='https://blaze.money/en/contact'
			paragraph
		link Blaze on X, url='https://twitter.com/blaze_payments'
			image Blaze on X, url='https://blaze.money/images/social-x.svg'
		link Blaze on Instagram, url='https://www.instagram.com/blaze.payments/'
			image Blaze on Instagram, url='https://blaze.money/images/social-ig.svg'
		link Blaze on LinkedIn, url='https://www.linkedin.com/company/useblazeapp'
			image Blaze on LinkedIn, url='https://blaze.money/images/social-li.svg'
		button Download Download Blaze
			image Download Blaze, url='https://blaze.money/images/ArrowLong.svg'
		paragraph
			StaticText ©2024 Blaze Payments Inc.
		link Terms of service, url='https://blaze.money/en/terms-of-service'
		link Privacy policy, url='https://blaze.money/en/privacy-policy'
	alert, atomic
```
</details>



```
RootWebArea, focused, url='chrome-error://chromewebdata/'
```
**Reasoning for action:** By clicking on the privacy policy link, I am able to access detailed information regarding how Blaze Payments handles user data and privacy. This is essential for the user story as it fulfills the requirement for the potential user to learn about the privacy practices, thus allowing them to make an informed decision regarding the service.

**Action:** click(104) # Click on the privacy policy link to explore more about their privacy practices.

**Change Description:** The agent clicked on the privacy policy link, which resulted in navigating away from the Blaze website to a 'chrome-error://chromewebdata/' page, indicating that the intended privacy policy page could not be loaded.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

chrome-error://chromewebdata/

https://blaze.money/

**Content (before/after):** 

```
RootWebArea, focused, url='chrome-error://chromewebdata/'
```


```
RootWebArea Blaze - Damn good payments, focused, url='https://blaze.money/'
	main
		paragraph
			StaticText We use cookies to optimise our services. Read our
			[97] link privacy policy, center=(1052,1062), url='https://privacy-policy/'
```
<details><summary>Show more</summary>

```
			StaticText .
		[98] button Deny, center=(1127,1062)
		[99] button Accept, center=(1182,1062)
		[106] link, center=(115,44), url='https://blaze.money/en'
			image
		[110] link PAYMENTS, center=(754,44), title=Blaze - Global payments, url='https://blaze.money/en'
		[112] link BUSINESS, center=(868,44), title=Blaze - For business, url='https://blaze.money/en/for-business'
		[114] link ABOUT, center=(969,44), title=Blaze - About us, url='https://blaze.money/en/about'
		[116] link CAREERS, center=(1066,44), title=Blaze - Careers, url='https://blaze.money/en/careers'
		[118] link CONTACT, center=(1172,44), title=Blaze - Contact, url='https://blaze.money/en/contact'
		StaticText En
		StaticText Es
		[124] button Download Download Blaze, center=(1820,44), inner_text=Download
			image Download Blaze, url='https://blaze.money/images/ArrowLong.svg'
		[123] div, center=(1735,44), inner_text=Es, title=Blaze - Select language
		[122] div, center=(1710,44), inner_text=En, title=Blaze - Select language
		heading GLOBAL MONEY LOCAL FEEL
		heading Blaze makes international payments made simple. Send, receive, and manage money across borders—instantly and almost free.
		[139] button Download Download Blaze, center=(116,994), inner_text=Download
			image Download Blaze, url='https://blaze.money/images/ArrowLong.svg'
		image Blaze Hero 1, url='https://blaze.money/_next/image?url=%2Fimages%2Fhome%2Fblaze-payments-slide-1.jpg&w=3840&q=75'
		image Blaze - Pay your teacher, url='https://blaze.money/_next/image?url=%2Fimages%2Fhome%2Fcase-1.png&w=3840&q=75'
		image Blaze Hero 1, url='https://blaze.money/_next/image?url=%2Fimages%2Fhome%2Fblaze-payments-slide-2.jpg&w=3840&q=75'
		image Blaze - Pay your teacher, url='https://blaze.money/_next/image?url=%2Fimages%2Fhome%2Fcase-2.png&w=1080&q=75'
		image Blaze Hero 1, url='https://blaze.money/_next/image?url=%2Fimages%2Fhome%2Fblaze-payments-slide-3.jpg&w=3840&q=75'
		image Blaze - Pay your teacher, url='https://blaze.money/_next/image?url=%2Fimages%2Fhome%2Fcase-3.png&w=1080&q=75'
		button
		button
		button
		paragraph
			StaticText We’re backed by
			image Y Combinator logo, url='https://blaze.money/images/yc-logo.svg'
			StaticText – the fund behind top companies
		image Coinbase logo, url='https://blaze.money/images/logos/yc-group/logo-coinbase.svg'
		image Coinbase logo, url='https://blaze.money/images/logos/yc-group/logo-airbnb.svg'
		image Dropbox logo, url='https://blaze.money/images/logos/yc-group/logo-dropbox.svg'
		image Stripe logo, url='https://blaze.money/images/logos/yc-group/logo-stripe.svg'
		image GitLab logo, url='https://blaze.money/images/logos/yc-group/logo-gitlab.svg'
		image Brex logo, url='https://blaze.money/images/logos/yc-group/logo-brex.svg'
		image Webflos logo, url='https://blaze.money/images/logos/yc-group/logo-webflow.svg'
		image Deel logo, url='https://blaze.money/images/logos/yc-group/logo-deel.svg'
		heading SEND MONEY AROUND THE WORLD
		paragraph
			StaticText Transfer money instantly to friends, family, or business contacts around the globe. Blaze supports 34 countries, ensuring your payments reach their destination without delay.
		heading ENJOY A SOCIAL PAYMENT EXPERIENCE
		paragraph
			StaticText See what’s up on Blaze–with Blaze’s network feed, see real-time updates of transactions and discover exciting things happening around you, like nearby events or vetted restaurants in expat hubs.
		heading PAY LIKE A LOCAL ANYWHERE
		paragraph
			StaticText Whether you're paying for a meal, buying something online, or settling up with friends, Blaze allows you to handle payments like a local, using the currency that’s most convenient.
		heading USE PAYMENT LINKS TO PAY FREELANCERS AND VENDORS
		paragraph
			StaticText Don’t worry about bank details—just create a Blaze Payment Link and share it. Request payments from clients or send funds to collaborators.
		heading NEARLY FREE TRANSFERS BETWEEN ANY GLOBAL CURRENCY
		paragraph
			StaticText Send US dollars to Mexico or Mexican Pesos to France. Use any global currency you prefer when paying friends or meeting people on the go. We use a digital US dollar as the underlying asset to ensure maximum stability and avoid currency fluctuations.
		paragraph
			link Supported countries, url='https://blaze.money/#'
			link Coming soon, url='https://blaze.money/#'
		image CAN, url='https://blaze.money/images/countries/flag-canada.svg'
		StaticText Canada
		image USA, url='https://blaze.money/images/countries/flag-usa.svg'
		StaticText United States
		image MEX, url='https://blaze.money/images/countries/flag-mexico.svg'
		StaticText Mexico
		image GUA, url='https://blaze.money/images/countries/flag-guatemala.svg'
		StaticText Guatemala
		image BLZ, url='https://blaze.money/images/countries/flag-belize.svg'
		StaticText Belize
		image HON, url='https://blaze.money/images/countries/flag-honduras.svg'
		StaticText Honduras
		image SLV, url='https://blaze.money/images/countries/flag-el-salvador.svg'
		StaticText El Salvador
		image NIC, url='https://blaze.money/images/countries/flag-nicaragua.svg'
		StaticText Nicaragua
		image CRI, url='https://blaze.money/images/countries/flag-costa-rica.svg'
		StaticText Costa Rica
		image PAN, url='https://blaze.money/images/countries/flag-panama.svg'
		StaticText Panama
		image CUB, url='https://blaze.money/images/countries/flag-cuba.svg'
		StaticText Cuba
		image DOM, url='https://blaze.money/images/countries/flag-dominican-republic.svg'
		StaticText Dominican Republic
		image HTI, url='https://blaze.money/images/countries/flag-haiti.svg'
		StaticText Haiti
		image JAM, url='https://blaze.money/images/countries/flag-jamaica.svg'
		StaticText Jamaica
		image BHS, url='https://blaze.money/images/countries/flag-bahamas.svg'
		StaticText Bahamas
		image TTO, url='https://blaze.money/images/countries/flag-trinidad-and-tobago.svg'
		StaticText Trinidad and Tobago
		image COL, url='https://blaze.money/images/countries/flag-colombia.svg'
		StaticText Colombia
		image VEN, url='https://blaze.money/images/countries/flag-venezuela.svg'
		StaticText Venezuela
		image GUY, url='https://blaze.money/images/countries/flag-guyana.svg'
		StaticText Guyana
		image SUR, url='https://blaze.money/images/countries/flag-suriname.svg'
		StaticText Suriname
		image ECU, url='https://blaze.money/images/countries/flag-ecuador.svg'
		StaticText Ecuador
		image PER, url='https://blaze.money/images/countries/flag-peru.svg'
		StaticText Peru
		image BOL, url='https://blaze.money/images/countries/flag-bolivia.svg'
		StaticText Bolivia
		image BRA, url='https://blaze.money/images/countries/flag-brazil.svg'
		StaticText Brazil
		image PAR, url='https://blaze.money/images/countries/flag-paraguay.svg'
		StaticText Paraguay
		image CHI, url='https://blaze.money/images/countries/flag-chile.svg'
		StaticText Chile
		image ARG, url='https://blaze.money/images/countries/flag-argentina.svg'
		StaticText Argentina
		image URU, url='https://blaze.money/images/countries/flag-uruguay.svg'
		StaticText Uruguay
		paragraph
			StaticText DOWNLOAD APP
		link, url='https://blaze.money/en'
			image
		link Payments, url='https://blaze.money/en'
			paragraph
		link Business, url='https://blaze.money/en/for-business'
			paragraph
		link About, url='https://blaze.money/en/about'
			paragraph
		link Careers, url='https://blaze.money/en/careers'
			paragraph
		link Contact, url='https://blaze.money/en/contact'
			paragraph
		link Blaze on X, url='https://twitter.com/blaze_payments'
			image Blaze on X, url='https://blaze.money/images/social-x.svg'
		link Blaze on Instagram, url='https://www.instagram.com/blaze.payments/'
			image Blaze on Instagram, url='https://blaze.money/images/social-ig.svg'
		link Blaze on LinkedIn, url='https://www.linkedin.com/company/useblazeapp'
			image Blaze on LinkedIn, url='https://blaze.money/images/social-li.svg'
		button Download Download Blaze
			image Download Blaze, url='https://blaze.money/images/ArrowLong.svg'
		paragraph
			StaticText ©2024 Blaze Payments Inc.
		link Terms of service, url='https://blaze.money/en/terms-of-service'
		link Privacy policy, url='https://blaze.money/en/privacy-policy'
	alert, atomic
```
</details>

**Reasoning for action:** I recognized that the current browser state indicates a chrome error page, which means I can't proceed with any actions relevant to the Blaze Payments website from this state. By using the go_back() function, I aim to return to the last accessible page where I can find the necessary link to the privacy policy. This step is crucial for advancing the task, as it will allow me to continue exploring the privacy practices of Blaze Payments and locate options for downloading the Blaze app.

**Action:** go_back() # Navigate back to the previous page to try again.

**Change Description:** The browser navigated back to the previous page, changing the URL from a chrome error page to the Blaze payments website, which introduced various interactive elements including a cookie consent banner, footer links, and content describing the services offered.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://blaze.money/

https://blaze.money/

**Content (before/after):** 

```
RootWebArea Blaze - Damn good payments, focused, url='https://blaze.money/'
	main
		paragraph
			StaticText We use cookies to optimise our services. Read our
			[97] link privacy policy, center=(1052,1062), url='https://privacy-policy/'
```
<details><summary>Show more</summary>

```
			StaticText .
		[98] button Deny, center=(1127,1062)
		[99] button Accept, center=(1182,1062)
		[106] link, center=(115,44), url='https://blaze.money/en'
			image
		[110] link PAYMENTS, center=(754,44), title=Blaze - Global payments, url='https://blaze.money/en'
		[112] link BUSINESS, center=(868,44), title=Blaze - For business, url='https://blaze.money/en/for-business'
		[114] link ABOUT, center=(969,44), title=Blaze - About us, url='https://blaze.money/en/about'
		[116] link CAREERS, center=(1066,44), title=Blaze - Careers, url='https://blaze.money/en/careers'
		[118] link CONTACT, center=(1172,44), title=Blaze - Contact, url='https://blaze.money/en/contact'
		StaticText En
		StaticText Es
		[124] button Download Download Blaze, center=(1820,44), inner_text=Download
			image Download Blaze, url='https://blaze.money/images/ArrowLong.svg'
		[123] div, center=(1735,44), inner_text=Es, title=Blaze - Select language
		[122] div, center=(1710,44), inner_text=En, title=Blaze - Select language
		heading GLOBAL MONEY LOCAL FEEL
		heading Blaze makes international payments made simple. Send, receive, and manage money across borders—instantly and almost free.
		[139] button Download Download Blaze, center=(116,994), inner_text=Download
			image Download Blaze, url='https://blaze.money/images/ArrowLong.svg'
		image Blaze Hero 1, url='https://blaze.money/_next/image?url=%2Fimages%2Fhome%2Fblaze-payments-slide-1.jpg&w=3840&q=75'
		image Blaze - Pay your teacher, url='https://blaze.money/_next/image?url=%2Fimages%2Fhome%2Fcase-1.png&w=3840&q=75'
		image Blaze Hero 1, url='https://blaze.money/_next/image?url=%2Fimages%2Fhome%2Fblaze-payments-slide-2.jpg&w=3840&q=75'
		image Blaze - Pay your teacher, url='https://blaze.money/_next/image?url=%2Fimages%2Fhome%2Fcase-2.png&w=1080&q=75'
		image Blaze Hero 1, url='https://blaze.money/_next/image?url=%2Fimages%2Fhome%2Fblaze-payments-slide-3.jpg&w=3840&q=75'
		image Blaze - Pay your teacher, url='https://blaze.money/_next/image?url=%2Fimages%2Fhome%2Fcase-3.png&w=1080&q=75'
		button
		button
		button
		paragraph
			StaticText We’re backed by
			image Y Combinator logo, url='https://blaze.money/images/yc-logo.svg'
			StaticText – the fund behind top companies
		image Coinbase logo, url='https://blaze.money/images/logos/yc-group/logo-coinbase.svg'
		image Coinbase logo, url='https://blaze.money/images/logos/yc-group/logo-airbnb.svg'
		image Dropbox logo, url='https://blaze.money/images/logos/yc-group/logo-dropbox.svg'
		image Stripe logo, url='https://blaze.money/images/logos/yc-group/logo-stripe.svg'
		image GitLab logo, url='https://blaze.money/images/logos/yc-group/logo-gitlab.svg'
		image Brex logo, url='https://blaze.money/images/logos/yc-group/logo-brex.svg'
		image Webflos logo, url='https://blaze.money/images/logos/yc-group/logo-webflow.svg'
		image Deel logo, url='https://blaze.money/images/logos/yc-group/logo-deel.svg'
		heading SEND MONEY AROUND THE WORLD
		paragraph
			StaticText Transfer money instantly to friends, family, or business contacts around the globe. Blaze supports 34 countries, ensuring your payments reach their destination without delay.
		heading ENJOY A SOCIAL PAYMENT EXPERIENCE
		paragraph
			StaticText See what’s up on Blaze–with Blaze’s network feed, see real-time updates of transactions and discover exciting things happening around you, like nearby events or vetted restaurants in expat hubs.
		heading PAY LIKE A LOCAL ANYWHERE
		paragraph
			StaticText Whether you're paying for a meal, buying something online, or settling up with friends, Blaze allows you to handle payments like a local, using the currency that’s most convenient.
		heading USE PAYMENT LINKS TO PAY FREELANCERS AND VENDORS
		paragraph
			StaticText Don’t worry about bank details—just create a Blaze Payment Link and share it. Request payments from clients or send funds to collaborators.
		heading NEARLY FREE TRANSFERS BETWEEN ANY GLOBAL CURRENCY
		paragraph
			StaticText Send US dollars to Mexico or Mexican Pesos to France. Use any global currency you prefer when paying friends or meeting people on the go. We use a digital US dollar as the underlying asset to ensure maximum stability and avoid currency fluctuations.
		paragraph
			link Supported countries, url='https://blaze.money/#'
			link Coming soon, url='https://blaze.money/#'
		image CAN, url='https://blaze.money/images/countries/flag-canada.svg'
		StaticText Canada
		image USA, url='https://blaze.money/images/countries/flag-usa.svg'
		StaticText United States
		image MEX, url='https://blaze.money/images/countries/flag-mexico.svg'
		StaticText Mexico
		image GUA, url='https://blaze.money/images/countries/flag-guatemala.svg'
		StaticText Guatemala
		image BLZ, url='https://blaze.money/images/countries/flag-belize.svg'
		StaticText Belize
		image HON, url='https://blaze.money/images/countries/flag-honduras.svg'
		StaticText Honduras
		image SLV, url='https://blaze.money/images/countries/flag-el-salvador.svg'
		StaticText El Salvador
		image NIC, url='https://blaze.money/images/countries/flag-nicaragua.svg'
		StaticText Nicaragua
		image CRI, url='https://blaze.money/images/countries/flag-costa-rica.svg'
		StaticText Costa Rica
		image PAN, url='https://blaze.money/images/countries/flag-panama.svg'
		StaticText Panama
		image CUB, url='https://blaze.money/images/countries/flag-cuba.svg'
		StaticText Cuba
		image DOM, url='https://blaze.money/images/countries/flag-dominican-republic.svg'
		StaticText Dominican Republic
		image HTI, url='https://blaze.money/images/countries/flag-haiti.svg'
		StaticText Haiti
		image JAM, url='https://blaze.money/images/countries/flag-jamaica.svg'
		StaticText Jamaica
		image BHS, url='https://blaze.money/images/countries/flag-bahamas.svg'
		StaticText Bahamas
		image TTO, url='https://blaze.money/images/countries/flag-trinidad-and-tobago.svg'
		StaticText Trinidad and Tobago
		image COL, url='https://blaze.money/images/countries/flag-colombia.svg'
		StaticText Colombia
		image VEN, url='https://blaze.money/images/countries/flag-venezuela.svg'
		StaticText Venezuela
		image GUY, url='https://blaze.money/images/countries/flag-guyana.svg'
		StaticText Guyana
		image SUR, url='https://blaze.money/images/countries/flag-suriname.svg'
		StaticText Suriname
		image ECU, url='https://blaze.money/images/countries/flag-ecuador.svg'
		StaticText Ecuador
		image PER, url='https://blaze.money/images/countries/flag-peru.svg'
		StaticText Peru
		image BOL, url='https://blaze.money/images/countries/flag-bolivia.svg'
		StaticText Bolivia
		image BRA, url='https://blaze.money/images/countries/flag-brazil.svg'
		StaticText Brazil
		image PAR, url='https://blaze.money/images/countries/flag-paraguay.svg'
		StaticText Paraguay
		image CHI, url='https://blaze.money/images/countries/flag-chile.svg'
		StaticText Chile
		image ARG, url='https://blaze.money/images/countries/flag-argentina.svg'
		StaticText Argentina
		image URU, url='https://blaze.money/images/countries/flag-uruguay.svg'
		StaticText Uruguay
		paragraph
			StaticText DOWNLOAD APP
		link, url='https://blaze.money/en'
			image
		link Payments, url='https://blaze.money/en'
			paragraph
		link Business, url='https://blaze.money/en/for-business'
			paragraph
		link About, url='https://blaze.money/en/about'
			paragraph
		link Careers, url='https://blaze.money/en/careers'
			paragraph
		link Contact, url='https://blaze.money/en/contact'
			paragraph
		link Blaze on X, url='https://twitter.com/blaze_payments'
			image Blaze on X, url='https://blaze.money/images/social-x.svg'
		link Blaze on Instagram, url='https://www.instagram.com/blaze.payments/'
			image Blaze on Instagram, url='https://blaze.money/images/social-ig.svg'
		link Blaze on LinkedIn, url='https://www.linkedin.com/company/useblazeapp'
			image Blaze on LinkedIn, url='https://blaze.money/images/social-li.svg'
		button Download Download Blaze
			image Download Blaze, url='https://blaze.money/images/ArrowLong.svg'
		paragraph
			StaticText ©2024 Blaze Payments Inc.
		link Terms of service, url='https://blaze.money/en/terms-of-service'
		link Privacy policy, url='https://blaze.money/en/privacy-policy'
	alert, atomic
```
</details>



```
RootWebArea Blaze - Damn good payments, focused, url='https://blaze.money/'
	main
		paragraph
			StaticText We use cookies to optimise our services. Read our
			[97] link privacy policy, center=(1052,1062), url='https://privacy-policy/'
```
<details><summary>Show more</summary>

```
			StaticText .
		[98] button Deny, center=(1127,1062)
		[99] button Accept, center=(1182,1062)
		link, url='https://blaze.money/en'
			image
		link PAYMENTS, url='https://blaze.money/en'
		link BUSINESS, url='https://blaze.money/en/for-business'
		link ABOUT, url='https://blaze.money/en/about'
		link CAREERS, url='https://blaze.money/en/careers'
		link CONTACT, url='https://blaze.money/en/contact'
		StaticText En
		StaticText Es
		button Download Download Blaze, focused
			image Download Blaze, url='https://blaze.money/images/ArrowLong.svg'
		[442] button, center=(1160,294)
			image
		heading SCAN QR CODE TO DOWNLOAD BLAZE
		image QR Code, url='https://blaze.money/images/app-store.svg'
		StaticText or
		[459] link Get it on Google Play, center=(892,738), url='https://blze.at/android-app'
			image Get it on Google Play, url='https://blaze.money/images/download/android-store.svg'
		[461] link Download on the App Store, center=(1028,738), url='https://blze.at/ios-app'
			image Download on the App Store, url='https://blaze.money/images/download/ios-store.svg'
		heading GLOBAL MONEY LOCAL FEEL
		heading Blaze makes international payments made simple. Send, receive, and manage money across borders—instantly and almost free.
		button Download Download Blaze
			image Download Blaze, url='https://blaze.money/images/ArrowLong.svg'
		image Blaze Hero 1, url='https://blaze.money/_next/image?url=%2Fimages%2Fhome%2Fblaze-payments-slide-1.jpg&w=3840&q=75'
		image Blaze - Pay your teacher, url='https://blaze.money/_next/image?url=%2Fimages%2Fhome%2Fcase-1.png&w=3840&q=75'
		image Blaze Hero 1, url='https://blaze.money/_next/image?url=%2Fimages%2Fhome%2Fblaze-payments-slide-2.jpg&w=3840&q=75'
		image Blaze - Pay your teacher, url='https://blaze.money/_next/image?url=%2Fimages%2Fhome%2Fcase-2.png&w=1080&q=75'
		image Blaze Hero 1, url='https://blaze.money/_next/image?url=%2Fimages%2Fhome%2Fblaze-payments-slide-3.jpg&w=3840&q=75'
		image Blaze - Pay your teacher, url='https://blaze.money/_next/image?url=%2Fimages%2Fhome%2Fcase-3.png&w=1080&q=75'
		button
		button
		button
		paragraph
			StaticText We’re backed by
			image Y Combinator logo, url='https://blaze.money/images/yc-logo.svg'
			StaticText – the fund behind top companies
		image Coinbase logo, url='https://blaze.money/images/logos/yc-group/logo-coinbase.svg'
		image Coinbase logo, url='https://blaze.money/images/logos/yc-group/logo-airbnb.svg'
		image Dropbox logo, url='https://blaze.money/images/logos/yc-group/logo-dropbox.svg'
		image Stripe logo, url='https://blaze.money/images/logos/yc-group/logo-stripe.svg'
		image GitLab logo, url='https://blaze.money/images/logos/yc-group/logo-gitlab.svg'
		image Brex logo, url='https://blaze.money/images/logos/yc-group/logo-brex.svg'
		image Webflos logo, url='https://blaze.money/images/logos/yc-group/logo-webflow.svg'
		image Deel logo, url='https://blaze.money/images/logos/yc-group/logo-deel.svg'
		heading SEND MONEY AROUND THE WORLD
		paragraph
			StaticText Transfer money instantly to friends, family, or business contacts around the globe. Blaze supports 34 countries, ensuring your payments reach their destination without delay.
		heading ENJOY A SOCIAL PAYMENT EXPERIENCE
		paragraph
			StaticText See what’s up on Blaze–with Blaze’s network feed, see real-time updates of transactions and discover exciting things happening around you, like nearby events or vetted restaurants in expat hubs.
		heading PAY LIKE A LOCAL ANYWHERE
		paragraph
			StaticText Whether you're paying for a meal, buying something online, or settling up with friends, Blaze allows you to handle payments like a local, using the currency that’s most convenient.
		heading USE PAYMENT LINKS TO PAY FREELANCERS AND VENDORS
		paragraph
			StaticText Don’t worry about bank details—just create a Blaze Payment Link and share it. Request payments from clients or send funds to collaborators.
		heading NEARLY FREE TRANSFERS BETWEEN ANY GLOBAL CURRENCY
		paragraph
			StaticText Send US dollars to Mexico or Mexican Pesos to France. Use any global currency you prefer when paying friends or meeting people on the go. We use a digital US dollar as the underlying asset to ensure maximum stability and avoid currency fluctuations.
		paragraph
			link Supported countries, url='https://blaze.money/#'
			link Coming soon, url='https://blaze.money/#'
		image CAN, url='https://blaze.money/images/countries/flag-canada.svg'
		StaticText Canada
		image USA, url='https://blaze.money/images/countries/flag-usa.svg'
		StaticText United States
		image MEX, url='https://blaze.money/images/countries/flag-mexico.svg'
		StaticText Mexico
		image GUA, url='https://blaze.money/images/countries/flag-guatemala.svg'
		StaticText Guatemala
		image BLZ, url='https://blaze.money/images/countries/flag-belize.svg'
		StaticText Belize
		image HON, url='https://blaze.money/images/countries/flag-honduras.svg'
		StaticText Honduras
		image SLV, url='https://blaze.money/images/countries/flag-el-salvador.svg'
		StaticText El Salvador
		image NIC, url='https://blaze.money/images/countries/flag-nicaragua.svg'
		StaticText Nicaragua
		image CRI, url='https://blaze.money/images/countries/flag-costa-rica.svg'
		StaticText Costa Rica
		image PAN, url='https://blaze.money/images/countries/flag-panama.svg'
		StaticText Panama
		image CUB, url='https://blaze.money/images/countries/flag-cuba.svg'
		StaticText Cuba
		image DOM, url='https://blaze.money/images/countries/flag-dominican-republic.svg'
		StaticText Dominican Republic
		image HTI, url='https://blaze.money/images/countries/flag-haiti.svg'
		StaticText Haiti
		image JAM, url='https://blaze.money/images/countries/flag-jamaica.svg'
		StaticText Jamaica
		image BHS, url='https://blaze.money/images/countries/flag-bahamas.svg'
		StaticText Bahamas
		image TTO, url='https://blaze.money/images/countries/flag-trinidad-and-tobago.svg'
		StaticText Trinidad and Tobago
		image COL, url='https://blaze.money/images/countries/flag-colombia.svg'
		StaticText Colombia
		image VEN, url='https://blaze.money/images/countries/flag-venezuela.svg'
		StaticText Venezuela
		image GUY, url='https://blaze.money/images/countries/flag-guyana.svg'
		StaticText Guyana
		image SUR, url='https://blaze.money/images/countries/flag-suriname.svg'
		StaticText Suriname
		image ECU, url='https://blaze.money/images/countries/flag-ecuador.svg'
		StaticText Ecuador
		image PER, url='https://blaze.money/images/countries/flag-peru.svg'
		StaticText Peru
		image BOL, url='https://blaze.money/images/countries/flag-bolivia.svg'
		StaticText Bolivia
		image BRA, url='https://blaze.money/images/countries/flag-brazil.svg'
		StaticText Brazil
		image PAR, url='https://blaze.money/images/countries/flag-paraguay.svg'
		StaticText Paraguay
		image CHI, url='https://blaze.money/images/countries/flag-chile.svg'
		StaticText Chile
		image ARG, url='https://blaze.money/images/countries/flag-argentina.svg'
		StaticText Argentina
		image URU, url='https://blaze.money/images/countries/flag-uruguay.svg'
		StaticText Uruguay
		paragraph
			StaticText DOWNLOAD APP
		link, url='https://blaze.money/en'
			image
		link Payments, url='https://blaze.money/en'
			paragraph
		link Business, url='https://blaze.money/en/for-business'
			paragraph
		link About, url='https://blaze.money/en/about'
			paragraph
		link Careers, url='https://blaze.money/en/careers'
			paragraph
		link Contact, url='https://blaze.money/en/contact'
			paragraph
		link Blaze on X, url='https://twitter.com/blaze_payments'
			image Blaze on X, url='https://blaze.money/images/social-x.svg'
		link Blaze on Instagram, url='https://www.instagram.com/blaze.payments/'
			image Blaze on Instagram, url='https://blaze.money/images/social-ig.svg'
		link Blaze on LinkedIn, url='https://www.linkedin.com/company/useblazeapp'
			image Blaze on LinkedIn, url='https://blaze.money/images/social-li.svg'
		button Download Download Blaze
			image Download Blaze, url='https://blaze.money/images/ArrowLong.svg'
		paragraph
			StaticText ©2024 Blaze Payments Inc.
		link Terms of service, url='https://blaze.money/en/terms-of-service'
		link Privacy policy, url='https://blaze.money/en/privacy-policy'
	alert, atomic
```
</details>

**Reasoning for action:** I chose to click on the download button because it directly addresses the user's goal of exploring options for downloading the Blaze app. By doing this, I ensure that the user can access the download options, such as QR codes and links to app stores, as mentioned in the success criteria. This step moves us closer to the user being able to make an informed decision about using the service.

**Action:** click(124) # Click on the Download button to explore the app download options.

**Change Description:** After clicking the Download button, the browser displayed a new section prompting users to scan a QR code to download the Blaze app, along with direct links to 'Get it on Google Play' and 'Download on the App Store', while the initial buttons for downloading the app were still present but focused.

**Screenshot before:****Screenshot after:**---

