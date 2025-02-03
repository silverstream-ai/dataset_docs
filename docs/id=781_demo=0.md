# Task

**Explore Corgea Pricing and Registration**

As a prospective customer,
I understand the pricing options and begin the registration process for the Free tier,
so that I can evaluate if Corgea's services meet my security needs before committing to a plan.

**Success definition:** Given I am on the Corgea About page httpscorgea.comabout
When I click on the Pricing link and subsequently click 'Get Started' for the Free tier
Then I should see the Corgea Pricing page with various service costs displayed, and be redirected to the registration page where a temporary verification screen is shown.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://corgea.com/

https://corgea.com/about

**Content (before/after):** 

```
RootWebArea Corgea - Home, focused, url='https://corgea.com/'
	[60] link, center=(464,51), url='https://corgea.com/'
		image, url='https://framerusercontent.com/images/yGr2lcNPx7bOFsUXFFm5R7Vy8o.png'
	paragraph
		[66] link About, center=(827,50), url='https://corgea.com/about'
```
<details><summary>Show more</summary>

```
	paragraph
		[69] link Pricing, center=(888,50), url='https://corgea.com/Pricing'
	paragraph
		[72] link Docs, center=(944,50), url='https://docs.corgea.app/introduction'
	paragraph
		[75] link Learn, center=(995,50), url='https://corgea.com/Learn'
	paragraph
		[78] link Blog, center=(1045,50), url='https://corgea.com/blog'
	paragraph
		[81] link Contact, center=(1105,50), url='https://corgea.com/Contact'
	[83] link Start for free, center=(1466,51), url='https://www.corgea.app/registration/'
		paragraph
		image
	heading Secure your code
	heading without the dev tax
	heading Corgea is an AI-powered security platform that finds, triages and fixes your insecure code
	[104] link Start for free, center=(871,477), url='https://www.corgea.app/registration/'
		paragraph
		image
	[112] link Schedule demo, center=(1044,477), url='https://calendly.com/asadeddin/30min?month=2024-02'
		paragraph
		image
	paragraph
		StaticText BACKED BY
	image, url='https://framerusercontent.com/images/H41aKYQauqiDdoCLJXy3OtIU0I.png?scale-down-to=512'
	paragraph
		StaticText THE PROBLEM
	heading Current tools don't work
	paragraph
		StaticText Your current SAST tool overlooks critical vulnerabilities, generates excessive noise, and fails to provide effective remediation guidance for your developers.
	image, url='https://framerusercontent.com/images/15IEEmB5XFCPRX1Gg12t6p5RUk.gif?scale-down-to=512'
	heading You have serious risk & blind spots
	paragraph
		StaticText Current tools miss up to 60% of vulnerabilities in your code, leaving hidden risks that could cause major issues down the line.
	image, url='https://framerusercontent.com/images/Hxjk518eDlmQx27Zsdc9oNSOwNQ.gif'
	heading You hear a lot of noise
	paragraph
		StaticText Current tools misreport around 30% of the time, causing you to waste time on false alarms while overlooking real threats
	image, url='https://framerusercontent.com/images/3zwDgiovQue8X7h58bzAuv5wpwI.gif?scale-down-to=512'
	heading Developers waste time
	paragraph
		StaticText Developers spend hours fixing a vulnerability, taking them away from critical security tasks and revenue-generating work.
	paragraph
		StaticText BENEFITS
	heading Increase Security and Reduce Work
	paragraph
		StaticText Corgea uses AI and advanced code analysis to detect, triage, and remediate insecure code.
	heading Detect the
	heading Undetected
	paragraph
		StaticText Corgea uncovers business logic and code logic vulnerabilities that other tools miss. Identify issues before bug bounties, malicious actors, or pentesters do.
	link Start for free, url='https://www.corgea.app/registration/'
		paragraph
		image
	image, url='https://framerusercontent.com/images/wYbDj3tAHOOtTyyFsK9QXdBOpwg.png?scale-down-to=1024'
	heading Reduce the
	heading Noise
	paragraph
		StaticText Corgea automatically reduces around 30% of tickets by triaging false positives from your SAST scanner.
	link Start for free, url='https://www.corgea.app/registration/'
		paragraph
		image
	image, url='https://framerusercontent.com/images/jjZBifQIHarc1qzf0HnnaC2VRM8.png?scale-down-to=1024'
	heading Faster
	heading Fixes
	paragraph
		StaticText Corgea generates high-quality code fixes for valid findings that are ready for your developers' approval.
	link Start for free, url='https://www.corgea.app/registration/'
		paragraph
		image
	image, url='https://framerusercontent.com/images/lCpU0doxPmfTOIPM0K8vwBiZbMw.png?scale-down-to=1024'
	heading Developer
	heading Friendly
	paragraph
		StaticText Engineers can stay in their favorite IDEs without learning new commands. Corgea integrates with popular tools and sends code fixes directly to GitHub or Azure DevOps for approval (GitLab and Bitbucket coming soon
	image
	image, url='https://framerusercontent.com/images/C1qw2OzrvMSdUJCirOD1hPPQuSI.png'
	image, url='https://framerusercontent.com/images/taoVBXDbA9hP2FcBAn7P1Qao.png?scale-down-to=512'
	image, url='https://framerusercontent.com/images/FGZsgcYYkfIO1n27aOprE5lKnpE.png?scale-down-to=512'
	image
	image, url='https://framerusercontent.com/images/lr3R0AIwBTt2J1BTTQiseRoc.png'
	image, url='https://framerusercontent.com/images/5JQabn7vw0cHdgMqnOvXDIeHi1E.png'
	image, url='https://framerusercontent.com/images/KsKK5DgiP9YDspOZWNVT9jmxXhA.png'
	link Start for free, url='https://www.corgea.app/registration/'
		paragraph
		image
	image, url='https://framerusercontent.com/images/8DHhLv5jgkoE6ZYMo7dpCcuTWPo.png'
	heading We speak your language
	paragraph
		StaticText Corgea supports any language and natively secures your code. Currently compatible with Java, JavaScript, TypeScript, Go, Ruby, Python, C#, and their frameworks.
	list
		listitem
			image, url='https://framerusercontent.com/images/PITedKkwxMNgXzKJxsHUL61cHGo.png?scale-down-to=512'
		listitem
			image, url='https://framerusercontent.com/images/N1t49dU6pRsmYL3zuMJxORLxM.png'
		listitem
			image, url='https://framerusercontent.com/images/Al3g6qCPNTdLtEv9CgrOHgA6qc.png'
		listitem
			image, url='https://framerusercontent.com/images/NLTbQQ0xglYxCUuNc3KzKBPj6D4.png'
		listitem
			image, url='https://framerusercontent.com/images/mNf0waetxbfn8lCPkDChT0sFESY.png'
		listitem
			image, url='https://framerusercontent.com/images/zTlXZRbDSM6VqBAAt4JCLwqurw.png'
	image, url='https://framerusercontent.com/images/IOSzbgwgh7x1huLC1zXSytIhA.png'
	list
		listitem
			image, url='https://framerusercontent.com/images/EtTgttYKvCSqsQxze65TjZIAidg.png'
		listitem
			image, url='https://framerusercontent.com/images/sJgO8SkRy9V4asgVWM5Y5GF6PQ.png'
		listitem
			image, url='https://framerusercontent.com/images/Fj9D97HT5WGKW2FTinEJegSZjU.png'
		listitem
			image, url='https://framerusercontent.com/images/OkKmWgIFEwKd8M0NHdloaf5K2iY.png'
	paragraph
		StaticText RESOURCES
	heading Blogs & Resources
	link New Integrations for Streamlined Workflows, url='https://corgea.com/blog/new-integrations-for-streamlined-workflows'
		image, url='https://framerusercontent.com/images/lWQKq6M9mV0Tvg9B1NQ1Of1C4.png?scale-down-to=512'
		heading New Integrations for Streamlined Workflows
	link Corgea Announces GitLab Integration, url='https://corgea.com/blog/corgea-announces-gitlab-integration'
		image, url='https://framerusercontent.com/images/3Iar82BzPRYUGntJnPFFsJGALs.png?scale-down-to=512'
		heading Corgea Announces GitLab Integration
	link Corgea Expands Language Support: C, C++, Ko..., url='https://corgea.com/blog/corgea-expands-language-support-c-c-kotlin-and-php-for-enhanced-code-security'
		image, url='https://framerusercontent.com/images/u1AZCG9DPieUr4tr4tVDrxKcj3k.png?scale-down-to=512'
		heading Corgea Expands Language Support: C, C++, Ko...
	link View all articles, url='https://corgea.com/blog'
		paragraph
		image
	image, url='https://framerusercontent.com/images/D9MqPUafoDCqfPP31yDLsC8oRGA.png'
	heading Diverse teams love what we offer
	list
		listitem
			image, url='https://framerusercontent.com/images/6VVoMLp5gJaUk8qs110M8oW2I.png'
			heading Sherif Nada
			paragraph
				StaticText Airbyte Founding Member & Engineering Lead
			paragraph
				StaticText Whereas most products are like compasses that vaguely tell you where to go, Corgea is a magic wand that immediately gets you there. It issues security patches with zero work from me.
		listitem
			image, url='https://framerusercontent.com/images/g0McRVUYGe5ZAHPjGRnoPGi1mFg.png'
			heading Stephen Singam
			paragraph
				StaticText Chief Information Security Officer
			paragraph
				StaticText In my career, rarely have I come across solutions that solve fundamental problems in security. Corgea has proven to me that automatically fixing code is possible, and it has been nothing short of impressive. It has given me peace of mind that things get done.
		listitem
			image, url='https://framerusercontent.com/images/xK39DfgOQyn1JVUXb9LPOhiPH4.png'
			heading Ryan Chow
			paragraph
				StaticText Co-founder Metalware & ex-Product Manager at SpaceX
			paragraph
				StaticText Building secure products is a challenge with vulnerabilities ever increasing. Corgea's approach to use AI to write security fixes is novel and powerful.
		listitem
			image, url='https://framerusercontent.com/images/aCOMPZa8HOEU9DLV6qYLXPiLzZw.png'
			heading Murat Basata
			paragraph
				StaticText Senior Data Scientist
			paragraph
				StaticText Using AI to write security fixes will be the future of how companies protect their most valuable intellectual property, and the Corgea team is the one to make that future happen.
	group Slideshow pagination controls
		button Scroll to page 1
		button Scroll to page 2
		button Scroll to page 3
		button Scroll to page 4
	heading Ready to fix with a click?
	paragraph
		StaticText Harden your software in less than 10 mins'
	link Start for free, url='https://www.corgea.app/registration/'
		paragraph
		image
	contentinfo
		link, url='https://www.linkedin.com/company/corgea/people/?viewAsMember=true'
			image
		link, url='https://twitter.com/CorgeaInc'
			image
		link, url='https://corgea-community.slack.com/join/shared_invite/zt-2cjmxat2f-Znvd06nP2gn9RYOSWrZI2A'
			image, url='https://framerusercontent.com/images/mDUUYsky4UjlsXuH7qO8NR7ag.png'
		heading Product
		paragraph
			link Pricing, url='https://corgea.com/Pricing'
		paragraph
			link About, url='https://corgea.com/about'
		paragraph
			link Contact, url='https://corgea.com/Contact'
		heading Resources
		paragraph
			link Blog, url='https://corgea.com/blog'
		paragraph
			link Docs, url='https://docs.corgea.app/introduction'
		paragraph
			link FAQ, url='https://corgea.com/FAQ'
		paragraph
			link Privacy, url='https://docs.corgea.app/privacy-policy'
		paragraph
			link Terms of Service, url='https://docs.corgea.app/terms-of-service'
		paragraph
			StaticText © 2024 Corgea Inc - Made with ❤ in California.
```
</details>



