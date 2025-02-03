# Task

**User Engagement with Pricing and Demo Features**

As a potential client,
I learn about pricing options and request a demo for Roundtable's services,
so that I can understand the value of the service and how it can meet my business needs.

**Success definition:** Given I am on the Roundtable website and I am curious about their offerings
When I click on the 'About' link and then navigate to the 'Pricing' link and finally click on 'Book a demo'
Then I should see the pricing details for Roundtable's services and be taken to a demo request form where I can enter my contact information and service details.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://roundtable.ai/

https://roundtable.ai/about

**Content (before/after):** 

```
RootWebArea Roundtable: Survey Data Cleaning and Fraud Prevention, focused, url='https://roundtable.ai/'
	[37] link Improving Market Research Data Quality with Human-in-the-Loop AI: Read the Whitepaper An arrow point up to the right, center=(960,27), inner_text=Improving Market Research Data Quality with Human-in-the-Loop AI: Read the Whitepaper, url='https://www.directionsgroup.com/whitepapers/improving-market-research-data-quality-with-human-in-the-loop-ai'
		strong
			StaticText Improving Market Research Data Quality with Human-in-the-Loop AI: Read the Whitepaper
		image An arrow point up to the right, url='https://roundtable.ai/images/arrow-up-right-white.svg'
```
<details><summary>Show more</summary>

