# Task

**User Story for Registration Process**

As a prospective customer eagerly exploring Shaped's offerings,
I register to explore the features and benefits of Shaped's AI solutions,
so that I can evaluate its potential impact on my business and decide if I want to use it.

**Success definition:** Given I am on the Shaped registration page after clicking 'Try for free'
When I fill in my email address and click 'Continue'
Then I should receive an indication that my email has an open invitation to join an organization on Shaped, along with options to join or create a new organization.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.shaped.ai/

https://dashboard.shaped.ai/register

**Content (before/after):** 

```
RootWebArea Shaped | Recommendations and Search, focused, url='https://www.shaped.ai/'
	[43] link 11/19 — Announcing Semantic Search with Behavioral Re-Ranking — Click here to learn more, center=(960,32), url='https://www.shaped.ai/blog/shaped-launches-semantic-search-with-behavioral-reranking'
		strong
			StaticText 11/19 — Announcing Semantic Search with Behavioral Re-Ranking
		StaticText — Click here to learn more
```
<details><summary>Show more</summary>

```
	banner
		[53] link home, center=(423,104), url='https://www.shaped.ai/'
			image, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/669a1d930fd1bb0e96c885b1_Shaped_Logo_Horizontal_White.svg'
		navigation
			[58] link Docs, center=(708,103), url='https://docs.shaped.ai/'
			[60] button Solutions, center=(797,103), expanded=False, hasPopup='menu'
			[68] button Products, center=(901,103), expanded=False, hasPopup='menu'
			[73] link Case Studies, center=(1020,103), url='https://www.shaped.ai/case-study'
			[74] link Blog, center=(1120,103), url='https://www.shaped.ai/blog'
			[75] link Contact, center=(1201,103), url='https://meetings.hubspot.com/matt2900/meet-with-shaped-?uuid=4076ed73-5725-4ee7-ac01-2e1869237a18'
		[82] link Login, center=(1392,103), url='https://dashboard.shaped.ai/login'
		[83] link Get Started, center=(1523,104), url='https://dashboard.shaped.ai/register'
	main
		heading Build Search &  Recommendations 100x Faster
		paragraph
			StaticText Increase engagement, conversion, and retention with a configurable system that adapts in real-time
		[103] link Try for free, center=(409,575), url='https://dashboard.shaped.ai/register'
		image Afterhour logo, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/669682e1e2aeb6a0188a164e_company-01.svg'
		image breakr logo, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/669682e00979326bb34a5fd4_company-03.svg'
		image checkmate logo, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/669682e1146f901fffdafc87_company-05.svg'
		image dev logo, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/669682e14244732017cb56cc_company-07.svg'
		image fetch logo, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/6696ee1b4ec64c7fcba0fb3a_company-05-1.svg'
		image Hang Logo, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/669682e0b11a2a58fe1869fb_company-09.svg'
		image kogan logo, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/669682e1805ed88805e58f62_company-02.svg'
		image locker logo, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/6696ef1fef5e55b6b390deb8_company-05.webp'
		image Outdorsy logo, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/669682e0d70cc51e8d7e111e_company-04.svg'
		image playbook logo, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/669682e10376bfc5993a0eeb_company-06.svg'
		image QVC logo, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/669682e0a71edf1a3845e19b_company-08.svg'
		image Trela Logo, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/669682e022cd1a0165caa413_company-10.svg'
		StaticText News
		link Announcing Semantic Search with Behavioral Re-Ranking, url='http://www.shaped.ai/blog/shaped-launches-semantic-search-with-behavioral-reranking'
		Canvas
		heading Why Shaped
		StaticText Turn behavior into
		StaticText relevance
		list
			listitem
				heading Easy Set-Up
				paragraph
					StaticText Connect and deploy rapidly with direct integration to your existing data sources.
			listitem
				heading Real-Time Adaptability
				paragraph
					StaticText Ingest and re-rank in real-time using behavioral signals.
			listitem
				heading State-of-the-Art Model Library
				paragraph
					StaticText Fine tune LLMs and neural ranking models for state-of-the-art performance.
			listitem
				heading Highly Customizable
				paragraph
					StaticText Build and experiment with ranking and retrieval components for any use case.
			listitem
				heading Explainable Results
				paragraph
					StaticText Visualize, evaluate, and interpret your data with in-session analytics and performance metrics.
			listitem
				heading Secure Infrastructure
				paragraph
					StaticText Scale with enterprise-grade security that’s GDPR and SOC2 compliant.
		image Diagram showing how you can connect and deploy rapidly with direct integration to your existing data sources., url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/669034fb9ace042cde50b1ae_shaped-why-01.webp'
		generic
			group 1 / 3
				link Hang Logo Increased Redemption Rate by 4x, url='https://www.shaped.ai/'
					image Hang Logo, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/66950ee5a536e90f2724dc24_Hang.svg'
					StaticText 4x
			group 2 / 3
				link Trela Logo Increased Average Order Value by 16%, url='https://www.shaped.ai/case-study/trela'
					image Trela Logo, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/66950ef3a0b78e01eb110332_trela.svg'
					StaticText 16%
			group 3 / 3
				link Breakr logo Increased Diversity by 3x, url='https://www.shaped.ai/case-study/breakr'
					image Breakr logo, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/66950efd21affb06adca55ac_Breakr.svg'
					StaticText 3x
		generic, atomic
		StaticText How It Works
		heading Shaped Overview
		image diagram showing shaped overview of how it works, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/6695218784c4b26d96c17b7e_How-it-works-p-2000.webp'
		group 1 / 3
			image, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/6695367aec1559b05980873d_axis%201.svg'
			StaticText “Shaped is the best of both worlds — easy to get started while allowing control over our features and models.”
			StaticText Mishaal Al Gergawi
			StaticText CEO, Axis
		group 2 / 3
			image brandazine logo, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/66955f11b8b6adcf99c6df7c_brandazine%201.svg'
			StaticText “Shaped's understanding of our data and ability to create a custom model has been impressive.”
			StaticText Matt Koh
			StaticText Co-CEO, Brandazine
		group 3 / 3
			image Breakr logo, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/66950efd21affb06adca55ac_Breakr.svg'
			StaticText “Shaped provided expertise on how we should collect session and streaming data, while advising on our long term data infrastructure”
			StaticText Ameer Brown
			StaticText Co-Founder, Breakr
		generic, atomic
		button Previous slide
			image
		button Next slide
			image
		heading Designed for technical teams
		paragraph
			StaticText Whether you’re an expert in recommendation systems, a casual machine-learning practitioner or a novice developer, Shaped is built for you.
		link Read the docs, url='https://docs.shaped.ai/'
		tablist, orientation='horizontal'
			tab Javascript, selected=True
			tab Python, selected=False
		tabpanel Javascript
			StaticText npm install
			StaticText @shaped.ai/client
			StaticText 01
			StaticText 02
			StaticText 03
			StaticText 04
			StaticText 05
			StaticText 06
			StaticText 07
			StaticText 08
			StaticText 09
			StaticText 10
			StaticText const
			StaticText {rank} = require('shapedai').Client(
			StaticText 'your_api_key'
			StaticText );
			StaticText await
			StaticText rank({model_name:
			StaticText 'for_you_feed'
			StaticText , user_id:
			StaticText '3'
			StaticText });
		StaticText Output
		StaticText {
		StaticText "ids"
		StaticText : [
		StaticText "carrot"
		StaticText ,
		StaticText "apple"
		StaticText ],
		StaticText "scores"
		StaticText : [
		StaticText 0.919
		StaticText ,
		StaticText 0.832
		StaticText ]
		StaticText }
		heading Solutions for every platform
		link dropship or deliver icon gift icon dollar or money icon Marketplaces Optimize all sides of any marketplace. Improve every step of a buyers’ and sellers’ experience. receipt icon cart icon package icon, url='https://www.shaped.ai/solutions/marketplace'
			image dropship or deliver icon, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/669610eeea3e27832ff61f62_sol-mp-03.svg'
			image gift icon, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/669610ee3ca92dfbcfc0d3b5_sol-mp-02.svg'
			image dollar or money icon, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/669610eec731a0a56d45c4a7_sol-mp-01.svg'
			heading Marketplaces
			paragraph
			image receipt icon, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/669610eedec253ed0698179b_sol-mp-05.svg'
			image cart icon, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/669610ee4bb5341b337dfd19_sol-mp-04.svg'
			image package icon, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/669610ee71c27deafdb959f7_sol-mp-06.svg'
		link chat icon heart icon stack of image icon Social Media Turn traffic into community. Boost engagement and retention. girl or person icon thumbs up icon camera icon, url='https://www.shaped.ai/solutions/social-media'
			image chat icon, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/669618fc95646c9873d168a3_sol-sm-02.svg'
			image heart icon, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/669618fc95a41898d427ef93_sol-sm-03.svg'
			image stack of image icon, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/669618fc67fe63e02bf6c901_sol-sm-01.svg'
			heading Social Media
			paragraph
			image girl or person icon, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/669618fc2ba645447f5db502_sol-sm-05.svg'
			image thumbs up icon, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/669618fca5ee0d95f14296d6_sol-sm-04.svg'
			image camera icon, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/669618fc9ebcc2efa8f525be_sol-sm-06.svg'
		link smiley icon gaming console icon music icon Media Platforms Turn traffic into subscriptions. Boost revenue and engagement. flower or picture icon chat icon television icon, url='https://www.shaped.ai/solutions/media-platforms'
			image smiley icon, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/6696178595646c9873d07b08_sol-me-06.svg'
			image gaming console icon, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/66961785182317f0ef327d52_sol-me-05.svg'
			image music icon, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/669617856a1341e1ad363f7c_sol-me-04.svg'
			heading Media Platforms
			paragraph
			image flower or picture icon, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/669617858d152dc383f3d154_sol-me-01.svg'
			image chat icon, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/669617858db9d3d9d0485d02_sol-me-02.svg'
			image television icon, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/669617856a1341e1ad363f78_sol-me-03.svg'
		link cart icon gift icon money bag icon E-Commerce Turn traffic into conversions. Boost engagement and retention. sunglasses icon bag icon receipt icon, url='https://www.shaped.ai/solutions/e-commerce'
			image cart icon, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/6696177debed04af9f416abf_sol-ec-02.svg'
			image gift icon, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/669610ee3ca92dfbcfc0d3b5_sol-mp-02.svg'
			image money bag icon, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/6696177e6be63aeebb4c355a_sol-ec-06.svg'
			heading E-Commerce
			paragraph
			image sunglasses icon, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/6696177dd490bc23f98f453b_sol-ec-05.svg'
			image bag icon, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/6696177edec253ed069cadf9_sol-ec-04.svg'
			image receipt icon, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/6696177d182317f0ef327a2c_sol-ec-03.svg'
		heading Get up and running with one engineer in one sprint
		paragraph
			StaticText Guaranteed lift within your first 30 days or your money back
		link Get Started for Free, url='https://dashboard.shaped.ai/register'
		link Contact us, url='https://meetings.hubspot.com/matt2900'
		Canvas
		StaticText 100M+
		StaticText Users and items
		StaticText 1000+
		StaticText Queries per second
		StaticText 1B+
		StaticText Requests
		heading FAQs
		paragraph
			StaticText Wherever you need us, we’re there. We are always on-hand to answer your questions.
		link Contact, url='https://meetings.hubspot.com/matt2900/meet-with-shaped-?uuid=4076ed73-5725-4ee7-ac01-2e1869237a18'
		button How long will it take to integrate?, expanded=True
		paragraph
			StaticText The integration process is quick. You can connect your data to Shaped in minutes, train your first model in hours, and fully integrate into your app in days.
		button How is Shaped different to Algolia, AWS Personalize...?, expanded=False
		button Can I use Shaped for multiple ranking use-cases?, expanded=False
		button How much data do I need?, expanded=False
		button Why shouldn’t I build this in-house?, expanded=False
		button What’s your pricing?, expanded=False
		button How do you handle my data?, expanded=False
	contentinfo
		StaticText Products
		link Semantic Search, url='https://www.shaped.ai/semanticsearch'
		link Recommendations, url='https://www.shaped.ai/recommendations'
		StaticText Solutions
		link Marketplaces, url='https://www.shaped.ai/solutions/marketplace'
		link Social Media, url='https://www.shaped.ai/solutions/social-media'
		link Media Platforms, url='https://www.shaped.ai/solutions/marketplace'
		link E-commerce, url='https://www.shaped.ai/solutions/e-commerce'
		StaticText Integrations
		link Segment, url='https://docs.shaped.ai/docs/integrations/segment'
		link Amplitude, url='https://docs.shaped.ai/docs/integrations/amplitude'
		link BigQuery, url='https://docs.shaped.ai/docs/integrations/bigquery'
		link PostgreSQL, url='https://docs.shaped.ai/docs/integrations/postgresql'
		link MySQL, url='https://docs.shaped.ai/docs/integrations/mysql'
		link SnowFlake, url='https://docs.shaped.ai/docs/integrations/snowflake'
		StaticText Resources
		link Docs, url='https://docs.shaped.ai/'
		link Case Studies, url='https://www.shaped.ai/case-study'
		link Blogs, url='https://www.shaped.ai/blog'
		link Vs. Algolia, url='https://www.shaped.ai/blog/shaped-vs-algolia-recommend'
		link Vs. AWS Personalize, url='https://www.shaped.ai/blog/shaped-vs-aws-personalize'
		StaticText Company
		link Careers, url='https://www.ycombinator.com/companies/shaped/jobs'
		link Security, url='https://docs.shaped.ai/docs/support/security'
		link Privacy Policy, url='https://www.shaped.ai/privacy-policy'
		link Terms Of Service, url='https://www.shaped.ai/terms-of-service'
		StaticText Stay informed on the latest news, updates, and releases.
		form Newsletter
			textbox Enter your email, required
			button Submit, disabled=True
		link, url='https://twitter.com/shapedai'
		link, url='https://www.linkedin.com/company/shapedai'
		link, url='https://docs.google.com/forms/d/e/1FAIpQLSdZKGa6FEqSlmIcWlmnv2T9SbGcNzCh-bsDMFoF7RimUAi2MA/viewform'
		link, url='https://www.shaped.ai/'
			image, url='https://cdn.prod.website-files.com/668c2c51c9deca1046d67070/669a1c4c7b8bc051ce153ee5_Shaped_Symbol_White.svg'
		StaticText © 2024 Shaped
		StaticText All right reserved.
```
</details>