```
RootWebArea Corgea - About Us, focused, url='https://corgea.com/about'
	[932] link, center=(464,51), url='https://corgea.com/'
		image, url='https://framerusercontent.com/images/yGr2lcNPx7bOFsUXFFm5R7Vy8o.png'
	paragraph
		[938] link About, center=(827,50), url='https://corgea.com/about'
```
<details><summary>Show more</summary>

```
	paragraph
		[941] link Pricing, center=(888,50), url='https://corgea.com/Pricing'
	paragraph
		[944] link Docs, center=(944,50), url='https://docs.corgea.app/introduction'
	paragraph
		[947] link Learn, center=(995,50), url='https://corgea.com/Learn'
	paragraph
		[950] link Blog, center=(1045,50), url='https://corgea.com/blog'
	paragraph
		[953] link Contact, center=(1105,50), url='https://corgea.com/Contact'
	[955] link Start for free, center=(1466,51), url='https://www.corgea.app/registration/'
		paragraph
		image
	heading We built a new way  to secure applications
	paragraph
		StaticText Corgea ensures application security by focusing on development speed, value delivery, and ease of use. Fix code security issues before they lead to incidents. Get started with Corgea in under 5 minutes.
	heading Who's behind Corgea
	[973] link Ahmad Sadeddin CEO, center=(562,787), inner_text=Ahmad Sadeddin
CEO  , url='https://www.linkedin.com/in/asadeddin/'
		image, url='https://framerusercontent.com/images/03jmeSiVrulXB6tDgdq5gMhSFc.png?scale-down-to=512'
		heading Ahmad Sadeddin
		heading CEO
	[982] link Adam Bronte Founding Engineer, center=(828,787), inner_text=Adam Bronte
Founding Engineer, url='https://www.linkedin.com/in/adambronte/'
		image, url='https://framerusercontent.com/images/hn2oYtvdit0B4p8MtWNYTYjBDDw.jpeg?scale-down-to=512'
		heading Adam Bronte
		heading Founding Engineer
	[991] link Yutaka Hosoai Founding Engineer, center=(1092,787), inner_text=Yutaka Hosoai
Founding Engineer, url='https://www.linkedin.com/in/yutakahosoai/'
		image, url='https://framerusercontent.com/images/tiKdHLWkuP7VJXgOFcafvfAZCCE.png?scale-down-to=512'
		heading Yutaka Hosoai
		heading Founding Engineer
	[1000] link Tamara Abualhsan Founding Engineer, center=(1358,787), inner_text=Tamara Abualhsan
Founding Engineer, url='https://www.linkedin.com/in/tamara-abualhsan/'
		image, url='https://framerusercontent.com/images/VDAj7CNTpQIPFjqippzhbS1pPG4.jpg?scale-down-to=1024'
		heading Tamara Abualhsan
		heading Founding Engineer
	link Al Ghous Advisor & CISO at Snapdocs, url='https://www.linkedin.com/in/alghous/'
		image, url='https://framerusercontent.com/images/OSI1xLFVeVieD6q3etckhRGrsY.jpeg?scale-down-to=512'
		heading Al Ghous
		heading Advisor & CISO at Snapdocs
	link Donna Wilczek Advisor & CPO at Oomnitza, url='https://www.linkedin.com/in/dwilczek/'
		image, url='https://framerusercontent.com/images/OnCLeSHBJBY71QsasW6wHTkolM.jpeg?scale-down-to=512'
		heading Donna Wilczek
		heading Advisor & CPO at Oomnitza
	link Jawed Karim Investor & Co-founder of Youtube, url='https://www.yventures.com/'
		image, url='https://framerusercontent.com/images/CaHK2daLDFJIGF9qyxLxuMDPY8.jpeg?scale-down-to=512'
		heading Jawed Karim
		heading Investor & Co-founder of Youtube
	link Sam Kassomeh Investor & Co-founder of SecurityScoreCard, url='https://www.linkedin.com/in/skassoum/'
		image, url='https://framerusercontent.com/images/LPwEhYLIkpU7JZOy3pUa9qdcfH8.jpeg'
		heading Sam Kassomeh
		heading Investor & Co-founder of SecurityScoreCard
	link Max Ament Investor & Serial Enterpenuer, url='https://www.linkedin.com/in/ament/'
		image, url='https://framerusercontent.com/images/KjFGEEidAHA6SiBQqk7s1QZjzU.jpeg?scale-down-to=512'
		heading Max Ament
		heading Investor & Serial Enterpenuer
	link Parker Treacy Investor & Co-founder of Cobli, url='https://www.linkedin.com/in/parkertreacy/'
		image, url='https://framerusercontent.com/images/7BBWRzLMgRLVSxn2nO4u6Mm90N4.jpeg'
		heading Parker Treacy
		heading Investor & Co-founder of Cobli
	link Tarek Alaruri Investor & Serial Entrepreneur, url='https://www.linkedin.com/in/tarekalaruri/'
		image, url='https://framerusercontent.com/images/ScGdJRui4sPAkr5EPCTsVLXdfI.png'
		heading Tarek Alaruri
		heading Investor & Serial Entrepreneur
	link Ian Eldred Pudney Investor, CTO of Repacket & ex-Google Security Engineer, url='https://www.linkedin.com/in/bitshift/'
		image, url='https://framerusercontent.com/images/SsValTuyvfzi5QxUSuPekvlkdwQ.jpeg?scale-down-to=512'
		heading Ian Eldred Pudney
		heading Investor, CTO of Repacket & ex-Google Security Engineer
	link Mahmoud Ali Investor & ex-Security Leader Reddit, Airbnb, and BitMex, url='https://www.linkedin.com/in/aliatbay/'
		image, url='https://framerusercontent.com/images/EbhZYvkxQpFZ7NupGipWlgYnQ.jpeg'
		heading Mahmoud Ali
		heading Investor & ex-Security Leader Reddit, Airbnb, and BitMex
	link Sherif Nada Investor, Founding Engineer at Airbyte, url='https://www.linkedin.com/in/shrif/'
		image, url='https://framerusercontent.com/images/CHwrjXBiyf21DyHaY6fGsiVa0U.jpg'
		heading Sherif Nada
		heading Investor, Founding Engineer at Airbyte
	list
		listitem
			image, url='https://framerusercontent.com/images/2HtEmMo2YGUH7t1fu5ZK8zoIGc.png?scale-down-to=512'
		listitem
			image, url='https://framerusercontent.com/images/EEpe9Q6EMuYGLfVDhZlXTrxjPGc.png'
		listitem
			image, url='https://framerusercontent.com/images/py42ih36smYjh0kRzUJBgxPX6U.png'
		listitem
			image, url='https://framerusercontent.com/images/ntzBcCrCi9Ww38jy9h3MhLtzzCE.png'
		listitem
			image, url='https://framerusercontent.com/images/zUA1ou52yNv9zfCzselydFg2Ll8.png?scale-down-to=512'
	heading As someone deeply invested in both the startup and enterprise security landscapes, I recognize the immense value Corgea brings to the table. By reducing false positives and fitting seamlessly into developer workflows, Corgea empowers security teams to focus on real risks. I’m thrilled to support Corgea as it reshapes the future of application security and meets the demands of a rapidly evolving threat landscape.
	image, url='https://framerusercontent.com/images/jFRDGY3K9ZM6SoheVPHd7jl450.png?scale-down-to=512'
	heading Sam Kassoumeh
	paragraph
		StaticText Angel Investor and
	paragraph
		StaticText Co-Founder of SecurityScorecard
	heading Ready to fix with a click?
	paragraph
		StaticText Harden your software in less than 10 mins'
	link Start for free, url='https://www.corgea.app/registration/'
		paragraph
		image
	contentinfo
		link, url='https://www.linkedin.com/company/corgea/people/?viewAsMember=true'
			image
		link, url='https://twitter.com/CorgeaInc'
			image
		link, url='https://corgea-community.slack.com/join/shared_invite/zt-2cjmxat2f-Znvd06nP2gn9RYOSWrZI2A'
			image, url='https://framerusercontent.com/images/mDUUYsky4UjlsXuH7qO8NR7ag.png'
		heading Product
		paragraph
			link Pricing, url='https://corgea.com/Pricing'
		paragraph
			link About, url='https://corgea.com/about'
		paragraph
			link Contact, url='https://corgea.com/Contact'
		heading Resources
		paragraph
			link Blog, url='https://corgea.com/blog'
		paragraph
			link Docs, url='https://docs.corgea.app/introduction'
		paragraph
			link FAQ, url='https://corgea.com/FAQ'
		paragraph
			link Privacy, url='https://docs.corgea.app/privacy-policy'
		paragraph
			link Terms of Service, url='https://docs.corgea.app/terms-of-service'
		paragraph
			StaticText © 2024 Corgea Inc - Made with ❤ in California.
```
</details>

