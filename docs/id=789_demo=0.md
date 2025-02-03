# Task

**User Journey through Maven Bio's Platform**

As a A biopharma research professional,
I explore Maven Bio's Workflows and schedule a demo to assess its capabilities,
so that I can evaluate how Maven Bio's AI-driven tools can streamline my research process.

**Success definition:** Given I am on the Maven Bio platform page
When I click on the Workflows link and then the Schedule Demo link
Then I should see the demo scheduling interface with available dates and times displayed.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.mavenbio.io/

https://www.mavenbio.io/

**Content (before/after):** 

```
RootWebArea Maven Bio, focused, url='https://www.mavenbio.io/'
	banner
		navigation
			[63] link Home, center=(457,54), url='https://www.mavenbio.io/'
				image, url='https://www.mavenbio.io/logo_horizontal.svg'
```
<details><summary>Show more</summary>

```
			[68] button Platform, center=(1045,54), expanded=False, hasPopup='menu', type=button
				paragraph
				image
			[72] link Research, center=(1166,54), url='https://www.mavenbio.io/research/page/1'
			[74] link Pricing, center=(1266,54), url='https://www.mavenbio.io/pricing'
			[80] link Sign in, center=(1370,54), url='https://auth.mavenbio.io/'
			[81] link Book a demo, center=(1499,54), url='https://cal.com/team/maven-bio/intro'
	main
		heading The AI Platform for BioPharma Knowledge Work
		paragraph
			StaticText Domain-specific AI for BioPharma consultants, investors, and in-house teams — reduce manual work and make better decisions
		[89] link Book a Demo, center=(359,532), url='https://cal.com/team/maven-bio/intro'
		navigation
			[95] link Workflows, center=(746,770), url='https://www.mavenbio.io/#workflows'
			[96] link Atlas, center=(888,770), url='https://www.mavenbio.io/#atlas'
			[97] link Compass, center=(1024,770), url='https://www.mavenbio.io/#compass'
			[98] link Assistant, center=(1181,770), url='https://www.mavenbio.io/#assistant'
		image
		heading Maven Workflows
		paragraph
			StaticText Collaborate directly with Maven's AI as it completes defined research tasks for you, in minutes. For example, our clinical data explorer workflow rapidly pulls together and standardizes clinical trial data for multiple assets
		link Collaborate with Maven Workflows, url='https://www.mavenbio.io/workflows'
		image Maven Workflows, url='https://www.mavenbio.io/_next/image?url=https%3A%2F%2Fmaven-bio-public.s3.us-east-1.amazonaws.com%2Fwebsite%2Fmaven_workflows.png&w=1080&q=75'
		separator, orientation='horizontal'
		image
		heading Maven Atlas
		paragraph
			StaticText Accelerate your research with hundreds of interactive indication landscapes. Generate custom landscapes, on demand, when an indication of interest is not available in the pre-built Atlas
		link Research with Maven Atlas, url='https://www.mavenbio.io/atlas'
		image Maven Atlas, url='https://www.mavenbio.io/_next/image?url=https%3A%2F%2Fmaven-bio-public.s3.us-east-1.amazonaws.com%2Fwebsite%2Fmaven_atlas.png&w=1080&q=75'
		separator, orientation='horizontal'
		image
		heading Maven Compass
		paragraph
			StaticText Create precise lists of companies, drugs, trials, and documents via natural language search. Use dozens of filters to refine your results.
		link Search with Maven Compass, url='https://www.mavenbio.io/compass'
		image Maven Compass, url='https://www.mavenbio.io/_next/image?url=https%3A%2F%2Fmaven-bio-public.s3.us-east-1.amazonaws.com%2Fwebsite%2Fmaven_compass.png&w=1080&q=75'
		separator, orientation='horizontal'
		image
		heading Maven Assistant
		paragraph
			StaticText Get instant answers to BioPharma questions, with direct links to primary sources. Answers grounded in the latest information from Maven Bio's curated database of BioPharma industry knowledge.
		link Get clarity with Maven Assistant, url='https://www.mavenbio.io/assistant'
		image Maven Assistant, url='https://www.mavenbio.io/_next/image?url=https%3A%2F%2Fmaven-bio-public.s3.us-east-1.amazonaws.com%2Fwebsite%2Fmaven_assistant.png&w=1080&q=75'
		image
		heading Unlock purpose-built AI research for your team
		paragraph
			StaticText Stop burning hours on manual data hunts — let Maven Bio do the heavy lifting so you can focus on the strategic decisions that drive your business forward.
		link Schedule a Demo, url='https://cal.com/team/maven-bio/intro'
	contentinfo
		image, url='https://www.mavenbio.io/logo_horizontal.svg'
		link, url='https://www.linkedin.com/company/mavenbio'
			image, url='https://www.mavenbio.io/linkedin.svg'
		navigation
			paragraph
				StaticText Platform
			link Maven Workflows, url='https://www.mavenbio.io/workflows'
			link Maven Atlas, url='https://www.mavenbio.io/atlas'
			link Maven Compass, url='https://www.mavenbio.io/compass'
			link Maven Assistant, url='https://www.mavenbio.io/assistant'
			paragraph
				StaticText Resources
			link Research, url='https://www.mavenbio.io/research/page/1'
			link Changelog, url='https://www.mavenbio.io/changelog'
			link Privacy Policy, url='https://www.mavenbio.io/privacy'
			link Terms of Service, url='https://www.mavenbio.io/terms'
		separator, orientation='horizontal'
		paragraph
			StaticText © Copyright
			StaticText 2025
			StaticText . All rights reserved.
	alert, atomic
```
</details>



