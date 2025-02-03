# Task

**User Story for BotCity Sign-Up Process**

As a potential user interested in intelligent automation solutions,,
I sign up for a free trial on the BotCity platform,
so that I can explore its features and understand how it can improve my organization's automation processes.

**Success definition:** Given I am on the BotCity homepage and interested in learning more about their automation solutions.
When I click on the 'Start for free' link and fill in my email address, then click the 'SIGN UP' button,
Then I should see a verification message indicating that a verification link has been sent to my email.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.botcity.dev/

https://www.botcity.dev/

**Content (before/after):** 

```
RootWebArea BotCity | Python RPA Software and Intelligent Automation Orchestrator, focused, url='https://www.botcity.dev/'
	paragraph
		StaticText This website stores cookies on your computer. These cookies are used to collect information about how you interact with our website and allow us to remember you. We use this information in order to improve and customize your browsing experience and for analytics and metrics about our visitors both on this website and other media. To find out more about the cookies we use, see our Privacy Policy
	paragraph
		StaticText If you decline, your information won’t be tracked when you visit this website. A single cookie will be used in your browser to remember your preference not to be tracked.
```
<details><summary>Show more</summary>

```
	[79] button Accept All, center=(1217,1034)
	[80] button Decline All, center=(1317,1034)
	banner
		link home, url='https://www.botcity.dev/'
			image BotCity Logo, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/66193a64d8ee208d28e3796f_logo_botcity_2024.svg'
		navigation
			button Why BotCity, expanded=False, hasPopup='menu'
				image
			button Products, expanded=False, hasPopup='menu'
				image
			link Pricing, url='https://meetings.hubspot.com/andreabotcity/botcity-sales-global-calls'
			link Security, url='https://www.botcity.dev/security'
			link Partners, url='https://www.botcity.dev/become-a-partner'
			link Case Studies, url='https://www.botcity.dev/cases'
			button Resources, expanded=False, hasPopup='menu'
				image
			link Log In, url='https://developers.botcity.dev/login'
			link Sign Up, url='https://developers.botcity.dev/signup'
			link Book a Live Demo, url='https://meetings.hubspot.com/andreabotcity/botcity-sales-global-calls'
	main
		banner
			[163] link home, center=(164,36), url='https://www.botcity.dev/'
				image BotCity Logo, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/66193a64d8ee208d28e3796f_logo_botcity_2024.svg'
			navigation
				[168] button Why BotCity, center=(322,36), expanded=False, hasPopup='menu'
					image
				[178] button Products, center=(427,36), expanded=False, hasPopup='menu'
					image
				[188] link Pricing, center=(504,36), inner_text=Pricing
, url='https://meetings.hubspot.com/andreabotcity/botcity-sales-global-calls'
				[190] link Security, center=(567,36), url='https://www.botcity.dev/security'
				[191] link Partners, center=(636,36), url='https://www.botcity.dev/become-a-partner'
				[192] link Case Studies, center=(720,36), inner_text=Case Studies
, url='https://www.botcity.dev/cases'
				[195] button Resources, center=(822,36), expanded=False, hasPopup='menu'
					image
				[226] link Log In, center=(1516,36), url='https://developers.botcity.dev/login'
				[227] link Sign Up, center=(1607,36), url='https://developers.botcity.dev/signup'
				[228] link Book a Live Demo, center=(1744,36), url='https://meetings.hubspot.com/andreabotcity/botcity-sales-global-calls'
		heading Real
		StaticText Governance
		StaticText Security
		StaticText Insights
		StaticText Control
		heading for Python RPA + AI
		paragraph
			StaticText Unlock the full potential of intelligent automation with an Orchestrator for Python automations, with no lock-in constraints.
		[264] link Start for free, center=(384,517), url='https://developers.botcity.dev/signup'
		[265] link Talk to experts, center=(534,517), url='https://meetings.hubspot.com/andreabotcity/botcity-sales-global-calls'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/66339e22c313c834fdad7fdf_Group%201%20(1).svg'
		heading Trusted by 1000+ companies in 70+ countries
		image Logo da LG, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fdc09c26b074d9ac4e03_LG_logo_(2014).svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fe8afea62ee7a549108a_ey.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fd862ce20de2d9f9c4ea_y.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fd40a400283747a68c70_Correios_(2014).svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fd19e4d8d41a67e02dd0_Algar_Telecom_logo.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fc6698bf4a69e5ed7cf2_sicoob-vector-logo.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9ffbc3887f2be7a7d582a_bayer.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fcd5ae17d297037019c2_h.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/66188ea210f8f36ed6656ddd_b93fa752-8cec-4fb8-92c8-bf2ab4c0b444___af80d9a5c64906e0662936151537ff10.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/66188e9fc9085c77fdabdd96_extra.svg'
		image Logo da LG, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fdc09c26b074d9ac4e03_LG_logo_(2014).svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fe8afea62ee7a549108a_ey.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fd862ce20de2d9f9c4ea_y.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fd40a400283747a68c70_Correios_(2014).svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fd19e4d8d41a67e02dd0_Algar_Telecom_logo.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fc6698bf4a69e5ed7cf2_sicoob-vector-logo.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9ffbc3887f2be7a7d582a_bayer.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fcd5ae17d297037019c2_h.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/66188ea210f8f36ed6656ddd_b93fa752-8cec-4fb8-92c8-bf2ab4c0b444___af80d9a5c64906e0662936151537ff10.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/66188e9fc9085c77fdabdd96_extra.svg'
		heading Why BotCity for Hyperautomation?
		heading Up to 50%
		paragraph
			StaticText Reduction in RPA license costs + strategic indicator reports for stakeholders and tech teams.
		heading 15X faster
		paragraph
			StaticText Robots with end-to-end governance and orchestration.
		heading Works everywhere
		paragraph
			StaticText From Citrix to SAP. From Windows to Linux.
		heading No vendor lock-in
		paragraph
			StaticText The code is forever yours. Free yourself from technical constraints and avoid dependency on vendors.
		StaticText The best platform for your tech team. The optimal ROI for your stakeholders.
		heading End-to-end Orchestration
		paragraph
			StaticText The best cloud-based orchestrator for code-based automations. Go beyond scheduling to achieve complete governance and control.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Create scheduling rules
			StaticText and never lose an automation execution.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Real-time alerts
			StaticText for stakeholders via Microsoft Teams, Email, WhatsApp.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Enable autonomy and segmentation
			StaticText across business areas with user groups and repositories.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Downtime reduction
			StaticText with automatic error reporting.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Infrastructure optimization
			StaticText with automatic load balancing.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Advanced item management
			StaticText with batch processing.
		link Learn more, url='https://www.botcity.dev/orchestrator'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/66339e9ef3383e90c49460b9_Group%203%20(1).svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/66339eb7d94e175c48639406_Group%204%20(1).svg'
		heading Global KPIs visibility with BotCity Insights
		paragraph
			StaticText Give your stakeholders full visibility of the results of your CoE. Consolidate and integrate KPIs directly into BotCity Orchestrator.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Finance Reports:
			StaticText Monitor ROI, FTE, and Savings segmented on the business and process level.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Efficiency:
			StaticText Generate insights for continuous improvement using efficiency indicators, common failures, and downtime rates.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Initiative and infrastructure evolution:
			StaticText Analyze automation evolution over time and agent utilization rates to optimize infrastructure.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Seamlessly integrate with BI solutions
			StaticText , ranging from Power BI to Grafana.
		link More about BotCity Insights, url='https://www.botcity.dev/insights'
		heading Speed up development
		paragraph
			StaticText Increase developer productivity and put automations into production in just a few days.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Develop complex automations
			StaticText , including ERPs, Legacy Systems, Desktop, and Web Applications.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Python libraries and plugins:
			StaticText Ready-to-use code snippets for daily operations.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText VSCode extension:
			StaticText Effortlessly generate Python code from any UI interaction using BotCity Studio’s computer vision coding assistant.
		link Learn more about BotCity Devtools, url='https://www.botcity.dev/automation-suite'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/66339e6ef42ba2e7bad79c52_Group%202%20(1).svg'
		region carousel
			group 1 of 2
				image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/661895fc6d0a291ec1d9d88f_logo-2018-header.svg'
				heading Intelligent Automation + AI
				StaticText Hyperautomation in Python for faster results.
				heading K
					marquee
						StaticText 100
				StaticText Hours saved (6 months)
				heading +%
					marquee
						StaticText 63
				StaticText Increase in Full-Time Equivalent (FTE)
				heading
					marquee
						StaticText 20
				StaticText Parallel agents
				heading +%
					marquee
						StaticText 175
				StaticText Productivity in RPA Development
				link Read full customer story Arrow Right, url='https://blog.botcity.dev/pt-br/2024/01/29/andrade-gutierrez-rpa-python/'
					image Arrow Right
				image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/661c775f87fc7458700f5795_quote.svg'
				blockquote
					StaticText We were using a low-code platform, and after adopting BotCity, our RPA initiative scaled up more rapidly. We accelerated the increase of ROI and FTE and also reduced license costs.
				paragraph
					strong
						StaticText Pieter Vosholyn
					StaticText , IT Manager at Andrade Gutierrez
			button previous slide
				StaticText 
			button next slide
				StaticText 
		link See our Case Studies, url='https://www.botcity.dev/cases'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/661d18f1f446c0aaa18b4674_RoboticProcessAutomation(RPA)_HighPerformer_Enterprise_HighPerformer.png'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/661d18ed51373c04abea5f37_RoboticProcessAutomation(RPA)_BestUsability_Total.png'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/661d18ed8d1dd65c42a9d9ab_RoboticProcessAutomation(RPA)_UsersMostLikelyToRecommend_Enterprise_Nps.png'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/661d18ed408213585db54a6d_Best-relationship-spring-24.webp'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/661d18ede9c09ea6b6215a50_RoboticProcessAutomation(RPA)_EasiestToUse_Enterprise_EaseOfUse.png'
		heading Customer's use cases
		image
		heading Construction
			strong
		paragraph
			StaticText Learn how a construction company reduced its supplier validation process on SAP from
			strong
				StaticText 10 days to 6 minutes.
		link Learn more, url='https://blog.botcity.dev/2023/06/16/python-rpa-sap-supply-chain-construction/'
		image
		heading Manufacturing
			strong
		paragraph
			StaticText Learn how a manufacturing company migrated from low-code and
			strong
				StaticText saved 70% in RPA licenses.
		link Learn more, url='https://blog.botcity.dev/2023/06/16/manufacturer-saved-70-migration-uipath-python-rpa/'
		image
		heading Engineering
			strong
		paragraph
			StaticText Learn how a multinational engineering company made their
			strong
				StaticText bots 10x faster
			StaticText than low-code with Python RPA.
		link Learn more, url='https://blog.botcity.dev/2023/06/16/rpa-saving-licenses-blueprism-to-python/'
		image
		heading Software ERP
			strong
		paragraph
			StaticText Learn how an ERP provider
			strong
				StaticText reduced 50% their support tickets
			StaticText with automated interface testing.
		link Learn more, url='https://blog.botcity.dev/2023/06/16/botcity-ui-testing-interface-testing-erp/'
		heading Learn more about Python RPA
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/6489c2149139b3c0d8a86370_Vectors-Wrapper.svg'
		heading Developing automations with computer vision
			strong
		paragraph
			StaticText This course teaches you how to create and orchestrate automation for any system using computer vision.
		link Learn more, url='https://developers.botcity.dev/academy/'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65bb8752310f48658c3021e7_python%20rpa%20orchestration-p-500.png'
		heading Python RPA Orchestration
			strong
		paragraph
			StaticText Learn the key features of the orchestrator in a hands-on approach. Discover the benefits and advantages of using each resource to enhance your automation processes.
		link Learn more, url='https://developers.botcity.dev/academy'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65bb88f51d57981d75461525_sap%20automation%20rpa%20python%20botcity%20marcelo%20cruz-p-500.png'
		heading SAP Automation with Python and BotCity
			strong
		paragraph
			StaticText Explore SAP automation with Python and BotCity in this practical course. Learn essential techniques to streamline and optimize SAP processes efficiently.
		link Learn more, url='https://developers.botcity.dev/academy'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65bb8833a0ce27cc4dc0086c_python-rpa-chatgpt-bard-openai.jpg'
		heading Python RPA, ChatGPT, Bard & OpenAI
			strong
		paragraph
			StaticText Build AI Automation Python Framework Integrating BotCity-RPA, OpenAI, ChatGPT &amp; Google Bard. Learn Next-Gen AI SkillSet
		link Learn more, url='https://www.udemy.com/course/python-driven-ai-automation-botcity-rpa-chatgpt-and-openai/'
		paragraph
			StaticText Get started with BotCity for free
		heading Unlock the full potential of intelligent automation
			strong
		paragraph
			StaticText Boost tech team productivity with BotCity's Python RPA and Intelligent Automation software. Drive ROI, orchestrate and enhance performance.
		link Sign up for free, url='https://developers.botcity.dev/signup'
	contentinfo
		link Botcity Logo, url='https://www.botcity.dev/'
			image Botcity Logo, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/66193a64d8ee208d28e3796f_logo_botcity_2024.svg'
		paragraph
			StaticText Build and orchestrate automation eliminating vendor lock-in. Leverage +440.000 Python libraries, full control of your code with enterprise-level governance, costing up to 5x less than low-code platforms.
		link GitHub Icon, url='https://github.com/botcity-dev'
			image GitHub Icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/648ae46909b094066028a8b2_icon-github.svg'
		link Linkedin logo, url='https://www.linkedin.com/company/botcity/?lipi=urn%3Ali%3Apage%3Ad_flagship3_search_srp_all%3BpxkmYgo3Tem0YJ9Vdw%2BT2g%3D%3D'
			image Linkedin logo, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/648ae4adeb905c3acb4eb83a_icon-LinkedIn.svg'
		link Youtube Logo, url='https://www.youtube.com/@botcity-dev'
			image Youtube Logo, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/661d204a06b06b114656522e_youtube%20(1).svg'
		link Twitter Logo, url='https://twitter.com/BotcityDev'
			image Twitter Logo, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/648ae4dfb4c707258cb88a61_icon-twitter.svg'
		link Log In, url='https://developers.botcity.dev/login'
		link Sign Up, url='https://developers.botcity.dev/signup'
		StaticText Why BotCity
		link Why Python RPA?, url='https://www.botcity.dev/wpr-old'
		link Python RPA x Low-Code, url='https://www.botcity.dev/python-rpa-x-low-code'
		link No Vendor Lock-In, url='https://www.botcity.dev/python-rpa-x-low-code'
		StaticText Products
		link BotCity Orchestrator, url='https://www.botcity.dev/orchestrator'
		link BotCity Devtools, url='https://www.botcity.dev/automation-suite'
		link BotCity Insights, url='https://www.botcity.dev/insights'
		StaticText Resources
		link Documentation, url='https://documentation.botcity.dev/'
		link Python RPA Training, url='https://developers.botcity.dev/academy'
		link Community Slack, url='https://join.slack.com/t/communitybotcitydev/shared_invite/zt-1crun2uma-OdBoUwYTNeGxPEJTFsuXSQ'
		link YouTube, url='https://www.youtube.com/@botcity-dev'
		link Blog, url='https://blog.botcity.dev/'
		link Forum, url='https://community.botcity.dev/'
		link Market Report, url='https://www.botcity.dev/major-contender'
		link Security, url='https://www.botcity.dev/security'
		link Partners, url='https://www.botcity.dev/become-a-partner'
		link Pricing, url='https://meetings.hubspot.com/andreabotcity/botcity-sales-global-calls'
		link Careers, url='https://botcity.notion.site/BotCity-Careers-91f223adc605420a9ccf3ac1231da238'
		link Case Studies, url='https://www.botcity.dev/cases'
		paragraph
			StaticText 1110 Brickell Ave, Miami, FL 33131, USA
		link Terms & Conditions, url='https://www.botcity.dev/terms-and-conditions'
		link Privacy Policy, url='https://www.botcity.dev/privacy-policy'
	[838] link EN, center=(1859,1060), url='https://www.botcity.dev/#'
		image English flag, url='https://cdn.weglot.com/flags/square/gb.svg'
	link BR, url='https://pt-br.botcity.dev/'
		image Português Brasileiro flag, url='https://cdn.weglot.com/flags/square/br.svg'
	link ES, url='https://es.botcity.dev/'
		image Español flag, url='https://cdn.weglot.com/flags/square/es.svg'
```
</details>



