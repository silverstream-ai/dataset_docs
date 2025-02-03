# Task

**User Registration Flow**

As a new user of Tenyks,
I register for an account,
so that I can access the features of the Tenyks platform to leverage visual data.

**Success definition:** Given I am on the registration page of the Tenyks application
When I fill in my first name, last name, email, and password in the registration form and click submit
Then I should receive a confirmation that my account has been successfully created and I should be able to log in to the application.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.tenyks.ai/

https://media.tenyks.ai/authentication/login

**Content (before/after):** 

```
RootWebArea Enterprise Visual Search Engine, focused, url='https://www.tenyks.ai/'
	StaticText By clicking
	strong
		StaticText “Accept All Cookies”
	StaticText , you agree to the storing of cookies on your device to enhance site navigation, analyze site usage, and assist in our marketing efforts. View our
```
<details><summary>Show more</summary>

```
	[59] link Privacy Policy, center=(806,1045), url='https://app.websitepolicies.com/policies/view/AG1odpD2#cookies'
	StaticText for more information.
	[61] button Manage Preferences, center=(1248,1032)
	[62] button Accept All Cookies, center=(1453,1032)
	[63] button, center=(1578,1032)
	group
		StaticText Zero-Shot AI: The End of Fine-Tuning as We Know It?
		[126] link Read more, center=(1106,17), url='https://www.tenyks.ai/blog/zero-shot-ai-the-end-of-fine-tuning-as-we-know-it'
			image
		[133] image, center=(1904,17)
	banner
		[140] link home, center=(398,74), url='https://www.tenyks.ai/'
			image Logo Tenyks, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/64ef648b87b00109b3260832_Tenyks_Logo_transparent.webp'
		navigation
			[143] link Product, center=(544,74), url='https://www.tenyks.ai/#'
			[145] button Industries, center=(658,74), expanded=False, hasPopup='menu'
			[187] link Pricing, center=(768,74), url='https://www.tenyks.ai/pricing'
			[189] button Resources, center=(881,74), expanded=False, hasPopup='menu'
			[214] link Company, center=(1003,74), url='https://www.tenyks.ai/about'
		[217] link Book a Demo, center=(1346,74), url='https://meetings.hubspot.com/botty/schedule-demo-website?uuid=1d1b6a4d-a7bd-4af2-baa8-636f604a6cea'
		[218] link Get Started, center=(1523,74), url='https://media.tenyks.ai/'
	main
		heading Conversational Visual Search
		paragraph
			StaticText Make Videos Searchable with GenAI
		paragraph
			StaticText ETL + BI for Video Powers Data-Driven Decisions
		paragraph
			StaticText Discover New & Unique Insights with Human-Level Precision
		[333] link Get Started, center=(461,459), url='https://media.tenyks.ai/'
		[334] link Book a Demo, center=(638,459), url='https://meetings.hubspot.com/botty/schedule-demo-website?uuid=1d1b6a4d-a7bd-4af2-baa8-636f604a6cea'
		paragraph
			StaticText Trusted by data-driven companies from startups to global enterprises
		[337] video, center=(1186,351)
		group 1 / 12
			image Recycleye, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/663af732fd45f871b0bc9d14_Recycleye.webp'
		group 2 / 12
			image 2. Fieldwork, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/663af7323a297dff84471f03_Fieldwork.webp'
		group 3 / 12
			image Remora, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/669eb620f443a11cb692fd6c_remora_logo_blue.webp'
		group 4 / 12
			image Columbo, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/663af73340262b45c15b56f7_Columbo.webp'
		group 5 / 12
			image Autonomo, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/663af732fd45f871b0bc9ce7_autonomo.webp'
		group 6 / 12
			image nvidia, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/665eafaacfe6b02f34a086da_nvidia.avif'
		group 7 / 12
			image intel, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/665eafd5cb012492f3000c9a_intel.avif'
		group 8 / 12
			image keymakr, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/665eb01347f02a4939e66cfc_keymakr.avif'
		group 9 / 12
			image Horiba, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/663af732f60702fea22e1618_horiba.webp'
		group 10 / 12
			image Imagga, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/663af732e11f97cc0d9c75da_imagga.webp'
		group 11 / 12
			image Safi, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/663af7320443543e13d2c66a_Safi.webp'
		group 12 / 12
			image KION, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/663af732514dced3ce38dda1_kion.webp'
		group 1 / 12
			image Recycleye, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/663af732fd45f871b0bc9d14_Recycleye.webp'
		group 2 / 12
			image 2. Fieldwork, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/663af7323a297dff84471f03_Fieldwork.webp'
		group 3 / 12
			image Remora, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/669eb620f443a11cb692fd6c_remora_logo_blue.webp'
		group 4 / 12
			image Columbo, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/663af73340262b45c15b56f7_Columbo.webp'
		group 5 / 12
			image Autonomo, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/663af732fd45f871b0bc9ce7_autonomo.webp'
		group 6 / 12
			image nvidia, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/665eafaacfe6b02f34a086da_nvidia.avif'
		group 7 / 12
			image intel, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/665eafd5cb012492f3000c9a_intel.avif'
		group 8 / 12
			image keymakr, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/665eb01347f02a4939e66cfc_keymakr.avif'
		group 9 / 12
			image Horiba, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/663af732f60702fea22e1618_horiba.webp'
		group 10 / 12
			image Imagga, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/663af732e11f97cc0d9c75da_imagga.webp'
		group 11 / 12
			image Safi, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/663af7320443543e13d2c66a_Safi.webp'
		group 12 / 12
			image KION, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/663af732514dced3ce38dda1_kion.webp'
		group 1 / 12
			image Recycleye, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/663af732fd45f871b0bc9d14_Recycleye.webp'
		group 2 / 12
			image 2. Fieldwork, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/663af7323a297dff84471f03_Fieldwork.webp'
		group 3 / 12
			image Remora, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/669eb620f443a11cb692fd6c_remora_logo_blue.webp'
		group 4 / 12
			image Columbo, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/663af73340262b45c15b56f7_Columbo.webp'
		group 5 / 12
			image Autonomo, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/663af732fd45f871b0bc9ce7_autonomo.webp'
		group 6 / 12
			image nvidia, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/665eafaacfe6b02f34a086da_nvidia.avif'
		group 7 / 12
			image intel, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/665eafd5cb012492f3000c9a_intel.avif'
		group 8 / 12
			image keymakr, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/665eb01347f02a4939e66cfc_keymakr.avif'
		group 9 / 12
			image Horiba, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/663af732f60702fea22e1618_horiba.webp'
		group 10 / 12
			image Imagga, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/663af732e11f97cc0d9c75da_imagga.webp'
		group 11 / 12
			image Safi, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/663af7320443543e13d2c66a_Safi.webp'
		group 12 / 12
			image KION, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/663af732514dced3ce38dda1_kion.webp'
		generic, atomic
		image product-icon, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673a5d0b55337a9ba494c78b_Product.png'
		StaticText Product
		heading Visual Intelligence Platform
		image Extract, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/67506631bfdca8e3de2b9d75_Extract-p-500.avif'
		StaticText Extract
		paragraph
			StaticText Extract, ingest and load diverse visual sources —including CCTV, drones, robots, media, and satellites.
		image Turn raw footage into searchable, taggable components and metrics., url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/67509491a2c2ff17d4ac1df1_Product_Extract_v3.avif'
		StaticText Transform
		paragraph
			StaticText Turn raw footage into searchable, taggable components and metrics.
		image Use multi-modal and reverse image searches to navigate through data and visualise the results in powerful BI dashboards., url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/67509492dc8d826cc57d179f_Product_Analyse_v3-p-500.avif'
		StaticText Analyse
		paragraph
			StaticText Use multi-modal and reverse image searches to navigate through data and visualise the results in powerful BI dashboards.
		image product-icon, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673a5e934f778469408e0f9d_Feature.avif'
		StaticText Functionalities
		heading Turn unstructured visual data into actionable intelligence
		paragraph
			StaticText Transform CCTV, drone, and satellite footage into actionable insights, with BI dashboards to track trends and drive smarter decisions.
		tabpanel drag-and-drop icon Multi-modal Search Find specific objects, events, people, and activities across large visual data assets.
		tablist, orientation='horizontal'
			tab drag-and-drop icon Multi-modal Search Find specific objects, events, people, and activities across large visual data assets., selected=True
				image drag-and-drop icon, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/63a086372fbe8d0f9afbf55e_icon-dragdrop.svg'
				heading Multi-modal Search
				paragraph
			tab Model Performance Powerful Dashboards, selected=False
				image Model Performance, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/63a08637889b46aa639a7324_icon-performance.svg'
				heading Powerful Dashboards
			tab Scenario Analysis Simple Integration, selected=False
				image Scenario Analysis, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/63a08637406f2f14f4bab203_icon-scenario.svg'
				heading Simple Integration
			tab Data Quality Analysis Scalable Data Processing, selected=False
				image Data Quality Analysis, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/63a08637d1f9587f9455e4f3_icon-dataquality.svg'
				heading Scalable Data Processing
					strong
		link Get Started, url='https://media.tenyks.ai/'
		image Industries-icon, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/63bfef21634af2bb3bf276f1_icon-industries.svg'
		StaticText Industries
		heading Who is Tenyks for?
		image Gain unparalleled visibility into customer behaviour by discovering insights about consumer preferences, dwell time, reactions to new products, and queue dynamic., url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673c976d0a845210888da16e_indsutries_retail_v3-p-500.webp'
		heading Retail
		paragraph
			StaticText Gain unparalleled visibility into customer behaviour by discovering insights about consumer preferences, dwell time, reactions to new products, and queue dynamic.
		link Read All, url='https://www.tenyks.ai/surveillance'
			image
		image Finance, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/675012d1568718a9fbdc2406_industries_finance_v4-p-500.webp'
		heading Finance
		paragraph
			StaticText Investment professionals access into a new and unique generation of insights to find market opportunities and capture alpha via untapped alternative data derived from visual sources.
		image Content creators reimagine the cubersome process of cataloguing terabytes of multi-year video footage to instantly access relevant content to accelerate pre-production, video editing, and social campaigns., url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673b9304c270136499b01db8_Media%20and%20Advertising-p-500.avif'
		heading Media and Advertising
		paragraph
			StaticText Content creators reimagine the cubersome process of cataloguing terabytes of multi-year video footage to instantly access relevant content to accelerate pre-production, video editing, and social campaigns.
		link Read All, url='https://www.tenyks.ai/media'
			image
		image product-icon, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673a5d0b55337a9ba494c78b_Product.png'
		StaticText Why Choose us?
		heading Built for multimodality, simplicity, and reliability
		heading Use Case Felexibility
		paragraph
			StaticText Easily integrate diverse visual sources.
		image, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673b6e12b66fb8696afe06d9_Use%20Case%20Felexibility-p-500.avif'
		image, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673b6c0489a9a6a9581b442a_Camera.svg'
		StaticText CCTV
		image, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673b6e94fc07f7d770854352_Satellite.svg'
		StaticText Satellites
		image, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673b6ebcae572571a32dc5fb_Drone.svg'
		StaticText Drones
		image, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673b6ed4d630d34cf86a6ade_Robot.svg'
		StaticText Robots
		image, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673b6ef19aee82d213941a45_Phone.svg'
		StaticText Phones
		image, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673b6f25057b731bcfadbc8c_Media.svg'
		StaticText Media
		image drag-and-drop icon, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673b7149457b6216d192b8f6_User-defined%20Features.avif'
		StaticText User-defined Features
		image drag-and-drop icon, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673b7167e48f918bb2dae071_Powerful%20BI%20Visualisations.avif'
		StaticText Powerful BI Visualisations
		image drag-and-drop icon, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673b7193cdfd7399e4fa3318_Multiple%20Data%20Sources.avif'
		StaticText Multiple Data Sources
		image drag-and-drop icon, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673b73e15bad832b6c735283_SOC%202%20Security%20%26%20Complience.avif'
		StaticText SOC 2 Security & Complience
		image drag-and-drop icon, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673b74085bad832b6c736da8_High%20Object%20Density.avif'
		StaticText High Object Density
		image drag-and-drop icon, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673b742bccbf2d859661c596_Precise%20Fine-tuning.avif'
		StaticText Precise Fine-tuning
		heading Support Low Resolution and Small Objects
		paragraph
			StaticText Our AI supports low resolutions and easily detects small objects.
		image Support Low Resolution and Small Objects, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673b766633ed4848edfcadef_Support%20Low%20Resolution%20and%20Small%20Objects-p-500.avif'
		image customer-icon, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/64b99626fb777c087f46bbf3_customer-icon.svg'
		StaticText Customers
		heading Hear from our Customers
		generic
			group 1 / 2
				image recycleye-logo, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/663af732fd45f871b0bc9d14_Recycleye.webp'
				image Peter-Hedley-avatar, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/64b9961dc1db50f4e4e7e14e_peter-hedley-min.png'
				StaticText Peter Hedley
				StaticText Chief Technology Officer,
				StaticText Recycleye
				paragraph
					StaticText "Working with Tenyks has been a game changer for us. We automated a previously laborious process, allowing our team to focus on more strategic activities. We tackled a bug we've been trying to squash for ages, and finally moved on without the stress of production models not performing exactly as we expect!"
				link Read All, url='https://www.tenyks.ai/case-study/recycleye-enhances-its-mlops-with-tenyks'
					image
			group 2 / 2
				image recycleye-logo, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/663af7323a297dff84471f03_Fieldwork.webp'
				image Peter-Hedley-avatar, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/663c4fe880a9e4b93be27651_Henry%20Jackson-Flux.webp'
				StaticText Henry Jackson-Flux
				StaticText Lead Research Engineer
				paragraph
					StaticText “Tenyks is a fantastic tool!  We are getting a huge amount of benefit from it. It’s becoming our source of truth, and we are relying on it more and more to streamline our ML Data pipeline.”
				link Read All, url='https://fieldworkrobotics.com/'
					image
			group 1 / 2
				image recycleye-logo, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/663af732fd45f871b0bc9d14_Recycleye.webp'
				image Peter-Hedley-avatar, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/64b9961dc1db50f4e4e7e14e_peter-hedley-min.png'
				StaticText Peter Hedley
				StaticText Chief Technology Officer,
				StaticText Recycleye
				paragraph
					StaticText "Working with Tenyks has been a game changer for us. We automated a previously laborious process, allowing our team to focus on more strategic activities. We tackled a bug we've been trying to squash for ages, and finally moved on without the stress of production models not performing exactly as we expect!"
				link Read All, url='https://www.tenyks.ai/case-study/recycleye-enhances-its-mlops-with-tenyks'
					image
			group 2 / 2
				image recycleye-logo, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/663af7323a297dff84471f03_Fieldwork.webp'
				image Peter-Hedley-avatar, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/663c4fe880a9e4b93be27651_Henry%20Jackson-Flux.webp'
				StaticText Henry Jackson-Flux
				StaticText Lead Research Engineer
				paragraph
					StaticText “Tenyks is a fantastic tool!  We are getting a huge amount of benefit from it. It’s becoming our source of truth, and we are relying on it more and more to streamline our ML Data pipeline.”
				link Read All, url='https://fieldworkrobotics.com/'
					image
			group 1 / 2
				image recycleye-logo, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/663af732fd45f871b0bc9d14_Recycleye.webp'
				image Peter-Hedley-avatar, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/64b9961dc1db50f4e4e7e14e_peter-hedley-min.png'
				StaticText Peter Hedley
				StaticText Chief Technology Officer,
				StaticText Recycleye
				paragraph
					StaticText "Working with Tenyks has been a game changer for us. We automated a previously laborious process, allowing our team to focus on more strategic activities. We tackled a bug we've been trying to squash for ages, and finally moved on without the stress of production models not performing exactly as we expect!"
				link Read All, url='https://www.tenyks.ai/case-study/recycleye-enhances-its-mlops-with-tenyks'
					image
			group 2 / 2
				image recycleye-logo, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/663af7323a297dff84471f03_Fieldwork.webp'
				image Peter-Hedley-avatar, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/663c4fe880a9e4b93be27651_Henry%20Jackson-Flux.webp'
				StaticText Henry Jackson-Flux
				StaticText Lead Research Engineer
				paragraph
					StaticText “Tenyks is a fantastic tool!  We are getting a huge amount of benefit from it. It’s becoming our source of truth, and we are relying on it more and more to streamline our ML Data pipeline.”
				link Read All, url='https://fieldworkrobotics.com/'
					image
		generic, atomic
		button Previous slide
			image
		button Next slide
			image
		button Go to slide 1
		button Go to slide 2
		image Industries-icon, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/675c6e17ba0bda1d18a41940_press.svg'
		StaticText Press
		heading As featured in
		link Forbes-logo, url='https://forbesbulgaria.com/2023/01/12/to-save-the-world-from-the-terminator/?utm_source=linkedin&utm_medium=link&utm_campaign=ForbesPage'
			image Forbes-logo, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673a77b0dcc68218bab073da_logo-forbes.avif'
		link Forbes-logo, url='https://techcrunch.com/2021/09/01/here-are-all-the-companies-from-day-two-of-y-combinators-summer-2021-demo-day/?guccounter=1'
			image Forbes-logo, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/675c713d8e6310d7137eb47c_techcrunch.avif'
		link Forbes-logo, url='https://therecursive.com/y-combinator-mlops-startup-tenyks-raises-3-4m-to-protect-the-world-from-the-ai-terminator/'
			image Forbes-logo, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673a77ede7e75e76b0e99698_logo-R.avif'
		link Forbes-logo, url='https://tech.eu/2022/03/07/cambridge-startup-ramps-up-3-4-million-to-show-how-ai-can-make-human-connections-deeper/'
			image Forbes-logo, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673a78304f77846940a16351_logo-tech.avif'
		link Forbes-logo, url='https://techfundingnews.com/tenyks-gets-34-million-to-develop-its-doctor-for-ai/'
			image Forbes-logo, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/675c71838d39fa539ca0aa8f_tfn.avif'
		link Forbes-logo, url='https://www.businessweekly.co.uk/posts/tenyks-lands-34m-for-human-ai-interaction-to-fend-off-the-terminator'
			image Forbes-logo, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/675c724e1569c2e8526be2fe_Business%20Weekly.avif'
		link Forbes-logo, url='https://sifted.eu/pro/briefings/gen-ai?25sif8X'
			image Forbes-logo, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673a789ab32cf036258f8d6a_logo-sifted.avif'
		image news-icon, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/63c1859a5af55d5bad9c0247_icon-news.svg'
		StaticText News
		heading Stay Updated with the Latest
		list
			group 4 / 6
				image, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673a5d0b55337a9ba494c78b_Product.png'
				StaticText 3 min read
				image, url='https://cdn.prod.website-files.com/63bfe0f56cd7cb4e1c759642/6501fd6b2940b69deab04c05_63d08c331819e072e95b33ca_tenyks_news-2-p-500.webp'
				link Cambridge startup Tenyks combats AI tech 'terminator', url='https://tech.eu/2022/03/07/cambridge-startup-ramps-up-3-4-million-to-show-how-ai-can-make-human-connections-deeper/'
				StaticText Celebrated Cambridge academic Stephen Hawking warned shortly before his death that if AI wasn't managed carefully it could spell the end of the human race.
				link Read All, url='https://www.tenyks.ai/news/cambridge-startup-tenyks-combats-ai-tech-terminator'
					image
				image, url='https://cdn.prod.website-files.com/63bfe0f56cd7cb4e1c759642/63c1c06917b4805a91ccc470_news-1-logo.png'
			group 5 / 6
				image, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673a5d0b55337a9ba494c78b_Product.png'
				StaticText 5 min read
				image, url='https://cdn.prod.website-files.com/63bfe0f56cd7cb4e1c759642/6501fd5ef71ac8514e21420c_63d08c5232a91dc0220f489e_tenyks_news-1-p-500.webp'
				link YC MLOps startup Tenyks raises $3.4M to protect the world from the AI terminator, url='https://therecursive.com/y-combinator-mlops-startup-tenyks-raises-3-4m-to-protect-the-world-from-the-ai-terminator/'
				StaticText Tenyks, the Cambridge University spin-off startup, closed a $3.4M round for the development of its MLOps tools platform to help ML engineers.
				link Read All, url='https://www.tenyks.ai/news/y-combinator-mlops-startup-tenyks-raises-3-4m-to-protect-the-world-from-the-ai-terminator'
					image
				image, url='https://cdn.prod.website-files.com/63bfe0f56cd7cb4e1c759642/63c1c0b6a3b16681d2e03fd3_news-2-logo.png'
			group 6 / 6
				image, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673a5d0b55337a9ba494c78b_Product.png'
				StaticText 3 min read
				image, url='https://cdn.prod.website-files.com/63bfe0f56cd7cb4e1c759642/6501fd54cf1d3b90ce983b76_63d08c5932a91d5a300f48af_tenyks_news-3-p-500.webp'
				link Tenyks Gets $3.4M to Develop its Doctor for AI, url='https://techfundingnews.com/tenyks-gets-34-million-to-develop-its-doctor-for-ai/'
				StaticText Tenyks, a spin-out from the University of Cambridge, hopes to provide the next breakthrough in AI after raising $3.4 million.
				link Read All, url='https://www.tenyks.ai/news/tenyks-gets-3-4m-to-develop-its-doctor-for-ai'
					image
				image, url='https://cdn.prod.website-files.com/63bfe0f56cd7cb4e1c759642/63c1c0cd732e931da797766f_news-3-logo.png'
			group 1 / 6
				image, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673a5d0b55337a9ba494c78b_Product.png'
				StaticText <1 min read
				image, url='https://cdn.prod.website-files.com/63bfe0f56cd7cb4e1c759642/6501fd115d44cd6927ea9bba_64651930d88bd8c9ef254d80_30U30Europe-p-500.webp'
				link Tenyks selected in Forbes Under 30, Technology Class of 2023, url='https://www.forbes.com/profile/tenyks/?sh=736597d66a69'
				StaticText The Founders of Tenyks were selected to be part of Forbes Under 30 Class Of 2023 for Powering a Digital Revolution.
				link Read All, url='https://www.tenyks.ai/news/tenyks-selected-in-forbes-under-30-technology-class-of-2023'
					image
				image, url='https://cdn.prod.website-files.com/63bfe0f56cd7cb4e1c759642/6462eb3dbc7291adea38689b_5847e9aacef1014c0b5e4828-p-500.png'
			group 2 / 6
				image, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673a5d0b55337a9ba494c78b_Product.png'
				StaticText 12 min read
				image, url='https://cdn.prod.website-files.com/63bfe0f56cd7cb4e1c759642/6501fd226b0919ca4a214830_645ee248c592fff767b18320_Screen%20Shot%202023-05-12%20at%2020.05.01-p-800-p-500.webp'
				link Tenyks wins Company of the Year at University of Cambridge, url='https://www.cst.cam.ac.uk/news/presenting-2022-hall-fame-awards'
				StaticText Tenyks wins the Company of the Year Hall of Fame Awards 2022 at the University of Cambridge.
				link Read All, url='https://www.tenyks.ai/news/tenyks-wins-company-of-the-year-cambridge-hall-of-fame'
					image
				image, url='https://cdn.prod.website-files.com/63bfe0f56cd7cb4e1c759642/6501fd31b31b392b324dce96_645ee26e4f8e6541f3f56787_logo-p-500.webp'
			group 3 / 6
				image, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673a5d0b55337a9ba494c78b_Product.png'
				StaticText 1 min read
				image, url='https://cdn.prod.website-files.com/63bfe0f56cd7cb4e1c759642/6501f9ac2940b69deaab4931_63ed6eb01fad0c46afb01d4f_Screen%20Shot%202023-02-15%20at%2018.45.48-p-800-p-500.webp'
				link Tenyks, a University of Cambridge spin-out focused on helping ML engineers, url='https://www.businessweekly.co.uk/killer-50/ones-watch/tenyks'
				StaticText The startup’s platform helps machine learning engineers working with computer vision data build more reliable software, faster.
				link Read All, url='https://www.tenyks.ai/news/tenyks-a-university-of-cambridge-spin-out-focused-on-helping-machine-learning-engineers-build-better-safer-ai-raised-a-3-4-million-seed-round-in-january-2022'
					image
				image, url='https://cdn.prod.website-files.com/63bfe0f56cd7cb4e1c759642/63ed6659451297faac9adca4_businesslogo555-p-500.webp'
			group 4 / 6
				image, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673a5d0b55337a9ba494c78b_Product.png'
				StaticText 3 min read
				image, url='https://cdn.prod.website-files.com/63bfe0f56cd7cb4e1c759642/6501fd6b2940b69deab04c05_63d08c331819e072e95b33ca_tenyks_news-2-p-500.webp'
				link Cambridge startup Tenyks combats AI tech 'terminator', url='https://tech.eu/2022/03/07/cambridge-startup-ramps-up-3-4-million-to-show-how-ai-can-make-human-connections-deeper/'
				StaticText Celebrated Cambridge academic Stephen Hawking warned shortly before his death that if AI wasn't managed carefully it could spell the end of the human race.
				link Read All, url='https://www.tenyks.ai/news/cambridge-startup-tenyks-combats-ai-tech-terminator'
					image
				image, url='https://cdn.prod.website-files.com/63bfe0f56cd7cb4e1c759642/63c1c06917b4805a91ccc470_news-1-logo.png'
			group 5 / 6
				image, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673a5d0b55337a9ba494c78b_Product.png'
				StaticText 5 min read
				image, url='https://cdn.prod.website-files.com/63bfe0f56cd7cb4e1c759642/6501fd5ef71ac8514e21420c_63d08c5232a91dc0220f489e_tenyks_news-1-p-500.webp'
				link YC MLOps startup Tenyks raises $3.4M to protect the world from the AI terminator, url='https://therecursive.com/y-combinator-mlops-startup-tenyks-raises-3-4m-to-protect-the-world-from-the-ai-terminator/'
				StaticText Tenyks, the Cambridge University spin-off startup, closed a $3.4M round for the development of its MLOps tools platform to help ML engineers.
				link Read All, url='https://www.tenyks.ai/news/y-combinator-mlops-startup-tenyks-raises-3-4m-to-protect-the-world-from-the-ai-terminator'
					image
				image, url='https://cdn.prod.website-files.com/63bfe0f56cd7cb4e1c759642/63c1c0b6a3b16681d2e03fd3_news-2-logo.png'
			group 6 / 6
				image, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673a5d0b55337a9ba494c78b_Product.png'
				StaticText 3 min read
				image, url='https://cdn.prod.website-files.com/63bfe0f56cd7cb4e1c759642/6501fd54cf1d3b90ce983b76_63d08c5932a91d5a300f48af_tenyks_news-3-p-500.webp'
				link Tenyks Gets $3.4M to Develop its Doctor for AI, url='https://techfundingnews.com/tenyks-gets-34-million-to-develop-its-doctor-for-ai/'
				StaticText Tenyks, a spin-out from the University of Cambridge, hopes to provide the next breakthrough in AI after raising $3.4 million.
				link Read All, url='https://www.tenyks.ai/news/tenyks-gets-3-4m-to-develop-its-doctor-for-ai'
					image
				image, url='https://cdn.prod.website-files.com/63bfe0f56cd7cb4e1c759642/63c1c0cd732e931da797766f_news-3-logo.png'
			group 1 / 6
				image, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673a5d0b55337a9ba494c78b_Product.png'
				StaticText <1 min read
				image, url='https://cdn.prod.website-files.com/63bfe0f56cd7cb4e1c759642/6501fd115d44cd6927ea9bba_64651930d88bd8c9ef254d80_30U30Europe-p-500.webp'
				link Tenyks selected in Forbes Under 30, Technology Class of 2023, url='https://www.forbes.com/profile/tenyks/?sh=736597d66a69'
				StaticText The Founders of Tenyks were selected to be part of Forbes Under 30 Class Of 2023 for Powering a Digital Revolution.
				link Read All, url='https://www.tenyks.ai/news/tenyks-selected-in-forbes-under-30-technology-class-of-2023'
					image
				image, url='https://cdn.prod.website-files.com/63bfe0f56cd7cb4e1c759642/6462eb3dbc7291adea38689b_5847e9aacef1014c0b5e4828-p-500.png'
			group 2 / 6
				image, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673a5d0b55337a9ba494c78b_Product.png'
				StaticText 12 min read
				image, url='https://cdn.prod.website-files.com/63bfe0f56cd7cb4e1c759642/6501fd226b0919ca4a214830_645ee248c592fff767b18320_Screen%20Shot%202023-05-12%20at%2020.05.01-p-800-p-500.webp'
				link Tenyks wins Company of the Year at University of Cambridge, url='https://www.cst.cam.ac.uk/news/presenting-2022-hall-fame-awards'
				StaticText Tenyks wins the Company of the Year Hall of Fame Awards 2022 at the University of Cambridge.
				link Read All, url='https://www.tenyks.ai/news/tenyks-wins-company-of-the-year-cambridge-hall-of-fame'
					image
				image, url='https://cdn.prod.website-files.com/63bfe0f56cd7cb4e1c759642/6501fd31b31b392b324dce96_645ee26e4f8e6541f3f56787_logo-p-500.webp'
			group 3 / 6
				image, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/673a5d0b55337a9ba494c78b_Product.png'
				StaticText 1 min read
				image, url='https://cdn.prod.website-files.com/63bfe0f56cd7cb4e1c759642/6501f9ac2940b69deaab4931_63ed6eb01fad0c46afb01d4f_Screen%20Shot%202023-02-15%20at%2018.45.48-p-800-p-500.webp'
				link Tenyks, a University of Cambridge spin-out focused on helping ML engineers, url='https://www.businessweekly.co.uk/killer-50/ones-watch/tenyks'
				StaticText The startup’s platform helps machine learning engineers working with computer vision data build more reliable software, faster.
				link Read All, url='https://www.tenyks.ai/news/tenyks-a-university-of-cambridge-spin-out-focused-on-helping-machine-learning-engineers-build-better-safer-ai-raised-a-3-4-million-seed-round-in-january-2022'
					image
				image, url='https://cdn.prod.website-files.com/63bfe0f56cd7cb4e1c759642/63ed6659451297faac9adca4_businesslogo555-p-500.webp'
		generic, atomic
		button Previous slide
			image
		button Next slide
			image
		image cta-icon, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/63c188d2690e4ae170a7ecea_icon-cta.svg'
		StaticText Try It Out
		heading Ready to Unlock the Power of Your Visual Data?
		paragraph
			StaticText Sign up to our Newsletter to stay updated
		form newsletter
			textbox Enter your email, required
			button Stay Updated
		link Book a Demo, url='https://meetings.hubspot.com/botty/schedule-demo-website?uuid=1d1b6a4d-a7bd-4af2-baa8-636f604a6cea'
		link Get Started, url='https://media.tenyks.ai/'
	link, url='https://www.tenyks.ai/'
		image, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/64ef6536af464e38d04d239d_Tenyks_Logo_icon_transparent.webp'
	heading TENYKS
	StaticText 28 Chesterton Road,
	StaticText Cambridge CB4 3AZ,
	StaticText United Kingdom
	link info@tenyks.ai, url='https://www.tenyks.ai/#'
	heading COMPANY
	link About, url='https://www.tenyks.ai/about'
	link Platform, url='https://www.tenyks.ai/#product'
	link Industries, url='https://www.tenyks.ai/#industries'
	link Contact Us, url='https://form.jotform.com/232282254201646'
	heading PLATFORM
	link Drag & Drop Integration, url='https://www.tenyks.ai/?tab=integration#functionalities'
	link Failure Analysis, url='https://www.tenyks.ai/?tab=failure#functionalities'
	link Model Comparison, url='https://www.tenyks.ai/?tab=model#functionalities'
	link Scenario Analysis, url='https://www.tenyks.ai/?tab=scenario#functionalities'
	link Data Quality Analysis, url='https://www.tenyks.ai/?tab=data#functionalities'
	heading RESOURCES
	link Blog, url='https://www.tenyks.ai/blog'
	link News, url='https://www.tenyks.ai/news'
	link Case studies, url='https://www.tenyks.ai/case-study/recycleye-enhances-its-mlops-with-tenyks'
	link Security, url='https://www.tenyks.ai/#'
	StaticText © Tenyks
	link Terms & Conditions, url='https://www.tenyks.ai/terms-and-conditions'
	link Privacy Policy, url='https://www.tenyks.ai/privacy-policy'
	link, url='https://twitter.com/Tenyks_AI'
		image
	link, url='https://www.linkedin.com/company/tenyks/'
		image
	link, url='https://medium.com/@tenyks_blogger'
		image, url='https://cdn.prod.website-files.com/63a0220866f41638081f4fce/63cdc58e8de9f2016954f670_tenyks-logo_medium.svg'
```
</details>



