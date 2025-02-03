# Task

**Explore Cercli's Offerings and Mission**

As an interested potential customer,
I explore the Cercli platform's offerings and learn about the company's mission,
so that I can understand how Cercli can meet my business needs.

**Success definition:** Given I am on the Cercli homepage
When I navigate through the 'Why Cercli?', 'Product', and 'About Us' tabs
Then I should be able to view information about the platform's value, specific offerings, and the company's mission and values.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.cercli.com/

https://www.cercli.com/

**Content (before/after):** 

```
RootWebArea Cercli: The Modern Platform for HR, Payroll, Finance and IT, focused, url='https://www.cercli.com/'
	banner
		paragraph
			StaticText 🚀 Catch Up on Product Launch Week Highlights!
			[212] link 👉 Read the full recap, center=(1152,20), url='https://www.cercli.com/blog/cercli-2024-product-launch-week'
```
<details><summary>Show more</summary>

```
		[215] link Cercli, center=(434,77), url='https://www.cercli.com/'
			image Cercli, url='https://www.cercli.com/cercli-logo.svg'
		navigation
			tablist, orientation='horizontal'
				[226] tab Why Cercli?, center=(754,77), selected=True, type=button
				[228] tab Product, center=(861,77), selected=False, type=button
				[230] tab About Us, center=(959,77), selected=False, type=button
			tablist, orientation='horizontal'
				[236] tab Blog, center=(1044,77), selected=False, type=button
		[255] link Sign In, center=(1330,77), url='https://app.cercli.com/login'
		[257] link Book Demo, center=(1463,77), url='https://www.cercli.com/join'
			button Book Demo
	image cercli hero image, url='https://www.cercli.com/_next/static/media/hero.bacb027e.jpg'
	image cercli hero image, url='https://www.cercli.com/_next/static/media/hero-circle.f719c080.png'
	heading The single modern platform for MENA to run your entire workforce
		strong
	paragraph
		StaticText Get started
	[276] link Book Demo, center=(1010,603), url='https://www.cercli.com/join'
		button Book Demo
	StaticText Designed and localized for the
	strong
		StaticText Middle East and North Africa
	heading Team Management
	paragraph
		StaticText Manage your team’s employment and payroll data in one secure platform.
	image Team Management, url='https://www.cercli.com/assets/card-people.png'
	heading Payroll
	paragraph
		StaticText Pay your entire team in multiple currencies and send payslips or contractor invoices.
	image Payroll, url='https://www.cercli.com/assets/card-payroll.png'
	heading Reimbursements
	paragraph
		StaticText Review and process team expense reimbursements in any currency.
	image Reimbursements, url='https://www.cercli.com/assets/card-expenses.png'
	heading Time Off
	paragraph
		StaticText Manage time off policies, review time off requests and track balances all in one place.
	image Time Off, url='https://www.cercli.com/assets/card-timeoff.png'
	paragraph
		StaticText A local platform to help
		StaticText you run fast
		strong
			StaticText globally
	link Book demo, url='https://www.cercli.com/join'
		button Book demo
	heading One platform to manage your global team
	list
		listitem
			paragraph
				StaticText A single, secure source of truth for all team members’ data
		listitem
			paragraph
				StaticText Compliant hiring and payments for WPS employees, employer of records, and contractors
		listitem
			paragraph
				StaticText One single monthly payment for all salaries, expense claims, and contractor service fees
	image Cercli global payroll, url='https://www.cercli.com/_next/static/media/global.6a143c98.svg'
	heading Run fully-automated payroll in minutes, stress-free
	list
		listitem
			paragraph
				StaticText Eliminate the human errors that come with entering data manually and downloading reports to move payroll between systems
		listitem
			paragraph
				StaticText Avoid fines and stay 100% compliant with local regulations, reporting and tax filings
		listitem
			paragraph
				StaticText Fully customized reports for your finance teams
	image
	heading Systems that now "speak to each other"
	list
		listitem
			paragraph
				StaticText Key integrations across HR, Finance, Accounting, Legal and IT
		listitem
			paragraph
				StaticText Full control of your workflows. No more calendar reminders to send that onboarding email or add a new joiner to Slack
		listitem
			paragraph
				StaticText The single source of truth for your company's greatest asset – your people
	image
	heading Enterprise Level-Security on a Single Platform
	paragraph
		StaticText Secure your people data with Cercli's technical, organizational, and physical safeguards
	link GDPR compliant, url='https://app.drata.com/trust/61f4ed60-97a3-4f01-895a-6e3f656997c9'
		image GDPR compliant, url='https://www.cercli.com/assets/gdpr.svg'
	image Cercli security, url='https://www.cercli.com/_next/static/media/security.41404a34.png'
	heading About Us
	paragraph
		StaticText Our purpose is to unlock the true potential of organizations and their people
	heading Our Values
	heading Our values drive the way we hire, the way we make decisions, and the way we build
	button icon We Are Owners, Not Employees, expanded=False
		image icon, url='https://www.cercli.com/assets/key-icon.svg'
		heading We Are Owners, Not Employees
	button icon We Dream Big & Prioritize Diligently, expanded=False
		image icon, url='https://www.cercli.com/assets/dart-icon.svg'
		heading We Dream Big & Prioritize Diligently
	button icon We Practice Empathy & Radical Transparency, expanded=False
		image icon, url='https://www.cercli.com/assets/heart-icon.svg'
		heading We Practice Empathy & Radical Transparency
	heading Backed by
	link Afore logo, url='https://www.afore.vc/'
		image Afore logo, url='https://www.cercli.com/_next/static/media/afore.18d1e4a3.png'
	link Cotu logo, url='https://www.cotu.vc/'
		image Cotu logo, url='https://www.cercli.com/_next/static/media/cotu.cc8108f9.svg'
	link YCombinator logo, url='https://www.ycombinator.com/'
		image YCombinator logo, url='https://www.cercli.com/_next/static/media/ycombinator.26770c7e.svg'
	contentinfo
		paragraph
			StaticText Automate
			StaticText your local and remote payroll, HRIS, expenses, onboarding and more
		image Cercli, url='https://www.cercli.com/cercli-logo-icon.svg'
		paragraph
			StaticText Get started
		link Book Demo, url='https://www.cercli.com/join'
			button Book Demo
		button Why Cercli?
		button Product
		button About Us
		link, url='https://www.linkedin.com/company/cercli/'
		link, url='https://twitter.com/cercliHQ'
		link Privacy Policy, url='https://www.cercli.com/privacy-policy'
			button Privacy Policy
		link Terms, url='https://www.cercli.com/terms'
			button Terms
		link Status, url='http://status.cercli.com/'
			button Status
		paragraph
			StaticText © 2025 Cercli · All rights reserved
	StaticText By using this website you agree with our privacy and cookies policy
	[581] button Agree, center=(1160,1029), type=button
	alert, atomic
```
</details>



