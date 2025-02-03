# Task

**Booking a Demo with Swift**

As a potential customer,
I book a demo appointment,
so that I can learn more about Swift's services and how they can help me.

**Success definition:** Given I am on the Swift website and I want to explore their services
When I click on the 'Book a demo' button and select a 200 PM time slot, then fill in my name
Then I should see a confirmation of my selected time slot and my name should be displayed in the 'Your name' field.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.joinswift.app/

https://cal.com/swift-finance/demo?date=2025-01-03&month=2025-01

**Content (before/after):** 

```
RootWebArea Swift, focused, url='https://www.joinswift.app/'
	main
		[29] link logo Swift, center=(960,448), inner_text=Swift, url='https://www.joinswift.app/'
			image logo, url='https://www.joinswift.app/_next/image?url=%2FLogo.png&w=96&q=75'
		heading Backed by Y Combinator.
```
<details><summary>Show more</summary>

```
		[36] link Book a demo, center=(960,572), url='https://cal.com/swift-finance/demo'
			button Book a demo
		[38] link Login, center=(960,628), url='https://accounts.joinswift.app/sign-in'
			button Login
	alert, atomic
```
</details>



```
RootWebArea Book Demo | Swift | Cal.com, focused, url='https://cal.com/swift-finance/demo?date=2025-01-03&month=2025-01'
	image
	main
		[92] switch Overlay my calendar, center=(1585,34), checked='false', type=button
		LabelText
```
<details><summary>Show more</summary>

```
			StaticText Overlay my calendar
		group
			[96] radio $Switch to monthly view, center=(1795,34), checked='true', type=button
			[100] radio $Switch to weekly view, center=(1837,34), checked='false', type=button
			[104] radio $Switch to column view, center=(1879,34), checked='false', type=button
		list
			listitem
				[114] link Swift, center=(477,292), url='https://cal.com/swift-finance?redirect=false'
					image Swift, url='https://cal.com/api/avatar/d45452d7-10cf-4715-b6f0-e895762ab8df.png'
		paragraph
			StaticText Swift
		heading Book Demo
		paragraph
			StaticText David – Co-Founder & CEO
		StaticText Requires confirmation
		StaticText 30m
		image Google Meet icon, url='https://cal.com/app-store/googlevideo/logo.webp'
		[135] paragraph, center=(536,510), inner_text=Google Meet
			StaticText Google Meet
		generic
		StaticText Select...
		[148] combobox Timezone Select, center=(491,546), autocomplete=off, contenteditable=True, expanded=False, hasPopup='menu', type=text
		[137] svg, center=(473,546)
		strong
			StaticText January
		[152] svg, center=(560,546)
		StaticText 2025
		[161] button View previous month, center=(1126,286), type=button
		[163] button View next month, center=(1162,286), type=button
		StaticText MON
		StaticText TUE
		StaticText WED
		StaticText THU
		StaticText FRI
		StaticText SAT
		StaticText SUN
		[179] button 1, center=(897,386), type=button
		[181] button 2, center=(960,386), type=button
		[183] button 3 today, center=(1024,386), inner_text=3
today, type=button
		[187] button 4, center=(1087,386), type=button
		[189] button 5, center=(1150,386), type=button
		[191] button 6, center=(771,449), type=button
		[193] button 7, center=(834,449), type=button
		[195] button 8, center=(897,449), type=button
		[197] button 9, center=(960,449), type=button
		[199] button 10, center=(1024,449), type=button
		[201] button 11, center=(1087,449), type=button
		[203] button 12, center=(1150,449), type=button
		[205] button 13, center=(771,512), type=button
		[207] button 14, center=(834,512), type=button
		[209] button 15, center=(897,512), type=button
		[211] button 16, center=(960,512), type=button
		[213] button 17, center=(1024,512), type=button
		[215] button 18, center=(1087,512), type=button
		[217] button 19, center=(1150,512), type=button
		[219] button 20, center=(771,576), type=button
		[221] button 21, center=(834,576), type=button
		[223] button 22, center=(897,576), type=button
		[225] button 23, center=(960,576), type=button
		[227] button 24, center=(1024,576), type=button
		[229] button 25, center=(1087,576), type=button
		[231] button 26, center=(1150,576), type=button
		[233] button 27, center=(771,639), type=button
		[235] button 28, center=(834,639), type=button
		[237] button 29, center=(897,639), type=button
		[239] button 30, center=(960,639), type=button
		[241] button 31, center=(1024,639), type=button
		StaticText Fri
		StaticText 03
		group
			[250] radio 12h, center=(1377,286), checked='true', type=button
			[252] radio 24h, center=(1429,286), checked='false', type=button
		[259] button 2:00pm, center=(1340,335), type=button
		[262] button 2:30pm, center=(1340,381), type=button
		[265] button 3:00pm, center=(1340,427), type=button
		[268] button 3:30pm, center=(1340,473), type=button
		[271] button 4:00pm, center=(1340,519), type=button
		[274] button 4:30pm, center=(1340,565), type=button
		[278] link Cal.com Logo, center=(960,784), url='https://go.cal.com/booking'
			image Cal.com Logo, url='https://app.cal.com/api/logo'
	alert, atomic
```
</details>