```
	banner
		[48] link home, center=(448,106), url='https://roundtable.ai/'
			image Roundtable logo with text., url='https://roundtable.ai/images/logo-with-text.svg'
		navigation
			[51] link About, center=(751,106), url='https://roundtable.ai/about'
			[53] link Pricing, center=(839,106), url='https://roundtable.ai/pricing'
			[55] link Developers, center=(946,106), url='https://docs.roundtable.ai/'
			[56] link Integrations, center=(1072,106), url='https://docs.roundtable.ai/forsta'
		[58] link Sign in, center=(1400,106), url='https://app.roundtable.ai/sign-in'
		[59] link Book a demo, center=(1503,106), url='https://roundtable.ai/survey/17069cabff43d1038521d294a0837cb32e76bb39'
	heading Roundtable cleans your survey data.
	heading Easy-to-integrate API for cleaning open-ended survey responses — save 70% of your time.
	[96] link Book a demo, center=(522,546), url='https://roundtable.ai/survey/17069cabff43d1038521d294a0837cb32e76bb39'
	image A black checkmark in a circle., url='https://roundtable.ai/images/circle-check-2.svg'
	StaticText 5M+ open-ends analyzed
	image A black checkmark in a circle., url='https://roundtable.ai/images/circle-check-2.svg'
	StaticText 10K+ hours saved
	StaticText How is the packaging?
	StaticText not sure
	image An arrow pointing right., url='https://roundtable.ai/images/arrow-narrow-right-gray.svg'
	image A red explanation point in a circle., url='https://roundtable.ai/images/exclamation-circle-red.svg'
	StaticText Low-effort
	StaticText What do you remember from the ad?
	StaticText The setting (home for the holidays) and the music.
	image An arrow pointing right., url='https://roundtable.ai/images/arrow-narrow-right-gray.svg'
	image A green checkmark in a circle., url='https://roundtable.ai/images/circle-check-green.svg'
	StaticText All checks passed
	StaticText What do you like about NYC?
	StaticText really like the food, the people, and the energy
	image An arrow pointing right., url='https://roundtable.ai/images/arrow-narrow-right-gray.svg'
	image A red explanation point in a circle., url='https://roundtable.ai/images/exclamation-circle-red.svg'
	StaticText Duplicate response
	StaticText What do you like about Miami?
	StaticText I really like the food, the people, and the energy
	image An arrow pointing right., url='https://roundtable.ai/images/arrow-narrow-right-gray.svg'
	image A red explanation point in a circle., url='https://roundtable.ai/images/exclamation-circle-red.svg'
	StaticText Response pasted
	StaticText How was sign-in experience?
	StaticText I thought it was ok
	image An arrow pointing right., url='https://roundtable.ai/images/arrow-narrow-right-gray.svg'
	image A green checkmark in a circle., url='https://roundtable.ai/images/circle-check-green.svg'
	StaticText All checks passed
	StaticText What's your ideal workspace?
	StaticText As a large language model, I do not have a preference.
	image An arrow pointing right., url='https://roundtable.ai/images/arrow-narrow-right-gray.svg'
	image A red explanation point in a circle., url='https://roundtable.ai/images/exclamation-circle-red.svg'
	StaticText GPT detected
	StaticText Describe your ideal vacation.
	StaticText one a look for times
	image An arrow pointing right., url='https://roundtable.ai/images/arrow-narrow-right-gray.svg'
	image A red explanation point in a circle., url='https://roundtable.ai/images/exclamation-circle-red.svg'
	StaticText Gibberish
	StaticText How do you choose jeans?
	StaticText I only buy levis but I always wait for a sale
	image An arrow pointing right., url='https://roundtable.ai/images/arrow-narrow-right-gray.svg'
	image A green checkmark in a circle., url='https://roundtable.ai/images/circle-check-green.svg'
	StaticText All checks passed
	StaticText What do you think of the ad?
	StaticText every day I wake up i eat a bowl of oatmeal
	image An arrow pointing right., url='https://roundtable.ai/images/arrow-narrow-right-gray.svg'
	image A red explanation point in a circle., url='https://roundtable.ai/images/exclamation-circle-red.svg'
	StaticText Off-topic
	StaticText Trusted by leaders in 25+ global markets
	image Logo for JD Power, url='https://roundtable.ai/images/jdpower-bw.svg'
	image Logo for The Directions Group, url='https://roundtable.ai/images/directions-bw.svg'
	image Logo for KJT, url='https://roundtable.ai/images/kjt-bw.svg'
	image Logo for Obsurvant, url='https://roundtable.ai/images/obsurvant-bw.svg'
	image Logo for Respondent, url='https://roundtable.ai/images/respondent-bw.svg'
	StaticText Features
	heading Why choose Roundtable?
	paragraph
		StaticText AI-assisted data cleaning saves hours of manual work.
	heading Easy-to-integrate API
	heading Get started in less than 60 seconds.
	code
		StaticText 1
		StaticText curl --request POST \
		StaticText 2
		StaticText --url https://roundtable.ai/api/alias/v014 \
		StaticText 3
		StaticText --header 'Content-Type: application/json' \
		StaticText 4
		StaticText --header 'api_key: <api_key>' \
		StaticText 5
		StaticText --data '{
		StaticText 6
		StaticText "participant_id"
		StaticText :
		StaticText "participant_123"
		StaticText ,
		StaticText 7
		StaticText "questions"
		StaticText : {
		StaticText 8
		StaticText "Q1"
		StaticText :
		StaticText "Tell me about yourself"
		StaticText 9
		StaticText },
		StaticText 10
		StaticText "responses"
		StaticText : {
		StaticText 11
		StaticText "Q1"
		StaticText :
		StaticText "I like to code."
		StaticText 12
		StaticText },
		StaticText 13
		StaticText "survey_id"
		StaticText :
		StaticText "survey_456"
		StaticText 14
		StaticText }'
	heading Real-time behavioral tracking
	heading Detect unnatural typing and programmatic entries.
	image An example graph of typing behavior., url='https://roundtable.ai/images/typing-plot-v2.jpg'
	heading Multilingual functionality
	heading Deploy your study to any major market or population.
	StaticText 中文
	StaticText العربية
	StaticText English
	StaticText Bahasa Indonesia
	StaticText Français
	StaticText 日本語
	StaticText Русский
	StaticText Deutsch
	StaticText Português
	StaticText 한국어
	StaticText Español
	StaticText हिंदी
	StaticText Italiano
	heading GPT detection
	heading Identify bots and participants using ChatGPT and other LLMs.
	StaticText How do you choose a shampoo?
	StaticText Choosing a shampoo can depend on various factors, including hair type, hair needs, and ingredients.
	image An arrow pointing down., url='https://roundtable.ai/images/arrow-narrow-down.svg'
	image A red explanation point in a circle., url='https://roundtable.ai/images/exclamation-circle-red.svg'
	StaticText GPT detected
	heading Dynamic clustering
	heading Identify and group duplicate responses across multiple participants.
	StaticText The name has a nice ring to it
	StaticText Th name has a nice ring to it
	StaticText Group 1
	StaticText Group 2
	StaticText It conveys innovation and quality
	StaticText It conveys quality and innovation
	StaticText Conveys quality and innovation
	StaticText Customers
	heading Better quality, less time.
	heading Leaders and innovators use Roundtable to improve their data quality.
	image Photo of Sebastian Sciarra, url='https://roundtable.ai/images/sebastian.jpeg'
	StaticText "Automated verbatim reviews are far more effective and far more efficient (estimated 85% reduction in labor hours). We also gain initial insights into sources of low-quality and fraudulent data."
	StaticText Sebastian Sciarra, PhD
	StaticText Data Scientist at JD Power
	StaticText "We have the confidence in the tool that if something is not flagged, then we don't have to spend time poring over those open end responses and can focus on our attention on fewer open ends that have suspicious markers. In some cases this can save us up to 66% of time spent checking open ends."
	image A man smiling in a blue shirt., url='https://roundtable.ai/images/mike-herrel.jpeg'
	StaticText Michael Herrel
	StaticText Director of Data at The Directions Group
	StaticText "Our commitment to data quality has been integral to our growth since day one. Integrating Roundtable with our tech is an additional step to ensure the accuracy of our results, preserving the integrity of our research and allowing us to provide our clients with reliable human-generated insights."
	image A photo of a man smiling in black and white., url='https://roundtable.ai/images/alex-morrison_1.jpeg'
	StaticText Alex Morrison
	StaticText Co-Founder at Obsurvant
	StaticText "The main benefit is understanding the nuance in open response screening questions that we would otherwise rely on our end users to make decisions on. This reduces the friction on them, allowing our researcher customers to move more fluently through our experience."
	image Photo of Matt Bennet, url='https://roundtable.ai/images/matt-bennet.jpg'
	StaticText Matthew Bennett
	StaticText Head of Product at Respondent
	StaticText "Roundtable helps us be more objective around a pretty difficult area. We spend less time examining the quality of data that is good and more time around the questionable data. If I can spend 2 more hours delivering better quality research for a client and offset that with 2 fewer hours reviewing open-ended data, I’m all for it."
	image Photo of Dan Wasserman, url='https://roundtable.ai/images/dan-wasserman-p-500.jpg'
	StaticText Dan Wasserman
	StaticText Chief Operating Officer at KJT
	StaticText Solutions
	heading Save time. Save money.
	paragraph
		StaticText Embed Roundtable's API into your survey to get real-time markers of data quality.
	heading AI-Assisted Data Cleaning
	StaticText Manually analyzing every open-end is tedious. Let Roundtable flag the suspicious responses for you to review.
	link About us A black arrow facing up and to the right., url='https://roundtable.ai/about'
		image A black arrow facing up and to the right., url='https://roundtable.ai/images/arrow-up-right.svg'
	image A diagram of Roundtable's data cleaning service., url='https://roundtable.ai/images/csv-p-500.png'
	heading Programmatic Pre-Screening
	StaticText Define customized thresholds to auto-reject low quality participants from completing your study.
	link Documentation A black arrow facing up and to the right., url='https://docs.roundtable.ai/'
		image A black arrow facing up and to the right., url='https://roundtable.ai/images/arrow-up-right.svg'
	image A diagram of Roundtable's pre-screening service., url='https://roundtable.ai/images/screener-p-500.png'
	heading Response Quality Dashboard
	StaticText Real-time tracking across all your sample populations, ensuring high-quality data throughout.
	link Book a demo A black arrow facing up and to the right., url='https://roundtable.ai/survey/17069cabff43d1038521d294a0837cb32e76bb39'
		image A black arrow facing up and to the right., url='https://roundtable.ai/images/arrow-up-right.svg'
	image An illustration of the Roundtable dashboard., url='https://roundtable.ai/images/dashboard-p-500.png'
	heading Join the Roundtable community today
		strong
			emphasis
		strong
		strong
	link Book a demo, url='https://roundtable.ai/survey/17069cabff43d1038521d294a0837cb32e76bb39'
	image Roundtable logo with text., url='https://roundtable.ai/images/logo-with-text.svg'
	paragraph
		StaticText 228 Park Avenue S
		StaticText New York, NY 10003
	StaticText PRODUCT
	link Pricing, url='https://roundtable.ai/pricing'
	link Documentation, url='https://docs.roundtable.ai/introduction'
	link Status, url='https://status.roundtable.ai/'
	StaticText COMPANY
	link About, url='https://roundtable.ai/about'
	link Blog, url='https://roundtable.ai/blog'
	link Contact, url='mailto:support@roundtable.ai'
	StaticText INTEGRATIONS
	link Forsta, url='https://docs.roundtable.ai/forsta'
	link Qualtrics, url='https://docs.roundtable.ai/qualtrics'
	link jsPsych, url='https://docs.roundtable.ai/jspsych'
	StaticText LEGAL
	link Terms, url='https://app.roundtable.ai/terms'
	link Privacy, url='https://app.roundtable.ai/privacy'
	StaticText Roundtable © 2024
	link A logo icon for X., url='https://x.com/RoundtableDotAI'
		image A logo icon for X., url='https://roundtable.ai/images/brand-x.svg'
	link A logo icon for LinkedIn., url='https://www.linkedin.com/company/roundtable-ai'
		image A logo icon for LinkedIn., url='https://roundtable.ai/images/brand-linkedin.svg'
	[692] button Open chat window, center=(1868,1028), title=Open chat window
		image
```
</details>