```
RootWebArea Maven Bio, focused, url='https://www.mavenbio.io/'
	menu Platform, focused, orientation='vertical'
		[209] link Workflows, center=(1045,93), url='https://www.mavenbio.io/workflows'
		[211] link Atlas, center=(1045,141), url='https://www.mavenbio.io/atlas'
		[213] link Compass, center=(1045,189), url='https://www.mavenbio.io/compass'
```
<details><summary>Show more</summary>

```
		[215] link Assistant, center=(1045,237), url='https://www.mavenbio.io/assistant'
```
</details>

**Reasoning for action:** I clicked on the Platform button to access the dropdown menu, as this is the first step towards finding the Workflows link that I need to select. The dropdown will provide various options that include the Workflows, which will help me continue towards scheduling the demo.

**Action:** click(68) # Click on the Platform button to explore the dropdown menu.

**Change Description:** The Platform button was clicked, which expanded a vertical dropdown menu displaying links to Workflows, Atlas, Compass, and Assistant, allowing the user to explore these sections directly.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://www.mavenbio.io/

https://www.mavenbio.io/workflows

**Content (before/after):** 

```
RootWebArea Maven Bio, focused, url='https://www.mavenbio.io/'
	menu Platform, focused, orientation='vertical'
		[209] link Workflows, center=(1045,93), url='https://www.mavenbio.io/workflows'
		[211] link Atlas, center=(1045,141), url='https://www.mavenbio.io/atlas'
		[213] link Compass, center=(1045,189), url='https://www.mavenbio.io/compass'
```
<details><summary>Show more</summary>

```
		[215] link Assistant, center=(1045,237), url='https://www.mavenbio.io/assistant'
```
</details>



```
RootWebArea Maven Bio, focused, url='https://www.mavenbio.io/workflows'
	alert, atomic
	banner
		navigation
			[248] link Home, center=(457,54), url='https://www.mavenbio.io/'
```
<details><summary>Show more</summary>

```
				image, url='https://www.mavenbio.io/logo_horizontal.svg'
			[253] button Platform, center=(1045,54), expanded=False, hasPopup='menu', type=button
				paragraph
				image
			[257] link Research, center=(1166,54), url='https://www.mavenbio.io/research/page/1'
			[259] link Pricing, center=(1266,54), url='https://www.mavenbio.io/pricing'
			[265] link Sign in, center=(1370,54), url='https://auth.mavenbio.io/'
			[266] link Book a demo, center=(1499,54), url='https://cal.com/team/maven-bio/intro'
	main
		image
		StaticText Maven Workflows
		heading AI-Driven Workflows for Rapid BioPharma Research
		paragraph
			StaticText Monitor Maven’s AI as it completes structured research tasks—step by step—in minutes. Observe progress in real time, intervene if needed, and finalize results with confidence.
		paragraph
			StaticText Maven Workflows leverage domain-expert-defined work plans to guide each stage of research. Users can review inputs and outputs at every step, intervene to refine data, and seamlessly collaborate with the agent to drastically shorten timelines. For instance, our Clinical Data Explorer rapidly collects and standardizes trial data across multiple assets.
		[279] link Schedule Demo, center=(492,705), url='https://cal.com/team/maven-bio/intro'
		separator, orientation='horizontal'
		image
		heading Maven Workflows
		paragraph
			StaticText Collaborate directly with Maven's AI as it completes defined research tasks for you, in minutes. For example, our clinical data explorer workflow rapidly pulls together and standardizes clinical trial data for multiple assets.
		image Maven Workflows, url='https://www.mavenbio.io/_next/image?url=https%3A%2F%2Fmaven-bio-public.s3.us-east-1.amazonaws.com%2Fwebsite%2Fmaven_workflows.png&w=640&q=75'
		image
		heading Unlock purpose-built AI research for your team
		paragraph
			StaticText Stop burning hours on manual data hunts — let Maven Bio do the heavy lifting so you can focus on the strategic decisions that drive your business forward.
		link Schedule a Demo, url='https://cal.com/team/maven-bio/intro'
	contentinfo
		image, url='https://www.mavenbio.io/logo_horizontal.svg'
		link, url='https://www.linkedin.com/company/mavenbio'
			image, url='https://www.mavenbio.io/linkedin.svg'
		navigation
			paragraph
				StaticText Platform
			link Maven Workflows, url='https://www.mavenbio.io/workflows'
			link Maven Atlas, url='https://www.mavenbio.io/atlas'
			link Maven Compass, url='https://www.mavenbio.io/compass'
			link Maven Assistant, url='https://www.mavenbio.io/assistant'
			paragraph
				StaticText Resources
			link Research, url='https://www.mavenbio.io/research/page/1'
			link Changelog, url='https://www.mavenbio.io/changelog'
			link Privacy Policy, url='https://www.mavenbio.io/privacy'
			link Terms of Service, url='https://www.mavenbio.io/terms'
		separator, orientation='horizontal'
		paragraph
			StaticText © Copyright
			StaticText 2025
			StaticText . All rights reserved.
```
</details>