**Reasoning for action:** By clicking on the 'Book a demo' button, I navigate to the demo booking page. This is a crucial step because it brings me one step closer to scheduling a demo appointment, allowing me to explore Swift's services as per the user story requirements.

**Action:** click('36') # Click on the 'Book a demo' button to explore further.

**Change Description:** After clicking the 'Book a demo' button, the browser navigated to a booking interface on Cal.com, where the header changed to 'Book Demo | Swift | Cal.com' and new form elements for scheduling a demo appeared, including date and time selectors.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://cal.com/swift-finance/demo?date=2025-01-03&month=2025-01

https://cal.com/swift-finance/demo?date=2025-01-03&month=2025-01&slot=2025-01-03T14%3A00%3A00.000Z

**Content (before/after):** 

```
RootWebArea Book Demo | Swift | Cal.com, focused, url='https://cal.com/swift-finance/demo?date=2025-01-03&month=2025-01'
	image
	main
		[92] switch Overlay my calendar, center=(1585,34), checked='false', type=button
		LabelText
```
<details><summary>Show more</summary>

```
			StaticText Overlay my calendar
		group
			[96] radio $Switch to monthly view, center=(1795,34), checked='true', type=button
			[100] radio $Switch to weekly view, center=(1837,34), checked='false', type=button
			[104] radio $Switch to column view, center=(1879,34), checked='false', type=button
		list
			listitem
				[114] link Swift, center=(477,292), url='https://cal.com/swift-finance?redirect=false'
					image Swift, url='https://cal.com/api/avatar/d45452d7-10cf-4715-b6f0-e895762ab8df.png'
		paragraph
			StaticText Swift
		heading Book Demo
		paragraph
			StaticText David – Co-Founder & CEO
		StaticText Requires confirmation
		StaticText 30m
		image Google Meet icon, url='https://cal.com/app-store/googlevideo/logo.webp'
		[135] paragraph, center=(536,510), inner_text=Google Meet
			StaticText Google Meet
		generic
		StaticText Select...
		[148] combobox Timezone Select, center=(491,546), autocomplete=off, contenteditable=True, expanded=False, hasPopup='menu', type=text
		[137] svg, center=(473,546)
		strong
			StaticText January
		[152] svg, center=(560,546)
		StaticText 2025
		[161] button View previous month, center=(1126,286), type=button
		[163] button View next month, center=(1162,286), type=button
		StaticText MON
		StaticText TUE
		StaticText WED
		StaticText THU
		StaticText FRI
		StaticText SAT
		StaticText SUN
		[179] button 1, center=(897,386), type=button
		[181] button 2, center=(960,386), type=button
		[183] button 3 today, center=(1024,386), inner_text=3
today, type=button
		[187] button 4, center=(1087,386), type=button
		[189] button 5, center=(1150,386), type=button
		[191] button 6, center=(771,449), type=button
		[193] button 7, center=(834,449), type=button
		[195] button 8, center=(897,449), type=button
		[197] button 9, center=(960,449), type=button
		[199] button 10, center=(1024,449), type=button
		[201] button 11, center=(1087,449), type=button
		[203] button 12, center=(1150,449), type=button
		[205] button 13, center=(771,512), type=button
		[207] button 14, center=(834,512), type=button
		[209] button 15, center=(897,512), type=button
		[211] button 16, center=(960,512), type=button
		[213] button 17, center=(1024,512), type=button
		[215] button 18, center=(1087,512), type=button
		[217] button 19, center=(1150,512), type=button
		[219] button 20, center=(771,576), type=button
		[221] button 21, center=(834,576), type=button
		[223] button 22, center=(897,576), type=button
		[225] button 23, center=(960,576), type=button
		[227] button 24, center=(1024,576), type=button
		[229] button 25, center=(1087,576), type=button
		[231] button 26, center=(1150,576), type=button
		[233] button 27, center=(771,639), type=button
		[235] button 28, center=(834,639), type=button
		[237] button 29, center=(897,639), type=button
		[239] button 30, center=(960,639), type=button
		[241] button 31, center=(1024,639), type=button
		StaticText Fri
		StaticText 03
		group
			[250] radio 12h, center=(1377,286), checked='true', type=button
			[252] radio 24h, center=(1429,286), checked='false', type=button
		[259] button 2:00pm, center=(1340,335), type=button
		[262] button 2:30pm, center=(1340,381), type=button
		[265] button 3:00pm, center=(1340,427), type=button
		[268] button 3:30pm, center=(1340,473), type=button
		[271] button 4:00pm, center=(1340,519), type=button
		[274] button 4:30pm, center=(1340,565), type=button
		[278] link Cal.com Logo, center=(960,784), url='https://go.cal.com/booking'
			image Cal.com Logo, url='https://app.cal.com/api/logo'
	alert, atomic
```
</details>