**Reasoning for action:** This action allows me to understand more about Corgea and its services before diving into the Pricing section. However, in this specific task, clicking on the About page may not be necessary as my end goal is to find pricing options and start registration for the Free tier. I acknowledge that clicking the About link does not immediately lead me to relevant pricing information.

**Action:** click('66') # Click on the About link to learn more about the company.

**Change Description:** The browser's content changed from the Corgea home page to the About Us page, updating the URL to 'https://corgea.com/about' and displaying new information about the company's mission, team members, and their roles, including links to their LinkedIn profiles.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://corgea.com/about

https://corgea.com/Pricing

**Content (before/after):** 

```
RootWebArea Corgea - About Us, focused, url='https://corgea.com/about'
	[932] link, center=(464,51), url='https://corgea.com/'
		image, url='https://framerusercontent.com/images/yGr2lcNPx7bOFsUXFFm5R7Vy8o.png'
	paragraph
		[938] link About, center=(827,50), url='https://corgea.com/about'
```
<details><summary>Show more</summary>

```
	paragraph
		[941] link Pricing, center=(888,50), url='https://corgea.com/Pricing'
	paragraph
		[944] link Docs, center=(944,50), url='https://docs.corgea.app/introduction'
	paragraph
		[947] link Learn, center=(995,50), url='https://corgea.com/Learn'
	paragraph
		[950] link Blog, center=(1045,50), url='https://corgea.com/blog'
	paragraph
		[953] link Contact, center=(1105,50), url='https://corgea.com/Contact'
	[955] link Start for free, center=(1466,51), url='https://www.corgea.app/registration/'
		paragraph
		image
	heading We built a new way  to secure applications
	paragraph
		StaticText Corgea ensures application security by focusing on development speed, value delivery, and ease of use. Fix code security issues before they lead to incidents. Get started with Corgea in under 5 minutes.
	heading Who's behind Corgea
	[973] link Ahmad Sadeddin CEO, center=(562,787), inner_text=Ahmad Sadeddin
CEO  , url='https://www.linkedin.com/in/asadeddin/'
		image, url='https://framerusercontent.com/images/03jmeSiVrulXB6tDgdq5gMhSFc.png?scale-down-to=512'
		heading Ahmad Sadeddin
		heading CEO
	[982] link Adam Bronte Founding Engineer, center=(828,787), inner_text=Adam Bronte
Founding Engineer, url='https://www.linkedin.com/in/adambronte/'
		image, url='https://framerusercontent.com/images/hn2oYtvdit0B4p8MtWNYTYjBDDw.jpeg?scale-down-to=512'
		heading Adam Bronte
		heading Founding Engineer
	[991] link Yutaka Hosoai Founding Engineer, center=(1092,787), inner_text=Yutaka Hosoai
Founding Engineer, url='https://www.linkedin.com/in/yutakahosoai/'
		image, url='https://framerusercontent.com/images/tiKdHLWkuP7VJXgOFcafvfAZCCE.png?scale-down-to=512'
		heading Yutaka Hosoai
		heading Founding Engineer
	[1000] link Tamara Abualhsan Founding Engineer, center=(1358,787), inner_text=Tamara Abualhsan
Founding Engineer, url='https://www.linkedin.com/in/tamara-abualhsan/'
		image, url='https://framerusercontent.com/images/VDAj7CNTpQIPFjqippzhbS1pPG4.jpg?scale-down-to=1024'
		heading Tamara Abualhsan
		heading Founding Engineer
	link Al Ghous Advisor & CISO at Snapdocs, url='https://www.linkedin.com/in/alghous/'
		image, url='https://framerusercontent.com/images/OSI1xLFVeVieD6q3etckhRGrsY.jpeg?scale-down-to=512'
		heading Al Ghous
		heading Advisor & CISO at Snapdocs
	link Donna Wilczek Advisor & CPO at Oomnitza, url='https://www.linkedin.com/in/dwilczek/'
		image, url='https://framerusercontent.com/images/OnCLeSHBJBY71QsasW6wHTkolM.jpeg?scale-down-to=512'
		heading Donna Wilczek
		heading Advisor & CPO at Oomnitza
	link Jawed Karim Investor & Co-founder of Youtube, url='https://www.yventures.com/'
		image, url='https://framerusercontent.com/images/CaHK2daLDFJIGF9qyxLxuMDPY8.jpeg?scale-down-to=512'
		heading Jawed Karim
		heading Investor & Co-founder of Youtube
	link Sam Kassomeh Investor & Co-founder of SecurityScoreCard, url='https://www.linkedin.com/in/skassoum/'
		image, url='https://framerusercontent.com/images/LPwEhYLIkpU7JZOy3pUa9qdcfH8.jpeg'
		heading Sam Kassomeh
		heading Investor & Co-founder of SecurityScoreCard
	link Max Ament Investor & Serial Enterpenuer, url='https://www.linkedin.com/in/ament/'
		image, url='https://framerusercontent.com/images/KjFGEEidAHA6SiBQqk7s1QZjzU.jpeg?scale-down-to=512'
		heading Max Ament
		heading Investor & Serial Enterpenuer
	link Parker Treacy Investor & Co-founder of Cobli, url='https://www.linkedin.com/in/parkertreacy/'
		image, url='https://framerusercontent.com/images/7BBWRzLMgRLVSxn2nO4u6Mm90N4.jpeg'
		heading Parker Treacy
		heading Investor & Co-founder of Cobli
	link Tarek Alaruri Investor & Serial Entrepreneur, url='https://www.linkedin.com/in/tarekalaruri/'
		image, url='https://framerusercontent.com/images/ScGdJRui4sPAkr5EPCTsVLXdfI.png'
		heading Tarek Alaruri
		heading Investor & Serial Entrepreneur
	link Ian Eldred Pudney Investor, CTO of Repacket & ex-Google Security Engineer, url='https://www.linkedin.com/in/bitshift/'
		image, url='https://framerusercontent.com/images/SsValTuyvfzi5QxUSuPekvlkdwQ.jpeg?scale-down-to=512'
		heading Ian Eldred Pudney
		heading Investor, CTO of Repacket & ex-Google Security Engineer
	link Mahmoud Ali Investor & ex-Security Leader Reddit, Airbnb, and BitMex, url='https://www.linkedin.com/in/aliatbay/'
		image, url='https://framerusercontent.com/images/EbhZYvkxQpFZ7NupGipWlgYnQ.jpeg'
		heading Mahmoud Ali
		heading Investor & ex-Security Leader Reddit, Airbnb, and BitMex
	link Sherif Nada Investor, Founding Engineer at Airbyte, url='https://www.linkedin.com/in/shrif/'
		image, url='https://framerusercontent.com/images/CHwrjXBiyf21DyHaY6fGsiVa0U.jpg'
		heading Sherif Nada
		heading Investor, Founding Engineer at Airbyte
	list
		listitem
			image, url='https://framerusercontent.com/images/2HtEmMo2YGUH7t1fu5ZK8zoIGc.png?scale-down-to=512'
		listitem
			image, url='https://framerusercontent.com/images/EEpe9Q6EMuYGLfVDhZlXTrxjPGc.png'
		listitem
			image, url='https://framerusercontent.com/images/py42ih36smYjh0kRzUJBgxPX6U.png'
		listitem
			image, url='https://framerusercontent.com/images/ntzBcCrCi9Ww38jy9h3MhLtzzCE.png'
		listitem
			image, url='https://framerusercontent.com/images/zUA1ou52yNv9zfCzselydFg2Ll8.png?scale-down-to=512'
	heading As someone deeply invested in both the startup and enterprise security landscapes, I recognize the immense value Corgea brings to the table. By reducing false positives and fitting seamlessly into developer workflows, Corgea empowers security teams to focus on real risks. I’m thrilled to support Corgea as it reshapes the future of application security and meets the demands of a rapidly evolving threat landscape.
	image, url='https://framerusercontent.com/images/jFRDGY3K9ZM6SoheVPHd7jl450.png?scale-down-to=512'
	heading Sam Kassoumeh
	paragraph
		StaticText Angel Investor and
	paragraph
		StaticText Co-Founder of SecurityScorecard
	heading Ready to fix with a click?
	paragraph
		StaticText Harden your software in less than 10 mins'
	link Start for free, url='https://www.corgea.app/registration/'
		paragraph
		image
	contentinfo
		link, url='https://www.linkedin.com/company/corgea/people/?viewAsMember=true'
			image
		link, url='https://twitter.com/CorgeaInc'
			image
		link, url='https://corgea-community.slack.com/join/shared_invite/zt-2cjmxat2f-Znvd06nP2gn9RYOSWrZI2A'
			image, url='https://framerusercontent.com/images/mDUUYsky4UjlsXuH7qO8NR7ag.png'
		heading Product
		paragraph
			link Pricing, url='https://corgea.com/Pricing'
		paragraph
			link About, url='https://corgea.com/about'
		paragraph
			link Contact, url='https://corgea.com/Contact'
		heading Resources
		paragraph
			link Blog, url='https://corgea.com/blog'
		paragraph
			link Docs, url='https://docs.corgea.app/introduction'
		paragraph
			link FAQ, url='https://corgea.com/FAQ'
		paragraph
			link Privacy, url='https://docs.corgea.app/privacy-policy'
		paragraph
			link Terms of Service, url='https://docs.corgea.app/terms-of-service'
		paragraph
			StaticText © 2024 Corgea Inc - Made with ❤ in California.
```
</details>



