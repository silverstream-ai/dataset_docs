# Task

**Influencer Follower Range Selection**

As a marketing professional,
I select a specific follower range for influencer search,
so that I can find influencers that best match my campaign criteria.

**Success definition:** Given I am on the Stormy AI homepage
When I select the follower range from '10K - 50K' to '30K' in the combobox
Then I should see the 'From' option updated to '30K' and the 'To' option displaying '50K', reflecting my choice.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.stormy.ai/

https://www.stormy.ai/

**Content (before/after):** 

```
RootWebArea Stormy, focused, url='https://www.stormy.ai/'
	banner
		[30] link Stormy AI, center=(338,46), url='https://www.stormy.ai/#'
	main
		heading Find your next Influencer
```
<details><summary>Show more</summary>

```
		[45] textbox Describe your perfect influencer..., center=(960,274), contenteditable=True
		[48] button 10K - 50K followers, center=(728,348), expanded=False, hasPopup='dialog', type=button
			image
		[50] combobox value='All Countries', center=(893,348), expanded=False, hasPopup='listbox', inner_text=All Countries, type=button
			image
		[53] button, center=(1268,348)
			image
		paragraph
			StaticText Powering the influencer campaigns for companies like:
		image invisibility, url='https://www.stormy.ai/_next/image?url=%2Flogos%2Finvisibility.png&w=256&q=75'
		image fixkey, url='https://www.stormy.ai/_next/image?url=%2Flogos%2Ffixkey.png&w=256&q=75'
		image realfake, url='https://www.stormy.ai/_next/image?url=%2Flogos%2Frealfake.png&w=256&q=75'
		image ceejay, url='https://www.stormy.ai/_next/image?url=%2Flogos%2Fceejay.png&w=256&q=75'
		heading AI-Powered Influencer Search
		paragraph
			StaticText Simply describe your ideal influencer in natural language, and our AI will find the perfect match based on your requirements. No more manual searching through endless profiles.
		image AI-powered search demo, url='https://www.stormy.ai/_next/image?url=%2Fvideos%2Ftyping.gif&w=1200&q=75'
		image Smart filtering and analysis visualization, url='https://www.stormy.ai/_next/image?url=%2Fvideos%2Fsimilar_users.png&w=1200&q=75'
		heading Smart Filtering & Analysis
		paragraph
			StaticText Our AI automatically analyzes engagement rates, follower count, and content quality to ensure authentic influence. Get detailed insights into performance metrics and audience demographics.
		heading Automated Negotiations
		paragraph
			StaticText Let our AI handle price negotiations with influencers, saving you time and ensuring the best deals. Our system analyzes market rates and engagement metrics to determine fair pricing.
		image Smart filtering and analysis visualization, url='https://www.stormy.ai/_next/image?url=%2Fvideos%2Fnego.jpg&w=1200&q=75'
		link Investor? Click Here, url='https://cal.com/stormy-ai/investor'
	contentinfo
		paragraph
			StaticText © 2024 Stormy AI. All rights reserved.
		navigation
			link Terms, url='https://www.stormy.ai/#'
			link Privacy, url='https://www.stormy.ai/#'
			link Contact, url='https://www.stormy.ai/#'
	region Notifications alt+T
	alert, atomic
```
</details>



```
RootWebArea Stormy, focused, url='https://www.stormy.ai/'
	banner
		[30] link Stormy AI, center=(338,46), url='https://www.stormy.ai/#'
	main
		heading Find your next Influencer
```
<details><summary>Show more</summary>

```
		[45] textbox Describe your perfect influencer..., center=(960,274), contenteditable=True
		[48] button 10K - 50K followers, center=(728,348), expanded=True, hasPopup='dialog', type=button
			image
		[50] combobox value='All Countries', center=(893,348), expanded=False, hasPopup='listbox', inner_text=All Countries, type=button
			image
		[53] button, center=(1268,348)
			image
		paragraph
			StaticText Powering the influencer campaigns for companies like:
		image invisibility, url='https://www.stormy.ai/_next/image?url=%2Flogos%2Finvisibility.png&w=256&q=75'
		image fixkey, url='https://www.stormy.ai/_next/image?url=%2Flogos%2Ffixkey.png&w=256&q=75'
		image realfake, url='https://www.stormy.ai/_next/image?url=%2Flogos%2Frealfake.png&w=256&q=75'
		image ceejay, url='https://www.stormy.ai/_next/image?url=%2Flogos%2Fceejay.png&w=256&q=75'
		heading AI-Powered Influencer Search
		paragraph
			StaticText Simply describe your ideal influencer in natural language, and our AI will find the perfect match based on your requirements. No more manual searching through endless profiles.
		image AI-powered search demo, url='https://www.stormy.ai/_next/image?url=%2Fvideos%2Ftyping.gif&w=1200&q=75'
		image Smart filtering and analysis visualization, url='https://www.stormy.ai/_next/image?url=%2Fvideos%2Fsimilar_users.png&w=1200&q=75'
		heading Smart Filtering & Analysis
		paragraph
			StaticText Our AI automatically analyzes engagement rates, follower count, and content quality to ensure authentic influence. Get detailed insights into performance metrics and audience demographics.
		heading Automated Negotiations
		paragraph
			StaticText Let our AI handle price negotiations with influencers, saving you time and ensuring the best deals. Our system analyzes market rates and engagement metrics to determine fair pricing.
		image Smart filtering and analysis visualization, url='https://www.stormy.ai/_next/image?url=%2Fvideos%2Fnego.jpg&w=1200&q=75'
		link Investor? Click Here, url='https://cal.com/stormy-ai/investor'
	contentinfo
		paragraph
			StaticText © 2024 Stormy AI. All rights reserved.
		navigation
			link Terms, url='https://www.stormy.ai/#'
			link Privacy, url='https://www.stormy.ai/#'
			link Contact, url='https://www.stormy.ai/#'
	region Notifications alt+T
	alert, atomic
	dialog, modal=False
		paragraph
			StaticText From
		[106] combobox value='10K', center=(720,425), expanded=False, focused, hasPopup='listbox', inner_text=10K, type=button
		paragraph
			StaticText To
		[111] combobox value='50K', center=(868,425), expanded=False, hasPopup='listbox', inner_text=50K, type=button
```
</details>