```
RootWebArea Book Demo | Swift | Cal.com, focused, url='https://cal.com/swift-finance/demo?date=2025-01-03&month=2025-01&slot=2025-01-03T14%3A00%3A00.000Z'
	image
	main
		[92] switch Overlay my calendar, center=(1585,34), checked='false', type=button
		LabelText
```
<details><summary>Show more</summary>

```
			StaticText Overlay my calendar
		group
			[96] radio $Switch to monthly view, center=(1795,34), checked='true', type=button
			[100] radio $Switch to weekly view, center=(1837,34), checked='false', type=button
			[104] radio $Switch to column view, center=(1879,34), checked='false', type=button
		list
			listitem
				[114] link Swift, center=(617,312), url='https://cal.com/swift-finance?redirect=false'
					image Swift, url='https://cal.com/api/avatar/d45452d7-10cf-4715-b6f0-e895762ab8df.png'
		paragraph
			StaticText Swift
		heading Book Demo
		paragraph
			StaticText David – Co-Founder & CEO
		StaticText Friday, January 3, 2025
		StaticText 2:00 – 2:30 pm
		StaticText Requires confirmation
		StaticText 30m
		image Google Meet icon, url='https://cal.com/app-store/googlevideo/logo.webp'
		[135] paragraph, center=(676,586), inner_text=Google Meet
			StaticText Google Meet
		StaticText UTC
		LabelText
			StaticText Your name
			StaticText *
		[138] div, center=(644,622), inner_text=UTC
		[137] svg, center=(613,622)
		[303] textbox Your name*, center=(1130,340), contenteditable=True, required, type=text
		LabelText
			StaticText Email address
			StaticText *
		[312] textbox Email address *, center=(1130,414), contenteditable=True, type=email
		LabelText
			StaticText Additional notes
		[340] textbox Additional notes, center=(1130,509), contenteditable=True
		[344] button Add guests, center=(1010,584), type=button
		StaticText By proceeding, you agree to our
		[348] link Terms, center=(1157,640), url='https://cal.com/terms'
		StaticText and
		[349] link Privacy Policy, center=(1244,640), url='https://cal.com/privacy'
		StaticText .
		[351] button Back, center=(1188,682), type=button
		[352] button Confirm, center=(1272,682), type=submit
		[278] link Cal.com Logo, center=(960,764), url='https://go.cal.com/booking'
			image Cal.com Logo, url='https://app.cal.com/api/logo'
	alert, atomic
```
</details>

**Reasoning for action:** I selected the '2:00 PM' time slot by clicking on button '259'. This step is crucial because it finalizes the timing for the demo appointment, moving closer to confirming the appointment request. The next step will involve filling in the user's name to complete the initial booking process.

**Action:** click('259') # Click on the 2:00 PM time slot to proceed with booking the demo.

**Change Description:** After clicking on the 2:00 PM time slot, the browser updated the URL to include the selected time slot and displayed additional form fields for entering the user's name, email address, and additional notes for the booking, along with the confirmation buttons and the new demo details.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://cal.com/swift-finance/demo?date=2025-01-03&month=2025-01&slot=2025-01-03T14%3A00%3A00.000Z

https://cal.com/swift-finance/demo?date=2025-01-03&month=2025-01&slot=2025-01-03T14%3A00%3A00.000Z

**Content (before/after):** 

```
RootWebArea Book Demo | Swift | Cal.com, focused, url='https://cal.com/swift-finance/demo?date=2025-01-03&month=2025-01&slot=2025-01-03T14%3A00%3A00.000Z'
	image
	main
		[92] switch Overlay my calendar, center=(1585,34), checked='false', type=button
		LabelText
```
<details><summary>Show more</summary>