```
RootWebArea About Roundtable - API for Survey Data Cleaning, focused, url='https://roundtable.ai/about'
	banner
		[40] link home, center=(448,52), url='https://roundtable.ai/'
			image Roundtable logo with text., url='https://roundtable.ai/images/logo-with-text.svg'
		navigation
```
<details><summary>Show more</summary>

```
			[43] link About, center=(751,52), url='https://roundtable.ai/about'
			[45] link Pricing, center=(839,52), url='https://roundtable.ai/pricing'
			[47] link Developers, center=(946,52), url='https://docs.roundtable.ai/'
			[48] link Integrations, center=(1072,52), url='https://docs.roundtable.ai/forsta'
		[50] link Sign in, center=(1400,52), url='https://app.roundtable.ai/sign-in'
		[51] link Book a demo, center=(1503,52), url='https://roundtable.ai/survey/17069cabff43d1038521d294a0837cb32e76bb39'
	heading Building the infrastructure for market researchers.
	[91] link Y Combinator logo, center=(485,400), url='https://www.ycombinator.com/'
		image Y Combinator logo, url='https://roundtable.ai/images/1200px-Y_Combinator_logo.svg-p-500.png'
	[93] link Logo of Brickyard Ventures, center=(577,400), url='https://www.justlaybrick.com/'
		image Logo of Brickyard Ventures, url='https://roundtable.ai/images/brickyard_altlogo_black-1-p-500.png'
	[95] link Princeton logo, center=(663,400), url='https://www.princeton.edu/'
		image Princeton logo, url='https://roundtable.ai/images/Princeton_seal.svg'
	StaticText Our story began out of a need to streamline data cleaning in market research. Roundtable's AI-powered API automates the analysis of open-end responses, saving researchers countless hours of manual work.
	StaticText ‍
	StaticText Founded in 2023 by two Princeton PhDs and backed by Y Combinator and Brickyard Ventures, Roundtable is harnessing the power of AI to revolutionize market research. Join the Roundtable community and help shape the future.
	StaticText Testimonials
	heading Built for high-performance teams.
	image A photo of a man smiling., url='https://roundtable.ai/images/matt-patterson-p-500.jpeg'
	image Brickyard Ventures logo, url='https://roundtable.ai/images/brickyard-p-500.png'
	paragraph
		StaticText The more we dug into the market research industry, we became stunned at how rampant fraud and manipulation of data and surveys were. In addition, we were equally surprised at how little, if any, real solutions there were in the market. This, coupled with the founders' ability and passion to bring trust and transparency in this space, we knew we wanted to join the team at Roundtable.
	StaticText Matt Patterson
	StaticText |
	StaticText General Partner at Brickyard Ventures
	image Logo for Common Sense Machines, url='https://roundtable.ai/images/csm-logo.svg'
	paragraph
		StaticText We know that high-quality data is often the key input for decision-making. However, reaching deep consumer insights from online surveys is still a major challenge because the data is noisy and inaccurate at best. Roundtable’s AI-based solution is the only one out there for scalable, trustworthy data acquisition.
	StaticText Max Kleiman-Weiner
	StaticText |
	StaticText Chief Scientist at Common Sense Machines
	image A man in a suit smiling., url='https://roundtable.ai/images/max-kw_1.png'
	StaticText Careers
	StaticText Our story is still being written, and we're excited to see what the future holds. Join us on this journey, and together let's redefine what it means to conduct market research.
	image A photo of a modern officespace., url='https://roundtable.ai/images/office.png'
	strong
		StaticText No openings at this time.
	image Roundtable logo with text., url='https://roundtable.ai/images/logo-with-text.svg'
	paragraph
		StaticText 228 Park Avenue S
		StaticText New York, NY 10003
	StaticText PRODUCT
	link Pricing, url='https://roundtable.ai/pricing'
	link Documentation, url='https://docs.roundtable.ai/introduction'
	link Status, url='https://status.roundtable.ai/'
	StaticText COMPANY
	link About, url='https://roundtable.ai/about'
	link Blog, url='https://roundtable.ai/blog'
	link Contact, url='mailto:support@roundtable.ai'
	StaticText INTEGRATIONS
	link Forsta, url='https://docs.roundtable.ai/forsta'
	link Qualtrics, url='https://docs.roundtable.ai/qualtrics'
	link jsPsych, url='https://docs.roundtable.ai/jspsych'
	StaticText LEGAL
	link Terms, url='https://app.roundtable.ai/terms'
	link Privacy, url='https://app.roundtable.ai/privacy'
	StaticText Roundtable © 2024
	link A logo icon for X., url='https://x.com/RoundtableDotAI'
		image A logo icon for X., url='https://roundtable.ai/images/brand-x.svg'
	link A logo icon for LinkedIn., url='https://www.linkedin.com/company/roundtable-ai'
		image A logo icon for LinkedIn., url='https://roundtable.ai/images/brand-linkedin.svg'
	[210] button Open chat window, center=(1868,1028), title=Open chat window
		image
```
</details>

