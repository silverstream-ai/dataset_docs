# Task

**Explore Use Cases on Flowise**

As a potential customer,
I explore the features and practical applications of Flowise,
so that I can understand how Flowise can help me build customized LLM apps.

**Success definition:** Given I am on the Flowise homepage
When I click on the 'Features' link and then the 'Use Cases' link followed by 'Product Catalog'
Then I should be presented with the various use cases of Flowise, including a detailed view of the product catalog use case.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://flowiseai.com/

https://flowiseai.com/#features

**Content (before/after):** 

```
RootWebArea Flowise - Low code LLM Apps Builder, focused, url='https://flowiseai.com/'
	banner
		[51] link Flowise, center=(473,40), url='https://flowiseai.com/'
			image Flowise, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Flogo-color-high.e60de2f8.png&w=256&q=75'
		link Star FlowiseAI/Flowise on GitHub, url='https://github.com/FlowiseAI/Flowise'
```
<details><summary>Show more</summary>

```
		link 33609 stargazers on GitHub, url='https://github.com/FlowiseAI/Flowise/stargazers'
			StaticText 33,609
		navigation
			list
				listitem
					[59] link Features, center=(789,40), url='https://flowiseai.com/#features'
				listitem
					[61] link Use Cases, center=(893,40), url='https://flowiseai.com/#usecases'
				listitem
					[63] link Pricing, center=(989,40), url='https://flowiseai.com/#pricing'
				listitem
					[65] link Community, center=(1089,40), url='https://flowiseai.com/#community'
				listitem
					[67] link Webinars, center=(1198,40), url='https://flowiseai.com/#webinars'
				listitem
					[69] link Login, center=(1296,40), url='https://flowiseai.com/auth/login'
						button Login
				listitem
					[72] link Request Access, center=(1428,40), url='https://flowiseai.com/join'
						button Request Access
							image
	main
		heading Build LLM Apps
		heading Easily
		paragraph
			StaticText Open source low-code tool for developers to build customized LLM orchestration flow & AI agents
		[112] link Request Access, center=(862,357), url='https://flowiseai.com/join'
			button Request Access
				image
		[115] link Documentation, center=(1072,357), url='https://docs.flowiseai.com/'
			button Documentation
		StaticText Backed by
		image YCombinator, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2FYC.dc9b9030.png&w=32&q=75'
		StaticText Combinator
		paragraph
			StaticText Trusted and used by teams around the globe
		[124] video, center=(960,582)
		image AWS, url='https://flowiseai.com/_next/static/media/aws.c9a4034b.svg'
		image Alibaba, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Falibaba.d717abe3.png&w=128&q=75'
		image Hitachi, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fhitachi.cc8b5524.png&w=64&q=75'
		image ByteDance, url='https://flowiseai.com/_next/static/media/ByteDance.cfa75bfd.svg'
		image Microsoft, url='https://flowiseai.com/_next/static/media/microsoft.0e14c6cf.svg'
		image InsightSoftware, url='https://flowiseai.com/_next/static/media/insightsoftware.c5783e21.svg'
		image Google, url='https://flowiseai.com/_next/static/media/google.c43e43a7.svg'
		image Accenture, url='https://flowiseai.com/_next/static/media/accenture.3222125e.svg'
		image ERoad, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Feroad.ea8bab6e.png&w=64&q=75'
		image AWS, url='https://flowiseai.com/_next/static/media/aws.c9a4034b.svg'
		image Alibaba, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Falibaba.d717abe3.png&w=128&q=75'
		image Hitachi, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fhitachi.cc8b5524.png&w=64&q=75'
		image ByteDance, url='https://flowiseai.com/_next/static/media/ByteDance.cfa75bfd.svg'
		image Microsoft, url='https://flowiseai.com/_next/static/media/microsoft.0e14c6cf.svg'
		image InsightSoftware, url='https://flowiseai.com/_next/static/media/insightsoftware.c5783e21.svg'
		image Google, url='https://flowiseai.com/_next/static/media/google.c43e43a7.svg'
		image Accenture, url='https://flowiseai.com/_next/static/media/accenture.3222125e.svg'
		image ERoad, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Feroad.ea8bab6e.png&w=64&q=75'
		heading Iterate, fast
		paragraph
			StaticText Developing LLM apps takes countless iterations. With low code approach, we enable quick iterations to go from testing to production
		list
			listitem
				StaticText $
				StaticText npm install -g flowise
			listitem
				StaticText $
				StaticText npx flowise start
		link Get Started, url='https://docs.flowiseai.com/getting-started'
		image Features 01, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fintegrations1.8181abd6.png&w=640&q=75'
		StaticText Chatflow
		heading LLM Orchestration
		paragraph
			StaticText Connect LLMs with memory, data loaders, cache, moderation and many more
		list
			listitem
				image
				StaticText Langchain
			listitem
				image
				StaticText LlamaIndex
			listitem
				image
				StaticText 100+ integrations
		StaticText Agents
		heading Agents & Assistants
		paragraph
			StaticText Create autonomous agent that can uses tools to execute different tasks
		list
			listitem
				image
				StaticText Custom Tools
			listitem
				image
				StaticText OpenAI Assistant
			listitem
				image
				StaticText Function Agent
		list
			listitem
				StaticText import
				StaticText requests
			listitem
			listitem
				StaticText url
				StaticText =
				StaticText "/api/v1/prediction/:id"
			listitem
			listitem
				StaticText def
				StaticText query
				StaticText (
				StaticText payload
				StaticText )
				StaticText :
			listitem
				StaticText response
				StaticText =
				StaticText requests.post
				StaticText (
			listitem
				StaticText url,
			listitem
				StaticText json
				StaticText =
				StaticText payload
			listitem
				StaticText )
			listitem
				StaticText return
				StaticText response.json
				StaticText (
				StaticText )
			listitem
			listitem
				StaticText output
				StaticText =
				StaticText query
				StaticText (
				StaticText {
			listitem
				StaticText question
				StaticText :
				StaticText "hello!"
			listitem
				StaticText )
				StaticText }
		StaticText Developer Friendly
		heading API, SDK, Embed
		paragraph
			StaticText Extend and integrate to your applications using APIs, SDK and Embedded Chat
		list
			listitem
				image
				StaticText APIs
			listitem
				image
				StaticText Embedded Widget
			listitem
				image
				StaticText React SDK
		image Features 02, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fopensource.bed900d8.png&w=640&q=75'
		StaticText Platform Agnostic
		heading Open source LLMs
		paragraph
			StaticText Run in air-gapped environment with local LLMs, embeddings and vector databases
		list
			listitem
				image
				StaticText HuggingFace, Ollama, LocalAI, Replicate
			listitem
				image
				StaticText Llama2, Mistral, Vicuna, Orca, Llava
			listitem
				image
				StaticText Self host on AWS, Azure, GCP
		heading Use Cases
		paragraph
			StaticText One platform, endless possibilities. See some of the use cases
		button Product Catalog
		button Product Description
		button Query SQL Database
		button Customer Support
		button Structured Data
		paragraph
			StaticText Product catalog chatbot to answer any questions related to the products
		image ProductCatalog, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fproductcatalog.9d6b9124.png&w=1920&q=75'
		heading Pricing
		paragraph
			StaticText Free 14 day trial. No credit card required.
		heading Starter
		paragraph
			StaticText For individuals & small teams
		paragraph
			StaticText $35
			StaticText /month
		list
			listitem
				image
				StaticText 10,000 Predictions / month
				button
					image
				StaticText then $0.001 per prediction
			listitem
				image
				StaticText 1GB Storage
				button
					image
			listitem
				image
				StaticText Database Backup
			listitem
				image
				StaticText 1 Week Log Retention
			listitem
				image
				StaticText Evaluations & Metrics
			listitem
				image
				StaticText Custom Chatbot Branding
				button
					image
			listitem
				image
				StaticText Community Support
		link Start free trial, url='https://flowiseai.com/join'
			button Start free trial
		heading Pro
		paragraph
			StaticText For medium-sized businesses
		paragraph
			StaticText $65
			StaticText /month
		list
			listitem
				image
				StaticText Everything in Starter
			listitem
				image
				StaticText 50,000 Predictions / month
				button
					image
				StaticText then $0.001 per prediction
			listitem
				image
				StaticText 10GB Storage
				button
					image
			listitem
				image
				StaticText Unlimited Workspaces
			listitem
				image
				StaticText Admin Roles & Permissions
			listitem
				image
				StaticText 3 Months Log Retention
			listitem
				image
				StaticText Priority Support
		button Coming Soon, disabled=True
		heading Enterprise
		paragraph
			StaticText For large organizations
		paragraph
			StaticText Contact Us
		list
			listitem
				image
				StaticText On-Premise Deployment
			listitem
				image
				StaticText Air-gapped Environments
			listitem
				image
				StaticText SSO & SAML
			listitem
				image
				StaticText LDAP & RBAC
			listitem
				image
				StaticText Versioning
			listitem
				image
				StaticText Audit Logs
			listitem
				image
				StaticText 99.99% Uptime SLA
		link Contact Us, url='mailto:hello@flowiseai.com'
			button Contact Us
		heading Community 🫶
		paragraph
			StaticText Open source community is the heart of Flowise. See why developers love and build using Flowise
		link Join Discord, url='https://discord.gg/jbaHfsRVBW'
			image
		Iframe
			RootWebArea Flowise AI Tutorial #1 - Introduction & Setup - YouTube, url='https://www.youtube.com/embed/tD6fwQyUIJE?si=na1zK5OISsE4N5Vg'
				[a30] link Photo image of Leon van Zyl, center=(440,5756)
				[a38] link Flowise AI Tutorial #1 - Introduction & Setup, center=(585,5757), url='https://www.youtube.com/watch?v=tD6fwQyUIJE'
				[a68] button More, center=(724,5750), hasPopup='menu'
					image
				[a79] button Play, center=(584,5823)
					image
				generic, atomic
		Iframe
			RootWebArea How to Build an AI Document Chatbot in 10 Minutes - YouTube, url='https://www.youtube.com/embed/riXpu1tHzl0?si=KLVQ9TRUcZCTjXuj'
				[b30] link Photo image of Dave Ebbelaar, center=(816,5756)
				[b38] link How to Build an AI Document Chatbot in 10 Minutes, center=(961,5757), url='https://www.youtube.com/watch?v=riXpu1tHzl0'
				[b68] button More, center=(1100,5750), hasPopup='menu'
					image
				[b79] button Play, center=(960,5823)
					image
				generic, atomic
		Iframe
			RootWebArea Flowise is an open source no-code UI visual tool to build 🦜🔗LangChain applications - YouTube, url='https://www.youtube.com/embed/CovAPtQPU0k?si=KcH3ttNubGtp03Za'
				[c30] link Photo image of Cobus Greyling, center=(1192,5756)
				[c38] link Flowise is an open source no-code UI visual tool to build 🦜🔗LangChain applications, center=(1337,5757), url='https://www.youtube.com/watch?v=CovAPtQPU0k'
				[c68] button More, center=(1476,5750), hasPopup='menu'
					image
				[c79] button Play, center=(1336,5823)
					image
				generic, atomic
		Iframe
			RootWebArea Flowise: No Code ChatBot Building Platform: LangChain - YouTube, url='https://www.youtube.com/embed/Q7_dKkosJY4?si=O0swoActrfHlDFSN'
				[d30] link Photo image of Prompt Engineering, center=(440,5978)
				[d38] link Flowise: No Code ChatBot Building Platform: LangChain, center=(585,5979), url='https://www.youtube.com/watch?v=Q7_dKkosJY4'
				[d68] button More, center=(724,5972), hasPopup='menu'
					image
				[d79] button Play, center=(584,6045)
					image
				generic, atomic
		Iframe
			RootWebArea Build a No-Code Chat-with-PDF LangChain app using Flowise and Bubble - YouTube, url='https://www.youtube.com/embed/kOwmPe8aLAA?si=gBaUlkyFOe3TS2V-'
				[e30] link Photo image of AI with Misbah, center=(816,5978)
				[e38] link Build a No-Code Chat-with-PDF LangChain app using Flowise and Bubble, center=(961,5979), url='https://www.youtube.com/watch?v=kOwmPe8aLAA'
				[e68] button More, center=(1100,5972), hasPopup='menu'
					image
				[e79] button Play, center=(960,6045)
					image
				generic, atomic
		Iframe
			RootWebArea Flowise AI: Create LLM Apps with NO Code - FREE Opensource LangChain Apps - YouTube, url='https://www.youtube.com/embed/kvvBUz0q-6I?si=WtrfQ948R1c2dHpf'
				[f30] link Photo image of WorldofAI, center=(1192,5978)
				[f38] link Flowise AI: Create LLM Apps with NO Code - FREE Opensource LangChain Apps, center=(1337,5979), url='https://www.youtube.com/watch?v=kvvBUz0q-6I'
				[f68] button More, center=(1476,5972), hasPopup='menu'
					image
				[f79] button Play, center=(1336,6045)
					image
				generic, atomic
		article
			link Siddhant Gupta, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
				image Siddhant Gupta, url='https://pbs.twimg.com/profile_images/1761449475883835392/yYkjTFPr_normal.jpg'
			link Siddhant Gupta Verified account, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
				image Verified account
			link @Siddhan65490545, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=Siddhan65490545'
			link View on Twitter, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
			paragraph
				StaticText Finally after a month of relentless trial and error, I've successfully created an AI persona bot emulating the teaching style of my mentor
				link @abnux, url='https://twitter.com/abnux'
				StaticText ,  the founder of
				link @10kdesigners, url='https://twitter.com/10kdesigners'
				StaticText . Excited to share my journey in this twitter thread. 🤖🎨 "Sound on 🎙️🔊"
			button View video on Twitter
			link Watch on Twitter, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
			link 2:43 PM · Oct 10, 2023, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 262 likes, url='https://twitter.com/intent/like?tweet_id=1711754261527458189'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1711754261527458189'
			button Copy link
			link Read 33 replies, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
		article
			link Shubham Saboo, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
				image Shubham Saboo, url='https://pbs.twimg.com/profile_images/1670107849815478273/Q3oUhtHM_normal.jpg'
			link Shubham Saboo Verified account, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
				image Verified account
			link @Saboo_Shubham_, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=Saboo_Shubham_'
			link View on Twitter, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
			paragraph
				StaticText Flowise is trending on GitHub

It's an open-source drag & drop UI tool that lets you build custom LLM apps in just minutes.

Powered by LangChain, it features:
- Ready-to-use app templates
- Conversational agents that remember
- Seamless deployment on cloud platforms
			button View video on Twitter
			link Watch on Twitter, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
			link 4:05 AM · Aug 16, 2023, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 523 likes, url='https://twitter.com/intent/like?tweet_id=1691662432807137623'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1691662432807137623'
			button Copy link
			link Read 18 replies, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
		article
			link Muratcan Koylan, url='https://twitter.com/youraimarketer/status/1710908393265782900'
				image Muratcan Koylan, url='https://pbs.twimg.com/profile_images/1847174349335257088/cGzzFLOo_normal.jpg'
			link Muratcan Koylan Verified account, url='https://twitter.com/youraimarketer/status/1710908393265782900'
				image Verified account
			link @youraimarketer, url='https://twitter.com/youraimarketer/status/1710908393265782900'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=youraimarketer'
			link View on Twitter, url='https://twitter.com/youraimarketer/status/1710908393265782900'
			paragraph
				StaticText When you lose momentum, it's hard to regain it.

But here we go again, building a Personal Cockpit with AI Agents.

I've built a chatbot connected to the internet and various APIs, linking it to multiple workflows and AI agents.

Here's the first demo:

1. AI Newsletter Agent…
			button View video on Twitter
			link Watch on Twitter, url='https://twitter.com/youraimarketer/status/1710908393265782900'
			link 6:42 AM · Oct 8, 2023, url='https://twitter.com/youraimarketer/status/1710908393265782900'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 468 likes, url='https://twitter.com/intent/like?tweet_id=1710908393265782900'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1710908393265782900'
			button Copy link
			link Read 17 replies, url='https://twitter.com/youraimarketer/status/1710908393265782900'
		article
			link Eugene, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
				image Eugene, url='https://pbs.twimg.com/profile_images/1501559855865339914/1FzvS9lb_normal.jpg'
			link Eugene, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
			link @sudo_eugene, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=sudo_eugene'
			link View on Twitter, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
			paragraph
				StaticText Using our new AI bot called Koos with
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText to create project management tasks in Notion, right from Slack 🤯

Let me know who would like to see a 5min explainer on how we did this 🎉
			link Image, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
				image Image, url='https://pbs.twimg.com/media/F6dMWW-WsAAUR7d?format=jpg&name=small'
			link Image, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
				image Image, url='https://pbs.twimg.com/media/F6dMWW_XgAEfotx?format=jpg&name=small'
			link 8:39 AM · Sep 20, 2023, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 16 likes, url='https://twitter.com/intent/like?tweet_id=1704414944551125293'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1704414944551125293'
			button Copy link
			link Read 8 replies, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
		article
			link Lior⚡, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
				image Lior⚡, url='https://pbs.twimg.com/profile_images/1817166841992597504/zLRK5Qx__normal.jpg'
			link Lior⚡ Verified account, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
				image Verified account
			link @LiorOnAI, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=LiorOnAI'
			link View on Twitter, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
			paragraph
				StaticText Flowise just reached 12,000 stars on Github. 

It allows you to build customized LLM apps using a simple drag & drop UI.

You can even use built-in templates with logic and conditions connected to LangChain and GPT:

▸ Conversational agent with memory
▸ Chat with PDF and Excel…
			button View video on Twitter
			link Watch on Twitter, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
			link 4:33 PM · Aug 10, 2023, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 836 likes, url='https://twitter.com/intent/like?tweet_id=1689676278746529793'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1689676278746529793'
			button Copy link
			link Read 30 replies, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
		article
			link Derek Cheung, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
				image Derek Cheung, url='https://pbs.twimg.com/profile_images/1653155172414046209/-_tpBZHC_normal.jpg'
			link Derek Cheung Verified account, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
				image Verified account
			link @derekcheungsa, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=derekcheungsa'
			link View on Twitter, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
			paragraph
				StaticText A multi-modal chatbot that effortlessly merges text and image generation into seamless conversations. 🚀

📢 Watch the demo with conversation starting with asking for advice on building strong financial habits (sped up slightly for demo)
 🪄Chatbot magically generates a visual…
			button View video on Twitter
			link Watch on Twitter, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
			link 3:11 AM · Oct 2, 2023, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 21 likes, url='https://twitter.com/intent/like?tweet_id=1708681200661889447'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1708681200661889447'
			button Copy link
			link Read 4 replies, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
		article
			link armand, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
				image armand, url='https://pbs.twimg.com/profile_images/1758729285744091136/9nZk7KcA_normal.jpg'
			link armand Verified account, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
				image Verified account
			link @armand_ruiz, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=armand_ruiz'
			link View on Twitter, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
			paragraph
				StaticText Create your first custom chatbot using LLMs in 5 min!

No-coding required. We will use
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText Join here to get the step-by-step tutorial and video tomorrow at 7 a.m. ET:
				link nocode.ai, url='https://www.nocode.ai/'
			link Image, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
				image Image, url='https://pbs.twimg.com/media/F4ZG8HwaEAAhSE9?format=jpg&name=small'
			link 5:06 PM · Aug 25, 2023, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 13 likes, url='https://twitter.com/intent/like?tweet_id=1695120505945383161'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1695120505945383161'
			button Copy link
			link Read 3 replies, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
		article
			link Alessio Pomaro, url='https://twitter.com/alepom/status/1694599974716153904'
				image Alessio Pomaro, url='https://pbs.twimg.com/profile_images/1350189157931479041/LaWfQ0IQ_normal.jpg'
			link Alessio Pomaro, url='https://twitter.com/alepom/status/1694599974716153904'
			link @alepom, url='https://twitter.com/alepom/status/1694599974716153904'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=alepom'
			link View on Twitter, url='https://twitter.com/alepom/status/1694599974716153904'
			paragraph
				StaticText 🧠 Realizzare un
				link #chatbot, url='https://twitter.com/hashtag/chatbot'
				StaticText o una ricerca evoluta per un sito web: quanto sarebbe stato complesso un paio d'anni fa? Tanto. Pochi servizi erano davvero efficienti. 
🦾 Nelle immagini si vede un'esempio di come l'ho creato con
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText .
				link #AI, url='https://twitter.com/hashtag/AI'
				link #Flowise, url='https://twitter.com/hashtag/Flowise'
				link #LLaMA2, url='https://twitter.com/hashtag/LLaMA2'
				link #Claude, url='https://twitter.com/hashtag/Claude'
			link Image, url='https://twitter.com/alepom/status/1694599974716153904'
				image Image, url='https://pbs.twimg.com/media/F4RtrXGWQAAdnSg?format=jpg&name=small'
			link Image, url='https://twitter.com/alepom/status/1694599974716153904'
				image Image, url='https://pbs.twimg.com/media/F4RtrygWUAAFCua?format=jpg&name=small'
			link Image, url='https://twitter.com/alepom/status/1694599974716153904'
				image Image, url='https://pbs.twimg.com/media/F4RtsJjXIAAJOhx?format=jpg&name=small'
			link Image, url='https://twitter.com/alepom/status/1694599974716153904'
				image Image, url='https://pbs.twimg.com/media/F4RtscNXgAAMGhu?format=png&name=small'
			link 6:38 AM · Aug 24, 2023, url='https://twitter.com/alepom/status/1694599974716153904'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 7 likes, url='https://twitter.com/intent/like?tweet_id=1694599974716153904'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1694599974716153904'
			button Copy link
			link Read 2 replies, url='https://twitter.com/alepom/status/1694599974716153904'
		article
			link John Damask, url='https://twitter.com/jbdamask/status/1693777249009373584'
				image John Damask, url='https://pbs.twimg.com/profile_images/1688209206204121093/9iNcGQoo_normal.jpg'
			link John Damask Verified account, url='https://twitter.com/jbdamask/status/1693777249009373584'
				image Verified account
			link @jbdamask, url='https://twitter.com/jbdamask/status/1693777249009373584'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=jbdamask'
			link View on Twitter, url='https://twitter.com/jbdamask/status/1693777249009373584'
			paragraph
				StaticText Flowise is seriously impressive. Not only for quickly building and deploying LLM apps, but for visualizing chains
			link 12:08 AM · Aug 22, 2023, url='https://twitter.com/jbdamask/status/1693777249009373584'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 9 likes, url='https://twitter.com/intent/like?tweet_id=1693777249009373584'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1693777249009373584'
			button Copy link
			link Read 3 replies, url='https://twitter.com/jbdamask/status/1693777249009373584'
		article
			link Abu Mu'aaz, url='https://twitter.com/abumuaaz/status/1693448039594381481'
				image Abu Mu'aaz, url='https://pbs.twimg.com/profile_images/1396343945190285314/brEgb4B9_normal.jpg'
			link Abu Mu'aaz, url='https://twitter.com/abumuaaz/status/1693448039594381481'
			link @abumuaaz, url='https://twitter.com/abumuaaz/status/1693448039594381481'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=abumuaaz'
			link View on Twitter, url='https://twitter.com/abumuaaz/status/1693448039594381481'
			paragraph
				StaticText Thanks to
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText &
				link @LangChainAI, url='https://twitter.com/LangChainAI'
				StaticText , it's so easy to create Telegram Bot that capable of getting real-time bus info (location & speed) from GPS device. Plus more functionality to calculate distance, duration & presenting map to user.
				link @OpenAI, url='https://twitter.com/OpenAI'
				StaticText Function Calling is awesome too 👍
			link Image, url='https://twitter.com/abumuaaz/status/1693448039594381481'
				image Image, url='https://pbs.twimg.com/media/F4BToWubcAANu1L?format=jpg&name=small'
			link Image, url='https://twitter.com/abumuaaz/status/1693448039594381481'
				image Image, url='https://pbs.twimg.com/media/F4BTptvbgAIc_hK?format=jpg&name=small'
			link 2:20 AM · Aug 21, 2023, url='https://twitter.com/abumuaaz/status/1693448039594381481'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 16 likes, url='https://twitter.com/intent/like?tweet_id=1693448039594381481'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1693448039594381481'
			button Copy link
			link Read 3 replies, url='https://twitter.com/abumuaaz/status/1693448039594381481'
		article
			link Wayne Culbreth, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
				image Wayne Culbreth, url='https://pbs.twimg.com/profile_images/1622684462587777037/_SDI7qtQ_normal.png'
			link Wayne Culbreth Verified account, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
				image Verified account
			link @wayne_culbreth, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=wayne_culbreth'
			link View on Twitter, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
			paragraph
				StaticText If you are building in AI and not using
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText - you are seriously wasting your time. It's like Figma but for backend AI applications. Design & test your entire stack in less than an hour. Even test MVP. Build to industrial scale with the exported output.
			link 6:56 PM · Aug 19, 2023, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 11 likes, url='https://twitter.com/intent/like?tweet_id=1692973803188392402'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1692973803188392402'
			button Copy link
			link Read 2 replies, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
		article
			link Damian Soto, url='https://twitter.com/sotoplatero/status/1692286497850855494'
				image Damian Soto, url='https://pbs.twimg.com/profile_images/1872860928502349824/HItLB9zt_normal.jpg'
			link Damian Soto, url='https://twitter.com/sotoplatero/status/1692286497850855494'
			link @sotoplatero, url='https://twitter.com/sotoplatero/status/1692286497850855494'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=sotoplatero'
			link View on Twitter, url='https://twitter.com/sotoplatero/status/1692286497850855494'
			paragraph
				StaticText Chatea Gratis con tus PDF sin código !!!

En este hilo te muestro como crear un chat gpt personalizado sin una linea de código que puedes incluir en tu web

Usamos
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText que es una increíble herramienta para crear aplicaciones LLM con
				link #nocode, url='https://twitter.com/hashtag/nocode'
				StaticText .

Empezamos🧵
			link Image, url='https://twitter.com/sotoplatero/status/1692286497850855494'
				image Image, url='https://pbs.twimg.com/media/F3w1mbEWUAQPpmL?format=jpg&name=small'
			link 9:25 PM · Aug 17, 2023, url='https://twitter.com/sotoplatero/status/1692286497850855494'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 22 likes, url='https://twitter.com/intent/like?tweet_id=1692286497850855494'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1692286497850855494'
			button Copy link
			link Read 2 replies, url='https://twitter.com/sotoplatero/status/1692286497850855494'
		article
			link VerySmallWoods, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
				image VerySmallWoods, url='https://pbs.twimg.com/profile_images/1600964189731934222/eWMb0-L2_normal.jpg'
			link VerySmallWoods Verified account, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
				image Verified account
			link @verysmallwoods, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=verysmallwoods'
			link View on Twitter, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
			paragraph
				StaticText AutoGen = LLM多代理框架 👨‍👩‍👧‍👦
Flowise = 无代码LLM工作流构建平台 0️⃣

由
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText 负责构建功能单元；由AutoGen负责调度协作，任务执行。

嗯！有点美妙！
🎏 🎀 🪄 🪅 🎊 🎉

AutoGen + Flowise = 零代码平台上的超级AI助理 

视频 👇
				link youtu.be/gKNR1ghU1Ao?si…, url='https://youtu.be/gKNR1ghU1Ao?si=ZI9jqz3ss51NG8HX'
				link #AutoGen, url='https://twitter.com/hashtag/AutoGen'
				link #Flowise, url='https://twitter.com/hashtag/Flowise'
				link #OpenAI, url='https://twitter.com/hashtag/OpenAI'
				StaticText …
			link 1:05 AM · Oct 22, 2023, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 11 likes, url='https://twitter.com/intent/like?tweet_id=1715897092244189221'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1715897092244189221'
			button Copy link
			link Read more on Twitter, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
		heading Webinars
		paragraph
			StaticText Learn how to use Flowise from different webinar series with our partners
		image How to Build No-Code SQL Chatbots using Flowise, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fsinglestore_webinar_2.94e511f6.jpeg&w=828&q=75'
		image SingleStore, url='https://flowiseai.com/_next/static/media/singlestore.a5b72cb0.svg'
		StaticText How to Build No-Code SQL Chatbots using Flowise
		link Learn More, url='https://memsql.wistia.com/medias/i1ra0jared'
		image LlamaIndex Webinar: Build No-Code RAG with Flowise, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fllamaindex_webinar.a14452aa.png&w=750&q=75'
		image Milvus, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fllamaindex.5ac46e4e.png&w=48&q=75'
		StaticText LlamaIndex Webinar: Build No-Code RAG with Flowise
		link Learn More, url='https://youtu.be/k5Txq5C_AWA?si=5oqbNBvqP1BEcpVm'
		image How to Build a NoCode AWS Bedrock LLM App on Flowise, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fsinglestore_aws_webinar.185bcd9c.png&w=1080&q=75'
		image SingleStore, url='https://flowiseai.com/_next/static/media/singlestore.a5b72cb0.svg'
		image AWS, url='https://flowiseai.com/_next/static/media/aws.c9a4034b.svg'
		StaticText How to Build a NoCode AWS Bedrock LLM App on Flowise
		link Learn More, url='https://memsql.wistia.com/medias/y230cbhxb0?utm_medium=email&utm_source=singlestore&utm_campaign=7014X0000029ZgFQAU&campaignid=7014X0000029ZgFQAU'
		image Drag and Drop LLMs: Simplifying RAG with FlowiseAI and Milvus, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fmilvus_webinar.0165f039.png&w=828&q=75'
		image Milvus, url='https://flowiseai.com/_next/static/media/milvus.1ae32e3c.svg'
		StaticText Drag and Drop LLMs: Simplifying RAG with FlowiseAI and Milvus
		link Learn More, url='https://youtu.be/OeloMm8SdMc?si=R1sdxako6YM857MT'
		image LangChain Low-Code/No-Code Webinar, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Flangchainwebinar.2f5914b2.png&w=640&q=75'
		image Langchain, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Flangchain.c1e79304.png&w=48&q=75'
		StaticText LangChain Weekly Webinar - Low-Code/No-Code LLM
		link Learn More, url='https://youtu.be/qWv2vyOX0tk?si=-SJM5Z7UvYlOdUhG'
		heading Enterprise
		paragraph
			StaticText Looking for specific use cases and support?
		link Lets Chat, url='mailto:hello@flowiseai.com'
	contentinfo
		list
			listitem
				link Terms of Service, url='https://flowiseai.com/terms'
			listitem
				link Privacy Policy, url='https://flowiseai.com/privacy'
			listitem
				link Twitter, url='https://twitter.com/FlowiseAI'
					image
			listitem
				link Github, url='https://github.com/FlowiseAI/Flowise'
					image
			listitem
				link Linkedin, url='https://www.linkedin.com/company/flowiseai'
					image
		StaticText © FlowiseAI Inc. All rights reserved.
	alert, atomic
```
</details>