```
			StaticText Overlay my calendar
		group
			[96] radio $Switch to monthly view, center=(1795,34), checked='true', type=button
			[100] radio $Switch to weekly view, center=(1837,34), checked='false', type=button
			[104] radio $Switch to column view, center=(1879,34), checked='false', type=button
		list
			listitem
				[114] link Swift, center=(617,312), url='https://cal.com/swift-finance?redirect=false'
					image Swift, url='https://cal.com/api/avatar/d45452d7-10cf-4715-b6f0-e895762ab8df.png'
		paragraph
			StaticText Swift
		heading Book Demo
		paragraph
			StaticText David – Co-Founder & CEO
		StaticText Friday, January 3, 2025
		StaticText 2:00 – 2:30 pm
		StaticText Requires confirmation
		StaticText 30m
		image Google Meet icon, url='https://cal.com/app-store/googlevideo/logo.webp'
		[135] paragraph, center=(676,586), inner_text=Google Meet
			StaticText Google Meet
		StaticText UTC
		LabelText
			StaticText Your name
			StaticText *
		[138] div, center=(644,622), inner_text=UTC
		[137] svg, center=(613,622)
		[303] textbox Your name*, center=(1130,340), contenteditable=True, required, type=text
		LabelText
			StaticText Email address
			StaticText *
		[312] textbox Email address *, center=(1130,414), contenteditable=True, type=email
		LabelText
			StaticText Additional notes
		[340] textbox Additional notes, center=(1130,509), contenteditable=True
		[344] button Add guests, center=(1010,584), type=button
		StaticText By proceeding, you agree to our
		[348] link Terms, center=(1157,640), url='https://cal.com/terms'
		StaticText and
		[349] link Privacy Policy, center=(1244,640), url='https://cal.com/privacy'
		StaticText .
		[351] button Back, center=(1188,682), type=button
		[352] button Confirm, center=(1272,682), type=submit
		[278] link Cal.com Logo, center=(960,764), url='https://go.cal.com/booking'
			image Cal.com Logo, url='https://app.cal.com/api/logo'
	alert, atomic
```
</details>



```
RootWebArea Book Demo | Swift | Cal.com, focused, url='https://cal.com/swift-finance/demo?date=2025-01-03&month=2025-01&slot=2025-01-03T14%3A00%3A00.000Z'
	image
	main
		[92] switch Overlay my calendar, center=(1585,34), checked='false', type=button
		LabelText
```
<details><summary>Show more</summary>

```
			StaticText Overlay my calendar
		group
			[96] radio $Switch to monthly view, center=(1795,34), checked='true', type=button
			[100] radio $Switch to weekly view, center=(1837,34), checked='false', type=button
			[104] radio $Switch to column view, center=(1879,34), checked='false', type=button
		list
			listitem
				[114] link Swift, center=(617,312), url='https://cal.com/swift-finance?redirect=false'
					image Swift, url='https://cal.com/api/avatar/d45452d7-10cf-4715-b6f0-e895762ab8df.png'
		paragraph
			StaticText Swift
		heading Book Demo
		paragraph
			StaticText David – Co-Founder & CEO
		StaticText Friday, January 3, 2025
		StaticText 2:00 – 2:30 pm
		StaticText Requires confirmation
		StaticText 30m
		image Google Meet icon, url='https://cal.com/app-store/googlevideo/logo.webp'
		[135] paragraph, center=(676,586), inner_text=Google Meet
			StaticText Google Meet
		StaticText UTC
		LabelText
			StaticText Your name
			StaticText *
		[138] div, center=(644,622), inner_text=UTC
		[137] svg, center=(613,622)
		[303] textbox Your name* value='John Doe', center=(1130,340), contenteditable=True, focused, required, type=text
		LabelText
			StaticText Email address
			StaticText *
		[312] textbox Email address *, center=(1130,414), contenteditable=True, type=email
		LabelText
			StaticText Additional notes
		[340] textbox Additional notes, center=(1130,509), contenteditable=True
		[344] button Add guests, center=(1010,584), type=button
		StaticText By proceeding, you agree to our
		[348] link Terms, center=(1157,640), url='https://cal.com/terms'
		StaticText and
		[349] link Privacy Policy, center=(1244,640), url='https://cal.com/privacy'
		StaticText .
		[351] button Back, center=(1188,682), type=button
		[352] button Confirm, center=(1272,682), type=submit
		[278] link Cal.com Logo, center=(960,764), url='https://go.cal.com/booking'
			image Cal.com Logo, url='https://app.cal.com/api/logo'
	alert, atomic
```
</details>

**Reasoning for action:** By filling in the 'Your name' field with 'John Doe', I'm providing the required information needed to successfully book the demo appointment. This is a critical step in the process as the user's name is part of the essential data required to confirm the appointment. The action aligns with the user story, getting us closer to receiving confirmation of the selected time slot.

**Action:** fill('303', 'John Doe') # Fill in the 'Your name' field with a sample name.

**Change Description:** The 'Your name' text field has been filled with the value 'John Doe', which is now displayed as the current value of that field.

**Screenshot before:****Screenshot after:**---