**Reasoning for action:** By clicking on the Workflows link, I am accessing the area of the platform dedicated to explaining Maven Bio's workflows. This is a necessary step to explore the functionality of the workflows and subsequently to find the option to schedule a demo.

**Action:** click(209) # Click on the Workflows link to explore that section.

**Change Description:** The browser navigated from the main page of Maven Bio to the Workflows section, updating the URL to 'https://www.mavenbio.io/workflows' and displaying new content related to AI-driven workflows for biopharma research, including headings, paragraphs, and links specific to workflow functionalities.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://www.mavenbio.io/workflows

https://cal.com/team/maven-bio/intro?date=2025-01-13&month=2025-01

**Content (before/after):** 

```
RootWebArea Maven Bio, focused, url='https://www.mavenbio.io/workflows'
	alert, atomic
	banner
		navigation
			[248] link Home, center=(457,54), url='https://www.mavenbio.io/'
```
<details><summary>Show more</summary>

```
				image, url='https://www.mavenbio.io/logo_horizontal.svg'
			[253] button Platform, center=(1045,54), expanded=False, hasPopup='menu', type=button
				paragraph
				image
			[257] link Research, center=(1166,54), url='https://www.mavenbio.io/research/page/1'
			[259] link Pricing, center=(1266,54), url='https://www.mavenbio.io/pricing'
			[265] link Sign in, center=(1370,54), url='https://auth.mavenbio.io/'
			[266] link Book a demo, center=(1499,54), url='https://cal.com/team/maven-bio/intro'
	main
		image
		StaticText Maven Workflows
		heading AI-Driven Workflows for Rapid BioPharma Research
		paragraph
			StaticText Monitor Maven’s AI as it completes structured research tasks—step by step—in minutes. Observe progress in real time, intervene if needed, and finalize results with confidence.
		paragraph
			StaticText Maven Workflows leverage domain-expert-defined work plans to guide each stage of research. Users can review inputs and outputs at every step, intervene to refine data, and seamlessly collaborate with the agent to drastically shorten timelines. For instance, our Clinical Data Explorer rapidly collects and standardizes trial data across multiple assets.
		[279] link Schedule Demo, center=(492,705), url='https://cal.com/team/maven-bio/intro'
		separator, orientation='horizontal'
		image
		heading Maven Workflows
		paragraph
			StaticText Collaborate directly with Maven's AI as it completes defined research tasks for you, in minutes. For example, our clinical data explorer workflow rapidly pulls together and standardizes clinical trial data for multiple assets.
		image Maven Workflows, url='https://www.mavenbio.io/_next/image?url=https%3A%2F%2Fmaven-bio-public.s3.us-east-1.amazonaws.com%2Fwebsite%2Fmaven_workflows.png&w=640&q=75'
		image
		heading Unlock purpose-built AI research for your team
		paragraph
			StaticText Stop burning hours on manual data hunts — let Maven Bio do the heavy lifting so you can focus on the strategic decisions that drive your business forward.
		link Schedule a Demo, url='https://cal.com/team/maven-bio/intro'
	contentinfo
		image, url='https://www.mavenbio.io/logo_horizontal.svg'
		link, url='https://www.linkedin.com/company/mavenbio'
			image, url='https://www.mavenbio.io/linkedin.svg'
		navigation
			paragraph
				StaticText Platform
			link Maven Workflows, url='https://www.mavenbio.io/workflows'
			link Maven Atlas, url='https://www.mavenbio.io/atlas'
			link Maven Compass, url='https://www.mavenbio.io/compass'
			link Maven Assistant, url='https://www.mavenbio.io/assistant'
			paragraph
				StaticText Resources
			link Research, url='https://www.mavenbio.io/research/page/1'
			link Changelog, url='https://www.mavenbio.io/changelog'
			link Privacy Policy, url='https://www.mavenbio.io/privacy'
			link Terms of Service, url='https://www.mavenbio.io/terms'
		separator, orientation='horizontal'
		paragraph
			StaticText © Copyright
			StaticText 2025
			StaticText . All rights reserved.
```
</details>



