# Task

**User Registration Story**

As a new user,
I sign up for the Capi Money service,
so that I can start making international payments efficiently.

**Success definition:** Given I am on the Capi Money sign-up page and have already accepted the cookies consent
When I fill in the required fields with my personal information and click the Continue button
Then I should receive an alert notifying me of any unfilled required fields, and all correctly filled fields should remain unchanged.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://capimoney.com/

https://app.capimoney.com/sign-up?locale=en

**Content (before/after):** 

```
RootWebArea Capi Money, focused, url='https://capimoney.com/'
	dialog Cookie Consent Prompt, modal=False
		StaticText We use essential cookies to make our site work. With your consent, we may also use non-essential cookies to improve user experience, personalize advertisements, and analyze web traffic. For these reasons, we may share your site usage data with our advertising and analytics partners. By clicking “Accept,” you agree to our website's cookie use as described in our
		[75] link Cookie Policy, center=(350,1019)
		StaticText . You can change your cookie settings at any time by clicking “
```
<details><summary>Show more</summary>

```
		[76] link Preferences, center=(747,1019)
		StaticText .”
		[78] button Preferences, center=(1285,998)
		[79] button Decline, center=(1452,998)
		[80] button Accept, center=(1618,998)
	banner
		image Capi Money Logo, url='https://capimoney.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fcombined_light_bkg.f1133c63.png&w=1920&q=75'
		[85] link Become an FX partner, center=(1334,52), url='https://capimoney.com/fx'
		[86] link Log in, center=(1470,52), url='https://app.capimoney.com/sign-in'
		[87] button EN, center=(1546,52), expanded=False, hasPopup='menu', type=button
			image
	heading Reliable international payments for importers in Africa
	StaticText Pay your international suppliers in EUR, USD or GBP on-time, every time.
	[95] link Sign up and get access, center=(960,528), url='https://app.capimoney.com/sign-up?locale=en'
		button Sign up and get access
	image
	strong
		StaticText Reliability
	StaticText Always available foreign currency at competitive rates
	image
	strong
		StaticText Speed
	StaticText Instant rates and payment settlements in 24hr
	image
	strong
		StaticText Control
	StaticText Track payment progress on your dashboard in real-time
	image
	strong
		StaticText Security
	StaticText A regulated service with banks in top-tier jurisdictions
	StaticText Backed by
	image logo, url='https://capimoney.com/_next/image?url=https%3A%2F%2Fcdn.sanity.io%2Fimages%2Fy6kgvqnx%2Fproduction%2F5c3e42dfa7cfb19f42b3cc18c3ccfae7e8273482-520x60.png%3Fw%3D200%26sat%3D-100%26auto%3Dformat%26dpr%3D2&w=256&q=75'
	image logo, url='https://capimoney.com/_next/image?url=https%3A%2F%2Fcdn.sanity.io%2Fimages%2Fy6kgvqnx%2Fproduction%2F2e8ae34ebc92402e6be176bb28dd706dbc379c9a-464x138.png%3Fw%3D200%26sat%3D-100%26auto%3Dformat%26dpr%3D2&w=256&q=75'
	image logo, url='https://capimoney.com/_next/image?url=https%3A%2F%2Fcdn.sanity.io%2Fimages%2Fy6kgvqnx%2Fproduction%2Fb45d8fafc09c2c5a1fa01adbefcf7119ca48a30d-3208x640.png%3Fw%3D200%26sat%3D-100%26auto%3Dformat%26dpr%3D2&w=256&q=75'
	image logo, url='https://capimoney.com/_next/image?url=https%3A%2F%2Fcdn.sanity.io%2Fimages%2Fy6kgvqnx%2Fproduction%2F3f0f824251c8d71d5511e6d3a59e3c2613464f88-1000x138.png%3Fw%3D200%26sat%3D-100%26auto%3Dformat%26dpr%3D2&w=256&q=75'
	image logo, url='https://capimoney.com/_next/image?url=https%3A%2F%2Fcdn.sanity.io%2Fimages%2Fy6kgvqnx%2Fproduction%2F977a33199c252bf431b5bc541a33777dadb5e637-1396x384.png%3Fw%3D200%26sat%3D-100%26auto%3Dformat%26dpr%3D2&w=256&q=75'
	heading Focus on your business without the hassle of paying overseas invoices
	StaticText Businesses across Africa are waiting weeks for local banks to process international invoices. Capi Money provides reliable foreign currency at affordable prices.
	image demo, url='https://capimoney.com/_next/image?url=https%3A%2F%2Fcdn.sanity.io%2Fimages%2Fy6kgvqnx%2Fproduction%2Fa8f0b87d0ccd4117577d5652b9674afd343a7638-754x835.png%3Frect%3D0%2C68%2C754%2C754%26w%3D720%26h%3D720%26dpr%3D2&w=750&q=75'
	image
	strong
		StaticText Move faster
	StaticText Always have access to USD, EUR or GBP for your invoices
	image
	strong
		StaticText Increase turnover
	StaticText Pay your international invoices faster
	image
	strong
		StaticText Build trust
	StaticText Give reliable payment timelines to your suppliers
	StaticText Built by the team behind
	image logo, url='https://capimoney.com/_next/image?url=https%3A%2F%2Fcdn.sanity.io%2Fimages%2Fy6kgvqnx%2Fproduction%2F26ab4a7b40adacb4bac505752b3b4941eb79aedf-500x238.png%3Fw%3D200%26sat%3D-100%26auto%3Dformat%26dpr%3D2&w=256&q=75'
	image logo, url='https://capimoney.com/_next/image?url=https%3A%2F%2Fcdn.sanity.io%2Fimages%2Fy6kgvqnx%2Fproduction%2F93244469fde90069a2efd67fbd74868c5ae7f862-480x117.png%3Fw%3D200%26sat%3D-100%26auto%3Dformat%26dpr%3D2&w=256&q=75'
	image logo, url='https://capimoney.com/_next/image?url=https%3A%2F%2Fcdn.sanity.io%2Fimages%2Fy6kgvqnx%2Fproduction%2Fd30eb71f06010ba0fc9b783e07e98704be60d65c-500x110.png%3Fw%3D200%26sat%3D-100%26auto%3Dformat%26dpr%3D2&w=256&q=75'
	image logo, url='https://capimoney.com/_next/image?url=https%3A%2F%2Fcdn.sanity.io%2Fimages%2Fy6kgvqnx%2Fproduction%2F42c7bd3f7d6cac243d66fcaf9d1c55cd0214905e-500x105.png%3Fw%3D200%26sat%3D-100%26auto%3Dformat%26dpr%3D2&w=256&q=75'
	image logo, url='https://capimoney.com/_next/image?url=https%3A%2F%2Fcdn.sanity.io%2Fimages%2Fy6kgvqnx%2Fproduction%2Fcf512b9468fd765aecb423970d50241b2d212561-500x122.png%3Fw%3D200%26sat%3D-100%26auto%3Dformat%26dpr%3D2&w=256&q=75'
	image logo, url='https://capimoney.com/_next/image?url=https%3A%2F%2Fcdn.sanity.io%2Fimages%2Fy6kgvqnx%2Fproduction%2F9ba6cda592ae5a4fa2dc5ba12a0de618dc664bb2-1600x407.png%3Fw%3D200%26sat%3D-100%26auto%3Dformat%26dpr%3D2&w=256&q=75'
	heading Seamless experience with enterprise-grade security
	StaticText Stop queuing at the bank with piles of signed paper. International invoice payments should be as easy as sending a mobile money transfer to your friend, while ensuring that you are in control of your money throughout the process.
	link Sign up and get access, url='https://app.capimoney.com/sign-up?locale=en'
		button Sign up and get access
	image
	StaticText Sign up and do your first transfer on the same day
	image
	StaticText We hold your money with licensed financial institutions
	image
	StaticText See real-time updates on your transfer
	heading Unlock your business's growth
	StaticText Sign up and get access to reliable, affordable, international payments.
	link Sign up and get access, url='https://app.capimoney.com/?locale=en'
		button Sign up and get access
	image Capi Money Logo, url='https://capimoney.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fcombined_dark_bkg.084cada7.png&w=256&q=75'
	StaticText Legals
	link Cookie Policy, url='https://app.termly.io/document/cookie-policy/7167a4cf-fa0a-4407-afff-3733b0b661f6'
	link Privacy Policy, url='https://capimoney.com/privacy-policy'
	link Terms and Conditions, url='https://capimoney.com/terms'
	link Prohibited industries and countries, url='https://capimoney.com/prohibited-industries-and-countries'
	StaticText Resources
	link Contact, url='mailto:support@capimoney.com'
	link Become an FX partner, url='https://capimoney.com/fx'
	link Careers, url='https://jobs.ashbyhq.com/capimoney'
	link Switch to English, url='https://capimoney.com/'
	link Passer au Français, url='https://capimoney.com/fr'
	StaticText ©
	StaticText 2025
	StaticText Capi Money, Inc
	alert, atomic
```
</details>



