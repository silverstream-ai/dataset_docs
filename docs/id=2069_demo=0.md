# Task

**Explore Wasp Documentation**

As a developer evaluating Wasp framework,
I explore the Wasp documentation to understand its installation process and quick start guidelines,
so that I can effectively set up Wasp for my development projects without any obstacles.

**Success definition:** Given I have accessed the Wasp documentation page
When I navigate through the documentation sections by clicking on the 'Quick Start' link followed by the 'Installation' link
Then I should see the installation steps and prerequisites clearly outlined for setting up Wasp.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://wasp-lang.dev/

https://wasp-lang.dev/docs

**Content (before/after):** 

```
RootWebArea Wasp, url='https://wasp-lang.dev/'
	StaticText 🐝 Wasp v0.15 is here! 🐝
	StaticText See what's new ⚙️ →
	navigation
		[193] link Wasp Logo, center=(290,80), url='https://wasp-lang.dev/'
```
<details><summary>Show more</summary>

```
			image Wasp Logo, url='https://wasp-lang.dev/img/lp/wasp-logo.png'
		StaticText Wasp
		superscript
			StaticText βeta
		[198] link Docs, center=(468,80), url='https://wasp-lang.dev/docs'
		[200] link Blog, center=(524,80), url='https://wasp-lang.dev/blog'
		[202] link FAQ, center=(578,80), url='https://wasp-lang.dev/#faq'
		[204] link 📬 Join the list, center=(672,80), url='https://wasp-lang.dev/#signup'
		[208] link Star us on GitHub, center=(1358,80), url='https://github.com/wasp-lang/wasp'
			image
		[212] link Get Started, center=(1486,80), url='https://wasp-lang.dev/docs/quick-start'
			button Get Started
		[214] link GitHub, center=(1556,80), url='https://github.com/wasp-lang/wasp'
			image GitHub
		[217] link Discord, center=(1596,80), url='https://discord.gg/rzdnErX'
			image Discord
		[220] link X, center=(1636,80), url='https://twitter.com/WaspLang'
			image X
	[181] span, center=(1058,24), inner_text=See what's new ⚙️ →
	[179] b, center=(876,24), inner_text=🐝 Wasp v0.15 is here! 🐝
	main
		heading Develop full-stack web appsfaster.
		paragraph
			StaticText Rails-like framework for React, Node.js and Prisma. Build your app in a day and deploy it with a single CLI command.
		[236] link Get Started, center=(335,470), url='https://wasp-lang.dev/docs/quick-start'
			button Get Started
				image
		[240] link Documentation, center=(480,470), url='https://wasp-lang.dev/docs'
			button Documentation
				image
		StaticText Works with
		image React, url='https://wasp-lang.dev/img/lp/react-logo-gray.svg'
		image Node, url='https://wasp-lang.dev/img/lp/nodejs-logo-gray.svg'
		image Prisma, url='https://wasp-lang.dev/img/lp/prisma-logo-gray.svg'
		StaticText Backed by
		image YC, url='https://wasp-lang.dev/img/lp/yc-logo-rounded.png'
		[256] link todoApp.wasp · Wasp config file, center=(1116,221), inner_text=todoApp.wasp
· Wasp config file, url='https://github.com/wasp-lang/wasp/blob/release/examples/todo-typescript/main.wasp'
			image
		code
			StaticText MainPage
			StaticText page
			StaticText MainPage
			StaticText authRequired
			StaticText true
			StaticText // Limit access to logged in users.
			StaticText component
			StaticText import
			StaticText Main
			StaticText from
			StaticText "@client/Main.tsx"
			StaticText // Your React code.
			StaticText query
			StaticText getTasks
			StaticText fn
			StaticText import
			StaticText {
			StaticText getTasks
			StaticText }
			StaticText from
			StaticText "@server/tasks.js"
			StaticText ,
			StaticText // Your Node.js code.
			StaticText entities
			StaticText [
			StaticText Task
			StaticText ]
			StaticText // Automatic cache invalidation.
		[340] link schema.prisma · Wasp entities schema, center=(1136,597), inner_text=schema.prisma
· Wasp entities schema, url='https://github.com/wasp-lang/wasp/blob/release/examples/todo-typescript/schema.prisma'
			image
		code
		DescriptionList
			image
			term
				StaticText Open Source
			paragraph
				StaticText This is the way. Wasp is fully open-source and you're welcome to contribute!
			[372] link Learn more, center=(420,1002), url='https://github.com/wasp-lang/wasp'
				StaticText Learn more
				image
			image
			term
				StaticText Full-stack Auth
			paragraph
				StaticText Add login with social providers or email in a few lines of code with powerful UI helpers. No third party vendor lock-in.
			[385] link Learn more, center=(780,1026), url='https://wasp-lang.dev/blog/2023/04/12/auth-ui'
				StaticText Learn more
				image
			image
			term
				StaticText RPC (Client <-> Server)
			paragraph
				StaticText Wasp provides a typesafe RPC layer that instantly brings your data models and server logic to the client.
			[398] link Learn more, center=(1140,1002), url='https://wasp-lang.dev/docs/data-model/operations/overview'
				StaticText Learn more
				image
			image
			term
				StaticText Simple Deployment
			paragraph
				StaticText Deploy your app to any platform. Wasp offers CLI helpers for the most popular options.
			[411] link Learn more, center=(1500,1002), url='https://wasp-lang.dev/docs/advanced/deployment/overview'
				StaticText Learn more
				image
			image
			term
				StaticText Jobs
			paragraph
				StaticText Easily define, schedule and run specialized server tasks. Persistent, retryable, delayable.
			link Learn more, url='https://wasp-lang.dev/docs/advanced/jobs'
				StaticText Learn more
				image
			image
			term
				StaticText Email Sending
			paragraph
				StaticText All you need to do is connect an email provider and you can send emails!
			link Learn more, url='https://wasp-lang.dev/docs/advanced/email'
				StaticText Learn more
				image
			image
			term
				StaticText Full-stack Type Safety
			paragraph
				StaticText Full support for TypeScript with auto-generated types that span the whole stack.
			link Learn more, url='https://wasp-lang.dev/docs/tutorial/queries#implementing-a-query'
				StaticText Learn more
				image
			image
			term
				StaticText And More!
			paragraph
				StaticText Custom API routes, database seeding, optimistic updates, automatic cache invalidation on the client, ...
			link Learn more, url='https://wasp-lang.dev/docs'
				StaticText Learn more
				image
		heading How does it work? 🧐
		paragraph
			StaticText Given a simple
			code
				StaticText .wasp
			StaticText configuration file that describes the high-level details of your web app, and
			code
				StaticText .js(x)/.css/...
			StaticText , source files with your unique logic, Wasp compiler generates the full source of your web app in the target stack: front-end, back-end and deployment.
			StaticText This unique approach is what makes Wasp "smart" and gives it its super powers!
		DescriptionList
			term
				heading Simple config language
				paragraph
					StaticText Declaratively describe high-level details of your app.
				link Learn more, url='https://wasp-lang.dev/docs/general/language'
					StaticText Learn more
					image
			term
				heading Wasp CLI
				paragraph
					StaticText All the handy commands at your fingertips.
				link Learn more, url='https://wasp-lang.dev/docs/general/cli'
					StaticText Learn more
					image
			term
				heading React / Node.js / Prisma
				paragraph
					StaticText You are still writing 90% of the code in your favorite technologies.
			term
				heading Arrivederci boilerplate
				paragraph
					StaticText Write only the code that matters, let Wasp handle the rest.
				link Learn more, url='https://www.youtube.com/watch?v=x5nsBbLvKnU'
					StaticText Learn more
					image
		image React, url='https://wasp-lang.dev/img/lp/wasp-compilation-diagram.png'
		heading Show, don't tell.
		paragraph
			StaticText Take a look at examples - see how things work and get inspired for your next project.
		heading Todo App (TypeScript) ✅
		paragraph
			StaticText A famous To-Do list app, implemented in TypeScript.
		image wasp GitHub profile picture, url='https://avatars.githubusercontent.com/u/55102317'
		StaticText wasp
		link todo-typescript, url='https://github.com/wasp-lang/wasp/tree/release/examples/todo-typescript'
			image
		link See the code, url='https://github.com/wasp-lang/wasp/tree/release/examples/todo-typescript'
			button See the code
				image
		heading CoverLetterGPT 🤖
		paragraph
			StaticText Generate cover letters based on your CV and the job description. Powered by ChatGPT.
		image vincanger GitHub profile picture, url='https://avatars.githubusercontent.com/u/70215737'
		StaticText vincanger
		link coverlettergpt, url='https://github.com/vincanger/coverlettergpt'
			image
		link See the code, url='https://github.com/vincanger/coverlettergpt'
			button See the code
				image
		link Demo, url='https://coverlettergpt.xyz/'
			button Demo
				image
		heading Realtime voting via WebSockets 🔌
		paragraph
			StaticText A realtime, websockets-powered voting app built with Wasp and TypeScript.
		image wasp GitHub profile picture, url='https://avatars.githubusercontent.com/u/55102317'
		StaticText wasp
		link websockets-realtime-voting, url='https://github.com/wasp-lang/wasp/tree/release/examples/websockets-realtime-voting'
			image
		link See the code, url='https://github.com/wasp-lang/wasp/tree/release/examples/websockets-realtime-voting'
			button See the code
				image
		link Demo, url='https://websockets-voting-client.fly.dev/login'
			button Demo
				image
		link See all examples, url='https://github.com/wasp-lang/wasp/tree/release/examples'
			image
		heading You're in a good crowd
		paragraph
			StaticText Here's what folks using Wasp say about it. Join
			link our Discord, url='https://discord.gg/rzdnErX'
			StaticText for more!
		link Joan Reyero @joanreyero I spent the one weekend building with Wasp and it was amazing, a real pleasure. I normally develop in Vue.js, but in a weekend I had time to learn Wasp, React and finish a full-stack app (only missing styling). This would have been impossible before. So glad to see Wasp in Beta! 🍻, url='https://www.producthunt.com/posts/wasp-lang-beta?comment=2048094'
			image, url='https://wasp-lang.dev/img/lp/tm/reyero.jpg'
			heading Joan Reyero
			paragraph
				StaticText @joanreyero
			image, url='https://wasp-lang.dev/img/lp/ph-logo.png'
			StaticText I spent the one weekend building with Wasp and it was amazing, a real pleasure. I normally develop in Vue.js, but in a weekend I had time to learn Wasp, React and finish a full-stack app (only missing styling). This would have been impossible before.

So glad to see Wasp in Beta! 🍻
		link Tim ✌️ @tskaggs The simplification of the main.wasp file is 👍. And it feels like a very light weight version of a few larger frameworks., url='https://twitter.com/tskaggs/status/1602513968207101954'
			image, url='https://wasp-lang.dev/img/lp/tm/tskaggs.png'
			heading Tim ✌️
			paragraph
				StaticText @tskaggs
			image, url='https://wasp-lang.dev/img/lp/twitter-logo.png'
		link Attila Vago @AttilaTheDev @WaspLang has been in the back of my mind for months now. It left an impression, and I’m really not easy to impress. That’s gotta mean something… #programming #webdevelopment #FullStack, url='https://twitter.com/AttilaTheDev/status/1583530646047117317'
			image, url='https://wasp-lang.dev/img/lp/tm/attila.jpg'
			heading Attila Vago
			paragraph
				StaticText @AttilaTheDev
			image, url='https://wasp-lang.dev/img/lp/twitter-logo.png'
		button 🐝 Load more
		heading 🏆 Showcase Gallery 🏆
		paragraph
			StaticText See what others are building with Wasp.
		link Farnance: SaaS marketplace for farmers hackathon material-ui See how Julian won HackLBS 2021 among 250 participants and why Wasp was instrumental for the team's victory., url='https://wasp-lang.dev/blog/2022/10/28/farnance-hackathon-winner'
			image, url='https://wasp-lang.dev/img/lp/showcase/farnance-dashboard.png'
			heading Farnance: SaaS marketplace for farmers
			StaticText hackathon
			StaticText material-ui
			paragraph
				StaticText See how Julian won HackLBS 2021 among 250 participants and why Wasp was instrumental for the team's victory.
		link Grabbit: Easily manage dev environments internal-tools See how Michael built and deployed an internal tool for managing dev resources at StudentBeans., url='https://wasp-lang.dev/blog/2022/11/26/michael-curry-usecase'
			image, url='https://wasp-lang.dev/img/lp/showcase/grabbit-hero.png'
			heading Grabbit: Easily manage dev environments
			StaticText internal-tools
			paragraph
				StaticText See how Michael built and deployed an internal tool for managing dev resources at StudentBeans.
		link Amicus: Task and workflow management for legal teams startup material-ui See how Erlis rolled out fully-fledged SaaS as a team of one in record time and got first paying customers., url='https://wasp-lang.dev/blog/2022/11/26/erlis-amicus-usecase'
			image, url='https://wasp-lang.dev/img/lp/showcase/amicus-landing.png'
			heading Amicus: Task and workflow management for legal teams
			StaticText startup
			StaticText material-ui
			paragraph
				StaticText See how Erlis rolled out fully-fledged SaaS as a team of one in record time and got first paying customers.
		heading Stay up to date 📬
		paragraph
			StaticText Be the first to know when we ship new features and updates!
		textbox Email address, required
		button Subscribe
		heading 🚧 Roadmap 🚧
		paragraph
			StaticText Work on Wasp never stops: get a glimpse of what is coming next!
		StaticText Right behind the corner
		list
			listitem
				StaticText Improve Prisma support (more features, IDE)
				link 641, url='https://github.com/wasp-lang/wasp/issues/641'
					StaticText 641
					image
			listitem
				StaticText Add TS eDSL, next to Wasp DSL
				link 551, url='https://github.com/wasp-lang/wasp/issues/551'
					StaticText 551
					image
			listitem
				StaticText Make Wasp Auth usable in external services
				link 1973, url='https://github.com/wasp-lang/wasp/issues/1973'
					StaticText 1973
					image
			listitem
				StaticText Add more social providers to Wasp Auth
				link 2016, url='https://github.com/wasp-lang/wasp/issues/2016'
					StaticText 2016
					image
			listitem
				StaticText Support for SSR / SSG
				link 911, url='https://github.com/wasp-lang/wasp/issues/911'
					StaticText 911
					image
			listitem
				StaticText Full-Stack Modules (aka FSMs: think RoR Engines)
		StaticText Further down the road
		list
			listitem
				StaticText Multiple targets (e.g. mobile)
				link 1088, url='https://github.com/wasp-lang/wasp/issues/1088'
					StaticText 1088
					image
			listitem
				StaticText Automatic generation of API for Operations
				link 863, url='https://github.com/wasp-lang/wasp/issues/863'
					StaticText 863
					image
			listitem
				StaticText Top-level data schema
				link 642, url='https://github.com/wasp-lang/wasp/issues/642'
					StaticText 642
					image
			listitem
				StaticText Complex arch (multiple servers, clients, serverless)
			listitem
				StaticText Polyglot (Python, Rust, Go, ...)
				link 1940, url='https://github.com/wasp-lang/wasp/issues/1940'
					StaticText 1940
					image
			listitem
				StaticText Multiple frontend libraries (Vue, Svelte, ...)
		heading Frequently asked questions
		paragraph
			StaticText For anything not covered here, join
			link our Discord, url='https://discord.gg/rzdnErX'
			StaticText !
		DescriptionList
			term
				button How is Wasp different from Next.js / Nuxt.js / Gatsby?
					image
			term
				button How is Wasp different from Ruby on Rails or Django?
					image
			term
				button How hard is it to learn Wasp?
					image
			term
				button Do you support only React & Node.js currently?
					image
	contentinfo
		heading Docs
		list
			listitem
				link Getting Started, url='https://wasp-lang.dev/docs'
			listitem
				link Todo app tutorial, url='https://wasp-lang.dev/docs/tutorial/create'
			listitem
				link Language reference, url='https://wasp-lang.dev/docs/general/language'
		heading Community
		list
			listitem
				link Discord, url='https://discord.gg/rzdnErX'
			listitem
				link Twitter, url='https://twitter.com/WaspLang'
			listitem
				link GitHub, url='https://github.com/wasp-lang/wasp'
		heading Company
		list
			listitem
				link Blog, url='https://wasp-lang.dev/blog'
			listitem
				link Careers, url='https://wasp-lang.notion.site/Wasp-Careers-59fd1682c80d446f92be5fa65cc17672'
			listitem
				link Company, url='https://www.notion.so/wasp-lang/Founding-Engineer-at-Wasp-88a73838f7f04ab3aee1f8e1c1bee6dd#20569f14a8af452db10ae618d764d505'
		heading Stay up to date
		paragraph
			StaticText Join our mailing list and be the first to know when we ship new features and updates!
		textbox Email address, required
		button Subscribe
		StaticText Backed by
		image YC, url='https://wasp-lang.dev/img/lp/yc-logo-rounded.png'
		link Wasp Logo, url='https://wasp-lang.dev/'
			image Wasp Logo, url='https://wasp-lang.dev/img/lp/wasp-logo.png'
		StaticText Wasp
		paragraph
			StaticText © Wasp, Inc. All rights reserved.
```
</details>



