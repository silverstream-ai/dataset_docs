# Task

**User Registration for Waitlist**

As a prospective user,
I join the waitlist for Linum,
so that I can be notified when the service is available.

**Success definition:** Given I am on the Linum homepage and have clicked on the 'Join Waitlist' link
When I fill in my name and email address in the form
Then I should see a confirmation message indicating my registration was successful

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.linum.ai/

https://linum-ai.notion.site/16c39882d7348069a121f57400fb72c5

**Content (before/after):** 

```
RootWebArea Linum - AI Animator, focused, url='https://www.linum.ai/'
	banner
		[34] link Linum Logo, center=(324,35), url='https://www.linum.ai/#'
			image Linum Logo, url='https://cdn.prod.website-files.com/63d0b73e62b7fa2bd764b732/659848f9c5d3dbaebeb69d00_Frame%208.png'
		[36] link Join Waitlist, center=(1582,35), url='https://linum-ai.notion.site/16c39882d7348069a121f57400fb72c5'
```
<details><summary>Show more</summary>

```
	StaticText Type text
	StaticText Dream video
	image Anime waves GIF, url='https://cdn.prod.website-files.com/63d0b73e62b7fa2bd764b732/659877e2a8d6c3f9c720eaa3_waves-high.gif'
	image Cigar smoke GIF, url='https://cdn.prod.website-files.com/63d0b73e62b7fa2bd764b732/659889cb8183eee50bb7ad1e_cigar-smoke.gif'
	image Teddy bear swimming GIF, url='https://cdn.prod.website-files.com/63d0b73e62b7fa2bd764b732/65988a008420a166d7fee21b_bear-swimming.gif'
	image Cat yawning GIF, url='https://cdn.prod.website-files.com/63d0b73e62b7fa2bd764b732/65988a460878ff179889bdbd_cat-yawning.gif'
	StaticText GIFs generated using Linum text-to-video v1
	[58] link Join Waitlist, center=(960,711), url='https://linum-ai.notion.site/16c39882d7348069a121f57400fb72c5'
	[65] link Want to get in touch? Email us at hello @linum.ai, center=(420,773), url='mailto:hello@linum.ai?subject=Hi%20team!'
	StaticText Copyright © 2024 Linum, Inc. All rights reserved.
	[68] link Privacy Policy, center=(1607,777), url='https://www.notion.so/Privacy-Policy-21446ca4cdf44e3996e6200eacd868c2?pvs=4'
	[69] link Terms of Service, center=(1607,797), url='https://swamp-shop-015.notion.site/Terms-of-Service-6a93c411e43a4a1e855f150db6ad517b'
```
</details>



```
RootWebArea Linum Waitlist, focused, url='https://linum-ai.notion.site/16c39882d7348069a121f57400fb72c5'
	banner
		StaticText Linum Waitlist
		[53] button Close panel, center=(1752,18), disabled=True
			graphics-symbol
```
<details><summary>Show more</summary>

```
		[56] button More actions, center=(1780,20)
			graphics-symbol
		[58] button Made with, center=(1857,22)
			graphics-symbol
	main
		image Page icon, url='https://linum-ai.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Faea066b1-99e5-4636-80cb-2d11fa6d7be4%2F09920b79-6add-4105-898c-24831b7c8c24%2FLinum_L.svg?table=block&id=16c39882-d734-8069-a121-f57400fb72c5&spaceId=aea066b1-99e5-4636-80cb-2d11fa6d7be4&userId=&cache=v2'
		[89] heading Linum Waitlist, center=(960,310)
		StaticText Thank you for your interest in Linum’s text-to-video model. We will email you access credentials, once you are selected off the waitlist.
		heading Name*
		[92] div, center=(961,375), inner_text=Thank you for your interest in Linum’s text-to-video model. We will email you access credentials, once you are selected off the waitlist.
		[100] textbox Name*, center=(960,502), contenteditable=True, required, type=text
		heading Email Address*
		[107] textbox Email Address*, center=(960,624), contenteditable=True, required, type=text
		heading What are you trying to make?*
		[117] textbox What are you trying to make?*, center=(960,770), contenteditable=True, required, type=text
		group What other video models have you tried?*
			Legend
			StaticText (Select as many as you like)
			[125] button Runway Gen-3, center=(956,949)
				LabelText
					checkbox Runway Gen-3, checked='false'
					StaticText Runway Gen-3
			[137] button OpenAI Sora, center=(956,981)
				LabelText
					checkbox OpenAI Sora, checked='false'
					StaticText OpenAI Sora
			[149] button Google Veo-2, center=(956,1013)
				LabelText
					checkbox Google Veo-2, checked='false'
					StaticText Google Veo-2
			[161] button Tencent Hunyuan, center=(956,1045)
				LabelText
					checkbox Tencent Hunyuan, checked='false'
					StaticText Tencent Hunyuan
			[173] button MiniMax, center=(956,1077)
				LabelText
					checkbox MiniMax, checked='false'
					StaticText MiniMax
			button Pika
				LabelText
					checkbox Pika, checked='false'
					StaticText Pika
		heading What’s the biggest limitation you’ve hit with other video models?
		textbox What’s the biggest limitation you’ve hit with other video models?
		button Submit
		StaticText Never submit sensitive personal information, like passwords, through Notion Forms.
		button Report abuse
```
</details>