```
RootWebArea Tenyks App, focused, url='https://media.tenyks.ai/authentication/login'
	image Tenyks, url='https://media.tenyks.ai/assets/tenyks-logo-with-text-Ck5_Hdd4.webp'
	[18] video, center=(480,540)
	blockquote
		paragraph
```
<details><summary>Show more</summary>

```
			StaticText “
			StaticText This platform has saved me countless hours of work and helped me deliver stunning results faster than ever before.
			StaticText ”
		contentinfo
			StaticText Sofia Davis
	heading Login
	paragraph
		StaticText Enter your email below to login to your account
	LabelText
		StaticText Email
	[36] textbox Email, center=(1440,470), contenteditable=True, type=email
	LabelText
		StaticText Password
	[41] link Forgot your password?, center=(1536,532), url='https://media.tenyks.ai/authentication/forgot-password'
	[43] textbox Password, center=(1440,570), contenteditable=True, type=password
	[44] button Login, center=(1440,642), type=submit
	separator, orientation='horizontal'
	[46] button Login with Google, center=(1440,714)
		image, url='https://media.tenyks.ai/assets/google-logo-CKhf1V7v.png'
	StaticText Don't have an account?
	[49] link Sign up, center=(1525,768), url='https://media.tenyks.ai/authentication/register'
```
</details>

