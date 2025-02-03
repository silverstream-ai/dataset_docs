# Task

**Book a Demo for Abel Police**

As a police officer,
I book a demo of the Abel software,
so that I can see how it can help reduce paperwork and increase effective patrol hours.

**Success definition:** Given I am on the Abel Police website
When I click on the 'Book a demo' button, fill in my details, and submit the form
Then I should see a confirmation message indicating that my demo booking was successful and the button displays 'Thank you'.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://abelpolice.com/

https://abelpolice.com/

**Content (before/after):** 

```
RootWebArea Abel Police, focused, url='https://abelpolice.com/'
	image, url='https://framerusercontent.com/images/ADIJ16RgnI5NcolNJl649f4qu44.jpeg'
	image, url='https://framerusercontent.com/images/tYUgVHQFVYhayDM4F4a1ejQo9yo.png'
	paragraph
		StaticText Turn body camera footage into completed police reports
```
<details><summary>Show more</summary>

```
	[58] paragraph, center=(960,789), inner_text=Book a demo
	paragraph
		StaticText Backed by
	paragraph
		StaticText Y Combinator
	[67] link Work at Abel, center=(1805,48), url='https://abelpolice.com/careers'
		paragraph
	paragraph
		StaticText Patrol officers are spending too much time on paperwork
	paragraph
		StaticText 1
		StaticText /
		StaticText 3
	paragraph
		StaticText The share of a patrol officer's
	paragraph
		StaticText shift spent on paperwork
	paragraph
		StaticText 5
		StaticText 0
		StaticText %
	paragraph
		StaticText Increase in effective police hours
	paragraph
		StaticText if paperwork went to zero
	image, url='https://framerusercontent.com/images/T8zBqMAoq3gfVnFuxRqo4HxA7U8.jpeg?scale-down-to=2048'
	paragraph
		StaticText Abel works with your current systems to make patrol more efficient
	paragraph
		StaticText Comprehend the action
	paragraph
		StaticText Abel uses advanced video interpretation and transcription to understand body camera footage, then turns this into useful data and narratives for patrol officers.
	paragraph
		StaticText Get started instantly
	paragraph
		StaticText No data migration, no complicated installation. Simply provide access to your evidence locker and install our browser extension.
	paragraph
		StaticText Face sheets and narratives
	paragraph
		StaticText Clicking through forms is time consuming. Abel takes over and inserts incident, location, and subject information for patrol officers, and then injects a narrative.
	paragraph
		StaticText Built securely
	paragraph
		StaticText Hosted on AWS GovCloud, your agency’s data is always encrypted and CJIS compliant.
	image, url='https://framerusercontent.com/images/Mk976GgFBCH7K5HCmetc9Wraljs.jpg?scale-down-to=2048'
	paragraph
		StaticText Your department should be Abel
	paragraph
		StaticText Abel is nearing the end of Phase 1 development and we are now accepting applications from new agencies.
	paragraph
	paragraph
		StaticText Built in San Francisco.
	paragraph
	paragraph
		StaticText 2024 © DARIUS LABS INC
```
</details>



```
RootWebArea Abel Police, focused, url='https://abelpolice.com/'
	image, url='https://framerusercontent.com/images/ADIJ16RgnI5NcolNJl649f4qu44.jpeg'
	image, url='https://framerusercontent.com/images/tYUgVHQFVYhayDM4F4a1ejQo9yo.png'
	paragraph
		StaticText Turn body camera footage into completed police reports
```
<details><summary>Show more</summary>

