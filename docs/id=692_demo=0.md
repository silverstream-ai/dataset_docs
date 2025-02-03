# Task

**Checking Eligibility for Medicaid**

As a potential Medicaid recipient,
I check my eligibility for Medicaid coverage,
so that I can understand what benefits I may be entitled to and how to access them.

**Success definition:** Given I am on the Fortuna Health eligibility page
When I check the 'Checking Eligibility' checkbox and click the 'Next' button
Then I should see options to select whether I am checking eligibility for myself or my household along with a progress bar indicating my current status.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.fortunahealth.com/

https://app.fortunahealth.com/eligibility

**Content (before/after):** 

```
RootWebArea Medicaid Made Easy | Fortuna Health, focused, url='https://www.fortunahealth.com/'
	main
		banner
			[35] link, center=(236,56), url='http://www.fortunahealth.com/'
				image, url='https://cdn.prod.website-files.com/644edae40aef43dacc33caad/64daad5557665e4bbe170b8e_Logo-p-500.png'
```
<details><summary>Show more</summary>

```
			navigation
				[39] link Health Plans, center=(400,56), url='https://www.fortunahealth.com/health-plans'
				[40] link Providers, center=(511,56), url='https://www.fortunahealth.com/providers'
				[41] link Resources, center=(614,56), url='https://www.fortunahealth.com/resources'
			[46] link Login, center=(1608,56), url='https://app.fortunahealth.com/login'
			[47] link Sign up, center=(1741,56), url='https://app.fortunahealth.com/signup'
		heading Medicaid made easy
		StaticText Navigating Medicaid for consumers is always fast, simple, and digital with Fortuna.
		[110] link Get Medicaid Help, center=(841,671), url='https://app.fortunahealth.com/eligibility'
		[111] button Partner with Us, center=(1093,671), expanded=False, hasPopup='dialog'
		image, url='https://cdn.prod.website-files.com/644edae40aef43dacc33caad/6778829bc747dcc5e6de3444_Search%20Heart.svg'
		image, url='https://cdn.prod.website-files.com/644edae40aef43dacc33caad/677882cc77d43b89f399fa45_Stethoscope.svg'
		image, url='https://cdn.prod.website-files.com/644edae40aef43dacc33caad/67788217981c4d87afc53f1f_Cell%20Phone.svg'
		image, url='https://cdn.prod.website-files.com/644edae40aef43dacc33caad/67797a9e2927787791bd1141_Woman-Notifications.svg'
		heading Eligibility checks in as little as 30 seconds
		StaticText No complicated forms and sign ups - just a fast screening for government coverage.
		SvgRoot
			group 0 sec
		heading Fast enrollment and renewal
		StaticText Smart, guided enrollment and renewal for the right Medicaid programs.
		heading Never miss an action
		StaticText Always up-to-date on enrollment status with notifications for every important admin action.
		heading Outstanding results and outcomes
		StaticText We meet Medicaid consumers where they are - regardless of circumstances and barriers to coverage.
		image, url='https://cdn.prod.website-files.com/644edae40aef43dacc33caad/6722bc12332b6097debf2ea1_material-symbols_dashboard-outline.png'
		heading 5x faster Medicaid experience
		paragraph
			StaticText Consumers deserve a simple Medicaid experience. Fortuna’s dynamic enrollment by state, program, and household situation speeds up time-to-enrollment.
		image, url='https://cdn.prod.website-files.com/644edae40aef43dacc33caad/6722bc1280a58bcfbb92ca04_cuida_radar-outline.png'
		heading 15% increase in renewal rates
		paragraph
			StaticText Fortuna’s personalized engagement, custom tool tips, and guided, end-to-end process makes renewals easier. 52% of users completing their actions the same day.
		image, url='https://cdn.prod.website-files.com/644edae40aef43dacc33caad/6722bc1260a82653f46bbd60_stash_wand-light.png'
		heading Closed loop reporting with full visibility
		paragraph
			StaticText See the whole picture. Fortuna’s reporting gives partners comprehensive data the entire eligibility, enrollment, and renewal funnel.
		image, url='https://cdn.prod.website-files.com/644edae40aef43dacc33caad/6722bc12cbb0d44ab32291fc_mynaui_click.png'
		heading 95% application approval
		paragraph
			StaticText Every application counts. With Fortuna’s 24/7 support, virtual mailbox, and multilingual assistance, even the most complex enrollments and renewals are handled from start to finish.
		heading Why consumers love Fortuna
		StaticText No more paper Medicaid forms, long call wait times, and lost recertification notices.
		image, url='https://cdn.prod.website-files.com/644edae40aef43dacc33caad/65f4a1834e092775d87167af_Pixel%207.svg'
		image, url='https://cdn.prod.website-files.com/644edae40aef43dacc33caad/6779778dc3156ee8fe96182a_Digital.svg'
		heading Simple, fast, digital experience
		StaticText Tailored to consumer situations
		image, url='https://cdn.prod.website-files.com/644edae40aef43dacc33caad/65f4a1834e092775d87167af_Pixel%207.svg'
		image, url='https://cdn.prod.website-files.com/644edae40aef43dacc33caad/6779780669f3a0277518e741_Language.svg'
		heading Multilingual live navigation
		StaticText Available 24/7 for consumers
		image, url='https://cdn.prod.website-files.com/644edae40aef43dacc33caad/65f4a1834e092775d87167af_Pixel%207.svg'
		image, url='https://cdn.prod.website-files.com/644edae40aef43dacc33caad/67797888ca2758e3a277dc9b_Notifications.svg'
		heading Stay up-to-date
		StaticText With communications and actions - handled by Fortuna
		heading Still have questions?
		StaticText Medicaid and state-sponsored health insurance can be confusing so we’ve tried in plain language to answer common questions.
		heading What is the difference between Medicare and Medicaid ?
		StaticText Medicare is health insurance that generally covers people aged 65+. Medicaid covers people of all ages if you make below a certain income or face hardship based on other circumstances like disability.
		StaticText Fortuna focuses on Medicaid. If you need Medicare support, we can help you dual-enroll.
		heading Can I use Fortuna to renew Medicaid coverage?
		StaticText Yes. We make it easy to renew on Medicaid.
		StaticText With a dedicated, licensed navigator and our automations, never miss a Medicaid-related notification from the state or county.
		heading Why apply through Fortuna Health?ﾠ
		StaticText Filling out government forms can be confusing and stressful. And with the state working overtime to keep their websites and team running, glitches and lags in the system are understandable.
		StaticText We built Fortuna so that you don’t need to deal with that. Spend 10 minutes working on your enrollment and even less with renewals.
		StaticText We take care of the rest with the state.
		heading Do I need to come to Fortuna through an insurance company or doctor?
		StaticText Yes, Fortuna is only available through providers and insurers. Please contact us at
		link help@fortunahealth.com, url='mailto:help@fortunahealth.com'
		StaticText for more information.
		heading What is Medicaid ?
		StaticText Medicaid is $0 or low-cost health insurance covered by the government. Eligibility varies by factors like state, household size, and income.
		heading How do I apply for Medicaid ?
		StaticText Anyone can apply for Medicaid directly with the state or with the help of licensed healthcare navigators like Fortuna.
		link Get started here, url='https://app.fortunahealth.com/eligibility'
		heading Why trust Fortuna?
		StaticText Every Fortuna navigator is certified and licensed to enroll. Our platform is built for and by Medicaid members based on our lived experiences, with multilingual support.
		StaticText Show full list of questions
		heading Are you a business that wants to offer Medicaid navigation?
		StaticText See how providing consumers with Medicaid enrollment and renewal can improve revenue and decrease care gaps.
		link Health Plans, url='https://www.fortunahealth.com/health-plans'
		link Providers, url='https://www.fortunahealth.com/providers'
		link, url='https://www.fortunahealth.com/'
			image, url='https://cdn.prod.website-files.com/644edae40aef43dacc33caad/64b0599f24dd751863cbe65b_Group%204-p-500.png'
		link Terms of Service, url='https://app.fortunahealth.com/tos'
		link Privacy Policy, url='https://app.fortunahealth.com/privacy-policy'
		link Security, url='https://www.fortunahealth.com/security-policy'
		link System Status, url='https://status.fortunahealth.com/'
		link help@fortunahealth.com, url='mailto:help@fortunahealth.com'
		image, url='https://cdn.prod.website-files.com/644edae40aef43dacc33caad/64daa9b2f826137d74651bae_HIPAA%20Vanta.png'
		image, url='https://cdn.prod.website-files.com/644edae40aef43dacc33caad/65dfb61d0d1e64d54d0b4512_Vanta_Compliance_SOC%202%20(1).png'
		link, url='https://www.linkedin.com/company/fortuna-health/'
			image, url='https://cdn.prod.website-files.com/644edae40aef43dacc33caad/64b1635686e5bb441d771e85_linkedin-2-icon-11-256.png'
		link, url='https://twitter.com/hifortunahealth'
			image, url='https://cdn.prod.website-files.com/644edae40aef43dacc33caad/64ad76009abfb265fd8f5a00_31%20Twitter.svg'
		link, url='https://www.facebook.com/fortunahealth'
			image, url='https://cdn.prod.website-files.com/644edae40aef43dacc33caad/64ad76004b6011e52720fde1_32%20Facebook.svg'
```
</details>



