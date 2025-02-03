# Task

**User Story for Onboarding Process**

As a potential user of Aglide,
I provide my contact information to express interest in the service,
so that I can receive more information and proceed with the onboarding process.

**Success definition:** Given I am on the 'Get Started' page of Aglide
When I fill in my First Name, Last Name, and Work Email Address, and click 'Continue'
Then I should receive a valid input alert if the information is incomplete or incorrect and upon correcting my details I should navigate to the 'Book onboarding' page.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://aglide.com/

https://aglide.com/get-started

**Content (before/after):** 

```
RootWebArea Aglide: Connect any app to your SSO, without SAML., focused, url='https://aglide.com/'
	[29] link Aglide Logo Aglide Logo, center=(102,64), url='https://aglide.com/'
		image Aglide Logo, url='https://aglide.com/media/iconText.png'
		image Aglide Logo, url='https://aglide.com/media/icon.png'
	paragraph
```
<details><summary>Show more</summary>

```
		[36] image, center=(1175,64)
	[37] paragraph, center=(1219,64), inner_text=Platform
		StaticText Platform
	[39] paragraph, center=(1336,64), inner_text=Security
		StaticText Security
	[41] paragraph, center=(1448,64), inner_text=Savings
		StaticText Savings
	[43] paragraph, center=(1572,64), inner_text=Book Demo
		StaticText Book Demo
	[45] button Sign In, center=(1712,64)
	[46] button Get Started, center=(1818,64)
	heading Backed by
	image Y Combinator, url='https://aglide.com/media/YCLogo.png'
	heading Combinator
	heading Connect any app to your SSO, without SAML.
	heading Avoid the SSO tax and manage access to apps that don’t support SAML, with no impact on security or end-user experience.
	[61] button Get Started, center=(382,554)
	[62] button Book Demo, center=(524,554)
	heading Access management & SSO for any app.
	paragraph
		StaticText Users can access any app with their existing SSO credentials or dashboard.
	paragraph
		StaticText Admins can enable SSO, set conditional access policies, and revoke sessions.
	paragraph
		StaticText Aglide SSO works just like SAML SSO.
	button Learn More
	image onboarding, url='https://aglide.com/media/Desktop.png'
	heading The same secure SSO, none of the SAML hassle.
	heading Powerful conditional access policies.
	paragraph
		StaticText Control when and how end-users access their apps. Limit app access to managed devices, require VPNs, or apply georestrictions.
	image onboarding, url='https://aglide.com/media/SSO/ConditionalAccess.png'
	heading Apps only accessible through Aglide.
	paragraph
		StaticText Aglide automatically sets account passwords to values end-users can't see or change, so they can only access their apps via Aglide.
	image onboarding, url='https://aglide.com/media/SSO/OnlyAglide.png'
	heading Instant user access revoking.
	paragraph
		StaticText Revoke all of a user's sessions in a click - locking them out of everything from their emails to the company's social media accounts.
	image onboarding, url='https://aglide.com/media/SSO/Freeze.png'
	heading Designed to work with your existing provider.
	image logo-Okta, url='https://aglide.com/media/IdPLogos/OktaLogo.png'
	image logo-OneLogin, url='https://aglide.com/media/IdPLogos/OneLoginLogo-Grey.png'
	image logo-Microsoft Entra, url='https://aglide.com/media/IdPLogos/EntraLogo-Grey.png'
	image logo-Google Workspace, url='https://aglide.com/media/IdPLogos/GoogleLogo-Grey.png'
	heading Other
	heading None
	image dashboard-Okta, url='https://aglide.com/media/IdPLogos/OktaGrid.png'
	paragraph
		StaticText Admins can sync users and groups from their current identity provider.
	paragraph
		StaticText Users can access their apps from their existing SSO dashboard.
	paragraph
		StaticText Aglide is designed to fit right in to your unique environment.
	button Learn More
	heading From unmanaged account to SSO app, in seconds.
	paragraph
		StaticText With Auto Migrate, you can convert any account into a managed SSO app in seconds.
	paragraph
		StaticText Aglide customers can be live in a day, with no access down time.
	button Learn More
	image onboarding, url='https://aglide.com/media/AutoMigrate.png'
	heading More than just SSO.
	paragraph
		StaticText Integrated password manager
	paragraph
		StaticText Store everything from credit cards to API keys in Aglide’s encrypted vaults.
	image onboarding, url='https://aglide.com/media/OtherFeatures/PasswordManager.png'
	paragraph
		StaticText App usage monitoring
	paragraph
		StaticText See how frequently each app is used, to spot unnecessary accounts and cut bills.
	image onboarding, url='https://aglide.com/media/OtherFeatures/Usage.png'
	paragraph
		StaticText Shared SSO apps & item vaults
	paragraph
		StaticText Shared vaults let multiple users access both SSO apps and password manager items.
	image onboarding, url='https://aglide.com/media/OtherFeatures/Shared.png'
	paragraph
		StaticText Ghost app detection
	paragraph
		StaticText Aglide detects unmanaged apps - flagging them to you to get them under control.
	image onboarding, url='https://aglide.com/media/OtherFeatures/Ghost.png'
	paragraph
		StaticText Powerful user grouping tools
	paragraph
		StaticText Create user groups, linked to your existings IAM, to bulk set rules and permissions.
	image onboarding, url='https://aglide.com/media/OtherFeatures/Groups.png'
	paragraph
		StaticText Integrated password manager
	paragraph
		StaticText Store everything from credit cards to API keys in Aglide’s encrypted vaults.
	image onboarding, url='https://aglide.com/media/OtherFeatures/PasswordManager.png'
	paragraph
		StaticText App usage monitoring
	paragraph
		StaticText See how frequently each app is used, to spot unnecessary accounts and cut bills.
	image onboarding, url='https://aglide.com/media/OtherFeatures/Usage.png'
	paragraph
		StaticText Shared SSO apps & item vaults
	paragraph
		StaticText Shared vaults let multiple users access both SSO apps and password manager items.
	image onboarding, url='https://aglide.com/media/OtherFeatures/Shared.png'
	paragraph
		StaticText Ghost app detection
	paragraph
		StaticText Aglide detects unmanaged apps - flagging them to you to get them under control.
	image onboarding, url='https://aglide.com/media/OtherFeatures/Ghost.png'
	paragraph
		StaticText Powerful user grouping tools
	paragraph
		StaticText Create user groups, linked to your existings IAM, to bulk set rules and permissions.
	image onboarding, url='https://aglide.com/media/OtherFeatures/Groups.png'
	heading No more tiers. No more SSO Tax.
	paragraph
		StaticText Aglide is priced to help you save money. Usually, using Aglide SSO instead of SAML for just one app results in customers saving overall.
	button Calculate Savings
	button Book Demo
	image onboarding, url='https://aglide.com/media/SSOTax.png'
	link Aglide, url='https://aglide.com/'
	link, url='https://twitter.com/UseAglide'
		image
	link, url='https://www.linkedin.com/company/aglide'
		image
	heading Keep in touch
	textbox Your email address, required
	button Hear about updates
	paragraph
		StaticText By clicking “Hear about updates” you agree to be added to our newsletter. Your data will be stored in accordance with our
		link privacy policy, url='https://aglide.com/privacy-policy'
		StaticText . You may unsubscribe at any time.
	heading Company
	link Security, url='https://aglide.com/security'
	link Press Enquiries, url='mailto:press@aglide.com'
	link Privacy Policy, url='https://aglide.com/privacy-policy'
	link Security Policy, url='https://aglide.com/security-policy'
	heading Product
	link Single Sign On, url='https://aglide.com/single-sign-on'
	link IdP Integration, url='https://aglide.com/idp-connect'
	link Auto Migrate, url='https://aglide.com/auto-migrate'
	heading Enquiries
	link Savings Calculator, url='https://aglide.com/savings'
	link Book Demo, url='https://aglide.com/book-demo'
	link Book Onboarding, url='https://aglide.com/get-started'
	StaticText ©️ Aglide Inc.
	StaticText 2025
```
</details>