```
RootWebArea Cercli: The Modern Platform for HR, Payroll, Finance and IT, focused, url='https://www.cercli.com/'
	banner
		paragraph
			StaticText 🚀 Catch Up on Product Launch Week Highlights!
			[212] link 👉 Read the full recap, center=(1152,20), url='https://www.cercli.com/blog/cercli-2024-product-launch-week'
```
<details><summary>Show more</summary>

```
		[215] link Cercli, center=(434,77), url='https://www.cercli.com/'
			image Cercli, url='https://www.cercli.com/cercli-logo.svg'
		navigation
			tablist, orientation='horizontal'
				[226] tab Why Cercli?, center=(754,77), focused, selected=True, type=button
				[228] tab Product, center=(861,77), selected=False, type=button
				[230] tab About Us, center=(959,77), selected=False, type=button
			tablist, orientation='horizontal'
				[236] tab Blog, center=(1044,77), selected=False, type=button
		[255] link Sign In, center=(1330,77), url='https://app.cercli.com/login'
		[257] link Book Demo, center=(1463,77), url='https://www.cercli.com/join'
			button Book Demo
	image cercli hero image, url='https://www.cercli.com/_next/static/media/hero.bacb027e.jpg'
	image cercli hero image, url='https://www.cercli.com/_next/static/media/hero-circle.f719c080.png'
	heading The single modern platform for MENA to run your entire workforce
		strong
	paragraph
		StaticText Get started
	[276] link Book Demo, center=(1010,603), url='https://www.cercli.com/join'
		button Book Demo
	StaticText Designed and localized for the
	strong
		StaticText Middle East and North Africa
	heading Team Management
	paragraph
		StaticText Manage your team’s employment and payroll data in one secure platform.
	image Team Management, url='https://www.cercli.com/assets/card-people.png'
	heading Payroll
	paragraph
		StaticText Pay your entire team in multiple currencies and send payslips or contractor invoices.
	image Payroll, url='https://www.cercli.com/assets/card-payroll.png'
	heading Reimbursements
	paragraph
		StaticText Review and process team expense reimbursements in any currency.
	image Reimbursements, url='https://www.cercli.com/assets/card-expenses.png'
	heading Time Off
	paragraph
		StaticText Manage time off policies, review time off requests and track balances all in one place.
	image Time Off, url='https://www.cercli.com/assets/card-timeoff.png'
	paragraph
		StaticText A local platform to help
		StaticText you run fast
		strong
			StaticText globally
	link Book demo, url='https://www.cercli.com/join'
		button Book demo
	heading One platform to manage your global team
	list
		listitem
			paragraph
				StaticText A single, secure source of truth for all team members’ data
		listitem
			paragraph
				StaticText Compliant hiring and payments for WPS employees, employer of records, and contractors
		listitem
			paragraph
				StaticText One single monthly payment for all salaries, expense claims, and contractor service fees
	image Cercli global payroll, url='https://www.cercli.com/_next/static/media/global.6a143c98.svg'
	heading Run fully-automated payroll in minutes, stress-free
	list
		listitem
			paragraph
				StaticText Eliminate the human errors that come with entering data manually and downloading reports to move payroll between systems
		listitem
			paragraph
				StaticText Avoid fines and stay 100% compliant with local regulations, reporting and tax filings
		listitem
			paragraph
				StaticText Fully customized reports for your finance teams
	image
	heading Systems that now "speak to each other"
	list
		listitem
			paragraph
				StaticText Key integrations across HR, Finance, Accounting, Legal and IT
		listitem
			paragraph
				StaticText Full control of your workflows. No more calendar reminders to send that onboarding email or add a new joiner to Slack
		listitem
			paragraph
				StaticText The single source of truth for your company's greatest asset – your people
	image
	heading Enterprise Level-Security on a Single Platform
	paragraph
		StaticText Secure your people data with Cercli's technical, organizational, and physical safeguards
	link GDPR compliant, url='https://app.drata.com/trust/61f4ed60-97a3-4f01-895a-6e3f656997c9'
		image GDPR compliant, url='https://www.cercli.com/assets/gdpr.svg'
	image Cercli security, url='https://www.cercli.com/_next/static/media/security.41404a34.png'
	heading About Us
	paragraph
		StaticText Our purpose is to unlock the true potential of organizations and their people
	heading Our Values
	heading Our values drive the way we hire, the way we make decisions, and the way we build
	button icon We Are Owners, Not Employees, expanded=False
		image icon, url='https://www.cercli.com/assets/key-icon.svg'
		heading We Are Owners, Not Employees
	button icon We Dream Big & Prioritize Diligently, expanded=False
		image icon, url='https://www.cercli.com/assets/dart-icon.svg'
		heading We Dream Big & Prioritize Diligently
	button icon We Practice Empathy & Radical Transparency, expanded=False
		image icon, url='https://www.cercli.com/assets/heart-icon.svg'
		heading We Practice Empathy & Radical Transparency
	heading Backed by
	link Afore logo, url='https://www.afore.vc/'
		image Afore logo, url='https://www.cercli.com/_next/static/media/afore.18d1e4a3.png'
	link Cotu logo, url='https://www.cotu.vc/'
		image Cotu logo, url='https://www.cercli.com/_next/static/media/cotu.cc8108f9.svg'
	link YCombinator logo, url='https://www.ycombinator.com/'
		image YCombinator logo, url='https://www.cercli.com/_next/static/media/ycombinator.26770c7e.svg'
	contentinfo
		paragraph
			StaticText Automate
			StaticText your local and remote payroll, HRIS, expenses, onboarding and more
		image Cercli, url='https://www.cercli.com/cercli-logo-icon.svg'
		paragraph
			StaticText Get started
		link Book Demo, url='https://www.cercli.com/join'
			button Book Demo
		button Why Cercli?
		button Product
		button About Us
		link, url='https://www.linkedin.com/company/cercli/'
		link, url='https://twitter.com/cercliHQ'
		link Privacy Policy, url='https://www.cercli.com/privacy-policy'
			button Privacy Policy
		link Terms, url='https://www.cercli.com/terms'
			button Terms
		link Status, url='http://status.cercli.com/'
			button Status
		paragraph
			StaticText © 2025 Cercli · All rights reserved
	StaticText By using this website you agree with our privacy and cookies policy
	[581] button Agree, center=(1160,1029), type=button
	alert, atomic
```
</details>