```
RootWebArea BotCity | Python RPA Software and Intelligent Automation Orchestrator, focused, url='https://www.botcity.dev/'
	paragraph
		StaticText This website stores cookies on your computer. These cookies are used to collect information about how you interact with our website and allow us to remember you. We use this information in order to improve and customize your browsing experience and for analytics and metrics about our visitors both on this website and other media. To find out more about the cookies we use, see our Privacy Policy
	paragraph
		StaticText If you decline, your information won’t be tracked when you visit this website. A single cookie will be used in your browser to remember your preference not to be tracked.
```
<details><summary>Show more</summary>

```
	[79] button Accept All, center=(1217,1034)
	[80] button Decline All, center=(1317,1034)
	banner
		link home, url='https://www.botcity.dev/'
			image BotCity Logo, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/66193a64d8ee208d28e3796f_logo_botcity_2024.svg'
		navigation
			button Why BotCity, expanded=False, hasPopup='menu'
				image
			button Products, expanded=False, hasPopup='menu'
				image
			link Pricing, url='https://meetings.hubspot.com/andreabotcity/botcity-sales-global-calls'
			link Security, url='https://www.botcity.dev/security'
			link Partners, url='https://www.botcity.dev/become-a-partner'
			link Case Studies, url='https://www.botcity.dev/cases'
			button Resources, expanded=False, hasPopup='menu'
				image
			link Log In, url='https://developers.botcity.dev/login'
			link Sign Up, url='https://developers.botcity.dev/signup'
			link Book a Live Demo, url='https://meetings.hubspot.com/andreabotcity/botcity-sales-global-calls'
	main
		banner
			[163] link home, center=(164,36), url='https://www.botcity.dev/'
				image BotCity Logo, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/66193a64d8ee208d28e3796f_logo_botcity_2024.svg'
			navigation
				[168] button Why BotCity, center=(322,36), expanded=False, hasPopup='menu'
					image
				[178] button Products, center=(427,36), expanded=False, hasPopup='menu'
					image
				[188] link Pricing, center=(504,36), inner_text=Pricing
, url='https://meetings.hubspot.com/andreabotcity/botcity-sales-global-calls'
				[190] link Security, center=(567,36), url='https://www.botcity.dev/security'
				[191] link Partners, center=(636,36), url='https://www.botcity.dev/become-a-partner'
				[192] link Case Studies, center=(720,36), inner_text=Case Studies
, url='https://www.botcity.dev/cases'
				[195] button Resources, center=(822,36), expanded=False, hasPopup='menu'
					image
				[226] link Log In, center=(1516,36), url='https://developers.botcity.dev/login'
				[227] link Sign Up, center=(1607,36), url='https://developers.botcity.dev/signup'
				[228] link Book a Live Demo, center=(1744,36), url='https://meetings.hubspot.com/andreabotcity/botcity-sales-global-calls'
		heading Real
		StaticText Governance
		StaticText Security
		StaticText Insights
		StaticText Control
		heading for Python RPA + AI
		paragraph
			StaticText Unlock the full potential of intelligent automation with an Orchestrator for Python automations, with no lock-in constraints.
		[264] link Start for free, center=(384,517), url='https://developers.botcity.dev/signup'
		[265] link Talk to experts, center=(534,517), url='https://meetings.hubspot.com/andreabotcity/botcity-sales-global-calls'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/66339e22c313c834fdad7fdf_Group%201%20(1).svg'
		heading Trusted by 1000+ companies in 70+ countries
		image Logo da LG, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fdc09c26b074d9ac4e03_LG_logo_(2014).svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fe8afea62ee7a549108a_ey.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fd862ce20de2d9f9c4ea_y.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fd40a400283747a68c70_Correios_(2014).svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fd19e4d8d41a67e02dd0_Algar_Telecom_logo.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fc6698bf4a69e5ed7cf2_sicoob-vector-logo.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9ffbc3887f2be7a7d582a_bayer.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fcd5ae17d297037019c2_h.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/66188ea210f8f36ed6656ddd_b93fa752-8cec-4fb8-92c8-bf2ab4c0b444___af80d9a5c64906e0662936151537ff10.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/66188e9fc9085c77fdabdd96_extra.svg'
		image Logo da LG, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fdc09c26b074d9ac4e03_LG_logo_(2014).svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fe8afea62ee7a549108a_ey.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fd862ce20de2d9f9c4ea_y.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fd40a400283747a68c70_Correios_(2014).svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fd19e4d8d41a67e02dd0_Algar_Telecom_logo.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fc6698bf4a69e5ed7cf2_sicoob-vector-logo.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9ffbc3887f2be7a7d582a_bayer.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fcd5ae17d297037019c2_h.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/66188ea210f8f36ed6656ddd_b93fa752-8cec-4fb8-92c8-bf2ab4c0b444___af80d9a5c64906e0662936151537ff10.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/66188e9fc9085c77fdabdd96_extra.svg'
		heading Why BotCity for Hyperautomation?
		heading Up to 50%
		paragraph
			StaticText Reduction in RPA license costs + strategic indicator reports for stakeholders and tech teams.
		heading 15X faster
		paragraph
			StaticText Robots with end-to-end governance and orchestration.
		heading Works everywhere
		paragraph
			StaticText From Citrix to SAP. From Windows to Linux.
		heading No vendor lock-in
		paragraph
			StaticText The code is forever yours. Free yourself from technical constraints and avoid dependency on vendors.
		StaticText The best platform for your tech team. The optimal ROI for your stakeholders.
		heading End-to-end Orchestration
		paragraph
			StaticText The best cloud-based orchestrator for code-based automations. Go beyond scheduling to achieve complete governance and control.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Create scheduling rules
			StaticText and never lose an automation execution.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Real-time alerts
			StaticText for stakeholders via Microsoft Teams, Email, WhatsApp.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Enable autonomy and segmentation
			StaticText across business areas with user groups and repositories.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Downtime reduction
			StaticText with automatic error reporting.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Infrastructure optimization
			StaticText with automatic load balancing.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Advanced item management
			StaticText with batch processing.
		link Learn more, url='https://www.botcity.dev/orchestrator'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/66339e9ef3383e90c49460b9_Group%203%20(1).svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/66339eb7d94e175c48639406_Group%204%20(1).svg'
		heading Global KPIs visibility with BotCity Insights
		paragraph
			StaticText Give your stakeholders full visibility of the results of your CoE. Consolidate and integrate KPIs directly into BotCity Orchestrator.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Finance Reports:
			StaticText Monitor ROI, FTE, and Savings segmented on the business and process level.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Efficiency:
			StaticText Generate insights for continuous improvement using efficiency indicators, common failures, and downtime rates.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Initiative and infrastructure evolution:
			StaticText Analyze automation evolution over time and agent utilization rates to optimize infrastructure.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Seamlessly integrate with BI solutions
			StaticText , ranging from Power BI to Grafana.
		link More about BotCity Insights, url='https://www.botcity.dev/insights'
		heading Speed up development
		paragraph
			StaticText Increase developer productivity and put automations into production in just a few days.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Develop complex automations
			StaticText , including ERPs, Legacy Systems, Desktop, and Web Applications.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Python libraries and plugins:
			StaticText Ready-to-use code snippets for daily operations.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText VSCode extension:
			StaticText Effortlessly generate Python code from any UI interaction using BotCity Studio’s computer vision coding assistant.
		link Learn more about BotCity Devtools, url='https://www.botcity.dev/automation-suite'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/66339e6ef42ba2e7bad79c52_Group%202%20(1).svg'
		region carousel
			group 1 of 2
				image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/661895fc6d0a291ec1d9d88f_logo-2018-header.svg'
				heading Intelligent Automation + AI
				StaticText Hyperautomation in Python for faster results.
				heading K
					marquee
						StaticText 100
				StaticText Hours saved (6 months)
				heading +%
					marquee
						StaticText 63
				StaticText Increase in Full-Time Equivalent (FTE)
				heading
					marquee
						StaticText 20
				StaticText Parallel agents
				heading +%
					marquee
						StaticText 175
				StaticText Productivity in RPA Development
				link Read full customer story Arrow Right, url='https://blog.botcity.dev/pt-br/2024/01/29/andrade-gutierrez-rpa-python/'
					image Arrow Right
				image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/661c775f87fc7458700f5795_quote.svg'
				blockquote
					StaticText We were using a low-code platform, and after adopting BotCity, our RPA initiative scaled up more rapidly. We accelerated the increase of ROI and FTE and also reduced license costs.
				paragraph
					strong
						StaticText Pieter Vosholyn
					StaticText , IT Manager at Andrade Gutierrez
			button previous slide
				StaticText 
			button next slide
				StaticText 
		link See our Case Studies, url='https://www.botcity.dev/cases'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/661d18f1f446c0aaa18b4674_RoboticProcessAutomation(RPA)_HighPerformer_Enterprise_HighPerformer.png'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/661d18ed51373c04abea5f37_RoboticProcessAutomation(RPA)_BestUsability_Total.png'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/661d18ed8d1dd65c42a9d9ab_RoboticProcessAutomation(RPA)_UsersMostLikelyToRecommend_Enterprise_Nps.png'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/661d18ed408213585db54a6d_Best-relationship-spring-24.webp'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/661d18ede9c09ea6b6215a50_RoboticProcessAutomation(RPA)_EasiestToUse_Enterprise_EaseOfUse.png'
		heading Customer's use cases
		image
		heading Construction
			strong
		paragraph
			StaticText Learn how a construction company reduced its supplier validation process on SAP from
			strong
				StaticText 10 days to 6 minutes.
		link Learn more, url='https://blog.botcity.dev/2023/06/16/python-rpa-sap-supply-chain-construction/'
		image
		heading Manufacturing
			strong
		paragraph
			StaticText Learn how a manufacturing company migrated from low-code and
			strong
				StaticText saved 70% in RPA licenses.
		link Learn more, url='https://blog.botcity.dev/2023/06/16/manufacturer-saved-70-migration-uipath-python-rpa/'
		image
		heading Engineering
			strong
		paragraph
			StaticText Learn how a multinational engineering company made their
			strong
				StaticText bots 10x faster
			StaticText than low-code with Python RPA.
		link Learn more, url='https://blog.botcity.dev/2023/06/16/rpa-saving-licenses-blueprism-to-python/'
		image
		heading Software ERP
			strong
		paragraph
			StaticText Learn how an ERP provider
			strong
				StaticText reduced 50% their support tickets
			StaticText with automated interface testing.
		link Learn more, url='https://blog.botcity.dev/2023/06/16/botcity-ui-testing-interface-testing-erp/'
		heading Learn more about Python RPA
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/6489c2149139b3c0d8a86370_Vectors-Wrapper.svg'
		heading Developing automations with computer vision
			strong
		paragraph
			StaticText This course teaches you how to create and orchestrate automation for any system using computer vision.
		link Learn more, url='https://developers.botcity.dev/academy/'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65bb8752310f48658c3021e7_python%20rpa%20orchestration-p-500.png'
		heading Python RPA Orchestration
			strong
		paragraph
			StaticText Learn the key features of the orchestrator in a hands-on approach. Discover the benefits and advantages of using each resource to enhance your automation processes.
		link Learn more, url='https://developers.botcity.dev/academy'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65bb88f51d57981d75461525_sap%20automation%20rpa%20python%20botcity%20marcelo%20cruz-p-500.png'
		heading SAP Automation with Python and BotCity
			strong
		paragraph
			StaticText Explore SAP automation with Python and BotCity in this practical course. Learn essential techniques to streamline and optimize SAP processes efficiently.
		link Learn more, url='https://developers.botcity.dev/academy'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65bb8833a0ce27cc4dc0086c_python-rpa-chatgpt-bard-openai.jpg'
		heading Python RPA, ChatGPT, Bard & OpenAI
			strong
		paragraph
			StaticText Build AI Automation Python Framework Integrating BotCity-RPA, OpenAI, ChatGPT &amp; Google Bard. Learn Next-Gen AI SkillSet
		link Learn more, url='https://www.udemy.com/course/python-driven-ai-automation-botcity-rpa-chatgpt-and-openai/'
		paragraph
			StaticText Get started with BotCity for free
		heading Unlock the full potential of intelligent automation
			strong
		paragraph
			StaticText Boost tech team productivity with BotCity's Python RPA and Intelligent Automation software. Drive ROI, orchestrate and enhance performance.
		link Sign up for free, url='https://developers.botcity.dev/signup'
	contentinfo
		link Botcity Logo, url='https://www.botcity.dev/'
			image Botcity Logo, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/66193a64d8ee208d28e3796f_logo_botcity_2024.svg'
		paragraph
			StaticText Build and orchestrate automation eliminating vendor lock-in. Leverage +440.000 Python libraries, full control of your code with enterprise-level governance, costing up to 5x less than low-code platforms.
		link GitHub Icon, url='https://github.com/botcity-dev'
			image GitHub Icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/648ae46909b094066028a8b2_icon-github.svg'
		link Linkedin logo, url='https://www.linkedin.com/company/botcity/?lipi=urn%3Ali%3Apage%3Ad_flagship3_search_srp_all%3BpxkmYgo3Tem0YJ9Vdw%2BT2g%3D%3D'
			image Linkedin logo, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/648ae4adeb905c3acb4eb83a_icon-LinkedIn.svg'
		link Youtube Logo, url='https://www.youtube.com/@botcity-dev'
			image Youtube Logo, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/661d204a06b06b114656522e_youtube%20(1).svg'
		link Twitter Logo, url='https://twitter.com/BotcityDev'
			image Twitter Logo, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/648ae4dfb4c707258cb88a61_icon-twitter.svg'
		link Log In, url='https://developers.botcity.dev/login'
		link Sign Up, url='https://developers.botcity.dev/signup'
		StaticText Why BotCity
		link Why Python RPA?, url='https://www.botcity.dev/wpr-old'
		link Python RPA x Low-Code, url='https://www.botcity.dev/python-rpa-x-low-code'
		link No Vendor Lock-In, url='https://www.botcity.dev/python-rpa-x-low-code'
		StaticText Products
		link BotCity Orchestrator, url='https://www.botcity.dev/orchestrator'
		link BotCity Devtools, url='https://www.botcity.dev/automation-suite'
		link BotCity Insights, url='https://www.botcity.dev/insights'
		StaticText Resources
		link Documentation, url='https://documentation.botcity.dev/'
		link Python RPA Training, url='https://developers.botcity.dev/academy'
		link Community Slack, url='https://join.slack.com/t/communitybotcitydev/shared_invite/zt-1crun2uma-OdBoUwYTNeGxPEJTFsuXSQ'
		link YouTube, url='https://www.youtube.com/@botcity-dev'
		link Blog, url='https://blog.botcity.dev/'
		link Forum, url='https://community.botcity.dev/'
		link Market Report, url='https://www.botcity.dev/major-contender'
		link Security, url='https://www.botcity.dev/security'
		link Partners, url='https://www.botcity.dev/become-a-partner'
		link Pricing, url='https://meetings.hubspot.com/andreabotcity/botcity-sales-global-calls'
		link Careers, url='https://botcity.notion.site/BotCity-Careers-91f223adc605420a9ccf3ac1231da238'
		link Case Studies, url='https://www.botcity.dev/cases'
		paragraph
			StaticText 1110 Brickell Ave, Miami, FL 33131, USA
		link Terms & Conditions, url='https://www.botcity.dev/terms-and-conditions'
		link Privacy Policy, url='https://www.botcity.dev/privacy-policy'
	[847] link EN, center=(1859,1060), url='https://www.botcity.dev/#'
		image English flag, url='https://cdn.weglot.com/flags/square/gb.svg'
	link BR, url='https://pt-br.botcity.dev/'
		image Português Brasileiro flag, url='https://cdn.weglot.com/flags/square/br.svg'
	link ES, url='https://es.botcity.dev/'
		image Español flag, url='https://cdn.weglot.com/flags/square/es.svg'
```
</details>