```
RootWebArea Aglide: Connect any app to your SSO, without SAML., focused, url='https://aglide.com/get-started'
	[29] link Aglide Logo Aglide Logo, center=(102,64), url='https://aglide.com/'
		image Aglide Logo, url='https://aglide.com/media/iconText.png'
		image Aglide Logo, url='https://aglide.com/media/icon.png'
	paragraph
```
<details><summary>Show more</summary>

```
		[36] image, center=(1175,64)
	[37] paragraph, center=(1219,64), inner_text=Platform
		StaticText Platform
	[39] paragraph, center=(1336,64), inner_text=Security
		StaticText Security
	[41] paragraph, center=(1448,64), inner_text=Savings
		StaticText Savings
	[43] paragraph, center=(1572,64), inner_text=Book Demo
		StaticText Book Demo
	[45] button Sign In, center=(1712,64)
	[46] button Get Started, center=(1818,64)
	heading Join Aglide
	heading Get Started
	heading To get started with Aglide, we will connect you with a member of our team to help you get set up.
	[62] textbox First Name, center=(1250,253), contenteditable=True, required, type=text
	[63] textbox Last Name, center=(1489,253), contenteditable=True, required, type=text
	[64] textbox Work Email Address, center=(1370,327), contenteditable=True, required, type=email
	[65] button Continue, center=(1370,402), type=submit
	paragraph
		StaticText By clicking "Continue" you agree to
		[67] link Aglide's Privacy Notice, center=(1477,457), url='https://aglide.com/privacy-policy'
		StaticText .
	[71] link Aglide, center=(362,749), url='https://aglide.com/'
	[73] link, center=(330,785), url='https://twitter.com/UseAglide'
		image
	[75] link, center=(358,785), url='https://www.linkedin.com/company/aglide'
		image
	heading Keep in touch
	[81] textbox Your email address, center=(1296,855), contenteditable=True, required, type=email
	[82] button Hear about updates, center=(1524,855), type=submit
	paragraph
		StaticText By clicking “Hear about updates” you agree to be added to our newsletter. Your data will be stored in accordance with our
		[84] link privacy policy, center=(1418,906), url='https://aglide.com/privacy-policy'
		StaticText . You may unsubscribe at any time.
	heading Company
	[87] link Security, center=(447,843), url='https://aglide.com/security'
	[88] link Press Enquiries, center=(447,871), url='mailto:press@aglide.com'
	[89] link Privacy Policy, center=(447,899), url='https://aglide.com/privacy-policy'
	[90] link Security Policy, center=(447,927), url='https://aglide.com/security-policy'
	heading Product
	[93] link Single Sign On, center=(724,843), url='https://aglide.com/single-sign-on'
	[94] link IdP Integration, center=(724,871), url='https://aglide.com/idp-connect'
	[95] link Auto Migrate, center=(724,899), url='https://aglide.com/auto-migrate'
	heading Enquiries
	[98] link Savings Calculator, center=(1001,843), url='https://aglide.com/savings'
	[99] link Book Demo, center=(1001,871), url='https://aglide.com/book-demo'
	[100] link Book Onboarding, center=(1001,899), url='https://aglide.com/get-started'
	StaticText ©️ Aglide Inc.
	StaticText 2025
```
</details>