**Reasoning for action:** I chose to click on the 'About' link first because the user story specifies the need to learn about the offerings provided by Roundtable. Understanding the company's background and approach will help identify how their services align with my business needs. This initial step is crucial to setting up further actions, specifically the navigation to pricing and ultimately requesting a demo.

**Action:** click('51') # Click on the 'About' link to explore more about the company.

**Change Description:** The browser navigated from the 'Roundtable: Survey Data Cleaning and Fraud Prevention' homepage to the 'About Roundtable' page, revealing information about the company's background, founders, and mission, as well as various testimonials, while updating the URL to 'https://roundtable.ai/about'.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://roundtable.ai/about

https://roundtable.ai/pricing

**Content (before/after):** 

```
RootWebArea About Roundtable - API for Survey Data Cleaning, focused, url='https://roundtable.ai/about'
	banner
		[40] link home, center=(448,52), url='https://roundtable.ai/'
			image Roundtable logo with text., url='https://roundtable.ai/images/logo-with-text.svg'
		navigation
```
<details><summary>Show more</summary>

```
			[43] link About, center=(751,52), url='https://roundtable.ai/about'
			[45] link Pricing, center=(839,52), url='https://roundtable.ai/pricing'
			[47] link Developers, center=(946,52), url='https://docs.roundtable.ai/'
			[48] link Integrations, center=(1072,52), url='https://docs.roundtable.ai/forsta'
		[50] link Sign in, center=(1400,52), url='https://app.roundtable.ai/sign-in'
		[51] link Book a demo, center=(1503,52), url='https://roundtable.ai/survey/17069cabff43d1038521d294a0837cb32e76bb39'
	heading Building the infrastructure for market researchers.
	[91] link Y Combinator logo, center=(485,400), url='https://www.ycombinator.com/'
		image Y Combinator logo, url='https://roundtable.ai/images/1200px-Y_Combinator_logo.svg-p-500.png'
	[93] link Logo of Brickyard Ventures, center=(577,400), url='https://www.justlaybrick.com/'
		image Logo of Brickyard Ventures, url='https://roundtable.ai/images/brickyard_altlogo_black-1-p-500.png'
	[95] link Princeton logo, center=(663,400), url='https://www.princeton.edu/'
		image Princeton logo, url='https://roundtable.ai/images/Princeton_seal.svg'
	StaticText Our story began out of a need to streamline data cleaning in market research. Roundtable's AI-powered API automates the analysis of open-end responses, saving researchers countless hours of manual work.
	StaticText ‍
	StaticText Founded in 2023 by two Princeton PhDs and backed by Y Combinator and Brickyard Ventures, Roundtable is harnessing the power of AI to revolutionize market research. Join the Roundtable community and help shape the future.
	StaticText Testimonials
	heading Built for high-performance teams.
	image A photo of a man smiling., url='https://roundtable.ai/images/matt-patterson-p-500.jpeg'
	image Brickyard Ventures logo, url='https://roundtable.ai/images/brickyard-p-500.png'
	paragraph
		StaticText The more we dug into the market research industry, we became stunned at how rampant fraud and manipulation of data and surveys were. In addition, we were equally surprised at how little, if any, real solutions there were in the market. This, coupled with the founders' ability and passion to bring trust and transparency in this space, we knew we wanted to join the team at Roundtable.
	StaticText Matt Patterson
	StaticText |
	StaticText General Partner at Brickyard Ventures
	image Logo for Common Sense Machines, url='https://roundtable.ai/images/csm-logo.svg'
	paragraph
		StaticText We know that high-quality data is often the key input for decision-making. However, reaching deep consumer insights from online surveys is still a major challenge because the data is noisy and inaccurate at best. Roundtable’s AI-based solution is the only one out there for scalable, trustworthy data acquisition.
	StaticText Max Kleiman-Weiner
	StaticText |
	StaticText Chief Scientist at Common Sense Machines
	image A man in a suit smiling., url='https://roundtable.ai/images/max-kw_1.png'
	StaticText Careers
	StaticText Our story is still being written, and we're excited to see what the future holds. Join us on this journey, and together let's redefine what it means to conduct market research.
	image A photo of a modern officespace., url='https://roundtable.ai/images/office.png'
	strong
		StaticText No openings at this time.
	image Roundtable logo with text., url='https://roundtable.ai/images/logo-with-text.svg'
	paragraph
		StaticText 228 Park Avenue S
		StaticText New York, NY 10003
	StaticText PRODUCT
	link Pricing, url='https://roundtable.ai/pricing'
	link Documentation, url='https://docs.roundtable.ai/introduction'
	link Status, url='https://status.roundtable.ai/'
	StaticText COMPANY
	link About, url='https://roundtable.ai/about'
	link Blog, url='https://roundtable.ai/blog'
	link Contact, url='mailto:support@roundtable.ai'
	StaticText INTEGRATIONS
	link Forsta, url='https://docs.roundtable.ai/forsta'
	link Qualtrics, url='https://docs.roundtable.ai/qualtrics'
	link jsPsych, url='https://docs.roundtable.ai/jspsych'
	StaticText LEGAL
	link Terms, url='https://app.roundtable.ai/terms'
	link Privacy, url='https://app.roundtable.ai/privacy'
	StaticText Roundtable © 2024
	link A logo icon for X., url='https://x.com/RoundtableDotAI'
		image A logo icon for X., url='https://roundtable.ai/images/brand-x.svg'
	link A logo icon for LinkedIn., url='https://www.linkedin.com/company/roundtable-ai'
		image A logo icon for LinkedIn., url='https://roundtable.ai/images/brand-linkedin.svg'
	[210] button Open chat window, center=(1868,1028), title=Open chat window
		image
```
</details>



