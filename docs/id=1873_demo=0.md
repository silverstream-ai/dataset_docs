# Task

**User Story for Mergent Signup Process**

As a new user interested in Mergent's services,,
I sign up for a free account easily,,
so that I can start exploring the features of the platform without any commitments.

**Success definition:** Given I am on the Mergent homepage and I want to get started with a free trial.
When I click on the 'GET STARTED FREE' button and submit my email address
Then I receive a confirmation message stating that a login link has been sent to my provided email.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://mergent.co/

https://app.mergent.co/login

**Content (before/after):** 

```
RootWebArea Mergent - Serverless Crons & Background Jobs, focused, url='https://mergent.co/'
	paragraph
		StaticText Mergent's APIs surpassed
		StaticText 99.995%
		StaticText uptime for the second year in a row.
```
<details><summary>Show more</summary>

```
		[46] link Learn more →, center=(1248,24), url='https://blog.mergent.co/mergents-apis-surpass-99995-uptime-for-the-second-year'
	banner
		[51] link, center=(372,96), url='https://mergent.co/'
			image
		[54] link Overview, center=(465,96), url='https://mergent.co/'
		[55] link Features, center=(560,96), url='https://mergent.co/#features'
		[56] link Pricing, center=(647,96), url='https://mergent.co/#pricing'
		[57] link Docs, center=(720,96), url='https://docs.mergent.co/'
		[58] link Changelog, center=(808,96), url='https://blog.mergent.co/tag/changelog'
		[59] link Contact, center=(906,96), url='mailto:hello@mergent.co'
		[63] link, center=(1285,98), url='https://github.com/mergentlabs'
			image
		[66] link, center=(1345,98), url='https://twitter.com/mergentlabs'
			image
		[68] link Log In, center=(1416,98), url='https://app.mergent.co/login'
		[70] link SIGN UP, center=(1523,98), url='https://app.mergent.co/login'
	main
		[74] link All systems operational, center=(468,1022), url='https://status.mergent.co/'
			image
		heading Background jobs & crons made easy.
		paragraph
			StaticText Mergent is a fully-managed task queue for applications in any language.
		paragraph
			StaticText Scale to billions of tasks with
			StaticText zero infrastructure
			StaticText .
		[86] link GET STARTED FREE, center=(443,540), url='https://app.mergent.co/login'
		[87] link EXPLORE DOCS, center=(627,540), url='https://docs.mergent.co/'
		code
			StaticText {
			StaticText "id"
			StaticText :
			StaticText "ed2754ab-d3be-4742-b0d2-1755765ea914"
			StaticText ,
			StaticText "status"
			StaticText :
			StaticText "queued"
			StaticText ,
			StaticText "scheduled_for"
			StaticText :
			StaticText "
			StaticText 2025-01-14T17:52:34.375Z
			StaticText "
			StaticText ,
			StaticText "request"
			StaticText :
			StaticText {
			StaticText "url"
			StaticText :
			StaticText "https://example.com/webhooks/mergent"
			StaticText ,
			StaticText "body"
			StaticText :
			StaticText "Hello, Mergent!"
			StaticText }
			StaticText }
		image
		image
		image
		image
		image
		image
		image
		image
		image
		image
		image
		image
		image
		image
		image
		image
		StaticText TRUSTED BY
		image
		image
		StaticText Scheduled & recurring tasks
		StaticText Schedule tasks to run later, either once or on a recurring basis (cron & RRULE).
		image
		StaticText HTTP webhook targets
		StaticText Receive an HTTP webhook on any server when your task is ready to be invoked.
		image
		StaticText Better debugging tools
		StaticText Monitor, change, and reschedule your tasks from Mergent's dashboard or API.
		image
		StaticText Scalable & fully managed
		StaticText Schedule tasks without ever having to manage or monitor a Redis instance.
		StaticText PRICING
		StaticText Simple. Transparent.
		StaticText Free, Forever!
		StaticText Try it out! Integrate fast and explore features.
		StaticText No credit card required.
		StaticText $0
		StaticText /mo
		list
			listitem
				ListMarker -
				StaticText Includes
				StaticText 1,000
				StaticText invocations per month
			listitem
				ListMarker -
				StaticText Unlimited Crons
			listitem
				ListMarker -
				StaticText 7-day history
			listitem
				ListMarker -
				StaticText Future scheduling
			listitem
				ListMarker -
				StaticText Automatic retries
		link GET STARTED FOR FREE, url='https://app.mergent.co/login'
		StaticText Standard
		StaticText All of Mergent's features. Pay for what you use.
		StaticText Starting at
		StaticText $20
		StaticText /mo
		list
			listitem
				ListMarker -
				StaticText Includes
				StaticText 10,000
				StaticText invocations per month
			listitem
				ListMarker -
				StaticText As low as
				StaticText $0.000003
				StaticText per invocation
			listitem
				ListMarker -
				StaticText Up to
				StaticText 10 billion
				StaticText invocations per month
			listitem
				ListMarker -
				StaticText Unlimited Crons
			listitem
				ListMarker -
				StaticText 30-day history
			listitem
				ListMarker -
				StaticText Future scheduling
			listitem
				ListMarker -
				StaticText Automatic retries
		link GET STARTED FOR FREE, url='https://app.mergent.co/login'
		StaticText Enterprise
		StaticText Customized pricing for the most demanding workloads.
		StaticText Starting at
		StaticText $2k
		StaticText /mo
		list
			listitem
				ListMarker -
				StaticText Priority support
			listitem
				ListMarker -
				StaticText Flexible data retention
			listitem
				ListMarker -
				StaticText Stringent data protection
			listitem
				ListMarker -
				StaticText Single Sign-On
			listitem
				ListMarker -
				StaticText 99.995% SLA
			listitem
				ListMarker -
				StaticText SOC 2 and ISO 27001 reports
		link CONTACT US, url='mailto:hello@mergent.co'
		StaticText Ready to get started?
		StaticText Explore Mergent with your first 1,000 invocations/mo
		StaticText free, forever
		StaticText .
		link GET STARTED FREE, url='https://app.mergent.co/login'
		link EXPLORE DOCS, url='https://docs.mergent.co/'
	contentinfo
		link All systems operational, url='https://status.mergent.co/'
			image
		StaticText © 2021-2024 Mergent Labs Inc.
		StaticText Made with 💻 all over the world.
		link Blog, url='https://blog.mergent.co/'
		StaticText |
		link Changelog, url='https://blog.mergent.co/tag/changelog'
		StaticText |
		link Contact, url='mailto:hello@mergent.co'
		StaticText |
		link Terms, url='https://mergent.co/terms'
		StaticText |
		link Privacy, url='https://mergent.co/privacy'
		StaticText |
		link, url='https://github.com/mergentlabs'
			image
		StaticText |
		link, url='https://twitter.com/mergentlabs'
			image
	alert, atomic
```
</details>