```
RootWebArea Flowise - Low code LLM Apps Builder, focused, url='https://flowiseai.com/#features'
	banner
		link Flowise, url='https://flowiseai.com/'
			image Flowise, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Flogo-color-high.e60de2f8.png&w=256&q=75'
		link Star FlowiseAI/Flowise on GitHub, url='https://github.com/FlowiseAI/Flowise'
```
<details><summary>Show more</summary>

```
		link 33609 stargazers on GitHub, url='https://github.com/FlowiseAI/Flowise/stargazers'
			StaticText 33,609
		navigation
			list
				listitem
					link Features, focused, url='https://flowiseai.com/#features'
				listitem
					link Use Cases, url='https://flowiseai.com/#usecases'
				listitem
					link Pricing, url='https://flowiseai.com/#pricing'
				listitem
					link Community, url='https://flowiseai.com/#community'
				listitem
					link Webinars, url='https://flowiseai.com/#webinars'
				listitem
					link Login, url='https://flowiseai.com/auth/login'
						button Login
				listitem
					link Request Access, url='https://flowiseai.com/join'
						button Request Access
							image
	main
		heading Build LLM Apps
		heading Easily
		paragraph
			StaticText Open source low-code tool for developers to build customized LLM orchestration flow & AI agents
		link Request Access, url='https://flowiseai.com/join'
			button Request Access
				image
		link Documentation, url='https://docs.flowiseai.com/'
			button Documentation
		StaticText Backed by
		image YCombinator, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2FYC.dc9b9030.png&w=32&q=75'
		StaticText Combinator
		paragraph
			StaticText Trusted and used by teams around the globe
		image AWS, url='https://flowiseai.com/_next/static/media/aws.c9a4034b.svg'
		image Alibaba, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Falibaba.d717abe3.png&w=128&q=75'
		image Hitachi, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fhitachi.cc8b5524.png&w=64&q=75'
		image ByteDance, url='https://flowiseai.com/_next/static/media/ByteDance.cfa75bfd.svg'
		image Microsoft, url='https://flowiseai.com/_next/static/media/microsoft.0e14c6cf.svg'
		image InsightSoftware, url='https://flowiseai.com/_next/static/media/insightsoftware.c5783e21.svg'
		image Google, url='https://flowiseai.com/_next/static/media/google.c43e43a7.svg'
		image Accenture, url='https://flowiseai.com/_next/static/media/accenture.3222125e.svg'
		image ERoad, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Feroad.ea8bab6e.png&w=64&q=75'
		image AWS, url='https://flowiseai.com/_next/static/media/aws.c9a4034b.svg'
		image Alibaba, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Falibaba.d717abe3.png&w=128&q=75'
		image Hitachi, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fhitachi.cc8b5524.png&w=64&q=75'
		image ByteDance, url='https://flowiseai.com/_next/static/media/ByteDance.cfa75bfd.svg'
		image Microsoft, url='https://flowiseai.com/_next/static/media/microsoft.0e14c6cf.svg'
		image InsightSoftware, url='https://flowiseai.com/_next/static/media/insightsoftware.c5783e21.svg'
		image Google, url='https://flowiseai.com/_next/static/media/google.c43e43a7.svg'
		image Accenture, url='https://flowiseai.com/_next/static/media/accenture.3222125e.svg'
		image ERoad, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Feroad.ea8bab6e.png&w=64&q=75'
		heading Iterate, fast
		paragraph
			StaticText Developing LLM apps takes countless iterations. With low code approach, we enable quick iterations to go from testing to production
		list
			[176] listitem, center=(960,1270), inner_text=$ npm install -g flowise
				StaticText $
				StaticText npm install -g flowise
			[178] listitem, center=(960,1298), inner_text=$ npx flowise start
				StaticText $
				StaticText npx flowise start
		[181] link Get Started, center=(968,1395), url='https://docs.flowiseai.com/getting-started'
		image Features 01, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fintegrations1.8181abd6.png&w=640&q=75'
		StaticText Chatflow
		heading LLM Orchestration
		paragraph
			StaticText Connect LLMs with memory, data loaders, cache, moderation and many more
		list
			[192] listitem, center=(646,1804), inner_text=Langchain
				image
				StaticText Langchain
			[195] listitem, center=(646,1839), inner_text=LlamaIndex
				image
				StaticText LlamaIndex
			[198] listitem, center=(646,1874), inner_text=100+ integrations
				image
				StaticText 100+ integrations
		StaticText Agents
		heading Agents & Assistants
		paragraph
			StaticText Create autonomous agent that can uses tools to execute different tasks
		list
			listitem
				image
				StaticText Custom Tools
			listitem
				image
				StaticText OpenAI Assistant
			listitem
				image
				StaticText Function Agent
		list
			listitem
				StaticText import
				StaticText requests
			listitem
			listitem
				StaticText url
				StaticText =
				StaticText "/api/v1/prediction/:id"
			listitem
			listitem
				StaticText def
				StaticText query
				StaticText (
				StaticText payload
				StaticText )
				StaticText :
			listitem
				StaticText response
				StaticText =
				StaticText requests.post
				StaticText (
			listitem
				StaticText url,
			listitem
				StaticText json
				StaticText =
				StaticText payload
			listitem
				StaticText )
			listitem
				StaticText return
				StaticText response.json
				StaticText (
				StaticText )
			listitem
			listitem
				StaticText output
				StaticText =
				StaticText query
				StaticText (
				StaticText {
			listitem
				StaticText question
				StaticText :
				StaticText "hello!"
			listitem
				StaticText )
				StaticText }
		StaticText Developer Friendly
		heading API, SDK, Embed
		paragraph
			StaticText Extend and integrate to your applications using APIs, SDK and Embedded Chat
		list
			listitem
				image
				StaticText APIs
			listitem
				image
				StaticText Embedded Widget
			listitem
				image
				StaticText React SDK
		image Features 02, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fopensource.bed900d8.png&w=640&q=75'
		StaticText Platform Agnostic
		heading Open source LLMs
		paragraph
			StaticText Run in air-gapped environment with local LLMs, embeddings and vector databases
		list
			listitem
				image
				StaticText HuggingFace, Ollama, LocalAI, Replicate
			listitem
				image
				StaticText Llama2, Mistral, Vicuna, Orca, Llava
			listitem
				image
				StaticText Self host on AWS, Azure, GCP
		heading Use Cases
		paragraph
			StaticText One platform, endless possibilities. See some of the use cases
		button Product Catalog
		button Product Description
		button Query SQL Database
		button Customer Support
		button Structured Data
		paragraph
			StaticText Product catalog chatbot to answer any questions related to the products
		image ProductCatalog, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fproductcatalog.9d6b9124.png&w=1920&q=75'
		heading Pricing
		paragraph
			StaticText Free 14 day trial. No credit card required.
		heading Starter
		paragraph
			StaticText For individuals & small teams
		paragraph
			StaticText $35
			StaticText /month
		list
			listitem
				image
				StaticText 10,000 Predictions / month
				button
					image
				StaticText then $0.001 per prediction
			listitem
				image
				StaticText 1GB Storage
				button
					image
			listitem
				image
				StaticText Database Backup
			listitem
				image
				StaticText 1 Week Log Retention
			listitem
				image
				StaticText Evaluations & Metrics
			listitem
				image
				StaticText Custom Chatbot Branding
				button
					image
			listitem
				image
				StaticText Community Support
		link Start free trial, url='https://flowiseai.com/join'
			button Start free trial
		heading Pro
		paragraph
			StaticText For medium-sized businesses
		paragraph
			StaticText $65
			StaticText /month
		list
			listitem
				image
				StaticText Everything in Starter
			listitem
				image
				StaticText 50,000 Predictions / month
				button
					image
				StaticText then $0.001 per prediction
			listitem
				image
				StaticText 10GB Storage
				button
					image
			listitem
				image
				StaticText Unlimited Workspaces
			listitem
				image
				StaticText Admin Roles & Permissions
			listitem
				image
				StaticText 3 Months Log Retention
			listitem
				image
				StaticText Priority Support
		button Coming Soon, disabled=True
		heading Enterprise
		paragraph
			StaticText For large organizations
		paragraph
			StaticText Contact Us
		list
			listitem
				image
				StaticText On-Premise Deployment
			listitem
				image
				StaticText Air-gapped Environments
			listitem
				image
				StaticText SSO & SAML
			listitem
				image
				StaticText LDAP & RBAC
			listitem
				image
				StaticText Versioning
			listitem
				image
				StaticText Audit Logs
			listitem
				image
				StaticText 99.99% Uptime SLA
		link Contact Us, url='mailto:hello@flowiseai.com'
			button Contact Us
		heading Community 🫶
		paragraph
			StaticText Open source community is the heart of Flowise. See why developers love and build using Flowise
		link Join Discord, url='https://discord.gg/jbaHfsRVBW'
			image
		Iframe
			RootWebArea Flowise AI Tutorial #1 - Introduction & Setup - YouTube, url='https://www.youtube.com/embed/tD6fwQyUIJE?si=na1zK5OISsE4N5Vg'
				[a30] link Photo image of Leon van Zyl, center=(440,5756)
				[a38] link Flowise AI Tutorial #1 - Introduction & Setup, center=(585,5757), url='https://www.youtube.com/watch?v=tD6fwQyUIJE'
				[a68] button More, center=(724,5750), hasPopup='menu'
					image
				[a79] button Play, center=(584,5823)
					image
				generic, atomic
		Iframe
			RootWebArea How to Build an AI Document Chatbot in 10 Minutes - YouTube, url='https://www.youtube.com/embed/riXpu1tHzl0?si=KLVQ9TRUcZCTjXuj'
				[b30] link Photo image of Dave Ebbelaar, center=(816,5756)
				[b38] link How to Build an AI Document Chatbot in 10 Minutes, center=(961,5757), url='https://www.youtube.com/watch?v=riXpu1tHzl0'
				[b68] button More, center=(1100,5750), hasPopup='menu'
					image
				[b79] button Play, center=(960,5823)
					image
				generic, atomic
		Iframe
			RootWebArea Flowise is an open source no-code UI visual tool to build 🦜🔗LangChain applications - YouTube, url='https://www.youtube.com/embed/CovAPtQPU0k?si=KcH3ttNubGtp03Za'
				[c30] link Photo image of Cobus Greyling, center=(1192,5756)
				[c38] link Flowise is an open source no-code UI visual tool to build 🦜🔗LangChain applications, center=(1337,5757), url='https://www.youtube.com/watch?v=CovAPtQPU0k'
				[c68] button More, center=(1476,5750), hasPopup='menu'
					image
				[c79] button Play, center=(1336,5823)
					image
				generic, atomic
		Iframe
			RootWebArea Flowise: No Code ChatBot Building Platform: LangChain - YouTube, url='https://www.youtube.com/embed/Q7_dKkosJY4?si=O0swoActrfHlDFSN'
				[d30] link Photo image of Prompt Engineering, center=(440,5978)
				[d38] link Flowise: No Code ChatBot Building Platform: LangChain, center=(585,5979), url='https://www.youtube.com/watch?v=Q7_dKkosJY4'
				[d68] button More, center=(724,5972), hasPopup='menu'
					image
				[d79] button Play, center=(584,6045)
					image
				generic, atomic
		Iframe
			RootWebArea Build a No-Code Chat-with-PDF LangChain app using Flowise and Bubble - YouTube, url='https://www.youtube.com/embed/kOwmPe8aLAA?si=gBaUlkyFOe3TS2V-'
				[e30] link Photo image of AI with Misbah, center=(816,5978)
				[e38] link Build a No-Code Chat-with-PDF LangChain app using Flowise and Bubble, center=(961,5979), url='https://www.youtube.com/watch?v=kOwmPe8aLAA'
				[e68] button More, center=(1100,5972), hasPopup='menu'
					image
				[e79] button Play, center=(960,6045)
					image
				generic, atomic
		Iframe
			RootWebArea Flowise AI: Create LLM Apps with NO Code - FREE Opensource LangChain Apps - YouTube, url='https://www.youtube.com/embed/kvvBUz0q-6I?si=WtrfQ948R1c2dHpf'
				[f30] link Photo image of WorldofAI, center=(1192,5978)
				[f38] link Flowise AI: Create LLM Apps with NO Code - FREE Opensource LangChain Apps, center=(1337,5979), url='https://www.youtube.com/watch?v=kvvBUz0q-6I'
				[f68] button More, center=(1476,5972), hasPopup='menu'
					image
				[f79] button Play, center=(1336,6045)
					image
				generic, atomic
		article
			link Siddhant Gupta, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
				image Siddhant Gupta, url='https://pbs.twimg.com/profile_images/1761449475883835392/yYkjTFPr_normal.jpg'
			link Siddhant Gupta Verified account, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
				image Verified account
			link @Siddhan65490545, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=Siddhan65490545'
			link View on Twitter, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
			paragraph
				StaticText Finally after a month of relentless trial and error, I've successfully created an AI persona bot emulating the teaching style of my mentor
				link @abnux, url='https://twitter.com/abnux'
				StaticText ,  the founder of
				link @10kdesigners, url='https://twitter.com/10kdesigners'
				StaticText . Excited to share my journey in this twitter thread. 🤖🎨 "Sound on 🎙️🔊"
			button View video on Twitter
			link Watch on Twitter, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
			link 2:43 PM · Oct 10, 2023, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 262 likes, url='https://twitter.com/intent/like?tweet_id=1711754261527458189'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1711754261527458189'
			button Copy link
			link Read 33 replies, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
		article
			link Shubham Saboo, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
				image Shubham Saboo, url='https://pbs.twimg.com/profile_images/1670107849815478273/Q3oUhtHM_normal.jpg'
			link Shubham Saboo Verified account, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
				image Verified account
			link @Saboo_Shubham_, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=Saboo_Shubham_'
			link View on Twitter, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
			paragraph
				StaticText Flowise is trending on GitHub

It's an open-source drag & drop UI tool that lets you build custom LLM apps in just minutes.

Powered by LangChain, it features:
- Ready-to-use app templates
- Conversational agents that remember
- Seamless deployment on cloud platforms
			button View video on Twitter
			link Watch on Twitter, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
			link 4:05 AM · Aug 16, 2023, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 523 likes, url='https://twitter.com/intent/like?tweet_id=1691662432807137623'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1691662432807137623'
			button Copy link
			link Read 18 replies, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
		article
			link Muratcan Koylan, url='https://twitter.com/youraimarketer/status/1710908393265782900'
				image Muratcan Koylan, url='https://pbs.twimg.com/profile_images/1847174349335257088/cGzzFLOo_normal.jpg'
			link Muratcan Koylan Verified account, url='https://twitter.com/youraimarketer/status/1710908393265782900'
				image Verified account
			link @youraimarketer, url='https://twitter.com/youraimarketer/status/1710908393265782900'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=youraimarketer'
			link View on Twitter, url='https://twitter.com/youraimarketer/status/1710908393265782900'
			paragraph
				StaticText When you lose momentum, it's hard to regain it.

But here we go again, building a Personal Cockpit with AI Agents.

I've built a chatbot connected to the internet and various APIs, linking it to multiple workflows and AI agents.

Here's the first demo:

1. AI Newsletter Agent…
			button View video on Twitter
			link Watch on Twitter, url='https://twitter.com/youraimarketer/status/1710908393265782900'
			link 6:42 AM · Oct 8, 2023, url='https://twitter.com/youraimarketer/status/1710908393265782900'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 468 likes, url='https://twitter.com/intent/like?tweet_id=1710908393265782900'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1710908393265782900'
			button Copy link
			link Read 17 replies, url='https://twitter.com/youraimarketer/status/1710908393265782900'
		article
			link Eugene, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
				image Eugene, url='https://pbs.twimg.com/profile_images/1501559855865339914/1FzvS9lb_normal.jpg'
			link Eugene, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
			link @sudo_eugene, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=sudo_eugene'
			link View on Twitter, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
			paragraph
				StaticText Using our new AI bot called Koos with
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText to create project management tasks in Notion, right from Slack 🤯

Let me know who would like to see a 5min explainer on how we did this 🎉
			link Image, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
				image Image, url='https://pbs.twimg.com/media/F6dMWW-WsAAUR7d?format=jpg&name=small'
			link Image, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
				image Image, url='https://pbs.twimg.com/media/F6dMWW_XgAEfotx?format=jpg&name=small'
			link 8:39 AM · Sep 20, 2023, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 16 likes, url='https://twitter.com/intent/like?tweet_id=1704414944551125293'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1704414944551125293'
			button Copy link
			link Read 8 replies, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
		article
			link Lior⚡, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
				image Lior⚡, url='https://pbs.twimg.com/profile_images/1817166841992597504/zLRK5Qx__normal.jpg'
			link Lior⚡ Verified account, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
				image Verified account
			link @LiorOnAI, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=LiorOnAI'
			link View on Twitter, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
			paragraph
				StaticText Flowise just reached 12,000 stars on Github. 

It allows you to build customized LLM apps using a simple drag & drop UI.

You can even use built-in templates with logic and conditions connected to LangChain and GPT:

▸ Conversational agent with memory
▸ Chat with PDF and Excel…
			button View video on Twitter
			link Watch on Twitter, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
			link 4:33 PM · Aug 10, 2023, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 836 likes, url='https://twitter.com/intent/like?tweet_id=1689676278746529793'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1689676278746529793'
			button Copy link
			link Read 30 replies, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
		article
			link Derek Cheung, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
				image Derek Cheung, url='https://pbs.twimg.com/profile_images/1653155172414046209/-_tpBZHC_normal.jpg'
			link Derek Cheung Verified account, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
				image Verified account
			link @derekcheungsa, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=derekcheungsa'
			link View on Twitter, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
			paragraph
				StaticText A multi-modal chatbot that effortlessly merges text and image generation into seamless conversations. 🚀

📢 Watch the demo with conversation starting with asking for advice on building strong financial habits (sped up slightly for demo)
 🪄Chatbot magically generates a visual…
			button View video on Twitter
			link Watch on Twitter, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
			link 3:11 AM · Oct 2, 2023, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 21 likes, url='https://twitter.com/intent/like?tweet_id=1708681200661889447'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1708681200661889447'
			button Copy link
			link Read 4 replies, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
		article
			link armand, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
				image armand, url='https://pbs.twimg.com/profile_images/1758729285744091136/9nZk7KcA_normal.jpg'
			link armand Verified account, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
				image Verified account
			link @armand_ruiz, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=armand_ruiz'
			link View on Twitter, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
			paragraph
				StaticText Create your first custom chatbot using LLMs in 5 min!

No-coding required. We will use
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText Join here to get the step-by-step tutorial and video tomorrow at 7 a.m. ET:
				link nocode.ai, url='https://www.nocode.ai/'
			link Image, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
				image Image, url='https://pbs.twimg.com/media/F4ZG8HwaEAAhSE9?format=jpg&name=small'
			link 5:06 PM · Aug 25, 2023, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 13 likes, url='https://twitter.com/intent/like?tweet_id=1695120505945383161'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1695120505945383161'
			button Copy link
			link Read 3 replies, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
		article
			link Alessio Pomaro, url='https://twitter.com/alepom/status/1694599974716153904'
				image Alessio Pomaro, url='https://pbs.twimg.com/profile_images/1350189157931479041/LaWfQ0IQ_normal.jpg'
			link Alessio Pomaro, url='https://twitter.com/alepom/status/1694599974716153904'
			link @alepom, url='https://twitter.com/alepom/status/1694599974716153904'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=alepom'
			link View on Twitter, url='https://twitter.com/alepom/status/1694599974716153904'
			paragraph
				StaticText 🧠 Realizzare un
				link #chatbot, url='https://twitter.com/hashtag/chatbot'
				StaticText o una ricerca evoluta per un sito web: quanto sarebbe stato complesso un paio d'anni fa? Tanto. Pochi servizi erano davvero efficienti. 
🦾 Nelle immagini si vede un'esempio di come l'ho creato con
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText .
				link #AI, url='https://twitter.com/hashtag/AI'
				link #Flowise, url='https://twitter.com/hashtag/Flowise'
				link #LLaMA2, url='https://twitter.com/hashtag/LLaMA2'
				link #Claude, url='https://twitter.com/hashtag/Claude'
			link Image, url='https://twitter.com/alepom/status/1694599974716153904'
				image Image, url='https://pbs.twimg.com/media/F4RtrXGWQAAdnSg?format=jpg&name=small'
			link Image, url='https://twitter.com/alepom/status/1694599974716153904'
				image Image, url='https://pbs.twimg.com/media/F4RtrygWUAAFCua?format=jpg&name=small'
			link Image, url='https://twitter.com/alepom/status/1694599974716153904'
				image Image, url='https://pbs.twimg.com/media/F4RtsJjXIAAJOhx?format=jpg&name=small'
			link Image, url='https://twitter.com/alepom/status/1694599974716153904'
				image Image, url='https://pbs.twimg.com/media/F4RtscNXgAAMGhu?format=png&name=small'
			link 6:38 AM · Aug 24, 2023, url='https://twitter.com/alepom/status/1694599974716153904'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 7 likes, url='https://twitter.com/intent/like?tweet_id=1694599974716153904'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1694599974716153904'
			button Copy link
			link Read 2 replies, url='https://twitter.com/alepom/status/1694599974716153904'
		article
			link John Damask, url='https://twitter.com/jbdamask/status/1693777249009373584'
				image John Damask, url='https://pbs.twimg.com/profile_images/1688209206204121093/9iNcGQoo_normal.jpg'
			link John Damask Verified account, url='https://twitter.com/jbdamask/status/1693777249009373584'
				image Verified account
			link @jbdamask, url='https://twitter.com/jbdamask/status/1693777249009373584'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=jbdamask'
			link View on Twitter, url='https://twitter.com/jbdamask/status/1693777249009373584'
			paragraph
				StaticText Flowise is seriously impressive. Not only for quickly building and deploying LLM apps, but for visualizing chains
			link 12:08 AM · Aug 22, 2023, url='https://twitter.com/jbdamask/status/1693777249009373584'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 9 likes, url='https://twitter.com/intent/like?tweet_id=1693777249009373584'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1693777249009373584'
			button Copy link
			link Read 3 replies, url='https://twitter.com/jbdamask/status/1693777249009373584'
		article
			link Abu Mu'aaz, url='https://twitter.com/abumuaaz/status/1693448039594381481'
				image Abu Mu'aaz, url='https://pbs.twimg.com/profile_images/1396343945190285314/brEgb4B9_normal.jpg'
			link Abu Mu'aaz, url='https://twitter.com/abumuaaz/status/1693448039594381481'
			link @abumuaaz, url='https://twitter.com/abumuaaz/status/1693448039594381481'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=abumuaaz'
			link View on Twitter, url='https://twitter.com/abumuaaz/status/1693448039594381481'
			paragraph
				StaticText Thanks to
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText &
				link @LangChainAI, url='https://twitter.com/LangChainAI'
				StaticText , it's so easy to create Telegram Bot that capable of getting real-time bus info (location & speed) from GPS device. Plus more functionality to calculate distance, duration & presenting map to user.
				link @OpenAI, url='https://twitter.com/OpenAI'
				StaticText Function Calling is awesome too 👍
			link Image, url='https://twitter.com/abumuaaz/status/1693448039594381481'
				image Image, url='https://pbs.twimg.com/media/F4BToWubcAANu1L?format=jpg&name=small'
			link Image, url='https://twitter.com/abumuaaz/status/1693448039594381481'
				image Image, url='https://pbs.twimg.com/media/F4BTptvbgAIc_hK?format=jpg&name=small'
			link 2:20 AM · Aug 21, 2023, url='https://twitter.com/abumuaaz/status/1693448039594381481'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 16 likes, url='https://twitter.com/intent/like?tweet_id=1693448039594381481'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1693448039594381481'
			button Copy link
			link Read 3 replies, url='https://twitter.com/abumuaaz/status/1693448039594381481'
		article
			link Wayne Culbreth, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
				image Wayne Culbreth, url='https://pbs.twimg.com/profile_images/1622684462587777037/_SDI7qtQ_normal.png'
			link Wayne Culbreth Verified account, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
				image Verified account
			link @wayne_culbreth, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=wayne_culbreth'
			link View on Twitter, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
			paragraph
				StaticText If you are building in AI and not using
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText - you are seriously wasting your time. It's like Figma but for backend AI applications. Design & test your entire stack in less than an hour. Even test MVP. Build to industrial scale with the exported output.
			link 6:56 PM · Aug 19, 2023, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 11 likes, url='https://twitter.com/intent/like?tweet_id=1692973803188392402'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1692973803188392402'
			button Copy link
			link Read 2 replies, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
		article
			link Damian Soto, url='https://twitter.com/sotoplatero/status/1692286497850855494'
				image Damian Soto, url='https://pbs.twimg.com/profile_images/1872860928502349824/HItLB9zt_normal.jpg'
			link Damian Soto, url='https://twitter.com/sotoplatero/status/1692286497850855494'
			link @sotoplatero, url='https://twitter.com/sotoplatero/status/1692286497850855494'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=sotoplatero'
			link View on Twitter, url='https://twitter.com/sotoplatero/status/1692286497850855494'
			paragraph
				StaticText Chatea Gratis con tus PDF sin código !!!

En este hilo te muestro como crear un chat gpt personalizado sin una linea de código que puedes incluir en tu web

Usamos
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText que es una increíble herramienta para crear aplicaciones LLM con
				link #nocode, url='https://twitter.com/hashtag/nocode'
				StaticText .

Empezamos🧵
			link Image, url='https://twitter.com/sotoplatero/status/1692286497850855494'
				image Image, url='https://pbs.twimg.com/media/F3w1mbEWUAQPpmL?format=jpg&name=small'
			link 9:25 PM · Aug 17, 2023, url='https://twitter.com/sotoplatero/status/1692286497850855494'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 22 likes, url='https://twitter.com/intent/like?tweet_id=1692286497850855494'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1692286497850855494'
			button Copy link
			link Read 2 replies, url='https://twitter.com/sotoplatero/status/1692286497850855494'
		article
			link VerySmallWoods, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
				image VerySmallWoods, url='https://pbs.twimg.com/profile_images/1600964189731934222/eWMb0-L2_normal.jpg'
			link VerySmallWoods Verified account, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
				image Verified account
			link @verysmallwoods, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=verysmallwoods'
			link View on Twitter, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
			paragraph
				StaticText AutoGen = LLM多代理框架 👨‍👩‍👧‍👦
Flowise = 无代码LLM工作流构建平台 0️⃣

由
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText 负责构建功能单元；由AutoGen负责调度协作，任务执行。

嗯！有点美妙！
🎏 🎀 🪄 🪅 🎊 🎉

AutoGen + Flowise = 零代码平台上的超级AI助理 

视频 👇
				link youtu.be/gKNR1ghU1Ao?si…, url='https://youtu.be/gKNR1ghU1Ao?si=ZI9jqz3ss51NG8HX'
				link #AutoGen, url='https://twitter.com/hashtag/AutoGen'
				link #Flowise, url='https://twitter.com/hashtag/Flowise'
				link #OpenAI, url='https://twitter.com/hashtag/OpenAI'
				StaticText …
			link 1:05 AM · Oct 22, 2023, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 11 likes, url='https://twitter.com/intent/like?tweet_id=1715897092244189221'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1715897092244189221'
			button Copy link
			link Read more on Twitter, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
		heading Webinars
		paragraph
			StaticText Learn how to use Flowise from different webinar series with our partners
		image How to Build No-Code SQL Chatbots using Flowise, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fsinglestore_webinar_2.94e511f6.jpeg&w=828&q=75'
		image SingleStore, url='https://flowiseai.com/_next/static/media/singlestore.a5b72cb0.svg'
		StaticText How to Build No-Code SQL Chatbots using Flowise
		link Learn More, url='https://memsql.wistia.com/medias/i1ra0jared'
		image LlamaIndex Webinar: Build No-Code RAG with Flowise, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fllamaindex_webinar.a14452aa.png&w=750&q=75'
		image Milvus, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fllamaindex.5ac46e4e.png&w=48&q=75'
		StaticText LlamaIndex Webinar: Build No-Code RAG with Flowise
		link Learn More, url='https://youtu.be/k5Txq5C_AWA?si=5oqbNBvqP1BEcpVm'
		image How to Build a NoCode AWS Bedrock LLM App on Flowise, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fsinglestore_aws_webinar.185bcd9c.png&w=1080&q=75'
		image SingleStore, url='https://flowiseai.com/_next/static/media/singlestore.a5b72cb0.svg'
		image AWS, url='https://flowiseai.com/_next/static/media/aws.c9a4034b.svg'
		StaticText How to Build a NoCode AWS Bedrock LLM App on Flowise
		link Learn More, url='https://memsql.wistia.com/medias/y230cbhxb0?utm_medium=email&utm_source=singlestore&utm_campaign=7014X0000029ZgFQAU&campaignid=7014X0000029ZgFQAU'
		image Drag and Drop LLMs: Simplifying RAG with FlowiseAI and Milvus, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fmilvus_webinar.0165f039.png&w=828&q=75'
		image Milvus, url='https://flowiseai.com/_next/static/media/milvus.1ae32e3c.svg'
		StaticText Drag and Drop LLMs: Simplifying RAG with FlowiseAI and Milvus
		link Learn More, url='https://youtu.be/OeloMm8SdMc?si=R1sdxako6YM857MT'
		image LangChain Low-Code/No-Code Webinar, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Flangchainwebinar.2f5914b2.png&w=640&q=75'
		image Langchain, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Flangchain.c1e79304.png&w=48&q=75'
		StaticText LangChain Weekly Webinar - Low-Code/No-Code LLM
		link Learn More, url='https://youtu.be/qWv2vyOX0tk?si=-SJM5Z7UvYlOdUhG'
		heading Enterprise
		paragraph
			StaticText Looking for specific use cases and support?
		link Lets Chat, url='mailto:hello@flowiseai.com'
	contentinfo
		list
			listitem
				link Terms of Service, url='https://flowiseai.com/terms'
			listitem
				link Privacy Policy, url='https://flowiseai.com/privacy'
			listitem
				link Twitter, url='https://twitter.com/FlowiseAI'
					image
			listitem
				link Github, url='https://github.com/FlowiseAI/Flowise'
					image
			listitem
				link Linkedin, url='https://www.linkedin.com/company/flowiseai'
					image
		StaticText © FlowiseAI Inc. All rights reserved.
	alert, atomic
```
</details>