```
	generic Book a demo, focused
		paragraph
	paragraph
		StaticText Backed by
	paragraph
		StaticText Y Combinator
	link Work at Abel, url='https://abelpolice.com/careers'
		paragraph
	paragraph
		StaticText Patrol officers are spending too much time on paperwork
	paragraph
		StaticText 1
		StaticText /
		StaticText 3
	paragraph
		StaticText The share of a patrol officer's
	paragraph
		StaticText shift spent on paperwork
	paragraph
		StaticText 5
		StaticText 0
		StaticText %
	paragraph
		StaticText Increase in effective police hours
	paragraph
		StaticText if paperwork went to zero
	image, url='https://framerusercontent.com/images/T8zBqMAoq3gfVnFuxRqo4HxA7U8.jpeg?scale-down-to=2048'
	paragraph
		StaticText Abel works with your current systems to make patrol more efficient
	paragraph
		StaticText Comprehend the action
	paragraph
		StaticText Abel uses advanced video interpretation and transcription to understand body camera footage, then turns this into useful data and narratives for patrol officers.
	paragraph
		StaticText Get started instantly
	paragraph
		StaticText No data migration, no complicated installation. Simply provide access to your evidence locker and install our browser extension.
	paragraph
		StaticText Face sheets and narratives
	paragraph
		StaticText Clicking through forms is time consuming. Abel takes over and inserts incident, location, and subject information for patrol officers, and then injects a narrative.
	paragraph
		StaticText Built securely
	paragraph
		StaticText Hosted on AWS GovCloud, your agency’s data is always encrypted and CJIS compliant.
	image, url='https://framerusercontent.com/images/Mk976GgFBCH7K5HCmetc9Wraljs.jpg?scale-down-to=2048'
	paragraph
		StaticText Your department should be Abel
	paragraph
		StaticText Abel is nearing the end of Phase 1 development and we are now accepting applications from new agencies.
	paragraph
	paragraph
		StaticText Built in San Francisco.
	paragraph
	paragraph
		StaticText 2024 © DARIUS LABS INC
	paragraph
		StaticText Book a demo
	LabelText
		[185] textbox, center=(960,403), contenteditable=True, required, type=text
	LabelText
		[188] textbox, center=(960,471), contenteditable=True, required, type=email
	LabelText
		[191] textbox, center=(960,538), contenteditable=True, type=text
	LabelText
		[194] combobox value='Select your role', center=(951,606), contenteditable=True, expanded=False, hasPopup='menu', inner_text=Select your role
Officer
Command Staff
Admin/Support, required
			option Select your role, disabled=True
			option Officer, selected=False
			option Command Staff, selected=False
			option Admin/Support, selected=False
	[200] button Submit, center=(756,674), type=submit
		paragraph
```
</details>

**Reasoning for action:** By clicking on the 'Book a demo' button, I initiate the process of scheduling a demonstration. This is necessary because it allows me to access the form where I can provide my details, ultimately leading to the confirmation message that indicates the demo has been successfully booked. This step directly aligns with the user's objective of seeing how Abel software can improve their work efficiency.

**Action:** click(58) # Click on the 'Book a demo' button.

**Change Description:** After clicking the 'Book a demo' button, the browser introduced a form for users to fill out, including textboxes for personal information, a dropdown to select a role, and a submit button, while the button itself changed to a generic type to reflect its current state.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://abelpolice.com/

https://abelpolice.com/

**Content (before/after):** 

```
RootWebArea Abel Police, focused, url='https://abelpolice.com/'
	image, url='https://framerusercontent.com/images/ADIJ16RgnI5NcolNJl649f4qu44.jpeg'
	image, url='https://framerusercontent.com/images/tYUgVHQFVYhayDM4F4a1ejQo9yo.png'
	paragraph
		StaticText Turn body camera footage into completed police reports
```
<details><summary>Show more</summary>