```
RootWebArea Introduction | Wasp, focused, url='https://wasp-lang.dev/docs'
	region Skip to main content
		link Skip to main content, url='https://wasp-lang.dev/docs#docusaurus_skipToContent_fallback'
	banner
		StaticText Wasp v0.15 is here!
```
<details><summary>Show more</summary>

```
		StaticText 🐝
		[1095] link See what's new ⚙️, center=(1037,14), url='https://wasp-lang.dev/blog/2024/09/30/wasp-launch-week-7'
	navigation Main
		[1101] link Wasp logo .wasp (beta), center=(85,60), inner_text=.wasp (beta), url='https://wasp-lang.dev/'
			image Wasp logo, url='https://wasp-lang.dev/img/wasp-logo-eqpar-circle.png'
		[1105] link Docs, center=(202,60), url='https://wasp-lang.dev/docs'
		[1107] button 0.15.0, center=(277,60), expanded=False, hasPopup='menu'
		[1119] link Blog, center=(350,60), url='https://wasp-lang.dev/blog'
		[1121] link, center=(1645,60), url='https://github.com/wasp-lang/wasp'
		[1122] link, center=(1669,60), url='https://twitter.com/WaspLang'
		[1123] link, center=(1693,60), url='https://discord.gg/rzdnErX'
		[1125] button Switch between dark and light mode (currently light mode), center=(1721,60), title=Switch between dark and light mode (currently light mode), type=button
			image
		[1129] button Search, center=(1826,60), inner_text=Search
K, type=button
			image
			image
			StaticText K
	complementary
		navigation Docs sidebar
			list
				listitem
					[1148] link Getting Started, center=(146,114), expanded=True, url='https://wasp-lang.dev/docs#'
					list
						listitem
							[1151] link Introduction, center=(152,150), url='https://wasp-lang.dev/docs'
						listitem
							[1153] link Quick Start, center=(152,186), url='https://wasp-lang.dev/docs/quick-start'
						listitem
							[1155] link Editor Setup, center=(152,222), url='https://wasp-lang.dev/docs/editor-setup'
				listitem
					[1158] link Tutorial, center=(146,270), expanded=True, url='https://wasp-lang.dev/docs#'
					list
						listitem
							[1161] link 1. Creating a New Project, center=(152,306), url='https://wasp-lang.dev/docs/tutorial/create'
						listitem
							[1163] link 2. Project Structure, center=(152,342), url='https://wasp-lang.dev/docs/tutorial/project-structure'
						listitem
							[1165] link 3. Pages & Routes, center=(152,378), url='https://wasp-lang.dev/docs/tutorial/pages'
						listitem
							[1167] link 4. Database Entities, center=(152,414), url='https://wasp-lang.dev/docs/tutorial/entities'
						listitem
							[1169] link 5. Querying the Database, center=(152,450), url='https://wasp-lang.dev/docs/tutorial/queries'
						listitem
							[1171] link 6. Modifying Data, center=(152,486), url='https://wasp-lang.dev/docs/tutorial/actions'
						listitem
							[1173] link 7. Adding Authentication, center=(152,522), url='https://wasp-lang.dev/docs/tutorial/auth'
				listitem
					[1175] link Examples, center=(146,570), url='https://github.com/wasp-lang/wasp/tree/release/examples'
				listitem
					[1179] link Data Model, center=(146,618), expanded=True, url='https://wasp-lang.dev/docs#'
					list
						listitem
							[1182] link Entities, center=(152,654), url='https://wasp-lang.dev/docs/data-model/entities'
						listitem
							[1185] link Operations, center=(152,690), expanded=False, url='https://wasp-lang.dev/docs#'
						listitem
							[1187] link Automatic CRUD, center=(152,726), url='https://wasp-lang.dev/docs/data-model/crud'
						listitem
							[1189] link Databases, center=(152,762), url='https://wasp-lang.dev/docs/data-model/backends'
						listitem
							[1191] link Prisma Schema File, center=(152,798), url='https://wasp-lang.dev/docs/data-model/prisma-file'
				listitem
					[1194] link Authentication, center=(146,846), expanded=True, url='https://wasp-lang.dev/docs#'
					list
						listitem
							[1197] link Overview, center=(152,882), url='https://wasp-lang.dev/docs/auth/overview'
						listitem
							[1199] link Auth UI, center=(152,918), url='https://wasp-lang.dev/docs/auth/ui'
						listitem
							[1201] link Username & Password, center=(152,954), url='https://wasp-lang.dev/docs/auth/username-and-pass'
						listitem
							[1203] link Email, center=(152,990), url='https://wasp-lang.dev/docs/auth/email'
						listitem
							[1206] link Social Auth, center=(152,1026), expanded=False, url='https://wasp-lang.dev/docs#'
						listitem
							[1208] link Accessing User Data, center=(152,1062), url='https://wasp-lang.dev/docs/auth/entities'
						listitem
							link Auth Hooks, url='https://wasp-lang.dev/docs/auth/auth-hooks'
				listitem
					link Project Setup, expanded=True, url='https://wasp-lang.dev/docs#'
					list
						listitem
							link Starter Templates, url='https://wasp-lang.dev/docs/project/starter-templates'
						listitem
							link Customizing the App, url='https://wasp-lang.dev/docs/project/customizing-app'
						listitem
							link Client Config, url='https://wasp-lang.dev/docs/project/client-config'
						listitem
							link Server Config, url='https://wasp-lang.dev/docs/project/server-config'
						listitem
							link Static Asset Handling, url='https://wasp-lang.dev/docs/project/static-assets'
						listitem
							link Env Variables, url='https://wasp-lang.dev/docs/project/env-vars'
						listitem
							link Testing, url='https://wasp-lang.dev/docs/project/testing'
						listitem
							link Dependencies, url='https://wasp-lang.dev/docs/project/dependencies'
						listitem
							link CSS Frameworks, url='https://wasp-lang.dev/docs/project/css-frameworks'
						listitem
							link Custom Vite Config, url='https://wasp-lang.dev/docs/project/custom-vite-config'
				listitem
					link Wasp AI, expanded=True, url='https://wasp-lang.dev/docs#'
					list
						listitem
							link Creating New App with AI, url='https://wasp-lang.dev/docs/wasp-ai/creating-new-app'
						listitem
							link Developing Existing App with AI, url='https://wasp-lang.dev/docs/wasp-ai/developing-existing-app'
				listitem
					link Advanced Features, expanded=True, url='https://wasp-lang.dev/docs#'
					list
						listitem
							link Sending Emails, url='https://wasp-lang.dev/docs/advanced/email'
						listitem
							link Recurring Jobs, url='https://wasp-lang.dev/docs/advanced/jobs'
						listitem
							link Web Sockets, url='https://wasp-lang.dev/docs/advanced/web-sockets'
						listitem
							link Accessing the configuration, url='https://wasp-lang.dev/docs/advanced/accessing-app-config'
						listitem
							link Custom HTTP API Endpoints, url='https://wasp-lang.dev/docs/advanced/apis'
						listitem
							link Configuring Middleware, url='https://wasp-lang.dev/docs/advanced/middleware-config'
						listitem
							link Type-Safe Links, url='https://wasp-lang.dev/docs/advanced/links'
				listitem
					link Deployment, expanded=True, url='https://wasp-lang.dev/docs#'
					list
						listitem
							link Overview, url='https://wasp-lang.dev/docs/advanced/deployment/overview'
						listitem
							link Deploying with the Wasp CLI, url='https://wasp-lang.dev/docs/advanced/deployment/cli'
						listitem
							link Deploying Manually, url='https://wasp-lang.dev/docs/advanced/deployment/manually'
				listitem
					link General, expanded=True, url='https://wasp-lang.dev/docs#'
					list
						listitem
							link Wasp Language (.wasp), url='https://wasp-lang.dev/docs/general/language'
						listitem
							link CLI Reference, url='https://wasp-lang.dev/docs/general/cli'
						listitem
							link TypeScript Support, url='https://wasp-lang.dev/docs/general/typescript'
						listitem
							link Wasp TypeScript config (*.wasp.ts), url='https://wasp-lang.dev/docs/general/wasp-ts-config'
				listitem
					link Migration guides, expanded=False, url='https://wasp-lang.dev/docs#'
				listitem
					link Miscellaneous, expanded=False, url='https://wasp-lang.dev/docs#'
	main
		article
			navigation Breadcrumbs
				list
					listitem
						[1298] link Home page, center=(377,121), url='https://wasp-lang.dev/'
							image
					[1300] listitem, center=(488,121), inner_text=Getting Started
						StaticText Getting Started
					[1303] listitem, center=(603,121), inner_text=Introduction
						StaticText Introduction
			StaticText Version: 0.15.0
			heading Introduction
			image
			StaticText NOTE
			paragraph
				StaticText If you are looking for the installation instructions, check out the
				[1318] link Quick Start, center=(902,317), url='https://wasp-lang.dev/docs/quick-start'
				StaticText section.
			paragraph
				StaticText We will give a brief overview of what Wasp is, how it works on a high level and when to use it.
			heading Wasp is a tool to build modern web applications Direct link to Wasp is a tool to build modern web applications
				[1321] link Direct link to Wasp is a tool to build modern web applications, center=(1104,444), inner_text=​, title=Direct link to Wasp is a tool to build modern web applications, url='https://wasp-lang.dev/docs#wasp-is-a-tool-to-build-modern-web-applications'
					StaticText ​
			paragraph
				StaticText It is an opinionated way of building
				strong
					StaticText full-stack web applications
				StaticText . It takes care of all three major parts of a web application:
				strong
					StaticText client
				StaticText (front-end),
				strong
					StaticText server
				StaticText (back-end) and
				strong
					StaticText database
				StaticText .
			heading Works well with your existing stack Direct link to Works well with your existing stack
				[1328] link Direct link to Works well with your existing stack, center=(776,577), inner_text=​, title=Direct link to Works well with your existing stack, url='https://wasp-lang.dev/docs#works-well-with-your-existing-stack'
					StaticText ​
			paragraph
				StaticText Wasp is not trying to do everything at once but rather focuses on the complexity that arises from connecting all the parts of the stack (client, server, database, deployment).
			paragraph
				StaticText Wasp is using
				strong
					StaticText React
				StaticText ,
				strong
					StaticText Node.js
				StaticText and
				strong
					StaticText Prisma
				StaticText under the hood and relies on them to define web components and server queries and actions.
			heading Wasp's secret sauce Direct link to Wasp's secret sauce
				[1335] link Direct link to Wasp's secret sauce, center=(610,749), inner_text=​, title=Direct link to Wasp's secret sauce, url='https://wasp-lang.dev/docs#wasps-secret-sauce'
					StaticText ​
			paragraph
				StaticText At the core is the Wasp compiler which takes the Wasp config and your Javascript code and outputs the client app, server app and deployment code.
			paragraph
				figure
					image, url='https://wasp-lang.dev/img/lp/wasp-compilation-diagram.png'
					Figcaption
						StaticText How the magic happens 🌈
			paragraph
				StaticText The cool thing about having a compiler that understands your code is that it can do a lot of things for you.
			paragraph
				StaticText Define your app in the Wasp config and get:
			list
				listitem
					ListMarker •
					StaticText login and signup with Auth UI components,
				listitem
					ListMarker •
					StaticText full-stack type safety,
				listitem
					ListMarker •
					StaticText e-mail sending,
				listitem
					ListMarker •
					StaticText async processing jobs,
				listitem
					ListMarker •
					StaticText React Query powered data fetching,
				listitem
					ListMarker •
					StaticText security best practices,
				listitem
					ListMarker •
					StaticText and more.
			paragraph
				StaticText You don't need to write any code for these features, Wasp will take care of it for you 🤯 And what's even better, Wasp also maintains the code for you, so you don't have to worry about keeping up with the latest security best practices. As Wasp updates, so does your app.
			heading So what does the code look like? Direct link to So what does the code look like?
				link Direct link to So what does the code look like?, url='https://wasp-lang.dev/docs#so-what-does-the-code-look-like'
					StaticText ​
			paragraph
				StaticText Let's say you want to build a web app that allows users to
				strong
					StaticText create and share their favorite recipes
				StaticText .
			paragraph
				StaticText Let's start with the
				code
					StaticText main.wasp
				StaticText file: it is the central file of your app, where you describe the app from the high level.
			paragraph
				StaticText Let's give our app a title and let's immediately turn on the full-stack authentication via username and password:
			StaticText main.wasp
			code
				StaticText app
				StaticText RecipeApp
				StaticText {
				StaticText title
				StaticText :
				StaticText "My Recipes"
				StaticText ,
				StaticText wasp
				StaticText :
				StaticText {
				StaticText version
				StaticText :
				StaticText "^0.15.0"
				StaticText }
				StaticText ,
				StaticText auth
				StaticText :
				StaticText {
				StaticText methods
				StaticText :
				StaticText {
				StaticText usernameAndPassword
				StaticText :
				StaticText {
				StaticText }
				StaticText }
				StaticText ,
				StaticText onAuthFailedRedirectTo
				StaticText :
				StaticText "/login"
				StaticText ,
				StaticText userEntity
				StaticText :
				StaticText User
				StaticText }
				StaticText }
			button Copy code to clipboard
			paragraph
				StaticText Let's then add the data models for your recipes. Wasp understands and uses the models from the
				code
					StaticText schema.prisma
				StaticText file. We will want to have Users and Users can own Recipes:
			StaticText schema.prisma
			code
				StaticText .
				StaticText .
				StaticText .
				StaticText // Data models are defined using Prisma Schema Language.
				StaticText model
				StaticText User
				StaticText {
				StaticText id
				StaticText Int
				StaticText @id
				StaticText @default
				StaticText (
				StaticText autoincrement
				StaticText (
				StaticText )
				StaticText )
				StaticText recipes
				StaticText Recipe
				StaticText [
				StaticText ]
				StaticText }
				StaticText model
				StaticText Recipe
				StaticText {
				StaticText id
				StaticText Int
				StaticText @id
				StaticText @default
				StaticText (
				StaticText autoincrement
				StaticText (
				StaticText )
				StaticText )
				StaticText title
				StaticText String
				StaticText description
				StaticText String
				StaticText ?
				StaticText userId
				StaticText Int
				StaticText user
				StaticText User
				StaticText @relation
				StaticText (
				StaticText fields:
				StaticText [
				StaticText userId
				StaticText ]
				StaticText ,
				StaticText references:
				StaticText [
				StaticText id
				StaticText ]
				StaticText )
				StaticText }
			button Copy code to clipboard
			paragraph
				StaticText Next, let's define how to do something with these data models!
			paragraph
				StaticText We do that by defining Operations, in this case, a Query
				code
					StaticText getRecipes
				StaticText and Action
				code
					StaticText addRecipe
				StaticText , which are in their essence Node.js functions that execute on the server and can, thanks to Wasp, very easily be called from the client.
			paragraph
				StaticText First, we define these Operations in our
				code
					StaticText main.wasp
				StaticText file, so Wasp knows about them and can "beef them up":
			StaticText main.wasp
			code
				StaticText // Queries have automatic cache invalidation and are type-safe.
				StaticText query
				StaticText getRecipes
				StaticText {
				StaticText fn
				StaticText :
				StaticText import
				StaticText {
				StaticText getRecipes
				StaticText }
				StaticText from
				StaticText "@src/recipe/operations"
				StaticText ,
				StaticText entities
				StaticText :
				StaticText [
				StaticText Recipe
				StaticText ]
				StaticText ,
				StaticText }
				StaticText // Actions are type-safe and can be used to perform side-effects.
				StaticText action
				StaticText addRecipe
				StaticText {
				StaticText fn
				StaticText :
				StaticText import
				StaticText {
				StaticText addRecipe
				StaticText }
				StaticText from
				StaticText "@src/recipe/operations"
				StaticText ,
				StaticText entities
				StaticText :
				StaticText [
				StaticText Recipe
				StaticText ]
				StaticText ,
				StaticText }
			button Copy code to clipboard
			paragraph
				StaticText ... and then implement them in our Javascript (or TypeScript) code (we show just the query here, using TypeScript):
			StaticText src/recipe/operations.ts
			code
				StaticText // Wasp generates the types for you.
				StaticText import
				StaticText {
				StaticText type
				StaticText GetRecipes
				StaticText }
				StaticText from
				StaticText "wasp/server/operations"
				StaticText ;
				StaticText import
				StaticText {
				StaticText type
				StaticText Recipe
				StaticText }
				StaticText from
				StaticText "wasp/entities"
				StaticText ;
				StaticText export
				StaticText const
				StaticText getRecipes
				StaticText :
				StaticText GetRecipes
				StaticText <
				StaticText {
				StaticText }
				StaticText ,
				StaticText Recipe
				StaticText [
				StaticText ]
				StaticText >
				StaticText =
				StaticText async
				StaticText (
				StaticText _args
				StaticText ,
				StaticText context
				StaticText )
				StaticText =>
				StaticText {
				StaticText return
				StaticText context
				StaticText .
				StaticText entities
				StaticText .
				StaticText Recipe
				StaticText .
				StaticText findMany
				StaticText (
				StaticText // Prisma query
				StaticText {
				StaticText where
				StaticText :
				StaticText {
				StaticText user
				StaticText :
				StaticText {
				StaticText id
				StaticText :
				StaticText context
				StaticText .
				StaticText user
				StaticText .
				StaticText id
				StaticText }
				StaticText }
				StaticText }
				StaticText )
				StaticText ;
				StaticText }
				StaticText ;
				StaticText export
				StaticText const
				StaticText addRecipe
				StaticText ...
			button Copy code to clipboard
			paragraph
				StaticText Now we can very easily use these in our React components!
			paragraph
				StaticText For the end, let's create a home page of our app.
			paragraph
				StaticText First, we define it in
				code
					StaticText main.wasp
				StaticText :
			StaticText main.wasp
			code
				StaticText ...
				StaticText route
				StaticText HomeRoute
				StaticText {
				StaticText path
				StaticText :
				StaticText "/"
				StaticText ,
				StaticText to
				StaticText :
				StaticText HomePage
				StaticText }
				StaticText page
				StaticText HomePage
				StaticText {
				StaticText component
				StaticText :
				StaticText import
				StaticText {
				StaticText HomePage
				StaticText }
				StaticText from
				StaticText "@src/pages/HomePage"
				StaticText ,
				StaticText authRequired
				StaticText :
				StaticText true
				StaticText // Will send user to /login if not authenticated.
				StaticText }
			button Copy code to clipboard
			paragraph
				StaticText and then implement it as a React component in JS/TS (that calls the Operations we previously defined):
			StaticText src/pages/HomePage.tsx
			code
				StaticText import
				StaticText {
				StaticText useQuery
				StaticText ,
				StaticText getRecipes
				StaticText }
				StaticText from
				StaticText 'wasp/client/operations'
				StaticText import
				StaticText {
				StaticText type
				StaticText User
				StaticText }
				StaticText from
				StaticText 'wasp/entities'
				StaticText export
				StaticText function
				StaticText HomePage
				StaticText (
				StaticText {
				StaticText user
				StaticText }
				StaticText :
				StaticText {
				StaticText user
				StaticText :
				StaticText User
				StaticText }
				StaticText )
				StaticText {
				StaticText // Due to full-stack type safety, `recipes` will be of type `Recipe[]` here.
				StaticText const
				StaticText {
				StaticText data
				StaticText :
				StaticText recipes
				StaticText ,
				StaticText isLoading
				StaticText }
				StaticText =
				StaticText useQuery
				StaticText (
				StaticText getRecipes
				StaticText )
				StaticText // Calling our query here!
				StaticText if
				StaticText (
				StaticText isLoading
				StaticText )
				StaticText {
				StaticText return
				StaticText <
				StaticText div
				StaticText >
				StaticText Loading...
				StaticText </
				StaticText div
				StaticText >
				StaticText }
				StaticText return
				StaticText (
				StaticText <
				StaticText div
				StaticText >
				StaticText <
				StaticText h1
				StaticText >
				StaticText Recipes
				StaticText </
				StaticText h1
				StaticText >
				StaticText <
				StaticText ul
				StaticText >
				StaticText {
				StaticText recipes
				StaticText ?
				StaticText recipes
				StaticText .
				StaticText map
				StaticText (
				StaticText (
				StaticText recipe
				StaticText )
				StaticText =>
				StaticText (
				StaticText <
				StaticText li
				StaticText key
				StaticText =
				StaticText {
				StaticText recipe
				StaticText .
				StaticText id
				StaticText }
				StaticText >
				StaticText <
				StaticText div
				StaticText >
				StaticText {
				StaticText recipe
				StaticText .
				StaticText title
				StaticText }
				StaticText </
				StaticText div
				StaticText >
				StaticText <
				StaticText div
				StaticText >
				StaticText {
				StaticText recipe
				StaticText .
				StaticText description
				StaticText }
				StaticText </
				StaticText div
				StaticText >
				StaticText </
				StaticText li
				StaticText >
				StaticText )
				StaticText )
				StaticText :
				StaticText 'No recipes defined yet!'
				StaticText }
				StaticText </
				StaticText ul
				StaticText >
				StaticText </
				StaticText div
				StaticText >
				StaticText )
				StaticText }
			button Copy code to clipboard
			paragraph
				StaticText And voila! We are listing all the recipes in our app 🎉
			paragraph
				StaticText This was just a quick example to give you a taste of what Wasp is. For step by step tour through the most important Wasp features, check out the
				link Todo app tutorial, url='https://wasp-lang.dev/docs/tutorial/create'
				StaticText .
			image
			StaticText NOTE
			paragraph
				StaticText Above we skipped defining
				code
					StaticText /login
				StaticText and
				code
					StaticText /signup
				StaticText pages to keep the example a bit shorter, but those are very simple to do by using Wasp's Auth UI feature.
			heading When to use Wasp Direct link to When to use Wasp
				link Direct link to When to use Wasp, url='https://wasp-lang.dev/docs#when-to-use-wasp'
					StaticText ​
			paragraph
				StaticText Wasp addresses the same core problems that typical web app frameworks are addressing, and it in big part
				link looks, swims and quacks, url='https://en.wikipedia.org/wiki/Duck_test'
				StaticText like a web app framework.
			heading Best used for Direct link to Best used for
				link Direct link to Best used for, url='https://wasp-lang.dev/docs#best-used-for'
					StaticText ​
			list
				listitem
					ListMarker •
					StaticText building full-stack web apps (like e.g. Airbnb or Asana)
				listitem
					ListMarker •
					StaticText quickly starting a web app with industry best practices
				listitem
					ListMarker •
					StaticText to be used alongside modern web dev stack (React and Node.js are currently supported)
			heading Avoid using Wasp for Direct link to Avoid using Wasp for
				link Direct link to Avoid using Wasp for, url='https://wasp-lang.dev/docs#avoid-using-wasp-for'
					StaticText ​
			list
				listitem
					ListMarker •
					StaticText building static/presentational websites
				listitem
					ListMarker •
					StaticText to be used as a no-code solution
				listitem
					ListMarker •
					StaticText to be a solve-it-all tool in a single language
			heading Wasp is a DSL Direct link to Wasp is a DSL
				link Direct link to Wasp is a DSL, url='https://wasp-lang.dev/docs#wasp-is-a-dsl'
					StaticText ​
			image
			StaticText NOTE
			paragraph
				StaticText You don't need to know what a DSL is to use Wasp, but if you are curious, you can read more about it below.
			paragraph
				StaticText Wasp does not match typical expectations of a web app framework: it is not a set of libraries, it is instead a simple programming language that understands your code and can do a lot of things for you.
			paragraph
				StaticText Wasp is a programming language, but a specific kind: it is specialized for a single purpose:
				strong
					StaticText building modern web applications
				StaticText . We call such languages
				emphasis
					StaticText DSL
				StaticText s (Domain Specific Language).
			paragraph
				StaticText Other examples of
				emphasis
					StaticText DSL
				StaticText s that are often used today are e.g.
				emphasis
					StaticText SQL
				StaticText for databases and
				emphasis
					StaticText HTML
				StaticText for web page layouts. The main advantage and reason why
				emphasis
					StaticText DSL
				StaticText s exist is that they need to do only one task (e.g. database queries) so they can do it well and provide the best possible experience for the developer.
			paragraph
				StaticText The same idea stands behind Wasp - a language that will allow developers to
				strong
					StaticText build modern web applications with 10x less code and less stack-specific knowledge
				StaticText .
			link Edit this page, url='https://github.com/wasp-lang/wasp/edit/release/web/versioned_docs/version-0.15.0/introduction/introduction.md'
		navigation Docs pages navigation
			link Next Quick Start », url='https://wasp-lang.dev/docs/quick-start'
		list
			listitem
				[2242] link Wasp is a tool to build modern web applications, center=(1690,132), url='https://wasp-lang.dev/docs#wasp-is-a-tool-to-build-modern-web-applications'
				list
					listitem
						[2245] link Works well with your existing stack, center=(1694,159), url='https://wasp-lang.dev/docs#works-well-with-your-existing-stack'
					listitem
						[2247] link Wasp's secret sauce, center=(1694,186), url='https://wasp-lang.dev/docs#wasps-secret-sauce'
			listitem
				[2249] link So what does the code look like?, center=(1690,213), url='https://wasp-lang.dev/docs#so-what-does-the-code-look-like'
			listitem
				[2251] link When to use Wasp, center=(1690,240), url='https://wasp-lang.dev/docs#when-to-use-wasp'
				list
					listitem
						[2254] link Best used for, center=(1694,268), url='https://wasp-lang.dev/docs#best-used-for'
					listitem
						[2256] link Avoid using Wasp for, center=(1694,295), url='https://wasp-lang.dev/docs#avoid-using-wasp-for'
			listitem
				[2258] link Wasp is a DSL, center=(1690,322), url='https://wasp-lang.dev/docs#wasp-is-a-dsl'
	contentinfo
		StaticText Docs
		list
			listitem
				link Getting started, url='https://wasp-lang.dev/docs'
			listitem
				link Todo app tutorial, url='https://wasp-lang.dev/docs/tutorial/create'
		StaticText Community
		list
			listitem
				link Discord, url='https://discord.gg/rzdnErX'
		StaticText More
		list
			listitem
				link GitHub, url='https://github.com/wasp-lang/wasp'
			listitem
				link Contact, url='https://wasp-lang.dev/docs/contact'
		StaticText Copyright © 2024 Wasp.
```
</details>