```
RootWebArea Shaped, focused, url='https://dashboard.shaped.ai/register'
	image Logo, url='https://dashboard.shaped.ai/shaped-logo-with-name.svg'
	heading Create a free trial account
	[61] button Continue with Github, center=(960,447), type=button
	[63] button Continue with Google, center=(960,495), type=button
```
<details><summary>Show more</summary>

```
		image
	StaticText or
	LabelText
		StaticText Email
	[74] textbox Email, center=(960,621), autocomplete=email, contenteditable=True, type=email
	paragraph
		StaticText By clicking continue, you agree to our
		[76] link Terms of Service, center=(1059,664), url='https://www.shaped.ai/terms-of-service'
		StaticText and
		[77] link Privacy Policy, center=(958,680), url='https://www.shaped.ai/privacy-policy'
		StaticText .
	[78] button Continue, center=(960,725)
	paragraph
		[80] link Already have an account?Sign in., center=(960,778), inner_text=Already have an account? Sign in., url='https://dashboard.shaped.ai/login'
	region Notifications (F8)
		list
	alert, atomic
```
</details>

**Reasoning for action:** I identified the 'Try for free' button with the identifier '103' in the accessibility tree. Clicking this button is essential as it leads me to the registration page, which is the next step in completing the user's task of registering to explore Shaped's AI solutions. This action aligns with the user story, enabling me to input my email and await the next instructions.