**Reasoning for action:** By clicking on the 'Why Cercli?' tab, I aimed to gather information on the unique value propositions of the Cercli platform. This section is likely to highlight the reasons a potential customer should consider Cercli, addressing their needs and expectations. It directly aligns with the user story of exploring what Cercli has to offer.

**Action:** click(226) # Click on the 'Why Cercli?' tab to explore more about the platform.

**Change Description:** The active navigation state changed as the 'Why Cercli?' tab became selected and focused, while all other tabs remain unselected. This indicates that the user is now exploring the reasons for using the Cercli platform.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://www.cercli.com/

https://www.cercli.com/

**Content (before/after):** 

```
RootWebArea Cercli: The Modern Platform for HR, Payroll, Finance and IT, focused, url='https://www.cercli.com/'
	banner
		paragraph
			StaticText 🚀 Catch Up on Product Launch Week Highlights!
			[212] link 👉 Read the full recap, center=(1152,20), url='https://www.cercli.com/blog/cercli-2024-product-launch-week'
```
<details><summary>Show more</summary>

```
		[215] link Cercli, center=(434,77), url='https://www.cercli.com/'
			image Cercli, url='https://www.cercli.com/cercli-logo.svg'
		navigation
			tablist, orientation='horizontal'
				[226] tab Why Cercli?, center=(754,77), focused, selected=True, type=button
				[228] tab Product, center=(861,77), selected=False, type=button
				[230] tab About Us, center=(959,77), selected=False, type=button
			tablist, orientation='horizontal'
				[236] tab Blog, center=(1044,77), selected=False, type=button
		[255] link Sign In, center=(1330,77), url='https://app.cercli.com/login'
		[257] link Book Demo, center=(1463,77), url='https://www.cercli.com/join'
			button Book Demo
	image cercli hero image, url='https://www.cercli.com/_next/static/media/hero.bacb027e.jpg'
	image cercli hero image, url='https://www.cercli.com/_next/static/media/hero-circle.f719c080.png'
	heading The single modern platform for MENA to run your entire workforce
		strong
	paragraph
		StaticText Get started
	[276] link Book Demo, center=(1010,603), url='https://www.cercli.com/join'
		button Book Demo
	StaticText Designed and localized for the
	strong
		StaticText Middle East and North Africa
	heading Team Management
	paragraph
		StaticText Manage your team’s employment and payroll data in one secure platform.
	image Team Management, url='https://www.cercli.com/assets/card-people.png'
	heading Payroll
	paragraph
		StaticText Pay your entire team in multiple currencies and send payslips or contractor invoices.
	image Payroll, url='https://www.cercli.com/assets/card-payroll.png'
	heading Reimbursements
	paragraph
		StaticText Review and process team expense reimbursements in any currency.
	image Reimbursements, url='https://www.cercli.com/assets/card-expenses.png'
	heading Time Off
	paragraph
		StaticText Manage time off policies, review time off requests and track balances all in one place.
	image Time Off, url='https://www.cercli.com/assets/card-timeoff.png'
	paragraph
		StaticText A local platform to help
		StaticText you run fast
		strong
			StaticText globally
	link Book demo, url='https://www.cercli.com/join'
		button Book demo
	heading One platform to manage your global team
	list
		listitem
			paragraph
				StaticText A single, secure source of truth for all team members’ data
		listitem
			paragraph
				StaticText Compliant hiring and payments for WPS employees, employer of records, and contractors
		listitem
			paragraph
				StaticText One single monthly payment for all salaries, expense claims, and contractor service fees
	image Cercli global payroll, url='https://www.cercli.com/_next/static/media/global.6a143c98.svg'
	heading Run fully-automated payroll in minutes, stress-free
	list
		listitem
			paragraph
				StaticText Eliminate the human errors that come with entering data manually and downloading reports to move payroll between systems
		listitem
			paragraph
				StaticText Avoid fines and stay 100% compliant with local regulations, reporting and tax filings
		listitem
			paragraph
				StaticText Fully customized reports for your finance teams
	image
	heading Systems that now "speak to each other"
	list
		listitem
			paragraph
				StaticText Key integrations across HR, Finance, Accounting, Legal and IT
		listitem
			paragraph
				StaticText Full control of your workflows. No more calendar reminders to send that onboarding email or add a new joiner to Slack
		listitem
			paragraph
				StaticText The single source of truth for your company's greatest asset – your people
	image
	heading Enterprise Level-Security on a Single Platform
	paragraph
		StaticText Secure your people data with Cercli's technical, organizational, and physical safeguards
	link GDPR compliant, url='https://app.drata.com/trust/61f4ed60-97a3-4f01-895a-6e3f656997c9'
		image GDPR compliant, url='https://www.cercli.com/assets/gdpr.svg'
	image Cercli security, url='https://www.cercli.com/_next/static/media/security.41404a34.png'
	heading About Us
	paragraph
		StaticText Our purpose is to unlock the true potential of organizations and their people
	heading Our Values
	heading Our values drive the way we hire, the way we make decisions, and the way we build
	button icon We Are Owners, Not Employees, expanded=False
		image icon, url='https://www.cercli.com/assets/key-icon.svg'
		heading We Are Owners, Not Employees
	button icon We Dream Big & Prioritize Diligently, expanded=False
		image icon, url='https://www.cercli.com/assets/dart-icon.svg'
		heading We Dream Big & Prioritize Diligently
	button icon We Practice Empathy & Radical Transparency, expanded=False
		image icon, url='https://www.cercli.com/assets/heart-icon.svg'
		heading We Practice Empathy & Radical Transparency
	heading Backed by
	link Afore logo, url='https://www.afore.vc/'
		image Afore logo, url='https://www.cercli.com/_next/static/media/afore.18d1e4a3.png'
	link Cotu logo, url='https://www.cotu.vc/'
		image Cotu logo, url='https://www.cercli.com/_next/static/media/cotu.cc8108f9.svg'
	link YCombinator logo, url='https://www.ycombinator.com/'
		image YCombinator logo, url='https://www.cercli.com/_next/static/media/ycombinator.26770c7e.svg'
	contentinfo
		paragraph
			StaticText Automate
			StaticText your local and remote payroll, HRIS, expenses, onboarding and more
		image Cercli, url='https://www.cercli.com/cercli-logo-icon.svg'
		paragraph
			StaticText Get started
		link Book Demo, url='https://www.cercli.com/join'
			button Book Demo
		button Why Cercli?
		button Product
		button About Us
		link, url='https://www.linkedin.com/company/cercli/'
		link, url='https://twitter.com/cercliHQ'
		link Privacy Policy, url='https://www.cercli.com/privacy-policy'
			button Privacy Policy
		link Terms, url='https://www.cercli.com/terms'
			button Terms
		link Status, url='http://status.cercli.com/'
			button Status
		paragraph
			StaticText © 2025 Cercli · All rights reserved
	StaticText By using this website you agree with our privacy and cookies policy
	[581] button Agree, center=(1160,1029), type=button
	alert, atomic
```
</details>