**Reasoning for action:** I clicked on the 'Join Waitlist' link because this is the first required step to register for the waitlist for Linum. By clicking this link, I will be directed to the necessary form to complete my registration, allowing me to fulfill the user story of joining the waitlist.

**Action:** click(36) # Click on the 'Join Waitlist' link to explore further.

**Change Description:** After clicking the 'Join Waitlist' link, the browser navigated to the Linum Waitlist page, which now displays a form for users to enter their name, email address, and details about their video creation interests, along with several interactive buttons and text indicating the purpose and instructions related to the waitlist.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://linum-ai.notion.site/16c39882d7348069a121f57400fb72c5

https://linum-ai.notion.site/16c39882d7348069a121f57400fb72c5

**Content (before/after):** 

```
RootWebArea Linum Waitlist, focused, url='https://linum-ai.notion.site/16c39882d7348069a121f57400fb72c5'
	banner
		StaticText Linum Waitlist
		[53] button Close panel, center=(1752,18), disabled=True
			graphics-symbol
```
<details><summary>Show more</summary>

```
		[56] button More actions, center=(1780,20)
			graphics-symbol
		[58] button Made with, center=(1857,22)
			graphics-symbol
	main
		image Page icon, url='https://linum-ai.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Faea066b1-99e5-4636-80cb-2d11fa6d7be4%2F09920b79-6add-4105-898c-24831b7c8c24%2FLinum_L.svg?table=block&id=16c39882-d734-8069-a121-f57400fb72c5&spaceId=aea066b1-99e5-4636-80cb-2d11fa6d7be4&userId=&cache=v2'
		[89] heading Linum Waitlist, center=(960,310)
		StaticText Thank you for your interest in Linum’s text-to-video model. We will email you access credentials, once you are selected off the waitlist.
		heading Name*
		[92] div, center=(961,375), inner_text=Thank you for your interest in Linum’s text-to-video model. We will email you access credentials, once you are selected off the waitlist.
		[100] textbox Name*, center=(960,502), contenteditable=True, required, type=text
		heading Email Address*
		[107] textbox Email Address*, center=(960,624), contenteditable=True, required, type=text
		heading What are you trying to make?*
		[117] textbox What are you trying to make?*, center=(960,770), contenteditable=True, required, type=text
		group What other video models have you tried?*
			Legend
			StaticText (Select as many as you like)
			[125] button Runway Gen-3, center=(956,949)
				LabelText
					checkbox Runway Gen-3, checked='false'
					StaticText Runway Gen-3
			[137] button OpenAI Sora, center=(956,981)
				LabelText
					checkbox OpenAI Sora, checked='false'
					StaticText OpenAI Sora
			[149] button Google Veo-2, center=(956,1013)
				LabelText
					checkbox Google Veo-2, checked='false'
					StaticText Google Veo-2
			[161] button Tencent Hunyuan, center=(956,1045)
				LabelText
					checkbox Tencent Hunyuan, checked='false'
					StaticText Tencent Hunyuan
			[173] button MiniMax, center=(956,1077)
				LabelText
					checkbox MiniMax, checked='false'
					StaticText MiniMax
			button Pika
				LabelText
					checkbox Pika, checked='false'
					StaticText Pika
		heading What’s the biggest limitation you’ve hit with other video models?
		textbox What’s the biggest limitation you’ve hit with other video models?
		button Submit
		StaticText Never submit sensitive personal information, like passwords, through Notion Forms.
		button Report abuse
```
</details>



```
RootWebArea Linum Waitlist, focused, url='https://linum-ai.notion.site/16c39882d7348069a121f57400fb72c5'
	banner
		StaticText Linum Waitlist
		[53] button Close panel, center=(1752,18), disabled=True
			graphics-symbol
```
<details><summary>Show more</summary>