```
RootWebArea Mergent, focused, url='https://app.mergent.co/login'
	main
		image
		heading Welcome to Mergent
		[36] textbox hello@mergent.co, center=(960,552), contenteditable=True, type=email
```
<details><summary>Show more</summary>

```
		[42] button Continue with Email, center=(960,600), type=submit
		StaticText By clicking "Continue with Email" above, you agree to Mergent's
		[45] link Terms of Service, center=(935,668), url='https://mergent.co/terms'
		StaticText and
		[46] link Privacy Policy, center=(1051,668), url='https://mergent.co/privacy'
		StaticText .
```
</details>

**Reasoning for action:** By clicking on the 'GET STARTED FREE' button, I am effectively initiating the sign-up process for a free account. This action is crucial for the user to access the necessary form to provide their email address, which is a key step in fulfilling their objective of signing up easily and starting to explore the features of the platform.

**Action:** click(86) # Click on the 'GET STARTED FREE' button to explore the signup process.

**Change Description:** After clicking the 'GET STARTED FREE' button, the browser navigated to the Mergent login page, which now features a welcome heading, an email input textbox, and a 'Continue with Email' button, indicating the beginning of the signup process.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://app.mergent.co/login

https://app.mergent.co/login

**Content (before/after):** 

```
RootWebArea Mergent, focused, url='https://app.mergent.co/login'
	main
		image
		heading Welcome to Mergent
		[36] textbox hello@mergent.co, center=(960,552), contenteditable=True, type=email
```
<details><summary>Show more</summary>