```
RootWebArea Capi Money | Reliable international payments for importers in Africa, focused, url='https://app.capimoney.com/sign-up?locale=en'
	main
		main
			image Capi Logo, url='https://app.capimoney.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fcombined_light_bkg.f1133c63.png&w=256&q=75'
			heading Create your account
```
<details><summary>Show more</summary>

```
			paragraph
				StaticText Welcome! Please fill in the details to get started.
			LabelText
				StaticText First name
			[95] textbox First name, center=(876,365), contenteditable=True, required, type=text
			LabelText
				StaticText Last name
			[101] textbox Last name, center=(1044,365), contenteditable=True, required, type=text
			LabelText
				StaticText Email address
			[108] textbox Email address, center=(960,453), contenteditable=True, required, type=text
			LabelText
				StaticText Phone number
			[116] button US, center=(833,541)
				image
			paragraph
				StaticText +
				StaticText 1
			[121] textbox Phone number, center=(1002,541), contenteditable=True, required, type=tel
			LabelText
				StaticText Password
			[129] textbox Password, center=(960,630), contenteditable=True, required, type=password
			[130] button Show password, center=(1096,630)
				image
			[136] button Continue, center=(960,696)
				image
			StaticText Already have an account?
			[142] link Sign in, center=(1057,772), url='https://app.capimoney.com/sign-in#/?locale=en'
	region Notifications (F8)
		list
	alert, atomic
```
</details>