```
RootWebArea Roundtable Pricing - Start saving 70% of your data cleaning time today, focused, url='https://roundtable.ai/pricing'
	banner
		[40] link home, center=(448,52), url='https://roundtable.ai/'
			image Roundtable logo with text., url='https://roundtable.ai/images/logo-with-text.svg'
		navigation
```
<details><summary>Show more</summary>

```
			[43] link About, center=(751,52), url='https://roundtable.ai/about'
			[45] link Pricing, center=(839,52), url='https://roundtable.ai/pricing'
			[47] link Developers, center=(946,52), url='https://docs.roundtable.ai/'
			[48] link Integrations, center=(1072,52), url='https://docs.roundtable.ai/forsta'
		[50] link Sign in, center=(1400,52), url='https://app.roundtable.ai/sign-in'
		[51] link Book a demo, center=(1503,52), url='https://roundtable.ai/survey/17069cabff43d1038521d294a0837cb32e76bb39'
	heading Protect your data today.
	paragraph
		StaticText Automated data cleaning saves up to 70% of your time and protects you from fraudulent actors.
	[86] paragraph, center=(918,426), inner_text=Monthly
		StaticText Monthly
	[87] paragraph, center=(1002,426), inner_text=Yearly
		StaticText Yearly
	heading Essentials
	paragraph
		StaticText $140/mo ($0.14/participant)
	heading 1K participants
	StaticText / month
	[104] link Book a demo, center=(535,697), url='https://roundtable.ai/survey/17069cabff43d1038521d294a0837cb32e76bb39'
	paragraph
		StaticText What’s Included:
	image A checkmark icon., url='https://roundtable.ai/images/circle-check-3.svg'
	paragraph
		StaticText 6 questions per API call
	image A checkmark icon., url='https://roundtable.ai/images/circle-check-3.svg'
	paragraph
		StaticText Open-end analyses
	image A checkmark icon., url='https://roundtable.ai/images/circle-check-3.svg'
	paragraph
		StaticText Behavioral tracking
	image A checkmark icon., url='https://roundtable.ai/images/circle-check-3.svg'
	paragraph
		StaticText Device fingerprinting (coming soon)
	image A checkmark icon., url='https://roundtable.ai/images/circle-check-3.svg'
	paragraph
		StaticText Open-end coding (coming soon)
	StaticText Save 20%
	heading Scale
	paragraph
		StaticText $1,080/mo ($0.108/participant)
	heading 10K participants
	StaticText / month
	[133] link Book a demo, center=(960,697), url='https://roundtable.ai/survey/17069cabff43d1038521d294a0837cb32e76bb39'
	paragraph
		StaticText What’s Included:
	image
	paragraph
		StaticText Everything in
		strong
			StaticText Essentials
	image
	paragraph
		StaticText 99.9% uptime SLA guarantee
	image
	paragraph
		StaticText Priority email support
	image
	paragraph
		StaticText Dedicated point of contact
	image
	paragraph
		StaticText Dedicated support channel
	StaticText Save 20%
	heading Enterprise
	paragraph
		StaticText Custom pricing
	heading 10K+ participants
	StaticText / month
	[169] link Book a demo, center=(1385,697), url='https://roundtable.ai/survey/17069cabff43d1038521d294a0837cb32e76bb39'
	paragraph
		StaticText What’s Included:
	image A checkmark icon., url='https://roundtable.ai/images/circle-check-3.svg'
	paragraph
		StaticText Everything in
		strong
			StaticText Scale
	image A checkmark icon., url='https://roundtable.ai/images/circle-check-3.svg'
	paragraph
		StaticText 6+ questions per API call
	image A checkmark icon., url='https://roundtable.ai/images/circle-check-3.svg'
	paragraph
		StaticText Customized thresholds
	image A checkmark icon., url='https://roundtable.ai/images/circle-check-3.svg'
	paragraph
		StaticText Employee training and onboarding
	image A checkmark icon., url='https://roundtable.ai/images/circle-check-3.svg'
	paragraph
		StaticText Dedicated account manager
	StaticText "
	StaticText Roundtable is an excellent tool to use. It catches things I cannot. It also brings my attention to things I might catch, but makes it easier for me to see. Data quality is the most important part of our work. Nothing works if the data is not good."
	StaticText Stephen Lee
	StaticText |
	StaticText Senior Project Manager at Market Probe International
	StaticText FAQs
	heading Frequently Asked Questions
	StaticText How do I choose the right Roundtable plan?
	paragraph
		StaticText Roundtable plans are volume-based, with three tiers to accommodate different needs. Each API call represents one participant and supports up to six questions. Choose the plan that matches your participant volume.
	StaticText Is Roundtable SOC2 compliant?
	paragraph
		StaticText Yes! Roundtable is SOC2 compliant and deeply committed to ensuring the security and privacy of your data.
	StaticText Can I use Roundtable for free?
	paragraph
		StaticText We offer case-by-case discounts for academics with an accredited educational e-mail address. If this is you, please contact us at support@roundtable.ai.
	StaticText How does Roundtable estimate time savings?
	paragraph
		StaticText Customer feedback and product usage data indicates that customers save on average 70% of their time doing manual survey open-end checks. Time savings vary by customer.
	StaticText How does Roundtable balance false negatives versus positives?
	paragraph
		StaticText By design, we aim to minimize false negatives and have a moderate degree of false positives. Our recommended decision procedure for most clients is to accept any unflagged responses and review any flagged responses. For details on your specific use case, contact your dedicated support contact.
	heading More questions?
	link Contact sales, url='mailto:sales@roundtable.ai'
	image Roundtable logo with text., url='https://roundtable.ai/images/logo-with-text.svg'
	paragraph
		StaticText 228 Park Avenue S
		StaticText New York, NY 10003
	StaticText PRODUCT
	link Pricing, url='https://roundtable.ai/pricing'
	link Documentation, url='https://docs.roundtable.ai/introduction'
	link Status, url='https://status.roundtable.ai/'
	StaticText COMPANY
	link About, url='https://roundtable.ai/about'
	link Blog, url='https://roundtable.ai/blog'
	link Contact, url='mailto:support@roundtable.ai'
	StaticText INTEGRATIONS
	link Forsta, url='https://docs.roundtable.ai/forsta'
	link Qualtrics, url='https://docs.roundtable.ai/qualtrics'
	link jsPsych, url='https://docs.roundtable.ai/jspsych'
	StaticText LEGAL
	link Terms, url='https://app.roundtable.ai/terms'
	link Privacy, url='https://app.roundtable.ai/privacy'
	StaticText Roundtable © 2024
	link A logo icon for X., url='https://x.com/RoundtableDotAI'
		image A logo icon for X., url='https://roundtable.ai/images/brand-x.svg'
	link A logo icon for LinkedIn., url='https://www.linkedin.com/company/roundtable-ai'
		image A logo icon for LinkedIn., url='https://roundtable.ai/images/brand-linkedin.svg'
	[298] button Open chat window, center=(1868,1028), title=Open chat window
		image
```
</details>