**Action:** click('103') # Click on the 'Try for free' button to explore the registration process.

**Change Description:** After clicking the 'Try for free' button, the browser navigated to the registration page at 'https://dashboard.shaped.ai/register', displaying a heading for account creation and options to continue with GitHub or Google, along with an email input field and terms of service links.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://dashboard.shaped.ai/register

https://dashboard.shaped.ai/register

**Content (before/after):** 

```
RootWebArea Shaped, focused, url='https://dashboard.shaped.ai/register'
	image Logo, url='https://dashboard.shaped.ai/shaped-logo-with-name.svg'
	heading Create a free trial account
	[61] button Continue with Github, center=(960,447), type=button
	[63] button Continue with Google, center=(960,495), type=button
```
<details><summary>Show more</summary>

```
		image
	StaticText or
	LabelText
		StaticText Email
	[74] textbox Email, center=(960,621), autocomplete=email, contenteditable=True, type=email
	paragraph
		StaticText By clicking continue, you agree to our
		[76] link Terms of Service, center=(1059,664), url='https://www.shaped.ai/terms-of-service'
		StaticText and
		[77] link Privacy Policy, center=(958,680), url='https://www.shaped.ai/privacy-policy'
		StaticText .
	[78] button Continue, center=(960,725)
	paragraph
		[80] link Already have an account?Sign in., center=(960,778), inner_text=Already have an account? Sign in., url='https://dashboard.shaped.ai/login'
	region Notifications (F8)
		list
	alert, atomic
```
</details>