```
		[56] button More actions, center=(1780,20)
			graphics-symbol
		[58] button Made with, center=(1857,22)
			graphics-symbol
	main
		image Page icon, url='https://linum-ai.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Faea066b1-99e5-4636-80cb-2d11fa6d7be4%2F09920b79-6add-4105-898c-24831b7c8c24%2FLinum_L.svg?table=block&id=16c39882-d734-8069-a121-f57400fb72c5&spaceId=aea066b1-99e5-4636-80cb-2d11fa6d7be4&userId=&cache=v2'
		[89] heading Linum Waitlist, center=(960,310)
		StaticText Thank you for your interest in Linum’s text-to-video model. We will email you access credentials, once you are selected off the waitlist.
		heading Name*
		[92] div, center=(961,375), inner_text=Thank you for your interest in Linum’s text-to-video model. We will email you access credentials, once you are selected off the waitlist.
		[100] textbox Name* value='John Doe', center=(960,502), contenteditable=True, focused, required, type=text
		heading Email Address*
		[107] textbox Email Address*, center=(960,624), contenteditable=True, required, type=text
		heading What are you trying to make?*
		[117] textbox What are you trying to make?*, center=(960,770), contenteditable=True, required, type=text
		group What other video models have you tried?*
			Legend
			StaticText (Select as many as you like)
			[125] button Runway Gen-3, center=(956,949)
				LabelText
					checkbox Runway Gen-3, checked='false'
					StaticText Runway Gen-3
			[137] button OpenAI Sora, center=(956,981)
				LabelText
					checkbox OpenAI Sora, checked='false'
					StaticText OpenAI Sora
			[149] button Google Veo-2, center=(956,1013)
				LabelText
					checkbox Google Veo-2, checked='false'
					StaticText Google Veo-2
			[161] button Tencent Hunyuan, center=(956,1045)
				LabelText
					checkbox Tencent Hunyuan, checked='false'
					StaticText Tencent Hunyuan
			[173] button MiniMax, center=(956,1077)
				LabelText
					checkbox MiniMax, checked='false'
					StaticText MiniMax
			button Pika
				LabelText
					checkbox Pika, checked='false'
					StaticText Pika
		heading What’s the biggest limitation you’ve hit with other video models?
		textbox What’s the biggest limitation you’ve hit with other video models?
		button Submit
		StaticText Never submit sensitive personal information, like passwords, through Notion Forms.
		button Report abuse
```
</details>

**Reasoning for action:** Filling in the Name field is crucial because it is a required input for joining the waitlist. By entering a name, I am progressing towards fulfilling the user's goal of completing the waitlist registration. This action directly addresses the acceptance test success criteria by ensuring that this part of the form is completed.

**Action:** fill(100, 'John Doe') # Fill in the Name field with a sample name.

**Change Description:** The Name textbox was updated with the value 'John Doe', indicating that the user has entered their name in the form.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://linum-ai.notion.site/16c39882d7348069a121f57400fb72c5

https://linum-ai.notion.site/16c39882d7348069a121f57400fb72c5

**Content (before/after):** 

```
RootWebArea Linum Waitlist, focused, url='https://linum-ai.notion.site/16c39882d7348069a121f57400fb72c5'
	banner
		StaticText Linum Waitlist
		[53] button Close panel, center=(1752,18), disabled=True
			graphics-symbol
```
<details><summary>Show more</summary>

