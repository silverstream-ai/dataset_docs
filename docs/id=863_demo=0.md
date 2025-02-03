# Task

**User Signup for Launch Notification**

As a prospective user interested in Metal's services,,
I sign up for the launch notification waitlist,
so that I can be informed about the launch and updates regarding the platform.

**Success definition:** Given I am on the Metal homepage and see the sign-up form for launch notifications
When I fill in my email address and click the 'Sign Up' button
Then I should see a message confirming my sign-up for notifications with the text 'Thank you! You will be notified about our launch soon.'

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.metal.so/

https://www.metal.so/

**Content (before/after):** 

```
RootWebArea Metal | Startup Fundraising Platform, focused, url='https://www.metal.so/'
	image, url='https://cdn.prod.website-files.com/65cc79e68fc10dc2aae44b87/671a629df3cb2da15434aec0_metal%20purple%20logo.png'
	heading Launching Soon! Sign up for our waitlist.
	form Launch Notify Emails
		[28] textbox Enter your email, center=(910,486), contenteditable=True, required, type=email
```
<details><summary>Show more</summary>

```
		[29] button Sign Up, center=(1074,486), contenteditable=True, type=submit
	paragraph
		StaticText ©
		StaticText 2024 Metal Inc.
```
</details>



```
RootWebArea Metal | Startup Fundraising Platform, focused, url='https://www.metal.so/'
	alert Please fill out this field., atomic
	image, url='https://cdn.prod.website-files.com/65cc79e68fc10dc2aae44b87/671a629df3cb2da15434aec0_metal%20purple%20logo.png'
	heading Launching Soon! Sign up for our waitlist.
	form Launch Notify Emails
```
<details><summary>Show more</summary>

```
		[28] textbox Enter your email, center=(910,486), contenteditable=True, focused, required, type=email
		[29] button Sign Up, center=(1074,486), contenteditable=True, type=submit
	paragraph
		StaticText ©
		StaticText 2024 Metal Inc.
```
</details>

**Reasoning for action:** By clicking the 'Sign Up' button, I initiate the action needed to register the user's email for the launch notifications. This action directly aligns with the user story, as it allows the user to express interest in Metal's services and ensures they can receive updates about the platform's launch. Following this step, I expect to see a confirmation message that would validate the successful sign-up and fulfill the acceptance test criteria.

**Action:** click('29') # Click on the Sign Up button to explore any potential responses or actions.

**Change Description:** After clicking the Sign Up button, an alert was triggered stating 'Please fill out this field,' indicating that the email textbox was not filled out. The textbox remains focused and retains the 'required' status.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://www.metal.so/

https://www.metal.so/

**Content (before/after):** 

```
RootWebArea Metal | Startup Fundraising Platform, focused, url='https://www.metal.so/'
	alert Please fill out this field., atomic
	image, url='https://cdn.prod.website-files.com/65cc79e68fc10dc2aae44b87/671a629df3cb2da15434aec0_metal%20purple%20logo.png'
	heading Launching Soon! Sign up for our waitlist.
	form Launch Notify Emails
```
<details><summary>Show more</summary>

```
		[28] textbox Enter your email, center=(910,486), contenteditable=True, focused, required, type=email
		[29] button Sign Up, center=(1074,486), contenteditable=True, type=submit
	paragraph
		StaticText ©
		StaticText 2024 Metal Inc.
```
</details>



```
RootWebArea Metal | Startup Fundraising Platform, focused, url='https://www.metal.so/'
	image, url='https://cdn.prod.website-files.com/65cc79e68fc10dc2aae44b87/671a629df3cb2da15434aec0_metal%20purple%20logo.png'
	heading Launching Soon! Sign up for our waitlist.
	form Launch Notify Emails
		[28] textbox Enter your email value='example@example.com', center=(910,486), contenteditable=True, focused, required, type=email
```
<details><summary>Show more</summary>

```
		[29] button Sign Up, center=(1074,486), contenteditable=True, type=submit
	paragraph
		StaticText ©
		StaticText 2024 Metal Inc.
```
</details>

**Reasoning for action:** The email textbox is focused and required for submission, so entering a valid email address is the next step towards signing up for the launch notification waitlist. This action directly fulfills part of the User Story by providing the necessary information needed to complete the sign-up process. By populating the textbox with a sample email address, I am preparing to proceed to the next action of submitting the form.

**Action:** fill('28', 'example@example.com') # Fill the email textbox with a sample email address.

**Change Description:** The email textbox was filled with the sample email address 'example@example.com', updating its value from empty to the entered email while maintaining its focus and other properties.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://www.metal.so/

https://www.metal.so/

**Content (before/after):** 

```
RootWebArea Metal | Startup Fundraising Platform, focused, url='https://www.metal.so/'
	image, url='https://cdn.prod.website-files.com/65cc79e68fc10dc2aae44b87/671a629df3cb2da15434aec0_metal%20purple%20logo.png'
	heading Launching Soon! Sign up for our waitlist.
	form Launch Notify Emails
		[28] textbox Enter your email value='example@example.com', center=(910,486), contenteditable=True, focused, required, type=email
```
<details><summary>Show more</summary>

```
		[29] button Sign Up, center=(1074,486), contenteditable=True, type=submit
	paragraph
		StaticText ©
		StaticText 2024 Metal Inc.
```
</details>



```
RootWebArea Metal | Startup Fundraising Platform, focused, url='https://www.metal.so/'
	image, url='https://cdn.prod.website-files.com/65cc79e68fc10dc2aae44b87/671a629df3cb2da15434aec0_metal%20purple%20logo.png'
	heading Launching Soon! Sign up for our waitlist.
	region Launch Notify Emails success, focused
		StaticText Thank you! You will be notified about our launch soon.
```
<details><summary>Show more</summary>

```
	paragraph
		StaticText ©
		StaticText 2024 Metal Inc.
```
</details>

**Reasoning for action:** I clicked the 'Sign Up' button because this action is necessary to complete the user's task of signing up for launch notifications. By clicking the button, I am submitting the email address that was already entered in the textbox, which will trigger the confirmation message indicating that the user has successfully signed up. This step is crucial as it directly aligns with the user story and success criteria provided.

**Action:** click('29') # Click on the Sign Up button to submit the email and explore the response.

**Change Description:** After clicking the 'Sign Up' button, the form state changed to indicate a successful submission with a new message stating 'Thank you! You will be notified about our launch soon.', and the region previously labeled as 'Launch Notify Emails' transformed to reflect this success.

**Screenshot before:****Screenshot after:**---