```
	generic Book a demo, focused
		paragraph
	paragraph
		StaticText Backed by
	paragraph
		StaticText Y Combinator
	link Work at Abel, url='https://abelpolice.com/careers'
		paragraph
	paragraph
		StaticText Patrol officers are spending too much time on paperwork
	paragraph
		StaticText 1
		StaticText /
		StaticText 3
	paragraph
		StaticText The share of a patrol officer's
	paragraph
		StaticText shift spent on paperwork
	paragraph
		StaticText 5
		StaticText 0
		StaticText %
	paragraph
		StaticText Increase in effective police hours
	paragraph
		StaticText if paperwork went to zero
	image, url='https://framerusercontent.com/images/T8zBqMAoq3gfVnFuxRqo4HxA7U8.jpeg?scale-down-to=2048'
	paragraph
		StaticText Abel works with your current systems to make patrol more efficient
	paragraph
		StaticText Comprehend the action
	paragraph
		StaticText Abel uses advanced video interpretation and transcription to understand body camera footage, then turns this into useful data and narratives for patrol officers.
	paragraph
		StaticText Get started instantly
	paragraph
		StaticText No data migration, no complicated installation. Simply provide access to your evidence locker and install our browser extension.
	paragraph
		StaticText Face sheets and narratives
	paragraph
		StaticText Clicking through forms is time consuming. Abel takes over and inserts incident, location, and subject information for patrol officers, and then injects a narrative.
	paragraph
		StaticText Built securely
	paragraph
		StaticText Hosted on AWS GovCloud, your agency’s data is always encrypted and CJIS compliant.
	image, url='https://framerusercontent.com/images/Mk976GgFBCH7K5HCmetc9Wraljs.jpg?scale-down-to=2048'
	paragraph
		StaticText Your department should be Abel
	paragraph
		StaticText Abel is nearing the end of Phase 1 development and we are now accepting applications from new agencies.
	paragraph
	paragraph
		StaticText Built in San Francisco.
	paragraph
	paragraph
		StaticText 2024 © DARIUS LABS INC
	paragraph
		StaticText Book a demo
	LabelText
		[185] textbox, center=(960,403), contenteditable=True, required, type=text
	LabelText
		[188] textbox, center=(960,471), contenteditable=True, required, type=email
	LabelText
		[191] textbox, center=(960,538), contenteditable=True, type=text
	LabelText
		[194] combobox value='Select your role', center=(951,606), contenteditable=True, expanded=False, hasPopup='menu', inner_text=Select your role
Officer
Command Staff
Admin/Support, required
			option Select your role, disabled=True
			option Officer, selected=False
			option Command Staff, selected=False
			option Admin/Support, selected=False
	[200] button Submit, center=(756,674), type=submit
		paragraph
```
</details>



```
RootWebArea Abel Police, focused, url='https://abelpolice.com/'
	image, url='https://framerusercontent.com/images/ADIJ16RgnI5NcolNJl649f4qu44.jpeg'
	image, url='https://framerusercontent.com/images/tYUgVHQFVYhayDM4F4a1ejQo9yo.png'
	paragraph
		StaticText Turn body camera footage into completed police reports
```
<details><summary>Show more</summary>

```
	paragraph
	paragraph
		StaticText Backed by
	paragraph
		StaticText Y Combinator
	link Work at Abel, url='https://abelpolice.com/careers'
		paragraph
	paragraph
		StaticText Patrol officers are spending too much time on paperwork
	paragraph
		StaticText 1
		StaticText /
		StaticText 3
	paragraph
		StaticText The share of a patrol officer's
	paragraph
		StaticText shift spent on paperwork
	paragraph
		StaticText 5
		StaticText 0
		StaticText %
	paragraph
		StaticText Increase in effective police hours
	paragraph
		StaticText if paperwork went to zero
	image, url='https://framerusercontent.com/images/T8zBqMAoq3gfVnFuxRqo4HxA7U8.jpeg?scale-down-to=2048'
	paragraph
		StaticText Abel works with your current systems to make patrol more efficient
	paragraph
		StaticText Comprehend the action
	paragraph
		StaticText Abel uses advanced video interpretation and transcription to understand body camera footage, then turns this into useful data and narratives for patrol officers.
	paragraph
		StaticText Get started instantly
	paragraph
		StaticText No data migration, no complicated installation. Simply provide access to your evidence locker and install our browser extension.
	paragraph
		StaticText Face sheets and narratives
	paragraph
		StaticText Clicking through forms is time consuming. Abel takes over and inserts incident, location, and subject information for patrol officers, and then injects a narrative.
	paragraph
		StaticText Built securely
	paragraph
		StaticText Hosted on AWS GovCloud, your agency’s data is always encrypted and CJIS compliant.
	image, url='https://framerusercontent.com/images/Mk976GgFBCH7K5HCmetc9Wraljs.jpg?scale-down-to=2048'
	paragraph
		StaticText Your department should be Abel
	paragraph
		StaticText Abel is nearing the end of Phase 1 development and we are now accepting applications from new agencies.
	paragraph
	paragraph
		StaticText Built in San Francisco.
	paragraph
	paragraph
		StaticText 2024 © DARIUS LABS INC
	paragraph
		StaticText Book a demo
	LabelText
		[185] textbox value='John Doe', center=(960,403), contenteditable=True, required, type=text
	LabelText
		[188] textbox value='john.doe@example.com', center=(960,471), contenteditable=True, required, type=email
	LabelText
		[191] textbox value='Example Agency', center=(960,538), contenteditable=True, focused, type=text
	LabelText
		[194] combobox value='Officer', center=(951,606), contenteditable=True, expanded=False, hasPopup='menu', inner_text=Select your role
Officer
Command Staff
Admin/Support, required
			option Select your role, disabled=True
			option Officer, selected=True
			option Command Staff, selected=False
			option Admin/Support, selected=False
	[200] button Submit, center=(756,674), type=submit
		paragraph
```
</details>