**Reasoning for action:** By clicking on the 'Features' link (identified by the index 59), I am taking the first step to fulfill the user's goal of exploring the features and practical applications of Flowise. This action will redirect me to a page specifically designed to inform potential customers about the various functionalities of Flowise, which is essential for understanding how it can help them build customized LLM (Large Language Model) applications.

**Action:** click(59) # Click on the Features link to explore the features of Flowise.

**Change Description:** After clicking on the 'Features' link, the URL updated to include a fragment identifier '#features', and the 'Features' link is now marked as focused, indicating that the user is currently on that section of the site. No other significant changes were noted in the browser state.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://flowiseai.com/#features

https://flowiseai.com/#usecases

**Content (before/after):** 

```
RootWebArea Flowise - Low code LLM Apps Builder, focused, url='https://flowiseai.com/#features'
	banner
		link Flowise, url='https://flowiseai.com/'
			image Flowise, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Flogo-color-high.e60de2f8.png&w=256&q=75'
		link Star FlowiseAI/Flowise on GitHub, url='https://github.com/FlowiseAI/Flowise'
```
<details><summary>Show more</summary>

```
		link 33609 stargazers on GitHub, url='https://github.com/FlowiseAI/Flowise/stargazers'
			StaticText 33,609
		navigation
			list
				listitem
					link Features, focused, url='https://flowiseai.com/#features'
				listitem
					link Use Cases, url='https://flowiseai.com/#usecases'
				listitem
					link Pricing, url='https://flowiseai.com/#pricing'
				listitem
					link Community, url='https://flowiseai.com/#community'
				listitem
					link Webinars, url='https://flowiseai.com/#webinars'
				listitem
					link Login, url='https://flowiseai.com/auth/login'
						button Login
				listitem
					link Request Access, url='https://flowiseai.com/join'
						button Request Access
							image
	main
		heading Build LLM Apps
		heading Easily
		paragraph
			StaticText Open source low-code tool for developers to build customized LLM orchestration flow & AI agents
		link Request Access, url='https://flowiseai.com/join'
			button Request Access
				image
		link Documentation, url='https://docs.flowiseai.com/'
			button Documentation
		StaticText Backed by
		image YCombinator, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2FYC.dc9b9030.png&w=32&q=75'
		StaticText Combinator
		paragraph
			StaticText Trusted and used by teams around the globe
		image AWS, url='https://flowiseai.com/_next/static/media/aws.c9a4034b.svg'
		image Alibaba, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Falibaba.d717abe3.png&w=128&q=75'
		image Hitachi, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fhitachi.cc8b5524.png&w=64&q=75'
		image ByteDance, url='https://flowiseai.com/_next/static/media/ByteDance.cfa75bfd.svg'
		image Microsoft, url='https://flowiseai.com/_next/static/media/microsoft.0e14c6cf.svg'
		image InsightSoftware, url='https://flowiseai.com/_next/static/media/insightsoftware.c5783e21.svg'
		image Google, url='https://flowiseai.com/_next/static/media/google.c43e43a7.svg'
		image Accenture, url='https://flowiseai.com/_next/static/media/accenture.3222125e.svg'
		image ERoad, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Feroad.ea8bab6e.png&w=64&q=75'
		image AWS, url='https://flowiseai.com/_next/static/media/aws.c9a4034b.svg'
		image Alibaba, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Falibaba.d717abe3.png&w=128&q=75'
		image Hitachi, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fhitachi.cc8b5524.png&w=64&q=75'
		image ByteDance, url='https://flowiseai.com/_next/static/media/ByteDance.cfa75bfd.svg'
		image Microsoft, url='https://flowiseai.com/_next/static/media/microsoft.0e14c6cf.svg'
		image InsightSoftware, url='https://flowiseai.com/_next/static/media/insightsoftware.c5783e21.svg'
		image Google, url='https://flowiseai.com/_next/static/media/google.c43e43a7.svg'
		image Accenture, url='https://flowiseai.com/_next/static/media/accenture.3222125e.svg'
		image ERoad, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Feroad.ea8bab6e.png&w=64&q=75'
		heading Iterate, fast
		paragraph
			StaticText Developing LLM apps takes countless iterations. With low code approach, we enable quick iterations to go from testing to production
		list
			[176] listitem, center=(960,1270), inner_text=$ npm install -g flowise
				StaticText $
				StaticText npm install -g flowise
			[178] listitem, center=(960,1298), inner_text=$ npx flowise start
				StaticText $
				StaticText npx flowise start
		[181] link Get Started, center=(968,1395), url='https://docs.flowiseai.com/getting-started'
		image Features 01, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fintegrations1.8181abd6.png&w=640&q=75'
		StaticText Chatflow
		heading LLM Orchestration
		paragraph
			StaticText Connect LLMs with memory, data loaders, cache, moderation and many more
		list
			[192] listitem, center=(646,1804), inner_text=Langchain
				image
				StaticText Langchain
			[195] listitem, center=(646,1839), inner_text=LlamaIndex
				image
				StaticText LlamaIndex
			[198] listitem, center=(646,1874), inner_text=100+ integrations
				image
				StaticText 100+ integrations
		StaticText Agents
		heading Agents & Assistants
		paragraph
			StaticText Create autonomous agent that can uses tools to execute different tasks
		list
			listitem
				image
				StaticText Custom Tools
			listitem
				image
				StaticText OpenAI Assistant
			listitem
				image
				StaticText Function Agent
		list
			listitem
				StaticText import
				StaticText requests
			listitem
			listitem
				StaticText url
				StaticText =
				StaticText "/api/v1/prediction/:id"
			listitem
			listitem
				StaticText def
				StaticText query
				StaticText (
				StaticText payload
				StaticText )
				StaticText :
			listitem
				StaticText response
				StaticText =
				StaticText requests.post
				StaticText (
			listitem
				StaticText url,
			listitem
				StaticText json
				StaticText =
				StaticText payload
			listitem
				StaticText )
			listitem
				StaticText return
				StaticText response.json
				StaticText (
				StaticText )
			listitem
			listitem
				StaticText output
				StaticText =
				StaticText query
				StaticText (
				StaticText {
			listitem
				StaticText question
				StaticText :
				StaticText "hello!"
			listitem
				StaticText )
				StaticText }
		StaticText Developer Friendly
		heading API, SDK, Embed
		paragraph
			StaticText Extend and integrate to your applications using APIs, SDK and Embedded Chat
		list
			listitem
				image
				StaticText APIs
			listitem
				image
				StaticText Embedded Widget
			listitem
				image
				StaticText React SDK
		image Features 02, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fopensource.bed900d8.png&w=640&q=75'
		StaticText Platform Agnostic
		heading Open source LLMs
		paragraph
			StaticText Run in air-gapped environment with local LLMs, embeddings and vector databases
		list
			listitem
				image
				StaticText HuggingFace, Ollama, LocalAI, Replicate
			listitem
				image
				StaticText Llama2, Mistral, Vicuna, Orca, Llava
			listitem
				image
				StaticText Self host on AWS, Azure, GCP
		heading Use Cases
		paragraph
			StaticText One platform, endless possibilities. See some of the use cases
		button Product Catalog
		button Product Description
		button Query SQL Database
		button Customer Support
		button Structured Data
		paragraph
			StaticText Product catalog chatbot to answer any questions related to the products
		image ProductCatalog, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fproductcatalog.9d6b9124.png&w=1920&q=75'
		heading Pricing
		paragraph
			StaticText Free 14 day trial. No credit card required.
		heading Starter
		paragraph
			StaticText For individuals & small teams
		paragraph
			StaticText $35
			StaticText /month
		list
			listitem
				image
				StaticText 10,000 Predictions / month
				button
					image
				StaticText then $0.001 per prediction
			listitem
				image
				StaticText 1GB Storage
				button
					image
			listitem
				image
				StaticText Database Backup
			listitem
				image
				StaticText 1 Week Log Retention
			listitem
				image
				StaticText Evaluations & Metrics
			listitem
				image
				StaticText Custom Chatbot Branding
				button
					image
			listitem
				image
				StaticText Community Support
		link Start free trial, url='https://flowiseai.com/join'
			button Start free trial
		heading Pro
		paragraph
			StaticText For medium-sized businesses
		paragraph
			StaticText $65
			StaticText /month
		list
			listitem
				image
				StaticText Everything in Starter
			listitem
				image
				StaticText 50,000 Predictions / month
				button
					image
				StaticText then $0.001 per prediction
			listitem
				image
				StaticText 10GB Storage
				button
					image
			listitem
				image
				StaticText Unlimited Workspaces
			listitem
				image
				StaticText Admin Roles & Permissions
			listitem
				image
				StaticText 3 Months Log Retention
			listitem
				image
				StaticText Priority Support
		button Coming Soon, disabled=True
		heading Enterprise
		paragraph
			StaticText For large organizations
		paragraph
			StaticText Contact Us
		list
			listitem
				image
				StaticText On-Premise Deployment
			listitem
				image
				StaticText Air-gapped Environments
			listitem
				image
				StaticText SSO & SAML
			listitem
				image
				StaticText LDAP & RBAC
			listitem
				image
				StaticText Versioning
			listitem
				image
				StaticText Audit Logs
			listitem
				image
				StaticText 99.99% Uptime SLA
		link Contact Us, url='mailto:hello@flowiseai.com'
			button Contact Us
		heading Community 🫶
		paragraph
			StaticText Open source community is the heart of Flowise. See why developers love and build using Flowise
		link Join Discord, url='https://discord.gg/jbaHfsRVBW'
			image
		Iframe
			RootWebArea Flowise AI Tutorial #1 - Introduction & Setup - YouTube, url='https://www.youtube.com/embed/tD6fwQyUIJE?si=na1zK5OISsE4N5Vg'
				[a30] link Photo image of Leon van Zyl, center=(440,5756)
				[a38] link Flowise AI Tutorial #1 - Introduction & Setup, center=(585,5757), url='https://www.youtube.com/watch?v=tD6fwQyUIJE'
				[a68] button More, center=(724,5750), hasPopup='menu'
					image
				[a79] button Play, center=(584,5823)
					image
				generic, atomic
		Iframe
			RootWebArea How to Build an AI Document Chatbot in 10 Minutes - YouTube, url='https://www.youtube.com/embed/riXpu1tHzl0?si=KLVQ9TRUcZCTjXuj'
				[b30] link Photo image of Dave Ebbelaar, center=(816,5756)
				[b38] link How to Build an AI Document Chatbot in 10 Minutes, center=(961,5757), url='https://www.youtube.com/watch?v=riXpu1tHzl0'
				[b68] button More, center=(1100,5750), hasPopup='menu'
					image
				[b79] button Play, center=(960,5823)
					image
				generic, atomic
		Iframe
			RootWebArea Flowise is an open source no-code UI visual tool to build 🦜🔗LangChain applications - YouTube, url='https://www.youtube.com/embed/CovAPtQPU0k?si=KcH3ttNubGtp03Za'
				[c30] link Photo image of Cobus Greyling, center=(1192,5756)
				[c38] link Flowise is an open source no-code UI visual tool to build 🦜🔗LangChain applications, center=(1337,5757), url='https://www.youtube.com/watch?v=CovAPtQPU0k'
				[c68] button More, center=(1476,5750), hasPopup='menu'
					image
				[c79] button Play, center=(1336,5823)
					image
				generic, atomic
		Iframe
			RootWebArea Flowise: No Code ChatBot Building Platform: LangChain - YouTube, url='https://www.youtube.com/embed/Q7_dKkosJY4?si=O0swoActrfHlDFSN'
				[d30] link Photo image of Prompt Engineering, center=(440,5978)
				[d38] link Flowise: No Code ChatBot Building Platform: LangChain, center=(585,5979), url='https://www.youtube.com/watch?v=Q7_dKkosJY4'
				[d68] button More, center=(724,5972), hasPopup='menu'
					image
				[d79] button Play, center=(584,6045)
					image
				generic, atomic
		Iframe
			RootWebArea Build a No-Code Chat-with-PDF LangChain app using Flowise and Bubble - YouTube, url='https://www.youtube.com/embed/kOwmPe8aLAA?si=gBaUlkyFOe3TS2V-'
				[e30] link Photo image of AI with Misbah, center=(816,5978)
				[e38] link Build a No-Code Chat-with-PDF LangChain app using Flowise and Bubble, center=(961,5979), url='https://www.youtube.com/watch?v=kOwmPe8aLAA'
				[e68] button More, center=(1100,5972), hasPopup='menu'
					image
				[e79] button Play, center=(960,6045)
					image
				generic, atomic
		Iframe
			RootWebArea Flowise AI: Create LLM Apps with NO Code - FREE Opensource LangChain Apps - YouTube, url='https://www.youtube.com/embed/kvvBUz0q-6I?si=WtrfQ948R1c2dHpf'
				[f30] link Photo image of WorldofAI, center=(1192,5978)
				[f38] link Flowise AI: Create LLM Apps with NO Code - FREE Opensource LangChain Apps, center=(1337,5979), url='https://www.youtube.com/watch?v=kvvBUz0q-6I'
				[f68] button More, center=(1476,5972), hasPopup='menu'
					image
				[f79] button Play, center=(1336,6045)
					image
				generic, atomic
		article
			link Siddhant Gupta, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
				image Siddhant Gupta, url='https://pbs.twimg.com/profile_images/1761449475883835392/yYkjTFPr_normal.jpg'
			link Siddhant Gupta Verified account, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
				image Verified account
			link @Siddhan65490545, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=Siddhan65490545'
			link View on Twitter, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
			paragraph
				StaticText Finally after a month of relentless trial and error, I've successfully created an AI persona bot emulating the teaching style of my mentor
				link @abnux, url='https://twitter.com/abnux'
				StaticText ,  the founder of
				link @10kdesigners, url='https://twitter.com/10kdesigners'
				StaticText . Excited to share my journey in this twitter thread. 🤖🎨 "Sound on 🎙️🔊"
			button View video on Twitter
			link Watch on Twitter, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
			link 2:43 PM · Oct 10, 2023, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 262 likes, url='https://twitter.com/intent/like?tweet_id=1711754261527458189'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1711754261527458189'
			button Copy link
			link Read 33 replies, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
		article
			link Shubham Saboo, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
				image Shubham Saboo, url='https://pbs.twimg.com/profile_images/1670107849815478273/Q3oUhtHM_normal.jpg'
			link Shubham Saboo Verified account, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
				image Verified account
			link @Saboo_Shubham_, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=Saboo_Shubham_'
			link View on Twitter, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
			paragraph
				StaticText Flowise is trending on GitHub

It's an open-source drag & drop UI tool that lets you build custom LLM apps in just minutes.

Powered by LangChain, it features:
- Ready-to-use app templates
- Conversational agents that remember
- Seamless deployment on cloud platforms
			button View video on Twitter
			link Watch on Twitter, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
			link 4:05 AM · Aug 16, 2023, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 523 likes, url='https://twitter.com/intent/like?tweet_id=1691662432807137623'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1691662432807137623'
			button Copy link
			link Read 18 replies, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
		article
			link Muratcan Koylan, url='https://twitter.com/youraimarketer/status/1710908393265782900'
				image Muratcan Koylan, url='https://pbs.twimg.com/profile_images/1847174349335257088/cGzzFLOo_normal.jpg'
			link Muratcan Koylan Verified account, url='https://twitter.com/youraimarketer/status/1710908393265782900'
				image Verified account
			link @youraimarketer, url='https://twitter.com/youraimarketer/status/1710908393265782900'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=youraimarketer'
			link View on Twitter, url='https://twitter.com/youraimarketer/status/1710908393265782900'
			paragraph
				StaticText When you lose momentum, it's hard to regain it.

But here we go again, building a Personal Cockpit with AI Agents.

I've built a chatbot connected to the internet and various APIs, linking it to multiple workflows and AI agents.

Here's the first demo:

1. AI Newsletter Agent…
			button View video on Twitter
			link Watch on Twitter, url='https://twitter.com/youraimarketer/status/1710908393265782900'
			link 6:42 AM · Oct 8, 2023, url='https://twitter.com/youraimarketer/status/1710908393265782900'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 468 likes, url='https://twitter.com/intent/like?tweet_id=1710908393265782900'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1710908393265782900'
			button Copy link
			link Read 17 replies, url='https://twitter.com/youraimarketer/status/1710908393265782900'
		article
			link Eugene, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
				image Eugene, url='https://pbs.twimg.com/profile_images/1501559855865339914/1FzvS9lb_normal.jpg'
			link Eugene, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
			link @sudo_eugene, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=sudo_eugene'
			link View on Twitter, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
			paragraph
				StaticText Using our new AI bot called Koos with
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText to create project management tasks in Notion, right from Slack 🤯

Let me know who would like to see a 5min explainer on how we did this 🎉
			link Image, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
				image Image, url='https://pbs.twimg.com/media/F6dMWW-WsAAUR7d?format=jpg&name=small'
			link Image, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
				image Image, url='https://pbs.twimg.com/media/F6dMWW_XgAEfotx?format=jpg&name=small'
			link 8:39 AM · Sep 20, 2023, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 16 likes, url='https://twitter.com/intent/like?tweet_id=1704414944551125293'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1704414944551125293'
			button Copy link
			link Read 8 replies, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
		article
			link Lior⚡, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
				image Lior⚡, url='https://pbs.twimg.com/profile_images/1817166841992597504/zLRK5Qx__normal.jpg'
			link Lior⚡ Verified account, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
				image Verified account
			link @LiorOnAI, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=LiorOnAI'
			link View on Twitter, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
			paragraph
				StaticText Flowise just reached 12,000 stars on Github. 

It allows you to build customized LLM apps using a simple drag & drop UI.

You can even use built-in templates with logic and conditions connected to LangChain and GPT:

▸ Conversational agent with memory
▸ Chat with PDF and Excel…
			button View video on Twitter
			link Watch on Twitter, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
			link 4:33 PM · Aug 10, 2023, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 836 likes, url='https://twitter.com/intent/like?tweet_id=1689676278746529793'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1689676278746529793'
			button Copy link
			link Read 30 replies, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
		article
			link Derek Cheung, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
				image Derek Cheung, url='https://pbs.twimg.com/profile_images/1653155172414046209/-_tpBZHC_normal.jpg'
			link Derek Cheung Verified account, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
				image Verified account
			link @derekcheungsa, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=derekcheungsa'
			link View on Twitter, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
			paragraph
				StaticText A multi-modal chatbot that effortlessly merges text and image generation into seamless conversations. 🚀

📢 Watch the demo with conversation starting with asking for advice on building strong financial habits (sped up slightly for demo)
 🪄Chatbot magically generates a visual…
			button View video on Twitter
			link Watch on Twitter, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
			link 3:11 AM · Oct 2, 2023, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 21 likes, url='https://twitter.com/intent/like?tweet_id=1708681200661889447'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1708681200661889447'
			button Copy link
			link Read 4 replies, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
		article
			link armand, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
				image armand, url='https://pbs.twimg.com/profile_images/1758729285744091136/9nZk7KcA_normal.jpg'
			link armand Verified account, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
				image Verified account
			link @armand_ruiz, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=armand_ruiz'
			link View on Twitter, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
			paragraph
				StaticText Create your first custom chatbot using LLMs in 5 min!

No-coding required. We will use
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText Join here to get the step-by-step tutorial and video tomorrow at 7 a.m. ET:
				link nocode.ai, url='https://www.nocode.ai/'
			link Image, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
				image Image, url='https://pbs.twimg.com/media/F4ZG8HwaEAAhSE9?format=jpg&name=small'
			link 5:06 PM · Aug 25, 2023, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 13 likes, url='https://twitter.com/intent/like?tweet_id=1695120505945383161'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1695120505945383161'
			button Copy link
			link Read 3 replies, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
		article
			link Alessio Pomaro, url='https://twitter.com/alepom/status/1694599974716153904'
				image Alessio Pomaro, url='https://pbs.twimg.com/profile_images/1350189157931479041/LaWfQ0IQ_normal.jpg'
			link Alessio Pomaro, url='https://twitter.com/alepom/status/1694599974716153904'
			link @alepom, url='https://twitter.com/alepom/status/1694599974716153904'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=alepom'
			link View on Twitter, url='https://twitter.com/alepom/status/1694599974716153904'
			paragraph
				StaticText 🧠 Realizzare un
				link #chatbot, url='https://twitter.com/hashtag/chatbot'
				StaticText o una ricerca evoluta per un sito web: quanto sarebbe stato complesso un paio d'anni fa? Tanto. Pochi servizi erano davvero efficienti. 
🦾 Nelle immagini si vede un'esempio di come l'ho creato con
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText .
				link #AI, url='https://twitter.com/hashtag/AI'
				link #Flowise, url='https://twitter.com/hashtag/Flowise'
				link #LLaMA2, url='https://twitter.com/hashtag/LLaMA2'
				link #Claude, url='https://twitter.com/hashtag/Claude'
			link Image, url='https://twitter.com/alepom/status/1694599974716153904'
				image Image, url='https://pbs.twimg.com/media/F4RtrXGWQAAdnSg?format=jpg&name=small'
			link Image, url='https://twitter.com/alepom/status/1694599974716153904'
				image Image, url='https://pbs.twimg.com/media/F4RtrygWUAAFCua?format=jpg&name=small'
			link Image, url='https://twitter.com/alepom/status/1694599974716153904'
				image Image, url='https://pbs.twimg.com/media/F4RtsJjXIAAJOhx?format=jpg&name=small'
			link Image, url='https://twitter.com/alepom/status/1694599974716153904'
				image Image, url='https://pbs.twimg.com/media/F4RtscNXgAAMGhu?format=png&name=small'
			link 6:38 AM · Aug 24, 2023, url='https://twitter.com/alepom/status/1694599974716153904'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 7 likes, url='https://twitter.com/intent/like?tweet_id=1694599974716153904'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1694599974716153904'
			button Copy link
			link Read 2 replies, url='https://twitter.com/alepom/status/1694599974716153904'
		article
			link John Damask, url='https://twitter.com/jbdamask/status/1693777249009373584'
				image John Damask, url='https://pbs.twimg.com/profile_images/1688209206204121093/9iNcGQoo_normal.jpg'
			link John Damask Verified account, url='https://twitter.com/jbdamask/status/1693777249009373584'
				image Verified account
			link @jbdamask, url='https://twitter.com/jbdamask/status/1693777249009373584'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=jbdamask'
			link View on Twitter, url='https://twitter.com/jbdamask/status/1693777249009373584'
			paragraph
				StaticText Flowise is seriously impressive. Not only for quickly building and deploying LLM apps, but for visualizing chains
			link 12:08 AM · Aug 22, 2023, url='https://twitter.com/jbdamask/status/1693777249009373584'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 9 likes, url='https://twitter.com/intent/like?tweet_id=1693777249009373584'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1693777249009373584'
			button Copy link
			link Read 3 replies, url='https://twitter.com/jbdamask/status/1693777249009373584'
		article
			link Abu Mu'aaz, url='https://twitter.com/abumuaaz/status/1693448039594381481'
				image Abu Mu'aaz, url='https://pbs.twimg.com/profile_images/1396343945190285314/brEgb4B9_normal.jpg'
			link Abu Mu'aaz, url='https://twitter.com/abumuaaz/status/1693448039594381481'
			link @abumuaaz, url='https://twitter.com/abumuaaz/status/1693448039594381481'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=abumuaaz'
			link View on Twitter, url='https://twitter.com/abumuaaz/status/1693448039594381481'
			paragraph
				StaticText Thanks to
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText &
				link @LangChainAI, url='https://twitter.com/LangChainAI'
				StaticText , it's so easy to create Telegram Bot that capable of getting real-time bus info (location & speed) from GPS device. Plus more functionality to calculate distance, duration & presenting map to user.
				link @OpenAI, url='https://twitter.com/OpenAI'
				StaticText Function Calling is awesome too 👍
			link Image, url='https://twitter.com/abumuaaz/status/1693448039594381481'
				image Image, url='https://pbs.twimg.com/media/F4BToWubcAANu1L?format=jpg&name=small'
			link Image, url='https://twitter.com/abumuaaz/status/1693448039594381481'
				image Image, url='https://pbs.twimg.com/media/F4BTptvbgAIc_hK?format=jpg&name=small'
			link 2:20 AM · Aug 21, 2023, url='https://twitter.com/abumuaaz/status/1693448039594381481'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 16 likes, url='https://twitter.com/intent/like?tweet_id=1693448039594381481'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1693448039594381481'
			button Copy link
			link Read 3 replies, url='https://twitter.com/abumuaaz/status/1693448039594381481'
		article
			link Wayne Culbreth, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
				image Wayne Culbreth, url='https://pbs.twimg.com/profile_images/1622684462587777037/_SDI7qtQ_normal.png'
			link Wayne Culbreth Verified account, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
				image Verified account
			link @wayne_culbreth, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=wayne_culbreth'
			link View on Twitter, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
			paragraph
				StaticText If you are building in AI and not using
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText - you are seriously wasting your time. It's like Figma but for backend AI applications. Design & test your entire stack in less than an hour. Even test MVP. Build to industrial scale with the exported output.
			link 6:56 PM · Aug 19, 2023, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 11 likes, url='https://twitter.com/intent/like?tweet_id=1692973803188392402'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1692973803188392402'
			button Copy link
			link Read 2 replies, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
		article
			link Damian Soto, url='https://twitter.com/sotoplatero/status/1692286497850855494'
				image Damian Soto, url='https://pbs.twimg.com/profile_images/1872860928502349824/HItLB9zt_normal.jpg'
			link Damian Soto, url='https://twitter.com/sotoplatero/status/1692286497850855494'
			link @sotoplatero, url='https://twitter.com/sotoplatero/status/1692286497850855494'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=sotoplatero'
			link View on Twitter, url='https://twitter.com/sotoplatero/status/1692286497850855494'
			paragraph
				StaticText Chatea Gratis con tus PDF sin código !!!

En este hilo te muestro como crear un chat gpt personalizado sin una linea de código que puedes incluir en tu web

Usamos
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText que es una increíble herramienta para crear aplicaciones LLM con
				link #nocode, url='https://twitter.com/hashtag/nocode'
				StaticText .

Empezamos🧵
			link Image, url='https://twitter.com/sotoplatero/status/1692286497850855494'
				image Image, url='https://pbs.twimg.com/media/F3w1mbEWUAQPpmL?format=jpg&name=small'
			link 9:25 PM · Aug 17, 2023, url='https://twitter.com/sotoplatero/status/1692286497850855494'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 22 likes, url='https://twitter.com/intent/like?tweet_id=1692286497850855494'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1692286497850855494'
			button Copy link
			link Read 2 replies, url='https://twitter.com/sotoplatero/status/1692286497850855494'
		article
			link VerySmallWoods, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
				image VerySmallWoods, url='https://pbs.twimg.com/profile_images/1600964189731934222/eWMb0-L2_normal.jpg'
			link VerySmallWoods Verified account, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
				image Verified account
			link @verysmallwoods, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=verysmallwoods'
			link View on Twitter, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
			paragraph
				StaticText AutoGen = LLM多代理框架 👨‍👩‍👧‍👦
Flowise = 无代码LLM工作流构建平台 0️⃣

由
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText 负责构建功能单元；由AutoGen负责调度协作，任务执行。

嗯！有点美妙！
🎏 🎀 🪄 🪅 🎊 🎉

AutoGen + Flowise = 零代码平台上的超级AI助理 

视频 👇
				link youtu.be/gKNR1ghU1Ao?si…, url='https://youtu.be/gKNR1ghU1Ao?si=ZI9jqz3ss51NG8HX'
				link #AutoGen, url='https://twitter.com/hashtag/AutoGen'
				link #Flowise, url='https://twitter.com/hashtag/Flowise'
				link #OpenAI, url='https://twitter.com/hashtag/OpenAI'
				StaticText …
			link 1:05 AM · Oct 22, 2023, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 11 likes, url='https://twitter.com/intent/like?tweet_id=1715897092244189221'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1715897092244189221'
			button Copy link
			link Read more on Twitter, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
		heading Webinars
		paragraph
			StaticText Learn how to use Flowise from different webinar series with our partners
		image How to Build No-Code SQL Chatbots using Flowise, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fsinglestore_webinar_2.94e511f6.jpeg&w=828&q=75'
		image SingleStore, url='https://flowiseai.com/_next/static/media/singlestore.a5b72cb0.svg'
		StaticText How to Build No-Code SQL Chatbots using Flowise
		link Learn More, url='https://memsql.wistia.com/medias/i1ra0jared'
		image LlamaIndex Webinar: Build No-Code RAG with Flowise, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fllamaindex_webinar.a14452aa.png&w=750&q=75'
		image Milvus, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fllamaindex.5ac46e4e.png&w=48&q=75'
		StaticText LlamaIndex Webinar: Build No-Code RAG with Flowise
		link Learn More, url='https://youtu.be/k5Txq5C_AWA?si=5oqbNBvqP1BEcpVm'
		image How to Build a NoCode AWS Bedrock LLM App on Flowise, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fsinglestore_aws_webinar.185bcd9c.png&w=1080&q=75'
		image SingleStore, url='https://flowiseai.com/_next/static/media/singlestore.a5b72cb0.svg'
		image AWS, url='https://flowiseai.com/_next/static/media/aws.c9a4034b.svg'
		StaticText How to Build a NoCode AWS Bedrock LLM App on Flowise
		link Learn More, url='https://memsql.wistia.com/medias/y230cbhxb0?utm_medium=email&utm_source=singlestore&utm_campaign=7014X0000029ZgFQAU&campaignid=7014X0000029ZgFQAU'
		image Drag and Drop LLMs: Simplifying RAG with FlowiseAI and Milvus, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fmilvus_webinar.0165f039.png&w=828&q=75'
		image Milvus, url='https://flowiseai.com/_next/static/media/milvus.1ae32e3c.svg'
		StaticText Drag and Drop LLMs: Simplifying RAG with FlowiseAI and Milvus
		link Learn More, url='https://youtu.be/OeloMm8SdMc?si=R1sdxako6YM857MT'
		image LangChain Low-Code/No-Code Webinar, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Flangchainwebinar.2f5914b2.png&w=640&q=75'
		image Langchain, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Flangchain.c1e79304.png&w=48&q=75'
		StaticText LangChain Weekly Webinar - Low-Code/No-Code LLM
		link Learn More, url='https://youtu.be/qWv2vyOX0tk?si=-SJM5Z7UvYlOdUhG'
		heading Enterprise
		paragraph
			StaticText Looking for specific use cases and support?
		link Lets Chat, url='mailto:hello@flowiseai.com'
	contentinfo
		list
			listitem
				link Terms of Service, url='https://flowiseai.com/terms'
			listitem
				link Privacy Policy, url='https://flowiseai.com/privacy'
			listitem
				link Twitter, url='https://twitter.com/FlowiseAI'
					image
			listitem
				link Github, url='https://github.com/FlowiseAI/Flowise'
					image
			listitem
				link Linkedin, url='https://www.linkedin.com/company/flowiseai'
					image
		StaticText © FlowiseAI Inc. All rights reserved.
	alert, atomic
```
</details>



