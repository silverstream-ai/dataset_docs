# Task

**User Story for Joining Waitlist and Exploring Enterprise Options**

As a potential customer interested in automation solutions,
I join the waitlist for early access and learn about enterprise options,
so that I can stay informed and explore how the service may benefit my organization.

**Success definition:** Given I am on the AutoComputer website and interested in their services
When I click the 'Join Waitlist' button and submit my email address, then click the 'Enterprise' link
Then I should see a confirmation message that I am on the waitlist and then be redirected to the enterprise options page.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.autocomputer.ai/

https://www.autocomputer.ai/

**Content (before/after):** 

```
RootWebArea, focused, url='https://www.autocomputer.ai/'
	navigation
		[16] link AutoComputer Logo, center=(278,32), url='https://www.autocomputer.ai/'
			image AutoComputer Logo, url='https://www.autocomputer.ai/assets/logo-svg-BU0OnO_4.svg'
		[19] link Waitlist, center=(1568,32), url='https://www.autocomputer.ai/#waitlist'
```
<details><summary>Show more</summary>

```
		[20] link Enterprise, center=(1671,32), url='https://www.autocomputer.ai/#enterprise'
	main
		heading Easily automate any workflow on your computer
		paragraph
			StaticText Zero-configuration automation with AI that uses your computer like you, while keeping you in charge.
		[30] button Join Waitlist, center=(866,466)
		[31] button Schedule a Call, center=(1041,466)
		image Backed by Y Combinator, url='https://www.autocomputer.ai/assets/yc-white-NOIgUgLa.svg'
		heading See It in Action
		paragraph
			StaticText Watch our desktop AI automate an example workflow of checking and transferring cost data that one of our users had to do manually multiple times a week.
		Iframe
			RootWebArea AutoComputer (YC F24) — Demo - YouTube, url='https://www.youtube.com/embed/tcFpwrvB7FE?enablejsapi=1&controls=0'
				[a28] link Photo image of AutoComputer, center=(569,980)
				[a36] link AutoComputer (YC F24) — Demo, center=(945,981), url='https://www.youtube.com/watch?v=tcFpwrvB7FE'
				[a57] button Copy link, center=(1330,978)
					image
				[a89] button Play, center=(959,1185)
					image
				generic, atomic
				[a297] link Watch on www.youtube.com, center=(1310,1393), url='https://www.youtube.com/watch?v=tcFpwrvB7FE'
					image
		button
			image
		heading Why AutoComputer over other automation solutions?
		image
		heading Desktop First Automation
		paragraph
			StaticText No new app to sign up to, no new platform to onboard onto, ready to automate any task like how you do it on your computer.
		image
		heading Zero Configuration
		paragraph
			StaticText No API Integrations, no data hydration and migration, no recording. Just a provide a prompt for AutoComputer to start automating next steps for you.
		image
		heading Full Visibility and Control
		paragraph
			StaticText For those tasks that are important but you want to still automate, be able to see, stop and correct any granular step while the automation runs.
		image
		heading Works Across Apps and Files
		paragraph
			StaticText Can do the workflow across any set of apps, custom software files, and websites, since it uses your computer like you do.
		heading Enterprise
		paragraph
			StaticText Get in touch with us to discover how AutoComputer can enable you to automate workflows for your business.
		button Schedule a Call
		heading Join the Waitlist
		paragraph
			StaticText We're currently focusing on enterprise and business customers, but you can sign up for our waitlist to get early access to AutoComputer on MacOS and Windows.
		textbox you@email.com
		button Sign Up
	contentinfo
		paragraph
			StaticText ©
			StaticText 2025
			StaticText AutoComputer, Inc. All rights reserved.
	region Notifications (F8)
		list
```
</details>



```
RootWebArea, focused, url='https://www.autocomputer.ai/'
	navigation
		[16] link AutoComputer Logo, center=(278,1984), url='https://www.autocomputer.ai/'
			image AutoComputer Logo, url='https://www.autocomputer.ai/assets/logo-svg-BU0OnO_4.svg'
		[19] link Waitlist, center=(1568,1984), url='https://www.autocomputer.ai/#waitlist'
```
<details><summary>Show more</summary>