**Reasoning for action:** I clicked on the follower range button because it is the first step needed to modify the follower range selection. By doing this, it allows me to access the follower range options that I can choose from to set my desired range for influencer search, which is crucial for fulfilling the user's requirement.

**Action:** click(48) # Click on the follower range button to explore options.

**Change Description:** After clicking the follower range button, it expanded to show a dialog with parameters for follower limits, including two comboboxes for selecting the lower limit (10K) and the upper limit (50K), allowing the user to refine their search.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://www.stormy.ai/

https://www.stormy.ai/

**Content (before/after):** 

```
RootWebArea Stormy, focused, url='https://www.stormy.ai/'
	banner
		[30] link Stormy AI, center=(338,46), url='https://www.stormy.ai/#'
	main
		heading Find your next Influencer
```
<details><summary>Show more</summary>

```
		[45] textbox Describe your perfect influencer..., center=(960,274), contenteditable=True
		[48] button 10K - 50K followers, center=(728,348), expanded=True, hasPopup='dialog', type=button
			image
		[50] combobox value='All Countries', center=(893,348), expanded=False, hasPopup='listbox', inner_text=All Countries, type=button
			image
		[53] button, center=(1268,348)
			image
		paragraph
			StaticText Powering the influencer campaigns for companies like:
		image invisibility, url='https://www.stormy.ai/_next/image?url=%2Flogos%2Finvisibility.png&w=256&q=75'
		image fixkey, url='https://www.stormy.ai/_next/image?url=%2Flogos%2Ffixkey.png&w=256&q=75'
		image realfake, url='https://www.stormy.ai/_next/image?url=%2Flogos%2Frealfake.png&w=256&q=75'
		image ceejay, url='https://www.stormy.ai/_next/image?url=%2Flogos%2Fceejay.png&w=256&q=75'
		heading AI-Powered Influencer Search
		paragraph
			StaticText Simply describe your ideal influencer in natural language, and our AI will find the perfect match based on your requirements. No more manual searching through endless profiles.
		image AI-powered search demo, url='https://www.stormy.ai/_next/image?url=%2Fvideos%2Ftyping.gif&w=1200&q=75'
		image Smart filtering and analysis visualization, url='https://www.stormy.ai/_next/image?url=%2Fvideos%2Fsimilar_users.png&w=1200&q=75'
		heading Smart Filtering & Analysis
		paragraph
			StaticText Our AI automatically analyzes engagement rates, follower count, and content quality to ensure authentic influence. Get detailed insights into performance metrics and audience demographics.
		heading Automated Negotiations
		paragraph
			StaticText Let our AI handle price negotiations with influencers, saving you time and ensuring the best deals. Our system analyzes market rates and engagement metrics to determine fair pricing.
		image Smart filtering and analysis visualization, url='https://www.stormy.ai/_next/image?url=%2Fvideos%2Fnego.jpg&w=1200&q=75'
		link Investor? Click Here, url='https://cal.com/stormy-ai/investor'
	contentinfo
		paragraph
			StaticText © 2024 Stormy AI. All rights reserved.
		navigation
			link Terms, url='https://www.stormy.ai/#'
			link Privacy, url='https://www.stormy.ai/#'
			link Contact, url='https://www.stormy.ai/#'
	region Notifications alt+T
	alert, atomic
	dialog, modal=False
		paragraph
			StaticText From
		[106] combobox value='10K', center=(720,425), expanded=False, focused, hasPopup='listbox', inner_text=10K, type=button
		paragraph
			StaticText To
		[111] combobox value='50K', center=(868,425), expanded=False, hasPopup='listbox', inner_text=50K, type=button
```
</details>



```
RootWebArea Stormy, focused, url='https://www.stormy.ai/'
	region Notifications alt+T
	listbox, orientation='vertical'
		[120] option 10K, center=(722,468), focused, selected=True
		[125] option 30K, center=(722,500), selected=False
```
<details><summary>Show more</summary>