**Reasoning for action:** By clicking the 'Get Started' button, I am advancing my progress towards providing my contact information, which is essential for expressing interest in the service. This action displays the necessary input fields for First Name, Last Name, and Work Email Address, enabling me to proceed with the user story as outlined.

**Action:** click(46) # Click on the 'Get Started' button to explore further.

**Change Description:** After clicking the 'Get Started' button, the browser navigated to the 'Get Started' page where users can input their first name, last name, and work email address to connect with Aglide's team for setup assistance.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://aglide.com/get-started

https://aglide.com/get-started

**Content (before/after):** 

```
RootWebArea Aglide: Connect any app to your SSO, without SAML., focused, url='https://aglide.com/get-started'
	[29] link Aglide Logo Aglide Logo, center=(102,64), url='https://aglide.com/'
		image Aglide Logo, url='https://aglide.com/media/iconText.png'
		image Aglide Logo, url='https://aglide.com/media/icon.png'
	paragraph
```
<details><summary>Show more</summary>

```
		[36] image, center=(1175,64)
	[37] paragraph, center=(1219,64), inner_text=Platform
		StaticText Platform
	[39] paragraph, center=(1336,64), inner_text=Security
		StaticText Security
	[41] paragraph, center=(1448,64), inner_text=Savings
		StaticText Savings
	[43] paragraph, center=(1572,64), inner_text=Book Demo
		StaticText Book Demo
	[45] button Sign In, center=(1712,64)
	[46] button Get Started, center=(1818,64)
	heading Join Aglide
	heading Get Started
	heading To get started with Aglide, we will connect you with a member of our team to help you get set up.
	[62] textbox First Name, center=(1250,253), contenteditable=True, required, type=text
	[63] textbox Last Name, center=(1489,253), contenteditable=True, required, type=text
	[64] textbox Work Email Address, center=(1370,327), contenteditable=True, required, type=email
	[65] button Continue, center=(1370,402), type=submit
	paragraph
		StaticText By clicking "Continue" you agree to
		[67] link Aglide's Privacy Notice, center=(1477,457), url='https://aglide.com/privacy-policy'
		StaticText .
	[71] link Aglide, center=(362,749), url='https://aglide.com/'
	[73] link, center=(330,785), url='https://twitter.com/UseAglide'
		image
	[75] link, center=(358,785), url='https://www.linkedin.com/company/aglide'
		image
	heading Keep in touch
	[81] textbox Your email address, center=(1296,855), contenteditable=True, required, type=email
	[82] button Hear about updates, center=(1524,855), type=submit
	paragraph
		StaticText By clicking “Hear about updates” you agree to be added to our newsletter. Your data will be stored in accordance with our
		[84] link privacy policy, center=(1418,906), url='https://aglide.com/privacy-policy'
		StaticText . You may unsubscribe at any time.
	heading Company
	[87] link Security, center=(447,843), url='https://aglide.com/security'
	[88] link Press Enquiries, center=(447,871), url='mailto:press@aglide.com'
	[89] link Privacy Policy, center=(447,899), url='https://aglide.com/privacy-policy'
	[90] link Security Policy, center=(447,927), url='https://aglide.com/security-policy'
	heading Product
	[93] link Single Sign On, center=(724,843), url='https://aglide.com/single-sign-on'
	[94] link IdP Integration, center=(724,871), url='https://aglide.com/idp-connect'
	[95] link Auto Migrate, center=(724,899), url='https://aglide.com/auto-migrate'
	heading Enquiries
	[98] link Savings Calculator, center=(1001,843), url='https://aglide.com/savings'
	[99] link Book Demo, center=(1001,871), url='https://aglide.com/book-demo'
	[100] link Book Onboarding, center=(1001,899), url='https://aglide.com/get-started'
	StaticText ©️ Aglide Inc.
	StaticText 2025
```
</details>