```
		[56] button More actions, center=(1780,20)
			graphics-symbol
		[58] button Made with, center=(1857,22)
			graphics-symbol
	main
		image Page icon, url='https://linum-ai.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Faea066b1-99e5-4636-80cb-2d11fa6d7be4%2F09920b79-6add-4105-898c-24831b7c8c24%2FLinum_L.svg?table=block&id=16c39882-d734-8069-a121-f57400fb72c5&spaceId=aea066b1-99e5-4636-80cb-2d11fa6d7be4&userId=&cache=v2'
		[89] heading Linum Waitlist, center=(960,310)
		StaticText Thank you for your interest in Linum’s text-to-video model. We will email you access credentials, once you are selected off the waitlist.
		heading Name*
		[92] div, center=(961,375), inner_text=Thank you for your interest in Linum’s text-to-video model. We will email you access credentials, once you are selected off the waitlist.
		[100] textbox Name* value='John Doe', center=(960,502), contenteditable=True, focused, required, type=text
		heading Email Address*
		[107] textbox Email Address*, center=(960,624), contenteditable=True, required, type=text
		heading What are you trying to make?*
		[117] textbox What are you trying to make?*, center=(960,770), contenteditable=True, required, type=text
		group What other video models have you tried?*
			Legend
			StaticText (Select as many as you like)
			[125] button Runway Gen-3, center=(956,949)
				LabelText
					checkbox Runway Gen-3, checked='false'
					StaticText Runway Gen-3
			[137] button OpenAI Sora, center=(956,981)
				LabelText
					checkbox OpenAI Sora, checked='false'
					StaticText OpenAI Sora
			[149] button Google Veo-2, center=(956,1013)
				LabelText
					checkbox Google Veo-2, checked='false'
					StaticText Google Veo-2
			[161] button Tencent Hunyuan, center=(956,1045)
				LabelText
					checkbox Tencent Hunyuan, checked='false'
					StaticText Tencent Hunyuan
			[173] button MiniMax, center=(956,1077)
				LabelText
					checkbox MiniMax, checked='false'
					StaticText MiniMax
			button Pika
				LabelText
					checkbox Pika, checked='false'
					StaticText Pika
		heading What’s the biggest limitation you’ve hit with other video models?
		textbox What’s the biggest limitation you’ve hit with other video models?
		button Submit
		StaticText Never submit sensitive personal information, like passwords, through Notion Forms.
		button Report abuse
```
</details>



```
RootWebArea Linum Waitlist, focused, url='https://linum-ai.notion.site/16c39882d7348069a121f57400fb72c5'
	banner
		StaticText Linum Waitlist
		[53] button Close panel, center=(1752,18), disabled=True
			graphics-symbol
```
<details><summary>Show more</summary>

```
		[56] button More actions, center=(1780,20)
			graphics-symbol
		[58] button Made with, center=(1857,22)
			graphics-symbol
	main
		image Page icon, url='https://linum-ai.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Faea066b1-99e5-4636-80cb-2d11fa6d7be4%2F09920b79-6add-4105-898c-24831b7c8c24%2FLinum_L.svg?table=block&id=16c39882-d734-8069-a121-f57400fb72c5&spaceId=aea066b1-99e5-4636-80cb-2d11fa6d7be4&userId=&cache=v2'
		[89] heading Linum Waitlist, center=(960,310)
		StaticText Thank you for your interest in Linum’s text-to-video model. We will email you access credentials, once you are selected off the waitlist.
		heading Name*
		[92] div, center=(961,375), inner_text=Thank you for your interest in Linum’s text-to-video model. We will email you access credentials, once you are selected off the waitlist.
		[100] textbox Name* value='John Doe', center=(960,502), contenteditable=True, required, type=text
		heading Email Address*
		[107] textbox Email Address* value='john.doe@example.com', center=(960,624), contenteditable=True, focused, required, type=text
		heading What are you trying to make?*
		[117] textbox What are you trying to make?*, center=(960,770), contenteditable=True, required, type=text
		group What other video models have you tried?*
			Legend
			StaticText (Select as many as you like)
			[125] button Runway Gen-3, center=(956,949)
				LabelText
					checkbox Runway Gen-3, checked='false'
					StaticText Runway Gen-3
			[137] button OpenAI Sora, center=(956,981)
				LabelText
					checkbox OpenAI Sora, checked='false'
					StaticText OpenAI Sora
			[149] button Google Veo-2, center=(956,1013)
				LabelText
					checkbox Google Veo-2, checked='false'
					StaticText Google Veo-2
			[161] button Tencent Hunyuan, center=(956,1045)
				LabelText
					checkbox Tencent Hunyuan, checked='false'
					StaticText Tencent Hunyuan
			[173] button MiniMax, center=(956,1077)
				LabelText
					checkbox MiniMax, checked='false'
					StaticText MiniMax
			button Pika
				LabelText
					checkbox Pika, checked='false'
					StaticText Pika
		heading What’s the biggest limitation you’ve hit with other video models?
		textbox What’s the biggest limitation you’ve hit with other video models?
		button Submit
		StaticText Never submit sensitive personal information, like passwords, through Notion Forms.
		button Report abuse
```
</details>

**Reasoning for action:** Filling in the Email Address field is a necessary step in completing the form to join the waitlist for Linum. This action progresses towards satisfying the user's goal by ensuring all required information (name, email, and potentially more) is provided, enabling the user to submit their registration successfully.

**Action:** fill(107, 'john.doe@example.com') # Fill in the Email Address field with a sample email.

**Change Description:** The Email Address field was updated with the value 'john.doe@example.com', reflecting the input made by the user.

**Screenshot before:****Screenshot after:**---