```
RootWebArea Maven Bio Intro | Maven Bio, focused, url='https://cal.com/team/maven-bio/intro?date=2025-01-13&month=2025-01'
	image
	main
		[95] switch Overlay my calendar, center=(1585,34), checked='false', type=button
		LabelText
```
<details><summary>Show more</summary>

```
			StaticText Overlay my calendar
		group
			[99] radio $Switch to monthly view, center=(1795,34), checked='true', type=button
			[103] radio $Switch to weekly view, center=(1837,34), checked='false', type=button
			[107] radio $Switch to column view, center=(1879,34), checked='false', type=button
		list
			listitem
				[117] link Maven Bio, center=(477,332), url='https://cal.com/team/maven-bio'
					image Maven Bio, url='https://cal.com/api/avatar/40373cf6-412b-40ad-ac05-63e13d275885.png'
			listitem
				[121] link Arjun Murthy, center=(497,332), url='https://cal.com/amurthy?redirect=false'
					image Arjun Murthy, url='https://cal.com/api/avatar/ecf891f8-a755-4668-b361-77bec196e94b.png'
			listitem
				[125] link Michael Brady, center=(517,332), url='https://cal.com/mwbrady?redirect=false'
					image Michael Brady, url='https://cal.com/api/avatar/dc992ae2-8238-43fb-8b89-e6a460423a73.png'
		paragraph
			StaticText Maven Bio
		heading Maven Bio Intro
		paragraph
			StaticText Maven Bio is the AI Platform for BioPharma Knowledge Work
		StaticText 30m
		generic
		StaticText Select...
		[152] combobox Timezone Select, center=(491,550), autocomplete=off, contenteditable=True, expanded=False, hasPopup='menu', type=text
		[141] svg, center=(473,550)
		strong
			StaticText January
		[160] svg, center=(560,550)
		StaticText 2025
		[169] button View previous month, center=(1126,326), type=button
		[171] button View next month, center=(1162,326), type=button
		StaticText SUN
		StaticText MON
		StaticText TUE
		StaticText WED
		StaticText THU
		StaticText FRI
		StaticText SAT
		button 1, disabled=True
		button 2, disabled=True
		button 3, disabled=True
		button 4, disabled=True
		button 5, disabled=True
		button 6, disabled=True
		button 7, disabled=True
		button 8, disabled=True
		button 9, disabled=True
		button 10, disabled=True
		button 11 today, disabled=True
		button 12, disabled=True
		button 13
		button 14
		button 15
		button 16
		button 17
		button 18, disabled=True
		button 19, disabled=True
		button 20
		button 21
		button 22
		button 23
		button 24
		button 25, disabled=True
		button 26, disabled=True
		button 27
		button 28
		button 29
		button 30
		button 31
		StaticText Mon
		StaticText 13
		group
			radio 12h, checked='true'
			radio 24h, checked='false'
		button 1:30pm
		button 2:00pm
		button 7:30pm
		button 8:00pm
		button 8:30pm
		button 9:00pm
		button 9:30pm
		button 10:00pm
		button 10:30pm
	alert, atomic
```
</details>

**Reasoning for action:** Since the user is attempting to schedule a demo to evaluate Maven Bio's capabilities, clicking on the 'Schedule Demo' link is necessary for moving forward. This action directly leads me to the demo scheduling interface as specified in the user's task, allowing for the next step of selecting available dates and times, thereby furthering the user's goal of assessing Maven Bio's AI-driven tools.

**Action:** click(279) # Click on the Schedule Demo link to explore the demo scheduling options.

**Change Description:** After clicking the 'Schedule Demo' link, the browser navigated to the demo scheduling interface, displaying the 'Maven Bio Intro' page with options to select a date and time for scheduling a demo, including the current month and available time slots, while also presenting a calendar view.

**Screenshot before:****Screenshot after:**---