**Reasoning for action:** I completed this action to fill out the required fields in the demo booking form. By entering 'John Doe' in the Full Name field, 'john.doe@example.com' in the Email field, and 'Example Agency' in the Agency Name field, I ensured that the form contains valid information needed to reserve a demo. Selecting 'Officer' from the role dropdown further specifies my role to the company, which can assist them in tailoring the demo to my specific needs. Filling out these fields moves me closer to the goal of submitting the form for the demo booking.

**Action:** fill(185, 'John Doe') # Fill in the Full Name field
fill(188, 'john.doe@example.com') # Fill in the Email field
fill(191, 'Example Agency') # Fill in the Agency Name field
select_option(194, ['Officer']) # Select 'Officer' from the role dropdown.

**Change Description:** The Full Name, Email, and Agency Name fields were filled with 'John Doe', 'john.doe@example.com', and 'Example Agency' respectively. Additionally, the 'Officer' option was selected from the role dropdown, showing these inputs are now ready for submission.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://abelpolice.com/

https://abelpolice.com/

**Content (before/after):** 

```
RootWebArea Abel Police, focused, url='https://abelpolice.com/'
	image, url='https://framerusercontent.com/images/ADIJ16RgnI5NcolNJl649f4qu44.jpeg'
	image, url='https://framerusercontent.com/images/tYUgVHQFVYhayDM4F4a1ejQo9yo.png'
	paragraph
		StaticText Turn body camera footage into completed police reports
```
<details><summary>Show more</summary>

```
	paragraph
	paragraph
		StaticText Backed by
	paragraph
		StaticText Y Combinator
	link Work at Abel, url='https://abelpolice.com/careers'
		paragraph
	paragraph
		StaticText Patrol officers are spending too much time on paperwork
	paragraph
		StaticText 1
		StaticText /
		StaticText 3
	paragraph
		StaticText The share of a patrol officer's
	paragraph
		StaticText shift spent on paperwork
	paragraph
		StaticText 5
		StaticText 0
		StaticText %
	paragraph
		StaticText Increase in effective police hours
	paragraph
		StaticText if paperwork went to zero
	image, url='https://framerusercontent.com/images/T8zBqMAoq3gfVnFuxRqo4HxA7U8.jpeg?scale-down-to=2048'
	paragraph
		StaticText Abel works with your current systems to make patrol more efficient
	paragraph
		StaticText Comprehend the action
	paragraph
		StaticText Abel uses advanced video interpretation and transcription to understand body camera footage, then turns this into useful data and narratives for patrol officers.
	paragraph
		StaticText Get started instantly
	paragraph
		StaticText No data migration, no complicated installation. Simply provide access to your evidence locker and install our browser extension.
	paragraph
		StaticText Face sheets and narratives
	paragraph
		StaticText Clicking through forms is time consuming. Abel takes over and inserts incident, location, and subject information for patrol officers, and then injects a narrative.
	paragraph
		StaticText Built securely
	paragraph
		StaticText Hosted on AWS GovCloud, your agency’s data is always encrypted and CJIS compliant.
	image, url='https://framerusercontent.com/images/Mk976GgFBCH7K5HCmetc9Wraljs.jpg?scale-down-to=2048'
	paragraph
		StaticText Your department should be Abel
	paragraph
		StaticText Abel is nearing the end of Phase 1 development and we are now accepting applications from new agencies.
	paragraph
	paragraph
		StaticText Built in San Francisco.
	paragraph
	paragraph
		StaticText 2024 © DARIUS LABS INC
	paragraph
		StaticText Book a demo
	LabelText
		[185] textbox value='John Doe', center=(960,403), contenteditable=True, required, type=text
	LabelText
		[188] textbox value='john.doe@example.com', center=(960,471), contenteditable=True, required, type=email
	LabelText
		[191] textbox value='Example Agency', center=(960,538), contenteditable=True, focused, type=text
	LabelText
		[194] combobox value='Officer', center=(951,606), contenteditable=True, expanded=False, hasPopup='menu', inner_text=Select your role
Officer
Command Staff
Admin/Support, required
			option Select your role, disabled=True
			option Officer, selected=True
			option Command Staff, selected=False
			option Admin/Support, selected=False
	[200] button Submit, center=(756,674), type=submit
		paragraph
```
</details>