```
RootWebArea Aglide: Connect any app to your SSO, without SAML., focused, url='https://aglide.com/get-started'
	alert Please fill out this field., atomic
	[29] link Aglide Logo Aglide Logo, center=(102,64), url='https://aglide.com/'
		image Aglide Logo, url='https://aglide.com/media/iconText.png'
		image Aglide Logo, url='https://aglide.com/media/icon.png'
```
<details><summary>Show more</summary>

```
	paragraph
		[36] image, center=(1175,64)
	[37] paragraph, center=(1219,64), inner_text=Platform
		StaticText Platform
	[39] paragraph, center=(1336,64), inner_text=Security
		StaticText Security
	[41] paragraph, center=(1448,64), inner_text=Savings
		StaticText Savings
	[43] paragraph, center=(1572,64), inner_text=Book Demo
		StaticText Book Demo
	[45] button Sign In, center=(1712,64)
	[46] button Get Started, center=(1818,64)
	heading Join Aglide
	heading Get Started
	heading To get started with Aglide, we will connect you with a member of our team to help you get set up.
	[62] textbox First Name value='John', center=(1250,253), contenteditable=True, required, type=text
	[63] textbox Last Name, center=(1489,253), contenteditable=True, focused, required, type=text
	[64] textbox Work Email Address value='Doejohn.doe@example.com', center=(1370,327), contenteditable=True, required, type=email
	[65] button Continue, center=(1370,402), type=submit
	paragraph
		StaticText By clicking "Continue" you agree to
		[67] link Aglide's Privacy Notice, center=(1477,457), url='https://aglide.com/privacy-policy'
		StaticText .
	[71] link Aglide, center=(362,749), url='https://aglide.com/'
	[73] link, center=(330,785), url='https://twitter.com/UseAglide'
		image
	[75] link, center=(358,785), url='https://www.linkedin.com/company/aglide'
		image
	heading Keep in touch
	[81] textbox Your email address, center=(1296,855), contenteditable=True, required, type=email
	[82] button Hear about updates, center=(1524,855), type=submit
	paragraph
		StaticText By clicking “Hear about updates” you agree to be added to our newsletter. Your data will be stored in accordance with our
		[84] link privacy policy, center=(1418,906), url='https://aglide.com/privacy-policy'
		StaticText . You may unsubscribe at any time.
	heading Company
	[87] link Security, center=(447,843), url='https://aglide.com/security'
	[88] link Press Enquiries, center=(447,871), url='mailto:press@aglide.com'
	[89] link Privacy Policy, center=(447,899), url='https://aglide.com/privacy-policy'
	[90] link Security Policy, center=(447,927), url='https://aglide.com/security-policy'
	heading Product
	[93] link Single Sign On, center=(724,843), url='https://aglide.com/single-sign-on'
	[94] link IdP Integration, center=(724,871), url='https://aglide.com/idp-connect'
	[95] link Auto Migrate, center=(724,899), url='https://aglide.com/auto-migrate'
	heading Enquiries
	[98] link Savings Calculator, center=(1001,843), url='https://aglide.com/savings'
	[99] link Book Demo, center=(1001,871), url='https://aglide.com/book-demo'
	[100] link Book Onboarding, center=(1001,899), url='https://aglide.com/get-started'
	StaticText ©️ Aglide Inc.
	StaticText 2025
```
</details>