```
RootWebArea Medicaid Eligibility | Fortuna, focused, url='https://app.fortunahealth.com/eligibility'
	main
		[77] link Fortuna Health, center=(84,32), url='https://fortunahealth.com/'
			image Fortuna Health, url='https://app.fortunahealth.com/_next/image?url=%2Flogo-long.png&w=256&q=75'
		[80] button Language menu, center=(1676,32), expanded=False, hasPopup='menu', type=button
```
<details><summary>Show more</summary>

```
			image
		[84] link Log in, center=(1750,32), url='https://app.fortunahealth.com/login'
		[85] link Sign up, center=(1848,32), url='https://app.fortunahealth.com/signup'
		heading Hi there! What do you need help with?
		[96] checkbox Medical Bills, center=(744,332), checked='false', type=button
			image, url='https://app.fortunahealth.com/illustrations/stethoscope.svg'
		[103] checkbox Pharmacy Bills, center=(960,332), checked='false', type=button
			image, url='https://app.fortunahealth.com/illustrations/pills.svg'
		[110] checkbox Checking Eligibility, center=(1176,332), checked='false', type=button
			image, url='https://app.fortunahealth.com/illustrations/form.svg'
		[117] checkbox Existing Health Insurance, center=(852,544), checked='false', type=button
			image, url='https://app.fortunahealth.com/illustrations/insurance-card.svg'
		[124] checkbox Something Else, center=(1068,544), checked='false', type=button
			image, url='https://app.fortunahealth.com/illustrations/something-else.svg'
		[130] button Next, center=(960,722), type=submit
		link Privacy Policy, url='https://app.fortunahealth.com/privacy-policy'
		StaticText •
		link Terms of Service, url='https://app.fortunahealth.com/tos'
		StaticText •
		link HIPAA Compliant, url='https://www.aptible.com/secured-by-aptible'
		StaticText ©
		StaticText 2025
		StaticText Fortuna Health, Inc. All rights reserved.
	alert, atomic
	image
	paragraph
		StaticText We use cookies on this site to improve security and enhance your experience. For more information, see our
		[142] link Privacy Policy, center=(586,1022), url='https://app.fortunahealth.com/privacy-policy'
		StaticText .
	[143] button Acknowledge, center=(1352,1012), type=button
```
</details>