**Reasoning for action:** I selected the 'Sign up and get access' button since this is the crucial first step for the user. By clicking this button, I advance to the next page in the sign-up process, which is necessary for entering the required personal information, thus moving closer to fulfilling the task of signing up for Capi Money.

**Action:** click(95) # Click on the 'Sign up and get access' button to explore the sign-up process.

**Change Description:** The browser transitioned to the sign-up page for Capi Money after clicking the 'Sign up and get access' button, displaying a form for users to create an account with fields for personal details such as first name, last name, email address, phone number, and password.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://app.capimoney.com/sign-up?locale=en

https://app.capimoney.com/sign-up?locale=en

**Content (before/after):** 

```
RootWebArea Capi Money | Reliable international payments for importers in Africa, focused, url='https://app.capimoney.com/sign-up?locale=en'
	main
		main
			image Capi Logo, url='https://app.capimoney.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fcombined_light_bkg.f1133c63.png&w=256&q=75'
			heading Create your account
```
<details><summary>Show more</summary>

```
			paragraph
				StaticText Welcome! Please fill in the details to get started.
			LabelText
				StaticText First name
			[95] textbox First name, center=(876,365), contenteditable=True, required, type=text
			LabelText
				StaticText Last name
			[101] textbox Last name, center=(1044,365), contenteditable=True, required, type=text
			LabelText
				StaticText Email address
			[108] textbox Email address, center=(960,453), contenteditable=True, required, type=text
			LabelText
				StaticText Phone number
			[116] button US, center=(833,541)
				image
			paragraph
				StaticText +
				StaticText 1
			[121] textbox Phone number, center=(1002,541), contenteditable=True, required, type=tel
			LabelText
				StaticText Password
			[129] textbox Password, center=(960,630), contenteditable=True, required, type=password
			[130] button Show password, center=(1096,630)
				image
			[136] button Continue, center=(960,696)
				image
			StaticText Already have an account?
			[142] link Sign in, center=(1057,772), url='https://app.capimoney.com/sign-in#/?locale=en'
	region Notifications (F8)
		list
	alert, atomic
```
</details>



```
RootWebArea Capi Money | Reliable international payments for importers in Africa, focused, url='https://app.capimoney.com/sign-up?locale=en'
	alert Please fill out this field., atomic
	main
		main
			image Capi Logo, url='https://app.capimoney.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fcombined_light_bkg.f1133c63.png&w=256&q=75'
```
<details><summary>Show more</summary>

```
			heading Create your account
			paragraph
				StaticText Welcome! Please fill in the details to get started.
			LabelText
				StaticText First name
			[95] textbox First name value='John', center=(876,365), contenteditable=True, required, type=text
			LabelText
				StaticText Last name
			[101] textbox Last name, center=(1044,365), contenteditable=True, focused, required, type=text
			LabelText
				StaticText Email address
			[108] textbox Email address value='Doejohn.doe@example.com', center=(960,453), contenteditable=True, required, type=text
			LabelText
				StaticText Phone number
			[116] button US, center=(833,541)
				image
			paragraph
				StaticText +
				StaticText 1
			[121] textbox Phone number value='(123) 456-7890', center=(1002,541), contenteditable=True, required, type=tel
			LabelText
				StaticText Password
			[129] textbox Password value='•••••••••••••••••', center=(960,630), contenteditable=True, required, type=password
			[130] button Show password, center=(1096,630)
				image
			paragraph
				image
				StaticText Your password meets all the necessary requirements.
			[136] button Continue, center=(960,752)
				image
			StaticText Already have an account?
			[142] link Sign in, center=(1057,828), url='https://app.capimoney.com/sign-in#/?locale=en'
	region Notifications (F8)
		list
	alert, atomic
```
</details>

