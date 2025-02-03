# Task

**User Journey to Start Exploring Tegon**

As a potential user of Tegon,
I create an account to explore the features offered,
so that I can understand how Tegon can streamline my bug tracking and management process.

**Success definition:** Given I am on the Tegon homepage and have clicked the 'Get started for free' button
When I enter my email address and click the 'Send a magic link' button to initiate the signup process
Then I should see a confirmation message that a magic link has been sent to my email address along with an option to re-enter my email.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.tegon.ai/

https://app.tegon.ai/auth

**Content (before/after):** 

```
RootWebArea, focused, url='https://www.tegon.ai/'
	banner
		[26] link logo, center=(352,32), url='https://www.tegon.ai/'
			image logo, url='https://www.tegon.ai/logo_text.svg'
		navigation
```
<details><summary>Show more</summary>

```
			[29] link Actions, center=(470,32), url='https://docs.tegon.ai/actions/overview'
			[30] link Docs, center=(554,32), url='https://docs.tegon.ai/'
			[31] link Releases, center=(643,32), url='https://github.com/tegonhq/tegon/releases'
			[32] link Our story, center=(746,32), url='https://www.tegon.ai/company'
		navigation
			[38] link 1.6k, center=(1512,28), url='https://github.com/tegonhq/tegon'
				image
				image
			[41] link Slack, center=(1576,28), url='https://github.com/tegonhq/tegon'
				image
			[45] button Toggle theme, center=(1612,28), expanded=False, hasPopup='menu', type=button
				image
				image
	main
		[52] button Introducing Actions, center=(398,134), type=button
			image
			image
		heading The dev-first issue tracking tool
		paragraph
			StaticText Open-source, customizable, and lightweight.
		[60] button Get started for free, center=(400,273), type=button
		[67] button Issue tracker, center=(366,371), type=button
			image
		[69] button Triage, center=(498,371), type=button
			image
		[71] button Actions, center=(614,371), type=button
			image
		[73] button AI, center=(715,371), type=button
			image
		image Issue tracker, url='https://www.tegon.ai/_next/image?url=%2Fhome%2FIssue%20tracker.png&w=1920&q=75'
		StaticText Backed by
		image Issue tracker, url='https://www.tegon.ai/_next/image?url=%2Fyc.png&w=128&q=75'
		heading Write, deploy and automate anything
		heading AI Bug Enricher
		paragraph
			StaticText Add context based tips on where to start, drop the barrier to resolve bugs
		image AI Bug, url='https://www.tegon.ai/_next/image?url=%2Ffeatures%2FAI_BUG.png&w=1920&q=75'
		heading Seamless PR Tracking
		paragraph
			StaticText Automatically create an issue to track a Pull Request (PR) as soon as it is assigned and linked to a Tegon issue
		image AI Bug, url='https://www.tegon.ai/_next/image?url=%2Ffeatures%2FPR.png&w=1920&q=75'
		heading Create Issues directly from Slack
		paragraph
			StaticText Effortlessly create issues from Slack and keep your conversations in sync by using 👀 emoji
		image AI Bug, url='https://www.tegon.ai/_next/image?url=%2Ffeatures%2FSlack.png&w=1920&q=75'
		heading Triage: omni-channel bug reporting system
		heading Central hub for bugs
		paragraph
			StaticText Automatically create and manage bugs from 8+ external sources (Slack, Email, Discord, Zendesk etc.) directly in Triage.
		image logo, url='https://www.tegon.ai/_next/image?url=%2Ffeatures%2Ftriage.png&w=1920&q=75'
		heading Automatic Bug Grouping
		paragraph
			StaticText Automatically categorize bugs based on labels ensuring a more organized and efficient view of the bugs.
		image logo, url='https://www.tegon.ai/_next/image?url=%2Ffeatures%2Fgrouping.png&w=1920&q=75'
		heading AI Suggestions
		paragraph
			StaticText Use AI to automatically suggest metadata in bugs and route them to appropriate destinations, streamlining the triage process.
		image logo, url='https://www.tegon.ai/_next/image?url=%2Ffeatures%2Fai-suggestions.png&w=1920&q=75'
		image
		StaticText We love opensource. Tegon is AGPL-3.0 licensed so you can view source code, contribute and self host
		link 1.6k, url='https://github.com/tegonhq/tegon'
			image
			image
		link Contribute, url='https://github.com/tegonhq/tegon'
			image
	contentinfo
		image logo, url='https://www.tegon.ai/logo_text.svg'
		link, url='https://github.com/tegonhq/tegon'
			image
		link Slack, url='https://github.com/tegonhq/tegon'
			image
		button Toggle theme, expanded=False, hasPopup='menu'
			image
			image
		heading Docs
		link Introduction, url='https://docs.tegon.ai/'
			image
		link Quick start guide, url='https://docs.tegon.ai/quickstart'
			image
		link Self hosting, url='https://docs.tegon.ai/oss/self-deployment'
			image
		heading Developers
		link Docs, url='https://docs.tegon.ai/'
			image
		link Contributing, url='https://github.com/tegonhq/tegon/blob/main/.github/CONTRIBUTING.md'
			image
		link Opensource, url='https://github.com/tegonhq/tegon/blob/main/LICENSE'
			image
		link Github, url='https://github.com/tegonhq/tegon'
			image
		paragraph
			StaticText Built by
			link Tegon, url='https://tegon.ai/'
			StaticText .
	region Notifications (F8)
		list
	alert, atomic
```
</details>