**Reasoning for action:** Before taking the action of clicking on 'Why BotCity', I considered that as a potential user, understanding the reasoning behind choosing this platform is crucial to making an informed decision. By clicking on this link, I can gather information that could help in the signup process, and potentially address any doubts I may have about the platform’s suitability for my organization's automation needs. Exploring this section better equips me with the knowledge needed before I proceed to sign up for the free trial, thereby aligning with my ultimate objective of exploring BotCity's automation solutions.

**Action:** click('163') # Click on the 'Why BotCity' button to explore more about the platform.

**Change Description:** After clicking the 'Why BotCity' button, the content related to the benefits and features of BotCity was displayed, providing information on hyperautomation, associated cost reductions, and enhanced productivity, while remaining in the same context of the website.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://www.botcity.dev/

https://developers.botcity.dev/signup?_gl=1*rwmipy*_gcl_au*MTU1NzY3NDgxNi4xNzM2MjU4OTY0*_ga*MTU5MjM1NjQ1OS4xNzM2MjU4OTY1*_ga_1SC1PVPMSC*MTczNjI1ODk2NC4xLjEuMTczNjI1OTAyNC42MC4wLjE5OTA3MTk1MjM.

**Content (before/after):** 

```
RootWebArea BotCity | Python RPA Software and Intelligent Automation Orchestrator, focused, url='https://www.botcity.dev/'
	paragraph
		StaticText This website stores cookies on your computer. These cookies are used to collect information about how you interact with our website and allow us to remember you. We use this information in order to improve and customize your browsing experience and for analytics and metrics about our visitors both on this website and other media. To find out more about the cookies we use, see our Privacy Policy
	paragraph
		StaticText If you decline, your information won’t be tracked when you visit this website. A single cookie will be used in your browser to remember your preference not to be tracked.
```
<details><summary>Show more</summary>