**Reasoning for action:** I clicked the 'Docs' link because this is the first step needed to access the Wasp documentation, which contains essential information on installation and getting started with the framework. This action aligns with the user story as it begins my exploration of the required documentation.

**Action:** click(198) # Click on the Docs link to explore the documentation section.

**Change Description:** After clicking the 'Docs' link, the browser navigated from the Wasp landing page to the Wasp documentation page, displaying a new set of content focused on the introduction to Wasp, including sections on its functionality, structure, and usage along with navigational links to further documentation topics.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://wasp-lang.dev/docs

https://wasp-lang.dev/docs/quick-start

**Content (before/after):** 

```
RootWebArea Introduction | Wasp, focused, url='https://wasp-lang.dev/docs'
	region Skip to main content
		link Skip to main content, url='https://wasp-lang.dev/docs#docusaurus_skipToContent_fallback'
	banner
		StaticText Wasp v0.15 is here!
```
<details><summary>Show more</summary>

```
		StaticText 🐝
		[1095] link See what's new ⚙️, center=(1037,14), url='https://wasp-lang.dev/blog/2024/09/30/wasp-launch-week-7'
	navigation Main
		[1101] link Wasp logo .wasp (beta), center=(85,60), inner_text=.wasp (beta), url='https://wasp-lang.dev/'
			image Wasp logo, url='https://wasp-lang.dev/img/wasp-logo-eqpar-circle.png'
		[1105] link Docs, center=(202,60), url='https://wasp-lang.dev/docs'
		[1107] button 0.15.0, center=(277,60), expanded=False, hasPopup='menu'
		[1119] link Blog, center=(350,60), url='https://wasp-lang.dev/blog'
		[1121] link, center=(1645,60), url='https://github.com/wasp-lang/wasp'
		[1122] link, center=(1669,60), url='https://twitter.com/WaspLang'
		[1123] link, center=(1693,60), url='https://discord.gg/rzdnErX'
		[1125] button Switch between dark and light mode (currently light mode), center=(1721,60), title=Switch between dark and light mode (currently light mode), type=button
			image
		[1129] button Search, center=(1826,60), inner_text=Search
K, type=button
			image
			image
			StaticText K
	complementary
		navigation Docs sidebar
			list
				listitem
					[1148] link Getting Started, center=(146,114), expanded=True, url='https://wasp-lang.dev/docs#'
					list
						listitem
							[1151] link Introduction, center=(152,150), url='https://wasp-lang.dev/docs'
						listitem
							[1153] link Quick Start, center=(152,186), url='https://wasp-lang.dev/docs/quick-start'
						listitem
							[1155] link Editor Setup, center=(152,222), url='https://wasp-lang.dev/docs/editor-setup'
				listitem
					[1158] link Tutorial, center=(146,270), expanded=True, url='https://wasp-lang.dev/docs#'
					list
						listitem
							[1161] link 1. Creating a New Project, center=(152,306), url='https://wasp-lang.dev/docs/tutorial/create'
						listitem
							[1163] link 2. Project Structure, center=(152,342), url='https://wasp-lang.dev/docs/tutorial/project-structure'
						listitem
							[1165] link 3. Pages & Routes, center=(152,378), url='https://wasp-lang.dev/docs/tutorial/pages'
						listitem
							[1167] link 4. Database Entities, center=(152,414), url='https://wasp-lang.dev/docs/tutorial/entities'
						listitem
							[1169] link 5. Querying the Database, center=(152,450), url='https://wasp-lang.dev/docs/tutorial/queries'
						listitem
							[1171] link 6. Modifying Data, center=(152,486), url='https://wasp-lang.dev/docs/tutorial/actions'
						listitem
							[1173] link 7. Adding Authentication, center=(152,522), url='https://wasp-lang.dev/docs/tutorial/auth'
				listitem
					[1175] link Examples, center=(146,570), url='https://github.com/wasp-lang/wasp/tree/release/examples'
				listitem
					[1179] link Data Model, center=(146,618), expanded=True, url='https://wasp-lang.dev/docs#'
					list
						listitem
							[1182] link Entities, center=(152,654), url='https://wasp-lang.dev/docs/data-model/entities'
						listitem
							[1185] link Operations, center=(152,690), expanded=False, url='https://wasp-lang.dev/docs#'
						listitem
							[1187] link Automatic CRUD, center=(152,726), url='https://wasp-lang.dev/docs/data-model/crud'
						listitem
							[1189] link Databases, center=(152,762), url='https://wasp-lang.dev/docs/data-model/backends'
						listitem
							[1191] link Prisma Schema File, center=(152,798), url='https://wasp-lang.dev/docs/data-model/prisma-file'
				listitem
					[1194] link Authentication, center=(146,846), expanded=True, url='https://wasp-lang.dev/docs#'
					list
						listitem
							[1197] link Overview, center=(152,882), url='https://wasp-lang.dev/docs/auth/overview'
						listitem
							[1199] link Auth UI, center=(152,918), url='https://wasp-lang.dev/docs/auth/ui'
						listitem
							[1201] link Username & Password, center=(152,954), url='https://wasp-lang.dev/docs/auth/username-and-pass'
						listitem
							[1203] link Email, center=(152,990), url='https://wasp-lang.dev/docs/auth/email'
						listitem
							[1206] link Social Auth, center=(152,1026), expanded=False, url='https://wasp-lang.dev/docs#'
						listitem
							[1208] link Accessing User Data, center=(152,1062), url='https://wasp-lang.dev/docs/auth/entities'
						listitem
							link Auth Hooks, url='https://wasp-lang.dev/docs/auth/auth-hooks'
				listitem
					link Project Setup, expanded=True, url='https://wasp-lang.dev/docs#'
					list
						listitem
							link Starter Templates, url='https://wasp-lang.dev/docs/project/starter-templates'
						listitem
							link Customizing the App, url='https://wasp-lang.dev/docs/project/customizing-app'
						listitem
							link Client Config, url='https://wasp-lang.dev/docs/project/client-config'
						listitem
							link Server Config, url='https://wasp-lang.dev/docs/project/server-config'
						listitem
							link Static Asset Handling, url='https://wasp-lang.dev/docs/project/static-assets'
						listitem
							link Env Variables, url='https://wasp-lang.dev/docs/project/env-vars'
						listitem
							link Testing, url='https://wasp-lang.dev/docs/project/testing'
						listitem
							link Dependencies, url='https://wasp-lang.dev/docs/project/dependencies'
						listitem
							link CSS Frameworks, url='https://wasp-lang.dev/docs/project/css-frameworks'
						listitem
							link Custom Vite Config, url='https://wasp-lang.dev/docs/project/custom-vite-config'
				listitem
					link Wasp AI, expanded=True, url='https://wasp-lang.dev/docs#'
					list
						listitem
							link Creating New App with AI, url='https://wasp-lang.dev/docs/wasp-ai/creating-new-app'
						listitem
							link Developing Existing App with AI, url='https://wasp-lang.dev/docs/wasp-ai/developing-existing-app'
				listitem
					link Advanced Features, expanded=True, url='https://wasp-lang.dev/docs#'
					list
						listitem
							link Sending Emails, url='https://wasp-lang.dev/docs/advanced/email'
						listitem
							link Recurring Jobs, url='https://wasp-lang.dev/docs/advanced/jobs'
						listitem
							link Web Sockets, url='https://wasp-lang.dev/docs/advanced/web-sockets'
						listitem
							link Accessing the configuration, url='https://wasp-lang.dev/docs/advanced/accessing-app-config'
						listitem
							link Custom HTTP API Endpoints, url='https://wasp-lang.dev/docs/advanced/apis'
						listitem
							link Configuring Middleware, url='https://wasp-lang.dev/docs/advanced/middleware-config'
						listitem
							link Type-Safe Links, url='https://wasp-lang.dev/docs/advanced/links'
				listitem
					link Deployment, expanded=True, url='https://wasp-lang.dev/docs#'
					list
						listitem
							link Overview, url='https://wasp-lang.dev/docs/advanced/deployment/overview'
						listitem
							link Deploying with the Wasp CLI, url='https://wasp-lang.dev/docs/advanced/deployment/cli'
						listitem
							link Deploying Manually, url='https://wasp-lang.dev/docs/advanced/deployment/manually'
				listitem
					link General, expanded=True, url='https://wasp-lang.dev/docs#'
					list
						listitem
							link Wasp Language (.wasp), url='https://wasp-lang.dev/docs/general/language'
						listitem
							link CLI Reference, url='https://wasp-lang.dev/docs/general/cli'
						listitem
							link TypeScript Support, url='https://wasp-lang.dev/docs/general/typescript'
						listitem
							link Wasp TypeScript config (*.wasp.ts), url='https://wasp-lang.dev/docs/general/wasp-ts-config'
				listitem
					link Migration guides, expanded=False, url='https://wasp-lang.dev/docs#'
				listitem
					link Miscellaneous, expanded=False, url='https://wasp-lang.dev/docs#'
	main
		article
			navigation Breadcrumbs
				list
					listitem
						[1298] link Home page, center=(377,121), url='https://wasp-lang.dev/'
							image
					[1300] listitem, center=(488,121), inner_text=Getting Started
						StaticText Getting Started
					[1303] listitem, center=(603,121), inner_text=Introduction
						StaticText Introduction
			StaticText Version: 0.15.0
			heading Introduction
			image
			StaticText NOTE
			paragraph
				StaticText If you are looking for the installation instructions, check out the
				[1318] link Quick Start, center=(902,317), url='https://wasp-lang.dev/docs/quick-start'
				StaticText section.
			paragraph
				StaticText We will give a brief overview of what Wasp is, how it works on a high level and when to use it.
			heading Wasp is a tool to build modern web applications Direct link to Wasp is a tool to build modern web applications
				[1321] link Direct link to Wasp is a tool to build modern web applications, center=(1104,444), inner_text=​, title=Direct link to Wasp is a tool to build modern web applications, url='https://wasp-lang.dev/docs#wasp-is-a-tool-to-build-modern-web-applications'
					StaticText ​
			paragraph
				StaticText It is an opinionated way of building
				strong
					StaticText full-stack web applications
				StaticText . It takes care of all three major parts of a web application:
				strong
					StaticText client
				StaticText (front-end),
				strong
					StaticText server
				StaticText (back-end) and
				strong
					StaticText database
				StaticText .
			heading Works well with your existing stack Direct link to Works well with your existing stack
				[1328] link Direct link to Works well with your existing stack, center=(776,577), inner_text=​, title=Direct link to Works well with your existing stack, url='https://wasp-lang.dev/docs#works-well-with-your-existing-stack'
					StaticText ​
			paragraph
				StaticText Wasp is not trying to do everything at once but rather focuses on the complexity that arises from connecting all the parts of the stack (client, server, database, deployment).
			paragraph
				StaticText Wasp is using
				strong
					StaticText React
				StaticText ,
				strong
					StaticText Node.js
				StaticText and
				strong
					StaticText Prisma
				StaticText under the hood and relies on them to define web components and server queries and actions.
			heading Wasp's secret sauce Direct link to Wasp's secret sauce
				[1335] link Direct link to Wasp's secret sauce, center=(610,749), inner_text=​, title=Direct link to Wasp's secret sauce, url='https://wasp-lang.dev/docs#wasps-secret-sauce'
					StaticText ​
			paragraph
				StaticText At the core is the Wasp compiler which takes the Wasp config and your Javascript code and outputs the client app, server app and deployment code.
			paragraph
				figure
					image, url='https://wasp-lang.dev/img/lp/wasp-compilation-diagram.png'
					Figcaption
						StaticText How the magic happens 🌈
			paragraph
				StaticText The cool thing about having a compiler that understands your code is that it can do a lot of things for you.
			paragraph
				StaticText Define your app in the Wasp config and get:
			list
				listitem
					ListMarker •
					StaticText login and signup with Auth UI components,
				listitem
					ListMarker •
					StaticText full-stack type safety,
				listitem
					ListMarker •
					StaticText e-mail sending,
				listitem
					ListMarker •
					StaticText async processing jobs,
				listitem
					ListMarker •
					StaticText React Query powered data fetching,
				listitem
					ListMarker •
					StaticText security best practices,
				listitem
					ListMarker •
					StaticText and more.
			paragraph
				StaticText You don't need to write any code for these features, Wasp will take care of it for you 🤯 And what's even better, Wasp also maintains the code for you, so you don't have to worry about keeping up with the latest security best practices. As Wasp updates, so does your app.
			heading So what does the code look like? Direct link to So what does the code look like?
				link Direct link to So what does the code look like?, url='https://wasp-lang.dev/docs#so-what-does-the-code-look-like'
					StaticText ​
			paragraph
				StaticText Let's say you want to build a web app that allows users to
				strong
					StaticText create and share their favorite recipes
				StaticText .
			paragraph
				StaticText Let's start with the
				code
					StaticText main.wasp
				StaticText file: it is the central file of your app, where you describe the app from the high level.
			paragraph
				StaticText Let's give our app a title and let's immediately turn on the full-stack authentication via username and password:
			StaticText main.wasp
			code
				StaticText app
				StaticText RecipeApp
				StaticText {
				StaticText title
				StaticText :
				StaticText "My Recipes"
				StaticText ,
				StaticText wasp
				StaticText :
				StaticText {
				StaticText version
				StaticText :
				StaticText "^0.15.0"
				StaticText }
				StaticText ,
				StaticText auth
				StaticText :
				StaticText {
				StaticText methods
				StaticText :
				StaticText {
				StaticText usernameAndPassword
				StaticText :
				StaticText {
				StaticText }
				StaticText }
				StaticText ,
				StaticText onAuthFailedRedirectTo
				StaticText :
				StaticText "/login"
				StaticText ,
				StaticText userEntity
				StaticText :
				StaticText User
				StaticText }
				StaticText }
			button Copy code to clipboard
			paragraph
				StaticText Let's then add the data models for your recipes. Wasp understands and uses the models from the
				code
					StaticText schema.prisma
				StaticText file. We will want to have Users and Users can own Recipes:
			StaticText schema.prisma
			code
				StaticText .
				StaticText .
				StaticText .
				StaticText // Data models are defined using Prisma Schema Language.
				StaticText model
				StaticText User
				StaticText {
				StaticText id
				StaticText Int
				StaticText @id
				StaticText @default
				StaticText (
				StaticText autoincrement
				StaticText (
				StaticText )
				StaticText )
				StaticText recipes
				StaticText Recipe
				StaticText [
				StaticText ]
				StaticText }
				StaticText model
				StaticText Recipe
				StaticText {
				StaticText id
				StaticText Int
				StaticText @id
				StaticText @default
				StaticText (
				StaticText autoincrement
				StaticText (
				StaticText )
				StaticText )
				StaticText title
				StaticText String
				StaticText description
				StaticText String
				StaticText ?
				StaticText userId
				StaticText Int
				StaticText user
				StaticText User
				StaticText @relation
				StaticText (
				StaticText fields:
				StaticText [
				StaticText userId
				StaticText ]
				StaticText ,
				StaticText references:
				StaticText [
				StaticText id
				StaticText ]
				StaticText )
				StaticText }
			button Copy code to clipboard
			paragraph
				StaticText Next, let's define how to do something with these data models!
			paragraph
				StaticText We do that by defining Operations, in this case, a Query
				code
					StaticText getRecipes
				StaticText and Action
				code
					StaticText addRecipe
				StaticText , which are in their essence Node.js functions that execute on the server and can, thanks to Wasp, very easily be called from the client.
			paragraph
				StaticText First, we define these Operations in our
				code
					StaticText main.wasp
				StaticText file, so Wasp knows about them and can "beef them up":
			StaticText main.wasp
			code
				StaticText // Queries have automatic cache invalidation and are type-safe.
				StaticText query
				StaticText getRecipes
				StaticText {
				StaticText fn
				StaticText :
				StaticText import
				StaticText {
				StaticText getRecipes
				StaticText }
				StaticText from
				StaticText "@src/recipe/operations"
				StaticText ,
				StaticText entities
				StaticText :
				StaticText [
				StaticText Recipe
				StaticText ]
				StaticText ,
				StaticText }
				StaticText // Actions are type-safe and can be used to perform side-effects.
				StaticText action
				StaticText addRecipe
				StaticText {
				StaticText fn
				StaticText :
				StaticText import
				StaticText {
				StaticText addRecipe
				StaticText }
				StaticText from
				StaticText "@src/recipe/operations"
				StaticText ,
				StaticText entities
				StaticText :
				StaticText [
				StaticText Recipe
				StaticText ]
				StaticText ,
				StaticText }
			button Copy code to clipboard
			paragraph
				StaticText ... and then implement them in our Javascript (or TypeScript) code (we show just the query here, using TypeScript):
			StaticText src/recipe/operations.ts
			code
				StaticText // Wasp generates the types for you.
				StaticText import
				StaticText {
				StaticText type
				StaticText GetRecipes
				StaticText }
				StaticText from
				StaticText "wasp/server/operations"
				StaticText ;
				StaticText import
				StaticText {
				StaticText type
				StaticText Recipe
				StaticText }
				StaticText from
				StaticText "wasp/entities"
				StaticText ;
				StaticText export
				StaticText const
				StaticText getRecipes
				StaticText :
				StaticText GetRecipes
				StaticText <
				StaticText {
				StaticText }
				StaticText ,
				StaticText Recipe
				StaticText [
				StaticText ]
				StaticText >
				StaticText =
				StaticText async
				StaticText (
				StaticText _args
				StaticText ,
				StaticText context
				StaticText )
				StaticText =>
				StaticText {
				StaticText return
				StaticText context
				StaticText .
				StaticText entities
				StaticText .
				StaticText Recipe
				StaticText .
				StaticText findMany
				StaticText (
				StaticText // Prisma query
				StaticText {
				StaticText where
				StaticText :
				StaticText {
				StaticText user
				StaticText :
				StaticText {
				StaticText id
				StaticText :
				StaticText context
				StaticText .
				StaticText user
				StaticText .
				StaticText id
				StaticText }
				StaticText }
				StaticText }
				StaticText )
				StaticText ;
				StaticText }
				StaticText ;
				StaticText export
				StaticText const
				StaticText addRecipe
				StaticText ...
			button Copy code to clipboard
			paragraph
				StaticText Now we can very easily use these in our React components!
			paragraph
				StaticText For the end, let's create a home page of our app.
			paragraph
				StaticText First, we define it in
				code
					StaticText main.wasp
				StaticText :
			StaticText main.wasp
			code
				StaticText ...
				StaticText route
				StaticText HomeRoute
				StaticText {
				StaticText path
				StaticText :
				StaticText "/"
				StaticText ,
				StaticText to
				StaticText :
				StaticText HomePage
				StaticText }
				StaticText page
				StaticText HomePage
				StaticText {
				StaticText component
				StaticText :
				StaticText import
				StaticText {
				StaticText HomePage
				StaticText }
				StaticText from
				StaticText "@src/pages/HomePage"
				StaticText ,
				StaticText authRequired
				StaticText :
				StaticText true
				StaticText // Will send user to /login if not authenticated.
				StaticText }
			button Copy code to clipboard
			paragraph
				StaticText and then implement it as a React component in JS/TS (that calls the Operations we previously defined):
			StaticText src/pages/HomePage.tsx
			code
				StaticText import
				StaticText {
				StaticText useQuery
				StaticText ,
				StaticText getRecipes
				StaticText }
				StaticText from
				StaticText 'wasp/client/operations'
				StaticText import
				StaticText {
				StaticText type
				StaticText User
				StaticText }
				StaticText from
				StaticText 'wasp/entities'
				StaticText export
				StaticText function
				StaticText HomePage
				StaticText (
				StaticText {
				StaticText user
				StaticText }
				StaticText :
				StaticText {
				StaticText user
				StaticText :
				StaticText User
				StaticText }
				StaticText )
				StaticText {
				StaticText // Due to full-stack type safety, `recipes` will be of type `Recipe[]` here.
				StaticText const
				StaticText {
				StaticText data
				StaticText :
				StaticText recipes
				StaticText ,
				StaticText isLoading
				StaticText }
				StaticText =
				StaticText useQuery
				StaticText (
				StaticText getRecipes
				StaticText )
				StaticText // Calling our query here!
				StaticText if
				StaticText (
				StaticText isLoading
				StaticText )
				StaticText {
				StaticText return
				StaticText <
				StaticText div
				StaticText >
				StaticText Loading...
				StaticText </
				StaticText div
				StaticText >
				StaticText }
				StaticText return
				StaticText (
				StaticText <
				StaticText div
				StaticText >
				StaticText <
				StaticText h1
				StaticText >
				StaticText Recipes
				StaticText </
				StaticText h1
				StaticText >
				StaticText <
				StaticText ul
				StaticText >
				StaticText {
				StaticText recipes
				StaticText ?
				StaticText recipes
				StaticText .
				StaticText map
				StaticText (
				StaticText (
				StaticText recipe
				StaticText )
				StaticText =>
				StaticText (
				StaticText <
				StaticText li
				StaticText key
				StaticText =
				StaticText {
				StaticText recipe
				StaticText .
				StaticText id
				StaticText }
				StaticText >
				StaticText <
				StaticText div
				StaticText >
				StaticText {
				StaticText recipe
				StaticText .
				StaticText title
				StaticText }
				StaticText </
				StaticText div
				StaticText >
				StaticText <
				StaticText div
				StaticText >
				StaticText {
				StaticText recipe
				StaticText .
				StaticText description
				StaticText }
				StaticText </
				StaticText div
				StaticText >
				StaticText </
				StaticText li
				StaticText >
				StaticText )
				StaticText )
				StaticText :
				StaticText 'No recipes defined yet!'
				StaticText }
				StaticText </
				StaticText ul
				StaticText >
				StaticText </
				StaticText div
				StaticText >
				StaticText )
				StaticText }
			button Copy code to clipboard
			paragraph
				StaticText And voila! We are listing all the recipes in our app 🎉
			paragraph
				StaticText This was just a quick example to give you a taste of what Wasp is. For step by step tour through the most important Wasp features, check out the
				link Todo app tutorial, url='https://wasp-lang.dev/docs/tutorial/create'
				StaticText .
			image
			StaticText NOTE
			paragraph
				StaticText Above we skipped defining
				code
					StaticText /login
				StaticText and
				code
					StaticText /signup
				StaticText pages to keep the example a bit shorter, but those are very simple to do by using Wasp's Auth UI feature.
			heading When to use Wasp Direct link to When to use Wasp
				link Direct link to When to use Wasp, url='https://wasp-lang.dev/docs#when-to-use-wasp'
					StaticText ​
			paragraph
				StaticText Wasp addresses the same core problems that typical web app frameworks are addressing, and it in big part
				link looks, swims and quacks, url='https://en.wikipedia.org/wiki/Duck_test'
				StaticText like a web app framework.
			heading Best used for Direct link to Best used for
				link Direct link to Best used for, url='https://wasp-lang.dev/docs#best-used-for'
					StaticText ​
			list
				listitem
					ListMarker •
					StaticText building full-stack web apps (like e.g. Airbnb or Asana)
				listitem
					ListMarker •
					StaticText quickly starting a web app with industry best practices
				listitem
					ListMarker •
					StaticText to be used alongside modern web dev stack (React and Node.js are currently supported)
			heading Avoid using Wasp for Direct link to Avoid using Wasp for
				link Direct link to Avoid using Wasp for, url='https://wasp-lang.dev/docs#avoid-using-wasp-for'
					StaticText ​
			list
				listitem
					ListMarker •
					StaticText building static/presentational websites
				listitem
					ListMarker •
					StaticText to be used as a no-code solution
				listitem
					ListMarker •
					StaticText to be a solve-it-all tool in a single language
			heading Wasp is a DSL Direct link to Wasp is a DSL
				link Direct link to Wasp is a DSL, url='https://wasp-lang.dev/docs#wasp-is-a-dsl'
					StaticText ​
			image
			StaticText NOTE
			paragraph
				StaticText You don't need to know what a DSL is to use Wasp, but if you are curious, you can read more about it below.
			paragraph
				StaticText Wasp does not match typical expectations of a web app framework: it is not a set of libraries, it is instead a simple programming language that understands your code and can do a lot of things for you.
			paragraph
				StaticText Wasp is a programming language, but a specific kind: it is specialized for a single purpose:
				strong
					StaticText building modern web applications
				StaticText . We call such languages
				emphasis
					StaticText DSL
				StaticText s (Domain Specific Language).
			paragraph
				StaticText Other examples of
				emphasis
					StaticText DSL
				StaticText s that are often used today are e.g.
				emphasis
					StaticText SQL
				StaticText for databases and
				emphasis
					StaticText HTML
				StaticText for web page layouts. The main advantage and reason why
				emphasis
					StaticText DSL
				StaticText s exist is that they need to do only one task (e.g. database queries) so they can do it well and provide the best possible experience for the developer.
			paragraph
				StaticText The same idea stands behind Wasp - a language that will allow developers to
				strong
					StaticText build modern web applications with 10x less code and less stack-specific knowledge
				StaticText .
			link Edit this page, url='https://github.com/wasp-lang/wasp/edit/release/web/versioned_docs/version-0.15.0/introduction/introduction.md'
		navigation Docs pages navigation
			link Next Quick Start », url='https://wasp-lang.dev/docs/quick-start'
		list
			listitem
				[2242] link Wasp is a tool to build modern web applications, center=(1690,132), url='https://wasp-lang.dev/docs#wasp-is-a-tool-to-build-modern-web-applications'
				list
					listitem
						[2245] link Works well with your existing stack, center=(1694,159), url='https://wasp-lang.dev/docs#works-well-with-your-existing-stack'
					listitem
						[2247] link Wasp's secret sauce, center=(1694,186), url='https://wasp-lang.dev/docs#wasps-secret-sauce'
			listitem
				[2249] link So what does the code look like?, center=(1690,213), url='https://wasp-lang.dev/docs#so-what-does-the-code-look-like'
			listitem
				[2251] link When to use Wasp, center=(1690,240), url='https://wasp-lang.dev/docs#when-to-use-wasp'
				list
					listitem
						[2254] link Best used for, center=(1694,268), url='https://wasp-lang.dev/docs#best-used-for'
					listitem
						[2256] link Avoid using Wasp for, center=(1694,295), url='https://wasp-lang.dev/docs#avoid-using-wasp-for'
			listitem
				[2258] link Wasp is a DSL, center=(1690,322), url='https://wasp-lang.dev/docs#wasp-is-a-dsl'
	contentinfo
		StaticText Docs
		list
			listitem
				link Getting started, url='https://wasp-lang.dev/docs'
			listitem
				link Todo app tutorial, url='https://wasp-lang.dev/docs/tutorial/create'
		StaticText Community
		list
			listitem
				link Discord, url='https://discord.gg/rzdnErX'
		StaticText More
		list
			listitem
				link GitHub, url='https://github.com/wasp-lang/wasp'
			listitem
				link Contact, url='https://wasp-lang.dev/docs/contact'
		StaticText Copyright © 2024 Wasp.
```
</details>



