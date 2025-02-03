# Task

**Free Proposal Request Workflow**

As a potential customer,
I request a free proposal for services,
so that I can evaluate options for my business needs.

**Success definition:** Given I am on the Kaya Pricing page
When I click the 'Get free proposal' button and then the 'Get started' button
Then I should be directed to an interactive form where I can enter my work email to begin the proposal process.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.dime.io/

https://www.usekaya.com/pricing

**Content (before/after):** 

```
RootWebArea 404 Page not found, focused, url='https://www.dime.io/'
	heading Error: Page not found
	heading The requested URL was not found on this server.
	heading
```


```
RootWebArea Pricing | Kaya, focused, url='https://www.usekaya.com/pricing'
	banner
		[85] link Kaya logo, center=(410,33), url='https://www.usekaya.com/'
			image Kaya logo, url='https://cdn.prod.website-files.com/61dd865bd089adaaa43f7154/62922721cdd7df51b1a7e0e0_kaya-full-logo-p-500.png'
		[88] link Ads Management, center=(722,33), url='https://www.usekaya.com/'
```
<details><summary>Show more</summary>

```
		[90] link Competitor Ad Intelligence, center=(912,33), url='https://www.usekaya.com/competitor-ad-intelligence-tool'
		[92] link Pricing, center=(1064,33), url='https://www.usekaya.com/pricing'
		[94] link Customers, center=(1158,33), url='https://www.usekaya.com/customers'
		[96] link Blog, center=(1244,33), url='https://www.usekaya.com/blog'
		[99] link Get free proposal, center=(1490,33), url='https://app.usekaya.com/start-proposal'
		StaticText NEW
		StaticText Get competitor analysis done– without any manual work.
		[106] link Learn more ->, center=(1168,90), url='https://www.usekaya.com/competitor-ad-intelligence-tool'
	heading Pay Less, Grow More
	paragraph
		StaticText With our technology, we're able to deliver superior outcomes with minimal overhead costs, and we pass those savings back to you.
	tablist, orientation='horizontal'
		[117] tab Ads Management, center=(838,366), selected=True
		[119] tab Competitor Ad Intelligence, center=(1082,366), selected=False
	tabpanel Ads Management
		StaticText From
		StaticText $
		StaticText 3,000
		StaticText /month
		StaticText 3-month contract, paid monthly
		[134] link Get free proposal, center=(960,597), url='https://app.usekaya.com/start-proposal'
		heading What's included
		image, url='https://cdn.prod.website-files.com/61dd865bd089adaaa43f7154/66fd390c6257929c25f4fde5_emoji-rocket.png'
		StaticText Ads management
		StaticText Campaign setup end-to-end
		StaticText Ongoing ads management & optimisation
		StaticText Conversion tracking setup
		StaticText Landing page audit & recommendations
		StaticText Weekly reports
		StaticText Regular Slack/email updates
		StaticText Live dashboards
		StaticText Dedicated support via Slack Connect
		image, url='https://cdn.prod.website-files.com/61dd865bd089adaaa43f7154/66fd39088373486ba788f533_emoji-palette.png'
		StaticText Creative design
		StaticText Deliverables in Figma/Illustrator
		StaticText Unlimited revisions
		image, url='https://cdn.prod.website-files.com/61dd865bd089adaaa43f7154/66fd3908ee003be49716129d_emoji-screen.png'
		StaticText Landing page design
		StaticText Figma mockup
		StaticText Website copywriting
		StaticText Webflow/Shopify implementation
	heading Interested in performance-based pricing?
	paragraph
		StaticText Pay us based on the results we achieve. Check your eligibility by requesting a free proposal.
	link Get free proposal ->, url='https://app.usekaya.com/start'
	paragraph
		StaticText FREE, NO-OBLIGATION CONSULTATION
	heading Paid Ads Office Hour
	StaticText Our goal is to help you steer clear of potentially expensive missteps.
	StaticText You set the agenda.
	StaticText Potential topics include:
	StaticText Selecting the optimal growth channel
	StaticText Essential website and conversion tracking best practices
	StaticText Strategies to optimize and scale
	link Book a time, url='https://www.usekaya.com/pricing#'
	paragraph
		StaticText KAYA
		StaticText vs
		StaticText OTHERS
	heading Purpose built for startups
	image, url='https://cdn.prod.website-files.com/61dd865bd089adaaa43f7154/624203247e3aac20601c4009_kaya-256.png'
	StaticText Kaya
	StaticText Traditional Agencies
	StaticText Full-time Hire
	StaticText Cost
	StaticText From $3,000/m without minimum spend requirement
	StaticText High
	StaticText – due to retainer fees and minimum spend requirements
	StaticText High
	StaticText – from $100K+ per year due to salaries, benefits, recruitment
	StaticText Time to results
	StaticText As soon as
	StaticText 2 weeks
	StaticText Months
	StaticText – due to lengthy setup and traditional workflows
	StaticText 3+ months
	StaticText just to find and onboard the right hire
	StaticText Risk
	StaticText Low
	StaticText – we’ve helped hundreds of companies grow, and there’s no long term contract
	StaticText High
	StaticText – Experience varies, and contracts are long term
	StaticText High
	StaticText – Experience varies; a bad hire will cost you a whole year
	StaticText Comprehensive Analytics
	StaticText Advanced dashboards and alerts included out of the box
	StaticText May require additional resources for analytics solutions
	StaticText May require additional tools or software, and labour for setup and maintenance
	StaticText Transparency & Communication
	StaticText Full transparency with regular performance updates via Slack or email
	StaticText Less frequent updates and more formal communication channels
	StaticText Highly varies by individual's reporting skills
	StaticText Full stack capabilities
	StaticText Full-fledged team– strategists, designers, copywriters, and tracking experts
	StaticText Can offer a team, often at much higher costs and less flexibility
	StaticText Limited to the individual’s expertise; more hires may be needed for a full-stack solution
	heading FAQ
	list
		listitem
			button Does Kaya have a discount rate for startups?, expanded=False, hasPopup='menu'
		listitem
			button Is there any obligation to proceed with your services after receiving the proposal?, expanded=False, hasPopup='menu'
		listitem
			button Are there any fees associated with the free proposal?, expanded=False, hasPopup='menu'
		listitem
			button Can I cancel after I have decided to proceed with the setup of my ad campaigns?, expanded=False, hasPopup='menu'
		listitem
			button Can I cancel my contract at any time?, expanded=False, hasPopup='menu'
		listitem
			button How do I qualify for performance-based pricing?, expanded=False, hasPopup='menu'
		listitem
			button How does Kaya's performance-based pricing work?, expanded=False, hasPopup='menu'
		listitem
			button Is there a maximum fee or cap to your pricing?, expanded=False, hasPopup='menu'
		listitem
			button Are there any hidden fees I should be aware of?, expanded=False, hasPopup='menu'
	list
		listitem
			image, url='https://cdn.prod.website-files.com/62815636aaaae951fed982e5/6700677fedd1aedbaf708d9f_Frame%202747%20(2).png'
			paragraph
				StaticText “
				StaticText Kaya exceeded my expectations. We had weak results with other agencies that our team worked with in the past. Kaya is the best, by a wide margin.
				StaticText ”
			StaticText Vineet Mehta
			StaticText Founder
			StaticText ,
			StaticText Homebreeze
	heading Leave Traditional Marketing Agencies & Freelancers Behind
	paragraph
		StaticText We understand the frustrations of working with traditional marketing agencies: slow processes, inadequate reporting, communication issues, and restrictive contracts. That's why we created Kaya as a superior alternative.
		StaticText Ready to experience the difference? Simply fill out a short form, and within 3 days, you'll receive a comprehensive, tailored proposal that will accelerate your startup's growth.
	link Get free proposal, url='https://app.usekaya.com/start-proposal'
	link Kaya logo, url='https://www.usekaya.com/'
		image Kaya logo, url='https://cdn.prod.website-files.com/61dd865bd089adaaa43f7154/62922721f07b5eb835287449_kaya-full-logo--for%20dark-p-500.png'
	form Newsletter form
		LabelText
			StaticText Subscribe to our newsletter
		textbox name@email.com, required
		button Subscribe
	paragraph
		StaticText Menu
	link Pricing, url='https://www.usekaya.com/pricing'
	link FAQ, url='https://www.usekaya.com/faq'
	link Customers, url='https://www.usekaya.com/customers'
	link Blog, url='https://www.usekaya.com/blog'
	paragraph
		StaticText Launch
	link Google Ads, url='https://www.usekaya.com/launch/google-ads'
	link Meta Ads, url='https://www.usekaya.com/launch/facebook-ads'
	link YouTube Ads, url='https://www.usekaya.com/launch/youtube-ads'
	link LinkedIn Ads, url='https://www.usekaya.com/launch/linkedin-ads'
	link TikTok Ads, url='https://www.usekaya.com/launch/tiktok-ads'
	paragraph
		StaticText Competitor Intelligence
	link Overview, url='https://www.usekaya.com/competitor-ad-intelligence-tool'
	paragraph
		StaticText Analytics
	link Overview, url='https://www.usekaya.com/analytics'
	paragraph
		StaticText Company
	link About, url='https://www.usekaya.com/about'
	link Hiring, url='https://www.ycombinator.com/companies/kaya/jobs'
	link LinkedIn, url='https://www.linkedin.com/company/usekaya'
	StaticText Backed by
	image, url='https://cdn.prod.website-files.com/61dd865bd089adaaa43f7154/62842373497c90fe833b1d58_YC%20Logo%20Square.png'
	StaticText Y Combinator
	paragraph
		StaticText © Kaya Technologies Ltd.
	link Terms, url='https://firebasestorage.googleapis.com/v0/b/kaya-apps-00.appspot.com/o/Kaya%20Service%20Agreement%20-%20Launch%20-%202024%3A04.pdf?alt=media&token=50939ee0-399a-4b0e-a317-7740057cadcd'
	link Privacy, url='https://www.iubenda.com/privacy-policy/58428147'
	link Cookie, url='https://www.iubenda.com/privacy-policy/58428147/cookie-policy'
	alertdialog Notice, modal=False
		region
			[525] button Close this notice, center=(1183,1063), type=button
			document
				StaticText Kaya uses cookies to bring you the best experience on our website.
			[531] button Learn more, center=(1113,1048)
			[533] button Got it, center=(1180,1049)
	[535] button Open chat window, center=(1868,1028), title=Open chat window
		image
```
</details>