```
	[79] button Accept All, center=(1217,1034)
	[80] button Decline All, center=(1317,1034)
	banner
		link home, url='https://www.botcity.dev/'
			image BotCity Logo, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/66193a64d8ee208d28e3796f_logo_botcity_2024.svg'
		navigation
			button Why BotCity, expanded=False, hasPopup='menu'
				image
			button Products, expanded=False, hasPopup='menu'
				image
			link Pricing, url='https://meetings.hubspot.com/andreabotcity/botcity-sales-global-calls'
			link Security, url='https://www.botcity.dev/security'
			link Partners, url='https://www.botcity.dev/become-a-partner'
			link Case Studies, url='https://www.botcity.dev/cases'
			button Resources, expanded=False, hasPopup='menu'
				image
			link Log In, url='https://developers.botcity.dev/login'
			link Sign Up, url='https://developers.botcity.dev/signup'
			link Book a Live Demo, url='https://meetings.hubspot.com/andreabotcity/botcity-sales-global-calls'
	main
		banner
			[163] link home, center=(164,36), url='https://www.botcity.dev/'
				image BotCity Logo, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/66193a64d8ee208d28e3796f_logo_botcity_2024.svg'
			navigation
				[168] button Why BotCity, center=(322,36), expanded=False, hasPopup='menu'
					image
				[178] button Products, center=(427,36), expanded=False, hasPopup='menu'
					image
				[188] link Pricing, center=(504,36), inner_text=Pricing
, url='https://meetings.hubspot.com/andreabotcity/botcity-sales-global-calls'
				[190] link Security, center=(567,36), url='https://www.botcity.dev/security'
				[191] link Partners, center=(636,36), url='https://www.botcity.dev/become-a-partner'
				[192] link Case Studies, center=(720,36), inner_text=Case Studies
, url='https://www.botcity.dev/cases'
				[195] button Resources, center=(822,36), expanded=False, hasPopup='menu'
					image
				[226] link Log In, center=(1516,36), url='https://developers.botcity.dev/login'
				[227] link Sign Up, center=(1607,36), url='https://developers.botcity.dev/signup'
				[228] link Book a Live Demo, center=(1744,36), url='https://meetings.hubspot.com/andreabotcity/botcity-sales-global-calls'
		heading Real
		StaticText Governance
		StaticText Security
		StaticText Insights
		StaticText Control
		heading for Python RPA + AI
		paragraph
			StaticText Unlock the full potential of intelligent automation with an Orchestrator for Python automations, with no lock-in constraints.
		[264] link Start for free, center=(384,517), url='https://developers.botcity.dev/signup'
		[265] link Talk to experts, center=(534,517), url='https://meetings.hubspot.com/andreabotcity/botcity-sales-global-calls'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/66339e22c313c834fdad7fdf_Group%201%20(1).svg'
		heading Trusted by 1000+ companies in 70+ countries
		image Logo da LG, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fdc09c26b074d9ac4e03_LG_logo_(2014).svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fe8afea62ee7a549108a_ey.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fd862ce20de2d9f9c4ea_y.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fd40a400283747a68c70_Correios_(2014).svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fd19e4d8d41a67e02dd0_Algar_Telecom_logo.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fc6698bf4a69e5ed7cf2_sicoob-vector-logo.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9ffbc3887f2be7a7d582a_bayer.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fcd5ae17d297037019c2_h.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/66188ea210f8f36ed6656ddd_b93fa752-8cec-4fb8-92c8-bf2ab4c0b444___af80d9a5c64906e0662936151537ff10.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/66188e9fc9085c77fdabdd96_extra.svg'
		image Logo da LG, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fdc09c26b074d9ac4e03_LG_logo_(2014).svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fe8afea62ee7a549108a_ey.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fd862ce20de2d9f9c4ea_y.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fd40a400283747a68c70_Correios_(2014).svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fd19e4d8d41a67e02dd0_Algar_Telecom_logo.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fc6698bf4a69e5ed7cf2_sicoob-vector-logo.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9ffbc3887f2be7a7d582a_bayer.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65f9fcd5ae17d297037019c2_h.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/66188ea210f8f36ed6656ddd_b93fa752-8cec-4fb8-92c8-bf2ab4c0b444___af80d9a5c64906e0662936151537ff10.svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/66188e9fc9085c77fdabdd96_extra.svg'
		heading Why BotCity for Hyperautomation?
		heading Up to 50%
		paragraph
			StaticText Reduction in RPA license costs + strategic indicator reports for stakeholders and tech teams.
		heading 15X faster
		paragraph
			StaticText Robots with end-to-end governance and orchestration.
		heading Works everywhere
		paragraph
			StaticText From Citrix to SAP. From Windows to Linux.
		heading No vendor lock-in
		paragraph
			StaticText The code is forever yours. Free yourself from technical constraints and avoid dependency on vendors.
		StaticText The best platform for your tech team. The optimal ROI for your stakeholders.
		heading End-to-end Orchestration
		paragraph
			StaticText The best cloud-based orchestrator for code-based automations. Go beyond scheduling to achieve complete governance and control.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Create scheduling rules
			StaticText and never lose an automation execution.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Real-time alerts
			StaticText for stakeholders via Microsoft Teams, Email, WhatsApp.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Enable autonomy and segmentation
			StaticText across business areas with user groups and repositories.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Downtime reduction
			StaticText with automatic error reporting.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Infrastructure optimization
			StaticText with automatic load balancing.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Advanced item management
			StaticText with batch processing.
		link Learn more, url='https://www.botcity.dev/orchestrator'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/66339e9ef3383e90c49460b9_Group%203%20(1).svg'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/66339eb7d94e175c48639406_Group%204%20(1).svg'
		heading Global KPIs visibility with BotCity Insights
		paragraph
			StaticText Give your stakeholders full visibility of the results of your CoE. Consolidate and integrate KPIs directly into BotCity Orchestrator.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Finance Reports:
			StaticText Monitor ROI, FTE, and Savings segmented on the business and process level.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Efficiency:
			StaticText Generate insights for continuous improvement using efficiency indicators, common failures, and downtime rates.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Initiative and infrastructure evolution:
			StaticText Analyze automation evolution over time and agent utilization rates to optimize infrastructure.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Seamlessly integrate with BI solutions
			StaticText , ranging from Power BI to Grafana.
		link More about BotCity Insights, url='https://www.botcity.dev/insights'
		heading Speed up development
		paragraph
			StaticText Increase developer productivity and put automations into production in just a few days.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Develop complex automations
			StaticText , including ERPs, Legacy Systems, Desktop, and Web Applications.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText Python libraries and plugins:
			StaticText Ready-to-use code snippets for daily operations.
		image Checked icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65ee32918cacf855513a65cc_d.svg'
		paragraph
			strong
				StaticText VSCode extension:
			StaticText Effortlessly generate Python code from any UI interaction using BotCity Studio’s computer vision coding assistant.
		link Learn more about BotCity Devtools, url='https://www.botcity.dev/automation-suite'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/66339e6ef42ba2e7bad79c52_Group%202%20(1).svg'
		region carousel
			group 1 of 2
				image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/661895fc6d0a291ec1d9d88f_logo-2018-header.svg'
				heading Intelligent Automation + AI
				StaticText Hyperautomation in Python for faster results.
				heading K
					marquee
						StaticText 100
				StaticText Hours saved (6 months)
				heading +%
					marquee
						StaticText 63
				StaticText Increase in Full-Time Equivalent (FTE)
				heading
					marquee
						StaticText 20
				StaticText Parallel agents
				heading +%
					marquee
						StaticText 175
				StaticText Productivity in RPA Development
				link Read full customer story Arrow Right, url='https://blog.botcity.dev/pt-br/2024/01/29/andrade-gutierrez-rpa-python/'
					image Arrow Right
				image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/661c775f87fc7458700f5795_quote.svg'
				blockquote
					StaticText We were using a low-code platform, and after adopting BotCity, our RPA initiative scaled up more rapidly. We accelerated the increase of ROI and FTE and also reduced license costs.
				paragraph
					strong
						StaticText Pieter Vosholyn
					StaticText , IT Manager at Andrade Gutierrez
			button previous slide
				StaticText 
			button next slide
				StaticText 
		link See our Case Studies, url='https://www.botcity.dev/cases'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/661d18f1f446c0aaa18b4674_RoboticProcessAutomation(RPA)_HighPerformer_Enterprise_HighPerformer.png'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/661d18ed51373c04abea5f37_RoboticProcessAutomation(RPA)_BestUsability_Total.png'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/661d18ed8d1dd65c42a9d9ab_RoboticProcessAutomation(RPA)_UsersMostLikelyToRecommend_Enterprise_Nps.png'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/661d18ed408213585db54a6d_Best-relationship-spring-24.webp'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/661d18ede9c09ea6b6215a50_RoboticProcessAutomation(RPA)_EasiestToUse_Enterprise_EaseOfUse.png'
		heading Customer's use cases
		image
		heading Construction
			strong
		paragraph
			StaticText Learn how a construction company reduced its supplier validation process on SAP from
			strong
				StaticText 10 days to 6 minutes.
		link Learn more, url='https://blog.botcity.dev/2023/06/16/python-rpa-sap-supply-chain-construction/'
		image
		heading Manufacturing
			strong
		paragraph
			StaticText Learn how a manufacturing company migrated from low-code and
			strong
				StaticText saved 70% in RPA licenses.
		link Learn more, url='https://blog.botcity.dev/2023/06/16/manufacturer-saved-70-migration-uipath-python-rpa/'
		image
		heading Engineering
			strong
		paragraph
			StaticText Learn how a multinational engineering company made their
			strong
				StaticText bots 10x faster
			StaticText than low-code with Python RPA.
		link Learn more, url='https://blog.botcity.dev/2023/06/16/rpa-saving-licenses-blueprism-to-python/'
		image
		heading Software ERP
			strong
		paragraph
			StaticText Learn how an ERP provider
			strong
				StaticText reduced 50% their support tickets
			StaticText with automated interface testing.
		link Learn more, url='https://blog.botcity.dev/2023/06/16/botcity-ui-testing-interface-testing-erp/'
		heading Learn more about Python RPA
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/6489c2149139b3c0d8a86370_Vectors-Wrapper.svg'
		heading Developing automations with computer vision
			strong
		paragraph
			StaticText This course teaches you how to create and orchestrate automation for any system using computer vision.
		link Learn more, url='https://developers.botcity.dev/academy/'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65bb8752310f48658c3021e7_python%20rpa%20orchestration-p-500.png'
		heading Python RPA Orchestration
			strong
		paragraph
			StaticText Learn the key features of the orchestrator in a hands-on approach. Discover the benefits and advantages of using each resource to enhance your automation processes.
		link Learn more, url='https://developers.botcity.dev/academy'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65bb88f51d57981d75461525_sap%20automation%20rpa%20python%20botcity%20marcelo%20cruz-p-500.png'
		heading SAP Automation with Python and BotCity
			strong
		paragraph
			StaticText Explore SAP automation with Python and BotCity in this practical course. Learn essential techniques to streamline and optimize SAP processes efficiently.
		link Learn more, url='https://developers.botcity.dev/academy'
		image, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/65bb8833a0ce27cc4dc0086c_python-rpa-chatgpt-bard-openai.jpg'
		heading Python RPA, ChatGPT, Bard & OpenAI
			strong
		paragraph
			StaticText Build AI Automation Python Framework Integrating BotCity-RPA, OpenAI, ChatGPT &amp; Google Bard. Learn Next-Gen AI SkillSet
		link Learn more, url='https://www.udemy.com/course/python-driven-ai-automation-botcity-rpa-chatgpt-and-openai/'
		paragraph
			StaticText Get started with BotCity for free
		heading Unlock the full potential of intelligent automation
			strong
		paragraph
			StaticText Boost tech team productivity with BotCity's Python RPA and Intelligent Automation software. Drive ROI, orchestrate and enhance performance.
		link Sign up for free, url='https://developers.botcity.dev/signup'
	contentinfo
		link Botcity Logo, url='https://www.botcity.dev/'
			image Botcity Logo, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/66193a64d8ee208d28e3796f_logo_botcity_2024.svg'
		paragraph
			StaticText Build and orchestrate automation eliminating vendor lock-in. Leverage +440.000 Python libraries, full control of your code with enterprise-level governance, costing up to 5x less than low-code platforms.
		link GitHub Icon, url='https://github.com/botcity-dev'
			image GitHub Icon, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/648ae46909b094066028a8b2_icon-github.svg'
		link Linkedin logo, url='https://www.linkedin.com/company/botcity/?lipi=urn%3Ali%3Apage%3Ad_flagship3_search_srp_all%3BpxkmYgo3Tem0YJ9Vdw%2BT2g%3D%3D'
			image Linkedin logo, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/648ae4adeb905c3acb4eb83a_icon-LinkedIn.svg'
		link Youtube Logo, url='https://www.youtube.com/@botcity-dev'
			image Youtube Logo, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/661d204a06b06b114656522e_youtube%20(1).svg'
		link Twitter Logo, url='https://twitter.com/BotcityDev'
			image Twitter Logo, url='https://cdn.prod.website-files.com/6487203eebdb29c0fff6af27/648ae4dfb4c707258cb88a61_icon-twitter.svg'
		link Log In, url='https://developers.botcity.dev/login'
		link Sign Up, url='https://developers.botcity.dev/signup'
		StaticText Why BotCity
		link Why Python RPA?, url='https://www.botcity.dev/wpr-old'
		link Python RPA x Low-Code, url='https://www.botcity.dev/python-rpa-x-low-code'
		link No Vendor Lock-In, url='https://www.botcity.dev/python-rpa-x-low-code'
		StaticText Products
		link BotCity Orchestrator, url='https://www.botcity.dev/orchestrator'
		link BotCity Devtools, url='https://www.botcity.dev/automation-suite'
		link BotCity Insights, url='https://www.botcity.dev/insights'
		StaticText Resources
		link Documentation, url='https://documentation.botcity.dev/'
		link Python RPA Training, url='https://developers.botcity.dev/academy'
		link Community Slack, url='https://join.slack.com/t/communitybotcitydev/shared_invite/zt-1crun2uma-OdBoUwYTNeGxPEJTFsuXSQ'
		link YouTube, url='https://www.youtube.com/@botcity-dev'
		link Blog, url='https://blog.botcity.dev/'
		link Forum, url='https://community.botcity.dev/'
		link Market Report, url='https://www.botcity.dev/major-contender'
		link Security, url='https://www.botcity.dev/security'
		link Partners, url='https://www.botcity.dev/become-a-partner'
		link Pricing, url='https://meetings.hubspot.com/andreabotcity/botcity-sales-global-calls'
		link Careers, url='https://botcity.notion.site/BotCity-Careers-91f223adc605420a9ccf3ac1231da238'
		link Case Studies, url='https://www.botcity.dev/cases'
		paragraph
			StaticText 1110 Brickell Ave, Miami, FL 33131, USA
		link Terms & Conditions, url='https://www.botcity.dev/terms-and-conditions'
		link Privacy Policy, url='https://www.botcity.dev/privacy-policy'
	[847] link EN, center=(1859,1060), url='https://www.botcity.dev/#'
		image English flag, url='https://cdn.weglot.com/flags/square/gb.svg'
	link BR, url='https://pt-br.botcity.dev/'
		image Português Brasileiro flag, url='https://cdn.weglot.com/flags/square/br.svg'
	link ES, url='https://es.botcity.dev/'
		image Español flag, url='https://cdn.weglot.com/flags/square/es.svg'
```
</details>