**Reasoning for action:** I clicked on the 'Get Started' button (ID: 218) because this button is likely to direct me to the registration page or the main features of the Tenyks platform. By accessing this page, I can begin the registration process, which is essential to meet the user's goal of creating a new account and utilizing the platform's features.

**Action:** click(218) # Click on the 'Get Started' button to explore further.

**Change Description:** The browser navigation transitioned from the Tenyks website's main interface to the Tenyks App login page, where users are prompted to enter their email and password to access their account.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://media.tenyks.ai/authentication/login

https://media.tenyks.ai/authentication/register

**Content (before/after):** 

```
RootWebArea Tenyks App, focused, url='https://media.tenyks.ai/authentication/login'
	image Tenyks, url='https://media.tenyks.ai/assets/tenyks-logo-with-text-Ck5_Hdd4.webp'
	[18] video, center=(480,540)
	blockquote
		paragraph
```
<details><summary>Show more</summary>

```
			StaticText “
			StaticText This platform has saved me countless hours of work and helped me deliver stunning results faster than ever before.
			StaticText ”
		contentinfo
			StaticText Sofia Davis
	heading Login
	paragraph
		StaticText Enter your email below to login to your account
	LabelText
		StaticText Email
	[36] textbox Email, center=(1440,470), contenteditable=True, type=email
	LabelText
		StaticText Password
	[41] link Forgot your password?, center=(1536,532), url='https://media.tenyks.ai/authentication/forgot-password'
	[43] textbox Password, center=(1440,570), contenteditable=True, type=password
	[44] button Login, center=(1440,642), type=submit
	separator, orientation='horizontal'
	[46] button Login with Google, center=(1440,714)
		image, url='https://media.tenyks.ai/assets/google-logo-CKhf1V7v.png'
	StaticText Don't have an account?
	[49] link Sign up, center=(1525,768), url='https://media.tenyks.ai/authentication/register'
```
</details>