**Reasoning for action:** By clicking the 'Pricing' link, I advance towards my goal of accessing the pricing details that the user is interested in. This step is crucial because it will provide me with the necessary information about Roundtable's services, which the user is keen to explore. Once on the pricing page, I can then proceed to the next action of requesting a demo.

**Action:** click('45') # Click on the 'Pricing' link to explore the pricing details.

**Change Description:** The browser navigated from the 'About' page to the 'Pricing' page, changing the title and URL of the page to reflect pricing options for Roundtable's services, which now prominently display subscription plans and their respective features.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://roundtable.ai/pricing

https://roundtable.ai/survey/17069cabff43d1038521d294a0837cb32e76bb39

**Content (before/after):** 

```
RootWebArea Roundtable Pricing - Start saving 70% of your data cleaning time today, focused, url='https://roundtable.ai/pricing'
	banner
		[40] link home, center=(448,52), url='https://roundtable.ai/'
			image Roundtable logo with text., url='https://roundtable.ai/images/logo-with-text.svg'
		navigation
```
<details><summary>Show more</summary>

```
			[43] link About, center=(751,52), url='https://roundtable.ai/about'
			[45] link Pricing, center=(839,52), url='https://roundtable.ai/pricing'
			[47] link Developers, center=(946,52), url='https://docs.roundtable.ai/'
			[48] link Integrations, center=(1072,52), url='https://docs.roundtable.ai/forsta'
		[50] link Sign in, center=(1400,52), url='https://app.roundtable.ai/sign-in'
		[51] link Book a demo, center=(1503,52), url='https://roundtable.ai/survey/17069cabff43d1038521d294a0837cb32e76bb39'
	heading Protect your data today.
	paragraph
		StaticText Automated data cleaning saves up to 70% of your time and protects you from fraudulent actors.
	[86] paragraph, center=(918,426), inner_text=Monthly
		StaticText Monthly
	[87] paragraph, center=(1002,426), inner_text=Yearly
		StaticText Yearly
	heading Essentials
	paragraph
		StaticText $140/mo ($0.14/participant)
	heading 1K participants
	StaticText / month
	[104] link Book a demo, center=(535,697), url='https://roundtable.ai/survey/17069cabff43d1038521d294a0837cb32e76bb39'
	paragraph
		StaticText What’s Included:
	image A checkmark icon., url='https://roundtable.ai/images/circle-check-3.svg'
	paragraph
		StaticText 6 questions per API call
	image A checkmark icon., url='https://roundtable.ai/images/circle-check-3.svg'
	paragraph
		StaticText Open-end analyses
	image A checkmark icon., url='https://roundtable.ai/images/circle-check-3.svg'
	paragraph
		StaticText Behavioral tracking
	image A checkmark icon., url='https://roundtable.ai/images/circle-check-3.svg'
	paragraph
		StaticText Device fingerprinting (coming soon)
	image A checkmark icon., url='https://roundtable.ai/images/circle-check-3.svg'
	paragraph
		StaticText Open-end coding (coming soon)
	StaticText Save 20%
	heading Scale
	paragraph
		StaticText $1,080/mo ($0.108/participant)
	heading 10K participants
	StaticText / month
	[133] link Book a demo, center=(960,697), url='https://roundtable.ai/survey/17069cabff43d1038521d294a0837cb32e76bb39'
	paragraph
		StaticText What’s Included:
	image
	paragraph
		StaticText Everything in
		strong
			StaticText Essentials
	image
	paragraph
		StaticText 99.9% uptime SLA guarantee
	image
	paragraph
		StaticText Priority email support
	image
	paragraph
		StaticText Dedicated point of contact
	image
	paragraph
		StaticText Dedicated support channel
	StaticText Save 20%
	heading Enterprise
	paragraph
		StaticText Custom pricing
	heading 10K+ participants
	StaticText / month
	[169] link Book a demo, center=(1385,697), url='https://roundtable.ai/survey/17069cabff43d1038521d294a0837cb32e76bb39'
	paragraph
		StaticText What’s Included:
	image A checkmark icon., url='https://roundtable.ai/images/circle-check-3.svg'
	paragraph
		StaticText Everything in
		strong
			StaticText Scale
	image A checkmark icon., url='https://roundtable.ai/images/circle-check-3.svg'
	paragraph
		StaticText 6+ questions per API call
	image A checkmark icon., url='https://roundtable.ai/images/circle-check-3.svg'
	paragraph
		StaticText Customized thresholds
	image A checkmark icon., url='https://roundtable.ai/images/circle-check-3.svg'
	paragraph
		StaticText Employee training and onboarding
	image A checkmark icon., url='https://roundtable.ai/images/circle-check-3.svg'
	paragraph
		StaticText Dedicated account manager
	StaticText "
	StaticText Roundtable is an excellent tool to use. It catches things I cannot. It also brings my attention to things I might catch, but makes it easier for me to see. Data quality is the most important part of our work. Nothing works if the data is not good."
	StaticText Stephen Lee
	StaticText |
	StaticText Senior Project Manager at Market Probe International
	StaticText FAQs
	heading Frequently Asked Questions
	StaticText How do I choose the right Roundtable plan?
	paragraph
		StaticText Roundtable plans are volume-based, with three tiers to accommodate different needs. Each API call represents one participant and supports up to six questions. Choose the plan that matches your participant volume.
	StaticText Is Roundtable SOC2 compliant?
	paragraph
		StaticText Yes! Roundtable is SOC2 compliant and deeply committed to ensuring the security and privacy of your data.
	StaticText Can I use Roundtable for free?
	paragraph
		StaticText We offer case-by-case discounts for academics with an accredited educational e-mail address. If this is you, please contact us at support@roundtable.ai.
	StaticText How does Roundtable estimate time savings?
	paragraph
		StaticText Customer feedback and product usage data indicates that customers save on average 70% of their time doing manual survey open-end checks. Time savings vary by customer.
	StaticText How does Roundtable balance false negatives versus positives?
	paragraph
		StaticText By design, we aim to minimize false negatives and have a moderate degree of false positives. Our recommended decision procedure for most clients is to accept any unflagged responses and review any flagged responses. For details on your specific use case, contact your dedicated support contact.
	heading More questions?
	link Contact sales, url='mailto:sales@roundtable.ai'
	image Roundtable logo with text., url='https://roundtable.ai/images/logo-with-text.svg'
	paragraph
		StaticText 228 Park Avenue S
		StaticText New York, NY 10003
	StaticText PRODUCT
	link Pricing, url='https://roundtable.ai/pricing'
	link Documentation, url='https://docs.roundtable.ai/introduction'
	link Status, url='https://status.roundtable.ai/'
	StaticText COMPANY
	link About, url='https://roundtable.ai/about'
	link Blog, url='https://roundtable.ai/blog'
	link Contact, url='mailto:support@roundtable.ai'
	StaticText INTEGRATIONS
	link Forsta, url='https://docs.roundtable.ai/forsta'
	link Qualtrics, url='https://docs.roundtable.ai/qualtrics'
	link jsPsych, url='https://docs.roundtable.ai/jspsych'
	StaticText LEGAL
	link Terms, url='https://app.roundtable.ai/terms'
	link Privacy, url='https://app.roundtable.ai/privacy'
	StaticText Roundtable © 2024
	link A logo icon for X., url='https://x.com/RoundtableDotAI'
		image A logo icon for X., url='https://roundtable.ai/images/brand-x.svg'
	link A logo icon for LinkedIn., url='https://www.linkedin.com/company/roundtable-ai'
		image A logo icon for LinkedIn., url='https://roundtable.ai/images/brand-linkedin.svg'
	[298] button Open chat window, center=(1868,1028), title=Open chat window
		image
```
</details>