```
		[128] option 50K, center=(722,532), selected=False
		[131] option 100K, center=(722,564), selected=False
		[134] option 200K, center=(722,596), selected=False
```
</details>

**Reasoning for action:** By clicking on the 'From' combobox, I initiate the process of updating the value that corresponds to the lower limit of the follower range. This action is essential because the goal is to change the follower range from '10K - 50K' to '30K'. Opening this combobox allows me to select the new lower limit directly, which is the first step in proceeding with the user's criteria.

**Action:** click(106) # Click on the 'From' combobox to explore follower range options.

**Change Description:** The 'From' combobox was clicked, resulting in the display of a listbox containing follower range options, with the current selection highlighting '10K' as selected, while options for '30K', '50K', '100K', and '200K' are also available.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://www.stormy.ai/

https://www.stormy.ai/

**Content (before/after):** 

```
RootWebArea Stormy, focused, url='https://www.stormy.ai/'
	region Notifications alt+T
	listbox, orientation='vertical'
		[120] option 10K, center=(722,468), focused, selected=True
		[125] option 30K, center=(722,500), selected=False
```
<details><summary>Show more</summary>

```
		[128] option 50K, center=(722,532), selected=False
		[131] option 100K, center=(722,564), selected=False
		[134] option 200K, center=(722,596), selected=False
```
</details>



```
RootWebArea Stormy, focused, url='https://www.stormy.ai/'
	banner
		[30] link Stormy AI, center=(338,46), url='https://www.stormy.ai/#'
	main
		heading Find your next Influencer
```
<details><summary>Show more</summary>

```
		[45] textbox Describe your perfect influencer..., center=(960,274), contenteditable=True
		[48] button 30K - 50K followers, center=(730,348), expanded=True, hasPopup='dialog', type=button
			image
		[50] combobox value='All Countries', center=(896,348), expanded=False, hasPopup='listbox', inner_text=All Countries, type=button
			image
		[53] button, center=(1268,348)
			image
		paragraph
			StaticText Powering the influencer campaigns for companies like:
		image invisibility, url='https://www.stormy.ai/_next/image?url=%2Flogos%2Finvisibility.png&w=256&q=75'
		image fixkey, url='https://www.stormy.ai/_next/image?url=%2Flogos%2Ffixkey.png&w=256&q=75'
		image realfake, url='https://www.stormy.ai/_next/image?url=%2Flogos%2Frealfake.png&w=256&q=75'
		image ceejay, url='https://www.stormy.ai/_next/image?url=%2Flogos%2Fceejay.png&w=256&q=75'
		heading AI-Powered Influencer Search
		paragraph
			StaticText Simply describe your ideal influencer in natural language, and our AI will find the perfect match based on your requirements. No more manual searching through endless profiles.
		image AI-powered search demo, url='https://www.stormy.ai/_next/image?url=%2Fvideos%2Ftyping.gif&w=1200&q=75'
		image Smart filtering and analysis visualization, url='https://www.stormy.ai/_next/image?url=%2Fvideos%2Fsimilar_users.png&w=1200&q=75'
		heading Smart Filtering & Analysis
		paragraph
			StaticText Our AI automatically analyzes engagement rates, follower count, and content quality to ensure authentic influence. Get detailed insights into performance metrics and audience demographics.
		heading Automated Negotiations
		paragraph
			StaticText Let our AI handle price negotiations with influencers, saving you time and ensuring the best deals. Our system analyzes market rates and engagement metrics to determine fair pricing.
		image Smart filtering and analysis visualization, url='https://www.stormy.ai/_next/image?url=%2Fvideos%2Fnego.jpg&w=1200&q=75'
		link Investor? Click Here, url='https://cal.com/stormy-ai/investor'
	contentinfo
		paragraph
			StaticText © 2024 Stormy AI. All rights reserved.
		navigation
			link Terms, url='https://www.stormy.ai/#'
			link Privacy, url='https://www.stormy.ai/#'
			link Contact, url='https://www.stormy.ai/#'
	region Notifications alt+T
	alert, atomic
	dialog, modal=False
		paragraph
			StaticText From
		[106] combobox value='30K', center=(720,425), expanded=False, focused, hasPopup='listbox', inner_text=30K, type=button
		paragraph
			StaticText To
		[111] combobox value='50K', center=(868,425), expanded=False, hasPopup='listbox', inner_text=50K, type=button
```
</details>

**Reasoning for action:** Selecting the '30K' option is essential for updating the range that matches my campaign criteria. By clicking this option, I change the current selection from '10K' to '30K', which is the desired starting point for my influencer search. This action directly modifies the 'From' value to '30K', which aligns with the task requirements of setting a specific follower range.

**Action:** click(125) # Click on the 30K option in the 'From' combobox.

**Change Description:** The selection in the 'From' combobox has changed from '10K' to '30K', and the 'To' combobox now displays '50K', reflecting the user's choice and updating the options for filtering influencers accordingly.

**Screenshot before:****Screenshot after:**---