```
RootWebArea Corgea - Pricing, focused, url='https://corgea.com/Pricing'
	[1253] link, center=(464,51), url='https://corgea.com/'
		image, url='https://framerusercontent.com/images/yGr2lcNPx7bOFsUXFFm5R7Vy8o.png'
	paragraph
		[1259] link About, center=(827,50), url='https://corgea.com/about'
```
<details><summary>Show more</summary>

```
	paragraph
		[1262] link Pricing, center=(888,50), url='https://corgea.com/Pricing'
	paragraph
		[1265] link Docs, center=(944,50), url='https://docs.corgea.app/introduction'
	paragraph
		[1268] link Learn, center=(995,50), url='https://corgea.com/Learn'
	paragraph
		[1271] link Blog, center=(1045,50), url='https://corgea.com/blog'
	paragraph
		[1274] link Contact, center=(1105,50), url='https://corgea.com/Contact'
	[1276] link Start for free, center=(1466,51), url='https://www.corgea.app/registration/'
		paragraph
		image
	paragraph
		StaticText PRICING
	heading Security for stress-free engineering
	paragraph
		StaticText FREE
	heading $0
	[1297] link Get Started, center=(650,587), url='https://www.corgea.app/registration/'
		paragraph
		image
	image
	paragraph
		StaticText Up to 10 fixes for 2 repos
	image
	paragraph
		StaticText Integrations into your SAST
	image
	paragraph
		StaticText Integration to your code repository
	image
	paragraph
		StaticText For teams of 5 engineers
	paragraph
		StaticText TEAM
	heading $39
	paragraph
		StaticText Per contributing dev per month
	[1342] link Get Started, center=(960,615), url='https://www.corgea.app/registration/'
		paragraph
		image
	image
	paragraph
		StaticText Business Logic Vulnerability Detection (Private Beta)
	image
	paragraph
		StaticText Unlimited Security Fixes
	image
	paragraph
		StaticText Unlimited Repos
	image
	paragraph
		StaticText Integrations into your SAST
	image
	paragraph
		StaticText Integration to your code repository
	image
	paragraph
		StaticText For teams of 50 engineers
	image
	paragraph
		StaticText RBAC
	paragraph
		StaticText ENTERPRISE
	heading Custom
	[1405] link Get Started, center=(1270,552), url='https://www.corgea.app/registration/'
		paragraph
		image
	image
	paragraph
		StaticText Business Logic Vulnerability Detection (Private Beta)
	image
	paragraph
		StaticText Private LLM model
	image
	paragraph
		StaticText Private Cloud Deployment
	image
	paragraph
		StaticText Unlimited Security Fixes
	image
	paragraph
		StaticText Unlimited Repos
	image
	paragraph
		StaticText Unlimited Teams
	image
	paragraph
		StaticText Integrations into your SAST
	image
	paragraph
		StaticText Integration to your code repository
	image
	paragraph
		StaticText Single-sign on
	image
	paragraph
		StaticText RBAC
	paragraph
		StaticText FAQ
	heading Frequently asked questions
	paragraph
	image
	paragraph
	image
	paragraph
	image
	paragraph
	image
	link More FAQ, url='https://corgea.com/FAQ'
		paragraph
		image
	heading Ready to fix with a click?
	paragraph
		StaticText Harden your software in less than 10 mins'
	link Start for free, url='https://www.corgea.app/registration/'
		paragraph
		image
	contentinfo
		link, url='https://www.linkedin.com/company/corgea/people/?viewAsMember=true'
			image
		link, url='https://twitter.com/CorgeaInc'
			image
		link, url='https://corgea-community.slack.com/join/shared_invite/zt-2cjmxat2f-Znvd06nP2gn9RYOSWrZI2A'
			image, url='https://framerusercontent.com/images/mDUUYsky4UjlsXuH7qO8NR7ag.png'
		heading Product
		paragraph
			link Pricing, url='https://corgea.com/Pricing'
		paragraph
			link About, url='https://corgea.com/about'
		paragraph
			link Contact, url='https://corgea.com/Contact'
		heading Resources
		paragraph
			link Blog, url='https://corgea.com/blog'
		paragraph
			link Docs, url='https://docs.corgea.app/introduction'
		paragraph
			link FAQ, url='https://corgea.com/FAQ'
		paragraph
			link Privacy, url='https://docs.corgea.app/privacy-policy'
		paragraph
			link Terms of Service, url='https://docs.corgea.app/terms-of-service'
		paragraph
			StaticText © 2024 Corgea Inc - Made with ❤ in California.
```
</details>