```
		[20] link Enterprise, center=(1671,1984), url='https://www.autocomputer.ai/#enterprise'
	main
		heading Easily automate any workflow on your computer
		paragraph
			StaticText Zero-configuration automation with AI that uses your computer like you, while keeping you in charge.
		button Join Waitlist, focused
		button Schedule a Call
		image Backed by Y Combinator, url='https://www.autocomputer.ai/assets/yc-white-NOIgUgLa.svg'
		heading See It in Action
		paragraph
			StaticText Watch our desktop AI automate an example workflow of checking and transferring cost data that one of our users had to do manually multiple times a week.
		Iframe
			RootWebArea AutoComputer (YC F24) — Demo - YouTube, url='https://www.youtube.com/embed/tcFpwrvB7FE?enablejsapi=1&controls=0'
				[a28] link Photo image of AutoComputer, center=(569,980)
				[a36] link AutoComputer (YC F24) — Demo, center=(945,981), url='https://www.youtube.com/watch?v=tcFpwrvB7FE'
				[a57] button Copy link, center=(1330,978)
					image
				[a89] button Play, center=(959,1185)
					image
				generic, atomic
				[a297] link Watch on www.youtube.com, center=(1310,1393), url='https://www.youtube.com/watch?v=tcFpwrvB7FE'
					image
		button
			image
		heading Why AutoComputer over other automation solutions?
		image
		heading Desktop First Automation
		paragraph
			StaticText No new app to sign up to, no new platform to onboard onto, ready to automate any task like how you do it on your computer.
		image
		heading Zero Configuration
		paragraph
			StaticText No API Integrations, no data hydration and migration, no recording. Just a provide a prompt for AutoComputer to start automating next steps for you.
		image
		heading Full Visibility and Control
		paragraph
			StaticText For those tasks that are important but you want to still automate, be able to see, stop and correct any granular step while the automation runs.
		image
		heading Works Across Apps and Files
		paragraph
			StaticText Can do the workflow across any set of apps, custom software files, and websites, since it uses your computer like you do.
		heading Enterprise
		paragraph
			StaticText Get in touch with us to discover how AutoComputer can enable you to automate workflows for your business.
		[77] button Schedule a Call, center=(960,2339)
		heading Join the Waitlist
		paragraph
			StaticText We're currently focusing on enterprise and business customers, but you can sign up for our waitlist to get early access to AutoComputer on MacOS and Windows.
		[89] textbox you@email.com, center=(960,2745), contenteditable=True
		[91] button Sign Up, center=(1087,2745)
	contentinfo
		paragraph
			StaticText ©
			StaticText 2025
			StaticText AutoComputer, Inc. All rights reserved.
	region Notifications (F8)
		list
```
</details>

**Reasoning for action:** I clicked the 'Join Waitlist' button because this action directly addresses the user's goal of expressing interest in AutoComputer's services. By clicking this button, I am likely to be taken to a form where I can submit my email address, which is essential for joining the waitlist and staying informed about future offerings related to the automation solutions they provide.

**Action:** click(30) # Click on the 'Join Waitlist' button to explore that section.

**Change Description:** After clicking the 'Join Waitlist' button, the browser's main content focused on the waitlist section, highlighting the text box to input an email for signing up and placing emphasis on the join waitlist message, while retaining other sections of information.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://www.autocomputer.ai/

https://www.autocomputer.ai/

**Content (before/after):** 

```
RootWebArea, focused, url='https://www.autocomputer.ai/'
	navigation
		[16] link AutoComputer Logo, center=(278,1984), url='https://www.autocomputer.ai/'
			image AutoComputer Logo, url='https://www.autocomputer.ai/assets/logo-svg-BU0OnO_4.svg'
		[19] link Waitlist, center=(1568,1984), url='https://www.autocomputer.ai/#waitlist'
```
<details><summary>Show more</summary>