```
RootWebArea Cercli: The Modern Platform for HR, Payroll, Finance and IT, focused, url='https://www.cercli.com/'
	banner
		paragraph
			StaticText 🚀 Catch Up on Product Launch Week Highlights!
			[212] link 👉 Read the full recap, center=(1152,1048), url='https://www.cercli.com/blog/cercli-2024-product-launch-week'
```
<details><summary>Show more</summary>

```
		[215] link Cercli, center=(434,1105), url='https://www.cercli.com/'
			image Cercli, url='https://www.cercli.com/cercli-logo.svg'
		navigation
			tablist, orientation='horizontal'
				[226] tab Why Cercli?, center=(754,1105), selected=False, type=button
				[228] tab Product, center=(861,1105), focused, selected=True, type=button
				[230] tab About Us, center=(959,1105), selected=False, type=button
			tablist, orientation='horizontal'
				[236] tab Blog, center=(1044,1105), selected=False, type=button
		[255] link Sign In, center=(1330,1105), url='https://app.cercli.com/login'
		[257] link Book Demo, center=(1463,1105), url='https://www.cercli.com/join'
			button Book Demo
	image cercli hero image, url='https://www.cercli.com/_next/static/media/hero.bacb027e.jpg'
	image cercli hero image, url='https://www.cercli.com/_next/static/media/hero-circle.f719c080.png'
	heading The single modern platform for MENA to run your entire workforce
		strong
	paragraph
		StaticText Get started
	link Book Demo, url='https://www.cercli.com/join'
		button Book Demo
	StaticText Designed and localized for the
	strong
		StaticText Middle East and North Africa
	heading Team Management
	paragraph
		StaticText Manage your team’s employment and payroll data in one secure platform.
	image Team Management, url='https://www.cercli.com/assets/card-people.png'
	heading Payroll
	paragraph
		StaticText Pay your entire team in multiple currencies and send payslips or contractor invoices.
	image Payroll, url='https://www.cercli.com/assets/card-payroll.png'
	heading Reimbursements
	paragraph
		StaticText Review and process team expense reimbursements in any currency.
	image Reimbursements, url='https://www.cercli.com/assets/card-expenses.png'
	heading Time Off
	paragraph
		StaticText Manage time off policies, review time off requests and track balances all in one place.
	image Time Off, url='https://www.cercli.com/assets/card-timeoff.png'
	paragraph
		StaticText A local platform to help
		StaticText you run fast
		strong
			StaticText globally
	link Book demo, url='https://www.cercli.com/join'
		button Book demo
	heading One platform to manage your global team
	list
		listitem
			paragraph
				StaticText A single, secure source of truth for all team members’ data
		listitem
			paragraph
				StaticText Compliant hiring and payments for WPS employees, employer of records, and contractors
		listitem
			paragraph
				StaticText One single monthly payment for all salaries, expense claims, and contractor service fees
	image Cercli global payroll, url='https://www.cercli.com/_next/static/media/global.6a143c98.svg'
	heading Run fully-automated payroll in minutes, stress-free
	list
		listitem
			paragraph
				StaticText Eliminate the human errors that come with entering data manually and downloading reports to move payroll between systems
		listitem
			paragraph
				StaticText Avoid fines and stay 100% compliant with local regulations, reporting and tax filings
		listitem
			paragraph
				StaticText Fully customized reports for your finance teams
	image
	heading Systems that now "speak to each other"
	list
		listitem
			paragraph
				StaticText Key integrations across HR, Finance, Accounting, Legal and IT
		listitem
			paragraph
				StaticText Full control of your workflows. No more calendar reminders to send that onboarding email or add a new joiner to Slack
		listitem
			paragraph
				StaticText The single source of truth for your company's greatest asset – your people
	image
	heading Enterprise Level-Security on a Single Platform
	paragraph
		StaticText Secure your people data with Cercli's technical, organizational, and physical safeguards
	link GDPR compliant, url='https://app.drata.com/trust/61f4ed60-97a3-4f01-895a-6e3f656997c9'
		image GDPR compliant, url='https://www.cercli.com/assets/gdpr.svg'
	image Cercli security, url='https://www.cercli.com/_next/static/media/security.41404a34.png'
	heading About Us
	paragraph
		StaticText Our purpose is to unlock the true potential of organizations and their people
	heading Our Values
	heading Our values drive the way we hire, the way we make decisions, and the way we build
	button icon We Are Owners, Not Employees, expanded=False
		image icon, url='https://www.cercli.com/assets/key-icon.svg'
		heading We Are Owners, Not Employees
	button icon We Dream Big & Prioritize Diligently, expanded=False
		image icon, url='https://www.cercli.com/assets/dart-icon.svg'
		heading We Dream Big & Prioritize Diligently
	button icon We Practice Empathy & Radical Transparency, expanded=False
		image icon, url='https://www.cercli.com/assets/heart-icon.svg'
		heading We Practice Empathy & Radical Transparency
	heading Backed by
	link Afore logo, url='https://www.afore.vc/'
		image Afore logo, url='https://www.cercli.com/_next/static/media/afore.18d1e4a3.png'
	link Cotu logo, url='https://www.cotu.vc/'
		image Cotu logo, url='https://www.cercli.com/_next/static/media/cotu.cc8108f9.svg'
	link YCombinator logo, url='https://www.ycombinator.com/'
		image YCombinator logo, url='https://www.cercli.com/_next/static/media/ycombinator.26770c7e.svg'
	contentinfo
		paragraph
			StaticText Automate
			StaticText your local and remote payroll, HRIS, expenses, onboarding and more
		image Cercli, url='https://www.cercli.com/cercli-logo-icon.svg'
		paragraph
			StaticText Get started
		link Book Demo, url='https://www.cercli.com/join'
			button Book Demo
		button Why Cercli?
		button Product
		button About Us
		link, url='https://www.linkedin.com/company/cercli/'
		link, url='https://twitter.com/cercliHQ'
		link Privacy Policy, url='https://www.cercli.com/privacy-policy'
			button Privacy Policy
		link Terms, url='https://www.cercli.com/terms'
			button Terms
		link Status, url='http://status.cercli.com/'
			button Status
		paragraph
			StaticText © 2025 Cercli · All rights reserved
	StaticText By using this website you agree with our privacy and cookies policy
	[581] button Agree, center=(1160,2057), type=button
	alert, atomic
```
</details>

