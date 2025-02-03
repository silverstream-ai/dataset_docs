# Task

**User Exploration of LYGG Corporation Website**

As a potential customer of LYGG Corporation,
I explore the company and its offerings,
so that I can understand more about their team and how to contact them for inquiries.

**Success definition:** Given I am on the LYGG Corporation homepage
When I click on the HOME link, then the TEAM link, and finally the CONTACT link
Then I should be able to see the team information, including team members' photos and credentials, and I should have access to the contact information, including a submission form and email details.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.lyggcorp.com/

https://www.lyggcorp.com/

**Content (before/after):** 

```
RootWebArea LYGG - Home, focused, url='https://www.lyggcorp.com/'
	LayoutTable
		[69] link LYGG, center=(73,39), url='https://www.lyggcorp.com/'
		list
			listitem
```
<details><summary>Show more</summary>

```
				[74] link HOME, center=(1657,39), url='https://www.lyggcorp.com/'
			listitem
				[76] link TEAM, center=(1739,39), url='https://www.lyggcorp.com/team.html'
			listitem
				[78] link CONTACT, center=(1834,39), url='https://www.lyggcorp.com/contact.html'
	LayoutTable
		LayoutTable
			heading Lygg
			StaticText Building New Sunscreen Ingredients
```
</details>



```
RootWebArea LYGG - Home, focused, url='https://www.lyggcorp.com/'
	LayoutTable
		[69] link LYGG, center=(73,39), url='https://www.lyggcorp.com/'
		list
			listitem
```
<details><summary>Show more</summary>

```
				[74] link HOME, center=(1657,39), url='https://www.lyggcorp.com/'
			listitem
				[76] link TEAM, center=(1739,39), url='https://www.lyggcorp.com/team.html'
			listitem
				[78] link CONTACT, center=(1834,39), url='https://www.lyggcorp.com/contact.html'
	LayoutTable
		LayoutTable
			heading Lygg
			StaticText Building New Sunscreen Ingredients
```
</details>

**Reasoning for action:** I clicked on the HOME link as my first action to ensure that I start from the main page of the LYGG Corporation website. This is a crucial first step because it allows me to confirm that I am on the homepage and provides me with direct access to the other important links I need for this task, particularly the TEAM and CONTACT links that will help me gather all the necessary information related to their offerings and contact options.

**Action:** click(74) # Click on the HOME link to explore the main content.

**Change Description:** After clicking the HOME link, the browser's state remained unchanged as the action did not navigate to a different page or alter any content.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://www.lyggcorp.com/

https://www.lyggcorp.com/team.html

**Content (before/after):** 

```
RootWebArea LYGG - Home, focused, url='https://www.lyggcorp.com/'
	LayoutTable
		[69] link LYGG, center=(73,39), url='https://www.lyggcorp.com/'
		list
			listitem
```
<details><summary>Show more</summary>

```
				[74] link HOME, center=(1657,39), url='https://www.lyggcorp.com/'
			listitem
				[76] link TEAM, center=(1739,39), url='https://www.lyggcorp.com/team.html'
			listitem
				[78] link CONTACT, center=(1834,39), url='https://www.lyggcorp.com/contact.html'
	LayoutTable
		LayoutTable
			heading Lygg
			StaticText Building New Sunscreen Ingredients
```
</details>



```
RootWebArea Team - LYGG, focused, url='https://www.lyggcorp.com/team.html'
	LayoutTable
		[69] link LYGG, center=(73,39), url='https://www.lyggcorp.com/'
		list
			listitem
```
<details><summary>Show more</summary>

```
				[74] link HOME, center=(1657,39), url='https://www.lyggcorp.com/'
			listitem
				[76] link TEAM, center=(1739,39), url='https://www.lyggcorp.com/team.html'
			listitem
				[78] link CONTACT, center=(1834,39), url='https://www.lyggcorp.com/contact.html'
	LayoutTable
		heading Team
	LayoutTable
		LayoutTable
			LayoutTableRow
				LayoutTableCell Photo of Graham Dick
					image Photo of Graham Dick, url='https://www.lyggcorp.com/uploads/1/3/4/8/134898224/editor/graham-dick-headshot_3.jpg?1687215635'
					[107] a, center=(684,826)
				LayoutTableCell Graham Dick Founder & CEO PhD Chemistry - Stanford University Postdoctoral Research - EPFL 12 Publications (1,000+ citations) 5 Patents (granted and pending)
					strong
						StaticText Graham Dick
					StaticText Founder & CEO
					list
						[121] listitem, center=(1203,645), inner_text=PhD Chemistry - Stanford University
							ListMarker •
							StaticText PhD Chemistry - Stanford University
						[122] listitem, center=(1203,672), inner_text=Postdoctoral Research - EPFL

							ListMarker •
							StaticText Postdoctoral Research - EPFL
						[124] listitem, center=(1203,699), inner_text=12 Publications (1,000+ citations)
							ListMarker •
							StaticText 12 Publications (1,000+ citations)
						[125] listitem, center=(1203,726), inner_text=5 Patents (granted and pending)
							ListMarker •
							StaticText 5 Patents (granted and pending)
	StaticText Lygg Corporation, 2627 Hanover Street, Palo Alto, CA, 94304
```
</details>