```
RootWebArea, focused, url='https://app.tegon.ai/auth'
	image logo, url='https://app.tegon.ai/logo_text.svg'
	heading Welcome
	StaticText Create an account or login
	[37] textbox Email address, center=(960,565), contenteditable=True
```
<details><summary>Show more</summary>

```
	[39] button Send a magic link, center=(960,609), type=submit
		image
	StaticText By clicking continue, you agree to our Terms of Service and Privacy Policy.
	region Notifications (F8)
		list
	alert, atomic
```
</details>

**Reasoning for action:** I identified the 'Get started for free' button as my next step to initiate the account creation process. Clicking this button is necessary for the user to access the signup interface, where they can enter their email and begin receiving further instructions. This action directly moves me closer to fulfilling the user's story of exploring Tegon's features through account creation.

**Action:** click(60) # Click on the 'Get started for free' button to explore the signup or introductory process.

**Change Description:** The browser navigated from the main page of Tegon AI to the signup page for the app after clicking the 'Get started for free' button, changing the URL to 'https://app.tegon.ai/auth', where users are prompted to create an account or log in using their email address.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://app.tegon.ai/auth

https://app.tegon.ai/auth

**Content (before/after):** 

```
RootWebArea, focused, url='https://app.tegon.ai/auth'
	image logo, url='https://app.tegon.ai/logo_text.svg'
	heading Welcome
	StaticText Create an account or login
	[37] textbox Email address, center=(960,565), contenteditable=True
```
<details><summary>Show more</summary>

```
	[39] button Send a magic link, center=(960,609), type=submit
		image
	StaticText By clicking continue, you agree to our Terms of Service and Privacy Policy.
	region Notifications (F8)
		list
	alert, atomic
```
</details>



```
RootWebArea, focused, url='https://app.tegon.ai/auth'
	image logo, url='https://app.tegon.ai/logo_text.svg'
	heading Welcome
	StaticText Create an account or login
	[37] textbox Email address value='example@example.com', center=(960,565), contenteditable=True, focused
```
<details><summary>Show more</summary>

```
	[39] button Send a magic link, center=(960,609), type=submit
		image
	StaticText By clicking continue, you agree to our Terms of Service and Privacy Policy.
	region Notifications (F8)
		list
	alert, atomic
```
</details>

**Reasoning for action:** Filling in the email textbox is a direct step to comply with the user's request of initiating the signup process. By entering 'example@example.com', I ensure that the required field is filled, which is a prerequisite for the next action of clicking the 'Send a magic link' button. This action brings me closer to achieving the user's goal of creating an account for exploring Tegon's features.

**Action:** fill(37, 'example@example.com') # Fill in the email address textbox with a sample email address.

**Change Description:** The email address textbox was filled with the value 'example@example.com', and it remained focused, indicating that the user is prepared to submit the form.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://app.tegon.ai/auth

https://app.tegon.ai/auth

**Content (before/after):** 

```
RootWebArea, focused, url='https://app.tegon.ai/auth'
	image logo, url='https://app.tegon.ai/logo_text.svg'
	heading Welcome
	StaticText Create an account or login
	[37] textbox Email address value='example@example.com', center=(960,565), contenteditable=True, focused
```
<details><summary>Show more</summary>

```
	[39] button Send a magic link, center=(960,609), type=submit
		image
	StaticText By clicking continue, you agree to our Terms of Service and Privacy Policy.
	region Notifications (F8)
		list
	alert, atomic
```
</details>



```
RootWebArea, focused, url='https://app.tegon.ai/auth'
	image logo, url='https://app.tegon.ai/logo_text.svg'
	heading We've sent you a magic link
	image
	StaticText We sent you an email which contains a magic link that will log you in to your account.
```
<details><summary>Show more</summary>

```
	[54] button Re-enter email, center=(841,639), type=button
		image
	region Notifications (F8)
		list
	alert, atomic
```
</details>

**Reasoning for action:** This action is necessary to progress in the signup process. By clicking the 'Send a magic link' button, I am ensuring that the email address I have entered gets submitted to Tegon, allowing them to send a confirmation link to the provided email. This aligns with the user's objective of creating an account to explore Tegon's features, and by doing this, I am following the user's instructions precisely to advance towards receiving the magic link confirmation.

**Action:** click(39) # Click on the 'Send a magic link' button to submit the email address.

**Change Description:** After clicking the 'Send a magic link' button, the heading changed from 'Welcome' to 'We've sent you a magic link', and a new static text was added informing the user that an email containing a magic link was sent. Additionally, a new button labeled 'Re-enter email' was introduced, while the original input fields were retained.

**Screenshot before:****Screenshot after:**---