**Reasoning for action:** By clicking on the 'Product' tab, I access detailed information about the specific services Cercli offers. This is essential to understand how their platform can meet my business needs, fulfilling part of the user story. The information presented in this section will provide insights into the value of Cercli's services, thus advancing my exploration of the platform.

**Action:** click(228) # Click on the 'Product' tab to explore the specific offerings of Cercli.

**Change Description:** After clicking the 'Product' tab, the tab is now marked as focused and selected, while the 'Why Cercli?' tab is deselected, reflecting the user's navigation choice to explore Cercli's specific offerings. Additionally, the vertical position of various elements, including links and buttons, has shifted accordingly due to the change in focus.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://www.cercli.com/

https://www.cercli.com/

**Content (before/after):** 

```
RootWebArea Cercli: The Modern Platform for HR, Payroll, Finance and IT, focused, url='https://www.cercli.com/'
	banner
		paragraph
			StaticText 🚀 Catch Up on Product Launch Week Highlights!
			[212] link 👉 Read the full recap, center=(1152,1048), url='https://www.cercli.com/blog/cercli-2024-product-launch-week'
```
<details><summary>Show more</summary>

```
		[215] link Cercli, center=(434,1105), url='https://www.cercli.com/'
			image Cercli, url='https://www.cercli.com/cercli-logo.svg'
		navigation
			tablist, orientation='horizontal'
				[226] tab Why Cercli?, center=(754,1105), selected=False, type=button
				[228] tab Product, center=(861,1105), focused, selected=True, type=button
				[230] tab About Us, center=(959,1105), selected=False, type=button
			tablist, orientation='horizontal'
				[236] tab Blog, center=(1044,1105), selected=False, type=button
		[255] link Sign In, center=(1330,1105), url='https://app.cercli.com/login'
		[257] link Book Demo, center=(1463,1105), url='https://www.cercli.com/join'
			button Book Demo
	image cercli hero image, url='https://www.cercli.com/_next/static/media/hero.bacb027e.jpg'
	image cercli hero image, url='https://www.cercli.com/_next/static/media/hero-circle.f719c080.png'
	heading The single modern platform for MENA to run your entire workforce
		strong
	paragraph
		StaticText Get started
	link Book Demo, url='https://www.cercli.com/join'
		button Book Demo
	StaticText Designed and localized for the
	strong
		StaticText Middle East and North Africa
	heading Team Management
	paragraph
		StaticText Manage your team’s employment and payroll data in one secure platform.
	image Team Management, url='https://www.cercli.com/assets/card-people.png'
	heading Payroll
	paragraph
		StaticText Pay your entire team in multiple currencies and send payslips or contractor invoices.
	image Payroll, url='https://www.cercli.com/assets/card-payroll.png'
	heading Reimbursements
	paragraph
		StaticText Review and process team expense reimbursements in any currency.
	image Reimbursements, url='https://www.cercli.com/assets/card-expenses.png'
	heading Time Off
	paragraph
		StaticText Manage time off policies, review time off requests and track balances all in one place.
	image Time Off, url='https://www.cercli.com/assets/card-timeoff.png'
	paragraph
		StaticText A local platform to help
		StaticText you run fast
		strong
			StaticText globally
	link Book demo, url='https://www.cercli.com/join'
		button Book demo
	heading One platform to manage your global team
	list
		listitem
			paragraph
				StaticText A single, secure source of truth for all team members’ data
		listitem
			paragraph
				StaticText Compliant hiring and payments for WPS employees, employer of records, and contractors
		listitem
			paragraph
				StaticText One single monthly payment for all salaries, expense claims, and contractor service fees
	image Cercli global payroll, url='https://www.cercli.com/_next/static/media/global.6a143c98.svg'
	heading Run fully-automated payroll in minutes, stress-free
	list
		listitem
			paragraph
				StaticText Eliminate the human errors that come with entering data manually and downloading reports to move payroll between systems
		listitem
			paragraph
				StaticText Avoid fines and stay 100% compliant with local regulations, reporting and tax filings
		listitem
			paragraph
				StaticText Fully customized reports for your finance teams
	image
	heading Systems that now "speak to each other"
	list
		listitem
			paragraph
				StaticText Key integrations across HR, Finance, Accounting, Legal and IT
		listitem
			paragraph
				StaticText Full control of your workflows. No more calendar reminders to send that onboarding email or add a new joiner to Slack
		listitem
			paragraph
				StaticText The single source of truth for your company's greatest asset – your people
	image
	heading Enterprise Level-Security on a Single Platform
	paragraph
		StaticText Secure your people data with Cercli's technical, organizational, and physical safeguards
	link GDPR compliant, url='https://app.drata.com/trust/61f4ed60-97a3-4f01-895a-6e3f656997c9'
		image GDPR compliant, url='https://www.cercli.com/assets/gdpr.svg'
	image Cercli security, url='https://www.cercli.com/_next/static/media/security.41404a34.png'
	heading About Us
	paragraph
		StaticText Our purpose is to unlock the true potential of organizations and their people
	heading Our Values
	heading Our values drive the way we hire, the way we make decisions, and the way we build
	button icon We Are Owners, Not Employees, expanded=False
		image icon, url='https://www.cercli.com/assets/key-icon.svg'
		heading We Are Owners, Not Employees
	button icon We Dream Big & Prioritize Diligently, expanded=False
		image icon, url='https://www.cercli.com/assets/dart-icon.svg'
		heading We Dream Big & Prioritize Diligently
	button icon We Practice Empathy & Radical Transparency, expanded=False
		image icon, url='https://www.cercli.com/assets/heart-icon.svg'
		heading We Practice Empathy & Radical Transparency
	heading Backed by
	link Afore logo, url='https://www.afore.vc/'
		image Afore logo, url='https://www.cercli.com/_next/static/media/afore.18d1e4a3.png'
	link Cotu logo, url='https://www.cotu.vc/'
		image Cotu logo, url='https://www.cercli.com/_next/static/media/cotu.cc8108f9.svg'
	link YCombinator logo, url='https://www.ycombinator.com/'
		image YCombinator logo, url='https://www.cercli.com/_next/static/media/ycombinator.26770c7e.svg'
	contentinfo
		paragraph
			StaticText Automate
			StaticText your local and remote payroll, HRIS, expenses, onboarding and more
		image Cercli, url='https://www.cercli.com/cercli-logo-icon.svg'
		paragraph
			StaticText Get started
		link Book Demo, url='https://www.cercli.com/join'
			button Book Demo
		button Why Cercli?
		button Product
		button About Us
		link, url='https://www.linkedin.com/company/cercli/'
		link, url='https://twitter.com/cercliHQ'
		link Privacy Policy, url='https://www.cercli.com/privacy-policy'
			button Privacy Policy
		link Terms, url='https://www.cercli.com/terms'
			button Terms
		link Status, url='http://status.cercli.com/'
			button Status
		paragraph
			StaticText © 2025 Cercli · All rights reserved
	StaticText By using this website you agree with our privacy and cookies policy
	[581] button Agree, center=(1160,2057), type=button
	alert, atomic
```
</details>