```
RootWebArea Flowise - Low code LLM Apps Builder, focused, url='https://flowiseai.com/#usecases'
	banner
		link Flowise, url='https://flowiseai.com/'
			image Flowise, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Flogo-color-high.e60de2f8.png&w=256&q=75'
		link Star FlowiseAI/Flowise on GitHub, url='https://github.com/FlowiseAI/Flowise'
```
<details><summary>Show more</summary>

```
		link 33609 stargazers on GitHub, url='https://github.com/FlowiseAI/Flowise/stargazers'
			StaticText 33,609
		navigation
			list
				listitem
					link Features, url='https://flowiseai.com/#features'
				listitem
					link Use Cases, focused, url='https://flowiseai.com/#usecases'
				listitem
					link Pricing, url='https://flowiseai.com/#pricing'
				listitem
					link Community, url='https://flowiseai.com/#community'
				listitem
					link Webinars, url='https://flowiseai.com/#webinars'
				listitem
					link Login, url='https://flowiseai.com/auth/login'
						button Login
				listitem
					link Request Access, url='https://flowiseai.com/join'
						button Request Access
							image
	main
		heading Build LLM Apps
		heading Easily
		paragraph
			StaticText Open source low-code tool for developers to build customized LLM orchestration flow & AI agents
		link Request Access, url='https://flowiseai.com/join'
			button Request Access
				image
		link Documentation, url='https://docs.flowiseai.com/'
			button Documentation
		StaticText Backed by
		image YCombinator, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2FYC.dc9b9030.png&w=32&q=75'
		StaticText Combinator
		paragraph
			StaticText Trusted and used by teams around the globe
		image AWS, url='https://flowiseai.com/_next/static/media/aws.c9a4034b.svg'
		image Alibaba, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Falibaba.d717abe3.png&w=128&q=75'
		image Hitachi, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fhitachi.cc8b5524.png&w=64&q=75'
		image ByteDance, url='https://flowiseai.com/_next/static/media/ByteDance.cfa75bfd.svg'
		image Microsoft, url='https://flowiseai.com/_next/static/media/microsoft.0e14c6cf.svg'
		image InsightSoftware, url='https://flowiseai.com/_next/static/media/insightsoftware.c5783e21.svg'
		image Google, url='https://flowiseai.com/_next/static/media/google.c43e43a7.svg'
		image Accenture, url='https://flowiseai.com/_next/static/media/accenture.3222125e.svg'
		image ERoad, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Feroad.ea8bab6e.png&w=64&q=75'
		image AWS, url='https://flowiseai.com/_next/static/media/aws.c9a4034b.svg'
		image Alibaba, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Falibaba.d717abe3.png&w=128&q=75'
		image Hitachi, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fhitachi.cc8b5524.png&w=64&q=75'
		image ByteDance, url='https://flowiseai.com/_next/static/media/ByteDance.cfa75bfd.svg'
		image Microsoft, url='https://flowiseai.com/_next/static/media/microsoft.0e14c6cf.svg'
		image InsightSoftware, url='https://flowiseai.com/_next/static/media/insightsoftware.c5783e21.svg'
		image Google, url='https://flowiseai.com/_next/static/media/google.c43e43a7.svg'
		image Accenture, url='https://flowiseai.com/_next/static/media/accenture.3222125e.svg'
		image ERoad, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Feroad.ea8bab6e.png&w=64&q=75'
		heading Iterate, fast
		paragraph
			StaticText Developing LLM apps takes countless iterations. With low code approach, we enable quick iterations to go from testing to production
		list
			listitem
				StaticText $
				StaticText npm install -g flowise
			listitem
				StaticText $
				StaticText npx flowise start
		link Get Started, url='https://docs.flowiseai.com/getting-started'
		image Features 01, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fintegrations1.8181abd6.png&w=640&q=75'
		StaticText Chatflow
		heading LLM Orchestration
		paragraph
			StaticText Connect LLMs with memory, data loaders, cache, moderation and many more
		list
			listitem
				image
				StaticText Langchain
			listitem
				image
				StaticText LlamaIndex
			listitem
				image
				StaticText 100+ integrations
		StaticText Agents
		heading Agents & Assistants
		paragraph
			StaticText Create autonomous agent that can uses tools to execute different tasks
		list
			listitem
				image
				StaticText Custom Tools
			listitem
				image
				StaticText OpenAI Assistant
			listitem
				image
				StaticText Function Agent
		list
			listitem
				StaticText import
				StaticText requests
			listitem
			listitem
				StaticText url
				StaticText =
				StaticText "/api/v1/prediction/:id"
			listitem
			listitem
				StaticText def
				StaticText query
				StaticText (
				StaticText payload
				StaticText )
				StaticText :
			listitem
				StaticText response
				StaticText =
				StaticText requests.post
				StaticText (
			listitem
				StaticText url,
			listitem
				StaticText json
				StaticText =
				StaticText payload
			listitem
				StaticText )
			listitem
				StaticText return
				StaticText response.json
				StaticText (
				StaticText )
			listitem
			listitem
				StaticText output
				StaticText =
				StaticText query
				StaticText (
				StaticText {
			listitem
				StaticText question
				StaticText :
				StaticText "hello!"
			listitem
				StaticText )
				StaticText }
		StaticText Developer Friendly
		heading API, SDK, Embed
		paragraph
			StaticText Extend and integrate to your applications using APIs, SDK and Embedded Chat
		list
			listitem
				image
				StaticText APIs
			listitem
				image
				StaticText Embedded Widget
			listitem
				image
				StaticText React SDK
		image Features 02, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fopensource.bed900d8.png&w=640&q=75'
		StaticText Platform Agnostic
		heading Open source LLMs
		paragraph
			StaticText Run in air-gapped environment with local LLMs, embeddings and vector databases
		list
			listitem
				image
				StaticText HuggingFace, Ollama, LocalAI, Replicate
			listitem
				image
				StaticText Llama2, Mistral, Vicuna, Orca, Llava
			listitem
				image
				StaticText Self host on AWS, Azure, GCP
		heading Use Cases
		paragraph
			StaticText One platform, endless possibilities. See some of the use cases
		[309] button Product Catalog, center=(518,3756)
		[310] button Product Description, center=(739,3756)
		[311] button Query SQL Database, center=(960,3756)
		[312] button Customer Support, center=(1181,3756)
		[313] button Structured Data, center=(1402,3756)
		paragraph
			StaticText Product catalog chatbot to answer any questions related to the products
		image ProductCatalog, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fproductcatalog.9d6b9124.png&w=1920&q=75'
		heading Pricing
		paragraph
			StaticText Free 14 day trial. No credit card required.
		heading Starter
		paragraph
			StaticText For individuals & small teams
		paragraph
			StaticText $35
			StaticText /month
		list
			listitem
				image
				StaticText 10,000 Predictions / month
				button
					image
				StaticText then $0.001 per prediction
			listitem
				image
				StaticText 1GB Storage
				button
					image
			listitem
				image
				StaticText Database Backup
			listitem
				image
				StaticText 1 Week Log Retention
			listitem
				image
				StaticText Evaluations & Metrics
			listitem
				image
				StaticText Custom Chatbot Branding
				button
					image
			listitem
				image
				StaticText Community Support
		link Start free trial, url='https://flowiseai.com/join'
			button Start free trial
		heading Pro
		paragraph
			StaticText For medium-sized businesses
		paragraph
			StaticText $65
			StaticText /month
		list
			listitem
				image
				StaticText Everything in Starter
			listitem
				image
				StaticText 50,000 Predictions / month
				button
					image
				StaticText then $0.001 per prediction
			listitem
				image
				StaticText 10GB Storage
				button
					image
			listitem
				image
				StaticText Unlimited Workspaces
			listitem
				image
				StaticText Admin Roles & Permissions
			listitem
				image
				StaticText 3 Months Log Retention
			listitem
				image
				StaticText Priority Support
		button Coming Soon, disabled=True
		heading Enterprise
		paragraph
			StaticText For large organizations
		paragraph
			StaticText Contact Us
		list
			listitem
				image
				StaticText On-Premise Deployment
			listitem
				image
				StaticText Air-gapped Environments
			listitem
				image
				StaticText SSO & SAML
			listitem
				image
				StaticText LDAP & RBAC
			listitem
				image
				StaticText Versioning
			listitem
				image
				StaticText Audit Logs
			listitem
				image
				StaticText 99.99% Uptime SLA
		link Contact Us, url='mailto:hello@flowiseai.com'
			button Contact Us
		heading Community 🫶
		paragraph
			StaticText Open source community is the heart of Flowise. See why developers love and build using Flowise
		link Join Discord, url='https://discord.gg/jbaHfsRVBW'
			image
		Iframe
			RootWebArea Flowise AI Tutorial #1 - Introduction & Setup - YouTube, url='https://www.youtube.com/embed/tD6fwQyUIJE?si=na1zK5OISsE4N5Vg'
				[a30] link Photo image of Leon van Zyl, center=(440,5756)
				[a38] link Flowise AI Tutorial #1 - Introduction & Setup, center=(585,5757), url='https://www.youtube.com/watch?v=tD6fwQyUIJE'
				[a68] button More, center=(724,5750), hasPopup='menu'
					image
				[a79] button Play, center=(584,5823)
					image
				generic, atomic
		Iframe
			RootWebArea How to Build an AI Document Chatbot in 10 Minutes - YouTube, url='https://www.youtube.com/embed/riXpu1tHzl0?si=KLVQ9TRUcZCTjXuj'
				[b30] link Photo image of Dave Ebbelaar, center=(816,5756)
				[b38] link How to Build an AI Document Chatbot in 10 Minutes, center=(961,5757), url='https://www.youtube.com/watch?v=riXpu1tHzl0'
				[b68] button More, center=(1100,5750), hasPopup='menu'
					image
				[b79] button Play, center=(960,5823)
					image
				generic, atomic
		Iframe
			RootWebArea Flowise is an open source no-code UI visual tool to build 🦜🔗LangChain applications - YouTube, url='https://www.youtube.com/embed/CovAPtQPU0k?si=KcH3ttNubGtp03Za'
				[c30] link Photo image of Cobus Greyling, center=(1192,5756)
				[c38] link Flowise is an open source no-code UI visual tool to build 🦜🔗LangChain applications, center=(1337,5757), url='https://www.youtube.com/watch?v=CovAPtQPU0k'
				[c68] button More, center=(1476,5750), hasPopup='menu'
					image
				[c79] button Play, center=(1336,5823)
					image
				generic, atomic
		Iframe
			RootWebArea Flowise: No Code ChatBot Building Platform: LangChain - YouTube, url='https://www.youtube.com/embed/Q7_dKkosJY4?si=O0swoActrfHlDFSN'
				[d30] link Photo image of Prompt Engineering, center=(440,5978)
				[d38] link Flowise: No Code ChatBot Building Platform: LangChain, center=(585,5979), url='https://www.youtube.com/watch?v=Q7_dKkosJY4'
				[d68] button More, center=(724,5972), hasPopup='menu'
					image
				[d79] button Play, center=(584,6045)
					image
				generic, atomic
		Iframe
			RootWebArea Build a No-Code Chat-with-PDF LangChain app using Flowise and Bubble - YouTube, url='https://www.youtube.com/embed/kOwmPe8aLAA?si=gBaUlkyFOe3TS2V-'
				[e30] link Photo image of AI with Misbah, center=(816,5978)
				[e38] link Build a No-Code Chat-with-PDF LangChain app using Flowise and Bubble, center=(961,5979), url='https://www.youtube.com/watch?v=kOwmPe8aLAA'
				[e68] button More, center=(1100,5972), hasPopup='menu'
					image
				[e79] button Play, center=(960,6045)
					image
				generic, atomic
		Iframe
			RootWebArea Flowise AI: Create LLM Apps with NO Code - FREE Opensource LangChain Apps - YouTube, url='https://www.youtube.com/embed/kvvBUz0q-6I?si=WtrfQ948R1c2dHpf'
				[f30] link Photo image of WorldofAI, center=(1192,5978)
				[f38] link Flowise AI: Create LLM Apps with NO Code - FREE Opensource LangChain Apps, center=(1337,5979), url='https://www.youtube.com/watch?v=kvvBUz0q-6I'
				[f68] button More, center=(1476,5972), hasPopup='menu'
					image
				[f79] button Play, center=(1336,6045)
					image
				generic, atomic
		article
			link Siddhant Gupta, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
				image Siddhant Gupta, url='https://pbs.twimg.com/profile_images/1761449475883835392/yYkjTFPr_normal.jpg'
			link Siddhant Gupta Verified account, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
				image Verified account
			link @Siddhan65490545, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=Siddhan65490545'
			link View on Twitter, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
			paragraph
				StaticText Finally after a month of relentless trial and error, I've successfully created an AI persona bot emulating the teaching style of my mentor
				link @abnux, url='https://twitter.com/abnux'
				StaticText ,  the founder of
				link @10kdesigners, url='https://twitter.com/10kdesigners'
				StaticText . Excited to share my journey in this twitter thread. 🤖🎨 "Sound on 🎙️🔊"
			button View video on Twitter
			link Watch on Twitter, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
			link 2:43 PM · Oct 10, 2023, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 262 likes, url='https://twitter.com/intent/like?tweet_id=1711754261527458189'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1711754261527458189'
			button Copy link
			link Read 33 replies, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
		article
			link Shubham Saboo, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
				image Shubham Saboo, url='https://pbs.twimg.com/profile_images/1670107849815478273/Q3oUhtHM_normal.jpg'
			link Shubham Saboo Verified account, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
				image Verified account
			link @Saboo_Shubham_, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=Saboo_Shubham_'
			link View on Twitter, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
			paragraph
				StaticText Flowise is trending on GitHub

It's an open-source drag & drop UI tool that lets you build custom LLM apps in just minutes.

Powered by LangChain, it features:
- Ready-to-use app templates
- Conversational agents that remember
- Seamless deployment on cloud platforms
			button View video on Twitter
			link Watch on Twitter, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
			link 4:05 AM · Aug 16, 2023, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 523 likes, url='https://twitter.com/intent/like?tweet_id=1691662432807137623'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1691662432807137623'
			button Copy link
			link Read 18 replies, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
		article
			link Muratcan Koylan, url='https://twitter.com/youraimarketer/status/1710908393265782900'
				image Muratcan Koylan, url='https://pbs.twimg.com/profile_images/1847174349335257088/cGzzFLOo_normal.jpg'
			link Muratcan Koylan Verified account, url='https://twitter.com/youraimarketer/status/1710908393265782900'
				image Verified account
			link @youraimarketer, url='https://twitter.com/youraimarketer/status/1710908393265782900'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=youraimarketer'
			link View on Twitter, url='https://twitter.com/youraimarketer/status/1710908393265782900'
			paragraph
				StaticText When you lose momentum, it's hard to regain it.

But here we go again, building a Personal Cockpit with AI Agents.

I've built a chatbot connected to the internet and various APIs, linking it to multiple workflows and AI agents.

Here's the first demo:

1. AI Newsletter Agent…
			button View video on Twitter
			link Watch on Twitter, url='https://twitter.com/youraimarketer/status/1710908393265782900'
			link 6:42 AM · Oct 8, 2023, url='https://twitter.com/youraimarketer/status/1710908393265782900'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 468 likes, url='https://twitter.com/intent/like?tweet_id=1710908393265782900'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1710908393265782900'
			button Copy link
			link Read 17 replies, url='https://twitter.com/youraimarketer/status/1710908393265782900'
		article
			link Eugene, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
				image Eugene, url='https://pbs.twimg.com/profile_images/1501559855865339914/1FzvS9lb_normal.jpg'
			link Eugene, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
			link @sudo_eugene, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=sudo_eugene'
			link View on Twitter, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
			paragraph
				StaticText Using our new AI bot called Koos with
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText to create project management tasks in Notion, right from Slack 🤯

Let me know who would like to see a 5min explainer on how we did this 🎉
			link Image, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
				image Image, url='https://pbs.twimg.com/media/F6dMWW-WsAAUR7d?format=jpg&name=small'
			link Image, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
				image Image, url='https://pbs.twimg.com/media/F6dMWW_XgAEfotx?format=jpg&name=small'
			link 8:39 AM · Sep 20, 2023, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 16 likes, url='https://twitter.com/intent/like?tweet_id=1704414944551125293'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1704414944551125293'
			button Copy link
			link Read 8 replies, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
		article
			link Lior⚡, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
				image Lior⚡, url='https://pbs.twimg.com/profile_images/1817166841992597504/zLRK5Qx__normal.jpg'
			link Lior⚡ Verified account, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
				image Verified account
			link @LiorOnAI, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=LiorOnAI'
			link View on Twitter, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
			paragraph
				StaticText Flowise just reached 12,000 stars on Github. 

It allows you to build customized LLM apps using a simple drag & drop UI.

You can even use built-in templates with logic and conditions connected to LangChain and GPT:

▸ Conversational agent with memory
▸ Chat with PDF and Excel…
			button View video on Twitter
			link Watch on Twitter, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
			link 4:33 PM · Aug 10, 2023, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 836 likes, url='https://twitter.com/intent/like?tweet_id=1689676278746529793'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1689676278746529793'
			button Copy link
			link Read 30 replies, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
		article
			link Derek Cheung, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
				image Derek Cheung, url='https://pbs.twimg.com/profile_images/1653155172414046209/-_tpBZHC_normal.jpg'
			link Derek Cheung Verified account, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
				image Verified account
			link @derekcheungsa, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=derekcheungsa'
			link View on Twitter, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
			paragraph
				StaticText A multi-modal chatbot that effortlessly merges text and image generation into seamless conversations. 🚀

📢 Watch the demo with conversation starting with asking for advice on building strong financial habits (sped up slightly for demo)
 🪄Chatbot magically generates a visual…
			button View video on Twitter
			link Watch on Twitter, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
			link 3:11 AM · Oct 2, 2023, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 21 likes, url='https://twitter.com/intent/like?tweet_id=1708681200661889447'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1708681200661889447'
			button Copy link
			link Read 4 replies, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
		article
			link armand, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
				image armand, url='https://pbs.twimg.com/profile_images/1758729285744091136/9nZk7KcA_normal.jpg'
			link armand Verified account, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
				image Verified account
			link @armand_ruiz, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=armand_ruiz'
			link View on Twitter, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
			paragraph
				StaticText Create your first custom chatbot using LLMs in 5 min!

No-coding required. We will use
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText Join here to get the step-by-step tutorial and video tomorrow at 7 a.m. ET:
				link nocode.ai, url='https://www.nocode.ai/'
			link Image, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
				image Image, url='https://pbs.twimg.com/media/F4ZG8HwaEAAhSE9?format=jpg&name=small'
			link 5:06 PM · Aug 25, 2023, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 13 likes, url='https://twitter.com/intent/like?tweet_id=1695120505945383161'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1695120505945383161'
			button Copy link
			link Read 3 replies, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
		article
			link Alessio Pomaro, url='https://twitter.com/alepom/status/1694599974716153904'
				image Alessio Pomaro, url='https://pbs.twimg.com/profile_images/1350189157931479041/LaWfQ0IQ_normal.jpg'
			link Alessio Pomaro, url='https://twitter.com/alepom/status/1694599974716153904'
			link @alepom, url='https://twitter.com/alepom/status/1694599974716153904'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=alepom'
			link View on Twitter, url='https://twitter.com/alepom/status/1694599974716153904'
			paragraph
				StaticText 🧠 Realizzare un
				link #chatbot, url='https://twitter.com/hashtag/chatbot'
				StaticText o una ricerca evoluta per un sito web: quanto sarebbe stato complesso un paio d'anni fa? Tanto. Pochi servizi erano davvero efficienti. 
🦾 Nelle immagini si vede un'esempio di come l'ho creato con
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText .
				link #AI, url='https://twitter.com/hashtag/AI'
				link #Flowise, url='https://twitter.com/hashtag/Flowise'
				link #LLaMA2, url='https://twitter.com/hashtag/LLaMA2'
				link #Claude, url='https://twitter.com/hashtag/Claude'
			link Image, url='https://twitter.com/alepom/status/1694599974716153904'
				image Image, url='https://pbs.twimg.com/media/F4RtrXGWQAAdnSg?format=jpg&name=small'
			link Image, url='https://twitter.com/alepom/status/1694599974716153904'
				image Image, url='https://pbs.twimg.com/media/F4RtrygWUAAFCua?format=jpg&name=small'
			link Image, url='https://twitter.com/alepom/status/1694599974716153904'
				image Image, url='https://pbs.twimg.com/media/F4RtsJjXIAAJOhx?format=jpg&name=small'
			link Image, url='https://twitter.com/alepom/status/1694599974716153904'
				image Image, url='https://pbs.twimg.com/media/F4RtscNXgAAMGhu?format=png&name=small'
			link 6:38 AM · Aug 24, 2023, url='https://twitter.com/alepom/status/1694599974716153904'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 7 likes, url='https://twitter.com/intent/like?tweet_id=1694599974716153904'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1694599974716153904'
			button Copy link
			link Read 2 replies, url='https://twitter.com/alepom/status/1694599974716153904'
		article
			link John Damask, url='https://twitter.com/jbdamask/status/1693777249009373584'
				image John Damask, url='https://pbs.twimg.com/profile_images/1688209206204121093/9iNcGQoo_normal.jpg'
			link John Damask Verified account, url='https://twitter.com/jbdamask/status/1693777249009373584'
				image Verified account
			link @jbdamask, url='https://twitter.com/jbdamask/status/1693777249009373584'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=jbdamask'
			link View on Twitter, url='https://twitter.com/jbdamask/status/1693777249009373584'
			paragraph
				StaticText Flowise is seriously impressive. Not only for quickly building and deploying LLM apps, but for visualizing chains
			link 12:08 AM · Aug 22, 2023, url='https://twitter.com/jbdamask/status/1693777249009373584'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 9 likes, url='https://twitter.com/intent/like?tweet_id=1693777249009373584'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1693777249009373584'
			button Copy link
			link Read 3 replies, url='https://twitter.com/jbdamask/status/1693777249009373584'
		article
			link Abu Mu'aaz, url='https://twitter.com/abumuaaz/status/1693448039594381481'
				image Abu Mu'aaz, url='https://pbs.twimg.com/profile_images/1396343945190285314/brEgb4B9_normal.jpg'
			link Abu Mu'aaz, url='https://twitter.com/abumuaaz/status/1693448039594381481'
			link @abumuaaz, url='https://twitter.com/abumuaaz/status/1693448039594381481'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=abumuaaz'
			link View on Twitter, url='https://twitter.com/abumuaaz/status/1693448039594381481'
			paragraph
				StaticText Thanks to
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText &
				link @LangChainAI, url='https://twitter.com/LangChainAI'
				StaticText , it's so easy to create Telegram Bot that capable of getting real-time bus info (location & speed) from GPS device. Plus more functionality to calculate distance, duration & presenting map to user.
				link @OpenAI, url='https://twitter.com/OpenAI'
				StaticText Function Calling is awesome too 👍
			link Image, url='https://twitter.com/abumuaaz/status/1693448039594381481'
				image Image, url='https://pbs.twimg.com/media/F4BToWubcAANu1L?format=jpg&name=small'
			link Image, url='https://twitter.com/abumuaaz/status/1693448039594381481'
				image Image, url='https://pbs.twimg.com/media/F4BTptvbgAIc_hK?format=jpg&name=small'
			link 2:20 AM · Aug 21, 2023, url='https://twitter.com/abumuaaz/status/1693448039594381481'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 16 likes, url='https://twitter.com/intent/like?tweet_id=1693448039594381481'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1693448039594381481'
			button Copy link
			link Read 3 replies, url='https://twitter.com/abumuaaz/status/1693448039594381481'
		article
			link Wayne Culbreth, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
				image Wayne Culbreth, url='https://pbs.twimg.com/profile_images/1622684462587777037/_SDI7qtQ_normal.png'
			link Wayne Culbreth Verified account, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
				image Verified account
			link @wayne_culbreth, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=wayne_culbreth'
			link View on Twitter, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
			paragraph
				StaticText If you are building in AI and not using
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText - you are seriously wasting your time. It's like Figma but for backend AI applications. Design & test your entire stack in less than an hour. Even test MVP. Build to industrial scale with the exported output.
			link 6:56 PM · Aug 19, 2023, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 11 likes, url='https://twitter.com/intent/like?tweet_id=1692973803188392402'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1692973803188392402'
			button Copy link
			link Read 2 replies, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
		article
			link Damian Soto, url='https://twitter.com/sotoplatero/status/1692286497850855494'
				image Damian Soto, url='https://pbs.twimg.com/profile_images/1872860928502349824/HItLB9zt_normal.jpg'
			link Damian Soto, url='https://twitter.com/sotoplatero/status/1692286497850855494'
			link @sotoplatero, url='https://twitter.com/sotoplatero/status/1692286497850855494'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=sotoplatero'
			link View on Twitter, url='https://twitter.com/sotoplatero/status/1692286497850855494'
			paragraph
				StaticText Chatea Gratis con tus PDF sin código !!!

En este hilo te muestro como crear un chat gpt personalizado sin una linea de código que puedes incluir en tu web

Usamos
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText que es una increíble herramienta para crear aplicaciones LLM con
				link #nocode, url='https://twitter.com/hashtag/nocode'
				StaticText .

Empezamos🧵
			link Image, url='https://twitter.com/sotoplatero/status/1692286497850855494'
				image Image, url='https://pbs.twimg.com/media/F3w1mbEWUAQPpmL?format=jpg&name=small'
			link 9:25 PM · Aug 17, 2023, url='https://twitter.com/sotoplatero/status/1692286497850855494'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 22 likes, url='https://twitter.com/intent/like?tweet_id=1692286497850855494'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1692286497850855494'
			button Copy link
			link Read 2 replies, url='https://twitter.com/sotoplatero/status/1692286497850855494'
		article
			link VerySmallWoods, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
				image VerySmallWoods, url='https://pbs.twimg.com/profile_images/1600964189731934222/eWMb0-L2_normal.jpg'
			link VerySmallWoods Verified account, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
				image Verified account
			link @verysmallwoods, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=verysmallwoods'
			link View on Twitter, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
			paragraph
				StaticText AutoGen = LLM多代理框架 👨‍👩‍👧‍👦
Flowise = 无代码LLM工作流构建平台 0️⃣

由
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText 负责构建功能单元；由AutoGen负责调度协作，任务执行。

嗯！有点美妙！
🎏 🎀 🪄 🪅 🎊 🎉

AutoGen + Flowise = 零代码平台上的超级AI助理 

视频 👇
				link youtu.be/gKNR1ghU1Ao?si…, url='https://youtu.be/gKNR1ghU1Ao?si=ZI9jqz3ss51NG8HX'
				link #AutoGen, url='https://twitter.com/hashtag/AutoGen'
				link #Flowise, url='https://twitter.com/hashtag/Flowise'
				link #OpenAI, url='https://twitter.com/hashtag/OpenAI'
				StaticText …
			link 1:05 AM · Oct 22, 2023, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 11 likes, url='https://twitter.com/intent/like?tweet_id=1715897092244189221'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1715897092244189221'
			button Copy link
			link Read more on Twitter, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
		heading Webinars
		paragraph
			StaticText Learn how to use Flowise from different webinar series with our partners
		image How to Build No-Code SQL Chatbots using Flowise, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fsinglestore_webinar_2.94e511f6.jpeg&w=828&q=75'
		image SingleStore, url='https://flowiseai.com/_next/static/media/singlestore.a5b72cb0.svg'
		StaticText How to Build No-Code SQL Chatbots using Flowise
		link Learn More, url='https://memsql.wistia.com/medias/i1ra0jared'
		image LlamaIndex Webinar: Build No-Code RAG with Flowise, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fllamaindex_webinar.a14452aa.png&w=750&q=75'
		image Milvus, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fllamaindex.5ac46e4e.png&w=48&q=75'
		StaticText LlamaIndex Webinar: Build No-Code RAG with Flowise
		link Learn More, url='https://youtu.be/k5Txq5C_AWA?si=5oqbNBvqP1BEcpVm'
		image How to Build a NoCode AWS Bedrock LLM App on Flowise, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fsinglestore_aws_webinar.185bcd9c.png&w=1080&q=75'
		image SingleStore, url='https://flowiseai.com/_next/static/media/singlestore.a5b72cb0.svg'
		image AWS, url='https://flowiseai.com/_next/static/media/aws.c9a4034b.svg'
		StaticText How to Build a NoCode AWS Bedrock LLM App on Flowise
		link Learn More, url='https://memsql.wistia.com/medias/y230cbhxb0?utm_medium=email&utm_source=singlestore&utm_campaign=7014X0000029ZgFQAU&campaignid=7014X0000029ZgFQAU'
		image Drag and Drop LLMs: Simplifying RAG with FlowiseAI and Milvus, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fmilvus_webinar.0165f039.png&w=828&q=75'
		image Milvus, url='https://flowiseai.com/_next/static/media/milvus.1ae32e3c.svg'
		StaticText Drag and Drop LLMs: Simplifying RAG with FlowiseAI and Milvus
		link Learn More, url='https://youtu.be/OeloMm8SdMc?si=R1sdxako6YM857MT'
		image LangChain Low-Code/No-Code Webinar, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Flangchainwebinar.2f5914b2.png&w=640&q=75'
		image Langchain, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Flangchain.c1e79304.png&w=48&q=75'
		StaticText LangChain Weekly Webinar - Low-Code/No-Code LLM
		link Learn More, url='https://youtu.be/qWv2vyOX0tk?si=-SJM5Z7UvYlOdUhG'
		heading Enterprise
		paragraph
			StaticText Looking for specific use cases and support?
		link Lets Chat, url='mailto:hello@flowiseai.com'
	contentinfo
		list
			listitem
				link Terms of Service, url='https://flowiseai.com/terms'
			listitem
				link Privacy Policy, url='https://flowiseai.com/privacy'
			listitem
				link Twitter, url='https://twitter.com/FlowiseAI'
					image
			listitem
				link Github, url='https://github.com/FlowiseAI/Flowise'
					image
			listitem
				link Linkedin, url='https://www.linkedin.com/company/flowiseai'
					image
		StaticText © FlowiseAI Inc. All rights reserved.
	alert, atomic
```
</details>