**Reasoning for action:** By clicking on the 'Get Medicaid Help' button, I directed myself to the relevant section of the Fortuna Health website where eligibility for Medicaid is assessed. This is a crucial step towards checking my eligibility, as it is necessary to access the tools and forms needed to understand the benefits I may be entitled to.

**Action:** click(110) # Click on the 'Get Medicaid Help' button to explore further.

**Change Description:** After clicking the 'Get Medicaid Help' button, the browser navigated to the Medicaid Eligibility page, displaying a new layout that includes checkboxes for various assistance options (e.g., Medical Bills, Pharmacy Bills) and a button to proceed, replacing the initial information about Medicaid with interactive elements aimed at guiding users through the eligibility process.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://app.fortunahealth.com/eligibility

https://app.fortunahealth.com/eligibility

**Content (before/after):** 

```
RootWebArea Medicaid Eligibility | Fortuna, focused, url='https://app.fortunahealth.com/eligibility'
	main
		[77] link Fortuna Health, center=(84,32), url='https://fortunahealth.com/'
			image Fortuna Health, url='https://app.fortunahealth.com/_next/image?url=%2Flogo-long.png&w=256&q=75'
		[80] button Language menu, center=(1676,32), expanded=False, hasPopup='menu', type=button
```
<details><summary>Show more</summary>