**Reasoning for action:** I encountered a 404 error on the current page, which indicates that the Kaya Pricing page is not accessible from the current URL. By going back, I am attempting to return to the previous webpage, which may lead me to the correct location where the Kaya Pricing page is available. This action is crucial to move forward with the user's request for a free proposal.

**Action:** go_back() # Navigate back to the previous page.

**Change Description:** The browser navigated back to the previous page, shifting from a 404 error state indicating that the page was not found to the 'Pricing' page of Kaya, which now displays various pricing options, service offerings, and promotional information.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://www.usekaya.com/pricing

https://app.usekaya.com/start-proposal

**Content (before/after):** 

```
RootWebArea Pricing | Kaya, focused, url='https://www.usekaya.com/pricing'
	banner
		[85] link Kaya logo, center=(410,33), url='https://www.usekaya.com/'
			image Kaya logo, url='https://cdn.prod.website-files.com/61dd865bd089adaaa43f7154/62922721cdd7df51b1a7e0e0_kaya-full-logo-p-500.png'
		[88] link Ads Management, center=(722,33), url='https://www.usekaya.com/'
```
<details><summary>Show more</summary>

```
		[90] link Competitor Ad Intelligence, center=(912,33), url='https://www.usekaya.com/competitor-ad-intelligence-tool'
		[92] link Pricing, center=(1064,33), url='https://www.usekaya.com/pricing'
		[94] link Customers, center=(1158,33), url='https://www.usekaya.com/customers'
		[96] link Blog, center=(1244,33), url='https://www.usekaya.com/blog'
		[99] link Get free proposal, center=(1490,33), url='https://app.usekaya.com/start-proposal'
		StaticText NEW
		StaticText Get competitor analysis done– without any manual work.
		[106] link Learn more ->, center=(1168,90), url='https://www.usekaya.com/competitor-ad-intelligence-tool'
	heading Pay Less, Grow More
	paragraph
		StaticText With our technology, we're able to deliver superior outcomes with minimal overhead costs, and we pass those savings back to you.
	tablist, orientation='horizontal'
		[117] tab Ads Management, center=(838,366), selected=True
		[119] tab Competitor Ad Intelligence, center=(1082,366), selected=False
	tabpanel Ads Management
		StaticText From
		StaticText $
		StaticText 3,000
		StaticText /month
		StaticText 3-month contract, paid monthly
		[134] link Get free proposal, center=(960,597), url='https://app.usekaya.com/start-proposal'
		heading What's included
		image, url='https://cdn.prod.website-files.com/61dd865bd089adaaa43f7154/66fd390c6257929c25f4fde5_emoji-rocket.png'
		StaticText Ads management
		StaticText Campaign setup end-to-end
		StaticText Ongoing ads management & optimisation
		StaticText Conversion tracking setup
		StaticText Landing page audit & recommendations
		StaticText Weekly reports
		StaticText Regular Slack/email updates
		StaticText Live dashboards
		StaticText Dedicated support via Slack Connect
		image, url='https://cdn.prod.website-files.com/61dd865bd089adaaa43f7154/66fd39088373486ba788f533_emoji-palette.png'
		StaticText Creative design
		StaticText Deliverables in Figma/Illustrator
		StaticText Unlimited revisions
		image, url='https://cdn.prod.website-files.com/61dd865bd089adaaa43f7154/66fd3908ee003be49716129d_emoji-screen.png'
		StaticText Landing page design
		StaticText Figma mockup
		StaticText Website copywriting
		StaticText Webflow/Shopify implementation
	heading Interested in performance-based pricing?
	paragraph
		StaticText Pay us based on the results we achieve. Check your eligibility by requesting a free proposal.
	link Get free proposal ->, url='https://app.usekaya.com/start'
	paragraph
		StaticText FREE, NO-OBLIGATION CONSULTATION
	heading Paid Ads Office Hour
	StaticText Our goal is to help you steer clear of potentially expensive missteps.
	StaticText You set the agenda.
	StaticText Potential topics include:
	StaticText Selecting the optimal growth channel
	StaticText Essential website and conversion tracking best practices
	StaticText Strategies to optimize and scale
	link Book a time, url='https://www.usekaya.com/pricing#'
	paragraph
		StaticText KAYA
		StaticText vs
		StaticText OTHERS
	heading Purpose built for startups
	image, url='https://cdn.prod.website-files.com/61dd865bd089adaaa43f7154/624203247e3aac20601c4009_kaya-256.png'
	StaticText Kaya
	StaticText Traditional Agencies
	StaticText Full-time Hire
	StaticText Cost
	StaticText From $3,000/m without minimum spend requirement
	StaticText High
	StaticText – due to retainer fees and minimum spend requirements
	StaticText High
	StaticText – from $100K+ per year due to salaries, benefits, recruitment
	StaticText Time to results
	StaticText As soon as
	StaticText 2 weeks
	StaticText Months
	StaticText – due to lengthy setup and traditional workflows
	StaticText 3+ months
	StaticText just to find and onboard the right hire
	StaticText Risk
	StaticText Low
	StaticText – we’ve helped hundreds of companies grow, and there’s no long term contract
	StaticText High
	StaticText – Experience varies, and contracts are long term
	StaticText High
	StaticText – Experience varies; a bad hire will cost you a whole year
	StaticText Comprehensive Analytics
	StaticText Advanced dashboards and alerts included out of the box
	StaticText May require additional resources for analytics solutions
	StaticText May require additional tools or software, and labour for setup and maintenance
	StaticText Transparency & Communication
	StaticText Full transparency with regular performance updates via Slack or email
	StaticText Less frequent updates and more formal communication channels
	StaticText Highly varies by individual's reporting skills
	StaticText Full stack capabilities
	StaticText Full-fledged team– strategists, designers, copywriters, and tracking experts
	StaticText Can offer a team, often at much higher costs and less flexibility
	StaticText Limited to the individual’s expertise; more hires may be needed for a full-stack solution
	heading FAQ
	list
		listitem
			button Does Kaya have a discount rate for startups?, expanded=False, hasPopup='menu'
		listitem
			button Is there any obligation to proceed with your services after receiving the proposal?, expanded=False, hasPopup='menu'
		listitem
			button Are there any fees associated with the free proposal?, expanded=False, hasPopup='menu'
		listitem
			button Can I cancel after I have decided to proceed with the setup of my ad campaigns?, expanded=False, hasPopup='menu'
		listitem
			button Can I cancel my contract at any time?, expanded=False, hasPopup='menu'
		listitem
			button How do I qualify for performance-based pricing?, expanded=False, hasPopup='menu'
		listitem
			button How does Kaya's performance-based pricing work?, expanded=False, hasPopup='menu'
		listitem
			button Is there a maximum fee or cap to your pricing?, expanded=False, hasPopup='menu'
		listitem
			button Are there any hidden fees I should be aware of?, expanded=False, hasPopup='menu'
	list
		listitem
			image, url='https://cdn.prod.website-files.com/62815636aaaae951fed982e5/6700677fedd1aedbaf708d9f_Frame%202747%20(2).png'
			paragraph
				StaticText “
				StaticText Kaya exceeded my expectations. We had weak results with other agencies that our team worked with in the past. Kaya is the best, by a wide margin.
				StaticText ”
			StaticText Vineet Mehta
			StaticText Founder
			StaticText ,
			StaticText Homebreeze
	heading Leave Traditional Marketing Agencies & Freelancers Behind
	paragraph
		StaticText We understand the frustrations of working with traditional marketing agencies: slow processes, inadequate reporting, communication issues, and restrictive contracts. That's why we created Kaya as a superior alternative.
		StaticText Ready to experience the difference? Simply fill out a short form, and within 3 days, you'll receive a comprehensive, tailored proposal that will accelerate your startup's growth.
	link Get free proposal, url='https://app.usekaya.com/start-proposal'
	link Kaya logo, url='https://www.usekaya.com/'
		image Kaya logo, url='https://cdn.prod.website-files.com/61dd865bd089adaaa43f7154/62922721f07b5eb835287449_kaya-full-logo--for%20dark-p-500.png'
	form Newsletter form
		LabelText
			StaticText Subscribe to our newsletter
		textbox name@email.com, required
		button Subscribe
	paragraph
		StaticText Menu
	link Pricing, url='https://www.usekaya.com/pricing'
	link FAQ, url='https://www.usekaya.com/faq'
	link Customers, url='https://www.usekaya.com/customers'
	link Blog, url='https://www.usekaya.com/blog'
	paragraph
		StaticText Launch
	link Google Ads, url='https://www.usekaya.com/launch/google-ads'
	link Meta Ads, url='https://www.usekaya.com/launch/facebook-ads'
	link YouTube Ads, url='https://www.usekaya.com/launch/youtube-ads'
	link LinkedIn Ads, url='https://www.usekaya.com/launch/linkedin-ads'
	link TikTok Ads, url='https://www.usekaya.com/launch/tiktok-ads'
	paragraph
		StaticText Competitor Intelligence
	link Overview, url='https://www.usekaya.com/competitor-ad-intelligence-tool'
	paragraph
		StaticText Analytics
	link Overview, url='https://www.usekaya.com/analytics'
	paragraph
		StaticText Company
	link About, url='https://www.usekaya.com/about'
	link Hiring, url='https://www.ycombinator.com/companies/kaya/jobs'
	link LinkedIn, url='https://www.linkedin.com/company/usekaya'
	StaticText Backed by
	image, url='https://cdn.prod.website-files.com/61dd865bd089adaaa43f7154/62842373497c90fe833b1d58_YC%20Logo%20Square.png'
	StaticText Y Combinator
	paragraph
		StaticText © Kaya Technologies Ltd.
	link Terms, url='https://firebasestorage.googleapis.com/v0/b/kaya-apps-00.appspot.com/o/Kaya%20Service%20Agreement%20-%20Launch%20-%202024%3A04.pdf?alt=media&token=50939ee0-399a-4b0e-a317-7740057cadcd'
	link Privacy, url='https://www.iubenda.com/privacy-policy/58428147'
	link Cookie, url='https://www.iubenda.com/privacy-policy/58428147/cookie-policy'
	alertdialog Notice, modal=False
		region
			[525] button Close this notice, center=(1183,1063), type=button
			document
				StaticText Kaya uses cookies to bring you the best experience on our website.
			[531] button Learn more, center=(1113,1048)
			[533] button Got it, center=(1180,1049)
	[535] button Open chat window, center=(1868,1028), title=Open chat window
		image
```
</details>