**Reasoning for action:** I identified that to achieve the goal of understanding how Flowise can help build customized LLM apps, I need to access the Use Cases section. By clicking the link to Use Cases (represented by the index 60 in the navigation tree), I will be directed to a page that outlines different scenarios where Flowise can be applied, thus providing insights necessary for the user's research.

**Action:** click(60) # Click on the Use Cases link to explore practical applications of Flowise.

**Change Description:** The web agent clicked on the 'Use Cases' link, transitioning the page from the features section to the use cases section of the Flowise website, which is now focused on practical applications of the product.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://flowiseai.com/#usecases

https://flowiseai.com/#usecases

**Content (before/after):** 

```
RootWebArea Flowise - Low code LLM Apps Builder, focused, url='https://flowiseai.com/#usecases'
	banner
		link Flowise, url='https://flowiseai.com/'
			image Flowise, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Flogo-color-high.e60de2f8.png&w=256&q=75'
		link Star FlowiseAI/Flowise on GitHub, url='https://github.com/FlowiseAI/Flowise'
```
<details><summary>Show more</summary>

```
		link 33609 stargazers on GitHub, url='https://github.com/FlowiseAI/Flowise/stargazers'
			StaticText 33,609
		navigation
			list
				listitem
					link Features, url='https://flowiseai.com/#features'
				listitem
					link Use Cases, focused, url='https://flowiseai.com/#usecases'
				listitem
					link Pricing, url='https://flowiseai.com/#pricing'
				listitem
					link Community, url='https://flowiseai.com/#community'
				listitem
					link Webinars, url='https://flowiseai.com/#webinars'
				listitem
					link Login, url='https://flowiseai.com/auth/login'
						button Login
				listitem
					link Request Access, url='https://flowiseai.com/join'
						button Request Access
							image
	main
		heading Build LLM Apps
		heading Easily
		paragraph
			StaticText Open source low-code tool for developers to build customized LLM orchestration flow & AI agents
		link Request Access, url='https://flowiseai.com/join'
			button Request Access
				image
		link Documentation, url='https://docs.flowiseai.com/'
			button Documentation
		StaticText Backed by
		image YCombinator, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2FYC.dc9b9030.png&w=32&q=75'
		StaticText Combinator
		paragraph
			StaticText Trusted and used by teams around the globe
		image AWS, url='https://flowiseai.com/_next/static/media/aws.c9a4034b.svg'
		image Alibaba, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Falibaba.d717abe3.png&w=128&q=75'
		image Hitachi, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fhitachi.cc8b5524.png&w=64&q=75'
		image ByteDance, url='https://flowiseai.com/_next/static/media/ByteDance.cfa75bfd.svg'
		image Microsoft, url='https://flowiseai.com/_next/static/media/microsoft.0e14c6cf.svg'
		image InsightSoftware, url='https://flowiseai.com/_next/static/media/insightsoftware.c5783e21.svg'
		image Google, url='https://flowiseai.com/_next/static/media/google.c43e43a7.svg'
		image Accenture, url='https://flowiseai.com/_next/static/media/accenture.3222125e.svg'
		image ERoad, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Feroad.ea8bab6e.png&w=64&q=75'
		image AWS, url='https://flowiseai.com/_next/static/media/aws.c9a4034b.svg'
		image Alibaba, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Falibaba.d717abe3.png&w=128&q=75'
		image Hitachi, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fhitachi.cc8b5524.png&w=64&q=75'
		image ByteDance, url='https://flowiseai.com/_next/static/media/ByteDance.cfa75bfd.svg'
		image Microsoft, url='https://flowiseai.com/_next/static/media/microsoft.0e14c6cf.svg'
		image InsightSoftware, url='https://flowiseai.com/_next/static/media/insightsoftware.c5783e21.svg'
		image Google, url='https://flowiseai.com/_next/static/media/google.c43e43a7.svg'
		image Accenture, url='https://flowiseai.com/_next/static/media/accenture.3222125e.svg'
		image ERoad, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Feroad.ea8bab6e.png&w=64&q=75'
		heading Iterate, fast
		paragraph
			StaticText Developing LLM apps takes countless iterations. With low code approach, we enable quick iterations to go from testing to production
		list
			listitem
				StaticText $
				StaticText npm install -g flowise
			listitem
				StaticText $
				StaticText npx flowise start
		link Get Started, url='https://docs.flowiseai.com/getting-started'
		image Features 01, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fintegrations1.8181abd6.png&w=640&q=75'
		StaticText Chatflow
		heading LLM Orchestration
		paragraph
			StaticText Connect LLMs with memory, data loaders, cache, moderation and many more
		list
			listitem
				image
				StaticText Langchain
			listitem
				image
				StaticText LlamaIndex
			listitem
				image
				StaticText 100+ integrations
		StaticText Agents
		heading Agents & Assistants
		paragraph
			StaticText Create autonomous agent that can uses tools to execute different tasks
		list
			listitem
				image
				StaticText Custom Tools
			listitem
				image
				StaticText OpenAI Assistant
			listitem
				image
				StaticText Function Agent
		list
			listitem
				StaticText import
				StaticText requests
			listitem
			listitem
				StaticText url
				StaticText =
				StaticText "/api/v1/prediction/:id"
			listitem
			listitem
				StaticText def
				StaticText query
				StaticText (
				StaticText payload
				StaticText )
				StaticText :
			listitem
				StaticText response
				StaticText =
				StaticText requests.post
				StaticText (
			listitem
				StaticText url,
			listitem
				StaticText json
				StaticText =
				StaticText payload
			listitem
				StaticText )
			listitem
				StaticText return
				StaticText response.json
				StaticText (
				StaticText )
			listitem
			listitem
				StaticText output
				StaticText =
				StaticText query
				StaticText (
				StaticText {
			listitem
				StaticText question
				StaticText :
				StaticText "hello!"
			listitem
				StaticText )
				StaticText }
		StaticText Developer Friendly
		heading API, SDK, Embed
		paragraph
			StaticText Extend and integrate to your applications using APIs, SDK and Embedded Chat
		list
			listitem
				image
				StaticText APIs
			listitem
				image
				StaticText Embedded Widget
			listitem
				image
				StaticText React SDK
		image Features 02, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fopensource.bed900d8.png&w=640&q=75'
		StaticText Platform Agnostic
		heading Open source LLMs
		paragraph
			StaticText Run in air-gapped environment with local LLMs, embeddings and vector databases
		list
			listitem
				image
				StaticText HuggingFace, Ollama, LocalAI, Replicate
			listitem
				image
				StaticText Llama2, Mistral, Vicuna, Orca, Llava
			listitem
				image
				StaticText Self host on AWS, Azure, GCP
		heading Use Cases
		paragraph
			StaticText One platform, endless possibilities. See some of the use cases
		[309] button Product Catalog, center=(518,3756)
		[310] button Product Description, center=(739,3756)
		[311] button Query SQL Database, center=(960,3756)
		[312] button Customer Support, center=(1181,3756)
		[313] button Structured Data, center=(1402,3756)
		paragraph
			StaticText Product catalog chatbot to answer any questions related to the products
		image ProductCatalog, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fproductcatalog.9d6b9124.png&w=1920&q=75'
		heading Pricing
		paragraph
			StaticText Free 14 day trial. No credit card required.
		heading Starter
		paragraph
			StaticText For individuals & small teams
		paragraph
			StaticText $35
			StaticText /month
		list
			listitem
				image
				StaticText 10,000 Predictions / month
				button
					image
				StaticText then $0.001 per prediction
			listitem
				image
				StaticText 1GB Storage
				button
					image
			listitem
				image
				StaticText Database Backup
			listitem
				image
				StaticText 1 Week Log Retention
			listitem
				image
				StaticText Evaluations & Metrics
			listitem
				image
				StaticText Custom Chatbot Branding
				button
					image
			listitem
				image
				StaticText Community Support
		link Start free trial, url='https://flowiseai.com/join'
			button Start free trial
		heading Pro
		paragraph
			StaticText For medium-sized businesses
		paragraph
			StaticText $65
			StaticText /month
		list
			listitem
				image
				StaticText Everything in Starter
			listitem
				image
				StaticText 50,000 Predictions / month
				button
					image
				StaticText then $0.001 per prediction
			listitem
				image
				StaticText 10GB Storage
				button
					image
			listitem
				image
				StaticText Unlimited Workspaces
			listitem
				image
				StaticText Admin Roles & Permissions
			listitem
				image
				StaticText 3 Months Log Retention
			listitem
				image
				StaticText Priority Support
		button Coming Soon, disabled=True
		heading Enterprise
		paragraph
			StaticText For large organizations
		paragraph
			StaticText Contact Us
		list
			listitem
				image
				StaticText On-Premise Deployment
			listitem
				image
				StaticText Air-gapped Environments
			listitem
				image
				StaticText SSO & SAML
			listitem
				image
				StaticText LDAP & RBAC
			listitem
				image
				StaticText Versioning
			listitem
				image
				StaticText Audit Logs
			listitem
				image
				StaticText 99.99% Uptime SLA
		link Contact Us, url='mailto:hello@flowiseai.com'
			button Contact Us
		heading Community 🫶
		paragraph
			StaticText Open source community is the heart of Flowise. See why developers love and build using Flowise
		link Join Discord, url='https://discord.gg/jbaHfsRVBW'
			image
		Iframe
			RootWebArea Flowise AI Tutorial #1 - Introduction & Setup - YouTube, url='https://www.youtube.com/embed/tD6fwQyUIJE?si=na1zK5OISsE4N5Vg'
				[a30] link Photo image of Leon van Zyl, center=(440,5756)
				[a38] link Flowise AI Tutorial #1 - Introduction & Setup, center=(585,5757), url='https://www.youtube.com/watch?v=tD6fwQyUIJE'
				[a68] button More, center=(724,5750), hasPopup='menu'
					image
				[a79] button Play, center=(584,5823)
					image
				generic, atomic
		Iframe
			RootWebArea How to Build an AI Document Chatbot in 10 Minutes - YouTube, url='https://www.youtube.com/embed/riXpu1tHzl0?si=KLVQ9TRUcZCTjXuj'
				[b30] link Photo image of Dave Ebbelaar, center=(816,5756)
				[b38] link How to Build an AI Document Chatbot in 10 Minutes, center=(961,5757), url='https://www.youtube.com/watch?v=riXpu1tHzl0'
				[b68] button More, center=(1100,5750), hasPopup='menu'
					image
				[b79] button Play, center=(960,5823)
					image
				generic, atomic
		Iframe
			RootWebArea Flowise is an open source no-code UI visual tool to build 🦜🔗LangChain applications - YouTube, url='https://www.youtube.com/embed/CovAPtQPU0k?si=KcH3ttNubGtp03Za'
				[c30] link Photo image of Cobus Greyling, center=(1192,5756)
				[c38] link Flowise is an open source no-code UI visual tool to build 🦜🔗LangChain applications, center=(1337,5757), url='https://www.youtube.com/watch?v=CovAPtQPU0k'
				[c68] button More, center=(1476,5750), hasPopup='menu'
					image
				[c79] button Play, center=(1336,5823)
					image
				generic, atomic
		Iframe
			RootWebArea Flowise: No Code ChatBot Building Platform: LangChain - YouTube, url='https://www.youtube.com/embed/Q7_dKkosJY4?si=O0swoActrfHlDFSN'
				[d30] link Photo image of Prompt Engineering, center=(440,5978)
				[d38] link Flowise: No Code ChatBot Building Platform: LangChain, center=(585,5979), url='https://www.youtube.com/watch?v=Q7_dKkosJY4'
				[d68] button More, center=(724,5972), hasPopup='menu'
					image
				[d79] button Play, center=(584,6045)
					image
				generic, atomic
		Iframe
			RootWebArea Build a No-Code Chat-with-PDF LangChain app using Flowise and Bubble - YouTube, url='https://www.youtube.com/embed/kOwmPe8aLAA?si=gBaUlkyFOe3TS2V-'
				[e30] link Photo image of AI with Misbah, center=(816,5978)
				[e38] link Build a No-Code Chat-with-PDF LangChain app using Flowise and Bubble, center=(961,5979), url='https://www.youtube.com/watch?v=kOwmPe8aLAA'
				[e68] button More, center=(1100,5972), hasPopup='menu'
					image
				[e79] button Play, center=(960,6045)
					image
				generic, atomic
		Iframe
			RootWebArea Flowise AI: Create LLM Apps with NO Code - FREE Opensource LangChain Apps - YouTube, url='https://www.youtube.com/embed/kvvBUz0q-6I?si=WtrfQ948R1c2dHpf'
				[f30] link Photo image of WorldofAI, center=(1192,5978)
				[f38] link Flowise AI: Create LLM Apps with NO Code - FREE Opensource LangChain Apps, center=(1337,5979), url='https://www.youtube.com/watch?v=kvvBUz0q-6I'
				[f68] button More, center=(1476,5972), hasPopup='menu'
					image
				[f79] button Play, center=(1336,6045)
					image
				generic, atomic
		article
			link Siddhant Gupta, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
				image Siddhant Gupta, url='https://pbs.twimg.com/profile_images/1761449475883835392/yYkjTFPr_normal.jpg'
			link Siddhant Gupta Verified account, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
				image Verified account
			link @Siddhan65490545, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=Siddhan65490545'
			link View on Twitter, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
			paragraph
				StaticText Finally after a month of relentless trial and error, I've successfully created an AI persona bot emulating the teaching style of my mentor
				link @abnux, url='https://twitter.com/abnux'
				StaticText ,  the founder of
				link @10kdesigners, url='https://twitter.com/10kdesigners'
				StaticText . Excited to share my journey in this twitter thread. 🤖🎨 "Sound on 🎙️🔊"
			button View video on Twitter
			link Watch on Twitter, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
			link 2:43 PM · Oct 10, 2023, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 262 likes, url='https://twitter.com/intent/like?tweet_id=1711754261527458189'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1711754261527458189'
			button Copy link
			link Read 33 replies, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
		article
			link Shubham Saboo, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
				image Shubham Saboo, url='https://pbs.twimg.com/profile_images/1670107849815478273/Q3oUhtHM_normal.jpg'
			link Shubham Saboo Verified account, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
				image Verified account
			link @Saboo_Shubham_, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=Saboo_Shubham_'
			link View on Twitter, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
			paragraph
				StaticText Flowise is trending on GitHub

It's an open-source drag & drop UI tool that lets you build custom LLM apps in just minutes.

Powered by LangChain, it features:
- Ready-to-use app templates
- Conversational agents that remember
- Seamless deployment on cloud platforms
			button View video on Twitter
			link Watch on Twitter, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
			link 4:05 AM · Aug 16, 2023, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 523 likes, url='https://twitter.com/intent/like?tweet_id=1691662432807137623'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1691662432807137623'
			button Copy link
			link Read 18 replies, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
		article
			link Muratcan Koylan, url='https://twitter.com/youraimarketer/status/1710908393265782900'
				image Muratcan Koylan, url='https://pbs.twimg.com/profile_images/1847174349335257088/cGzzFLOo_normal.jpg'
			link Muratcan Koylan Verified account, url='https://twitter.com/youraimarketer/status/1710908393265782900'
				image Verified account
			link @youraimarketer, url='https://twitter.com/youraimarketer/status/1710908393265782900'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=youraimarketer'
			link View on Twitter, url='https://twitter.com/youraimarketer/status/1710908393265782900'
			paragraph
				StaticText When you lose momentum, it's hard to regain it.

But here we go again, building a Personal Cockpit with AI Agents.

I've built a chatbot connected to the internet and various APIs, linking it to multiple workflows and AI agents.

Here's the first demo:

1. AI Newsletter Agent…
			button View video on Twitter
			link Watch on Twitter, url='https://twitter.com/youraimarketer/status/1710908393265782900'
			link 6:42 AM · Oct 8, 2023, url='https://twitter.com/youraimarketer/status/1710908393265782900'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 468 likes, url='https://twitter.com/intent/like?tweet_id=1710908393265782900'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1710908393265782900'
			button Copy link
			link Read 17 replies, url='https://twitter.com/youraimarketer/status/1710908393265782900'
		article
			link Eugene, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
				image Eugene, url='https://pbs.twimg.com/profile_images/1501559855865339914/1FzvS9lb_normal.jpg'
			link Eugene, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
			link @sudo_eugene, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=sudo_eugene'
			link View on Twitter, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
			paragraph
				StaticText Using our new AI bot called Koos with
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText to create project management tasks in Notion, right from Slack 🤯

Let me know who would like to see a 5min explainer on how we did this 🎉
			link Image, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
				image Image, url='https://pbs.twimg.com/media/F6dMWW-WsAAUR7d?format=jpg&name=small'
			link Image, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
				image Image, url='https://pbs.twimg.com/media/F6dMWW_XgAEfotx?format=jpg&name=small'
			link 8:39 AM · Sep 20, 2023, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 16 likes, url='https://twitter.com/intent/like?tweet_id=1704414944551125293'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1704414944551125293'
			button Copy link
			link Read 8 replies, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
		article
			link Lior⚡, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
				image Lior⚡, url='https://pbs.twimg.com/profile_images/1817166841992597504/zLRK5Qx__normal.jpg'
			link Lior⚡ Verified account, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
				image Verified account
			link @LiorOnAI, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=LiorOnAI'
			link View on Twitter, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
			paragraph
				StaticText Flowise just reached 12,000 stars on Github. 

It allows you to build customized LLM apps using a simple drag & drop UI.

You can even use built-in templates with logic and conditions connected to LangChain and GPT:

▸ Conversational agent with memory
▸ Chat with PDF and Excel…
			button View video on Twitter
			link Watch on Twitter, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
			link 4:33 PM · Aug 10, 2023, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 836 likes, url='https://twitter.com/intent/like?tweet_id=1689676278746529793'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1689676278746529793'
			button Copy link
			link Read 30 replies, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
		article
			link Derek Cheung, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
				image Derek Cheung, url='https://pbs.twimg.com/profile_images/1653155172414046209/-_tpBZHC_normal.jpg'
			link Derek Cheung Verified account, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
				image Verified account
			link @derekcheungsa, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=derekcheungsa'
			link View on Twitter, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
			paragraph
				StaticText A multi-modal chatbot that effortlessly merges text and image generation into seamless conversations. 🚀

📢 Watch the demo with conversation starting with asking for advice on building strong financial habits (sped up slightly for demo)
 🪄Chatbot magically generates a visual…
			button View video on Twitter
			link Watch on Twitter, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
			link 3:11 AM · Oct 2, 2023, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 21 likes, url='https://twitter.com/intent/like?tweet_id=1708681200661889447'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1708681200661889447'
			button Copy link
			link Read 4 replies, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
		article
			link armand, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
				image armand, url='https://pbs.twimg.com/profile_images/1758729285744091136/9nZk7KcA_normal.jpg'
			link armand Verified account, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
				image Verified account
			link @armand_ruiz, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=armand_ruiz'
			link View on Twitter, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
			paragraph
				StaticText Create your first custom chatbot using LLMs in 5 min!

No-coding required. We will use
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText Join here to get the step-by-step tutorial and video tomorrow at 7 a.m. ET:
				link nocode.ai, url='https://www.nocode.ai/'
			link Image, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
				image Image, url='https://pbs.twimg.com/media/F4ZG8HwaEAAhSE9?format=jpg&name=small'
			link 5:06 PM · Aug 25, 2023, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 13 likes, url='https://twitter.com/intent/like?tweet_id=1695120505945383161'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1695120505945383161'
			button Copy link
			link Read 3 replies, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
		article
			link Alessio Pomaro, url='https://twitter.com/alepom/status/1694599974716153904'
				image Alessio Pomaro, url='https://pbs.twimg.com/profile_images/1350189157931479041/LaWfQ0IQ_normal.jpg'
			link Alessio Pomaro, url='https://twitter.com/alepom/status/1694599974716153904'
			link @alepom, url='https://twitter.com/alepom/status/1694599974716153904'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=alepom'
			link View on Twitter, url='https://twitter.com/alepom/status/1694599974716153904'
			paragraph
				StaticText 🧠 Realizzare un
				link #chatbot, url='https://twitter.com/hashtag/chatbot'
				StaticText o una ricerca evoluta per un sito web: quanto sarebbe stato complesso un paio d'anni fa? Tanto. Pochi servizi erano davvero efficienti. 
🦾 Nelle immagini si vede un'esempio di come l'ho creato con
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText .
				link #AI, url='https://twitter.com/hashtag/AI'
				link #Flowise, url='https://twitter.com/hashtag/Flowise'
				link #LLaMA2, url='https://twitter.com/hashtag/LLaMA2'
				link #Claude, url='https://twitter.com/hashtag/Claude'
			link Image, url='https://twitter.com/alepom/status/1694599974716153904'
				image Image, url='https://pbs.twimg.com/media/F4RtrXGWQAAdnSg?format=jpg&name=small'
			link Image, url='https://twitter.com/alepom/status/1694599974716153904'
				image Image, url='https://pbs.twimg.com/media/F4RtrygWUAAFCua?format=jpg&name=small'
			link Image, url='https://twitter.com/alepom/status/1694599974716153904'
				image Image, url='https://pbs.twimg.com/media/F4RtsJjXIAAJOhx?format=jpg&name=small'
			link Image, url='https://twitter.com/alepom/status/1694599974716153904'
				image Image, url='https://pbs.twimg.com/media/F4RtscNXgAAMGhu?format=png&name=small'
			link 6:38 AM · Aug 24, 2023, url='https://twitter.com/alepom/status/1694599974716153904'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 7 likes, url='https://twitter.com/intent/like?tweet_id=1694599974716153904'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1694599974716153904'
			button Copy link
			link Read 2 replies, url='https://twitter.com/alepom/status/1694599974716153904'
		article
			link John Damask, url='https://twitter.com/jbdamask/status/1693777249009373584'
				image John Damask, url='https://pbs.twimg.com/profile_images/1688209206204121093/9iNcGQoo_normal.jpg'
			link John Damask Verified account, url='https://twitter.com/jbdamask/status/1693777249009373584'
				image Verified account
			link @jbdamask, url='https://twitter.com/jbdamask/status/1693777249009373584'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=jbdamask'
			link View on Twitter, url='https://twitter.com/jbdamask/status/1693777249009373584'
			paragraph
				StaticText Flowise is seriously impressive. Not only for quickly building and deploying LLM apps, but for visualizing chains
			link 12:08 AM · Aug 22, 2023, url='https://twitter.com/jbdamask/status/1693777249009373584'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 9 likes, url='https://twitter.com/intent/like?tweet_id=1693777249009373584'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1693777249009373584'
			button Copy link
			link Read 3 replies, url='https://twitter.com/jbdamask/status/1693777249009373584'
		article
			link Abu Mu'aaz, url='https://twitter.com/abumuaaz/status/1693448039594381481'
				image Abu Mu'aaz, url='https://pbs.twimg.com/profile_images/1396343945190285314/brEgb4B9_normal.jpg'
			link Abu Mu'aaz, url='https://twitter.com/abumuaaz/status/1693448039594381481'
			link @abumuaaz, url='https://twitter.com/abumuaaz/status/1693448039594381481'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=abumuaaz'
			link View on Twitter, url='https://twitter.com/abumuaaz/status/1693448039594381481'
			paragraph
				StaticText Thanks to
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText &
				link @LangChainAI, url='https://twitter.com/LangChainAI'
				StaticText , it's so easy to create Telegram Bot that capable of getting real-time bus info (location & speed) from GPS device. Plus more functionality to calculate distance, duration & presenting map to user.
				link @OpenAI, url='https://twitter.com/OpenAI'
				StaticText Function Calling is awesome too 👍
			link Image, url='https://twitter.com/abumuaaz/status/1693448039594381481'
				image Image, url='https://pbs.twimg.com/media/F4BToWubcAANu1L?format=jpg&name=small'
			link Image, url='https://twitter.com/abumuaaz/status/1693448039594381481'
				image Image, url='https://pbs.twimg.com/media/F4BTptvbgAIc_hK?format=jpg&name=small'
			link 2:20 AM · Aug 21, 2023, url='https://twitter.com/abumuaaz/status/1693448039594381481'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 16 likes, url='https://twitter.com/intent/like?tweet_id=1693448039594381481'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1693448039594381481'
			button Copy link
			link Read 3 replies, url='https://twitter.com/abumuaaz/status/1693448039594381481'
		article
			link Wayne Culbreth, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
				image Wayne Culbreth, url='https://pbs.twimg.com/profile_images/1622684462587777037/_SDI7qtQ_normal.png'
			link Wayne Culbreth Verified account, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
				image Verified account
			link @wayne_culbreth, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=wayne_culbreth'
			link View on Twitter, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
			paragraph
				StaticText If you are building in AI and not using
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText - you are seriously wasting your time. It's like Figma but for backend AI applications. Design & test your entire stack in less than an hour. Even test MVP. Build to industrial scale with the exported output.
			link 6:56 PM · Aug 19, 2023, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 11 likes, url='https://twitter.com/intent/like?tweet_id=1692973803188392402'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1692973803188392402'
			button Copy link
			link Read 2 replies, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
		article
			link Damian Soto, url='https://twitter.com/sotoplatero/status/1692286497850855494'
				image Damian Soto, url='https://pbs.twimg.com/profile_images/1872860928502349824/HItLB9zt_normal.jpg'
			link Damian Soto, url='https://twitter.com/sotoplatero/status/1692286497850855494'
			link @sotoplatero, url='https://twitter.com/sotoplatero/status/1692286497850855494'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=sotoplatero'
			link View on Twitter, url='https://twitter.com/sotoplatero/status/1692286497850855494'
			paragraph
				StaticText Chatea Gratis con tus PDF sin código !!!

En este hilo te muestro como crear un chat gpt personalizado sin una linea de código que puedes incluir en tu web

Usamos
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText que es una increíble herramienta para crear aplicaciones LLM con
				link #nocode, url='https://twitter.com/hashtag/nocode'
				StaticText .

Empezamos🧵
			link Image, url='https://twitter.com/sotoplatero/status/1692286497850855494'
				image Image, url='https://pbs.twimg.com/media/F3w1mbEWUAQPpmL?format=jpg&name=small'
			link 9:25 PM · Aug 17, 2023, url='https://twitter.com/sotoplatero/status/1692286497850855494'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 22 likes, url='https://twitter.com/intent/like?tweet_id=1692286497850855494'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1692286497850855494'
			button Copy link
			link Read 2 replies, url='https://twitter.com/sotoplatero/status/1692286497850855494'
		article
			link VerySmallWoods, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
				image VerySmallWoods, url='https://pbs.twimg.com/profile_images/1600964189731934222/eWMb0-L2_normal.jpg'
			link VerySmallWoods Verified account, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
				image Verified account
			link @verysmallwoods, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=verysmallwoods'
			link View on Twitter, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
			paragraph
				StaticText AutoGen = LLM多代理框架 👨‍👩‍👧‍👦
Flowise = 无代码LLM工作流构建平台 0️⃣

由
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText 负责构建功能单元；由AutoGen负责调度协作，任务执行。

嗯！有点美妙！
🎏 🎀 🪄 🪅 🎊 🎉

AutoGen + Flowise = 零代码平台上的超级AI助理 

视频 👇
				link youtu.be/gKNR1ghU1Ao?si…, url='https://youtu.be/gKNR1ghU1Ao?si=ZI9jqz3ss51NG8HX'
				link #AutoGen, url='https://twitter.com/hashtag/AutoGen'
				link #Flowise, url='https://twitter.com/hashtag/Flowise'
				link #OpenAI, url='https://twitter.com/hashtag/OpenAI'
				StaticText …
			link 1:05 AM · Oct 22, 2023, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 11 likes, url='https://twitter.com/intent/like?tweet_id=1715897092244189221'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1715897092244189221'
			button Copy link
			link Read more on Twitter, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
		heading Webinars
		paragraph
			StaticText Learn how to use Flowise from different webinar series with our partners
		image How to Build No-Code SQL Chatbots using Flowise, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fsinglestore_webinar_2.94e511f6.jpeg&w=828&q=75'
		image SingleStore, url='https://flowiseai.com/_next/static/media/singlestore.a5b72cb0.svg'
		StaticText How to Build No-Code SQL Chatbots using Flowise
		link Learn More, url='https://memsql.wistia.com/medias/i1ra0jared'
		image LlamaIndex Webinar: Build No-Code RAG with Flowise, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fllamaindex_webinar.a14452aa.png&w=750&q=75'
		image Milvus, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fllamaindex.5ac46e4e.png&w=48&q=75'
		StaticText LlamaIndex Webinar: Build No-Code RAG with Flowise
		link Learn More, url='https://youtu.be/k5Txq5C_AWA?si=5oqbNBvqP1BEcpVm'
		image How to Build a NoCode AWS Bedrock LLM App on Flowise, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fsinglestore_aws_webinar.185bcd9c.png&w=1080&q=75'
		image SingleStore, url='https://flowiseai.com/_next/static/media/singlestore.a5b72cb0.svg'
		image AWS, url='https://flowiseai.com/_next/static/media/aws.c9a4034b.svg'
		StaticText How to Build a NoCode AWS Bedrock LLM App on Flowise
		link Learn More, url='https://memsql.wistia.com/medias/y230cbhxb0?utm_medium=email&utm_source=singlestore&utm_campaign=7014X0000029ZgFQAU&campaignid=7014X0000029ZgFQAU'
		image Drag and Drop LLMs: Simplifying RAG with FlowiseAI and Milvus, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fmilvus_webinar.0165f039.png&w=828&q=75'
		image Milvus, url='https://flowiseai.com/_next/static/media/milvus.1ae32e3c.svg'
		StaticText Drag and Drop LLMs: Simplifying RAG with FlowiseAI and Milvus
		link Learn More, url='https://youtu.be/OeloMm8SdMc?si=R1sdxako6YM857MT'
		image LangChain Low-Code/No-Code Webinar, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Flangchainwebinar.2f5914b2.png&w=640&q=75'
		image Langchain, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Flangchain.c1e79304.png&w=48&q=75'
		StaticText LangChain Weekly Webinar - Low-Code/No-Code LLM
		link Learn More, url='https://youtu.be/qWv2vyOX0tk?si=-SJM5Z7UvYlOdUhG'
		heading Enterprise
		paragraph
			StaticText Looking for specific use cases and support?
		link Lets Chat, url='mailto:hello@flowiseai.com'
	contentinfo
		list
			listitem
				link Terms of Service, url='https://flowiseai.com/terms'
			listitem
				link Privacy Policy, url='https://flowiseai.com/privacy'
			listitem
				link Twitter, url='https://twitter.com/FlowiseAI'
					image
			listitem
				link Github, url='https://github.com/FlowiseAI/Flowise'
					image
			listitem
				link Linkedin, url='https://www.linkedin.com/company/flowiseai'
					image
		StaticText © FlowiseAI Inc. All rights reserved.
	alert, atomic
```
</details>