```
RootWebArea Tenyks App, focused, url='https://media.tenyks.ai/authentication/register'
	image Tenyks, url='https://media.tenyks.ai/assets/tenyks-logo-with-text-Ck5_Hdd4.webp'
	[18] video, center=(480,540)
	blockquote
		paragraph
```
<details><summary>Show more</summary>

```
			StaticText “
			StaticText This platform has saved me countless hours of work and helped me deliver stunning results faster than ever before.
			StaticText ”
		contentinfo
			StaticText Sofia Davis
	heading Register
	paragraph
		StaticText Enter details below to create an account
	LabelText
		StaticText First name
	[62] textbox First name, center=(1440,344), contenteditable=True
	LabelText
		StaticText Last name
	[67] textbox Last name, center=(1440,448), contenteditable=True
	LabelText
		StaticText Email
	[72] textbox Email, center=(1440,552), contenteditable=True, type=email
	LabelText
		StaticText Password
	[77] textbox Password, center=(1440,656), contenteditable=True, type=password
	[78] button Register, center=(1440,728), type=submit
	separator, orientation='horizontal'
	[80] button Google logo Continue with Google, center=(1440,800), inner_text=Continue with Google
		image Google logo, url='https://media.tenyks.ai/assets/google-logo-CKhf1V7v.png'
	StaticText Already have an account?
	[83] link Login, center=(1533,870), url='https://media.tenyks.ai/authentication/login'
```
</details>