```
RootWebArea Abel Police, focused, url='https://abelpolice.com/'
	image, url='https://framerusercontent.com/images/ADIJ16RgnI5NcolNJl649f4qu44.jpeg'
	image, url='https://framerusercontent.com/images/tYUgVHQFVYhayDM4F4a1ejQo9yo.png'
	paragraph
		StaticText Turn body camera footage into completed police reports
```
<details><summary>Show more</summary>

```
	paragraph
	paragraph
		StaticText Backed by
	paragraph
		StaticText Y Combinator
	link Work at Abel, url='https://abelpolice.com/careers'
		paragraph
	paragraph
		StaticText Patrol officers are spending too much time on paperwork
	paragraph
		StaticText 1
		StaticText /
		StaticText 3
	paragraph
		StaticText The share of a patrol officer's
	paragraph
		StaticText shift spent on paperwork
	paragraph
		StaticText 5
		StaticText 0
		StaticText %
	paragraph
		StaticText Increase in effective police hours
	paragraph
		StaticText if paperwork went to zero
	image, url='https://framerusercontent.com/images/T8zBqMAoq3gfVnFuxRqo4HxA7U8.jpeg?scale-down-to=2048'
	paragraph
		StaticText Abel works with your current systems to make patrol more efficient
	paragraph
		StaticText Comprehend the action
	paragraph
		StaticText Abel uses advanced video interpretation and transcription to understand body camera footage, then turns this into useful data and narratives for patrol officers.
	paragraph
		StaticText Get started instantly
	paragraph
		StaticText No data migration, no complicated installation. Simply provide access to your evidence locker and install our browser extension.
	paragraph
		StaticText Face sheets and narratives
	paragraph
		StaticText Clicking through forms is time consuming. Abel takes over and inserts incident, location, and subject information for patrol officers, and then injects a narrative.
	paragraph
		StaticText Built securely
	paragraph
		StaticText Hosted on AWS GovCloud, your agency’s data is always encrypted and CJIS compliant.
	image, url='https://framerusercontent.com/images/Mk976GgFBCH7K5HCmetc9Wraljs.jpg?scale-down-to=2048'
	paragraph
		StaticText Your department should be Abel
	paragraph
		StaticText Abel is nearing the end of Phase 1 development and we are now accepting applications from new agencies.
	paragraph
	paragraph
		StaticText Built in San Francisco.
	paragraph
	paragraph
		StaticText 2024 © DARIUS LABS INC
	paragraph
		StaticText Book a demo
	LabelText
		[185] textbox value='John Doe', center=(960,403), contenteditable=True, required, type=text
	LabelText
		[188] textbox value='john.doe@example.com', center=(960,471), contenteditable=True, required, type=email
	LabelText
		[191] textbox value='Example Agency', center=(960,538), contenteditable=True, type=text
	LabelText
		[194] combobox value='Officer', center=(951,606), contenteditable=True, expanded=False, hasPopup='menu', inner_text=Select your role
Officer
Command Staff
Admin/Support, required
			option Select your role, disabled=True
			option Officer, selected=True
			option Command Staff, selected=False
			option Admin/Support, selected=False
	[200] button Thank you, center=(766,674), focused, type=submit
		paragraph
```
</details>

**Reasoning for action:** The 'Submit' button is the next logical step after filling in the required details for the demo booking. By clicking this button, I trigger the website to process the submitted information and move forward in providing confirmation of the demo booking. This action is essential as it advances towards receiving the confirmation message, which is part of the success criteria outlined by the user.

**Action:** click(200) # Click on the 'Submit' button to complete the demo booking.

**Change Description:** After clicking the 'Submit' button, the button label changed from 'Submit' to 'Thank you', indicating that the demo booking was successfully completed.

**Screenshot before:****Screenshot after:**---