```
RootWebArea Flowise - Low code LLM Apps Builder, focused, url='https://flowiseai.com/#usecases'
	banner
		link Flowise, url='https://flowiseai.com/'
			image Flowise, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Flogo-color-high.e60de2f8.png&w=256&q=75'
		link Star FlowiseAI/Flowise on GitHub, url='https://github.com/FlowiseAI/Flowise'
```
<details><summary>Show more</summary>

```
		link 33609 stargazers on GitHub, url='https://github.com/FlowiseAI/Flowise/stargazers'
			StaticText 33,609
		navigation
			list
				listitem
					link Features, url='https://flowiseai.com/#features'
				listitem
					link Use Cases, url='https://flowiseai.com/#usecases'
				listitem
					link Pricing, url='https://flowiseai.com/#pricing'
				listitem
					link Community, url='https://flowiseai.com/#community'
				listitem
					link Webinars, url='https://flowiseai.com/#webinars'
				listitem
					link Login, url='https://flowiseai.com/auth/login'
						button Login
				listitem
					link Request Access, url='https://flowiseai.com/join'
						button Request Access
							image
	main
		heading Build LLM Apps
		heading Easily
		paragraph
			StaticText Open source low-code tool for developers to build customized LLM orchestration flow & AI agents
		link Request Access, url='https://flowiseai.com/join'
			button Request Access
				image
		link Documentation, url='https://docs.flowiseai.com/'
			button Documentation
		StaticText Backed by
		image YCombinator, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2FYC.dc9b9030.png&w=32&q=75'
		StaticText Combinator
		paragraph
			StaticText Trusted and used by teams around the globe
		image AWS, url='https://flowiseai.com/_next/static/media/aws.c9a4034b.svg'
		image Alibaba, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Falibaba.d717abe3.png&w=128&q=75'
		image Hitachi, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fhitachi.cc8b5524.png&w=64&q=75'
		image ByteDance, url='https://flowiseai.com/_next/static/media/ByteDance.cfa75bfd.svg'
		image Microsoft, url='https://flowiseai.com/_next/static/media/microsoft.0e14c6cf.svg'
		image InsightSoftware, url='https://flowiseai.com/_next/static/media/insightsoftware.c5783e21.svg'
		image Google, url='https://flowiseai.com/_next/static/media/google.c43e43a7.svg'
		image Accenture, url='https://flowiseai.com/_next/static/media/accenture.3222125e.svg'
		image ERoad, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Feroad.ea8bab6e.png&w=64&q=75'
		image AWS, url='https://flowiseai.com/_next/static/media/aws.c9a4034b.svg'
		image Alibaba, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Falibaba.d717abe3.png&w=128&q=75'
		image Hitachi, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fhitachi.cc8b5524.png&w=64&q=75'
		image ByteDance, url='https://flowiseai.com/_next/static/media/ByteDance.cfa75bfd.svg'
		image Microsoft, url='https://flowiseai.com/_next/static/media/microsoft.0e14c6cf.svg'
		image InsightSoftware, url='https://flowiseai.com/_next/static/media/insightsoftware.c5783e21.svg'
		image Google, url='https://flowiseai.com/_next/static/media/google.c43e43a7.svg'
		image Accenture, url='https://flowiseai.com/_next/static/media/accenture.3222125e.svg'
		image ERoad, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Feroad.ea8bab6e.png&w=64&q=75'
		heading Iterate, fast
		paragraph
			StaticText Developing LLM apps takes countless iterations. With low code approach, we enable quick iterations to go from testing to production
		list
			listitem
				StaticText $
				StaticText npm install -g flowise
			listitem
				StaticText $
				StaticText npx flowise start
		link Get Started, url='https://docs.flowiseai.com/getting-started'
		image Features 01, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fintegrations1.8181abd6.png&w=640&q=75'
		StaticText Chatflow
		heading LLM Orchestration
		paragraph
			StaticText Connect LLMs with memory, data loaders, cache, moderation and many more
		list
			listitem
				image
				StaticText Langchain
			listitem
				image
				StaticText LlamaIndex
			listitem
				image
				StaticText 100+ integrations
		StaticText Agents
		heading Agents & Assistants
		paragraph
			StaticText Create autonomous agent that can uses tools to execute different tasks
		list
			listitem
				image
				StaticText Custom Tools
			listitem
				image
				StaticText OpenAI Assistant
			listitem
				image
				StaticText Function Agent
		list
			listitem
				StaticText import
				StaticText requests
			listitem
			listitem
				StaticText url
				StaticText =
				StaticText "/api/v1/prediction/:id"
			listitem
			listitem
				StaticText def
				StaticText query
				StaticText (
				StaticText payload
				StaticText )
				StaticText :
			listitem
				StaticText response
				StaticText =
				StaticText requests.post
				StaticText (
			listitem
				StaticText url,
			listitem
				StaticText json
				StaticText =
				StaticText payload
			listitem
				StaticText )
			listitem
				StaticText return
				StaticText response.json
				StaticText (
				StaticText )
			listitem
			listitem
				StaticText output
				StaticText =
				StaticText query
				StaticText (
				StaticText {
			listitem
				StaticText question
				StaticText :
				StaticText "hello!"
			listitem
				StaticText )
				StaticText }
		StaticText Developer Friendly
		heading API, SDK, Embed
		paragraph
			StaticText Extend and integrate to your applications using APIs, SDK and Embedded Chat
		list
			listitem
				image
				StaticText APIs
			listitem
				image
				StaticText Embedded Widget
			listitem
				image
				StaticText React SDK
		image Features 02, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fopensource.bed900d8.png&w=640&q=75'
		StaticText Platform Agnostic
		heading Open source LLMs
		paragraph
			StaticText Run in air-gapped environment with local LLMs, embeddings and vector databases
		list
			listitem
				image
				StaticText HuggingFace, Ollama, LocalAI, Replicate
			listitem
				image
				StaticText Llama2, Mistral, Vicuna, Orca, Llava
			listitem
				image
				StaticText Self host on AWS, Azure, GCP
		heading Use Cases
		paragraph
			StaticText One platform, endless possibilities. See some of the use cases
		[309] button Product Catalog, center=(518,3756), focused
		[310] button Product Description, center=(739,3756)
		[311] button Query SQL Database, center=(960,3756)
		[312] button Customer Support, center=(1181,3756)
		[313] button Structured Data, center=(1402,3756)
		paragraph
			StaticText Product catalog chatbot to answer any questions related to the products
		image ProductCatalog, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fproductcatalog.9d6b9124.png&w=1920&q=75'
		heading Pricing
		paragraph
			StaticText Free 14 day trial. No credit card required.
		heading Starter
		paragraph
			StaticText For individuals & small teams
		paragraph
			StaticText $35
			StaticText /month
		list
			listitem
				image
				StaticText 10,000 Predictions / month
				button
					image
				StaticText then $0.001 per prediction
			listitem
				image
				StaticText 1GB Storage
				button
					image
			listitem
				image
				StaticText Database Backup
			listitem
				image
				StaticText 1 Week Log Retention
			listitem
				image
				StaticText Evaluations & Metrics
			listitem
				image
				StaticText Custom Chatbot Branding
				button
					image
			listitem
				image
				StaticText Community Support
		link Start free trial, url='https://flowiseai.com/join'
			button Start free trial
		heading Pro
		paragraph
			StaticText For medium-sized businesses
		paragraph
			StaticText $65
			StaticText /month
		list
			listitem
				image
				StaticText Everything in Starter
			listitem
				image
				StaticText 50,000 Predictions / month
				button
					image
				StaticText then $0.001 per prediction
			listitem
				image
				StaticText 10GB Storage
				button
					image
			listitem
				image
				StaticText Unlimited Workspaces
			listitem
				image
				StaticText Admin Roles & Permissions
			listitem
				image
				StaticText 3 Months Log Retention
			listitem
				image
				StaticText Priority Support
		button Coming Soon, disabled=True
		heading Enterprise
		paragraph
			StaticText For large organizations
		paragraph
			StaticText Contact Us
		list
			listitem
				image
				StaticText On-Premise Deployment
			listitem
				image
				StaticText Air-gapped Environments
			listitem
				image
				StaticText SSO & SAML
			listitem
				image
				StaticText LDAP & RBAC
			listitem
				image
				StaticText Versioning
			listitem
				image
				StaticText Audit Logs
			listitem
				image
				StaticText 99.99% Uptime SLA
		link Contact Us, url='mailto:hello@flowiseai.com'
			button Contact Us
		heading Community 🫶
		paragraph
			StaticText Open source community is the heart of Flowise. See why developers love and build using Flowise
		link Join Discord, url='https://discord.gg/jbaHfsRVBW'
			image
		Iframe
			RootWebArea Flowise AI Tutorial #1 - Introduction & Setup - YouTube, url='https://www.youtube.com/embed/tD6fwQyUIJE?si=na1zK5OISsE4N5Vg'
				[a30] link Photo image of Leon van Zyl, center=(440,5756)
				[a38] link Flowise AI Tutorial #1 - Introduction & Setup, center=(585,5757), url='https://www.youtube.com/watch?v=tD6fwQyUIJE'
				[a68] button More, center=(724,5750), hasPopup='menu'
					image
				[a79] button Play, center=(584,5823)
					image
				generic, atomic
		Iframe
			RootWebArea How to Build an AI Document Chatbot in 10 Minutes - YouTube, url='https://www.youtube.com/embed/riXpu1tHzl0?si=KLVQ9TRUcZCTjXuj'
				[b30] link Photo image of Dave Ebbelaar, center=(816,5756)
				[b38] link How to Build an AI Document Chatbot in 10 Minutes, center=(961,5757), url='https://www.youtube.com/watch?v=riXpu1tHzl0'
				[b68] button More, center=(1100,5750), hasPopup='menu'
					image
				[b79] button Play, center=(960,5823)
					image
				generic, atomic
		Iframe
			RootWebArea Flowise is an open source no-code UI visual tool to build 🦜🔗LangChain applications - YouTube, url='https://www.youtube.com/embed/CovAPtQPU0k?si=KcH3ttNubGtp03Za'
				[c30] link Photo image of Cobus Greyling, center=(1192,5756)
				[c38] link Flowise is an open source no-code UI visual tool to build 🦜🔗LangChain applications, center=(1337,5757), url='https://www.youtube.com/watch?v=CovAPtQPU0k'
				[c68] button More, center=(1476,5750), hasPopup='menu'
					image
				[c79] button Play, center=(1336,5823)
					image
				generic, atomic
		Iframe
			RootWebArea Flowise: No Code ChatBot Building Platform: LangChain - YouTube, url='https://www.youtube.com/embed/Q7_dKkosJY4?si=O0swoActrfHlDFSN'
				[d30] link Photo image of Prompt Engineering, center=(440,5978)
				[d38] link Flowise: No Code ChatBot Building Platform: LangChain, center=(585,5979), url='https://www.youtube.com/watch?v=Q7_dKkosJY4'
				[d68] button More, center=(724,5972), hasPopup='menu'
					image
				[d79] button Play, center=(584,6045)
					image
				generic, atomic
		Iframe
			RootWebArea Build a No-Code Chat-with-PDF LangChain app using Flowise and Bubble - YouTube, url='https://www.youtube.com/embed/kOwmPe8aLAA?si=gBaUlkyFOe3TS2V-'
				[e30] link Photo image of AI with Misbah, center=(816,5978)
				[e38] link Build a No-Code Chat-with-PDF LangChain app using Flowise and Bubble, center=(961,5979), url='https://www.youtube.com/watch?v=kOwmPe8aLAA'
				[e68] button More, center=(1100,5972), hasPopup='menu'
					image
				[e79] button Play, center=(960,6045)
					image
				generic, atomic
		Iframe
			RootWebArea Flowise AI: Create LLM Apps with NO Code - FREE Opensource LangChain Apps - YouTube, url='https://www.youtube.com/embed/kvvBUz0q-6I?si=WtrfQ948R1c2dHpf'
				[f30] link Photo image of WorldofAI, center=(1192,5978)
				[f38] link Flowise AI: Create LLM Apps with NO Code - FREE Opensource LangChain Apps, center=(1337,5979), url='https://www.youtube.com/watch?v=kvvBUz0q-6I'
				[f68] button More, center=(1476,5972), hasPopup='menu'
					image
				[f79] button Play, center=(1336,6045)
					image
				generic, atomic
		article
			link Siddhant Gupta, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
				image Siddhant Gupta, url='https://pbs.twimg.com/profile_images/1761449475883835392/yYkjTFPr_normal.jpg'
			link Siddhant Gupta Verified account, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
				image Verified account
			link @Siddhan65490545, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=Siddhan65490545'
			link View on Twitter, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
			paragraph
				StaticText Finally after a month of relentless trial and error, I've successfully created an AI persona bot emulating the teaching style of my mentor
				link @abnux, url='https://twitter.com/abnux'
				StaticText ,  the founder of
				link @10kdesigners, url='https://twitter.com/10kdesigners'
				StaticText . Excited to share my journey in this twitter thread. 🤖🎨 "Sound on 🎙️🔊"
			button View video on Twitter
			link Watch on Twitter, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
			link 2:43 PM · Oct 10, 2023, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 262 likes, url='https://twitter.com/intent/like?tweet_id=1711754261527458189'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1711754261527458189'
			button Copy link
			link Read 33 replies, url='https://twitter.com/Siddhan65490545/status/1711754261527458189'
		article
			link Shubham Saboo, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
				image Shubham Saboo, url='https://pbs.twimg.com/profile_images/1670107849815478273/Q3oUhtHM_normal.jpg'
			link Shubham Saboo Verified account, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
				image Verified account
			link @Saboo_Shubham_, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=Saboo_Shubham_'
			link View on Twitter, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
			paragraph
				StaticText Flowise is trending on GitHub

It's an open-source drag & drop UI tool that lets you build custom LLM apps in just minutes.

Powered by LangChain, it features:
- Ready-to-use app templates
- Conversational agents that remember
- Seamless deployment on cloud platforms
			button View video on Twitter
			link Watch on Twitter, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
			link 4:05 AM · Aug 16, 2023, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 523 likes, url='https://twitter.com/intent/like?tweet_id=1691662432807137623'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1691662432807137623'
			button Copy link
			link Read 18 replies, url='https://twitter.com/Saboo_Shubham_/status/1691662432807137623'
		article
			link Muratcan Koylan, url='https://twitter.com/youraimarketer/status/1710908393265782900'
				image Muratcan Koylan, url='https://pbs.twimg.com/profile_images/1847174349335257088/cGzzFLOo_normal.jpg'
			link Muratcan Koylan Verified account, url='https://twitter.com/youraimarketer/status/1710908393265782900'
				image Verified account
			link @youraimarketer, url='https://twitter.com/youraimarketer/status/1710908393265782900'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=youraimarketer'
			link View on Twitter, url='https://twitter.com/youraimarketer/status/1710908393265782900'
			paragraph
				StaticText When you lose momentum, it's hard to regain it.

But here we go again, building a Personal Cockpit with AI Agents.

I've built a chatbot connected to the internet and various APIs, linking it to multiple workflows and AI agents.

Here's the first demo:

1. AI Newsletter Agent…
			button View video on Twitter
			link Watch on Twitter, url='https://twitter.com/youraimarketer/status/1710908393265782900'
			link 6:42 AM · Oct 8, 2023, url='https://twitter.com/youraimarketer/status/1710908393265782900'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 468 likes, url='https://twitter.com/intent/like?tweet_id=1710908393265782900'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1710908393265782900'
			button Copy link
			link Read 17 replies, url='https://twitter.com/youraimarketer/status/1710908393265782900'
		article
			link Eugene, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
				image Eugene, url='https://pbs.twimg.com/profile_images/1501559855865339914/1FzvS9lb_normal.jpg'
			link Eugene, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
			link @sudo_eugene, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=sudo_eugene'
			link View on Twitter, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
			paragraph
				StaticText Using our new AI bot called Koos with
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText to create project management tasks in Notion, right from Slack 🤯

Let me know who would like to see a 5min explainer on how we did this 🎉
			link Image, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
				image Image, url='https://pbs.twimg.com/media/F6dMWW-WsAAUR7d?format=jpg&name=small'
			link Image, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
				image Image, url='https://pbs.twimg.com/media/F6dMWW_XgAEfotx?format=jpg&name=small'
			link 8:39 AM · Sep 20, 2023, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 16 likes, url='https://twitter.com/intent/like?tweet_id=1704414944551125293'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1704414944551125293'
			button Copy link
			link Read 8 replies, url='https://twitter.com/sudo_eugene/status/1704414944551125293'
		article
			link Lior⚡, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
				image Lior⚡, url='https://pbs.twimg.com/profile_images/1817166841992597504/zLRK5Qx__normal.jpg'
			link Lior⚡ Verified account, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
				image Verified account
			link @LiorOnAI, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=LiorOnAI'
			link View on Twitter, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
			paragraph
				StaticText Flowise just reached 12,000 stars on Github. 

It allows you to build customized LLM apps using a simple drag & drop UI.

You can even use built-in templates with logic and conditions connected to LangChain and GPT:

▸ Conversational agent with memory
▸ Chat with PDF and Excel…
			button View video on Twitter
			link Watch on Twitter, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
			link 4:33 PM · Aug 10, 2023, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 836 likes, url='https://twitter.com/intent/like?tweet_id=1689676278746529793'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1689676278746529793'
			button Copy link
			link Read 30 replies, url='https://twitter.com/LiorOnAI/status/1689676278746529793'
		article
			link Derek Cheung, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
				image Derek Cheung, url='https://pbs.twimg.com/profile_images/1653155172414046209/-_tpBZHC_normal.jpg'
			link Derek Cheung Verified account, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
				image Verified account
			link @derekcheungsa, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=derekcheungsa'
			link View on Twitter, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
			paragraph
				StaticText A multi-modal chatbot that effortlessly merges text and image generation into seamless conversations. 🚀

📢 Watch the demo with conversation starting with asking for advice on building strong financial habits (sped up slightly for demo)
 🪄Chatbot magically generates a visual…
			button View video on Twitter
			link Watch on Twitter, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
			link 3:11 AM · Oct 2, 2023, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 21 likes, url='https://twitter.com/intent/like?tweet_id=1708681200661889447'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1708681200661889447'
			button Copy link
			link Read 4 replies, url='https://twitter.com/derekcheungsa/status/1708681200661889447'
		article
			link armand, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
				image armand, url='https://pbs.twimg.com/profile_images/1758729285744091136/9nZk7KcA_normal.jpg'
			link armand Verified account, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
				image Verified account
			link @armand_ruiz, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=armand_ruiz'
			link View on Twitter, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
			paragraph
				StaticText Create your first custom chatbot using LLMs in 5 min!

No-coding required. We will use
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText Join here to get the step-by-step tutorial and video tomorrow at 7 a.m. ET:
				link nocode.ai, url='https://www.nocode.ai/'
			link Image, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
				image Image, url='https://pbs.twimg.com/media/F4ZG8HwaEAAhSE9?format=jpg&name=small'
			link 5:06 PM · Aug 25, 2023, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 13 likes, url='https://twitter.com/intent/like?tweet_id=1695120505945383161'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1695120505945383161'
			button Copy link
			link Read 3 replies, url='https://twitter.com/armand_ruiz/status/1695120505945383161'
		article
			link Alessio Pomaro, url='https://twitter.com/alepom/status/1694599974716153904'
				image Alessio Pomaro, url='https://pbs.twimg.com/profile_images/1350189157931479041/LaWfQ0IQ_normal.jpg'
			link Alessio Pomaro, url='https://twitter.com/alepom/status/1694599974716153904'
			link @alepom, url='https://twitter.com/alepom/status/1694599974716153904'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=alepom'
			link View on Twitter, url='https://twitter.com/alepom/status/1694599974716153904'
			paragraph
				StaticText 🧠 Realizzare un
				link #chatbot, url='https://twitter.com/hashtag/chatbot'
				StaticText o una ricerca evoluta per un sito web: quanto sarebbe stato complesso un paio d'anni fa? Tanto. Pochi servizi erano davvero efficienti. 
🦾 Nelle immagini si vede un'esempio di come l'ho creato con
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText .
				link #AI, url='https://twitter.com/hashtag/AI'
				link #Flowise, url='https://twitter.com/hashtag/Flowise'
				link #LLaMA2, url='https://twitter.com/hashtag/LLaMA2'
				link #Claude, url='https://twitter.com/hashtag/Claude'
			link Image, url='https://twitter.com/alepom/status/1694599974716153904'
				image Image, url='https://pbs.twimg.com/media/F4RtrXGWQAAdnSg?format=jpg&name=small'
			link Image, url='https://twitter.com/alepom/status/1694599974716153904'
				image Image, url='https://pbs.twimg.com/media/F4RtrygWUAAFCua?format=jpg&name=small'
			link Image, url='https://twitter.com/alepom/status/1694599974716153904'
				image Image, url='https://pbs.twimg.com/media/F4RtsJjXIAAJOhx?format=jpg&name=small'
			link Image, url='https://twitter.com/alepom/status/1694599974716153904'
				image Image, url='https://pbs.twimg.com/media/F4RtscNXgAAMGhu?format=png&name=small'
			link 6:38 AM · Aug 24, 2023, url='https://twitter.com/alepom/status/1694599974716153904'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 7 likes, url='https://twitter.com/intent/like?tweet_id=1694599974716153904'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1694599974716153904'
			button Copy link
			link Read 2 replies, url='https://twitter.com/alepom/status/1694599974716153904'
		article
			link John Damask, url='https://twitter.com/jbdamask/status/1693777249009373584'
				image John Damask, url='https://pbs.twimg.com/profile_images/1688209206204121093/9iNcGQoo_normal.jpg'
			link John Damask Verified account, url='https://twitter.com/jbdamask/status/1693777249009373584'
				image Verified account
			link @jbdamask, url='https://twitter.com/jbdamask/status/1693777249009373584'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=jbdamask'
			link View on Twitter, url='https://twitter.com/jbdamask/status/1693777249009373584'
			paragraph
				StaticText Flowise is seriously impressive. Not only for quickly building and deploying LLM apps, but for visualizing chains
			link 12:08 AM · Aug 22, 2023, url='https://twitter.com/jbdamask/status/1693777249009373584'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 9 likes, url='https://twitter.com/intent/like?tweet_id=1693777249009373584'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1693777249009373584'
			button Copy link
			link Read 3 replies, url='https://twitter.com/jbdamask/status/1693777249009373584'
		article
			link Abu Mu'aaz, url='https://twitter.com/abumuaaz/status/1693448039594381481'
				image Abu Mu'aaz, url='https://pbs.twimg.com/profile_images/1396343945190285314/brEgb4B9_normal.jpg'
			link Abu Mu'aaz, url='https://twitter.com/abumuaaz/status/1693448039594381481'
			link @abumuaaz, url='https://twitter.com/abumuaaz/status/1693448039594381481'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=abumuaaz'
			link View on Twitter, url='https://twitter.com/abumuaaz/status/1693448039594381481'
			paragraph
				StaticText Thanks to
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText &
				link @LangChainAI, url='https://twitter.com/LangChainAI'
				StaticText , it's so easy to create Telegram Bot that capable of getting real-time bus info (location & speed) from GPS device. Plus more functionality to calculate distance, duration & presenting map to user.
				link @OpenAI, url='https://twitter.com/OpenAI'
				StaticText Function Calling is awesome too 👍
			link Image, url='https://twitter.com/abumuaaz/status/1693448039594381481'
				image Image, url='https://pbs.twimg.com/media/F4BToWubcAANu1L?format=jpg&name=small'
			link Image, url='https://twitter.com/abumuaaz/status/1693448039594381481'
				image Image, url='https://pbs.twimg.com/media/F4BTptvbgAIc_hK?format=jpg&name=small'
			link 2:20 AM · Aug 21, 2023, url='https://twitter.com/abumuaaz/status/1693448039594381481'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 16 likes, url='https://twitter.com/intent/like?tweet_id=1693448039594381481'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1693448039594381481'
			button Copy link
			link Read 3 replies, url='https://twitter.com/abumuaaz/status/1693448039594381481'
		article
			link Wayne Culbreth, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
				image Wayne Culbreth, url='https://pbs.twimg.com/profile_images/1622684462587777037/_SDI7qtQ_normal.png'
			link Wayne Culbreth Verified account, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
				image Verified account
			link @wayne_culbreth, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=wayne_culbreth'
			link View on Twitter, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
			paragraph
				StaticText If you are building in AI and not using
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText - you are seriously wasting your time. It's like Figma but for backend AI applications. Design & test your entire stack in less than an hour. Even test MVP. Build to industrial scale with the exported output.
			link 6:56 PM · Aug 19, 2023, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 11 likes, url='https://twitter.com/intent/like?tweet_id=1692973803188392402'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1692973803188392402'
			button Copy link
			link Read 2 replies, url='https://twitter.com/wayne_culbreth/status/1692973803188392402'
		article
			link Damian Soto, url='https://twitter.com/sotoplatero/status/1692286497850855494'
				image Damian Soto, url='https://pbs.twimg.com/profile_images/1872860928502349824/HItLB9zt_normal.jpg'
			link Damian Soto, url='https://twitter.com/sotoplatero/status/1692286497850855494'
			link @sotoplatero, url='https://twitter.com/sotoplatero/status/1692286497850855494'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=sotoplatero'
			link View on Twitter, url='https://twitter.com/sotoplatero/status/1692286497850855494'
			paragraph
				StaticText Chatea Gratis con tus PDF sin código !!!

En este hilo te muestro como crear un chat gpt personalizado sin una linea de código que puedes incluir en tu web

Usamos
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText que es una increíble herramienta para crear aplicaciones LLM con
				link #nocode, url='https://twitter.com/hashtag/nocode'
				StaticText .

Empezamos🧵
			link Image, url='https://twitter.com/sotoplatero/status/1692286497850855494'
				image Image, url='https://pbs.twimg.com/media/F3w1mbEWUAQPpmL?format=jpg&name=small'
			link 9:25 PM · Aug 17, 2023, url='https://twitter.com/sotoplatero/status/1692286497850855494'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 22 likes, url='https://twitter.com/intent/like?tweet_id=1692286497850855494'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1692286497850855494'
			button Copy link
			link Read 2 replies, url='https://twitter.com/sotoplatero/status/1692286497850855494'
		article
			link VerySmallWoods, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
				image VerySmallWoods, url='https://pbs.twimg.com/profile_images/1600964189731934222/eWMb0-L2_normal.jpg'
			link VerySmallWoods Verified account, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
				image Verified account
			link @verysmallwoods, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
			StaticText ·
			link Follow, url='https://twitter.com/intent/follow?screen_name=verysmallwoods'
			link View on Twitter, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
			paragraph
				StaticText AutoGen = LLM多代理框架 👨‍👩‍👧‍👦
Flowise = 无代码LLM工作流构建平台 0️⃣

由
				link @FlowiseAI, url='https://twitter.com/FlowiseAI'
				StaticText 负责构建功能单元；由AutoGen负责调度协作，任务执行。

嗯！有点美妙！
🎏 🎀 🪄 🪅 🎊 🎉

AutoGen + Flowise = 零代码平台上的超级AI助理 

视频 👇
				link youtu.be/gKNR1ghU1Ao?si…, url='https://youtu.be/gKNR1ghU1Ao?si=ZI9jqz3ss51NG8HX'
				link #AutoGen, url='https://twitter.com/hashtag/AutoGen'
				link #Flowise, url='https://twitter.com/hashtag/Flowise'
				link #OpenAI, url='https://twitter.com/hashtag/OpenAI'
				StaticText …
			link 1:05 AM · Oct 22, 2023, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
				time
			link Twitter for Websites, Ads Information and Privacy, url='https://help.twitter.com/en/twitter-for-websites-ads-info-and-privacy'
			link Like. This Tweet has 11 likes, url='https://twitter.com/intent/like?tweet_id=1715897092244189221'
			link Reply to this Tweet on Twitter, url='https://twitter.com/intent/tweet?in_reply_to=1715897092244189221'
			button Copy link
			link Read more on Twitter, url='https://twitter.com/verysmallwoods/status/1715897092244189221'
		heading Webinars
		paragraph
			StaticText Learn how to use Flowise from different webinar series with our partners
		image How to Build No-Code SQL Chatbots using Flowise, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fsinglestore_webinar_2.94e511f6.jpeg&w=828&q=75'
		image SingleStore, url='https://flowiseai.com/_next/static/media/singlestore.a5b72cb0.svg'
		StaticText How to Build No-Code SQL Chatbots using Flowise
		link Learn More, url='https://memsql.wistia.com/medias/i1ra0jared'
		image LlamaIndex Webinar: Build No-Code RAG with Flowise, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fllamaindex_webinar.a14452aa.png&w=750&q=75'
		image Milvus, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fllamaindex.5ac46e4e.png&w=48&q=75'
		StaticText LlamaIndex Webinar: Build No-Code RAG with Flowise
		link Learn More, url='https://youtu.be/k5Txq5C_AWA?si=5oqbNBvqP1BEcpVm'
		image How to Build a NoCode AWS Bedrock LLM App on Flowise, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fsinglestore_aws_webinar.185bcd9c.png&w=1080&q=75'
		image SingleStore, url='https://flowiseai.com/_next/static/media/singlestore.a5b72cb0.svg'
		image AWS, url='https://flowiseai.com/_next/static/media/aws.c9a4034b.svg'
		StaticText How to Build a NoCode AWS Bedrock LLM App on Flowise
		link Learn More, url='https://memsql.wistia.com/medias/y230cbhxb0?utm_medium=email&utm_source=singlestore&utm_campaign=7014X0000029ZgFQAU&campaignid=7014X0000029ZgFQAU'
		image Drag and Drop LLMs: Simplifying RAG with FlowiseAI and Milvus, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fmilvus_webinar.0165f039.png&w=828&q=75'
		image Milvus, url='https://flowiseai.com/_next/static/media/milvus.1ae32e3c.svg'
		StaticText Drag and Drop LLMs: Simplifying RAG with FlowiseAI and Milvus
		link Learn More, url='https://youtu.be/OeloMm8SdMc?si=R1sdxako6YM857MT'
		image LangChain Low-Code/No-Code Webinar, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Flangchainwebinar.2f5914b2.png&w=640&q=75'
		image Langchain, url='https://flowiseai.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Flangchain.c1e79304.png&w=48&q=75'
		StaticText LangChain Weekly Webinar - Low-Code/No-Code LLM
		link Learn More, url='https://youtu.be/qWv2vyOX0tk?si=-SJM5Z7UvYlOdUhG'
		heading Enterprise
		paragraph
			StaticText Looking for specific use cases and support?
		link Lets Chat, url='mailto:hello@flowiseai.com'
	contentinfo
		list
			listitem
				link Terms of Service, url='https://flowiseai.com/terms'
			listitem
				link Privacy Policy, url='https://flowiseai.com/privacy'
			listitem
				link Twitter, url='https://twitter.com/FlowiseAI'
					image
			listitem
				link Github, url='https://github.com/FlowiseAI/Flowise'
					image
			listitem
				link Linkedin, url='https://www.linkedin.com/company/flowiseai'
					image
		StaticText © FlowiseAI Inc. All rights reserved.
	alert, atomic
```
</details>

**Reasoning for action:** By clicking on the Product Catalog button, I am directly accessing the specific use case of Flowise that the user is interested in. This action moves me closer to fulfilling the user's objective of exploring the practical applications of Flowise, as detailed use cases are crucial for understanding how Flowise can assist in building customized LLM apps.

**Action:** click(309) # Click on the Product Catalog button to explore this specific use case.

**Change Description:** After clicking the 'Product Catalog' button, it became focused, indicating a potential transition to a detailed exploration of the product catalog use case, reflecting a change in user focus within the 'Use Cases' section of the Flowise website.

**Screenshot before:****Screenshot after:**---

