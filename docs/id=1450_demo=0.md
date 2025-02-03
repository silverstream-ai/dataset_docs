# Task

**Explore Shinkei's Services and Manage Cookie Preferences**

As a A potential customer interested in Shinkei's automation solutions for seafood processing,
I learn more about Shinkei's offerings and manage cookie preferences before proceeding further,
so that I can make an informed decision about engaging with Shinkei's services and ensure my privacy preferences are respected.

**Success definition:** Given I am on Shinkei's homepage after clicking on the 'LEARN MORE' link
When I manage my cookie preferences by clicking 'Cookie settings' and then 'Confirm My Choices'
Then I should not see any active cookie consent dialogs and be able to view the main services offered by Shinkei.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.shinkei.systems/

https://calendly.com/shinkei/shinkei-intro

**Content (before/after):** 

```
RootWebArea Shinkei Systems, focused, url='https://www.shinkei.systems/'
	banner
		link home, url='https://www.shinkei.systems/'
			image, url='https://cdn.prod.website-files.com/628d5b9cb2ae6902f84003be/64064d8a8def2f8849cfc315_logo.svg'
		navigation
```
<details><summary>Show more</summary>

```
			link Contact, url='mailto:Inbound@shinkei.systems'
	banner
		[47] link home, center=(203,30), url='https://www.shinkei.systems/'
			image, url='https://cdn.prod.website-files.com/628d5b9cb2ae6902f84003be/64064d8a8def2f8849cfc315_logo.svg'
		navigation
			[50] link Updates, center=(1618,30), url='https://www.shinkei.systems/engineering'
			[51] link Contact, center=(1724,30), url='mailto:Inbound@shinkei.systems'
	Video
	heading Reinventing fish processing for a larger, more sustainable bottom-line.
	paragraph
		StaticText Lift your wholesale and ex-vessel prices and shrink your shrink. Shinkei’s automation suite eliminates human headache to multiply your bottom line.
	[65] link LEARN MORE, center=(202,637), url='https://calendly.com/shinkei/shinkei-intro'
	StaticText OUR SECRET SAUCE
	heading ulmOs
	paragraph
		StaticText We merge sensor fusion, edge computing and machine learning to turn data into information, decisions, and action. Our tribe of autonomous systems work together to deliver value to you completely hands-free.
	heading Evolution, Not Revolution.
	paragraph
		StaticText We only go in one direction: up to 85% of labor can be eliminated.
	heading A Better Supply
	paragraph
		StaticText Scientifically validated to improve your drip loss by up to 20%.
	heading Taste The Difference
	paragraph
		StaticText Side-by-side, Michelin Star chefs can’t distinguish between hand and machine.
	heading Multiply your supply today.
	link GET IN TOUCH, url='mailto:Inbound@shinkei.systems'
	heading We’re transforming our seafood supply chain with the vanguard technologies of today.
	paragraph
		StaticText The demands  our ocean have evolved. Our fish supply needs to evolve too.
		StaticText An estimated half a trillion pounds of seafood are caught every year, yet as little as 1 in 3 fish make it to a plate (FAO). We’re making leaps and bounds across the seafood supply chain to rebuild our food supply for the better.
	StaticText ROBOTICS AS A SERVICE
	heading Our complete harvest suite includes analytics and record-keeping automation so fishers and farmers can optimize and scale at any size.
	link TRY 90 DAYS STRESS-FREE, url='mailto:Inbound@shinkei.systems'
	Video
	heading Our Waitlist is Filling Up
	paragraph
		StaticText Shinkei’s technologies strive to eliminate shrink, drive premiums and protect farmer and fisher revenues with our intelligent systems.
		strong
			StaticText Now, ready for scale.
	link LET'S GET STARTED, url='https://calendly.com/shinkei/shinkei-intro'
	image Shinkei Logo, url='https://cdn.prod.website-files.com/628d5b9cb2ae6902f84003be/64064d8a8def2f8849cfc315_logo.svg'
	StaticText © Shinkei Systems Corp.
```
</details>