**Reasoning for action:** I selected the TEAM link because it's essential for the user to gain insight into the people behind LYGG Corporation. By clicking on this link, I will be redirected to a page dedicated to showcasing the team, which directly addresses the user's need to understand more about them. This step is crucial as it gets me closer to fulfilling the user's objective of exploring the company offerings.

**Action:** click(76) # Click on the TEAM link to explore the team behind Lygg.

**Change Description:** After clicking the TEAM link, the browser navigated to the Team page of LYGG, changing the title to 'Team - LYGG' and updating the URL to 'https://www.lyggcorp.com/team.html'. Additionally, new content was loaded featuring an introduction to Graham Dick, including his photo and credentials, which were not present in the previous state.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://www.lyggcorp.com/team.html

https://www.lyggcorp.com/contact.html

**Content (before/after):** 

```
RootWebArea Team - LYGG, focused, url='https://www.lyggcorp.com/team.html'
	LayoutTable
		[69] link LYGG, center=(73,39), url='https://www.lyggcorp.com/'
		list
			listitem
```
<details><summary>Show more</summary>

```
				[74] link HOME, center=(1657,39), url='https://www.lyggcorp.com/'
			listitem
				[76] link TEAM, center=(1739,39), url='https://www.lyggcorp.com/team.html'
			listitem
				[78] link CONTACT, center=(1834,39), url='https://www.lyggcorp.com/contact.html'
	LayoutTable
		heading Team
	LayoutTable
		LayoutTable
			LayoutTableRow
				LayoutTableCell Photo of Graham Dick
					image Photo of Graham Dick, url='https://www.lyggcorp.com/uploads/1/3/4/8/134898224/editor/graham-dick-headshot_3.jpg?1687215635'
					[107] a, center=(684,826)
				LayoutTableCell Graham Dick Founder & CEO PhD Chemistry - Stanford University Postdoctoral Research - EPFL 12 Publications (1,000+ citations) 5 Patents (granted and pending)
					strong
						StaticText Graham Dick
					StaticText Founder & CEO
					list
						[121] listitem, center=(1203,645), inner_text=PhD Chemistry - Stanford University
							ListMarker •
							StaticText PhD Chemistry - Stanford University
						[122] listitem, center=(1203,672), inner_text=Postdoctoral Research - EPFL

							ListMarker •
							StaticText Postdoctoral Research - EPFL
						[124] listitem, center=(1203,699), inner_text=12 Publications (1,000+ citations)
							ListMarker •
							StaticText 12 Publications (1,000+ citations)
						[125] listitem, center=(1203,726), inner_text=5 Patents (granted and pending)
							ListMarker •
							StaticText 5 Patents (granted and pending)
	StaticText Lygg Corporation, 2627 Hanover Street, Palo Alto, CA, 94304
```
</details>



```
RootWebArea Contact - LYGG, focused, url='https://www.lyggcorp.com/contact.html'
	LayoutTable
		[71] link LYGG, center=(73,39), url='https://www.lyggcorp.com/'
		list
			listitem
```
<details><summary>Show more</summary>

```
				[76] link HOME, center=(1657,39), url='https://www.lyggcorp.com/'
			listitem
				[78] link TEAM, center=(1739,39), url='https://www.lyggcorp.com/team.html'
			listitem
				[80] link CONTACT, center=(1834,39), url='https://www.lyggcorp.com/contact.html'
	LayoutTable
		heading Contact
	LayoutTable
		LayoutTable
			LayoutTableRow
				[107] LayoutTableCell Reach out to learn more about what we're doing EMAIL / info@lyggcorp.com, center=(712,694), inner_text=Reach out to learn more about what we're doing

EMAIL / info@lyggcorp.com
					StaticText Reach out to learn more about what we're doing
					strong
						StaticText EMAIL /
					strong
						StaticText info@lyggcorp.com
				LayoutTableCell * Indicates required field Name * Email * Comment * Submit SUBMIT
					list
						LabelText
							StaticText *
							StaticText Indicates required field
						LabelText
							StaticText Name
							StaticText *
						[131] textbox, center=(1055,521), contenteditable=True, required, type=text
						[134] textbox, center=(1265,521), contenteditable=True, required, type=text
						LabelText
							StaticText Email
							StaticText *
						[143] textbox Email *, center=(1160,610), contenteditable=True, required, type=text
						LabelText
							StaticText Comment
							StaticText *
						[150] textbox Comment *, center=(1160,780), contenteditable=True, required
					button Submit
					[160] a, center=(1019,930), inner_text=SUBMIT
					StaticText SUBMIT
	StaticText Lygg Corporation, 2627 Hanover Street, Palo Alto, CA, 94304
```
</details>

**Reasoning for action:** I reasoned that since the user story requires accessing the contact information after viewing the team details, I needed to follow the provided instructions by clicking on the CONTACT link (link 78). This action advances my task by moving me closer to fulfilling the user's request to see the contact options, such as the submission form and email details, once I navigate away from the team information.

**Action:** click(78) # Click on the CONTACT link to explore how to reach Lygg Corporation.

**Change Description:** The browser navigated from the Team page to the Contact page of Lygg Corporation, updating the URL to 'https://www.lyggcorp.com/contact.html' and displaying new content related to contact information, including a form to submit inquiries and an email address for further communication.

**Screenshot before:****Screenshot after:**---