**Reasoning for action:** I clicked on the 'Pricing' link (link number 941) because this is the next logical step to meet the user's goal of understanding the pricing options for Corgea's services. By navigating to the Pricing page, I will have access to the information regarding different pricing tiers, which is essential for the user to evaluate their options.

**Action:** click('941') # Click on the Pricing link to learn about the service costs.

**Change Description:** After clicking the Pricing link, the browser navigated to the Corgea Pricing page, where the content updated to reflect pricing information for various plans including Free and Team options, and the focus shifted to the new page with the title 'Corgea - Pricing'.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://corgea.com/Pricing

https://www.corgea.app/registration/

**Content (before/after):** 

```
RootWebArea Corgea - Pricing, focused, url='https://corgea.com/Pricing'
	[1253] link, center=(464,51), url='https://corgea.com/'
		image, url='https://framerusercontent.com/images/yGr2lcNPx7bOFsUXFFm5R7Vy8o.png'
	paragraph
		[1259] link About, center=(827,50), url='https://corgea.com/about'
```
<details><summary>Show more</summary>

```
	paragraph
		[1262] link Pricing, center=(888,50), url='https://corgea.com/Pricing'
	paragraph
		[1265] link Docs, center=(944,50), url='https://docs.corgea.app/introduction'
	paragraph
		[1268] link Learn, center=(995,50), url='https://corgea.com/Learn'
	paragraph
		[1271] link Blog, center=(1045,50), url='https://corgea.com/blog'
	paragraph
		[1274] link Contact, center=(1105,50), url='https://corgea.com/Contact'
	[1276] link Start for free, center=(1466,51), url='https://www.corgea.app/registration/'
		paragraph
		image
	paragraph
		StaticText PRICING
	heading Security for stress-free engineering
	paragraph
		StaticText FREE
	heading $0
	[1297] link Get Started, center=(650,587), url='https://www.corgea.app/registration/'
		paragraph
		image
	image
	paragraph
		StaticText Up to 10 fixes for 2 repos
	image
	paragraph
		StaticText Integrations into your SAST
	image
	paragraph
		StaticText Integration to your code repository
	image
	paragraph
		StaticText For teams of 5 engineers
	paragraph
		StaticText TEAM
	heading $39
	paragraph
		StaticText Per contributing dev per month
	[1342] link Get Started, center=(960,615), url='https://www.corgea.app/registration/'
		paragraph
		image
	image
	paragraph
		StaticText Business Logic Vulnerability Detection (Private Beta)
	image
	paragraph
		StaticText Unlimited Security Fixes
	image
	paragraph
		StaticText Unlimited Repos
	image
	paragraph
		StaticText Integrations into your SAST
	image
	paragraph
		StaticText Integration to your code repository
	image
	paragraph
		StaticText For teams of 50 engineers
	image
	paragraph
		StaticText RBAC
	paragraph
		StaticText ENTERPRISE
	heading Custom
	[1405] link Get Started, center=(1270,552), url='https://www.corgea.app/registration/'
		paragraph
		image
	image
	paragraph
		StaticText Business Logic Vulnerability Detection (Private Beta)
	image
	paragraph
		StaticText Private LLM model
	image
	paragraph
		StaticText Private Cloud Deployment
	image
	paragraph
		StaticText Unlimited Security Fixes
	image
	paragraph
		StaticText Unlimited Repos
	image
	paragraph
		StaticText Unlimited Teams
	image
	paragraph
		StaticText Integrations into your SAST
	image
	paragraph
		StaticText Integration to your code repository
	image
	paragraph
		StaticText Single-sign on
	image
	paragraph
		StaticText RBAC
	paragraph
		StaticText FAQ
	heading Frequently asked questions
	paragraph
	image
	paragraph
	image
	paragraph
	image
	paragraph
	image
	link More FAQ, url='https://corgea.com/FAQ'
		paragraph
		image
	heading Ready to fix with a click?
	paragraph
		StaticText Harden your software in less than 10 mins'
	link Start for free, url='https://www.corgea.app/registration/'
		paragraph
		image
	contentinfo
		link, url='https://www.linkedin.com/company/corgea/people/?viewAsMember=true'
			image
		link, url='https://twitter.com/CorgeaInc'
			image
		link, url='https://corgea-community.slack.com/join/shared_invite/zt-2cjmxat2f-Znvd06nP2gn9RYOSWrZI2A'
			image, url='https://framerusercontent.com/images/mDUUYsky4UjlsXuH7qO8NR7ag.png'
		heading Product
		paragraph
			link Pricing, url='https://corgea.com/Pricing'
		paragraph
			link About, url='https://corgea.com/about'
		paragraph
			link Contact, url='https://corgea.com/Contact'
		heading Resources
		paragraph
			link Blog, url='https://corgea.com/blog'
		paragraph
			link Docs, url='https://docs.corgea.app/introduction'
		paragraph
			link FAQ, url='https://corgea.com/FAQ'
		paragraph
			link Privacy, url='https://docs.corgea.app/privacy-policy'
		paragraph
			link Terms of Service, url='https://docs.corgea.app/terms-of-service'
		paragraph
			StaticText © 2024 Corgea Inc - Made with ❤ in California.
```
</details>