```
RootWebArea Calendly - Saif Khawaja, focused, url='https://calendly.com/shinkei/shinkei-intro'
	[57] link POWERED BY Calendly, center=(1312,114), inner_text=POWERED BY
Calendly, url='https://calendly.com/?utm_campaign=sign_up&utm_medium=badge&utm_source=invitee'
	heading Saif Khawaja
	heading No openings at the moment.
```
<details><summary>Show more</summary>

```
	StaticText If you are the owner of this account, you can
	[66] link log in, center=(1057,207), url='https://calendly.com/app/login?return_to=%2Fshinkei%2Fshinkei-intro'
	StaticText to find out more.
	region Cookie banner
		alertdialog We respect your personal privacy, modal=False
			StaticText We respect your personal privacy
			StaticText We and our partners use cookies, pixels, and similar tracking technology (all called “cookies” here), including necessary cookies to provide our websites and optional cookies to collect information from you (including your clicks, cursor movements, and screen recordings on our websites) for site functionality and personalization, usage analytics, and marketing. You consent to our use of all cookies by choosing “l understand” or continuing to use this website. You may decline optional cookies by choosing "Do not allow cookies". We honor opt-out preference signals.
			[84] link Click here, center=(514,933), url='https://calendly.com/privacy'
			StaticText to read about how we use your personal data.
			[88] button Do not allow cookies, center=(372,1003)
			[89] button I understand, center=(510,1003)
			[90] button Cookie settings, center=(99,1003)
			[93] button Close, center=(560,764)
```
</details>

**Reasoning for action:** By clicking on the 'LEARN MORE' link, I initiate the process of gathering more information about Shinkei's offerings. This is essential for fulfilling the user story, as the user needs to be informed about the services provided by Shinkei in order to make an informed decision about engaging with their services. Additionally, the next steps involve managing cookie preferences to ensure privacy, but first, I must reach the relevant page where I can find services information.

**Action:** click('65') # Click on the 'LEARN MORE' link to explore further information about Shinkei's services.

**Change Description:** The browser navigated from the Shinkei Systems website to the Calendly scheduling page after the user clicked the 'LEARN MORE' link, thereby changing the active URL and displaying information about scheduling an appointment with Saif Khawaja.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://calendly.com/shinkei/shinkei-intro

https://calendly.com/shinkei/shinkei-intro

**Content (before/after):** 

```
RootWebArea Calendly - Saif Khawaja, focused, url='https://calendly.com/shinkei/shinkei-intro'
	[57] link POWERED BY Calendly, center=(1312,114), inner_text=POWERED BY
Calendly, url='https://calendly.com/?utm_campaign=sign_up&utm_medium=badge&utm_source=invitee'
	heading Saif Khawaja
	heading No openings at the moment.
```
<details><summary>Show more</summary>

```
	StaticText If you are the owner of this account, you can
	[66] link log in, center=(1057,207), url='https://calendly.com/app/login?return_to=%2Fshinkei%2Fshinkei-intro'
	StaticText to find out more.
	region Cookie banner
		alertdialog We respect your personal privacy, modal=False
			StaticText We respect your personal privacy
			StaticText We and our partners use cookies, pixels, and similar tracking technology (all called “cookies” here), including necessary cookies to provide our websites and optional cookies to collect information from you (including your clicks, cursor movements, and screen recordings on our websites) for site functionality and personalization, usage analytics, and marketing. You consent to our use of all cookies by choosing “l understand” or continuing to use this website. You may decline optional cookies by choosing "Do not allow cookies". We honor opt-out preference signals.
			[84] link Click here, center=(514,933), url='https://calendly.com/privacy'
			StaticText to read about how we use your personal data.
			[88] button Do not allow cookies, center=(372,1003)
			[89] button I understand, center=(510,1003)
			[90] button Cookie settings, center=(99,1003)
			[93] button Close, center=(560,764)
```
</details>



```
RootWebArea Calendly - Saif Khawaja, focused, url='https://calendly.com/shinkei/shinkei-intro'
	link POWERED BY Calendly, url='https://calendly.com/?utm_campaign=sign_up&utm_medium=badge&utm_source=invitee'
	heading Saif Khawaja
	heading No openings at the moment.
	StaticText If you are the owner of this account, you can
```
<details><summary>Show more</summary>