```
RootWebArea Quick Start | Wasp, focused, url='https://wasp-lang.dev/docs/quick-start'
	region Skip to main content
		link Skip to main content, url='https://wasp-lang.dev/docs/quick-start#docusaurus_skipToContent_fallback'
	banner
		StaticText Wasp v0.15 is here!
```
<details><summary>Show more</summary>

```
		StaticText 🐝
		[1095] link See what's new ⚙️, center=(1037,14), url='https://wasp-lang.dev/blog/2024/09/30/wasp-launch-week-7'
	navigation Main
		[1101] link Wasp logo .wasp (beta), center=(85,60), inner_text=.wasp (beta), url='https://wasp-lang.dev/'
			image Wasp logo, url='https://wasp-lang.dev/img/wasp-logo-eqpar-circle.png'
		[1105] link Docs, center=(202,60), url='https://wasp-lang.dev/docs'
		[1107] button 0.15.0, center=(277,60), expanded=False, hasPopup='menu'
		[1119] link Blog, center=(350,60), url='https://wasp-lang.dev/blog'
		[1121] link, center=(1645,60), url='https://github.com/wasp-lang/wasp'
		[1122] link, center=(1669,60), url='https://twitter.com/WaspLang'
		[1123] link, center=(1693,60), url='https://discord.gg/rzdnErX'
		[1125] button Switch between dark and light mode (currently light mode), center=(1721,60), title=Switch between dark and light mode (currently light mode), type=button
			image
		[1129] button Search, center=(1826,60), inner_text=Search
K, type=button
			image
			image
			StaticText K
	complementary
		navigation Docs sidebar
			list
				listitem
					[1148] link Getting Started, center=(146,114), expanded=True, url='https://wasp-lang.dev/docs/quick-start#'
					list
						listitem
							[1151] link Introduction, center=(152,150), url='https://wasp-lang.dev/docs'
						listitem
							[1153] link Quick Start, center=(152,186), url='https://wasp-lang.dev/docs/quick-start'
						listitem
							[1155] link Editor Setup, center=(152,222), url='https://wasp-lang.dev/docs/editor-setup'
				listitem
					[1158] link Tutorial, center=(146,270), expanded=True, url='https://wasp-lang.dev/docs/quick-start#'
					list
						listitem
							[1161] link 1. Creating a New Project, center=(152,306), url='https://wasp-lang.dev/docs/tutorial/create'
						listitem
							[1163] link 2. Project Structure, center=(152,342), url='https://wasp-lang.dev/docs/tutorial/project-structure'
						listitem
							[1165] link 3. Pages & Routes, center=(152,378), url='https://wasp-lang.dev/docs/tutorial/pages'
						listitem
							[1167] link 4. Database Entities, center=(152,414), url='https://wasp-lang.dev/docs/tutorial/entities'
						listitem
							[1169] link 5. Querying the Database, center=(152,450), url='https://wasp-lang.dev/docs/tutorial/queries'
						listitem
							[1171] link 6. Modifying Data, center=(152,486), url='https://wasp-lang.dev/docs/tutorial/actions'
						listitem
							[1173] link 7. Adding Authentication, center=(152,522), url='https://wasp-lang.dev/docs/tutorial/auth'
				listitem
					[1175] link Examples, center=(146,570), url='https://github.com/wasp-lang/wasp/tree/release/examples'
				listitem
					[1179] link Data Model, center=(146,618), expanded=True, url='https://wasp-lang.dev/docs/quick-start#'
					list
						listitem
							[1182] link Entities, center=(152,654), url='https://wasp-lang.dev/docs/data-model/entities'
						listitem
							[1185] link Operations, center=(152,690), expanded=False, url='https://wasp-lang.dev/docs/quick-start#'
						listitem
							[1187] link Automatic CRUD, center=(152,726), url='https://wasp-lang.dev/docs/data-model/crud'
						listitem
							[1189] link Databases, center=(152,762), url='https://wasp-lang.dev/docs/data-model/backends'
						listitem
							[1191] link Prisma Schema File, center=(152,798), url='https://wasp-lang.dev/docs/data-model/prisma-file'
				listitem
					[1194] link Authentication, center=(146,846), expanded=True, url='https://wasp-lang.dev/docs/quick-start#'
					list
						listitem
							[1197] link Overview, center=(152,882), url='https://wasp-lang.dev/docs/auth/overview'
						listitem
							[1199] link Auth UI, center=(152,918), url='https://wasp-lang.dev/docs/auth/ui'
						listitem
							[1201] link Username & Password, center=(152,954), url='https://wasp-lang.dev/docs/auth/username-and-pass'
						listitem
							[1203] link Email, center=(152,990), url='https://wasp-lang.dev/docs/auth/email'
						listitem
							[1206] link Social Auth, center=(152,1026), expanded=False, url='https://wasp-lang.dev/docs/quick-start#'
						listitem
							[1208] link Accessing User Data, center=(152,1062), url='https://wasp-lang.dev/docs/auth/entities'
						listitem
							link Auth Hooks, url='https://wasp-lang.dev/docs/auth/auth-hooks'
				listitem
					link Project Setup, expanded=True, url='https://wasp-lang.dev/docs/quick-start#'
					list
						listitem
							link Starter Templates, url='https://wasp-lang.dev/docs/project/starter-templates'
						listitem
							link Customizing the App, url='https://wasp-lang.dev/docs/project/customizing-app'
						listitem
							link Client Config, url='https://wasp-lang.dev/docs/project/client-config'
						listitem
							link Server Config, url='https://wasp-lang.dev/docs/project/server-config'
						listitem
							link Static Asset Handling, url='https://wasp-lang.dev/docs/project/static-assets'
						listitem
							link Env Variables, url='https://wasp-lang.dev/docs/project/env-vars'
						listitem
							link Testing, url='https://wasp-lang.dev/docs/project/testing'
						listitem
							link Dependencies, url='https://wasp-lang.dev/docs/project/dependencies'
						listitem
							link CSS Frameworks, url='https://wasp-lang.dev/docs/project/css-frameworks'
						listitem
							link Custom Vite Config, url='https://wasp-lang.dev/docs/project/custom-vite-config'
				listitem
					link Wasp AI, expanded=True, url='https://wasp-lang.dev/docs/quick-start#'
					list
						listitem
							link Creating New App with AI, url='https://wasp-lang.dev/docs/wasp-ai/creating-new-app'
						listitem
							link Developing Existing App with AI, url='https://wasp-lang.dev/docs/wasp-ai/developing-existing-app'
				listitem
					link Advanced Features, expanded=True, url='https://wasp-lang.dev/docs/quick-start#'
					list
						listitem
							link Sending Emails, url='https://wasp-lang.dev/docs/advanced/email'
						listitem
							link Recurring Jobs, url='https://wasp-lang.dev/docs/advanced/jobs'
						listitem
							link Web Sockets, url='https://wasp-lang.dev/docs/advanced/web-sockets'
						listitem
							link Accessing the configuration, url='https://wasp-lang.dev/docs/advanced/accessing-app-config'
						listitem
							link Custom HTTP API Endpoints, url='https://wasp-lang.dev/docs/advanced/apis'
						listitem
							link Configuring Middleware, url='https://wasp-lang.dev/docs/advanced/middleware-config'
						listitem
							link Type-Safe Links, url='https://wasp-lang.dev/docs/advanced/links'
				listitem
					link Deployment, expanded=True, url='https://wasp-lang.dev/docs/quick-start#'
					list
						listitem
							link Overview, url='https://wasp-lang.dev/docs/advanced/deployment/overview'
						listitem
							link Deploying with the Wasp CLI, url='https://wasp-lang.dev/docs/advanced/deployment/cli'
						listitem
							link Deploying Manually, url='https://wasp-lang.dev/docs/advanced/deployment/manually'
				listitem
					link General, expanded=True, url='https://wasp-lang.dev/docs/quick-start#'
					list
						listitem
							link Wasp Language (.wasp), url='https://wasp-lang.dev/docs/general/language'
						listitem
							link CLI Reference, url='https://wasp-lang.dev/docs/general/cli'
						listitem
							link TypeScript Support, url='https://wasp-lang.dev/docs/general/typescript'
						listitem
							link Wasp TypeScript config (*.wasp.ts), url='https://wasp-lang.dev/docs/general/wasp-ts-config'
				listitem
					link Migration guides, expanded=False, url='https://wasp-lang.dev/docs/quick-start#'
				listitem
					link Miscellaneous, expanded=False, url='https://wasp-lang.dev/docs/quick-start#'
	main
		article
			navigation Breadcrumbs
				list
					listitem
						[2318] link Home page, center=(377,121), url='https://wasp-lang.dev/'
							image
					[2320] listitem, center=(488,121), inner_text=Getting Started
						StaticText Getting Started
					[2323] listitem, center=(599,121), inner_text=Quick Start
						StaticText Quick Start
			StaticText Version: 0.15.0
			heading Quick Start
			heading Installation Direct link to Installation
				[2333] link Direct link to Installation, center=(540,278), inner_text=​, title=Direct link to Installation, url='https://wasp-lang.dev/docs/quick-start#installation'
					StaticText ​
			paragraph
				StaticText Welcome, new Waspeteer 🐝!
			paragraph
				StaticText Let's create and run our first Wasp app in 3 short steps:
			list
				listitem
					ListMarker 0.
					paragraph
						strong
							StaticText To install Wasp on Linux / OSX / WSL (Windows), open your terminal and run:
					code
						StaticText curl
						StaticText -sSL https://get.wasp-lang.dev/installer.sh
						StaticText |
						StaticText sh
					[2352] button Copy code to clipboard, center=(1454,475), title=Copy, type=button
					paragraph
						StaticText ℹ️ Wasp requires Node.js and will warn you if it is missing: check below for
						[2357] link more details, center=(1016,531), url='https://wasp-lang.dev/docs/quick-start#requirements'
						StaticText .
				listitem
					ListMarker 0.
					paragraph
						strong
							StaticText Then, create a new app by running:
					code
						StaticText wasp new
					[2369] button Copy code to clipboard, center=(1454,632), title=Copy, type=button
				listitem
					ListMarker 0.
					paragraph
						strong
							StaticText Finally, run the app:
					code
						StaticText cd
						StaticText <
						StaticText my-project-name
						StaticText >
						StaticText wasp start
					[2392] button Copy code to clipboard, center=(1454,745), title=Copy, type=button
			paragraph
				StaticText That's it 🎉 You have successfully created and served a new full-stack web app at
				[2397] link http://localhost:3000, center=(1066,819), url='http://localhost:3000/'
				StaticText and Wasp is serving both frontend and backend for you.
			image
			StaticText SOMETHING UNCLEAR?
			paragraph
				StaticText Check
				[2404] link More Details, center=(480,934), url='https://wasp-lang.dev/docs/quick-start#more-details'
				StaticText section below if anything went wrong with the installation, or if you have additional questions.
			image
			StaticText WANT AN EVEN FASTER START?
			paragraph
				StaticText Try out
				[2411] link Wasp AI, center=(468,1037), url='https://wasp-lang.dev/docs/wasp-ai/creating-new-app'
				StaticText 🤖 to generate a new Wasp app in minutes just from a title and short description!
			image
			StaticText TRY WASP WITHOUT INSTALLING 🤔?
			paragraph
				StaticText Give Wasp a spin in the browser with GitHub Codespaces by following the intructions in our
				link Tutorial App README, url='https://github.com/wasp-lang/wasp/tree/release/examples/tutorials/TodoApp'
			heading What next? Direct link to What next?
				link Direct link to What next?, url='https://wasp-lang.dev/docs/quick-start#what-next'
					StaticText ​
			list
				listitem
					checkbox, checked='false', disabled=True
					StaticText 👉
					strong
						StaticText Check out the
						link Todo App tutorial, url='https://wasp-lang.dev/docs/tutorial/create'
						StaticText , which will take you through all the core features of Wasp!
					StaticText 👈
				listitem
					checkbox, checked='false', disabled=True
					link Setup your editor, url='https://wasp-lang.dev/docs/editor-setup'
					StaticText for working with Wasp.
				listitem
					checkbox, checked='false', disabled=True
					StaticText Join us on
					link Discord, url='https://discord.gg/rzdnErX'
					StaticText ! Any feedback or questions you have, we are there for you.
				listitem
					checkbox, checked='false', disabled=True
					StaticText Follow Wasp development by subscribing to our newsletter:
					link https://wasp-lang.dev/#signup, url='https://wasp-lang.dev/#signup'
					StaticText . We usually send 1 per month, and
					link Matija, url='https://github.com/matijaSos'
					StaticText does his best to unleash his creativity to make them engaging and fun to read :D!
			separator, orientation='horizontal'
			heading More details Direct link to More details
				link Direct link to More details, url='https://wasp-lang.dev/docs/quick-start#more-details'
					StaticText ​
			heading Requirements Direct link to Requirements
				link Direct link to Requirements, url='https://wasp-lang.dev/docs/quick-start#requirements'
					StaticText ​
			paragraph
				StaticText You must have Node.js (and NPM) installed on your machine and available in
				code
					StaticText PATH
				StaticText . A version of Node.js must be >= 18.
			paragraph
				StaticText If you need it, we recommend using
				link nvm, url='https://github.com/nvm-sh/nvm'
				StaticText for managing your Node.js installation version(s).
			group
				DisclosureTriangle A quick guide on installing/using nvm, expanded=False
			heading Installation Direct link to Installation
				link Direct link to Installation, url='https://wasp-lang.dev/docs/quick-start#installation-1'
					StaticText ​
			tablist, orientation='horizontal'
				tab Linux / macOS, selected=True
				tab Windows, selected=False
				tab From source, selected=False
			tabpanel
				paragraph
					StaticText Open your terminal and run:
				code
					StaticText curl
					StaticText -sSL https://get.wasp-lang.dev/installer.sh
					StaticText |
					StaticText sh
				button Copy code to clipboard
				image
				StaticText RUNNING WASP ON MAC WITH MX CHIP (ARM64)
				paragraph
					strong
						StaticText Experiencing the 'Bad CPU type in executable' issue on a device with arm64 (Apple Silicon)?
					StaticText Given that the wasp binary is built for x86 and not for arm64 (Apple Silicon), you'll need to install
					link Rosetta on your Mac, url='https://support.apple.com/en-us/HT211861'
					StaticText if you are using a Mac with Mx (M1, M2, ...). Rosetta is a translation process that enables users to run applications designed for x86 on arm64 (Apple Silicon). To install Rosetta, run the following command in your terminal
				code
					StaticText softwareupdate --install-rosetta
				button Copy code to clipboard
				paragraph
					StaticText Once Rosetta is installed, you should be able to run Wasp without any issues.
			link Edit this page, url='https://github.com/wasp-lang/wasp/edit/release/web/versioned_docs/version-0.15.0/introduction/quick-start.md'
		navigation Docs pages navigation
			link Previous « Introduction, url='https://wasp-lang.dev/docs'
			link Next Editor Setup », url='https://wasp-lang.dev/docs/editor-setup'
		list
			listitem
				[2592] link Installation, center=(1690,132), url='https://wasp-lang.dev/docs/quick-start#installation'
				list
					listitem
						[2595] link What next?, center=(1694,159), url='https://wasp-lang.dev/docs/quick-start#what-next'
			listitem
				[2597] link More details, center=(1690,186), url='https://wasp-lang.dev/docs/quick-start#more-details'
				list
					listitem
						[2600] link Requirements, center=(1694,213), url='https://wasp-lang.dev/docs/quick-start#requirements'
					listitem
						[2602] link Installation, center=(1694,240), url='https://wasp-lang.dev/docs/quick-start#installation-1'
	contentinfo
		StaticText Docs
		list
			listitem
				link Getting started, url='https://wasp-lang.dev/docs'
			listitem
				link Todo app tutorial, url='https://wasp-lang.dev/docs/tutorial/create'
		StaticText Community
		list
			listitem
				link Discord, url='https://discord.gg/rzdnErX'
		StaticText More
		list
			listitem
				link GitHub, url='https://github.com/wasp-lang/wasp'
			listitem
				link Contact, url='https://wasp-lang.dev/docs/contact'
		StaticText Copyright © 2024 Wasp.
```
</details>