```
		[42] button Continue with Email, center=(960,600), type=submit
		StaticText By clicking "Continue with Email" above, you agree to Mergent's
		[45] link Terms of Service, center=(935,668), url='https://mergent.co/terms'
		StaticText and
		[46] link Privacy Policy, center=(1051,668), url='https://mergent.co/privacy'
		StaticText .
```
</details>



```
RootWebArea Mergent, focused, url='https://app.mergent.co/login'
	main
		image
		heading Welcome to Mergent
		[36] textbox hello@mergent.co value='test@example.com', center=(960,552), contenteditable=True, focused, type=email
```
<details><summary>Show more</summary>

```
		[42] button Continue with Email, center=(960,600), type=submit
		StaticText By clicking "Continue with Email" above, you agree to Mergent's
		[45] link Terms of Service, center=(935,668), url='https://mergent.co/terms'
		StaticText and
		[46] link Privacy Policy, center=(1051,668), url='https://mergent.co/privacy'
		StaticText .
```
</details>

**Reasoning for action:** By entering a sample email address into the textbox, I am moving closer to completing the sign-up process for a free account. This action is necessary because the next step involves clicking the 'Continue with Email' button, which requires the presence of an email in the textbox to proceed. Filling in the email is crucial for allowing the system to recognize the user's intent to create an account and send a confirmation message.

**Action:** fill(36, 'test@example.com') # Fill in the email textbox with a sample email address.

**Change Description:** The email textbox now contains the value 'test@example.com' and remains focused, indicating that the user has filled in their email address.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://app.mergent.co/login

https://app.mergent.co/login

**Content (before/after):** 

```
RootWebArea Mergent, focused, url='https://app.mergent.co/login'
	main
		image
		heading Welcome to Mergent
		[36] textbox hello@mergent.co value='test@example.com', center=(960,552), contenteditable=True, focused, type=email
```
<details><summary>Show more</summary>

```
		[42] button Continue with Email, center=(960,600), type=submit
		StaticText By clicking "Continue with Email" above, you agree to Mergent's
		[45] link Terms of Service, center=(935,668), url='https://mergent.co/terms'
		StaticText and
		[46] link Privacy Policy, center=(1051,668), url='https://mergent.co/privacy'
		StaticText .
```
</details>



```
RootWebArea Mergent, focused, url='https://app.mergent.co/login'
	main
		image
		StaticText A login link has been sent to
		StaticText test@example.com
```
<details><summary>Show more</summary>

```
		StaticText .
		separator, orientation='horizontal'
		[57] link Open Gmail, center=(960,616), url='https://mail.google.com/'
			image
```
</details>

**Reasoning for action:** The 'Continue with Email' button is essential to advance from the initial input stage where I've entered my email address. By clicking this button, I'm effectively sending my provided email to the Mergent platform, which triggers the process of creating an account and leads to receiving the confirmation message about the login link being sent. This action directly addresses the user story's objective of signing up easily without commitments.

**Action:** click(42) # Click on the 'Continue with Email' button to proceed with the signup process.

**Change Description:** After clicking the 'Continue with Email' button, the initial prompt for email submission was replaced with a confirmation message indicating that a login link has been sent to 'test@example.com', along with a new link to open Gmail.

**Screenshot before:****Screenshot after:**---