**Reasoning for action:** I filled in the required information for First Name, Last Name, and Work Email Address to satisfy the input requirements of the 'Get Started' page. By doing this, I ensured that when I clicked on the 'Continue' button, the form would be complete, which would move me closer to either progressing through the onboarding steps or receiving an alert if the information was invalid. This action is critical as it directly initiates the process of expressing interest in Aglide's service.

**Action:** fill(62, 'John') # Fill in the First Name
fill(63, 'Doe') # Fill in the Last Name
fill(64, 'john.doe@example.com') # Fill in the Work Email Address
click(65) # Click on the 'Continue' button to proceed.

**Change Description:** The First Name, Last Name, and Work Email Address fields were filled with 'John', 'Doe', and 'john.doe@example.com' respectively, but an alert indicated that the input was not valid, preventing the form from proceeding.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://aglide.com/get-started

https://aglide.com/book-onboarding

**Content (before/after):** 

```
RootWebArea Aglide: Connect any app to your SSO, without SAML., focused, url='https://aglide.com/get-started'
	alert Please fill out this field., atomic
	[29] link Aglide Logo Aglide Logo, center=(102,64), url='https://aglide.com/'
		image Aglide Logo, url='https://aglide.com/media/iconText.png'
		image Aglide Logo, url='https://aglide.com/media/icon.png'
```
<details><summary>Show more</summary>