```
RootWebArea BotCity - Sign Up, focused, url='https://developers.botcity.dev/signup?_gl=1*rwmipy*_gcl_au*MTU1NzY3NDgxNi4xNzM2MjU4OTY0*_ga*MTU5MjM1NjQ1OS4xNzM2MjU4OTY1*_ga_1SC1PVPMSC*MTczNjI1ODk2NC4xLjEuMTczNjI1OTAyNC42MC4wLjE5OTA3MTk1MjM.'
	paragraph
		StaticText This website stores cookies on your computer. These cookies are used to collect information about how you interact with our website and allow us to remember you. We use this information in order to improve and customize your browsing experience and for analytics and metrics about our visitors both on this website and other media. To find out more about the cookies we use, see our Privacy Policy
	paragraph
		StaticText If you decline, your information won’t be tracked when you visit this website. A single cookie will be used in your browser to remember your preference not to be tracked.
```
<details><summary>Show more</summary>

```
	[53] button Accept All, center=(1214,1034)
	[54] button Decline All, center=(1316,1034)
	banner
		[61] image, center=(315,32), url='https://developers.botcity.dev/assets/images/botcity_logo_black.svg'
		[63] link TALK TO A SPECIALIST, center=(1562,32), url='https://meetings.hubspot.com/andreabotcity/botcity-sales-global-calls'
	paragraph
		StaticText A complete stack for Python automations
	heading Develop automations for web, desktop, legacy and Android applications
	heading Your automation is open source code (Python or Java)
	heading Orchestrate and scale any automation in Python. Schedule, receive alerts, monitor and integrate with your product
	heading Community Support Slack, Global Forum and Documentation Portal
		[85] link Slack, center=(555,658), url='https://join.slack.com/t/communitybotcitydev/shared_invite/zt-xt5lu9bq-l2E1gcf9pZgr4UrnIRJMLw'
		[86] link Global Forum, center=(632,658), url='https://community.botcity.dev/'
		link Documentation Portal, url='https://documentation.botcity.dev/'
	paragraph
		StaticText Get started for free
	paragraph
		StaticText All plans come with a free, 30-day trial of BotCity Growth.
		StaticText No credit card required.
		StaticText Upgrade at the end of the trial or continue using BotCity for free.
	[100] textbox Email address, center=(1324,412), contenteditable=True, type=text
	paragraph
		StaticText ​
	[106] button SIGN UP, center=(1324,493), type=submit
	paragraph
		StaticText By signing up you agree to the
		[109] link Privacy Policy, center=(1321,530), url='https://developers.botcity.dev/files/terms/21092021Privacy_BotCity.pdf'
		StaticText and the
		[110] link Terms of Service, center=(1456,530), url='https://developers.botcity.dev/files/terms/english_terms.pdf'
		StaticText .
	paragraph
		StaticText Already have an account?
		[112] link Log in, center=(1301,555), url='https://developers.botcity.dev/signup'
	paragraph
		StaticText After 30 days, included in the free plan:
	paragraph
		StaticText Develop and deploy 1 automation
	paragraph
		StaticText Run your automations up to 10x/day
	paragraph
		StaticText Botcity Academy
	paragraph
		StaticText BotCity is protected by reCAPTCHA and the
		[125] link Privacy Policy, center=(1395,795), url='https://developers.botcity.dev/files/terms/21092021Privacy_BotCity.pdf'
		StaticText and the
		link Terms of Service, url='https://developers.botcity.dev/files/terms/english_terms.pdf'
		StaticText apply.
	region Chat Widget
		Iframe Chat Widget
			RootWebArea Chat Widget, url='https://app.hubspot.com/conversations-visitor/5323276/threads/utk/bfc1bc1acd97458886b7fff60e0a254b?uuid=858b4612fac14f32bf855ac4447dbad5&mobile=false&mobileSafari=false&hideWelcomeMessage=false&hstc=&domain=developers.botcity.dev&inApp53=false&messagesUtk=bfc1bc1acd97458886b7fff60e0a254b&url=https%3A%2F%2Fdevelopers.botcity.dev%2Fsignup%3F_gl%3D1*rwmipy*_gcl_au*MTU1NzY3NDgxNi4xNzM2MjU4OTY0*_ga*MTU5MjM1NjQ1OS4xNzM2MjU4OTY1*_ga_1SC1PVPMSC*MTczNjI1ODk2NC4xLjEuMTczNjI1OTAyNC42MC4wLjE5OTA3MTk1MjM.&inline=false&isFullscreen=false&globalCookieOptOut=&isFirstVisitorSession=true&isAttachmentDisabled=false&isInitialInputFocusDisabled=false&enableWidgetCookieBanner=false&isInCMS=false&hideScrollToButton=true&isIOSMobile=false&hubspotUtk=ed6ddc707273712270398a8dae7b0b57'
				status Welcome message, atomic
					[e35] button Open live chat, center=(1784,897), hasPopup='dialog'
						image Avatar of Livia, url='https://api-na1.hubspot.com/userpreferences/v1/avatar/92e7fc8887e805e92d344af6170e12d4/100'
						status, atomic
							StaticText Hello there! We can speak in English or Portuguese!
Here to help with any tech questions on product, trial programs, training, and pricing. How can we help?
					[e43] button Dismiss, center=(1886,820)
						image
				[e49] button Open live chat, center=(1874,1034), hasPopup='dialog'
					image
					image
```
</details>