**Reasoning for action:** I reasoned that by filling in all the required fields (first name, last name, email address, phone number, and password) with valid information and then clicking the 'Continue' button, I could initiate the sign-up process. According to the user's story and success criteria, this action should allow me to check if there were any unfilled required fields. If there were issues with the submission, I would want to see alerts indicating what needed to be corrected, while correctly filled fields should remain unchanged. Thus, this action progresses the task by moving from data entry to form submission, necessary to verify the completeness of the input data.

**Action:** fill(95, 'John') # Fill in the first name
fill(101, 'Doe') # Fill in the last name
fill(108, 'john.doe@example.com') # Fill in the email address
fill(121, '1234567890') # Fill in the phone number
fill(129, 'SecurePassword123') # Fill in the password
click(136) # Click on the 'Continue' button to proceed with the sign-up.

**Change Description:** The text fields for First name, Last name, Email address, Phone number, and Password have been filled with user inputs, and the Continue button was clicked. An alert message indicates that a required field remains unfilled.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://app.capimoney.com/sign-up?locale=en

https://app.capimoney.com/sign-up?locale=en

**Content (before/after):** 

```
RootWebArea Capi Money | Reliable international payments for importers in Africa, focused, url='https://app.capimoney.com/sign-up?locale=en'
	alert Please fill out this field., atomic
	main
		main
			image Capi Logo, url='https://app.capimoney.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fcombined_light_bkg.f1133c63.png&w=256&q=75'
```
<details><summary>Show more</summary>

```
			heading Create your account
			paragraph
				StaticText Welcome! Please fill in the details to get started.
			LabelText
				StaticText First name
			[95] textbox First name value='John', center=(876,365), contenteditable=True, required, type=text
			LabelText
				StaticText Last name
			[101] textbox Last name, center=(1044,365), contenteditable=True, focused, required, type=text
			LabelText
				StaticText Email address
			[108] textbox Email address value='Doejohn.doe@example.com', center=(960,453), contenteditable=True, required, type=text
			LabelText
				StaticText Phone number
			[116] button US, center=(833,541)
				image
			paragraph
				StaticText +
				StaticText 1
			[121] textbox Phone number value='(123) 456-7890', center=(1002,541), contenteditable=True, required, type=tel
			LabelText
				StaticText Password
			[129] textbox Password value='•••••••••••••••••', center=(960,630), contenteditable=True, required, type=password
			[130] button Show password, center=(1096,630)
				image
			paragraph
				image
				StaticText Your password meets all the necessary requirements.
			[136] button Continue, center=(960,752)
				image
			StaticText Already have an account?
			[142] link Sign in, center=(1057,828), url='https://app.capimoney.com/sign-in#/?locale=en'
	region Notifications (F8)
		list
	alert, atomic
```
</details>



```
RootWebArea Capi Money | Reliable international payments for importers in Africa, focused, url='https://app.capimoney.com/sign-up?locale=en'
	main
		main
			image Capi Logo, url='https://app.capimoney.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fcombined_light_bkg.f1133c63.png&w=256&q=75'
			heading Create your account
```
<details><summary>Show more</summary>

```
			paragraph
				StaticText Welcome! Please fill in the details to get started.
			LabelText
				StaticText First name
			[95] textbox First name value='John', center=(876,365), contenteditable=True, required, type=text
			LabelText
				StaticText Last name
			[101] textbox Last name value='Smith', center=(1044,365), contenteditable=True, focused, required, type=text
			LabelText
				StaticText Email address
			[108] textbox Email address value='Doejohn.doe@example.com', center=(960,453), contenteditable=True, required, type=text
			LabelText
				StaticText Phone number
			[116] button US, center=(833,541)
				image
			paragraph
				StaticText +
				StaticText 1
			[121] textbox Phone number value='(123) 456-7890', center=(1002,541), contenteditable=True, required, type=tel
			LabelText
				StaticText Password
			[129] textbox Password value='•••••••••••••••••', center=(960,630), contenteditable=True, required, type=password
			[130] button Show password, center=(1096,630)
				image
			paragraph
				image
				StaticText Your password meets all the necessary requirements.
			[136] button Continue, center=(960,752)
				image
			StaticText Already have an account?
			[142] link Sign in, center=(1057,828), url='https://app.capimoney.com/sign-in#/?locale=en'
	region Notifications (F8)
		list
	alert, atomic
```
</details>

**Reasoning for action:** My reasoning for this action is to ensure that the required field for the last name is completed. The user story mentions that all required fields must be filled out in order to proceed with the sign-up process. By filling in this field, I'm taking a step towards meeting the acceptance criteria, as it should eliminate one potential error when the user clicks the 'Continue' button, thus getting closer to successfully signing up for the Capi Money service.

**Action:** fill(101, 'Smith') # Fill in the last name with 'Smith'.

**Change Description:** The last name textbox was updated from a blank value to 'Smith', reflecting the user's input in the registration form.

**Screenshot before:****Screenshot after:**---