```
	paragraph
		[36] image, center=(1175,64)
	[37] paragraph, center=(1219,64), inner_text=Platform
		StaticText Platform
	[39] paragraph, center=(1336,64), inner_text=Security
		StaticText Security
	[41] paragraph, center=(1448,64), inner_text=Savings
		StaticText Savings
	[43] paragraph, center=(1572,64), inner_text=Book Demo
		StaticText Book Demo
	[45] button Sign In, center=(1712,64)
	[46] button Get Started, center=(1818,64)
	heading Join Aglide
	heading Get Started
	heading To get started with Aglide, we will connect you with a member of our team to help you get set up.
	[62] textbox First Name value='John', center=(1250,253), contenteditable=True, required, type=text
	[63] textbox Last Name, center=(1489,253), contenteditable=True, focused, required, type=text
	[64] textbox Work Email Address value='Doejohn.doe@example.com', center=(1370,327), contenteditable=True, required, type=email
	[65] button Continue, center=(1370,402), type=submit
	paragraph
		StaticText By clicking "Continue" you agree to
		[67] link Aglide's Privacy Notice, center=(1477,457), url='https://aglide.com/privacy-policy'
		StaticText .
	[71] link Aglide, center=(362,749), url='https://aglide.com/'
	[73] link, center=(330,785), url='https://twitter.com/UseAglide'
		image
	[75] link, center=(358,785), url='https://www.linkedin.com/company/aglide'
		image
	heading Keep in touch
	[81] textbox Your email address, center=(1296,855), contenteditable=True, required, type=email
	[82] button Hear about updates, center=(1524,855), type=submit
	paragraph
		StaticText By clicking “Hear about updates” you agree to be added to our newsletter. Your data will be stored in accordance with our
		[84] link privacy policy, center=(1418,906), url='https://aglide.com/privacy-policy'
		StaticText . You may unsubscribe at any time.
	heading Company
	[87] link Security, center=(447,843), url='https://aglide.com/security'
	[88] link Press Enquiries, center=(447,871), url='mailto:press@aglide.com'
	[89] link Privacy Policy, center=(447,899), url='https://aglide.com/privacy-policy'
	[90] link Security Policy, center=(447,927), url='https://aglide.com/security-policy'
	heading Product
	[93] link Single Sign On, center=(724,843), url='https://aglide.com/single-sign-on'
	[94] link IdP Integration, center=(724,871), url='https://aglide.com/idp-connect'
	[95] link Auto Migrate, center=(724,899), url='https://aglide.com/auto-migrate'
	heading Enquiries
	[98] link Savings Calculator, center=(1001,843), url='https://aglide.com/savings'
	[99] link Book Demo, center=(1001,871), url='https://aglide.com/book-demo'
	[100] link Book Onboarding, center=(1001,899), url='https://aglide.com/get-started'
	StaticText ©️ Aglide Inc.
	StaticText 2025
```
</details>



```
RootWebArea Aglide: Connect any app to your SSO, without SAML., focused, url='https://aglide.com/book-onboarding'
	[107] link Aglide Logo Aglide Logo, center=(102,64), url='https://aglide.com/'
		image Aglide Logo, url='https://aglide.com/media/iconText.png'
		image Aglide Logo, url='https://aglide.com/media/icon.png'
	paragraph
```
<details><summary>Show more</summary>