```
		[20] link Enterprise, center=(1671,1984), url='https://www.autocomputer.ai/#enterprise'
	main
		heading Easily automate any workflow on your computer
		paragraph
			StaticText Zero-configuration automation with AI that uses your computer like you, while keeping you in charge.
		button Join Waitlist, focused
		button Schedule a Call
		image Backed by Y Combinator, url='https://www.autocomputer.ai/assets/yc-white-NOIgUgLa.svg'
		heading See It in Action
		paragraph
			StaticText Watch our desktop AI automate an example workflow of checking and transferring cost data that one of our users had to do manually multiple times a week.
		Iframe
			RootWebArea AutoComputer (YC F24) — Demo - YouTube, url='https://www.youtube.com/embed/tcFpwrvB7FE?enablejsapi=1&controls=0'
				[a28] link Photo image of AutoComputer, center=(569,980)
				[a36] link AutoComputer (YC F24) — Demo, center=(945,981), url='https://www.youtube.com/watch?v=tcFpwrvB7FE'
				[a57] button Copy link, center=(1330,978)
					image
				[a89] button Play, center=(959,1185)
					image
				generic, atomic
				[a297] link Watch on www.youtube.com, center=(1310,1393), url='https://www.youtube.com/watch?v=tcFpwrvB7FE'
					image
		button
			image
		heading Why AutoComputer over other automation solutions?
		image
		heading Desktop First Automation
		paragraph
			StaticText No new app to sign up to, no new platform to onboard onto, ready to automate any task like how you do it on your computer.
		image
		heading Zero Configuration
		paragraph
			StaticText No API Integrations, no data hydration and migration, no recording. Just a provide a prompt for AutoComputer to start automating next steps for you.
		image
		heading Full Visibility and Control
		paragraph
			StaticText For those tasks that are important but you want to still automate, be able to see, stop and correct any granular step while the automation runs.
		image
		heading Works Across Apps and Files
		paragraph
			StaticText Can do the workflow across any set of apps, custom software files, and websites, since it uses your computer like you do.
		heading Enterprise
		paragraph
			StaticText Get in touch with us to discover how AutoComputer can enable you to automate workflows for your business.
		[77] button Schedule a Call, center=(960,2339)
		heading Join the Waitlist
		paragraph
			StaticText We're currently focusing on enterprise and business customers, but you can sign up for our waitlist to get early access to AutoComputer on MacOS and Windows.
		[89] textbox you@email.com, center=(960,2745), contenteditable=True
		[91] button Sign Up, center=(1087,2745)
	contentinfo
		paragraph
			StaticText ©
			StaticText 2025
			StaticText AutoComputer, Inc. All rights reserved.
	region Notifications (F8)
		list
```
</details>



```
RootWebArea, focused, url='https://www.autocomputer.ai/'
	navigation
		[16] link AutoComputer Logo, center=(278,1968), url='https://www.autocomputer.ai/'
			image AutoComputer Logo, url='https://www.autocomputer.ai/assets/logo-svg-BU0OnO_4.svg'
		[19] link Waitlist, center=(1568,1968), url='https://www.autocomputer.ai/#waitlist'
```
<details><summary>Show more</summary>

```
		[20] link Enterprise, center=(1671,1968), url='https://www.autocomputer.ai/#enterprise'
	main
		heading Easily automate any workflow on your computer
		paragraph
			StaticText Zero-configuration automation with AI that uses your computer like you, while keeping you in charge.
		button Join Waitlist
		button Schedule a Call
		image Backed by Y Combinator, url='https://www.autocomputer.ai/assets/yc-white-NOIgUgLa.svg'
		heading See It in Action
		paragraph
			StaticText Watch our desktop AI automate an example workflow of checking and transferring cost data that one of our users had to do manually multiple times a week.
		Iframe
			RootWebArea AutoComputer (YC F24) — Demo - YouTube, url='https://www.youtube.com/embed/tcFpwrvB7FE?enablejsapi=1&controls=0'
				[a28] link Photo image of AutoComputer, center=(569,980)
				[a36] link AutoComputer (YC F24) — Demo, center=(945,981), url='https://www.youtube.com/watch?v=tcFpwrvB7FE'
				[a57] button Copy link, center=(1330,978)
					image
				[a89] button Play, center=(959,1185)
					image
				generic, atomic
				[a297] link Watch on www.youtube.com, center=(1310,1393), url='https://www.youtube.com/watch?v=tcFpwrvB7FE'
					image
		button
			image
		heading Why AutoComputer over other automation solutions?
		image
		heading Desktop First Automation
		paragraph
			StaticText No new app to sign up to, no new platform to onboard onto, ready to automate any task like how you do it on your computer.
		image
		heading Zero Configuration
		paragraph
			StaticText No API Integrations, no data hydration and migration, no recording. Just a provide a prompt for AutoComputer to start automating next steps for you.
		image
		heading Full Visibility and Control
		paragraph
			StaticText For those tasks that are important but you want to still automate, be able to see, stop and correct any granular step while the automation runs.
		image
		heading Works Across Apps and Files
		paragraph
			StaticText Can do the workflow across any set of apps, custom software files, and websites, since it uses your computer like you do.
		heading Enterprise
		paragraph
			StaticText Get in touch with us to discover how AutoComputer can enable you to automate workflows for your business.
		[77] button Schedule a Call, center=(960,2339)
		heading Join the Waitlist
		paragraph
			StaticText We're currently focusing on enterprise and business customers, but you can sign up for our waitlist to get early access to AutoComputer on MacOS and Windows.
		StaticText You are #572 in line!
	contentinfo
		paragraph
			StaticText ©
			StaticText 2025
			StaticText AutoComputer, Inc. All rights reserved.
	region Notifications (F8)
		list
```
</details>