**Reasoning for action:** I chose to click on the 'Sign up' link because the user story indicates that the task involves registering for a new account. By clicking this link, I am redirecting the user to the appropriate registration page where they can enter their first name, last name, email, and password as required. This step is essential for progressing towards the user's goal of leveraging the Tenyks platform features.

**Action:** click(49) # Click on the 'Sign up' link to explore the registration process.

**Change Description:** The browser navigated from the login page to the registration page of the Tenyks App, changing the URL to 'https://media.tenyks.ai/authentication/register'; the content now prompts users to enter their details for creating an account instead of logging in, featuring new fields for 'First name' and 'Last name'.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://media.tenyks.ai/authentication/register

https://media.tenyks.ai/authentication/register

**Content (before/after):** 

```
RootWebArea Tenyks App, focused, url='https://media.tenyks.ai/authentication/register'
	image Tenyks, url='https://media.tenyks.ai/assets/tenyks-logo-with-text-Ck5_Hdd4.webp'
	[18] video, center=(480,540)
	blockquote
		paragraph
```
<details><summary>Show more</summary>

```
			StaticText “
			StaticText This platform has saved me countless hours of work and helped me deliver stunning results faster than ever before.
			StaticText ”
		contentinfo
			StaticText Sofia Davis
	heading Register
	paragraph
		StaticText Enter details below to create an account
	LabelText
		StaticText First name
	[62] textbox First name, center=(1440,344), contenteditable=True
	LabelText
		StaticText Last name
	[67] textbox Last name, center=(1440,448), contenteditable=True
	LabelText
		StaticText Email
	[72] textbox Email, center=(1440,552), contenteditable=True, type=email
	LabelText
		StaticText Password
	[77] textbox Password, center=(1440,656), contenteditable=True, type=password
	[78] button Register, center=(1440,728), type=submit
	separator, orientation='horizontal'
	[80] button Google logo Continue with Google, center=(1440,800), inner_text=Continue with Google
		image Google logo, url='https://media.tenyks.ai/assets/google-logo-CKhf1V7v.png'
	StaticText Already have an account?
	[83] link Login, center=(1533,870), url='https://media.tenyks.ai/authentication/login'
```
</details>