**Reasoning for action:** By clicking on the 'Start for free' link, I am directly taking the user to the sign-up section of the BotCity platform. This is a crucial step toward fulfilling the user story, as it allows me to proceed with the registration process needed to access the intelligent automation solutions offered. It transitions from being an interested visitor to a potential user ready to explore the platform's features.

**Action:** click('264') # Click on the 'Start for free' link to explore sign-up options.

**Change Description:** The browser transitioned from the main BotCity website to the Sign Up page after clicking the 'Start for free' link, introducing an input field for email registration, information about a free trial, and options to access community support and documentation.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://developers.botcity.dev/signup?_gl=1*rwmipy*_gcl_au*MTU1NzY3NDgxNi4xNzM2MjU4OTY0*_ga*MTU5MjM1NjQ1OS4xNzM2MjU4OTY1*_ga_1SC1PVPMSC*MTczNjI1ODk2NC4xLjEuMTczNjI1OTAyNC42MC4wLjE5OTA3MTk1MjM.

https://developers.botcity.dev/signup?_gl=1*rwmipy*_gcl_au*MTU1NzY3NDgxNi4xNzM2MjU4OTY0*_ga*MTU5MjM1NjQ1OS4xNzM2MjU4OTY1*_ga_1SC1PVPMSC*MTczNjI1ODk2NC4xLjEuMTczNjI1OTAyNC42MC4wLjE5OTA3MTk1MjM.