```
RootWebArea Survey, focused, url='https://roundtable.ai/survey/17069cabff43d1038521d294a0837cb32e76bb39'
	image Roundtable Logo, url='https://roundtable.ai/images/logo-with-text.svg'
	paragraph
		StaticText Please fill out this form and a member of our sales team will contact you.
	LabelText
```
<details><summary>Show more</summary>

```
		StaticText Email
	[25] textbox Email, center=(960,230), contenteditable=True, required, type=text
	LabelText
		StaticText Name
	[32] textbox Name, center=(960,331), contenteditable=True, required, type=text
	LabelText
		StaticText Company
	[39] textbox Company, center=(960,432), contenteditable=True, required, type=text
	LabelText
		StaticText Role
	[46] textbox Role, center=(960,534), contenteditable=True, required, type=text
	LabelText
		StaticText What is your average participant volume per month?
	[53] textbox What is your average participant volume per month?, center=(960,635), contenteditable=True, required, type=text
	LabelText
		StaticText What % B2B vs B2C?
	[60] textbox What % B2B vs B2C?, center=(960,737), contenteditable=True, required, type=text
	LabelText
		StaticText How did you hear about us?
	[67] textbox How did you hear about us?, center=(960,838), contenteditable=True, type=text
	LabelText
		StaticText Additional comments
	[74] textbox Additional comments, center=(960,948), contenteditable=True
	StaticText Built with
	[80] link RoundtableJS, center=(1211,1056), url='https://docs.roundtable.ai/rjs/introduction'
	[82] button Next, center=(715,1045)
```
</details>

**Reasoning for action:** By clicking the 'Book a demo' link, I am initiating the process to request a demo for Roundtable's services. This action directly fulfills the user's goal of understanding the value of the service, as it will lead me to a form where I can provide my contact information and select the relevant services. This step is crucial in progressing towards the acceptance test criteria, which requires me to land on the demo request form.

**Action:** click('51') # Click on the 'Book a demo' link to explore demo options.

**Change Description:** After clicking the 'Book a demo' link, the browser moved from the pricing page to a survey form page where users can provide their details for a demo request, including fields for email, name, company, role, participant volume, B2B vs B2C percentage, and additional comments.

**Screenshot before:****Screenshot after:**---