```
		[114] image, center=(1175,64)
	[115] paragraph, center=(1219,64), inner_text=Platform
		StaticText Platform
	[117] paragraph, center=(1336,64), inner_text=Security
		StaticText Security
	[119] paragraph, center=(1448,64), inner_text=Savings
		StaticText Savings
	[121] paragraph, center=(1572,64), inner_text=Book Demo
		StaticText Book Demo
	[123] button Sign In, center=(1712,64)
	[124] button Get Started, center=(1818,64)
	heading Get Started
	heading Book onboarding
	heading One of our team will take you through setup, answer your specific questions and give you a guided tour of the product.
	[a] Iframe Calendly Scheduling Page, center=(1370,526), title=Calendly Scheduling Page
		RootWebArea Select a Date & Time - Calendly, url='https://calendly.com/d/39j-mbc-48c/aglide-white-glove-onboarding?background_color=ffffff&hide_event_type_details=1&hide_landing_page_details=1&primary_color=20513b&text_color=000c06&embed_type=Inline&embed_domain=1&month=2025-01'
			heading Aglide Priority Onboarding
			heading Select a Day
			button Go to previous month, disabled=True
			StaticText January 2025
			button Go to next month, disabled=True
			status, atomic
				StaticText January is now displayed
			table Select a Day
				rowgroup
					row
						columnheader SUN
						columnheader MON
						columnheader TUE
						columnheader WED
						columnheader THU
						columnheader FRI
						columnheader SAT
				rowgroup
					row
						gridcell
						gridcell
						gridcell
						gridcell Wednesday, January 1 - No times available
							button Wednesday, January 1 - No times available, disabled=True
						gridcell Thursday, January 2 - No times available
							button Thursday, January 2 - No times available, disabled=True
						gridcell Friday, January 3 - No times available
							button Friday, January 3 - No times available, disabled=True
						gridcell Saturday, January 4 - No times available
							button Saturday, January 4 - No times available, disabled=True
					row
						gridcell Sunday, January 5 - No times available
							button Sunday, January 5 - No times available, disabled=True
						gridcell Monday, January 6 - No times available
							button Monday, January 6 - No times available, disabled=True
						gridcell Tuesday, January 7 - No times available
							button Tuesday, January 7 - No times available, disabled=True
						gridcell Wednesday, January 8 - No times available
							button Wednesday, January 8 - No times available, disabled=True
						gridcell Thursday, January 9 - No times available
							button Thursday, January 9 - No times available, disabled=True
						gridcell Friday, January 10 - No times available
							button Friday, January 10 - No times available, disabled=True
						gridcell Saturday, January 11 - No times available
							button Saturday, January 11 - No times available, disabled=True
					row
						gridcell Sunday, January 12 - No times available
							button Sunday, January 12 - No times available, disabled=True
						gridcell Monday, January 13 - Times available, selected=False
							button Monday, January 13 - Times available
						gridcell Tuesday, January 14 - Times available, selected=False
							button Tuesday, January 14 - Times available
						gridcell Wednesday, January 15 - Times available, selected=False
							button Wednesday, January 15 - Times available
						gridcell Thursday, January 16 - Times available, selected=False
							button Thursday, January 16 - Times available
						gridcell Friday, January 17 - Times available, selected=False
							button Friday, January 17 - Times available
						gridcell Saturday, January 18 - No times available
							button Saturday, January 18 - No times available, disabled=True
					row
						gridcell Sunday, January 19 - No times available
							button Sunday, January 19 - No times available, disabled=True
						gridcell Monday, January 20 - No times available
							button Monday, January 20 - No times available, disabled=True
						gridcell Tuesday, January 21 - No times available
							button Tuesday, January 21 - No times available, disabled=True
						gridcell Wednesday, January 22 - No times available
							button Wednesday, January 22 - No times available, disabled=True
						gridcell Thursday, January 23 - No times available
							button Thursday, January 23 - No times available, disabled=True
						gridcell Friday, January 24 - No times available
							button Friday, January 24 - No times available, disabled=True
						gridcell Saturday, January 25 - No times available
							button Saturday, January 25 - No times available, disabled=True
					row
						gridcell Sunday, January 26 - No times available
							button Sunday, January 26 - No times available, disabled=True
						gridcell Monday, January 27 - No times available
							button Monday, January 27 - No times available, disabled=True
						gridcell Tuesday, January 28 - No times available
							button Tuesday, January 28 - No times available, disabled=True
						gridcell Wednesday, January 29 - No times available
							button Wednesday, January 29 - No times available, disabled=True
						gridcell Thursday, January 30 - No times available
							button Thursday, January 30 - No times available, disabled=True
						gridcell Friday, January 31 - No times available
							button Friday, January 31 - No times available, disabled=True
						gridcell
			status, atomic
			paragraph
				StaticText Time zone
			button Time zone  UTC Time (7:07pm) , expanded=False
			button Cookie settings
			region Cookie banner
				alertdialog We respect your personal privacy, modal=False
					StaticText We respect your personal privacy
					StaticText We and our partners use cookies, pixels, and similar tracking technology (all called “cookies” here), including necessary cookies to provide our websites and optional cookies to collect information from you (including your clicks, cursor movements, and screen recordings on our websites) for site functionality and personalization, usage analytics, and marketing. You consent to our use of all cookies by choosing “l understand” or continuing to use this website. You may decline optional cookies by choosing "Do not allow cookies". We honor opt-out preference signals.
					[a230] link Click here, center=(1343,638), url='https://calendly.com/privacy'
					StaticText to read about how we use your personal data.
					[a234] button Do not allow cookies, center=(1258,757)
					[a235] button I understand, center=(1447,757)
					[a236] button Cookie settings, center=(1248,707)
					[a239] button Close, center=(1548,352)
	link Aglide, url='https://aglide.com/'
	link, url='https://twitter.com/UseAglide'
		image
	link, url='https://www.linkedin.com/company/aglide'
		image
	heading Keep in touch
	textbox Your email address, required
	button Hear about updates
	paragraph
		StaticText By clicking “Hear about updates” you agree to be added to our newsletter. Your data will be stored in accordance with our
		link privacy policy, url='https://aglide.com/privacy-policy'
		StaticText . You may unsubscribe at any time.
	heading Company
	link Security, url='https://aglide.com/security'
	link Press Enquiries, url='mailto:press@aglide.com'
	link Privacy Policy, url='https://aglide.com/privacy-policy'
	link Security Policy, url='https://aglide.com/security-policy'
	heading Product
	link Single Sign On, url='https://aglide.com/single-sign-on'
	link IdP Integration, url='https://aglide.com/idp-connect'
	link Auto Migrate, url='https://aglide.com/auto-migrate'
	heading Enquiries
	link Savings Calculator, url='https://aglide.com/savings'
	link Book Demo, url='https://aglide.com/book-demo'
	link Book Onboarding, url='https://aglide.com/get-started'
	StaticText ©️ Aglide Inc.
	StaticText 2025
```
</details>

**Reasoning for action:** I filled in the Last Name field with 'Smith' to provide valid input necessary for the form submission. Then, I clicked on the 'Continue' button to trigger the form submission process. This step is crucial as it checks whether the provided response meets the requirements set in the acceptance criteria. If the information is complete, I should move to the next page for booking the onboarding.

**Action:** fill(63, 'Smith') # Fill in the Last Name with a sample name
click(65) # Click on the 'Continue' button to proceed.

**Change Description:** The Last Name textbox was updated with the value 'Smith' and the form was submitted by clicking the 'Continue' button, resulting in a navigation to a new page titled 'Book onboarding'.

**Screenshot before:****Screenshot after:**---