**Content (before/after):** 

```
RootWebArea BotCity - Sign Up, focused, url='https://developers.botcity.dev/signup?_gl=1*rwmipy*_gcl_au*MTU1NzY3NDgxNi4xNzM2MjU4OTY0*_ga*MTU5MjM1NjQ1OS4xNzM2MjU4OTY1*_ga_1SC1PVPMSC*MTczNjI1ODk2NC4xLjEuMTczNjI1OTAyNC42MC4wLjE5OTA3MTk1MjM.'
	paragraph
		StaticText This website stores cookies on your computer. These cookies are used to collect information about how you interact with our website and allow us to remember you. We use this information in order to improve and customize your browsing experience and for analytics and metrics about our visitors both on this website and other media. To find out more about the cookies we use, see our Privacy Policy
	paragraph
		StaticText If you decline, your information won’t be tracked when you visit this website. A single cookie will be used in your browser to remember your preference not to be tracked.
```
<details><summary>Show more</summary>

```
	[53] button Accept All, center=(1214,1034)
	[54] button Decline All, center=(1316,1034)
	banner
		[61] image, center=(315,32), url='https://developers.botcity.dev/assets/images/botcity_logo_black.svg'
		[63] link TALK TO A SPECIALIST, center=(1562,32), url='https://meetings.hubspot.com/andreabotcity/botcity-sales-global-calls'
	paragraph
		StaticText A complete stack for Python automations
	heading Develop automations for web, desktop, legacy and Android applications
	heading Your automation is open source code (Python or Java)
	heading Orchestrate and scale any automation in Python. Schedule, receive alerts, monitor and integrate with your product
	heading Community Support Slack, Global Forum and Documentation Portal
		[85] link Slack, center=(555,658), url='https://join.slack.com/t/communitybotcitydev/shared_invite/zt-xt5lu9bq-l2E1gcf9pZgr4UrnIRJMLw'
		[86] link Global Forum, center=(632,658), url='https://community.botcity.dev/'
		link Documentation Portal, url='https://documentation.botcity.dev/'
	paragraph
		StaticText Get started for free
	paragraph
		StaticText All plans come with a free, 30-day trial of BotCity Growth.
		StaticText No credit card required.
		StaticText Upgrade at the end of the trial or continue using BotCity for free.
	[100] textbox Email address, center=(1324,412), contenteditable=True, type=text
	paragraph
		StaticText ​
	[106] button SIGN UP, center=(1324,493), type=submit
	paragraph
		StaticText By signing up you agree to the
		[109] link Privacy Policy, center=(1321,530), url='https://developers.botcity.dev/files/terms/21092021Privacy_BotCity.pdf'
		StaticText and the
		[110] link Terms of Service, center=(1456,530), url='https://developers.botcity.dev/files/terms/english_terms.pdf'
		StaticText .
	paragraph
		StaticText Already have an account?
		[112] link Log in, center=(1301,555), url='https://developers.botcity.dev/signup'
	paragraph
		StaticText After 30 days, included in the free plan:
	paragraph
		StaticText Develop and deploy 1 automation
	paragraph
		StaticText Run your automations up to 10x/day
	paragraph
		StaticText Botcity Academy
	paragraph
		StaticText BotCity is protected by reCAPTCHA and the
		[125] link Privacy Policy, center=(1395,795), url='https://developers.botcity.dev/files/terms/21092021Privacy_BotCity.pdf'
		StaticText and the
		link Terms of Service, url='https://developers.botcity.dev/files/terms/english_terms.pdf'
		StaticText apply.
	region Chat Widget
		Iframe Chat Widget
			RootWebArea Chat Widget, url='https://app.hubspot.com/conversations-visitor/5323276/threads/utk/bfc1bc1acd97458886b7fff60e0a254b?uuid=858b4612fac14f32bf855ac4447dbad5&mobile=false&mobileSafari=false&hideWelcomeMessage=false&hstc=&domain=developers.botcity.dev&inApp53=false&messagesUtk=bfc1bc1acd97458886b7fff60e0a254b&url=https%3A%2F%2Fdevelopers.botcity.dev%2Fsignup%3F_gl%3D1*rwmipy*_gcl_au*MTU1NzY3NDgxNi4xNzM2MjU4OTY0*_ga*MTU5MjM1NjQ1OS4xNzM2MjU4OTY1*_ga_1SC1PVPMSC*MTczNjI1ODk2NC4xLjEuMTczNjI1OTAyNC42MC4wLjE5OTA3MTk1MjM.&inline=false&isFullscreen=false&globalCookieOptOut=&isFirstVisitorSession=true&isAttachmentDisabled=false&isInitialInputFocusDisabled=false&enableWidgetCookieBanner=false&isInCMS=false&hideScrollToButton=true&isIOSMobile=false&hubspotUtk=ed6ddc707273712270398a8dae7b0b57'
				status Welcome message, atomic
					[e35] button Open live chat, center=(1784,897), hasPopup='dialog'
						image Avatar of Livia, url='https://api-na1.hubspot.com/userpreferences/v1/avatar/92e7fc8887e805e92d344af6170e12d4/100'
						status, atomic
							StaticText Hello there! We can speak in English or Portuguese!
Here to help with any tech questions on product, trial programs, training, and pricing. How can we help?
					[e43] button Dismiss, center=(1886,820)
						image
				[e49] button Open live chat, center=(1874,1034), hasPopup='dialog'
					image
					image
```
</details>