**Reasoning for action:** By clicking on the 'Quick Start' link, I am directly accessing the part of the documentation that is designed to give developers a fast overview of how to get started with Wasp. This is crucial for my objective to understand the installation process and quick start guidelines, as it likely contains the prerequisites and steps needed to effectively set up Wasp for development projects.

**Action:** click(1153) # Click on the Quick Start link to explore the initial setup and usage of Wasp.

**Change Description:** The browser navigated from the 'Introduction' page to the 'Quick Start' page of the Wasp documentation, as indicated by the change in URL to 'https://wasp-lang.dev/docs/quick-start' and the main content now focused on the installation steps and initial setup guidelines for Wasp.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://wasp-lang.dev/docs/quick-start

https://wasp-lang.dev/docs/quick-start#installation

**Content (before/after):** 

```
RootWebArea Quick Start | Wasp, focused, url='https://wasp-lang.dev/docs/quick-start'
	region Skip to main content
		link Skip to main content, url='https://wasp-lang.dev/docs/quick-start#docusaurus_skipToContent_fallback'
	banner
		StaticText Wasp v0.15 is here!
```
<details><summary>Show more</summary>

```
		StaticText 🐝
		[1095] link See what's new ⚙️, center=(1037,14), url='https://wasp-lang.dev/blog/2024/09/30/wasp-launch-week-7'
	navigation Main
		[1101] link Wasp logo .wasp (beta), center=(85,60), inner_text=.wasp (beta), url='https://wasp-lang.dev/'
			image Wasp logo, url='https://wasp-lang.dev/img/wasp-logo-eqpar-circle.png'
		[1105] link Docs, center=(202,60), url='https://wasp-lang.dev/docs'
		[1107] button 0.15.0, center=(277,60), expanded=False, hasPopup='menu'
		[1119] link Blog, center=(350,60), url='https://wasp-lang.dev/blog'
		[1121] link, center=(1645,60), url='https://github.com/wasp-lang/wasp'
		[1122] link, center=(1669,60), url='https://twitter.com/WaspLang'
		[1123] link, center=(1693,60), url='https://discord.gg/rzdnErX'
		[1125] button Switch between dark and light mode (currently light mode), center=(1721,60), title=Switch between dark and light mode (currently light mode), type=button
			image
		[1129] button Search, center=(1826,60), inner_text=Search
K, type=button
			image
			image
			StaticText K
	complementary
		navigation Docs sidebar
			list
				listitem
					[1148] link Getting Started, center=(146,114), expanded=True, url='https://wasp-lang.dev/docs/quick-start#'
					list
						listitem
							[1151] link Introduction, center=(152,150), url='https://wasp-lang.dev/docs'
						listitem
							[1153] link Quick Start, center=(152,186), url='https://wasp-lang.dev/docs/quick-start'
						listitem
							[1155] link Editor Setup, center=(152,222), url='https://wasp-lang.dev/docs/editor-setup'
				listitem
					[1158] link Tutorial, center=(146,270), expanded=True, url='https://wasp-lang.dev/docs/quick-start#'
					list
						listitem
							[1161] link 1. Creating a New Project, center=(152,306), url='https://wasp-lang.dev/docs/tutorial/create'
						listitem
							[1163] link 2. Project Structure, center=(152,342), url='https://wasp-lang.dev/docs/tutorial/project-structure'
						listitem
							[1165] link 3. Pages & Routes, center=(152,378), url='https://wasp-lang.dev/docs/tutorial/pages'
						listitem
							[1167] link 4. Database Entities, center=(152,414), url='https://wasp-lang.dev/docs/tutorial/entities'
						listitem
							[1169] link 5. Querying the Database, center=(152,450), url='https://wasp-lang.dev/docs/tutorial/queries'
						listitem
							[1171] link 6. Modifying Data, center=(152,486), url='https://wasp-lang.dev/docs/tutorial/actions'
						listitem
							[1173] link 7. Adding Authentication, center=(152,522), url='https://wasp-lang.dev/docs/tutorial/auth'
				listitem
					[1175] link Examples, center=(146,570), url='https://github.com/wasp-lang/wasp/tree/release/examples'
				listitem
					[1179] link Data Model, center=(146,618), expanded=True, url='https://wasp-lang.dev/docs/quick-start#'
					list
						listitem
							[1182] link Entities, center=(152,654), url='https://wasp-lang.dev/docs/data-model/entities'
						listitem
							[1185] link Operations, center=(152,690), expanded=False, url='https://wasp-lang.dev/docs/quick-start#'
						listitem
							[1187] link Automatic CRUD, center=(152,726), url='https://wasp-lang.dev/docs/data-model/crud'
						listitem
							[1189] link Databases, center=(152,762), url='https://wasp-lang.dev/docs/data-model/backends'
						listitem
							[1191] link Prisma Schema File, center=(152,798), url='https://wasp-lang.dev/docs/data-model/prisma-file'
				listitem
					[1194] link Authentication, center=(146,846), expanded=True, url='https://wasp-lang.dev/docs/quick-start#'
					list
						listitem
							[1197] link Overview, center=(152,882), url='https://wasp-lang.dev/docs/auth/overview'
						listitem
							[1199] link Auth UI, center=(152,918), url='https://wasp-lang.dev/docs/auth/ui'
						listitem
							[1201] link Username & Password, center=(152,954), url='https://wasp-lang.dev/docs/auth/username-and-pass'
						listitem
							[1203] link Email, center=(152,990), url='https://wasp-lang.dev/docs/auth/email'
						listitem
							[1206] link Social Auth, center=(152,1026), expanded=False, url='https://wasp-lang.dev/docs/quick-start#'
						listitem
							[1208] link Accessing User Data, center=(152,1062), url='https://wasp-lang.dev/docs/auth/entities'
						listitem
							link Auth Hooks, url='https://wasp-lang.dev/docs/auth/auth-hooks'
				listitem
					link Project Setup, expanded=True, url='https://wasp-lang.dev/docs/quick-start#'
					list
						listitem
							link Starter Templates, url='https://wasp-lang.dev/docs/project/starter-templates'
						listitem
							link Customizing the App, url='https://wasp-lang.dev/docs/project/customizing-app'
						listitem
							link Client Config, url='https://wasp-lang.dev/docs/project/client-config'
						listitem
							link Server Config, url='https://wasp-lang.dev/docs/project/server-config'
						listitem
							link Static Asset Handling, url='https://wasp-lang.dev/docs/project/static-assets'
						listitem
							link Env Variables, url='https://wasp-lang.dev/docs/project/env-vars'
						listitem
							link Testing, url='https://wasp-lang.dev/docs/project/testing'
						listitem
							link Dependencies, url='https://wasp-lang.dev/docs/project/dependencies'
						listitem
							link CSS Frameworks, url='https://wasp-lang.dev/docs/project/css-frameworks'
						listitem
							link Custom Vite Config, url='https://wasp-lang.dev/docs/project/custom-vite-config'
				listitem
					link Wasp AI, expanded=True, url='https://wasp-lang.dev/docs/quick-start#'
					list
						listitem
							link Creating New App with AI, url='https://wasp-lang.dev/docs/wasp-ai/creating-new-app'
						listitem
							link Developing Existing App with AI, url='https://wasp-lang.dev/docs/wasp-ai/developing-existing-app'
				listitem
					link Advanced Features, expanded=True, url='https://wasp-lang.dev/docs/quick-start#'
					list
						listitem
							link Sending Emails, url='https://wasp-lang.dev/docs/advanced/email'
						listitem
							link Recurring Jobs, url='https://wasp-lang.dev/docs/advanced/jobs'
						listitem
							link Web Sockets, url='https://wasp-lang.dev/docs/advanced/web-sockets'
						listitem
							link Accessing the configuration, url='https://wasp-lang.dev/docs/advanced/accessing-app-config'
						listitem
							link Custom HTTP API Endpoints, url='https://wasp-lang.dev/docs/advanced/apis'
						listitem
							link Configuring Middleware, url='https://wasp-lang.dev/docs/advanced/middleware-config'
						listitem
							link Type-Safe Links, url='https://wasp-lang.dev/docs/advanced/links'
				listitem
					link Deployment, expanded=True, url='https://wasp-lang.dev/docs/quick-start#'
					list
						listitem
							link Overview, url='https://wasp-lang.dev/docs/advanced/deployment/overview'
						listitem
							link Deploying with the Wasp CLI, url='https://wasp-lang.dev/docs/advanced/deployment/cli'
						listitem
							link Deploying Manually, url='https://wasp-lang.dev/docs/advanced/deployment/manually'
				listitem
					link General, expanded=True, url='https://wasp-lang.dev/docs/quick-start#'
					list
						listitem
							link Wasp Language (.wasp), url='https://wasp-lang.dev/docs/general/language'
						listitem
							link CLI Reference, url='https://wasp-lang.dev/docs/general/cli'
						listitem
							link TypeScript Support, url='https://wasp-lang.dev/docs/general/typescript'
						listitem
							link Wasp TypeScript config (*.wasp.ts), url='https://wasp-lang.dev/docs/general/wasp-ts-config'
				listitem
					link Migration guides, expanded=False, url='https://wasp-lang.dev/docs/quick-start#'
				listitem
					link Miscellaneous, expanded=False, url='https://wasp-lang.dev/docs/quick-start#'
	main
		article
			navigation Breadcrumbs
				list
					listitem
						[2318] link Home page, center=(377,121), url='https://wasp-lang.dev/'
							image
					[2320] listitem, center=(488,121), inner_text=Getting Started
						StaticText Getting Started
					[2323] listitem, center=(599,121), inner_text=Quick Start
						StaticText Quick Start
			StaticText Version: 0.15.0
			heading Quick Start
			heading Installation Direct link to Installation
				[2333] link Direct link to Installation, center=(540,278), inner_text=​, title=Direct link to Installation, url='https://wasp-lang.dev/docs/quick-start#installation'
					StaticText ​
			paragraph
				StaticText Welcome, new Waspeteer 🐝!
			paragraph
				StaticText Let's create and run our first Wasp app in 3 short steps:
			list
				listitem
					ListMarker 0.
					paragraph
						strong
							StaticText To install Wasp on Linux / OSX / WSL (Windows), open your terminal and run:
					code
						StaticText curl
						StaticText -sSL https://get.wasp-lang.dev/installer.sh
						StaticText |
						StaticText sh
					[2352] button Copy code to clipboard, center=(1454,475), title=Copy, type=button
					paragraph
						StaticText ℹ️ Wasp requires Node.js and will warn you if it is missing: check below for
						[2357] link more details, center=(1016,531), url='https://wasp-lang.dev/docs/quick-start#requirements'
						StaticText .
				listitem
					ListMarker 0.
					paragraph
						strong
							StaticText Then, create a new app by running:
					code
						StaticText wasp new
					[2369] button Copy code to clipboard, center=(1454,632), title=Copy, type=button
				listitem
					ListMarker 0.
					paragraph
						strong
							StaticText Finally, run the app:
					code
						StaticText cd
						StaticText <
						StaticText my-project-name
						StaticText >
						StaticText wasp start
					[2392] button Copy code to clipboard, center=(1454,745), title=Copy, type=button
			paragraph
				StaticText That's it 🎉 You have successfully created and served a new full-stack web app at
				[2397] link http://localhost:3000, center=(1066,819), url='http://localhost:3000/'
				StaticText and Wasp is serving both frontend and backend for you.
			image
			StaticText SOMETHING UNCLEAR?
			paragraph
				StaticText Check
				[2404] link More Details, center=(480,934), url='https://wasp-lang.dev/docs/quick-start#more-details'
				StaticText section below if anything went wrong with the installation, or if you have additional questions.
			image
			StaticText WANT AN EVEN FASTER START?
			paragraph
				StaticText Try out
				[2411] link Wasp AI, center=(468,1037), url='https://wasp-lang.dev/docs/wasp-ai/creating-new-app'
				StaticText 🤖 to generate a new Wasp app in minutes just from a title and short description!
			image
			StaticText TRY WASP WITHOUT INSTALLING 🤔?
			paragraph
				StaticText Give Wasp a spin in the browser with GitHub Codespaces by following the intructions in our
				link Tutorial App README, url='https://github.com/wasp-lang/wasp/tree/release/examples/tutorials/TodoApp'
			heading What next? Direct link to What next?
				link Direct link to What next?, url='https://wasp-lang.dev/docs/quick-start#what-next'
					StaticText ​
			list
				listitem
					checkbox, checked='false', disabled=True
					StaticText 👉
					strong
						StaticText Check out the
						link Todo App tutorial, url='https://wasp-lang.dev/docs/tutorial/create'
						StaticText , which will take you through all the core features of Wasp!
					StaticText 👈
				listitem
					checkbox, checked='false', disabled=True
					link Setup your editor, url='https://wasp-lang.dev/docs/editor-setup'
					StaticText for working with Wasp.
				listitem
					checkbox, checked='false', disabled=True
					StaticText Join us on
					link Discord, url='https://discord.gg/rzdnErX'
					StaticText ! Any feedback or questions you have, we are there for you.
				listitem
					checkbox, checked='false', disabled=True
					StaticText Follow Wasp development by subscribing to our newsletter:
					link https://wasp-lang.dev/#signup, url='https://wasp-lang.dev/#signup'
					StaticText . We usually send 1 per month, and
					link Matija, url='https://github.com/matijaSos'
					StaticText does his best to unleash his creativity to make them engaging and fun to read :D!
			separator, orientation='horizontal'
			heading More details Direct link to More details
				link Direct link to More details, url='https://wasp-lang.dev/docs/quick-start#more-details'
					StaticText ​
			heading Requirements Direct link to Requirements
				link Direct link to Requirements, url='https://wasp-lang.dev/docs/quick-start#requirements'
					StaticText ​
			paragraph
				StaticText You must have Node.js (and NPM) installed on your machine and available in
				code
					StaticText PATH
				StaticText . A version of Node.js must be >= 18.
			paragraph
				StaticText If you need it, we recommend using
				link nvm, url='https://github.com/nvm-sh/nvm'
				StaticText for managing your Node.js installation version(s).
			group
				DisclosureTriangle A quick guide on installing/using nvm, expanded=False
			heading Installation Direct link to Installation
				link Direct link to Installation, url='https://wasp-lang.dev/docs/quick-start#installation-1'
					StaticText ​
			tablist, orientation='horizontal'
				tab Linux / macOS, selected=True
				tab Windows, selected=False
				tab From source, selected=False
			tabpanel
				paragraph
					StaticText Open your terminal and run:
				code
					StaticText curl
					StaticText -sSL https://get.wasp-lang.dev/installer.sh
					StaticText |
					StaticText sh
				button Copy code to clipboard
				image
				StaticText RUNNING WASP ON MAC WITH MX CHIP (ARM64)
				paragraph
					strong
						StaticText Experiencing the 'Bad CPU type in executable' issue on a device with arm64 (Apple Silicon)?
					StaticText Given that the wasp binary is built for x86 and not for arm64 (Apple Silicon), you'll need to install
					link Rosetta on your Mac, url='https://support.apple.com/en-us/HT211861'
					StaticText if you are using a Mac with Mx (M1, M2, ...). Rosetta is a translation process that enables users to run applications designed for x86 on arm64 (Apple Silicon). To install Rosetta, run the following command in your terminal
				code
					StaticText softwareupdate --install-rosetta
				button Copy code to clipboard
				paragraph
					StaticText Once Rosetta is installed, you should be able to run Wasp without any issues.
			link Edit this page, url='https://github.com/wasp-lang/wasp/edit/release/web/versioned_docs/version-0.15.0/introduction/quick-start.md'
		navigation Docs pages navigation
			link Previous « Introduction, url='https://wasp-lang.dev/docs'
			link Next Editor Setup », url='https://wasp-lang.dev/docs/editor-setup'
		list
			listitem
				[2592] link Installation, center=(1690,132), url='https://wasp-lang.dev/docs/quick-start#installation'
				list
					listitem
						[2595] link What next?, center=(1694,159), url='https://wasp-lang.dev/docs/quick-start#what-next'
			listitem
				[2597] link More details, center=(1690,186), url='https://wasp-lang.dev/docs/quick-start#more-details'
				list
					listitem
						[2600] link Requirements, center=(1694,213), url='https://wasp-lang.dev/docs/quick-start#requirements'
					listitem
						[2602] link Installation, center=(1694,240), url='https://wasp-lang.dev/docs/quick-start#installation-1'
	contentinfo
		StaticText Docs
		list
			listitem
				link Getting started, url='https://wasp-lang.dev/docs'
			listitem
				link Todo app tutorial, url='https://wasp-lang.dev/docs/tutorial/create'
		StaticText Community
		list
			listitem
				link Discord, url='https://discord.gg/rzdnErX'
		StaticText More
		list
			listitem
				link GitHub, url='https://github.com/wasp-lang/wasp'
			listitem
				link Contact, url='https://wasp-lang.dev/docs/contact'
		StaticText Copyright © 2024 Wasp.
```
</details>