```
			image
		[84] link Log in, center=(1750,32), url='https://app.fortunahealth.com/login'
		[85] link Sign up, center=(1848,32), url='https://app.fortunahealth.com/signup'
		heading Hi there! What do you need help with?
		[96] checkbox Medical Bills, center=(744,332), checked='false', type=button
			image, url='https://app.fortunahealth.com/illustrations/stethoscope.svg'
		[103] checkbox Pharmacy Bills, center=(960,332), checked='false', type=button
			image, url='https://app.fortunahealth.com/illustrations/pills.svg'
		[110] checkbox Checking Eligibility, center=(1176,332), checked='false', type=button
			image, url='https://app.fortunahealth.com/illustrations/form.svg'
		[117] checkbox Existing Health Insurance, center=(852,544), checked='false', type=button
			image, url='https://app.fortunahealth.com/illustrations/insurance-card.svg'
		[124] checkbox Something Else, center=(1068,544), checked='false', type=button
			image, url='https://app.fortunahealth.com/illustrations/something-else.svg'
		[130] button Next, center=(960,722), type=submit
		link Privacy Policy, url='https://app.fortunahealth.com/privacy-policy'
		StaticText •
		link Terms of Service, url='https://app.fortunahealth.com/tos'
		StaticText •
		link HIPAA Compliant, url='https://www.aptible.com/secured-by-aptible'
		StaticText ©
		StaticText 2025
		StaticText Fortuna Health, Inc. All rights reserved.
	alert, atomic
	image
	paragraph
		StaticText We use cookies on this site to improve security and enhance your experience. For more information, see our
		[142] link Privacy Policy, center=(586,1022), url='https://app.fortunahealth.com/privacy-policy'
		StaticText .
	[143] button Acknowledge, center=(1352,1012), type=button
```
</details>



```
RootWebArea Medicaid Eligibility | Fortuna, focused, url='https://app.fortunahealth.com/eligibility'
	main
		[77] link Fortuna Health, center=(84,32), url='https://fortunahealth.com/'
			image Fortuna Health, url='https://app.fortunahealth.com/_next/image?url=%2Flogo-long.png&w=256&q=75'
		[80] button Language menu, center=(1676,32), expanded=False, hasPopup='menu', type=button
```
<details><summary>Show more</summary>

```
			image
		[84] link Log in, center=(1750,32), url='https://app.fortunahealth.com/login'
		[85] link Sign up, center=(1848,32), url='https://app.fortunahealth.com/signup'
		heading Hi there! What do you need help with?
		[96] checkbox Medical Bills, center=(744,332), checked='false', type=button
			image, url='https://app.fortunahealth.com/illustrations/stethoscope.svg'
		[103] checkbox Pharmacy Bills, center=(960,332), checked='false', type=button
			image, url='https://app.fortunahealth.com/illustrations/pills.svg'
		[110] checkbox Checking Eligibility, center=(1176,332), checked='true', focused, type=button
			image, url='https://app.fortunahealth.com/illustrations/form.svg'
			image
		[117] checkbox Existing Health Insurance, center=(852,544), checked='false', type=button
			image, url='https://app.fortunahealth.com/illustrations/insurance-card.svg'
		[124] checkbox Something Else, center=(1068,544), checked='false', type=button
			image, url='https://app.fortunahealth.com/illustrations/something-else.svg'
		[130] button Next, center=(960,722), type=submit
		link Privacy Policy, url='https://app.fortunahealth.com/privacy-policy'
		StaticText •
		link Terms of Service, url='https://app.fortunahealth.com/tos'
		StaticText •
		link HIPAA Compliant, url='https://www.aptible.com/secured-by-aptible'
		StaticText ©
		StaticText 2025
		StaticText Fortuna Health, Inc. All rights reserved.
	alert, atomic
	image
	paragraph
		StaticText We use cookies on this site to improve security and enhance your experience. For more information, see our
		[142] link Privacy Policy, center=(586,1022), url='https://app.fortunahealth.com/privacy-policy'
		StaticText .
	[143] button Acknowledge, center=(1352,1012), type=button
```
</details>

**Reasoning for action:** I chose to click the 'Checking Eligibility' checkbox because this action directly addresses the user's task of checking their Medicaid eligibility. By selecting this option, I am ensuring that the user can move forward in the process of determining their eligibility, which is a key part of their overall goal. This is a required step before I can proceed to the next page where the user will be able to see options for whether they are checking eligibility for themselves or for their household.

**Action:** click(110) # Click on the 'Checking Eligibility' checkbox to proceed with that option.

**Change Description:** The 'Checking Eligibility' checkbox has been checked, indicating that the user has selected this option to proceed. Additionally, this checkbox is now focused.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://app.fortunahealth.com/eligibility

https://app.fortunahealth.com/eligibility/target

**Content (before/after):** 

```
RootWebArea Medicaid Eligibility | Fortuna, focused, url='https://app.fortunahealth.com/eligibility'
	main
		[77] link Fortuna Health, center=(84,32), url='https://fortunahealth.com/'
			image Fortuna Health, url='https://app.fortunahealth.com/_next/image?url=%2Flogo-long.png&w=256&q=75'
		[80] button Language menu, center=(1676,32), expanded=False, hasPopup='menu', type=button
```
<details><summary>Show more</summary>