```
	link log in, url='https://calendly.com/app/login?return_to=%2Fshinkei%2Fshinkei-intro'
	StaticText to find out more.
	region Cookie banner
		alertdialog We respect your personal privacy, modal=False
			StaticText We respect your personal privacy
			StaticText We and our partners use cookies, pixels, and similar tracking technology (all called “cookies” here), including necessary cookies to provide our websites and optional cookies to collect information from you (including your clicks, cursor movements, and screen recordings on our websites) for site functionality and personalization, usage analytics, and marketing. You consent to our use of all cookies by choosing “l understand” or continuing to use this website. You may decline optional cookies by choosing "Do not allow cookies". We honor opt-out preference signals.
			link Click here, url='https://calendly.com/privacy'
			StaticText to read about how we use your personal data.
			button Do not allow cookies
			button I understand
			button Cookie settings
			button Close
	region Privacy Preference Center
		alertdialog Privacy Preference Center, modal=True
			image Company Logo
				image Company Logo, url='https://cdn.cookielaw.org/logos/122ecfc3-4694-42f1-863f-2db42d1b1e68/0bcbbcf4-9b83-4684-ba59-bc913c0d5905/c21bea90-f4f1-43d1-8118-8938bbb27a9d/logo.png'
			[99] button Close, center=(458,32)
			StaticText When you visit any website, it may store or retrieve information on your browser, mostly in the form of cookies. This information might be about you, your preferences or your device and is mostly used to make the site work as you expect it to. The information does not usually directly identify you, but it can give you a more personalized web experience. Because we respect your right to privacy, you can choose not to allow some types of cookies. Click on the different category headings to find out more and change our default settings. However, blocking some types of cookies may impact your experience of the site and the services we are able to offer.
			StaticText Manage Consent Preferences
			[111] button Strictly Necessary Cookies Always Active, center=(244,368), expanded=False
			StaticText Strictly Necessary Cookies
			StaticText Always Active
			[123] button Functional Cookies, center=(244,419), expanded=False
			StaticText Functional Cookies
			switch Functional Cookies, checked='true', focused
			LabelText
				[132] switch Functional Cookies, center=(432,416), checked='true'
			[139] button Performance Cookies, center=(244,473), expanded=False
			StaticText Performance Cookies
			switch Performance Cookies, checked='true'
			LabelText
				[148] switch Performance Cookies, center=(432,470), checked='true'
			[155] button Targeting Cookies, center=(244,528), expanded=False
			StaticText Targeting Cookies
			switch Targeting Cookies, checked='true'
			LabelText
				[164] switch Targeting Cookies, center=(432,525), checked='true'
			[229] button Confirm My Choices, center=(130,1015)
			[231] link Powered by OneTrust Opens in a new Tab, center=(394,1068), url='https://www.onetrust.com/products/cookie-consent/'
				image Powered by Onetrust, url='https://cdn.cookielaw.org/logos/static/powered_by_logo.svg'
			generic, atomic
```
</details>

**Reasoning for action:** By clicking the 'Cookie settings' button, I am able to access the options related to cookie preferences, which is crucial for the user to be able to customize their privacy settings before proceeding with browsing Shinkei's services. This move directly addresses the user's need to manage cookie preferences as specified in the user story.

**Action:** click('90') # Click on the 'Cookie settings' button to explore cookie preferences.

**Change Description:** After clicking the 'Cookie settings' button, a new 'Privacy Preference Center' dialog appeared, allowing the user to manage their cookie consent preferences, replacing the previous state where only the cookie banner was visible.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://calendly.com/shinkei/shinkei-intro

https://calendly.com/shinkei/shinkei-intro

**Content (before/after):** 

```
RootWebArea Calendly - Saif Khawaja, focused, url='https://calendly.com/shinkei/shinkei-intro'
	link POWERED BY Calendly, url='https://calendly.com/?utm_campaign=sign_up&utm_medium=badge&utm_source=invitee'
	heading Saif Khawaja
	heading No openings at the moment.
	StaticText If you are the owner of this account, you can
```
<details><summary>Show more</summary>