```
RootWebArea Just a moment..., url='https://www.corgea.app/registration/'
	main
		heading www.corgea.app
		paragraph
			StaticText Verifying you are human. This may take a few seconds.
```
<details><summary>Show more</summary>

```
		StaticText www.corgea.app needs to review the security of your connection before proceeding.
	contentinfo
		StaticText Ray ID:
		code
			StaticText 8fb9daae2d03dada
		StaticText Performance & security by
		[39] link Cloudflare, center=(1042,1055), url='https://www.cloudflare.com/?utm_source=challenge&utm_campaign=j'
```
</details>

**Reasoning for action:** My reasoning for this action was to fulfill the user's objective of beginning the registration process for the Free tier after understanding the pricing options. By clicking the 'Get Started' link associated with the Free tier, I ensure that the user is taken to the relevant registration page where they can provide the necessary information to evaluate Corgea's services. This action is crucial in moving closer to completing the user's task of assessing their security needs.

**Action:** click('1297') # Click on the Get Started button for the Free tier to explore the registration process.

**Change Description:** After clicking the 'Get Started' button for the Free tier, the browser navigated to the registration page at 'https://www.corgea.app/registration/', displaying a temporary verification screen indicating that the site is reviewing the security of the connection.

**Screenshot before:****Screenshot after:**---