```
RootWebArea Quick Start | Wasp, focused, url='https://wasp-lang.dev/docs/quick-start#installation'
	region Skip to main content
		link Skip to main content, url='https://wasp-lang.dev/docs/quick-start#docusaurus_skipToContent_fallback'
	banner
		StaticText Wasp v0.15 is here!
```
<details><summary>Show more</summary>

```
		StaticText 🐝
		link See what's new ⚙️, url='https://wasp-lang.dev/blog/2024/09/30/wasp-launch-week-7'
	navigation Main
		[1101] link Wasp logo .wasp (beta), center=(85,220), inner_text=.wasp (beta), url='https://wasp-lang.dev/'
			image Wasp logo, url='https://wasp-lang.dev/img/wasp-logo-eqpar-circle.png'
		[1105] link Docs, center=(202,220), url='https://wasp-lang.dev/docs'
		[1107] button 0.15.0, center=(277,220), expanded=False, hasPopup='menu'
		[1119] link Blog, center=(350,220), url='https://wasp-lang.dev/blog'
		[1121] link, center=(1645,220), url='https://github.com/wasp-lang/wasp'
		[1122] link, center=(1669,220), url='https://twitter.com/WaspLang'
		[1123] link, center=(1693,220), url='https://discord.gg/rzdnErX'
		[1125] button Switch between dark and light mode (currently light mode), center=(1721,220), title=Switch between dark and light mode (currently light mode), type=button
			image
		[1129] button Search, center=(1826,220), inner_text=Search
K, type=button
			image
			image
			StaticText K
	complementary
		navigation Docs sidebar
			list
				listitem
					[1148] link Getting Started, center=(146,274), expanded=True, url='https://wasp-lang.dev/docs/quick-start#'
					list
						listitem
							[1151] link Introduction, center=(152,310), url='https://wasp-lang.dev/docs'
						listitem
							[1153] link Quick Start, center=(152,346), url='https://wasp-lang.dev/docs/quick-start'
						listitem
							[1155] link Editor Setup, center=(152,382), url='https://wasp-lang.dev/docs/editor-setup'
				listitem
					[1158] link Tutorial, center=(146,430), expanded=True, url='https://wasp-lang.dev/docs/quick-start#'
					list
						listitem
							[1161] link 1. Creating a New Project, center=(152,466), url='https://wasp-lang.dev/docs/tutorial/create'
						listitem
							[1163] link 2. Project Structure, center=(152,502), url='https://wasp-lang.dev/docs/tutorial/project-structure'
						listitem
							[1165] link 3. Pages & Routes, center=(152,538), url='https://wasp-lang.dev/docs/tutorial/pages'
						listitem
							[1167] link 4. Database Entities, center=(152,574), url='https://wasp-lang.dev/docs/tutorial/entities'
						listitem
							[1169] link 5. Querying the Database, center=(152,610), url='https://wasp-lang.dev/docs/tutorial/queries'
						listitem
							[1171] link 6. Modifying Data, center=(152,646), url='https://wasp-lang.dev/docs/tutorial/actions'
						listitem
							[1173] link 7. Adding Authentication, center=(152,682), url='https://wasp-lang.dev/docs/tutorial/auth'
				listitem
					[1175] link Examples, center=(146,730), url='https://github.com/wasp-lang/wasp/tree/release/examples'
				listitem
					[1179] link Data Model, center=(146,778), expanded=True, url='https://wasp-lang.dev/docs/quick-start#'
					list
						listitem
							[1182] link Entities, center=(152,814), url='https://wasp-lang.dev/docs/data-model/entities'
						listitem
							[1185] link Operations, center=(152,850), expanded=False, url='https://wasp-lang.dev/docs/quick-start#'
						listitem
							[1187] link Automatic CRUD, center=(152,886), url='https://wasp-lang.dev/docs/data-model/crud'
						listitem
							[1189] link Databases, center=(152,922), url='https://wasp-lang.dev/docs/data-model/backends'
						listitem
							[1191] link Prisma Schema File, center=(152,958), url='https://wasp-lang.dev/docs/data-model/prisma-file'
				listitem
					[1194] link Authentication, center=(146,1006), expanded=True, url='https://wasp-lang.dev/docs/quick-start#'
					list
						listitem
							[1197] link Overview, center=(152,1042), url='https://wasp-lang.dev/docs/auth/overview'
						listitem
							[1199] link Auth UI, center=(152,1078), url='https://wasp-lang.dev/docs/auth/ui'
						listitem
							[1201] link Username & Password, center=(152,1114), url='https://wasp-lang.dev/docs/auth/username-and-pass'
						listitem
							[1203] link Email, center=(152,1150), url='https://wasp-lang.dev/docs/auth/email'
						listitem
							[1206] link Social Auth, center=(152,1186), expanded=False, url='https://wasp-lang.dev/docs/quick-start#'
						listitem
							[1208] link Accessing User Data, center=(152,1222), url='https://wasp-lang.dev/docs/auth/entities'
						listitem
							[1210] link Auth Hooks, center=(152,1258), url='https://wasp-lang.dev/docs/auth/auth-hooks'
				listitem
					link Project Setup, expanded=True, url='https://wasp-lang.dev/docs/quick-start#'
					list
						listitem
							link Starter Templates, url='https://wasp-lang.dev/docs/project/starter-templates'
						listitem
							link Customizing the App, url='https://wasp-lang.dev/docs/project/customizing-app'
						listitem
							link Client Config, url='https://wasp-lang.dev/docs/project/client-config'
						listitem
							link Server Config, url='https://wasp-lang.dev/docs/project/server-config'
						listitem
							link Static Asset Handling, url='https://wasp-lang.dev/docs/project/static-assets'
						listitem
							link Env Variables, url='https://wasp-lang.dev/docs/project/env-vars'
						listitem
							link Testing, url='https://wasp-lang.dev/docs/project/testing'
						listitem
							link Dependencies, url='https://wasp-lang.dev/docs/project/dependencies'
						listitem
							link CSS Frameworks, url='https://wasp-lang.dev/docs/project/css-frameworks'
						listitem
							link Custom Vite Config, url='https://wasp-lang.dev/docs/project/custom-vite-config'
				listitem
					link Wasp AI, expanded=True, url='https://wasp-lang.dev/docs/quick-start#'
					list
						listitem
							link Creating New App with AI, url='https://wasp-lang.dev/docs/wasp-ai/creating-new-app'
						listitem
							link Developing Existing App with AI, url='https://wasp-lang.dev/docs/wasp-ai/developing-existing-app'
				listitem
					link Advanced Features, expanded=True, url='https://wasp-lang.dev/docs/quick-start#'
					list
						listitem
							link Sending Emails, url='https://wasp-lang.dev/docs/advanced/email'
						listitem
							link Recurring Jobs, url='https://wasp-lang.dev/docs/advanced/jobs'
						listitem
							link Web Sockets, url='https://wasp-lang.dev/docs/advanced/web-sockets'
						listitem
							link Accessing the configuration, url='https://wasp-lang.dev/docs/advanced/accessing-app-config'
						listitem
							link Custom HTTP API Endpoints, url='https://wasp-lang.dev/docs/advanced/apis'
						listitem
							link Configuring Middleware, url='https://wasp-lang.dev/docs/advanced/middleware-config'
						listitem
							link Type-Safe Links, url='https://wasp-lang.dev/docs/advanced/links'
				listitem
					link Deployment, expanded=True, url='https://wasp-lang.dev/docs/quick-start#'
					list
						listitem
							link Overview, url='https://wasp-lang.dev/docs/advanced/deployment/overview'
						listitem
							link Deploying with the Wasp CLI, url='https://wasp-lang.dev/docs/advanced/deployment/cli'
						listitem
							link Deploying Manually, url='https://wasp-lang.dev/docs/advanced/deployment/manually'
				listitem
					link General, expanded=True, url='https://wasp-lang.dev/docs/quick-start#'
					list
						listitem
							link Wasp Language (.wasp), url='https://wasp-lang.dev/docs/general/language'
						listitem
							link CLI Reference, url='https://wasp-lang.dev/docs/general/cli'
						listitem
							link TypeScript Support, url='https://wasp-lang.dev/docs/general/typescript'
						listitem
							link Wasp TypeScript config (*.wasp.ts), url='https://wasp-lang.dev/docs/general/wasp-ts-config'
				listitem
					link Migration guides, expanded=False, url='https://wasp-lang.dev/docs/quick-start#'
				listitem
					link Miscellaneous, expanded=False, url='https://wasp-lang.dev/docs/quick-start#'
	main
		article
			navigation Breadcrumbs
				list
					listitem
						link Home page, url='https://wasp-lang.dev/'
							image
					listitem
						StaticText Getting Started
					listitem
						StaticText Quick Start
			StaticText Version: 0.15.0
			heading Quick Start
			heading Installation Direct link to Installation
				[2333] link Direct link to Installation, center=(540,278), inner_text=​, title=Direct link to Installation, url='https://wasp-lang.dev/docs/quick-start#installation'
					StaticText ​
			paragraph
				StaticText Welcome, new Waspeteer 🐝!
			paragraph
				StaticText Let's create and run our first Wasp app in 3 short steps:
			list
				listitem
					ListMarker 0.
					paragraph
						strong
							StaticText To install Wasp on Linux / OSX / WSL (Windows), open your terminal and run:
					code
						StaticText curl
						StaticText -sSL https://get.wasp-lang.dev/installer.sh
						StaticText |
						StaticText sh
					[2352] button Copy code to clipboard, center=(1454,475), title=Copy, type=button
					paragraph
						StaticText ℹ️ Wasp requires Node.js and will warn you if it is missing: check below for
						[2357] link more details, center=(1016,531), url='https://wasp-lang.dev/docs/quick-start#requirements'
						StaticText .
				listitem
					ListMarker 0.
					paragraph
						strong
							StaticText Then, create a new app by running:
					code
						StaticText wasp new
					[2369] button Copy code to clipboard, center=(1454,632), title=Copy, type=button
				listitem
					ListMarker 0.
					paragraph
						strong
							StaticText Finally, run the app:
					code
						StaticText cd
						StaticText <
						StaticText my-project-name
						StaticText >
						StaticText wasp start
					[2392] button Copy code to clipboard, center=(1454,745), title=Copy, type=button
			paragraph
				StaticText That's it 🎉 You have successfully created and served a new full-stack web app at
				[2397] link http://localhost:3000, center=(1066,819), url='http://localhost:3000/'
				StaticText and Wasp is serving both frontend and backend for you.
			image
			StaticText SOMETHING UNCLEAR?
			paragraph
				StaticText Check
				[2404] link More Details, center=(480,934), url='https://wasp-lang.dev/docs/quick-start#more-details'
				StaticText section below if anything went wrong with the installation, or if you have additional questions.
			image
			StaticText WANT AN EVEN FASTER START?
			paragraph
				StaticText Try out
				[2411] link Wasp AI, center=(468,1037), url='https://wasp-lang.dev/docs/wasp-ai/creating-new-app'
				StaticText 🤖 to generate a new Wasp app in minutes just from a title and short description!
			image
			StaticText TRY WASP WITHOUT INSTALLING 🤔?
			paragraph
				StaticText Give Wasp a spin in the browser with GitHub Codespaces by following the intructions in our
				[2418] link Tutorial App README, center=(1160,1139), url='https://github.com/wasp-lang/wasp/tree/release/examples/tutorials/TodoApp'
			heading What next? Direct link to What next?
				[2420] link Direct link to What next?, center=(500,1212), inner_text=​, title=Direct link to What next?, url='https://wasp-lang.dev/docs/quick-start#what-next'
					StaticText ​
			list
				listitem
					[2423] checkbox, center=(368,1259), checked='false', type=checkbox
					StaticText 👉
					strong
						StaticText Check out the
						[2425] link Todo App tutorial, center=(590,1259), url='https://wasp-lang.dev/docs/tutorial/create'
						StaticText , which will take you through all the core features of Wasp!
					StaticText 👈
				listitem
					checkbox, checked='false', disabled=True
					link Setup your editor, url='https://wasp-lang.dev/docs/editor-setup'
					StaticText for working with Wasp.
				listitem
					checkbox, checked='false', disabled=True
					StaticText Join us on
					link Discord, url='https://discord.gg/rzdnErX'
					StaticText ! Any feedback or questions you have, we are there for you.
				listitem
					checkbox, checked='false', disabled=True
					StaticText Follow Wasp development by subscribing to our newsletter:
					link https://wasp-lang.dev/#signup, url='https://wasp-lang.dev/#signup'
					StaticText . We usually send 1 per month, and
					link Matija, url='https://github.com/matijaSos'
					StaticText does his best to unleash his creativity to make them engaging and fun to read :D!
			separator, orientation='horizontal'
			heading More details Direct link to More details
				link Direct link to More details, url='https://wasp-lang.dev/docs/quick-start#more-details'
					StaticText ​
			heading Requirements Direct link to Requirements
				link Direct link to Requirements, url='https://wasp-lang.dev/docs/quick-start#requirements'
					StaticText ​
			paragraph
				StaticText You must have Node.js (and NPM) installed on your machine and available in
				code
					StaticText PATH
				StaticText . A version of Node.js must be >= 18.
			paragraph
				StaticText If you need it, we recommend using
				link nvm, url='https://github.com/nvm-sh/nvm'
				StaticText for managing your Node.js installation version(s).
			group
				DisclosureTriangle A quick guide on installing/using nvm, expanded=False
			heading Installation Direct link to Installation
				link Direct link to Installation, url='https://wasp-lang.dev/docs/quick-start#installation-1'
					StaticText ​
			tablist, orientation='horizontal'
				tab Linux / macOS, selected=True
				tab Windows, selected=False
				tab From source, selected=False
			tabpanel
				paragraph
					StaticText Open your terminal and run:
				code
					StaticText curl
					StaticText -sSL https://get.wasp-lang.dev/installer.sh
					StaticText |
					StaticText sh
				button Copy code to clipboard
				image
				StaticText RUNNING WASP ON MAC WITH MX CHIP (ARM64)
				paragraph
					strong
						StaticText Experiencing the 'Bad CPU type in executable' issue on a device with arm64 (Apple Silicon)?
					StaticText Given that the wasp binary is built for x86 and not for arm64 (Apple Silicon), you'll need to install
					link Rosetta on your Mac, url='https://support.apple.com/en-us/HT211861'
					StaticText if you are using a Mac with Mx (M1, M2, ...). Rosetta is a translation process that enables users to run applications designed for x86 on arm64 (Apple Silicon). To install Rosetta, run the following command in your terminal
				code
					StaticText softwareupdate --install-rosetta
				button Copy code to clipboard
				paragraph
					StaticText Once Rosetta is installed, you should be able to run Wasp without any issues.
			link Edit this page, url='https://github.com/wasp-lang/wasp/edit/release/web/versioned_docs/version-0.15.0/introduction/quick-start.md'
		navigation Docs pages navigation
			link Previous « Introduction, url='https://wasp-lang.dev/docs'
			link Next Editor Setup », url='https://wasp-lang.dev/docs/editor-setup'
		list
			listitem
				[2592] link Installation, center=(1690,292), url='https://wasp-lang.dev/docs/quick-start#installation'
				list
					listitem
						[2595] link What next?, center=(1694,319), url='https://wasp-lang.dev/docs/quick-start#what-next'
			listitem
				[2597] link More details, center=(1690,346), url='https://wasp-lang.dev/docs/quick-start#more-details'
				list
					listitem
						[2600] link Requirements, center=(1694,373), url='https://wasp-lang.dev/docs/quick-start#requirements'
					listitem
						[2602] link Installation, center=(1694,400), url='https://wasp-lang.dev/docs/quick-start#installation-1'
	contentinfo
		StaticText Docs
		list
			listitem
				link Getting started, url='https://wasp-lang.dev/docs'
			listitem
				link Todo app tutorial, url='https://wasp-lang.dev/docs/tutorial/create'
		StaticText Community
		list
			listitem
				link Discord, url='https://discord.gg/rzdnErX'
		StaticText More
		list
			listitem
				link GitHub, url='https://github.com/wasp-lang/wasp'
			listitem
				link Contact, url='https://wasp-lang.dev/docs/contact'
		StaticText Copyright © 2024 Wasp.
```
</details>

**Reasoning for action:** By clicking the Installation link, I access the specific section that outlines the steps and prerequisites for installing Wasp. This directly advances the user's goal of understanding how to set up Wasp effectively, as it ensures they will now see the detailed installation instructions needed for their development projects.

**Action:** click(2333) # Click on the Installation link to explore the installation details for Wasp.

**Change Description:** After clicking the 'Installation' link, the browser navigated to the installation details section of the Wasp documentation, updating the URL to 'https://wasp-lang.dev/docs/quick-start#installation' and revealing content specific to installing Wasp, including commands and prerequisites.

**Screenshot before:****Screenshot after:**---