```
RootWebArea Tenyks App, focused, url='https://media.tenyks.ai/authentication/register'
	image Tenyks, url='https://media.tenyks.ai/assets/tenyks-logo-with-text-Ck5_Hdd4.webp'
	[18] video, center=(480,540)
	blockquote
		paragraph
```
<details><summary>Show more</summary>

```
			StaticText “
			StaticText This platform has saved me countless hours of work and helped me deliver stunning results faster than ever before.
			StaticText ”
		contentinfo
			StaticText Sofia Davis
	heading Register
	paragraph
		StaticText Enter details below to create an account
	LabelText
		StaticText First name
	[62] textbox First name value='Tom', center=(1440,344), contenteditable=True
	LabelText
		StaticText Last name
	[67] textbox Last name value='Cruise', center=(1440,448), contenteditable=True
	LabelText
		StaticText Email
	[72] textbox Email, center=(1440,552), contenteditable=True, type=email
	LabelText
		StaticText Password
	[77] textbox Password value='••••••••••••••••••••••••', center=(1440,656), contenteditable=True, focused, type=password
	[78] button Register, center=(1440,728), type=submit
	separator, orientation='horizontal'
	[80] button Google logo Continue with Google, center=(1440,800), inner_text=Continue with Google
		image Google logo, url='https://media.tenyks.ai/assets/google-logo-CKhf1V7v.png'
	StaticText Already have an account?
	[83] link Login, center=(1533,870), url='https://media.tenyks.ai/authentication/login'
```
</details>

**Reasoning for action:** Filling in the first name, last name, email, and password in the registration form is necessary to meet the success criteria outlined in the user story. Since the registration form requires these specific details to create a new account, completing this step ensures that I am adhering to the required inputs for successful registration. By doing this, I am moving closer to receiving confirmation that the account has been created.

**Action:** fill(62, 'Tom') # Fill in the first name
fill(67, 'Cruise') # Fill in the last name
fill(72, 'm@example.com') # Fill in the email
fill(77, 'password123') # Fill in the password

**Change Description:** The first name, last name, email, and password textboxes were filled with the values 'Tom', 'Cruise', 'm@example.com', and 'password123', respectively, updating their content in the form. The password textbox now shows a masked value while still being editable.

**Screenshot before:****Screenshot after:**---