```
	link log in, url='https://calendly.com/app/login?return_to=%2Fshinkei%2Fshinkei-intro'
	StaticText to find out more.
	region Cookie banner
		alertdialog We respect your personal privacy, modal=False
			StaticText We respect your personal privacy
			StaticText We and our partners use cookies, pixels, and similar tracking technology (all called “cookies” here), including necessary cookies to provide our websites and optional cookies to collect information from you (including your clicks, cursor movements, and screen recordings on our websites) for site functionality and personalization, usage analytics, and marketing. You consent to our use of all cookies by choosing “l understand” or continuing to use this website. You may decline optional cookies by choosing "Do not allow cookies". We honor opt-out preference signals.
			link Click here, url='https://calendly.com/privacy'
			StaticText to read about how we use your personal data.
			button Do not allow cookies
			button I understand
			button Cookie settings
			button Close
	region Privacy Preference Center
		alertdialog Privacy Preference Center, modal=True
			image Company Logo
				image Company Logo, url='https://cdn.cookielaw.org/logos/122ecfc3-4694-42f1-863f-2db42d1b1e68/0bcbbcf4-9b83-4684-ba59-bc913c0d5905/c21bea90-f4f1-43d1-8118-8938bbb27a9d/logo.png'
			[99] button Close, center=(458,32)
			StaticText When you visit any website, it may store or retrieve information on your browser, mostly in the form of cookies. This information might be about you, your preferences or your device and is mostly used to make the site work as you expect it to. The information does not usually directly identify you, but it can give you a more personalized web experience. Because we respect your right to privacy, you can choose not to allow some types of cookies. Click on the different category headings to find out more and change our default settings. However, blocking some types of cookies may impact your experience of the site and the services we are able to offer.
			StaticText Manage Consent Preferences
			[111] button Strictly Necessary Cookies Always Active, center=(244,368), expanded=False
			StaticText Strictly Necessary Cookies
			StaticText Always Active
			[123] button Functional Cookies, center=(244,419), expanded=False
			StaticText Functional Cookies
			switch Functional Cookies, checked='true', focused
			LabelText
				[132] switch Functional Cookies, center=(432,416), checked='true'
			[139] button Performance Cookies, center=(244,473), expanded=False
			StaticText Performance Cookies
			switch Performance Cookies, checked='true'
			LabelText
				[148] switch Performance Cookies, center=(432,470), checked='true'
			[155] button Targeting Cookies, center=(244,528), expanded=False
			StaticText Targeting Cookies
			switch Targeting Cookies, checked='true'
			LabelText
				[164] switch Targeting Cookies, center=(432,525), checked='true'
			[229] button Confirm My Choices, center=(130,1015)
			[231] link Powered by OneTrust Opens in a new Tab, center=(394,1068), url='https://www.onetrust.com/products/cookie-consent/'
				image Powered by Onetrust, url='https://cdn.cookielaw.org/logos/static/powered_by_logo.svg'
			generic, atomic
```
</details>



```
RootWebArea Calendly - Saif Khawaja, focused, url='https://calendly.com/shinkei/shinkei-intro'
	[57] link POWERED BY Calendly, center=(1312,114), inner_text=POWERED BY
Calendly, url='https://calendly.com/?utm_campaign=sign_up&utm_medium=badge&utm_source=invitee'
	heading Saif Khawaja
	heading No openings at the moment.
```
<details><summary>Show more</summary>

```
	StaticText If you are the owner of this account, you can
	[66] link log in, center=(1057,207), url='https://calendly.com/app/login?return_to=%2Fshinkei%2Fshinkei-intro'
	StaticText to find out more.
```
</details>

**Reasoning for action:** By clicking 'Confirm My Choices', I am finalizing the cookie preferences I set in the Privacy Preference Center. This is crucial because the user story indicates the need to manage cookie preferences to respect privacy and ensure an informed decision about engaging with Shinkei's services. Confirming these choices will ensure that there are no active cookie consent dialogs obstructing my view of the main services offered by Shinkei, thereby advancing the task towards a successful completion.

**Action:** click('229') # Click on 'Confirm My Choices' to finalize the cookie preferences.

**Change Description:** After clicking 'Confirm My Choices', the cookie preference modal has been closed, resulting in the removal of the Privacy Preference Center and its associated content from the browser's interface. The browser now displays the main page without any active cookie consent dialogs.

**Screenshot before:****Screenshot after:**---