**Reasoning for action:** I first filled in the email textbox with a sample email address because providing an email is a prerequisite for joining the waitlist. Once the email was entered, I proceeded to click the 'Sign Up' button to submit the form. This action is crucial as it directly contributes to achieving my goal of joining the waitlist, thereby notifying me of updates and allowing me to explore the services offered by AutoComputer.

**Action:** fill(89, 'test@example.com') # Fill in the email textbox with a sample email address
click(91) # Click on the 'Sign Up' button to submit the email.

**Change Description:** The email textbox was filled with 'test@example.com' and the 'Sign Up' button was clicked, which resulted in a confirmation message indicating the user is now #572 in line for the waitlist, reflecting a successful submission of the email.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://www.autocomputer.ai/

https://www.autocomputer.ai/

**Content (before/after):** 

```
RootWebArea, focused, url='https://www.autocomputer.ai/'
	navigation
		[16] link AutoComputer Logo, center=(278,1968), url='https://www.autocomputer.ai/'
			image AutoComputer Logo, url='https://www.autocomputer.ai/assets/logo-svg-BU0OnO_4.svg'
		[19] link Waitlist, center=(1568,1968), url='https://www.autocomputer.ai/#waitlist'
```
<details><summary>Show more</summary>

```
		[20] link Enterprise, center=(1671,1968), url='https://www.autocomputer.ai/#enterprise'
	main
		heading Easily automate any workflow on your computer
		paragraph
			StaticText Zero-configuration automation with AI that uses your computer like you, while keeping you in charge.
		button Join Waitlist
		button Schedule a Call
		image Backed by Y Combinator, url='https://www.autocomputer.ai/assets/yc-white-NOIgUgLa.svg'
		heading See It in Action
		paragraph
			StaticText Watch our desktop AI automate an example workflow of checking and transferring cost data that one of our users had to do manually multiple times a week.
		Iframe
			RootWebArea AutoComputer (YC F24) — Demo - YouTube, url='https://www.youtube.com/embed/tcFpwrvB7FE?enablejsapi=1&controls=0'
				[a28] link Photo image of AutoComputer, center=(569,980)
				[a36] link AutoComputer (YC F24) — Demo, center=(945,981), url='https://www.youtube.com/watch?v=tcFpwrvB7FE'
				[a57] button Copy link, center=(1330,978)
					image
				[a89] button Play, center=(959,1185)
					image
				generic, atomic
				[a297] link Watch on www.youtube.com, center=(1310,1393), url='https://www.youtube.com/watch?v=tcFpwrvB7FE'
					image
		button
			image
		heading Why AutoComputer over other automation solutions?
		image
		heading Desktop First Automation
		paragraph
			StaticText No new app to sign up to, no new platform to onboard onto, ready to automate any task like how you do it on your computer.
		image
		heading Zero Configuration
		paragraph
			StaticText No API Integrations, no data hydration and migration, no recording. Just a provide a prompt for AutoComputer to start automating next steps for you.
		image
		heading Full Visibility and Control
		paragraph
			StaticText For those tasks that are important but you want to still automate, be able to see, stop and correct any granular step while the automation runs.
		image
		heading Works Across Apps and Files
		paragraph
			StaticText Can do the workflow across any set of apps, custom software files, and websites, since it uses your computer like you do.
		heading Enterprise
		paragraph
			StaticText Get in touch with us to discover how AutoComputer can enable you to automate workflows for your business.
		[77] button Schedule a Call, center=(960,2339)
		heading Join the Waitlist
		paragraph
			StaticText We're currently focusing on enterprise and business customers, but you can sign up for our waitlist to get early access to AutoComputer on MacOS and Windows.
		StaticText You are #572 in line!
	contentinfo
		paragraph
			StaticText ©
			StaticText 2025
			StaticText AutoComputer, Inc. All rights reserved.
	region Notifications (F8)
		list
```
</details>