```
RootWebArea Get free proposal | Kaya, focused, url='https://app.usekaya.com/start-proposal'
	main
		[61] link Kaya logo, center=(480,55), url='https://www.usekaya.com/?utm_medium=referral&utm_source=app&utm_campaign=redirect-proposal-form'
			image Kaya logo, url='https://app.usekaya.com/assets/kaya-logo-full-BzJ2YAQ3.png'
		StaticText Get a free, tailored proposal
```
<details><summary>Show more</summary>

```
		StaticText 1
		paragraph
			StaticText Tell us more about your business and goals
		paragraph
			StaticText The information you provide will help us shape your proposal to your needs.
		StaticText 2
		paragraph
			StaticText We craft your proposal
		paragraph
			StaticText Within 3 days, we'll deliver a tailored proposal featuring a thorough analysis of your competitors' ads, practical channel recommendations, forecasting, and CAC simulation.
		StaticText 3
		paragraph
			StaticText Review your proposal
		paragraph
			StaticText And optionally, jump on a call with us to discuss it together.
		StaticText Get started
		image
		[92] div, center=(480,554), inner_text=Get started
		paragraph
			StaticText Takes 5 minutes
		paragraph
			StaticText Kaya exceeded my expectations. We had weak results with other agencies that our team worked with in the past. Kaya is the best, by a wide margin.
		image, url='https://app.usekaya.com/assets/homebreeze-vineet-mehta-DBzejI9Z.jpeg'
		paragraph
			StaticText Vineet Mehta
		paragraph
			StaticText Founder, Homebreeze
		image, url='https://app.usekaya.com/assets/library-backdrop-DmpfVXiF.jpg'
	region Notifications alt+T
		list
	[112] div, center=(1208,1040)
	[111] div, center=(1176,1040)
	[110] div, center=(1144,1040)
	[109] div, center=(1112,1040)
	[108] div, center=(1080,1040)
	[107] div, center=(1032,1040)
```
</details>