```
			image
		[84] link Log in, center=(1750,32), url='https://app.fortunahealth.com/login'
		[85] link Sign up, center=(1848,32), url='https://app.fortunahealth.com/signup'
		heading Hi there! What do you need help with?
		[96] checkbox Medical Bills, center=(744,332), checked='false', type=button
			image, url='https://app.fortunahealth.com/illustrations/stethoscope.svg'
		[103] checkbox Pharmacy Bills, center=(960,332), checked='false', type=button
			image, url='https://app.fortunahealth.com/illustrations/pills.svg'
		[110] checkbox Checking Eligibility, center=(1176,332), checked='true', focused, type=button
			image, url='https://app.fortunahealth.com/illustrations/form.svg'
			image
		[117] checkbox Existing Health Insurance, center=(852,544), checked='false', type=button
			image, url='https://app.fortunahealth.com/illustrations/insurance-card.svg'
		[124] checkbox Something Else, center=(1068,544), checked='false', type=button
			image, url='https://app.fortunahealth.com/illustrations/something-else.svg'
		[130] button Next, center=(960,722), type=submit
		link Privacy Policy, url='https://app.fortunahealth.com/privacy-policy'
		StaticText •
		link Terms of Service, url='https://app.fortunahealth.com/tos'
		StaticText •
		link HIPAA Compliant, url='https://www.aptible.com/secured-by-aptible'
		StaticText ©
		StaticText 2025
		StaticText Fortuna Health, Inc. All rights reserved.
	alert, atomic
	image
	paragraph
		StaticText We use cookies on this site to improve security and enhance your experience. For more information, see our
		[142] link Privacy Policy, center=(586,1022), url='https://app.fortunahealth.com/privacy-policy'
		StaticText .
	[143] button Acknowledge, center=(1352,1012), type=button
```
</details>



```
RootWebArea Medicaid Eligibility | Fortuna, focused, url='https://app.fortunahealth.com/eligibility/target'
	main
		[198] link Fortuna Health, center=(84,32), url='https://fortunahealth.com/'
			image Fortuna Health, url='https://app.fortunahealth.com/_next/image?url=%2Flogo-long.png&w=256&q=75'
		[201] button Restart, center=(1628,32), type=button
```
<details><summary>Show more</summary>

```
			image
		[203] button Language menu, center=(1676,32), expanded=False, hasPopup='menu', type=button
			image
		[207] link Log in, center=(1750,32), url='https://app.fortunahealth.com/login'
		[208] link Sign up, center=(1848,32), url='https://app.fortunahealth.com/signup'
		[214] button Go back to previous step, center=(72,99), inner_text=Back, type=button
			image
			StaticText Back
		progressbar value='5'
		heading Great, we can help with that! Would you like to check for just yourself or your household?
		radiogroup Subject of eligibility check
			[227] radio Just me, center=(852,441), checked='false', type=button
				image
			[233] radio My household, center=(1068,441), checked='false', type=button
				image
		[239] button Next, center=(960,642), type=submit
		link Privacy Policy, url='https://app.fortunahealth.com/privacy-policy'
		StaticText •
		link Terms of Service, url='https://app.fortunahealth.com/tos'
		StaticText •
		link HIPAA Compliant, url='https://www.aptible.com/secured-by-aptible'
		StaticText ©
		StaticText 2025
		StaticText Fortuna Health, Inc. All rights reserved.
	alert, atomic
		StaticText Medicaid Eligibility | Fortuna
	image
	paragraph
		StaticText We use cookies on this site to improve security and enhance your experience. For more information, see our
		[142] link Privacy Policy, center=(586,1022), url='https://app.fortunahealth.com/privacy-policy'
		StaticText .
	[143] button Acknowledge, center=(1352,1012), type=button
```
</details>

**Reasoning for action:** My reasoning for this action was to progress the user through the eligibility checking process since they have already selected the 'Checking Eligibility' checkbox. By clicking the 'Next' button, this action will trigger the website to display the subsequent options for selecting whether the user is checking eligibility for themselves or their household, as stated in the user story. This fulfills a critical part of achieving the user's goal of understanding potential Medicaid benefits.

**Action:** click(130) # Click on the 'Next' button to proceed with checking eligibility.

**Change Description:** After clicking the 'Next' button, the browser navigated to a new URL ('https://app.fortunahealth.com/eligibility/target') and updated the content to prompt the user to choose whether they are checking eligibility for just themselves or their household, along with a new progress bar indicating ongoing steps.

**Screenshot before:****Screenshot after:**---