```
RootWebArea Shaped, focused, url='https://dashboard.shaped.ai/register'
	image Logo, url='https://dashboard.shaped.ai/shaped-logo-with-name.svg'
	heading Create a free trial account
	[61] button Continue with Github, center=(960,447), type=button
	[63] button Continue with Google, center=(960,495), type=button
```
<details><summary>Show more</summary>

```
		image
	StaticText or
	LabelText
		StaticText Email
	[74] textbox Email value='test@example.com', center=(960,621), autocomplete=email, contenteditable=True, focused, type=email
	paragraph
		StaticText By clicking continue, you agree to our
		[76] link Terms of Service, center=(1059,664), url='https://www.shaped.ai/terms-of-service'
		StaticText and
		[77] link Privacy Policy, center=(958,680), url='https://www.shaped.ai/privacy-policy'
		StaticText .
	[78] button Continue, center=(960,725)
	paragraph
		[80] link Already have an account?Sign in., center=(960,778), inner_text=Already have an account? Sign in., url='https://dashboard.shaped.ai/login'
	region Notifications (F8)
		list
	alert, atomic
```
</details>

**Reasoning for action:** My reasoning for this action is that filling in the email address is the first part of the user's task to register on Shaped's platform. Once the email field is filled, it will allow the user to proceed by clicking the 'Continue' button, ultimately leading to an indication that their email has an open invitation to join an organization.