**Reasoning for action:** I identified that the user wants to request a free proposal for services offered on the Kaya Pricing page. Clicking the 'Get free proposal' button is the first step towards achieving this goal, as it will take the user to a dedicated form for starting the proposal process. This aligns with the user's request for a proposal, allowing them to evaluate their business options.

**Action:** click(134) # Click on the 'Get free proposal' button to request a proposal.

**Change Description:** The browser navigated from the pricing page of Kaya to a new page designated for obtaining a free proposal, featuring a form to collect business details and goals, and outlining the subsequent steps that would follow after submission.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://app.usekaya.com/start-proposal

https://app.usekaya.com/start-proposal

**Content (before/after):** 

```
RootWebArea Get free proposal | Kaya, focused, url='https://app.usekaya.com/start-proposal'
	main
		[61] link Kaya logo, center=(480,55), url='https://www.usekaya.com/?utm_medium=referral&utm_source=app&utm_campaign=redirect-proposal-form'
			image Kaya logo, url='https://app.usekaya.com/assets/kaya-logo-full-BzJ2YAQ3.png'
		StaticText Get a free, tailored proposal
```
<details><summary>Show more</summary>

```
		StaticText 1
		paragraph
			StaticText Tell us more about your business and goals
		paragraph
			StaticText The information you provide will help us shape your proposal to your needs.
		StaticText 2
		paragraph
			StaticText We craft your proposal
		paragraph
			StaticText Within 3 days, we'll deliver a tailored proposal featuring a thorough analysis of your competitors' ads, practical channel recommendations, forecasting, and CAC simulation.
		StaticText 3
		paragraph
			StaticText Review your proposal
		paragraph
			StaticText And optionally, jump on a call with us to discuss it together.
		StaticText Get started
		image
		[92] div, center=(480,554), inner_text=Get started
		paragraph
			StaticText Takes 5 minutes
		paragraph
			StaticText Kaya exceeded my expectations. We had weak results with other agencies that our team worked with in the past. Kaya is the best, by a wide margin.
		image, url='https://app.usekaya.com/assets/homebreeze-vineet-mehta-DBzejI9Z.jpeg'
		paragraph
			StaticText Vineet Mehta
		paragraph
			StaticText Founder, Homebreeze
		image, url='https://app.usekaya.com/assets/library-backdrop-DmpfVXiF.jpg'
	region Notifications alt+T
		list
	[112] div, center=(1208,1040)
	[111] div, center=(1176,1040)
	[110] div, center=(1144,1040)
	[109] div, center=(1112,1040)
	[108] div, center=(1080,1040)
	[107] div, center=(1032,1040)
```
</details>



```
RootWebArea Get free proposal | Kaya, focused, url='https://app.usekaya.com/start-proposal'
	banner
		[128] link Kaya logo, center=(112,32), url='https://app.usekaya.com/start-proposal'
			image Kaya logo, url='data:image/png;base64,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'
	main
```
<details><summary>Show more</summary>

```
		StaticText What's your work email?
		LabelText
			image
			[148] textbox, center=(972,224), autocomplete=off, contenteditable=True, focused, type=email
		StaticText Continue
	region Notifications alt+T
		list
```
</details>

**Reasoning for action:** By clicking the 'Get started' button (identified by element 92), I am directing the user to the next step in the process of requesting a proposal. This action is crucial as it transitions the user from the informational section of the pricing page to the interactive form where they can provide necessary details, including their work email. This aligns with the user's goal of obtaining a free proposal for their business needs.

**Action:** click(92) # Click on the 'Get started' button to begin the proposal process.

**Change Description:** Upon clicking the 'Get started' button, the webpage transitioned from a static proposal description to an interactive form prompting for the user's work email, indicating that the proposal process has begun. The interface updated to display a textbox for email input, replacing the previous static text with a focus on user interaction.

**Screenshot before:****Screenshot after:**---