```
RootWebArea Cercli: The Modern Platform for HR, Payroll, Finance and IT, focused, url='https://www.cercli.com/'
	banner
		paragraph
			StaticText 🚀 Catch Up on Product Launch Week Highlights!
			[212] link 👉 Read the full recap, center=(1152,4907), url='https://www.cercli.com/blog/cercli-2024-product-launch-week'
```
<details><summary>Show more</summary>

```
		[215] link Cercli, center=(434,4964), url='https://www.cercli.com/'
			image Cercli, url='https://www.cercli.com/cercli-logo.svg'
		navigation
			tablist, orientation='horizontal'
				[226] tab Why Cercli?, center=(754,4964), selected=False, type=button
				[228] tab Product, center=(861,4964), selected=False, type=button
				[230] tab About Us, center=(959,4964), focused, selected=True, type=button
			tablist, orientation='horizontal'
				[236] tab Blog, center=(1044,4964), selected=False, type=button
		[255] link Sign In, center=(1330,4964), url='https://app.cercli.com/login'
		[257] link Book Demo, center=(1463,4964), url='https://www.cercli.com/join'
			button Book Demo
	image cercli hero image, url='https://www.cercli.com/_next/static/media/hero.bacb027e.jpg'
	image cercli hero image, url='https://www.cercli.com/_next/static/media/hero-circle.f719c080.png'
	heading The single modern platform for MENA to run your entire workforce
		strong
	paragraph
		StaticText Get started
	link Book Demo, url='https://www.cercli.com/join'
		button Book Demo
	StaticText Designed and localized for the
	strong
		StaticText Middle East and North Africa
	heading Team Management
	paragraph
		StaticText Manage your team’s employment and payroll data in one secure platform.
	image Team Management, url='https://www.cercli.com/assets/card-people.png'
	heading Payroll
	paragraph
		StaticText Pay your entire team in multiple currencies and send payslips or contractor invoices.
	image Payroll, url='https://www.cercli.com/assets/card-payroll.png'
	heading Reimbursements
	paragraph
		StaticText Review and process team expense reimbursements in any currency.
	image Reimbursements, url='https://www.cercli.com/assets/card-expenses.png'
	heading Time Off
	paragraph
		StaticText Manage time off policies, review time off requests and track balances all in one place.
	image Time Off, url='https://www.cercli.com/assets/card-timeoff.png'
	paragraph
		StaticText A local platform to help
		StaticText you run fast
		strong
			StaticText globally
	link Book demo, url='https://www.cercli.com/join'
		button Book demo
	heading One platform to manage your global team
	list
		listitem
			paragraph
				StaticText A single, secure source of truth for all team members’ data
		listitem
			paragraph
				StaticText Compliant hiring and payments for WPS employees, employer of records, and contractors
		listitem
			paragraph
				StaticText One single monthly payment for all salaries, expense claims, and contractor service fees
	image Cercli global payroll, url='https://www.cercli.com/_next/static/media/global.6a143c98.svg'
	heading Run fully-automated payroll in minutes, stress-free
	list
		listitem
			paragraph
				StaticText Eliminate the human errors that come with entering data manually and downloading reports to move payroll between systems
		listitem
			paragraph
				StaticText Avoid fines and stay 100% compliant with local regulations, reporting and tax filings
		listitem
			paragraph
				StaticText Fully customized reports for your finance teams
	image
	heading Systems that now "speak to each other"
	list
		listitem
			paragraph
				StaticText Key integrations across HR, Finance, Accounting, Legal and IT
		listitem
			paragraph
				StaticText Full control of your workflows. No more calendar reminders to send that onboarding email or add a new joiner to Slack
		listitem
			paragraph
				StaticText The single source of truth for your company's greatest asset – your people
	image
	heading Enterprise Level-Security on a Single Platform
	paragraph
		StaticText Secure your people data with Cercli's technical, organizational, and physical safeguards
	link GDPR compliant, url='https://app.drata.com/trust/61f4ed60-97a3-4f01-895a-6e3f656997c9'
		image GDPR compliant, url='https://www.cercli.com/assets/gdpr.svg'
	image Cercli security, url='https://www.cercli.com/_next/static/media/security.41404a34.png'
	heading About Us
	paragraph
		StaticText Our purpose is to unlock the true potential of organizations and their people
	heading Our Values
	heading Our values drive the way we hire, the way we make decisions, and the way we build
	[428] button icon We Are Owners, Not Employees, center=(960,5617), expanded=False, inner_text=We Are Owners, Not Employees
		image icon, url='https://www.cercli.com/assets/key-icon.svg'
		heading We Are Owners, Not Employees
	[458] button icon We Dream Big & Prioritize Diligently, center=(960,5729), expanded=False, inner_text=We Dream Big & Prioritize Diligently
		image icon, url='https://www.cercli.com/assets/dart-icon.svg'
		heading We Dream Big & Prioritize Diligently
	[488] button icon We Practice Empathy & Radical Transparency, center=(960,5841), expanded=False, inner_text=We Practice Empathy & Radical Transparency
		image icon, url='https://www.cercli.com/assets/heart-icon.svg'
		heading We Practice Empathy & Radical Transparency
	heading Backed by
	link Afore logo, url='https://www.afore.vc/'
		image Afore logo, url='https://www.cercli.com/_next/static/media/afore.18d1e4a3.png'
	link Cotu logo, url='https://www.cotu.vc/'
		image Cotu logo, url='https://www.cercli.com/_next/static/media/cotu.cc8108f9.svg'
	link YCombinator logo, url='https://www.ycombinator.com/'
		image YCombinator logo, url='https://www.cercli.com/_next/static/media/ycombinator.26770c7e.svg'
	contentinfo
		paragraph
			StaticText Automate
			StaticText your local and remote payroll, HRIS, expenses, onboarding and more
		image Cercli, url='https://www.cercli.com/cercli-logo-icon.svg'
		paragraph
			StaticText Get started
		link Book Demo, url='https://www.cercli.com/join'
			button Book Demo
		button Why Cercli?
		button Product
		button About Us
		link, url='https://www.linkedin.com/company/cercli/'
		link, url='https://twitter.com/cercliHQ'
		link Privacy Policy, url='https://www.cercli.com/privacy-policy'
			button Privacy Policy
		link Terms, url='https://www.cercli.com/terms'
			button Terms
		link Status, url='http://status.cercli.com/'
			button Status
		paragraph
			StaticText © 2025 Cercli · All rights reserved
	StaticText By using this website you agree with our privacy and cookies policy
	[581] button Agree, center=(1160,5916), type=button
	alert, atomic
```
</details>

**Reasoning for action:** My reasoning for this action was to gather more insight into Cercli as a company, specifically its mission and values outlined in the 'About Us' section. Clicking this tab aligns with the user's objective of exploring Cercli's offerings and understanding how the company can fulfill their business needs. This step is essential because knowing the company's mission will help the user assess whether Cercli's platform resonates with their own values and requirements.

**Action:** click(230) # Click on the 'About Us' tab to learn more about the company and its mission.

**Change Description:** The user clicked on the 'About Us' tab, which is now selected, while the previously selected 'Product' tab is now deselected, shifting the focus of the page to information regarding the company's mission and values.

**Screenshot before:****Screenshot after:**---