**Action:** fill('74', 'test@example.com') # Fill in the email field with a test email address.

**Change Description:** The email textbox was populated with the value 'test@example.com', and it became focused, indicating a change in its state to reflect user input.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://dashboard.shaped.ai/register

https://dashboard.shaped.ai/join-organization?email=test@example.com

**Content (before/after):** 

```
RootWebArea Shaped, focused, url='https://dashboard.shaped.ai/register'
	image Logo, url='https://dashboard.shaped.ai/shaped-logo-with-name.svg'
	heading Create a free trial account
	[61] button Continue with Github, center=(960,447), type=button
	[63] button Continue with Google, center=(960,495), type=button
```
<details><summary>Show more</summary>

```
		image
	StaticText or
	LabelText
		StaticText Email
	[74] textbox Email value='test@example.com', center=(960,621), autocomplete=email, contenteditable=True, focused, type=email
	paragraph
		StaticText By clicking continue, you agree to our
		[76] link Terms of Service, center=(1059,664), url='https://www.shaped.ai/terms-of-service'
		StaticText and
		[77] link Privacy Policy, center=(958,680), url='https://www.shaped.ai/privacy-policy'
		StaticText .
	[78] button Continue, center=(960,725)
	paragraph
		[80] link Already have an account?Sign in., center=(960,778), inner_text=Already have an account? Sign in., url='https://dashboard.shaped.ai/login'
	region Notifications (F8)
		list
	alert, atomic
```
</details>



```
RootWebArea Shaped, focused, url='https://dashboard.shaped.ai/join-organization?email=test@example.com'
	image Logo, url='https://dashboard.shaped.ai/shaped-logo-with-name.svg'
	heading You were invited to join an org on Shaped.
	paragraph
		StaticText We found your email, "
```
<details><summary>Show more</summary>

```
		StaticText test@example.com
		StaticText " has an open invitation to join an org. You can join them or continue to
		[131] button create a new organization, center=(1098,396)
		StaticText .
	image
	StaticText nitu.razvan+account2@icloud.com
	[137] button Join, center=(1098,480)
	region Notifications (F8)
		list
	alert, atomic
```
</details>

**Reasoning for action:** I chose to click on the 'Continue' button to submit the email address I've entered into the textbox. This action is essential for proceeding with the registration process, triggering the system to recognize the email input and to initiate the next steps necessary to indicate whether the email has an invitation to join or create an organization on Shaped.

**Action:** click('78') # Click on the 'Continue' button to proceed with the registration.

**Change Description:** After clicking the 'Continue' button, the browser navigated from the registration page to a new page indicating that the email 'test@example.com' has an open invitation to join an organization on Shaped, along with options to either join the organization or create a new one.

**Screenshot before:****Screenshot after:**---