```
RootWebArea BotCity - Sign Up, focused, url='https://developers.botcity.dev/signup?_gl=1*rwmipy*_gcl_au*MTU1NzY3NDgxNi4xNzM2MjU4OTY0*_ga*MTU5MjM1NjQ1OS4xNzM2MjU4OTY1*_ga_1SC1PVPMSC*MTczNjI1ODk2NC4xLjEuMTczNjI1OTAyNC42MC4wLjE5OTA3MTk1MjM.'
	paragraph
		StaticText This website stores cookies on your computer. These cookies are used to collect information about how you interact with our website and allow us to remember you. We use this information in order to improve and customize your browsing experience and for analytics and metrics about our visitors both on this website and other media. To find out more about the cookies we use, see our Privacy Policy
	paragraph
		StaticText If you decline, your information won’t be tracked when you visit this website. A single cookie will be used in your browser to remember your preference not to be tracked.
```
<details><summary>Show more</summary>

```
	[53] button Accept All, center=(1214,1034)
	[54] button Decline All, center=(1316,1034)
	banner
		[61] image, center=(315,32), url='https://developers.botcity.dev/assets/images/botcity_logo_black.svg'
		[63] link TALK TO A SPECIALIST, center=(1562,32), url='https://meetings.hubspot.com/andreabotcity/botcity-sales-global-calls'
	paragraph
		StaticText A complete stack for Python automations
	heading Develop automations for web, desktop, legacy and Android applications
	heading Your automation is open source code (Python or Java)
	heading Orchestrate and scale any automation in Python. Schedule, receive alerts, monitor and integrate with your product
	heading Community Support Slack, Global Forum and Documentation Portal
		[85] link Slack, center=(555,658), url='https://join.slack.com/t/communitybotcitydev/shared_invite/zt-xt5lu9bq-l2E1gcf9pZgr4UrnIRJMLw'
		[86] link Global Forum, center=(632,658), url='https://community.botcity.dev/'
		link Documentation Portal, url='https://documentation.botcity.dev/'
	paragraph
		StaticText Verify your account
	image verify-email, url='https://developers.botcity.dev/assets/images/verify-email.svg'
	paragraph
		StaticText Check your e-mail
	paragraph
		StaticText Please, verify your account by clicking on the link sent to your mailbox
	paragraph
		StaticText If you can't find the email, check your spam box
	region Chat Widget
		Iframe Chat Widget
			RootWebArea Chat Widget, url='https://app.hubspot.com/conversations-visitor/5323276/threads/utk/bfc1bc1acd97458886b7fff60e0a254b?uuid=858b4612fac14f32bf855ac4447dbad5&mobile=false&mobileSafari=false&hideWelcomeMessage=false&hstc=&domain=developers.botcity.dev&inApp53=false&messagesUtk=bfc1bc1acd97458886b7fff60e0a254b&url=https%3A%2F%2Fdevelopers.botcity.dev%2Fsignup%3F_gl%3D1*rwmipy*_gcl_au*MTU1NzY3NDgxNi4xNzM2MjU4OTY0*_ga*MTU5MjM1NjQ1OS4xNzM2MjU4OTY1*_ga_1SC1PVPMSC*MTczNjI1ODk2NC4xLjEuMTczNjI1OTAyNC42MC4wLjE5OTA3MTk1MjM.&inline=false&isFullscreen=false&globalCookieOptOut=&isFirstVisitorSession=true&isAttachmentDisabled=false&isInitialInputFocusDisabled=false&enableWidgetCookieBanner=false&isInCMS=false&hideScrollToButton=true&isIOSMobile=false&hubspotUtk=ed6ddc707273712270398a8dae7b0b57'
				status Welcome message, atomic
					[e35] button Open live chat, center=(1784,897), hasPopup='dialog'
						image Avatar of Livia, url='https://api-na1.hubspot.com/userpreferences/v1/avatar/92e7fc8887e805e92d344af6170e12d4/100'
						status, atomic
							StaticText Hello there! We can speak in English or Portuguese!
Here to help with any tech questions on product, trial programs, training, and pricing. How can we help?
					[e43] button Dismiss, center=(1886,820)
						image
				[e49] button Open live chat, center=(1874,1034), hasPopup='dialog'
					image
					image
```
</details>

**Reasoning for action:** I first selected the email input field to enter 'user@example.com', which is necessary for the user to create an account on the BotCity platform. Next, I clicked the 'SIGN UP' button. This action is crucial as it submits the filled email address to the system, which is the required step in the sign-up process to receive a verification link emailed to the user. Completing these steps brings me closer to achieving the user's goal of exploring the platform features.

**Action:** fill('100', 'user@example.com') # Fill in the email address field with a sample email.
click('106') # Click on the 'SIGN UP' button to proceed with the sign-up.

**Change Description:** The email address field was filled with 'user@example.com' and the 'SIGN UP' button was clicked, resulting in the display of a new verification message prompting the user to check their email for an account verification link.

**Screenshot before:****Screenshot after:**---