```
RootWebArea, focused, url='https://www.autocomputer.ai/'
	navigation
		[16] link AutoComputer Logo, center=(278,1968), url='https://www.autocomputer.ai/'
			image AutoComputer Logo, url='https://www.autocomputer.ai/assets/logo-svg-BU0OnO_4.svg'
		[19] link Waitlist, center=(1568,1968), url='https://www.autocomputer.ai/#waitlist'
```
<details><summary>Show more</summary>

```
		[20] link Enterprise, center=(1671,1968), focused, url='https://www.autocomputer.ai/#enterprise'
	main
		heading Easily automate any workflow on your computer
		paragraph
			StaticText Zero-configuration automation with AI that uses your computer like you, while keeping you in charge.
		button Join Waitlist
		button Schedule a Call
		image Backed by Y Combinator, url='https://www.autocomputer.ai/assets/yc-white-NOIgUgLa.svg'
		heading See It in Action
		paragraph
			StaticText Watch our desktop AI automate an example workflow of checking and transferring cost data that one of our users had to do manually multiple times a week.
		Iframe
			RootWebArea AutoComputer (YC F24) — Demo - YouTube, url='https://www.youtube.com/embed/tcFpwrvB7FE?enablejsapi=1&controls=0'
				[a28] link Photo image of AutoComputer, center=(569,980)
				[a36] link AutoComputer (YC F24) — Demo, center=(945,981), url='https://www.youtube.com/watch?v=tcFpwrvB7FE'
				[a57] button Copy link, center=(1330,978)
					image
				[a89] button Play, center=(959,1185)
					image
				generic, atomic
				[a297] link Watch on www.youtube.com, center=(1310,1393), url='https://www.youtube.com/watch?v=tcFpwrvB7FE'
					image
		button
			image
		heading Why AutoComputer over other automation solutions?
		image
		heading Desktop First Automation
		paragraph
			StaticText No new app to sign up to, no new platform to onboard onto, ready to automate any task like how you do it on your computer.
		image
		heading Zero Configuration
		paragraph
			StaticText No API Integrations, no data hydration and migration, no recording. Just a provide a prompt for AutoComputer to start automating next steps for you.
		image
		heading Full Visibility and Control
		paragraph
			StaticText For those tasks that are important but you want to still automate, be able to see, stop and correct any granular step while the automation runs.
		image
		heading Works Across Apps and Files
		paragraph
			StaticText Can do the workflow across any set of apps, custom software files, and websites, since it uses your computer like you do.
		heading Enterprise
		paragraph
			StaticText Get in touch with us to discover how AutoComputer can enable you to automate workflows for your business.
		[77] button Schedule a Call, center=(960,2339)
		heading Join the Waitlist
		paragraph
			StaticText We're currently focusing on enterprise and business customers, but you can sign up for our waitlist to get early access to AutoComputer on MacOS and Windows.
		StaticText You are #572 in line!
	contentinfo
		paragraph
			StaticText ©
			StaticText 2025
			StaticText AutoComputer, Inc. All rights reserved.
	region Notifications (F8)
		list
```
</details>

**Reasoning for action:** I identified that clicking the 'Enterprise' link will transition me to the section of the website that provides detailed information regarding enterprise solutions. This step is crucial for fulfilling the user story since it aligns with the user's goal of learning about the services available for enterprises. It allows me to explore how AutoComputer’s offerings could benefit an organization, thus progressing towards the completion of the task.

**Action:** click(20) # Click on the 'Enterprise' link to explore enterprise options.

**Change Description:** After clicking the 'Enterprise' link, the focus shifted to that link, indicating that the user can now explore enterprise options on the AutoComputer website.

**Screenshot before:****Screenshot after:**---

