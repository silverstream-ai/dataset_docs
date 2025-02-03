# Task

**Documentation Navigation and Resource Access**

As a developer exploring Flightcontrol resources,,
I navigate through the documentation to find specific guides and examples,,
so that I can quickly learn how to build and deploy applications using Flightcontrol with relevant resources.

**Success definition:** Given I am on the Flightcontrol Documentation page after starting from the homepage
When I click on the JavaScript link to access JavaScript resources and then click on the 'Building and Deploying a Remix project' link
Then I should see the content for 'Building and Deploying a Remix Application with Flightcontrol' with specific instructions and links for deploying a Remix application.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.flightcontrol.dev/?ref=bookface

https://www.flightcontrol.dev/docs

**Content (before/after):** 

```
RootWebArea Flightcontrol – The AWS experience that didn't seem possible, focused, url='https://www.flightcontrol.dev/?ref=bookface'
	banner
		[70] link FlightControl FlightControl Home, center=(384,51), inner_text=FlightControl
FlightControl Home, title=FlightControl Home, url='https://www.flightcontrol.dev/'
		navigation
```
<details><summary>Show more</summary>

```
			navigation Main
				list
					listitem
						[83] link Documentation, center=(873,51), title=Documentation, url='https://www.flightcontrol.dev/docs'
					listitem
						[85] link Pricing, center=(1008,51), title=Pricing, url='https://www.flightcontrol.dev/pricing'
					listitem
						[87] link Blog, center=(1097,51), title=Blog, url='https://www.flightcontrol.dev/blog'
					listitem
						[89] link Careers, center=(1192,51), title=Careers, url='https://www.flightcontrol.dev/careers'
					listitem
						[91] link Company, center=(1307,51), title=Company, url='https://www.flightcontrol.dev/company'
			[93] link Log in, center=(1451,51), url='https://app.flightcontrol.dev/login'
			[99] link Start free, center=(1562,51), url='https://app.flightcontrol.dev/signup'
	main
		image
		image
		heading SAY GOODBYE TO RELIABILITY AND SCALING PROBLEMS
		list
			[132] listitem, center=(712,368), inner_text=Flightcontrol is a PaaS that deploys to your AWS account
				StaticText Flightcontrol is a PaaS that deploys to your AWS account
			[133] listitem, center=(712,420), inner_text=Servers, Lambdas, workers, crons, static sites, databases & Redis
				StaticText Servers, Lambdas, workers, crons, static sites, databases & Redis
			[134] listitem, center=(712,471), inner_text=We are your devops team with 24/7 emergency support
				StaticText We are your devops team with 24/7 emergency support
			[135] listitem, center=(712,539), inner_text=Companies outgrowing other PaaS or homegrown AWS switch to Flightcontrol to regain reliability, security, and scalability at a reasonable cost
				StaticText Companies outgrowing other PaaS or homegrown AWS switch to Flightcontrol to regain reliability, security, and scalability at a reasonable cost
		[137] link Start free trial, center=(450,651), url='https://app.flightcontrol.dev/signup'
			image
		[144] link Get a demo, center=(620,651), url='https://www.flightcontrol.dev/demo'
			image
		image Flightcontrol Dashboard, url='https://www.flightcontrol.dev/_next/image?url=%2FheroImage.png&w=1080&q=75'
		heading $1 MILLION OF AWS RESOURCES UNDER MANAGEMENT
		image cal.com logo, url='https://www.datocms-assets.com/98758/1716559487-cal-logo-1.svg'
		image cascade PBS logo, url='https://www.datocms-assets.com/98758/1716506661-cascade-logo.svg'
		image drive.com.au logo, url='https://www.datocms-assets.com/98758/1716506665-drive-logo.svg'
		image Webgears logo, url='https://www.datocms-assets.com/98758/1716390279-webgears-2.svg'
		image productlane, url='https://www.datocms-assets.com/98758/1716389963-productlane-2.svg'
		image echo/bind company logo, url='https://www.datocms-assets.com/98758/1698946123-echo-bind.svg'
		image Flick company logo, url='https://www.datocms-assets.com/98758/1698946117-flick.svg'
		image goHappy logo, url='https://www.datocms-assets.com/98758/1698946202-gohappy.png'
		image Remi company logo, url='https://www.datocms-assets.com/98758/1698946102-remi.svg'
		heading SERVE ALL YOUR USE-CASES FROM A SINGLE PLATFORM
		image
		paragraph
			StaticText Static Sites
		paragraph
			StaticText CloudFront + S3 + Lambda@Edge
		image
		paragraph
			StaticText Web & GPU Servers
		paragraph
			StaticText ECS + Fargate or EC2 + CloudFront CDN
		image
		paragraph
			StaticText Private Servers
		paragraph
			StaticText ECS + Fargate or EC2
		image
		paragraph
			StaticText Background Workers
		paragraph
			StaticText ECS + Fargate or EC2
		StaticText NEW
		image
		paragraph
			StaticText Lambda
		paragraph
			StaticText Serverless functions
		image
		paragraph
			StaticText Job Scheduler
		paragraph
			StaticText Cron jobs & ad-hoc commands via ECS
		image
		paragraph
			StaticText Databases
		paragraph
			StaticText Postgres, MySQL, MariaDB via RDS
		image
		paragraph
			StaticText Redis
		paragraph
			StaticText Via ElastiCache
		image
		blockquote
			StaticText Without FlightControl it would simply not have been possible for our company to begin the migration process to AWS. They simplify so much of the AWS experience which allows primarily frontend developers such as myself to focus more on code and less on infrastructure.
		paragraph
			StaticText Thomas Kovacs
			StaticText ,
			StaticText Software Architect
		StaticText |
		paragraph
			StaticText Webgears
		blockquote
			StaticText “Flightcontrol offers a nice balance between batteries-included and escape hatches that I haven't seen elsewhere. Keep up the good work and let us know if you need anything!”
		paragraph
			StaticText Matt Davis
			StaticText ,
			StaticText Head of Technology
		StaticText |
		paragraph
			StaticText Spring Studios
		blockquote
			StaticText Said it before but gonna shout it out again. Flightcontrol is the best PaaS on the market hands down. As a FE Lead who does not want to worry about devops its 100% worth the price.
		paragraph
			StaticText Aaron Rackley
			StaticText ,
			StaticText Front-end Lead
		StaticText |
		paragraph
			StaticText Wedtech
		blockquote
			StaticText We've been migrating our Rails app off of Heroku and onto AWS via Flightcontrol. The team is AWESOME and have built an excellent product. So good. ⭐⭐⭐⭐⭐
		paragraph
			StaticText Joel Hooks
			StaticText ,
			StaticText CEO
		StaticText |
		paragraph
			StaticText Egghead
		blockquote
			StaticText Nothing else compares for balance between control, flexibility and simplicity. A perfect fit for us. For our multiple locale deployments, 3-5 million monthly page views, use case, the Flightcontrol team were incredibly helpful in getting us setup + ensuring we understood what we had. 10/10
		paragraph
			StaticText Tim Booker
			StaticText ,
			StaticText COO
		StaticText |
		paragraph
			StaticText Lineup Publishing
		image
		Iframe
			RootWebArea Flightcontrol demo, url='https://www.loom.com/embed/6eb0a3dfd96846dfb560be9e291cd461?sid=6cef064c-9b53-4686-b9a9-7d7802bf024c'
				main
					image, url='https://cdn.loom.com/avatars/13513435_2b683f3a6b04463895c451b2de34a242_192.jpg'
					[a64] link Flightcontrol demo, center=(534,2773), url='https://www.loom.com/share/6eb0a3dfd96846dfb560be9e291cd461'
					image
					StaticText 4 min
					[a77] button Copy Link, center=(1440,2773)
						image
					[a82] link Open video in Loom, center=(1480,2771), url='https://www.loom.com/share/6eb0a3dfd96846dfb560be9e291cd461'
						button Open video in Loom
							image
					[a87] button Play the video, center=(960,3135)
						image
					image
					StaticText 0.8
					StaticText ×
					image
					StaticText 1
					StaticText ×
					image
					StaticText 1.2
					StaticText ×
					[a112] image, center=(945,3231)
					StaticText 1.5
					StaticText ×
					image
					StaticText 1.7
					StaticText ×
					image
					StaticText 2
					StaticText ×
					image
					StaticText 2.5
					StaticText ×
					StaticText 4 min
					StaticText ⚡️
					StaticText 4 min 27 sec
					StaticText 3 min 34 sec
					StaticText 2 min 58 sec
					StaticText 2 min 22 sec
					StaticText 2 min 5 sec
					StaticText 1 min 47 sec
					StaticText 1 min 25 sec
					slider value='50', orientation='horizontal'
						image thumb
						StaticText Introduction
						time
					image, url='https://cdn.loom.com/avatars/13513435_2b683f3a6b04463895c451b2de34a242_192.jpg'
					link Flightcontrol demo, url='https://www.loom.com/share/6eb0a3dfd96846dfb560be9e291cd461'
					image
					StaticText 4 min
					button Copy Link
						image
					link Open video in Loom, url='https://www.loom.com/share/6eb0a3dfd96846dfb560be9e291cd461'
						button Open video in Loom
							image
					button Play the video
						image
					image
					StaticText 0.8
					StaticText ×
					image
					StaticText 1
					StaticText ×
					image
					StaticText 1.2
					StaticText ×
					image
					StaticText 1.5
					StaticText ×
					image
					StaticText 1.7
					StaticText ×
					image
					StaticText 2
					StaticText ×
					image
					StaticText 2.5
					StaticText ×
					StaticText 4 min
					StaticText ⚡️
					StaticText 4 min 27 sec
					StaticText 3 min 34 sec
					StaticText 2 min 58 sec
					StaticText 2 min 22 sec
					StaticText 2 min 5 sec
					StaticText 1 min 47 sec
					StaticText 1 min 25 sec
					slider value='50', orientation='horizontal'
						image thumb
						StaticText Introduction
						time
		image
		blockquote
			StaticText Two large SaaS businesses I’m involved in have all deployed on Flightcontrol for years, and have had no issues. Infra devops cut down to zero! Deploying and scaling infra has been a dream. I can’t imagine why anyone in their sane mind not try Flightcontrol
		paragraph
			StaticText Andreas Asprou
			StaticText ,
			StaticText CTO
		StaticText |
		paragraph
			StaticText Flick & Dweet
		blockquote
			StaticText I've been using Flightcontrol for a long time, and I've never had a product that's given me better support. They have been so awesome and easy to work with. Being able to deploy things using AWS credits made a lot of things possible for me what weren't on other platforms.
		paragraph
			StaticText Leo Guinan
			StaticText ,
			StaticText Founder
		StaticText |
		paragraph
			StaticText Multiple
		blockquote
			StaticText We're using Flightcontrol at Productlane and love it. We moved from Fly.io to Railway to Flightcontrol and finally found the right platform for us that works reliably and didn't have random downtime.
		paragraph
			StaticText Raphael Fleckenstein
			StaticText ,
			StaticText CEO
		StaticText |
		paragraph
			StaticText Productlane
		blockquote
			StaticText We're using Flightcontrol at Tono Health and it has completely solved our lack of devops expertise. With the new CI build runners, it also cut our build time in HALF compared to GitHub Actions. We're so happy with Flightcontrol
		paragraph
			StaticText Ethan Cohen
			StaticText ,
			StaticText CTO
		StaticText |
		paragraph
			StaticText Tono Health
		image
		heading WHY YOUR AWS? BECAUSE YOU GET SUPERIOR PRICE-PERFORMANCE-RELIABILITY
		paragraph
			StaticText AWS has its flaws, but it's world-class at reliability and flexibility. With Flightcontrol you get the best of both worlds, great developer experience and utmost reliability and performance.
		table
			rowgroup
				row
					columnheader
					columnheader Flightcontrol
					columnheader Render
					columnheader Railway
					columnheader Fly
					columnheader Vercel
			rowgroup
				row
					rowheader Infra incidents over 90 days
					cell 1
						link 1, url='https://health.aws.amazon.com/health/status'
					cell 11
						link 11, url='https://status.render.com/'
					cell 18
						link 18, url='https://status.railway.app/'
					cell 39
						link 39, url='https://status.flyio.net/'
					cell 24
						link 24, url='https://www.vercel-status.com/'
				row
					rowheader Compute cost for 2 CPU / 4 GB
					cell $27burstable $56sustained reserved
						link $27burstable, url='https://instances.vantage.sh/aws/ec2/t3a.medium'
						link $56sustained, url='https://instances.vantage.sh/aws/ec2/c6a.large'
						switch reserved, checked='false'
						LabelText
							StaticText reserved
					cell $85
						link $85, url='https://render.com/pricing'
					cell $80
						link $80, url='https://railway.app/pricing'
					cell $62
						link $62, url='https://fly.io/pricing'
					cell n/a
				row
					rowheader Largest compute
					cell 448 CPU 24 TB
						link 448 CPU 24 TB, url='https://instances.vantage.sh/aws/ec2/u-24tb1.112xlarge'
					cell 8 CPU/32 GB Enterprise: 64 CPU/512 GB
						link 8 CPU/32 GB Enterprise: 64 CPU/512 GB, url='https://render.com/pricing'
					cell 32 CPU/32 GB Enterprise: custom
						link 32 CPU/32 GB Enterprise: custom, url='https://railway.app/pricing'
					cell 16 CPU/128 GB
						link 16 CPU/128 GB, url='https://fly.io/pricing'
					cell 1.7 CPU/3 GB
				row
					rowheader Regions
					cell 28
						link 28, url='https://awsregion.info/'
					cell 5
						link 5, url='https://docs.render.com/regions'
					cell 4
						link 4, url='https://docs.railway.app/reference/regions'
					cell 35
						link 35, url='https://fly.io/docs/reference/regions'
					cell 18
						link 18, url='https://vercel.com/docs/edge-network/regions#region-list'
				row
					rowheader Fully managed, ship fast
					cell
						image
					cell
						image
					cell
						image
					cell
						image
					cell
						image
				row
					rowheader CDN for compute
					cell
						image
					cell
						image
					cell
						image
					cell
						image
					cell
						image
				row
					rowheader Static sites
					cell
						image
					cell
						image
					cell
						image
					cell
						image
					cell
						image
				row
					rowheader GPUs
					cell
						image
					cell
						image
					cell
						image
					cell
						image
					cell
						image
				row
					rowheader HIPAA eligible
					cell
						image
					cell
						image
					cell Enterprise only
						image
					cell
						image
					cell Enterprise only
						image
				row
					rowheader Customize underlying infra
					cell
						image
					cell
						image
					cell
						image
					cell
						image
					cell
						image
				row
					rowheader API
					cell Basic
					cell Full
					cell Full
					cell Full
					cell Full
				row
					rowheader Protocols besides http
					cell
						image
					cell (private server only)
						image
					cell
						image
					cell
						image
					cell
						image
		paragraph
			StaticText Updated 2024-08-12
		heading 2-6X FASTER BUILDS THAN ANY OTHER PLATFORM
		paragraph
			StaticText We engineered a custom build system that uses an EC2 builder in your account for maximum performance and ultra low cost. And you have full control over the instance size.
		table
			rowgroup
				row
					columnheader
					columnheader Flightcontrol
					columnheader Render
					columnheader Railway
					columnheader Fly
					columnheader Vercel
			rowgroup
				row
					rowheader Initial provisioning
					cell 10m
					cell 0m
					cell 0m
					cell 1m
					cell 0m
				row
					rowheader Clean build(forCal.com)
						link Cal.com, url='https://github.com/calcom/cal.com'
					cell 11m 30s
					cell 9m
					cell 19m
					cell 19m
					cell 20m 30s
				row
					rowheader Cached build(forCal.com)
						link Cal.com, url='https://github.com/calcom/cal.com'
					cell 3m 35s
					cell 7m 30s
					cell 16m 15s
					cell 15m 40s
					cell 15m 20s
				row
					rowheader Deploy time(forCal.com)
						link Cal.com, url='https://github.com/calcom/cal.com'
					cell 3m 30s
					cell 4m
					cell 4m
					cell 45s
					cell 30s
		paragraph
			StaticText Updated 2024-08-12
		image
		blockquote
			StaticText “Flightcontrol is excellent devops tooling that would take time and dedicated devops engineers to build at many companies. We're very glad we found Flightcontrol. It's an amazing value for us.”
		paragraph
			StaticText Dylan
			StaticText ,
			StaticText CTO & Co-founder
		StaticText |
		paragraph
			StaticText Boardwalk Marketing
		blockquote
			StaticText “It's saving so much time and headache for me and my team. Keep up the good work, we love your product!”
		paragraph
			StaticText Johan
			StaticText ,
			StaticText CTO
		StaticText |
		paragraph
			StaticText xNomad
		blockquote
			StaticText "Flightcontrol has been a dream, and their level of support has been off the charts. I switched from Lambda to get GPU support and got magnitudes better performance at a fraction of the cost for my AI Video company."
		paragraph
			StaticText Daniel
			StaticText ,
			StaticText Founder
		StaticText |
		paragraph
			StaticText QuickVid
		blockquote
			StaticText “Flightcontrol is the real deal. I think this is the future for teams that don't have resources for SREs but still want control of their infra.”
		paragraph
			StaticText Thomas
			StaticText ,
			StaticText Co-founder
		StaticText |
		paragraph
			StaticText Unrevealed
		image
		paragraph
			StaticText Visual Config? Code config? Both!
		paragraph
			StaticText Infrastructure-as-code designed for moving fast
		image An interface showing visual config and code config side by side, url='https://www.flightcontrol.dev/_next/image?url=https%3A%2F%2Fwww.datocms-assets.com%2F98758%2F1699276422-visual-config-min.png%3Ffit%3Dcrop%26q%3D90&w=2048&q=75'
		paragraph
			StaticText Deploy close to your users
		paragraph
			StaticText Choose today from 28 AWS regions. Multi-region deploys in early access.
		image A worldmap showing edge locations, url='https://www.flightcontrol.dev/_next/image?url=https%3A%2F%2Fwww.datocms-assets.com%2F98758%2F1699276174-world-map-min.png%3Ffit%3Dcrop%26q%3D90&w=1920&q=75'
		paragraph
			StaticText Observability
		paragraph
			StaticText Stay on top of things with our metrics and alerts, or add sidecars like Datadog.
		image An interface showing server metrics, url='https://www.flightcontrol.dev/_next/image?url=https%3A%2F%2Fwww.datocms-assets.com%2F98758%2F1699276186-observability-min.png%3Ffit%3Dcrop%26q%3D90&w=1080&q=75'
		paragraph
			StaticText Nixpacks
		paragraph
			StaticText Build any language or framework without writing a Dockerfile. The modern successor to Heroku buildpacks.
		paragraph
			StaticText Stale while revalidate + Next.js & Svelte ISR
		paragraph
			StaticText Blazing fast speed with CloudFront's stale-while-revalidate support
		paragraph
			StaticText AWS cost transparency
		paragraph
			StaticText Understand exactly where the dollars are going by project, environment, and service.
		image An interface showing AWS cost, url='https://www.flightcontrol.dev/_next/image?url=https%3A%2F%2Fwww.datocms-assets.com%2F98758%2F1716389048-cost-transparency.png%3Ffit%3Dcrop%26q%3D90&w=640&q=75'
		paragraph
			StaticText Preview environments, fullstack
		paragraph
			StaticText Deploy your all your services for every pull request to a cost optimized environment.
		paragraph
			StaticText Bring your monoliths and your microservices
		paragraph
			StaticText Your architecture will work with us, no matter how big or small.
		paragraph
			StaticText Your domain, with https
		paragraph
			StaticText Connect your domain with a couple DNS records. No messing with SSL certificates.
		paragraph
			StaticText Peak edge performance
		paragraph
			StaticText World-class performance with CloudFront, Stale-While-Revalidate, and edge-based Next.js ISR. Even multi-region.
		paragraph
			StaticText Monorepos, with watch paths
		paragraph
			StaticText Put all your stuff in one place, that's fine with us. And only deploy changed files with watch paths.
		paragraph
			StaticText Maintenance mode
		paragraph
			StaticText Block traffic to your app while you're doing something important (we assume).
		paragraph
			StaticText API & deploy hooks
		paragraph
			StaticText Trigger deploys from CI. More thorough API is coming, we promise.
		paragraph
			StaticText Notifications
		paragraph
			StaticText Get alerted in Slack or email when things go south. Or when they go north.
		paragraph
			StaticText Rollback
		paragraph
			StaticText It happens to the best of us, so we've got your back when the inevitable happens.
		paragraph
			StaticText Private VPC networking
		paragraph
			StaticText Each environment is deployed to a new or existing VPC. Get private services and private databases.
		image
		image
		heading DEPLOY EVERY LANGUAGE GLOBALLY
		paragraph
			StaticText Every language and framework works beautifully in the Flightcontrol universe. Welcome home.
		heading 1. CONNECT YOUR AWS AND GITHUB WITH 1-CLICK
		paragraph
			StaticText Everything is deployed to your AWS account where you have full ownership and control. Without the frustrating limitations of black box PaaS.
		image Select a repo, try a demo and connect AWS account, url='https://www.flightcontrol.dev/_next/image?url=https%3A%2F%2Fwww.datocms-assets.com%2F98758%2F1706541367-selectrepo.png%3Ffit%3Dcrop%26q%3D90&w=1080&q=75'
		heading 2. ZERO-CONFIG OR CUSTOMIZE TO YOUR HEART'S CONTENT
		paragraph
			StaticText It will often "just work", but we also support many customizations like pulling from image registries or fine-tuning autoscaling.
		image Set up services, choose from presets, url='https://www.flightcontrol.dev/_next/image?url=https%3A%2F%2Fwww.datocms-assets.com%2F98758%2F1699390862-addservices.png%3Ffit%3Dcrop%26q%3D90&w=1920&q=75'
		heading 3. AUTOMATIC DEPLOYS WITH GIT PUSH OR WEBHOOK
		paragraph
			StaticText Fully automated infra provisioning, builds and deploys. All without having to use the AWS console.
		image See service metrics and deployments, url='https://www.flightcontrol.dev/_next/image?url=https%3A%2F%2Fwww.datocms-assets.com%2F98758%2F1699390892-servicesdeployments.png%3Ffit%3Dcrop%26q%3D90&w=1920&q=75'
		image
		heading Trusted by thousands of developers
		paragraph
			StaticText We've got your back with the most helpful, responsive support in the industry
		image
		heading Enterprise grade no matter your size
		paragraph
			StaticText Customers of all sizes rely on us for production, from startups to large enterprises
		image
		heading Save a fortune on devops costs
		paragraph
			StaticText We delay the need for infra engineers by a few years. And then we enable them to focus on more meaningful work
		image
		image
		heading YOU'RE MOMENTS AWAY FROM LAUNCH
		paragraph
			StaticText You're going to love this
		button Start free with Google
			link Start free with Google, url='https://app.flightcontrol.dev/api/auth/google/login?oAuthAction=signUp'
				image
		button Start free with GitHub
			link Start free with GitHub, url='https://app.flightcontrol.dev/api/auth/github/login?oAuthAction=signUp'
				image
		paragraph
			StaticText Or learn about the company
		link Learn more, url='https://www.flightcontrol.dev/company'
			image
	image
	contentinfo
		paragraph
			StaticText PRODUCT
		list
			listitem
				link Home, url='https://www.flightcontrol.dev/home'
			listitem
				link Docs, url='https://www.flightcontrol.dev/docs'
			listitem
				link Pricing, url='https://www.flightcontrol.dev/pricing'
		paragraph
			StaticText COMPARISONS
		list
			listitem
				link Migrate from Heroku, url='https://www.flightcontrol.dev/migrate-from-heroku-to-aws'
			listitem
				link Flightcontrol vs Porter, url='https://www.flightcontrol.dev/porter-alternatives'
		paragraph
			StaticText DOCUMENTATION
		list
			listitem
				link Service types, url='https://www.flightcontrol.dev/docs/concepts/services'
			listitem
				link Build types, url='https://www.flightcontrol.dev/docs/concepts/build-types'
			listitem
				link Preview environments, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/preview-environment'
		paragraph
			StaticText ABOUT
		list
			listitem
				link Company, url='https://www.flightcontrol.dev/company'
			listitem
				link Blog, url='https://www.flightcontrol.dev/blog'
			listitem
				link Enterprise, url='https://www.flightcontrol.dev/demo'
		StaticText FlightControl
		paragraph
			StaticText Subscribe to newsletter
		LabelText
			StaticText Email Address
		textbox Email Address
		list
			listitem
				link Twitter, url='https://twitter.com/flightcontrolhq'
					image
			listitem
				link LinkedIn, url='https://www.linkedin.com/company/flightcontrol'
					image
			listitem
				link YouTube, url='https://www.youtube.com/channel/UCSvpoW8VpRpixDn1jdDjeeg'
					image
		list
			listitem
				link Status, url='https://status.flightcontrol.dev/'
			listitem
				link Changelog, url='https://roadmap.flightcontrol.dev/changelog'
			listitem
				link Security, url='https://www.flightcontrol.dev/docs/security'
			listitem
				link Compliance, url='https://www.flightcontrol.dev/docs/security'
			listitem
				link Privacy, url='https://www.flightcontrol.dev/privacy'
			listitem
				StaticText ©
				StaticText 2025
				StaticText Blitz Revolution Inc.
			listitem
				image SOC 2 logo, url='https://www.flightcontrol.dev/_next/image?url=%2Fsoc2-logo.png&w=48&q=75'
	image
	image
	image
	image
	alert, atomic
```
</details>



```
RootWebArea Flightcontrol Documentation | Self-manage your AWS infrastructure - Flightcontrol, focused, url='https://www.flightcontrol.dev/docs'
	navigation
		[72] link Flightcontrol Logo, center=(344,32), url='https://www.flightcontrol.dev/'
			image Flightcontrol Logo, url='https://www.flightcontrol.dev/docs/img/fc-logo-black-wordmark.svg'
		[75] link Get Help, center=(1086,32), url='https://www.flightcontrol.dev/docs/troubleshooting/contacting-support'
```
<details><summary>Show more</summary>

```
		[76] link Status, center=(1150,32), url='https://status.flightcontrol.dev/'
		[77] link Roadmap, center=(1216,32), url='https://roadmap.flightcontrol.dev/roadmap'
		[78] link Changelog, center=(1297,32), url='https://roadmap.flightcontrol.dev/changelog'
		[79] button Search, center=(1452,32), inner_text=Search
K, type=button
			image
			StaticText K
		[87] link Sign Up, center=(1580,32), url='https://app.flightcontrol.dev/signup'
		[89] link Discord Discord, center=(1644,32), inner_text=Discord, url='https://discord.gg/yY8rSPrD6q'
			image Discord
	complementary
		list
			listitem
				[112] link Flightcontrol Docs, center=(363,96), url='https://www.flightcontrol.dev/docs'
			listitem
				[114] link Getting Started, center=(363,134), url='https://www.flightcontrol.dev/docs/getting-started'
					image
				list
					listitem
						[120] link First Project, center=(375,170), url='https://www.flightcontrol.dev/docs/getting-started/first-project'
					listitem
						[122] link Connecting GitHub, center=(375,208), url='https://www.flightcontrol.dev/docs/getting-started/connecting-github'
					[123] listitem, center=(375,244)
						separator, orientation='horizontal'
					listitem
						[126] link JavaScript, center=(375,282), url='https://www.flightcontrol.dev/docs/getting-started/javascript'
							image
						list
							listitem
								link Node Version, url='https://www.flightcontrol.dev/docs/getting-started/javascript/setting-node-version'
							listitem
								link Instance Size, url='https://www.flightcontrol.dev/docs/getting-started/javascript/node-fargate-instance-size'
					listitem
						[136] link Docker, center=(375,318), url='https://www.flightcontrol.dev/docs/getting-started/docker'
							image
						list
							listitem
								link Custom Dockerfile, url='https://www.flightcontrol.dev/docs/getting-started/docker/building-deploying-dockerfile'
							listitem
								link Docker Hub Images, url='https://www.flightcontrol.dev/docs/getting-started/docker/deploying-docker-hub'
							listitem
								link Amazon ECR Images, url='https://www.flightcontrol.dev/docs/getting-started/docker/deploying-docker-ecr'
							listitem
								link GitHub Container Registry, url='https://www.flightcontrol.dev/docs/getting-started/docker/github-container-registry'
							listitem
								link Automating Docker Deployments, url='https://www.flightcontrol.dev/docs/getting-started/docker/automating-docker-deployments'
					listitem
						[152] link Java, center=(375,356), url='https://www.flightcontrol.dev/docs/getting-started/java'
							image
						list
							listitem
								link Spring Boot, url='https://www.flightcontrol.dev/docs/getting-started/java/deploying-spring-boot'
					listitem
						[160] link PHP, center=(375,392), url='https://www.flightcontrol.dev/docs/getting-started/php'
							image
						list
							listitem
								link Laravel, url='https://www.flightcontrol.dev/docs/getting-started/php/deploying-laravel'
							listitem
								link PHP/Composer, url='https://www.flightcontrol.dev/docs/getting-started/php/deploying-php-composer'
					listitem
						[170] link Python, center=(375,430), url='https://www.flightcontrol.dev/docs/getting-started/python'
							image
						list
							listitem
								link Flask Deployment, url='https://www.flightcontrol.dev/docs/getting-started/python/getting-started-flask'
							listitem
								link Create a Flask App, url='https://www.flightcontrol.dev/docs/getting-started/python/creating-flask-app'
							listitem
								link Venv with Custom Commands, url='https://www.flightcontrol.dev/docs/getting-started/python/venv-custom-commands'
					listitem
						[182] link Ruby, center=(375,466), url='https://www.flightcontrol.dev/docs/getting-started/ruby'
							image
						list
							listitem
								link Rails Deployment, url='https://www.flightcontrol.dev/docs/getting-started/ruby/getting-started-rails'
							listitem
								link Using Sidekiq, url='https://www.flightcontrol.dev/docs/getting-started/ruby/using-sidekiq'
							listitem
								link Create a Rails App, url='https://www.flightcontrol.dev/docs/getting-started/ruby/creating-rails-app'
					[193] listitem, center=(375,504)
						separator, orientation='horizontal'
					listitem
						[196] link Everything Else, center=(375,540), url='https://www.flightcontrol.dev/docs/getting-started/everything-else'
			listitem
				[198] button Concepts, center=(363,578), type=button
					image
				list
					listitem
						[204] link Service Types, center=(375,614), url='https://www.flightcontrol.dev/docs/concepts/services'
					listitem
						[206] link Build Runners, center=(375,652), url='https://www.flightcontrol.dev/docs/concepts/build-runners'
					listitem
						[208] link Build Types, center=(375,688), url='https://www.flightcontrol.dev/docs/concepts/build-types'
					listitem
						[210] link Nixpacks, center=(375,726), url='https://www.flightcontrol.dev/docs/concepts/nixpacks'
					listitem
						[212] link Autoscaling, center=(375,762), url='https://www.flightcontrol.dev/docs/concepts/autoscaling'
			listitem
				[214] button Guides, center=(363,800), type=button
					image
				list
					listitem
						[220] button Flightcontrol, center=(375,836), type=button
							image
						list
							listitem
								[226] link Project Configuration, center=(387,874), url='https://www.flightcontrol.dev/docs/guides/flightcontrol/config'
							listitem
								[228] link Config with Code, center=(387,910), url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code'
									image
								list
									listitem
										[234] link Web, center=(399,948), url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/web'
									listitem
										[236] link Private Web, center=(399,984), url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/private-web'
									listitem
										link Worker, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/worker'
									listitem
										link Scheduler, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/scheduler'
									listitem
										link Lambda Function, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/lambda-function'
									listitem
										link Static Sites, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/static'
									listitem
										link RDS Database, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/rds'
									listitem
										link Redis, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/redis'
									listitem
										link Environment Variables, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/environment-variables'
							listitem
								link Config with Dashboard, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-ui'
							listitem
								link Environment Variables, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/environment-variables'
							listitem
								link Custom Domains, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/custom-domains'
							listitem
								link Logging, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/logging'
							listitem
								link Monorepo Setup, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/monorepos'
							listitem
								link Notifications, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/notifications'
							listitem
								link Preview Environments, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/preview-environment'
							listitem
								link SSO, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/sso'
					listitem
						button Amazon Web Services
							image
						list
							listitem
								link Getting Free AWS Credits, url='https://www.flightcontrol.dev/docs/guides/aws/aws-credits'
							listitem
								link Multiple AWS Accounts, url='https://www.flightcontrol.dev/docs/guides/aws/multiple-aws-accounts'
							listitem
								link Slack notification for ECS task status change, url='https://www.flightcontrol.dev/docs/guides/aws/ecs-task-status-notification'
					listitem
						button Integrations
							image
						list
							listitem
								button Datadog
									image
								list
									listitem
										link Set Up Core Datadog AWS Integration, url='https://www.flightcontrol.dev/docs/guides/integrations/datadog/setup'
									listitem
										link Metrics sidecar, url='https://www.flightcontrol.dev/docs/guides/integrations/datadog/metrics'
							listitem
								button Sentry
									image
								list
									listitem
										link Source Maps, url='https://www.flightcontrol.dev/docs/guides/integrations/sentry/uploading-source-maps'
							listitem
								link Logging with Firelens, url='https://www.flightcontrol.dev/docs/guides/integrations/logging'
					listitem
						button Advanced
							image
						list
							listitem
								link Watch Paths, url='https://www.flightcontrol.dev/docs/guides/advanced/watch-paths'
							listitem
								link Database Migrations, url='https://www.flightcontrol.dev/docs/guides/advanced/database-migrations'
							listitem
								link Pre-deploy Command, url='https://www.flightcontrol.dev/docs/guides/advanced/predeploy-command'
							listitem
								link Post-deploy Command, url='https://www.flightcontrol.dev/docs/guides/advanced/postdeploy-command'
							listitem
								link Deploy Prebuilt Image, url='https://www.flightcontrol.dev/docs/guides/advanced/deploy-prebuilt-image'
							listitem
								link Deploying into VPCs, url='https://www.flightcontrol.dev/docs/guides/advanced/deploying-vpc'
							listitem
								link Changing the Web Service Port, url='https://www.flightcontrol.dev/docs/guides/advanced/port-change'
							listitem
								link Git Submodules, url='https://www.flightcontrol.dev/docs/guides/advanced/git-submodules'
							listitem
								link Maintenance Mode, url='https://www.flightcontrol.dev/docs/guides/advanced/maintenance-mode'
							listitem
								link Rollback, url='https://www.flightcontrol.dev/docs/guides/advanced/rollback'
							listitem
								link Service Dependency, url='https://www.flightcontrol.dev/docs/guides/advanced/service-dependency'
							listitem
								link Sidecar Containers, url='https://www.flightcontrol.dev/docs/guides/advanced/sidecar-containers'
							listitem
								link Next.js Caching, url='https://www.flightcontrol.dev/docs/guides/advanced/isr'
							listitem
								link GitHub Actions, url='https://www.flightcontrol.dev/docs/guides/advanced/github-actions'
							listitem
								link Container Insights, url='https://www.flightcontrol.dev/docs/guides/advanced/enabling-container-insights'
							listitem
								link SSH, url='https://www.flightcontrol.dev/docs/guides/advanced/ssh'
							listitem
								link Multi-region, url='https://www.flightcontrol.dev/docs/guides/advanced/multi-region'
							listitem
								link Securely add environment variables to Dockerfile, url='https://www.flightcontrol.dev/docs/guides/advanced/add-env-vars-docker-securely'
					listitem
						button Migrations
							image
						list
							listitem
								link From Heroku, url='https://www.flightcontrol.dev/docs/guides/migrations/heroku-to-aws'
							listitem
								link Heroku Postgres to RDS, url='https://www.flightcontrol.dev/docs/guides/migrations/heroku-postgres-to-rds'
			listitem
				button Reference
					image
				list
					listitem
						link Flightcontrol API, url='https://www.flightcontrol.dev/docs/reference/http-api'
							image
						list
							listitem
								button Authorization
									image
								list
									listitem
										link API Keys, url='https://www.flightcontrol.dev/docs/reference/http-api/authorization/api-keys'
							listitem
								button Projects
									image
								list
									listitem
										link List Projects, url='https://www.flightcontrol.dev/docs/reference/http-api/projects/list-projects'
									listitem
										link Edit Preview Environment, url='https://www.flightcontrol.dev/docs/reference/http-api/projects/edit-preview-environment'
							listitem
								button Environments
									image
								list
									listitem
										link Create Environment, url='https://www.flightcontrol.dev/docs/reference/http-api/environments/create-environment'
									listitem
										link Edit Environment, url='https://www.flightcontrol.dev/docs/reference/http-api/environments/edit-environment'
							listitem
								button Services
									image
								list
									listitem
										link Get Service, url='https://www.flightcontrol.dev/docs/reference/http-api/services/get-service'
							listitem
								button Deployments
									image
								list
									listitem
										link Deploy Hooks, url='https://www.flightcontrol.dev/docs/reference/http-api/deployments/deploy-hooks'
									listitem
										link Get Deployment, url='https://www.flightcontrol.dev/docs/reference/http-api/deployments/get-deployment'
							listitem
								button CloudFront
									image
								list
									listitem
										link CloudFront Cache Invalidation, url='https://www.flightcontrol.dev/docs/reference/http-api/cloudfront/cache-invalidation-api'
									listitem
										link CloudFront Cache Invalidation Status, url='https://www.flightcontrol.dev/docs/reference/http-api/cloudfront/cache-invalidation-status-api'
							listitem
								button Scheduler Service
									image
								list
									listitem
										link Create Job Execution, url='https://www.flightcontrol.dev/docs/reference/http-api/scheduler/create-job-execution'
					listitem
						link Deployment Examples, url='https://www.flightcontrol.dev/docs/reference/examples'
							image
						list
							listitem
								link Blitz.js, url='https://www.flightcontrol.dev/docs/reference/examples/blitz'
							listitem
								link Bullet Train, url='https://www.flightcontrol.dev/docs/reference/examples/bullet-train'
							listitem
								link Docker, url='https://www.flightcontrol.dev/docs/reference/examples/docker'
							listitem
								link Gatsby, url='https://www.flightcontrol.dev/docs/reference/examples/gatsby'
							listitem
								link Hasura, url='https://www.flightcontrol.dev/docs/reference/examples/hasura'
							listitem
								link Next.js, url='https://www.flightcontrol.dev/docs/reference/examples/nextjs'
							listitem
								link Node.js, url='https://www.flightcontrol.dev/docs/reference/examples/node'
							listitem
								link Prisma Studio, url='https://www.flightcontrol.dev/docs/reference/examples/prisma-studio'
							listitem
								link Redwood, url='https://www.flightcontrol.dev/docs/reference/examples/redwood'
							listitem
								link Remix, url='https://www.flightcontrol.dev/docs/reference/examples/remix'
							listitem
								link Shopify App, url='https://www.flightcontrol.dev/docs/reference/examples/shopify'
							listitem
								link Strapi, url='https://www.flightcontrol.dev/docs/reference/examples/strapi'
							listitem
								link Docusaurus, url='https://www.flightcontrol.dev/docs/reference/examples/docusaurus'
							listitem
								link Solid, url='https://www.flightcontrol.dev/docs/reference/examples/solid'
							listitem
								link Vite, url='https://www.flightcontrol.dev/docs/reference/examples/vite'
			listitem
				link Troubleshooting and Errors, url='https://www.flightcontrol.dev/docs/troubleshooting'
					image
				list
					listitem
						link Contacting Support, url='https://www.flightcontrol.dev/docs/troubleshooting/contacting-support'
					listitem
						separator, orientation='horizontal'
					listitem
						link Changing Nixpacks Version, url='https://www.flightcontrol.dev/docs/troubleshooting/changing-nixpacks-version'
					listitem
						link CodeBuild Concurrency, url='https://www.flightcontrol.dev/docs/troubleshooting/codebuild-concurrency'
					listitem
						link Concurrency Limit for New Accounts, url='https://www.flightcontrol.dev/docs/troubleshooting/concurrency-limit'
					listitem
						link ECS Concurrent vCPU Limit, url='https://www.flightcontrol.dev/docs/troubleshooting/concurrent-cpu-limit'
					listitem
						link Configure CodeBuild, url='https://www.flightcontrol.dev/docs/troubleshooting/configure-codebuild'
					listitem
						link Docker Hub: Rate Limits, url='https://www.flightcontrol.dev/docs/troubleshooting/docker-hub-rate-limits'
					listitem
						link Fargate Task Storage, url='https://www.flightcontrol.dev/docs/troubleshooting/fargate-task-storage'
					listitem
						link Increase Node Memory, url='https://www.flightcontrol.dev/docs/troubleshooting/increase-node-memory'
					listitem
						link Long Deploys, url='https://www.flightcontrol.dev/docs/troubleshooting/long-deploys'
					listitem
						link Too Many VPCs, url='https://www.flightcontrol.dev/docs/troubleshooting/too-many-vpcs'
			listitem
				link Tips, url='https://www.flightcontrol.dev/docs/tips'
					image
				list
					listitem
						link Cloud Tips, url='https://www.flightcontrol.dev/docs/tips/cloud'
							image
						list
							listitem
								link Log Groups, url='https://www.flightcontrol.dev/docs/tips/cloud/log-groups'
							listitem
								link Object Storage, url='https://www.flightcontrol.dev/docs/tips/cloud/object-storage'
					listitem
						link Nixpacks Tips, url='https://www.flightcontrol.dev/docs/tips/nixpacks'
							image
						list
							listitem
								link Speeding Up the Build, url='https://www.flightcontrol.dev/docs/tips/nixpacks/speeding-up-nixpacks-builds'
					listitem
						link Deployment Tips, url='https://www.flightcontrol.dev/docs/tips/deployment'
							image
						list
							listitem
								link Puppeteer, url='https://www.flightcontrol.dev/docs/tips/deployment/puppeteer'
			listitem
				link Flightcontrol Security & Compliance, url='https://www.flightcontrol.dev/docs/security'
		[535] button System, center=(350,1050), expanded=False, hasPopup='listbox', title=Change theme, type=button
			image
		[539] button Hide sidebar, center=(466,1050), title=Hide sidebar, type=button
			image
	navigation table of contents
	article
		main
			heading Flightcontrol Docs
			paragraph
				StaticText The AWS experience you didn’t think was possible
			heading Get Started Permalink for this section
				[550] link Permalink for this section, center=(721,260), url='https://www.flightcontrol.dev/docs#get-started'
			heading Create a Flightcontrol Account
				StaticText 1
				paragraph
			heading Connect your AWS with 1 click
				StaticText 2
				paragraph
			heading Connect your GitHub with 1 click
				StaticText 3
				paragraph
			heading Create a service with guided setup
				StaticText 4
				paragraph
			[560] link Start your First Project, center=(662,498), url='https://www.flightcontrol.dev/docs/getting-started/first-project'
				paragraph
				image
			heading Quickstart Guides and Examples Permalink for this section
				[569] link Permalink for this section, center=(1010,604), url='https://www.flightcontrol.dev/docs#quickstart-guides-and-examples'
			[571] link JavaScript Next.js, Blitz.js, Node, and more., center=(748,701), inner_text=JavaScript

Next.js, Blitz.js, Node, and more., url='https://www.flightcontrol.dev/docs/getting-started/javascript'
				paragraph
					image, url='https://www.flightcontrol.dev/docs/img/technologies/javascript.svg'
				paragraph
					StaticText Next.js, Blitz.js, Node, and more.
			[582] link PHP Laravel and Composer Examples, center=(1172,701), inner_text=PHP

Laravel and Composer Examples, url='https://www.flightcontrol.dev/docs/getting-started/php'
				paragraph
					image, url='https://www.flightcontrol.dev/docs/img/technologies/php.svg'
				paragraph
					StaticText Laravel and Composer Examples
			[593] link Ruby Rails, Sidekiq, and Bullet Train Examples, center=(748,825), inner_text=Ruby

Rails, Sidekiq, and Bullet Train Examples, url='https://www.flightcontrol.dev/docs/getting-started/ruby'
				paragraph
					image, url='https://www.flightcontrol.dev/docs/img/technologies/ruby.svg'
				paragraph
					StaticText Rails, Sidekiq, and Bullet Train Examples
			[604] link Python Flask and more, center=(1172,825), inner_text=Python

Flask and more, url='https://www.flightcontrol.dev/docs/getting-started/python'
				paragraph
					image, url='https://www.flightcontrol.dev/docs/img/technologies/python.svg'
				paragraph
					StaticText Flask and more
			[615] link Docker Use your own Dockerfile, or deploy a pre-built image., center=(748,960), inner_text=Docker

Use your own Dockerfile, or deploy a pre-built image., url='https://www.flightcontrol.dev/docs/getting-started/docker'
				paragraph
					image, url='https://www.flightcontrol.dev/docs/img/technologies/docker.svg'
				paragraph
					StaticText Use your own Dockerfile, or deploy a pre-built image.
			[626] link More Flightcontrol supports any language or framework with Nixpacks or Docker, center=(1172,960), inner_text=More

Flightcontrol supports any language or framework with Nixpacks or Docker, url='https://www.flightcontrol.dev/docs/getting-started/everything-else'
				paragraph
				paragraph
					StaticText Flightcontrol supports any language or framework with Nixpacks or Docker
			heading Learn more about Flightcontrol Permalink for this section
				link Permalink for this section, url='https://www.flightcontrol.dev/docs#learn-more-about-flightcontrol'
			link AWS Service Types, url='https://www.flightcontrol.dev/docs/concepts/services'
				paragraph
			link Custom Domains, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/custom-domains'
				paragraph
			link Preview Environments, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/preview-environment'
				paragraph
			link Autoscaling, url='https://www.flightcontrol.dev/docs/concepts/autoscaling'
				paragraph
			heading Integrations Permalink for this section
				link Permalink for this section, url='https://www.flightcontrol.dev/docs#integrations'
			link GitHub, url='https://www.flightcontrol.dev/docs/getting-started/connecting-github'
				paragraph
			link Datadog, url='https://www.flightcontrol.dev/docs/guides/integrations/datadog/setup'
				paragraph
			link Docker Hub, url='https://www.flightcontrol.dev/docs/getting-started/docker/deploying-docker-hub'
				paragraph
			link AWS Elastic Container Registry (ECR), url='https://www.flightcontrol.dev/docs/getting-started/docker/deploying-docker-ecr'
				paragraph
			link Sentry, url='https://www.flightcontrol.dev/docs/guides/integrations/sentry/uploading-source-maps'
				paragraph
			heading Popular Resources Permalink for this section
				link Permalink for this section, url='https://www.flightcontrol.dev/docs#popular-resources'
			link How to get Free AWS Credits, url='https://www.flightcontrol.dev/docs/guides/aws/aws-credits'
				paragraph
			link Getting Started, url='https://www.flightcontrol.dev/docs/getting-started'
				image
	contentinfo
		separator, orientation='horizontal'
		StaticText Flightcontrol
	alert, atomic
```
</details>

**Reasoning for action:** I clicked on the Documentation link (id 83) because it was essential to reach the documentation section, where I can find specific guides, including those related to JavaScript resources as mentioned in the user story. This action directly supports the goal of accessing the necessary materials for exploring Flightcontrol resources effectively.

**Action:** click(83) # Click on the Documentation link to explore the available resources.

**Change Description:** After clicking the Documentation link, the browser navigated to the Flightcontrol Documentation page, which now displays an overview of available resources and guides for using Flightcontrol, replacing the previous homepage. The URL changed to 'https://www.flightcontrol.dev/docs', and the page content is focused on self-managing AWS infrastructure.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://www.flightcontrol.dev/docs

https://www.flightcontrol.dev/docs/getting-started/javascript

**Content (before/after):** 

```
RootWebArea Flightcontrol Documentation | Self-manage your AWS infrastructure - Flightcontrol, focused, url='https://www.flightcontrol.dev/docs'
	navigation
		[72] link Flightcontrol Logo, center=(344,32), url='https://www.flightcontrol.dev/'
			image Flightcontrol Logo, url='https://www.flightcontrol.dev/docs/img/fc-logo-black-wordmark.svg'
		[75] link Get Help, center=(1086,32), url='https://www.flightcontrol.dev/docs/troubleshooting/contacting-support'
```
<details><summary>Show more</summary>

```
		[76] link Status, center=(1150,32), url='https://status.flightcontrol.dev/'
		[77] link Roadmap, center=(1216,32), url='https://roadmap.flightcontrol.dev/roadmap'
		[78] link Changelog, center=(1297,32), url='https://roadmap.flightcontrol.dev/changelog'
		[79] button Search, center=(1452,32), inner_text=Search
K, type=button
			image
			StaticText K
		[87] link Sign Up, center=(1580,32), url='https://app.flightcontrol.dev/signup'
		[89] link Discord Discord, center=(1644,32), inner_text=Discord, url='https://discord.gg/yY8rSPrD6q'
			image Discord
	complementary
		list
			listitem
				[112] link Flightcontrol Docs, center=(363,96), url='https://www.flightcontrol.dev/docs'
			listitem
				[114] link Getting Started, center=(363,134), url='https://www.flightcontrol.dev/docs/getting-started'
					image
				list
					listitem
						[120] link First Project, center=(375,170), url='https://www.flightcontrol.dev/docs/getting-started/first-project'
					listitem
						[122] link Connecting GitHub, center=(375,208), url='https://www.flightcontrol.dev/docs/getting-started/connecting-github'
					[123] listitem, center=(375,244)
						separator, orientation='horizontal'
					listitem
						[126] link JavaScript, center=(375,282), url='https://www.flightcontrol.dev/docs/getting-started/javascript'
							image
						list
							listitem
								link Node Version, url='https://www.flightcontrol.dev/docs/getting-started/javascript/setting-node-version'
							listitem
								link Instance Size, url='https://www.flightcontrol.dev/docs/getting-started/javascript/node-fargate-instance-size'
					listitem
						[136] link Docker, center=(375,318), url='https://www.flightcontrol.dev/docs/getting-started/docker'
							image
						list
							listitem
								link Custom Dockerfile, url='https://www.flightcontrol.dev/docs/getting-started/docker/building-deploying-dockerfile'
							listitem
								link Docker Hub Images, url='https://www.flightcontrol.dev/docs/getting-started/docker/deploying-docker-hub'
							listitem
								link Amazon ECR Images, url='https://www.flightcontrol.dev/docs/getting-started/docker/deploying-docker-ecr'
							listitem
								link GitHub Container Registry, url='https://www.flightcontrol.dev/docs/getting-started/docker/github-container-registry'
							listitem
								link Automating Docker Deployments, url='https://www.flightcontrol.dev/docs/getting-started/docker/automating-docker-deployments'
					listitem
						[152] link Java, center=(375,356), url='https://www.flightcontrol.dev/docs/getting-started/java'
							image
						list
							listitem
								link Spring Boot, url='https://www.flightcontrol.dev/docs/getting-started/java/deploying-spring-boot'
					listitem
						[160] link PHP, center=(375,392), url='https://www.flightcontrol.dev/docs/getting-started/php'
							image
						list
							listitem
								link Laravel, url='https://www.flightcontrol.dev/docs/getting-started/php/deploying-laravel'
							listitem
								link PHP/Composer, url='https://www.flightcontrol.dev/docs/getting-started/php/deploying-php-composer'
					listitem
						[170] link Python, center=(375,430), url='https://www.flightcontrol.dev/docs/getting-started/python'
							image
						list
							listitem
								link Flask Deployment, url='https://www.flightcontrol.dev/docs/getting-started/python/getting-started-flask'
							listitem
								link Create a Flask App, url='https://www.flightcontrol.dev/docs/getting-started/python/creating-flask-app'
							listitem
								link Venv with Custom Commands, url='https://www.flightcontrol.dev/docs/getting-started/python/venv-custom-commands'
					listitem
						[182] link Ruby, center=(375,466), url='https://www.flightcontrol.dev/docs/getting-started/ruby'
							image
						list
							listitem
								link Rails Deployment, url='https://www.flightcontrol.dev/docs/getting-started/ruby/getting-started-rails'
							listitem
								link Using Sidekiq, url='https://www.flightcontrol.dev/docs/getting-started/ruby/using-sidekiq'
							listitem
								link Create a Rails App, url='https://www.flightcontrol.dev/docs/getting-started/ruby/creating-rails-app'
					[193] listitem, center=(375,504)
						separator, orientation='horizontal'
					listitem
						[196] link Everything Else, center=(375,540), url='https://www.flightcontrol.dev/docs/getting-started/everything-else'
			listitem
				[198] button Concepts, center=(363,578), type=button
					image
				list
					listitem
						[204] link Service Types, center=(375,614), url='https://www.flightcontrol.dev/docs/concepts/services'
					listitem
						[206] link Build Runners, center=(375,652), url='https://www.flightcontrol.dev/docs/concepts/build-runners'
					listitem
						[208] link Build Types, center=(375,688), url='https://www.flightcontrol.dev/docs/concepts/build-types'
					listitem
						[210] link Nixpacks, center=(375,726), url='https://www.flightcontrol.dev/docs/concepts/nixpacks'
					listitem
						[212] link Autoscaling, center=(375,762), url='https://www.flightcontrol.dev/docs/concepts/autoscaling'
			listitem
				[214] button Guides, center=(363,800), type=button
					image
				list
					listitem
						[220] button Flightcontrol, center=(375,836), type=button
							image
						list
							listitem
								[226] link Project Configuration, center=(387,874), url='https://www.flightcontrol.dev/docs/guides/flightcontrol/config'
							listitem
								[228] link Config with Code, center=(387,910), url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code'
									image
								list
									listitem
										[234] link Web, center=(399,948), url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/web'
									listitem
										[236] link Private Web, center=(399,984), url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/private-web'
									listitem
										link Worker, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/worker'
									listitem
										link Scheduler, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/scheduler'
									listitem
										link Lambda Function, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/lambda-function'
									listitem
										link Static Sites, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/static'
									listitem
										link RDS Database, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/rds'
									listitem
										link Redis, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/redis'
									listitem
										link Environment Variables, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/environment-variables'
							listitem
								link Config with Dashboard, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-ui'
							listitem
								link Environment Variables, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/environment-variables'
							listitem
								link Custom Domains, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/custom-domains'
							listitem
								link Logging, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/logging'
							listitem
								link Monorepo Setup, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/monorepos'
							listitem
								link Notifications, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/notifications'
							listitem
								link Preview Environments, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/preview-environment'
							listitem
								link SSO, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/sso'
					listitem
						button Amazon Web Services
							image
						list
							listitem
								link Getting Free AWS Credits, url='https://www.flightcontrol.dev/docs/guides/aws/aws-credits'
							listitem
								link Multiple AWS Accounts, url='https://www.flightcontrol.dev/docs/guides/aws/multiple-aws-accounts'
							listitem
								link Slack notification for ECS task status change, url='https://www.flightcontrol.dev/docs/guides/aws/ecs-task-status-notification'
					listitem
						button Integrations
							image
						list
							listitem
								button Datadog
									image
								list
									listitem
										link Set Up Core Datadog AWS Integration, url='https://www.flightcontrol.dev/docs/guides/integrations/datadog/setup'
									listitem
										link Metrics sidecar, url='https://www.flightcontrol.dev/docs/guides/integrations/datadog/metrics'
							listitem
								button Sentry
									image
								list
									listitem
										link Source Maps, url='https://www.flightcontrol.dev/docs/guides/integrations/sentry/uploading-source-maps'
							listitem
								link Logging with Firelens, url='https://www.flightcontrol.dev/docs/guides/integrations/logging'
					listitem
						button Advanced
							image
						list
							listitem
								link Watch Paths, url='https://www.flightcontrol.dev/docs/guides/advanced/watch-paths'
							listitem
								link Database Migrations, url='https://www.flightcontrol.dev/docs/guides/advanced/database-migrations'
							listitem
								link Pre-deploy Command, url='https://www.flightcontrol.dev/docs/guides/advanced/predeploy-command'
							listitem
								link Post-deploy Command, url='https://www.flightcontrol.dev/docs/guides/advanced/postdeploy-command'
							listitem
								link Deploy Prebuilt Image, url='https://www.flightcontrol.dev/docs/guides/advanced/deploy-prebuilt-image'
							listitem
								link Deploying into VPCs, url='https://www.flightcontrol.dev/docs/guides/advanced/deploying-vpc'
							listitem
								link Changing the Web Service Port, url='https://www.flightcontrol.dev/docs/guides/advanced/port-change'
							listitem
								link Git Submodules, url='https://www.flightcontrol.dev/docs/guides/advanced/git-submodules'
							listitem
								link Maintenance Mode, url='https://www.flightcontrol.dev/docs/guides/advanced/maintenance-mode'
							listitem
								link Rollback, url='https://www.flightcontrol.dev/docs/guides/advanced/rollback'
							listitem
								link Service Dependency, url='https://www.flightcontrol.dev/docs/guides/advanced/service-dependency'
							listitem
								link Sidecar Containers, url='https://www.flightcontrol.dev/docs/guides/advanced/sidecar-containers'
							listitem
								link Next.js Caching, url='https://www.flightcontrol.dev/docs/guides/advanced/isr'
							listitem
								link GitHub Actions, url='https://www.flightcontrol.dev/docs/guides/advanced/github-actions'
							listitem
								link Container Insights, url='https://www.flightcontrol.dev/docs/guides/advanced/enabling-container-insights'
							listitem
								link SSH, url='https://www.flightcontrol.dev/docs/guides/advanced/ssh'
							listitem
								link Multi-region, url='https://www.flightcontrol.dev/docs/guides/advanced/multi-region'
							listitem
								link Securely add environment variables to Dockerfile, url='https://www.flightcontrol.dev/docs/guides/advanced/add-env-vars-docker-securely'
					listitem
						button Migrations
							image
						list
							listitem
								link From Heroku, url='https://www.flightcontrol.dev/docs/guides/migrations/heroku-to-aws'
							listitem
								link Heroku Postgres to RDS, url='https://www.flightcontrol.dev/docs/guides/migrations/heroku-postgres-to-rds'
			listitem
				button Reference
					image
				list
					listitem
						link Flightcontrol API, url='https://www.flightcontrol.dev/docs/reference/http-api'
							image
						list
							listitem
								button Authorization
									image
								list
									listitem
										link API Keys, url='https://www.flightcontrol.dev/docs/reference/http-api/authorization/api-keys'
							listitem
								button Projects
									image
								list
									listitem
										link List Projects, url='https://www.flightcontrol.dev/docs/reference/http-api/projects/list-projects'
									listitem
										link Edit Preview Environment, url='https://www.flightcontrol.dev/docs/reference/http-api/projects/edit-preview-environment'
							listitem
								button Environments
									image
								list
									listitem
										link Create Environment, url='https://www.flightcontrol.dev/docs/reference/http-api/environments/create-environment'
									listitem
										link Edit Environment, url='https://www.flightcontrol.dev/docs/reference/http-api/environments/edit-environment'
							listitem
								button Services
									image
								list
									listitem
										link Get Service, url='https://www.flightcontrol.dev/docs/reference/http-api/services/get-service'
							listitem
								button Deployments
									image
								list
									listitem
										link Deploy Hooks, url='https://www.flightcontrol.dev/docs/reference/http-api/deployments/deploy-hooks'
									listitem
										link Get Deployment, url='https://www.flightcontrol.dev/docs/reference/http-api/deployments/get-deployment'
							listitem
								button CloudFront
									image
								list
									listitem
										link CloudFront Cache Invalidation, url='https://www.flightcontrol.dev/docs/reference/http-api/cloudfront/cache-invalidation-api'
									listitem
										link CloudFront Cache Invalidation Status, url='https://www.flightcontrol.dev/docs/reference/http-api/cloudfront/cache-invalidation-status-api'
							listitem
								button Scheduler Service
									image
								list
									listitem
										link Create Job Execution, url='https://www.flightcontrol.dev/docs/reference/http-api/scheduler/create-job-execution'
					listitem
						link Deployment Examples, url='https://www.flightcontrol.dev/docs/reference/examples'
							image
						list
							listitem
								link Blitz.js, url='https://www.flightcontrol.dev/docs/reference/examples/blitz'
							listitem
								link Bullet Train, url='https://www.flightcontrol.dev/docs/reference/examples/bullet-train'
							listitem
								link Docker, url='https://www.flightcontrol.dev/docs/reference/examples/docker'
							listitem
								link Gatsby, url='https://www.flightcontrol.dev/docs/reference/examples/gatsby'
							listitem
								link Hasura, url='https://www.flightcontrol.dev/docs/reference/examples/hasura'
							listitem
								link Next.js, url='https://www.flightcontrol.dev/docs/reference/examples/nextjs'
							listitem
								link Node.js, url='https://www.flightcontrol.dev/docs/reference/examples/node'
							listitem
								link Prisma Studio, url='https://www.flightcontrol.dev/docs/reference/examples/prisma-studio'
							listitem
								link Redwood, url='https://www.flightcontrol.dev/docs/reference/examples/redwood'
							listitem
								link Remix, url='https://www.flightcontrol.dev/docs/reference/examples/remix'
							listitem
								link Shopify App, url='https://www.flightcontrol.dev/docs/reference/examples/shopify'
							listitem
								link Strapi, url='https://www.flightcontrol.dev/docs/reference/examples/strapi'
							listitem
								link Docusaurus, url='https://www.flightcontrol.dev/docs/reference/examples/docusaurus'
							listitem
								link Solid, url='https://www.flightcontrol.dev/docs/reference/examples/solid'
							listitem
								link Vite, url='https://www.flightcontrol.dev/docs/reference/examples/vite'
			listitem
				link Troubleshooting and Errors, url='https://www.flightcontrol.dev/docs/troubleshooting'
					image
				list
					listitem
						link Contacting Support, url='https://www.flightcontrol.dev/docs/troubleshooting/contacting-support'
					listitem
						separator, orientation='horizontal'
					listitem
						link Changing Nixpacks Version, url='https://www.flightcontrol.dev/docs/troubleshooting/changing-nixpacks-version'
					listitem
						link CodeBuild Concurrency, url='https://www.flightcontrol.dev/docs/troubleshooting/codebuild-concurrency'
					listitem
						link Concurrency Limit for New Accounts, url='https://www.flightcontrol.dev/docs/troubleshooting/concurrency-limit'
					listitem
						link ECS Concurrent vCPU Limit, url='https://www.flightcontrol.dev/docs/troubleshooting/concurrent-cpu-limit'
					listitem
						link Configure CodeBuild, url='https://www.flightcontrol.dev/docs/troubleshooting/configure-codebuild'
					listitem
						link Docker Hub: Rate Limits, url='https://www.flightcontrol.dev/docs/troubleshooting/docker-hub-rate-limits'
					listitem
						link Fargate Task Storage, url='https://www.flightcontrol.dev/docs/troubleshooting/fargate-task-storage'
					listitem
						link Increase Node Memory, url='https://www.flightcontrol.dev/docs/troubleshooting/increase-node-memory'
					listitem
						link Long Deploys, url='https://www.flightcontrol.dev/docs/troubleshooting/long-deploys'
					listitem
						link Too Many VPCs, url='https://www.flightcontrol.dev/docs/troubleshooting/too-many-vpcs'
			listitem
				link Tips, url='https://www.flightcontrol.dev/docs/tips'
					image
				list
					listitem
						link Cloud Tips, url='https://www.flightcontrol.dev/docs/tips/cloud'
							image
						list
							listitem
								link Log Groups, url='https://www.flightcontrol.dev/docs/tips/cloud/log-groups'
							listitem
								link Object Storage, url='https://www.flightcontrol.dev/docs/tips/cloud/object-storage'
					listitem
						link Nixpacks Tips, url='https://www.flightcontrol.dev/docs/tips/nixpacks'
							image
						list
							listitem
								link Speeding Up the Build, url='https://www.flightcontrol.dev/docs/tips/nixpacks/speeding-up-nixpacks-builds'
					listitem
						link Deployment Tips, url='https://www.flightcontrol.dev/docs/tips/deployment'
							image
						list
							listitem
								link Puppeteer, url='https://www.flightcontrol.dev/docs/tips/deployment/puppeteer'
			listitem
				link Flightcontrol Security & Compliance, url='https://www.flightcontrol.dev/docs/security'
		[535] button System, center=(350,1050), expanded=False, hasPopup='listbox', title=Change theme, type=button
			image
		[539] button Hide sidebar, center=(466,1050), title=Hide sidebar, type=button
			image
	navigation table of contents
	article
		main
			heading Flightcontrol Docs
			paragraph
				StaticText The AWS experience you didn’t think was possible
			heading Get Started Permalink for this section
				[550] link Permalink for this section, center=(721,260), url='https://www.flightcontrol.dev/docs#get-started'
			heading Create a Flightcontrol Account
				StaticText 1
				paragraph
			heading Connect your AWS with 1 click
				StaticText 2
				paragraph
			heading Connect your GitHub with 1 click
				StaticText 3
				paragraph
			heading Create a service with guided setup
				StaticText 4
				paragraph
			[560] link Start your First Project, center=(662,498), url='https://www.flightcontrol.dev/docs/getting-started/first-project'
				paragraph
				image
			heading Quickstart Guides and Examples Permalink for this section
				[569] link Permalink for this section, center=(1010,604), url='https://www.flightcontrol.dev/docs#quickstart-guides-and-examples'
			[571] link JavaScript Next.js, Blitz.js, Node, and more., center=(748,701), inner_text=JavaScript

Next.js, Blitz.js, Node, and more., url='https://www.flightcontrol.dev/docs/getting-started/javascript'
				paragraph
					image, url='https://www.flightcontrol.dev/docs/img/technologies/javascript.svg'
				paragraph
					StaticText Next.js, Blitz.js, Node, and more.
			[582] link PHP Laravel and Composer Examples, center=(1172,701), inner_text=PHP

Laravel and Composer Examples, url='https://www.flightcontrol.dev/docs/getting-started/php'
				paragraph
					image, url='https://www.flightcontrol.dev/docs/img/technologies/php.svg'
				paragraph
					StaticText Laravel and Composer Examples
			[593] link Ruby Rails, Sidekiq, and Bullet Train Examples, center=(748,825), inner_text=Ruby

Rails, Sidekiq, and Bullet Train Examples, url='https://www.flightcontrol.dev/docs/getting-started/ruby'
				paragraph
					image, url='https://www.flightcontrol.dev/docs/img/technologies/ruby.svg'
				paragraph
					StaticText Rails, Sidekiq, and Bullet Train Examples
			[604] link Python Flask and more, center=(1172,825), inner_text=Python

Flask and more, url='https://www.flightcontrol.dev/docs/getting-started/python'
				paragraph
					image, url='https://www.flightcontrol.dev/docs/img/technologies/python.svg'
				paragraph
					StaticText Flask and more
			[615] link Docker Use your own Dockerfile, or deploy a pre-built image., center=(748,960), inner_text=Docker

Use your own Dockerfile, or deploy a pre-built image., url='https://www.flightcontrol.dev/docs/getting-started/docker'
				paragraph
					image, url='https://www.flightcontrol.dev/docs/img/technologies/docker.svg'
				paragraph
					StaticText Use your own Dockerfile, or deploy a pre-built image.
			[626] link More Flightcontrol supports any language or framework with Nixpacks or Docker, center=(1172,960), inner_text=More

Flightcontrol supports any language or framework with Nixpacks or Docker, url='https://www.flightcontrol.dev/docs/getting-started/everything-else'
				paragraph
				paragraph
					StaticText Flightcontrol supports any language or framework with Nixpacks or Docker
			heading Learn more about Flightcontrol Permalink for this section
				link Permalink for this section, url='https://www.flightcontrol.dev/docs#learn-more-about-flightcontrol'
			link AWS Service Types, url='https://www.flightcontrol.dev/docs/concepts/services'
				paragraph
			link Custom Domains, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/custom-domains'
				paragraph
			link Preview Environments, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/preview-environment'
				paragraph
			link Autoscaling, url='https://www.flightcontrol.dev/docs/concepts/autoscaling'
				paragraph
			heading Integrations Permalink for this section
				link Permalink for this section, url='https://www.flightcontrol.dev/docs#integrations'
			link GitHub, url='https://www.flightcontrol.dev/docs/getting-started/connecting-github'
				paragraph
			link Datadog, url='https://www.flightcontrol.dev/docs/guides/integrations/datadog/setup'
				paragraph
			link Docker Hub, url='https://www.flightcontrol.dev/docs/getting-started/docker/deploying-docker-hub'
				paragraph
			link AWS Elastic Container Registry (ECR), url='https://www.flightcontrol.dev/docs/getting-started/docker/deploying-docker-ecr'
				paragraph
			link Sentry, url='https://www.flightcontrol.dev/docs/guides/integrations/sentry/uploading-source-maps'
				paragraph
			heading Popular Resources Permalink for this section
				link Permalink for this section, url='https://www.flightcontrol.dev/docs#popular-resources'
			link How to get Free AWS Credits, url='https://www.flightcontrol.dev/docs/guides/aws/aws-credits'
				paragraph
			link Getting Started, url='https://www.flightcontrol.dev/docs/getting-started'
				image
	contentinfo
		separator, orientation='horizontal'
		StaticText Flightcontrol
	alert, atomic
```
</details>



```
RootWebArea JavaScript Resource Center - Flightcontrol, focused, url='https://www.flightcontrol.dev/docs/getting-started/javascript'
	navigation
		[72] link Flightcontrol Logo, center=(344,32), url='https://www.flightcontrol.dev/'
			image Flightcontrol Logo, url='https://www.flightcontrol.dev/docs/img/fc-logo-black-wordmark.svg'
		[75] link Get Help, center=(1086,32), url='https://www.flightcontrol.dev/docs/troubleshooting/contacting-support'
```
<details><summary>Show more</summary>

```
		[76] link Status, center=(1150,32), url='https://status.flightcontrol.dev/'
		[77] link Roadmap, center=(1216,32), url='https://roadmap.flightcontrol.dev/roadmap'
		[78] link Changelog, center=(1297,32), url='https://roadmap.flightcontrol.dev/changelog'
		[79] button Search, center=(1452,32), inner_text=Search
K, type=button
			image
			StaticText K
		[87] link Sign Up, center=(1580,32), url='https://app.flightcontrol.dev/signup'
		[89] link Discord Discord, center=(1644,32), inner_text=Discord, url='https://discord.gg/yY8rSPrD6q'
			image Discord
	complementary
		list
			listitem
				[112] link Flightcontrol Docs, center=(363,96), url='https://www.flightcontrol.dev/docs'
			listitem
				[114] link Getting Started, center=(363,134), url='https://www.flightcontrol.dev/docs/getting-started'
					image
				list
					listitem
						[120] link First Project, center=(375,170), url='https://www.flightcontrol.dev/docs/getting-started/first-project'
					listitem
						[122] link Connecting GitHub, center=(375,208), url='https://www.flightcontrol.dev/docs/getting-started/connecting-github'
					[123] listitem, center=(375,244)
						separator, orientation='horizontal'
					listitem
						[126] link JavaScript, center=(375,282), url='https://www.flightcontrol.dev/docs/getting-started/javascript'
							image
						list
							listitem
								[132] link Node Version, center=(387,318), url='https://www.flightcontrol.dev/docs/getting-started/javascript/setting-node-version'
							listitem
								[134] link Instance Size, center=(387,356), url='https://www.flightcontrol.dev/docs/getting-started/javascript/node-fargate-instance-size'
					listitem
						[136] link Docker, center=(375,392), url='https://www.flightcontrol.dev/docs/getting-started/docker'
							image
						list
							listitem
								link Custom Dockerfile, url='https://www.flightcontrol.dev/docs/getting-started/docker/building-deploying-dockerfile'
							listitem
								link Docker Hub Images, url='https://www.flightcontrol.dev/docs/getting-started/docker/deploying-docker-hub'
							listitem
								link Amazon ECR Images, url='https://www.flightcontrol.dev/docs/getting-started/docker/deploying-docker-ecr'
							listitem
								link GitHub Container Registry, url='https://www.flightcontrol.dev/docs/getting-started/docker/github-container-registry'
							listitem
								link Automating Docker Deployments, url='https://www.flightcontrol.dev/docs/getting-started/docker/automating-docker-deployments'
					listitem
						[152] link Java, center=(375,430), url='https://www.flightcontrol.dev/docs/getting-started/java'
							image
						list
							listitem
								link Spring Boot, url='https://www.flightcontrol.dev/docs/getting-started/java/deploying-spring-boot'
					listitem
						[160] link PHP, center=(375,466), url='https://www.flightcontrol.dev/docs/getting-started/php'
							image
						list
							listitem
								link Laravel, url='https://www.flightcontrol.dev/docs/getting-started/php/deploying-laravel'
							listitem
								link PHP/Composer, url='https://www.flightcontrol.dev/docs/getting-started/php/deploying-php-composer'
					listitem
						[170] link Python, center=(375,504), url='https://www.flightcontrol.dev/docs/getting-started/python'
							image
						list
							listitem
								link Flask Deployment, url='https://www.flightcontrol.dev/docs/getting-started/python/getting-started-flask'
							listitem
								link Create a Flask App, url='https://www.flightcontrol.dev/docs/getting-started/python/creating-flask-app'
							listitem
								link Venv with Custom Commands, url='https://www.flightcontrol.dev/docs/getting-started/python/venv-custom-commands'
					listitem
						[182] link Ruby, center=(375,540), url='https://www.flightcontrol.dev/docs/getting-started/ruby'
							image
						list
							listitem
								link Rails Deployment, url='https://www.flightcontrol.dev/docs/getting-started/ruby/getting-started-rails'
							listitem
								link Using Sidekiq, url='https://www.flightcontrol.dev/docs/getting-started/ruby/using-sidekiq'
							listitem
								link Create a Rails App, url='https://www.flightcontrol.dev/docs/getting-started/ruby/creating-rails-app'
					[193] listitem, center=(375,578)
						separator, orientation='horizontal'
					listitem
						[196] link Everything Else, center=(375,614), url='https://www.flightcontrol.dev/docs/getting-started/everything-else'
			listitem
				[198] button Concepts, center=(363,652), type=button
					image
				list
					listitem
						[204] link Service Types, center=(375,688), url='https://www.flightcontrol.dev/docs/concepts/services'
					listitem
						[206] link Build Runners, center=(375,726), url='https://www.flightcontrol.dev/docs/concepts/build-runners'
					listitem
						[208] link Build Types, center=(375,762), url='https://www.flightcontrol.dev/docs/concepts/build-types'
					listitem
						[210] link Nixpacks, center=(375,800), url='https://www.flightcontrol.dev/docs/concepts/nixpacks'
					listitem
						[212] link Autoscaling, center=(375,836), url='https://www.flightcontrol.dev/docs/concepts/autoscaling'
			listitem
				[214] button Guides, center=(363,874), type=button
					image
				list
					listitem
						[220] button Flightcontrol, center=(375,910), type=button
							image
						list
							listitem
								[226] link Project Configuration, center=(387,948), url='https://www.flightcontrol.dev/docs/guides/flightcontrol/config'
							listitem
								[228] link Config with Code, center=(387,984), url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code'
									image
								list
									listitem
										link Web, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/web'
									listitem
										link Private Web, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/private-web'
									listitem
										link Worker, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/worker'
									listitem
										link Scheduler, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/scheduler'
									listitem
										link Lambda Function, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/lambda-function'
									listitem
										link Static Sites, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/static'
									listitem
										link RDS Database, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/rds'
									listitem
										link Redis, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/redis'
									listitem
										link Environment Variables, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/environment-variables'
							listitem
								link Config with Dashboard, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-ui'
							listitem
								link Environment Variables, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/environment-variables'
							listitem
								link Custom Domains, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/custom-domains'
							listitem
								link Logging, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/logging'
							listitem
								link Monorepo Setup, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/monorepos'
							listitem
								link Notifications, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/notifications'
							listitem
								link Preview Environments, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/preview-environment'
							listitem
								link SSO, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/sso'
					listitem
						button Amazon Web Services
							image
						list
							listitem
								link Getting Free AWS Credits, url='https://www.flightcontrol.dev/docs/guides/aws/aws-credits'
							listitem
								link Multiple AWS Accounts, url='https://www.flightcontrol.dev/docs/guides/aws/multiple-aws-accounts'
							listitem
								link Slack notification for ECS task status change, url='https://www.flightcontrol.dev/docs/guides/aws/ecs-task-status-notification'
					listitem
						button Integrations
							image
						list
							listitem
								button Datadog
									image
								list
									listitem
										link Set Up Core Datadog AWS Integration, url='https://www.flightcontrol.dev/docs/guides/integrations/datadog/setup'
									listitem
										link Metrics sidecar, url='https://www.flightcontrol.dev/docs/guides/integrations/datadog/metrics'
							listitem
								button Sentry
									image
								list
									listitem
										link Source Maps, url='https://www.flightcontrol.dev/docs/guides/integrations/sentry/uploading-source-maps'
							listitem
								link Logging with Firelens, url='https://www.flightcontrol.dev/docs/guides/integrations/logging'
					listitem
						button Advanced
							image
						list
							listitem
								link Watch Paths, url='https://www.flightcontrol.dev/docs/guides/advanced/watch-paths'
							listitem
								link Database Migrations, url='https://www.flightcontrol.dev/docs/guides/advanced/database-migrations'
							listitem
								link Pre-deploy Command, url='https://www.flightcontrol.dev/docs/guides/advanced/predeploy-command'
							listitem
								link Post-deploy Command, url='https://www.flightcontrol.dev/docs/guides/advanced/postdeploy-command'
							listitem
								link Deploy Prebuilt Image, url='https://www.flightcontrol.dev/docs/guides/advanced/deploy-prebuilt-image'
							listitem
								link Deploying into VPCs, url='https://www.flightcontrol.dev/docs/guides/advanced/deploying-vpc'
							listitem
								link Changing the Web Service Port, url='https://www.flightcontrol.dev/docs/guides/advanced/port-change'
							listitem
								link Git Submodules, url='https://www.flightcontrol.dev/docs/guides/advanced/git-submodules'
							listitem
								link Maintenance Mode, url='https://www.flightcontrol.dev/docs/guides/advanced/maintenance-mode'
							listitem
								link Rollback, url='https://www.flightcontrol.dev/docs/guides/advanced/rollback'
							listitem
								link Service Dependency, url='https://www.flightcontrol.dev/docs/guides/advanced/service-dependency'
							listitem
								link Sidecar Containers, url='https://www.flightcontrol.dev/docs/guides/advanced/sidecar-containers'
							listitem
								link Next.js Caching, url='https://www.flightcontrol.dev/docs/guides/advanced/isr'
							listitem
								link GitHub Actions, url='https://www.flightcontrol.dev/docs/guides/advanced/github-actions'
							listitem
								link Container Insights, url='https://www.flightcontrol.dev/docs/guides/advanced/enabling-container-insights'
							listitem
								link SSH, url='https://www.flightcontrol.dev/docs/guides/advanced/ssh'
							listitem
								link Multi-region, url='https://www.flightcontrol.dev/docs/guides/advanced/multi-region'
							listitem
								link Securely add environment variables to Dockerfile, url='https://www.flightcontrol.dev/docs/guides/advanced/add-env-vars-docker-securely'
					listitem
						button Migrations
							image
						list
							listitem
								link From Heroku, url='https://www.flightcontrol.dev/docs/guides/migrations/heroku-to-aws'
							listitem
								link Heroku Postgres to RDS, url='https://www.flightcontrol.dev/docs/guides/migrations/heroku-postgres-to-rds'
			listitem
				button Reference
					image
				list
					listitem
						link Flightcontrol API, url='https://www.flightcontrol.dev/docs/reference/http-api'
							image
						list
							listitem
								button Authorization
									image
								list
									listitem
										link API Keys, url='https://www.flightcontrol.dev/docs/reference/http-api/authorization/api-keys'
							listitem
								button Projects
									image
								list
									listitem
										link List Projects, url='https://www.flightcontrol.dev/docs/reference/http-api/projects/list-projects'
									listitem
										link Edit Preview Environment, url='https://www.flightcontrol.dev/docs/reference/http-api/projects/edit-preview-environment'
							listitem
								button Environments
									image
								list
									listitem
										link Create Environment, url='https://www.flightcontrol.dev/docs/reference/http-api/environments/create-environment'
									listitem
										link Edit Environment, url='https://www.flightcontrol.dev/docs/reference/http-api/environments/edit-environment'
							listitem
								button Services
									image
								list
									listitem
										link Get Service, url='https://www.flightcontrol.dev/docs/reference/http-api/services/get-service'
							listitem
								button Deployments
									image
								list
									listitem
										link Deploy Hooks, url='https://www.flightcontrol.dev/docs/reference/http-api/deployments/deploy-hooks'
									listitem
										link Get Deployment, url='https://www.flightcontrol.dev/docs/reference/http-api/deployments/get-deployment'
							listitem
								button CloudFront
									image
								list
									listitem
										link CloudFront Cache Invalidation, url='https://www.flightcontrol.dev/docs/reference/http-api/cloudfront/cache-invalidation-api'
									listitem
										link CloudFront Cache Invalidation Status, url='https://www.flightcontrol.dev/docs/reference/http-api/cloudfront/cache-invalidation-status-api'
							listitem
								button Scheduler Service
									image
								list
									listitem
										link Create Job Execution, url='https://www.flightcontrol.dev/docs/reference/http-api/scheduler/create-job-execution'
					listitem
						link Deployment Examples, url='https://www.flightcontrol.dev/docs/reference/examples'
							image
						list
							listitem
								link Blitz.js, url='https://www.flightcontrol.dev/docs/reference/examples/blitz'
							listitem
								link Bullet Train, url='https://www.flightcontrol.dev/docs/reference/examples/bullet-train'
							listitem
								link Docker, url='https://www.flightcontrol.dev/docs/reference/examples/docker'
							listitem
								link Gatsby, url='https://www.flightcontrol.dev/docs/reference/examples/gatsby'
							listitem
								link Hasura, url='https://www.flightcontrol.dev/docs/reference/examples/hasura'
							listitem
								link Next.js, url='https://www.flightcontrol.dev/docs/reference/examples/nextjs'
							listitem
								link Node.js, url='https://www.flightcontrol.dev/docs/reference/examples/node'
							listitem
								link Prisma Studio, url='https://www.flightcontrol.dev/docs/reference/examples/prisma-studio'
							listitem
								link Redwood, url='https://www.flightcontrol.dev/docs/reference/examples/redwood'
							listitem
								link Remix, url='https://www.flightcontrol.dev/docs/reference/examples/remix'
							listitem
								link Shopify App, url='https://www.flightcontrol.dev/docs/reference/examples/shopify'
							listitem
								link Strapi, url='https://www.flightcontrol.dev/docs/reference/examples/strapi'
							listitem
								link Docusaurus, url='https://www.flightcontrol.dev/docs/reference/examples/docusaurus'
							listitem
								link Solid, url='https://www.flightcontrol.dev/docs/reference/examples/solid'
							listitem
								link Vite, url='https://www.flightcontrol.dev/docs/reference/examples/vite'
			listitem
				link Troubleshooting and Errors, url='https://www.flightcontrol.dev/docs/troubleshooting'
					image
				list
					listitem
						link Contacting Support, url='https://www.flightcontrol.dev/docs/troubleshooting/contacting-support'
					listitem
						separator, orientation='horizontal'
					listitem
						link Changing Nixpacks Version, url='https://www.flightcontrol.dev/docs/troubleshooting/changing-nixpacks-version'
					listitem
						link CodeBuild Concurrency, url='https://www.flightcontrol.dev/docs/troubleshooting/codebuild-concurrency'
					listitem
						link Concurrency Limit for New Accounts, url='https://www.flightcontrol.dev/docs/troubleshooting/concurrency-limit'
					listitem
						link ECS Concurrent vCPU Limit, url='https://www.flightcontrol.dev/docs/troubleshooting/concurrent-cpu-limit'
					listitem
						link Configure CodeBuild, url='https://www.flightcontrol.dev/docs/troubleshooting/configure-codebuild'
					listitem
						link Docker Hub: Rate Limits, url='https://www.flightcontrol.dev/docs/troubleshooting/docker-hub-rate-limits'
					listitem
						link Fargate Task Storage, url='https://www.flightcontrol.dev/docs/troubleshooting/fargate-task-storage'
					listitem
						link Increase Node Memory, url='https://www.flightcontrol.dev/docs/troubleshooting/increase-node-memory'
					listitem
						link Long Deploys, url='https://www.flightcontrol.dev/docs/troubleshooting/long-deploys'
					listitem
						link Too Many VPCs, url='https://www.flightcontrol.dev/docs/troubleshooting/too-many-vpcs'
			listitem
				link Tips, url='https://www.flightcontrol.dev/docs/tips'
					image
				list
					listitem
						link Cloud Tips, url='https://www.flightcontrol.dev/docs/tips/cloud'
							image
						list
							listitem
								link Log Groups, url='https://www.flightcontrol.dev/docs/tips/cloud/log-groups'
							listitem
								link Object Storage, url='https://www.flightcontrol.dev/docs/tips/cloud/object-storage'
					listitem
						link Nixpacks Tips, url='https://www.flightcontrol.dev/docs/tips/nixpacks'
							image
						list
							listitem
								link Speeding Up the Build, url='https://www.flightcontrol.dev/docs/tips/nixpacks/speeding-up-nixpacks-builds'
					listitem
						link Deployment Tips, url='https://www.flightcontrol.dev/docs/tips/deployment'
							image
						list
							listitem
								link Puppeteer, url='https://www.flightcontrol.dev/docs/tips/deployment/puppeteer'
			listitem
				link Flightcontrol Security & Compliance, url='https://www.flightcontrol.dev/docs/security'
		[535] button System, center=(350,1050), expanded=False, hasPopup='listbox', title=Change theme, type=button
			image
		[539] button Hide sidebar, center=(466,1050), title=Hide sidebar, type=button
			image
	navigation table of contents
		paragraph
			StaticText On This Page
		list
			listitem
				[802] link Working with Monorepos, center=(1547,142), url='https://www.flightcontrol.dev/docs/getting-started/javascript#working-with-monorepos'
			listitem
				[804] link Guides, center=(1547,170), url='https://www.flightcontrol.dev/docs/getting-started/javascript#guides'
			listitem
				[806] link Deployment Examples, center=(1547,200), url='https://www.flightcontrol.dev/docs/getting-started/javascript#deployment-examples'
			listitem
				[808] link JavaScript and TypeScript Support in Nixpacks, center=(1547,239), url='https://www.flightcontrol.dev/docs/getting-started/javascript#javascript-and-typescript-support-in-nixpacks'
		link, url='https://github.com/shuding/nextra/pages/getting-started/javascript.mdx'
	article
		main
			[814] link Getting Started, center=(592,96), title=Getting Started, url='https://www.flightcontrol.dev/docs/getting-started'
			[811] button, center=(1485,308), inner_text=Scroll to top, type=button
			image
			StaticText JavaScript
			heading JavaScript Resource Center
			paragraph
				StaticText Flightcontrol was built from the ground up to support modern JavaScript and TypeScript web application frameworks.
			paragraph
				StaticText Powered by Nixpacks, Flightcontrol deploys applications that you built with Blitz.js, Next.js, Remix, Astro, Express, and more.
			paragraph
				StaticText If you can run your project with
				code
					StaticText npm start
				StaticText or
				code
					StaticText yarn start
				StaticText , you can deploy it with Flightcontrol. If it’s a little more complicated, you can always change the run, build, or install commands to match your requirements.
			paragraph
				StaticText This page points you to all of our JavaScript ecosystem resources in our documentation.
			heading Working with Monorepos Permalink for this section
				[825] link Permalink for this section, center=(899,520), url='https://www.flightcontrol.dev/docs/getting-started/javascript#working-with-monorepos'
			paragraph
				StaticText If you are using a monorepo, for instance, with the
				code
					StaticText pnpm
				StaticText tool, use our
				[828] link Monorepo Support, center=(1102,586), url='https://www.flightcontrol.dev/docs/guides/flightcontrol/monorepos'
				StaticText guide to learn how to configure your project to work with Flightcontrol.
			heading Guides Permalink for this section
				[830] link Permalink for this section, center=(657,715), url='https://www.flightcontrol.dev/docs/getting-started/javascript#guides'
			table
				rowgroup
					row
						columnheader Title
				rowgroup
					row
						cell Building and Deploying a Remix project
							[838] link Building and Deploying a Remix project, center=(697,828), url='https://www.flightcontrol.dev/docs/reference/examples/remix'
					row
						cell Deploying a Bullet Train project
							[841] link Deploying a Bullet Train project, center=(670,870), url='https://www.flightcontrol.dev/docs/reference/examples/bullet-train'
					row
						cell Deploying a Strapi project
							[844] link Deploying a Strapi project, center=(653,910), url='https://www.flightcontrol.dev/docs/reference/examples/strapi'
					row
						cell Deploying a Shopify App
							[847] link Deploying a Shopify App, center=(647,952), url='https://www.flightcontrol.dev/docs/reference/examples/shopify'
			heading Deployment Examples Permalink for this section
				[849] link Permalink for this section, center=(867,1059), url='https://www.flightcontrol.dev/docs/getting-started/javascript#deployment-examples'
			table
				rowgroup
					row
						columnheader Title
						columnheader Description
				rowgroup
					row
						cell Blitz.js
							link Blitz.js, url='https://www.flightcontrol.dev/docs/reference/examples/blitz'
						cell
					row
						cell Next.js
							link Next.js, url='https://www.flightcontrol.dev/docs/reference/examples/nextjs'
						cell
					row
						cell Node
							link Node, url='https://www.flightcontrol.dev/docs/reference/examples/node'
						cell Generic example suitable for most Node.js projects
					row
						cell Prisma Studio
							link Prisma Studio, url='https://www.flightcontrol.dev/docs/reference/examples/prisma-studio'
						cell
					row
						cell Redwood
							link Redwood, url='https://www.flightcontrol.dev/docs/reference/examples/redwood'
						cell
					row
						cell Docusaurus
							link Docusaurus, url='https://www.flightcontrol.dev/docs/reference/examples/docusaurus'
						cell
			heading JavaScript and TypeScript Support in Nixpacks Permalink for this section
				link Permalink for this section, url='https://www.flightcontrol.dev/docs/getting-started/javascript#javascript-and-typescript-support-in-nixpacks'
			paragraph
				StaticText Flightcontrol uses Nixpacks, an advanced form of build packs, to deploy your JavaScript or TypeScript application.
			paragraph
				StaticText Nixpacks detects what type of application you are trying to deploy, and then uses a series of rules in the specific Nixpack provider (such as the JavaScript provider) to determine exactly how to build, install, and run that application.
			paragraph
				StaticText Nixpacks itself is open source, and available to view on GitHub. Each Nixpacks provider is written in Rust, but you can read through the source code to see exactly what it is doing with your application.
			paragraph
				StaticText To learn more, see the Nixpacks Documentation and the source code of the provider:
			list
				listitem
					ListMarker •
					link Nixpacks Node Documentation, url='https://nixpacks.com/docs/providers/node'
				listitem
					ListMarker •
					link Nixpacks JavaScript Provider, url='https://github.com/railwayapp/nixpacks/blob/main/src/providers/node'
					StaticText (Source Code on GitHub)
			link Connecting GitHub, url='https://www.flightcontrol.dev/docs/getting-started/connecting-github'
				image
			link Node Version, url='https://www.flightcontrol.dev/docs/getting-started/javascript/setting-node-version'
				image
	contentinfo
		separator, orientation='horizontal'
		StaticText Flightcontrol
	alert, atomic
		StaticText JavaScript Resource Center - Flightcontrol
```
</details>

**Reasoning for action:** I chose to click on the JavaScript link because doing so takes me to the relevant section that contains guides and examples specifically designed for JavaScript. This is crucial for achieving the user's goal of finding specific resources related to building and deploying applications using Flightcontrol. By accessing this section, I will be able to locate the next necessary guide, which is the 'Building and Deploying a Remix project' link.

**Action:** click(571) # Click on the JavaScript link to explore the quickstart guides and examples for JavaScript.

**Change Description:** The browser navigated from the Flightcontrol Documentation page to the JavaScript Resource Center, updating the URL to 'https://www.flightcontrol.dev/docs/getting-started/javascript'. The content now focuses on JavaScript and its related resources, including new headings and links for guides, deployment examples, and configuration tips specific to JavaScript projects.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://www.flightcontrol.dev/docs/getting-started/javascript

https://www.flightcontrol.dev/docs/reference/examples/remix

**Content (before/after):** 

```
RootWebArea JavaScript Resource Center - Flightcontrol, focused, url='https://www.flightcontrol.dev/docs/getting-started/javascript'
	navigation
		[72] link Flightcontrol Logo, center=(344,32), url='https://www.flightcontrol.dev/'
			image Flightcontrol Logo, url='https://www.flightcontrol.dev/docs/img/fc-logo-black-wordmark.svg'
		[75] link Get Help, center=(1086,32), url='https://www.flightcontrol.dev/docs/troubleshooting/contacting-support'
```
<details><summary>Show more</summary>

```
		[76] link Status, center=(1150,32), url='https://status.flightcontrol.dev/'
		[77] link Roadmap, center=(1216,32), url='https://roadmap.flightcontrol.dev/roadmap'
		[78] link Changelog, center=(1297,32), url='https://roadmap.flightcontrol.dev/changelog'
		[79] button Search, center=(1452,32), inner_text=Search
K, type=button
			image
			StaticText K
		[87] link Sign Up, center=(1580,32), url='https://app.flightcontrol.dev/signup'
		[89] link Discord Discord, center=(1644,32), inner_text=Discord, url='https://discord.gg/yY8rSPrD6q'
			image Discord
	complementary
		list
			listitem
				[112] link Flightcontrol Docs, center=(363,96), url='https://www.flightcontrol.dev/docs'
			listitem
				[114] link Getting Started, center=(363,134), url='https://www.flightcontrol.dev/docs/getting-started'
					image
				list
					listitem
						[120] link First Project, center=(375,170), url='https://www.flightcontrol.dev/docs/getting-started/first-project'
					listitem
						[122] link Connecting GitHub, center=(375,208), url='https://www.flightcontrol.dev/docs/getting-started/connecting-github'
					[123] listitem, center=(375,244)
						separator, orientation='horizontal'
					listitem
						[126] link JavaScript, center=(375,282), url='https://www.flightcontrol.dev/docs/getting-started/javascript'
							image
						list
							listitem
								[132] link Node Version, center=(387,318), url='https://www.flightcontrol.dev/docs/getting-started/javascript/setting-node-version'
							listitem
								[134] link Instance Size, center=(387,356), url='https://www.flightcontrol.dev/docs/getting-started/javascript/node-fargate-instance-size'
					listitem
						[136] link Docker, center=(375,392), url='https://www.flightcontrol.dev/docs/getting-started/docker'
							image
						list
							listitem
								link Custom Dockerfile, url='https://www.flightcontrol.dev/docs/getting-started/docker/building-deploying-dockerfile'
							listitem
								link Docker Hub Images, url='https://www.flightcontrol.dev/docs/getting-started/docker/deploying-docker-hub'
							listitem
								link Amazon ECR Images, url='https://www.flightcontrol.dev/docs/getting-started/docker/deploying-docker-ecr'
							listitem
								link GitHub Container Registry, url='https://www.flightcontrol.dev/docs/getting-started/docker/github-container-registry'
							listitem
								link Automating Docker Deployments, url='https://www.flightcontrol.dev/docs/getting-started/docker/automating-docker-deployments'
					listitem
						[152] link Java, center=(375,430), url='https://www.flightcontrol.dev/docs/getting-started/java'
							image
						list
							listitem
								link Spring Boot, url='https://www.flightcontrol.dev/docs/getting-started/java/deploying-spring-boot'
					listitem
						[160] link PHP, center=(375,466), url='https://www.flightcontrol.dev/docs/getting-started/php'
							image
						list
							listitem
								link Laravel, url='https://www.flightcontrol.dev/docs/getting-started/php/deploying-laravel'
							listitem
								link PHP/Composer, url='https://www.flightcontrol.dev/docs/getting-started/php/deploying-php-composer'
					listitem
						[170] link Python, center=(375,504), url='https://www.flightcontrol.dev/docs/getting-started/python'
							image
						list
							listitem
								link Flask Deployment, url='https://www.flightcontrol.dev/docs/getting-started/python/getting-started-flask'
							listitem
								link Create a Flask App, url='https://www.flightcontrol.dev/docs/getting-started/python/creating-flask-app'
							listitem
								link Venv with Custom Commands, url='https://www.flightcontrol.dev/docs/getting-started/python/venv-custom-commands'
					listitem
						[182] link Ruby, center=(375,540), url='https://www.flightcontrol.dev/docs/getting-started/ruby'
							image
						list
							listitem
								link Rails Deployment, url='https://www.flightcontrol.dev/docs/getting-started/ruby/getting-started-rails'
							listitem
								link Using Sidekiq, url='https://www.flightcontrol.dev/docs/getting-started/ruby/using-sidekiq'
							listitem
								link Create a Rails App, url='https://www.flightcontrol.dev/docs/getting-started/ruby/creating-rails-app'
					[193] listitem, center=(375,578)
						separator, orientation='horizontal'
					listitem
						[196] link Everything Else, center=(375,614), url='https://www.flightcontrol.dev/docs/getting-started/everything-else'
			listitem
				[198] button Concepts, center=(363,652), type=button
					image
				list
					listitem
						[204] link Service Types, center=(375,688), url='https://www.flightcontrol.dev/docs/concepts/services'
					listitem
						[206] link Build Runners, center=(375,726), url='https://www.flightcontrol.dev/docs/concepts/build-runners'
					listitem
						[208] link Build Types, center=(375,762), url='https://www.flightcontrol.dev/docs/concepts/build-types'
					listitem
						[210] link Nixpacks, center=(375,800), url='https://www.flightcontrol.dev/docs/concepts/nixpacks'
					listitem
						[212] link Autoscaling, center=(375,836), url='https://www.flightcontrol.dev/docs/concepts/autoscaling'
			listitem
				[214] button Guides, center=(363,874), type=button
					image
				list
					listitem
						[220] button Flightcontrol, center=(375,910), type=button
							image
						list
							listitem
								[226] link Project Configuration, center=(387,948), url='https://www.flightcontrol.dev/docs/guides/flightcontrol/config'
							listitem
								[228] link Config with Code, center=(387,984), url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code'
									image
								list
									listitem
										link Web, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/web'
									listitem
										link Private Web, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/private-web'
									listitem
										link Worker, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/worker'
									listitem
										link Scheduler, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/scheduler'
									listitem
										link Lambda Function, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/lambda-function'
									listitem
										link Static Sites, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/static'
									listitem
										link RDS Database, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/rds'
									listitem
										link Redis, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/redis'
									listitem
										link Environment Variables, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/environment-variables'
							listitem
								link Config with Dashboard, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-ui'
							listitem
								link Environment Variables, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/environment-variables'
							listitem
								link Custom Domains, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/custom-domains'
							listitem
								link Logging, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/logging'
							listitem
								link Monorepo Setup, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/monorepos'
							listitem
								link Notifications, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/notifications'
							listitem
								link Preview Environments, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/preview-environment'
							listitem
								link SSO, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/sso'
					listitem
						button Amazon Web Services
							image
						list
							listitem
								link Getting Free AWS Credits, url='https://www.flightcontrol.dev/docs/guides/aws/aws-credits'
							listitem
								link Multiple AWS Accounts, url='https://www.flightcontrol.dev/docs/guides/aws/multiple-aws-accounts'
							listitem
								link Slack notification for ECS task status change, url='https://www.flightcontrol.dev/docs/guides/aws/ecs-task-status-notification'
					listitem
						button Integrations
							image
						list
							listitem
								button Datadog
									image
								list
									listitem
										link Set Up Core Datadog AWS Integration, url='https://www.flightcontrol.dev/docs/guides/integrations/datadog/setup'
									listitem
										link Metrics sidecar, url='https://www.flightcontrol.dev/docs/guides/integrations/datadog/metrics'
							listitem
								button Sentry
									image
								list
									listitem
										link Source Maps, url='https://www.flightcontrol.dev/docs/guides/integrations/sentry/uploading-source-maps'
							listitem
								link Logging with Firelens, url='https://www.flightcontrol.dev/docs/guides/integrations/logging'
					listitem
						button Advanced
							image
						list
							listitem
								link Watch Paths, url='https://www.flightcontrol.dev/docs/guides/advanced/watch-paths'
							listitem
								link Database Migrations, url='https://www.flightcontrol.dev/docs/guides/advanced/database-migrations'
							listitem
								link Pre-deploy Command, url='https://www.flightcontrol.dev/docs/guides/advanced/predeploy-command'
							listitem
								link Post-deploy Command, url='https://www.flightcontrol.dev/docs/guides/advanced/postdeploy-command'
							listitem
								link Deploy Prebuilt Image, url='https://www.flightcontrol.dev/docs/guides/advanced/deploy-prebuilt-image'
							listitem
								link Deploying into VPCs, url='https://www.flightcontrol.dev/docs/guides/advanced/deploying-vpc'
							listitem
								link Changing the Web Service Port, url='https://www.flightcontrol.dev/docs/guides/advanced/port-change'
							listitem
								link Git Submodules, url='https://www.flightcontrol.dev/docs/guides/advanced/git-submodules'
							listitem
								link Maintenance Mode, url='https://www.flightcontrol.dev/docs/guides/advanced/maintenance-mode'
							listitem
								link Rollback, url='https://www.flightcontrol.dev/docs/guides/advanced/rollback'
							listitem
								link Service Dependency, url='https://www.flightcontrol.dev/docs/guides/advanced/service-dependency'
							listitem
								link Sidecar Containers, url='https://www.flightcontrol.dev/docs/guides/advanced/sidecar-containers'
							listitem
								link Next.js Caching, url='https://www.flightcontrol.dev/docs/guides/advanced/isr'
							listitem
								link GitHub Actions, url='https://www.flightcontrol.dev/docs/guides/advanced/github-actions'
							listitem
								link Container Insights, url='https://www.flightcontrol.dev/docs/guides/advanced/enabling-container-insights'
							listitem
								link SSH, url='https://www.flightcontrol.dev/docs/guides/advanced/ssh'
							listitem
								link Multi-region, url='https://www.flightcontrol.dev/docs/guides/advanced/multi-region'
							listitem
								link Securely add environment variables to Dockerfile, url='https://www.flightcontrol.dev/docs/guides/advanced/add-env-vars-docker-securely'
					listitem
						button Migrations
							image
						list
							listitem
								link From Heroku, url='https://www.flightcontrol.dev/docs/guides/migrations/heroku-to-aws'
							listitem
								link Heroku Postgres to RDS, url='https://www.flightcontrol.dev/docs/guides/migrations/heroku-postgres-to-rds'
			listitem
				button Reference
					image
				list
					listitem
						link Flightcontrol API, url='https://www.flightcontrol.dev/docs/reference/http-api'
							image
						list
							listitem
								button Authorization
									image
								list
									listitem
										link API Keys, url='https://www.flightcontrol.dev/docs/reference/http-api/authorization/api-keys'
							listitem
								button Projects
									image
								list
									listitem
										link List Projects, url='https://www.flightcontrol.dev/docs/reference/http-api/projects/list-projects'
									listitem
										link Edit Preview Environment, url='https://www.flightcontrol.dev/docs/reference/http-api/projects/edit-preview-environment'
							listitem
								button Environments
									image
								list
									listitem
										link Create Environment, url='https://www.flightcontrol.dev/docs/reference/http-api/environments/create-environment'
									listitem
										link Edit Environment, url='https://www.flightcontrol.dev/docs/reference/http-api/environments/edit-environment'
							listitem
								button Services
									image
								list
									listitem
										link Get Service, url='https://www.flightcontrol.dev/docs/reference/http-api/services/get-service'
							listitem
								button Deployments
									image
								list
									listitem
										link Deploy Hooks, url='https://www.flightcontrol.dev/docs/reference/http-api/deployments/deploy-hooks'
									listitem
										link Get Deployment, url='https://www.flightcontrol.dev/docs/reference/http-api/deployments/get-deployment'
							listitem
								button CloudFront
									image
								list
									listitem
										link CloudFront Cache Invalidation, url='https://www.flightcontrol.dev/docs/reference/http-api/cloudfront/cache-invalidation-api'
									listitem
										link CloudFront Cache Invalidation Status, url='https://www.flightcontrol.dev/docs/reference/http-api/cloudfront/cache-invalidation-status-api'
							listitem
								button Scheduler Service
									image
								list
									listitem
										link Create Job Execution, url='https://www.flightcontrol.dev/docs/reference/http-api/scheduler/create-job-execution'
					listitem
						link Deployment Examples, url='https://www.flightcontrol.dev/docs/reference/examples'
							image
						list
							listitem
								link Blitz.js, url='https://www.flightcontrol.dev/docs/reference/examples/blitz'
							listitem
								link Bullet Train, url='https://www.flightcontrol.dev/docs/reference/examples/bullet-train'
							listitem
								link Docker, url='https://www.flightcontrol.dev/docs/reference/examples/docker'
							listitem
								link Gatsby, url='https://www.flightcontrol.dev/docs/reference/examples/gatsby'
							listitem
								link Hasura, url='https://www.flightcontrol.dev/docs/reference/examples/hasura'
							listitem
								link Next.js, url='https://www.flightcontrol.dev/docs/reference/examples/nextjs'
							listitem
								link Node.js, url='https://www.flightcontrol.dev/docs/reference/examples/node'
							listitem
								link Prisma Studio, url='https://www.flightcontrol.dev/docs/reference/examples/prisma-studio'
							listitem
								link Redwood, url='https://www.flightcontrol.dev/docs/reference/examples/redwood'
							listitem
								link Remix, url='https://www.flightcontrol.dev/docs/reference/examples/remix'
							listitem
								link Shopify App, url='https://www.flightcontrol.dev/docs/reference/examples/shopify'
							listitem
								link Strapi, url='https://www.flightcontrol.dev/docs/reference/examples/strapi'
							listitem
								link Docusaurus, url='https://www.flightcontrol.dev/docs/reference/examples/docusaurus'
							listitem
								link Solid, url='https://www.flightcontrol.dev/docs/reference/examples/solid'
							listitem
								link Vite, url='https://www.flightcontrol.dev/docs/reference/examples/vite'
			listitem
				link Troubleshooting and Errors, url='https://www.flightcontrol.dev/docs/troubleshooting'
					image
				list
					listitem
						link Contacting Support, url='https://www.flightcontrol.dev/docs/troubleshooting/contacting-support'
					listitem
						separator, orientation='horizontal'
					listitem
						link Changing Nixpacks Version, url='https://www.flightcontrol.dev/docs/troubleshooting/changing-nixpacks-version'
					listitem
						link CodeBuild Concurrency, url='https://www.flightcontrol.dev/docs/troubleshooting/codebuild-concurrency'
					listitem
						link Concurrency Limit for New Accounts, url='https://www.flightcontrol.dev/docs/troubleshooting/concurrency-limit'
					listitem
						link ECS Concurrent vCPU Limit, url='https://www.flightcontrol.dev/docs/troubleshooting/concurrent-cpu-limit'
					listitem
						link Configure CodeBuild, url='https://www.flightcontrol.dev/docs/troubleshooting/configure-codebuild'
					listitem
						link Docker Hub: Rate Limits, url='https://www.flightcontrol.dev/docs/troubleshooting/docker-hub-rate-limits'
					listitem
						link Fargate Task Storage, url='https://www.flightcontrol.dev/docs/troubleshooting/fargate-task-storage'
					listitem
						link Increase Node Memory, url='https://www.flightcontrol.dev/docs/troubleshooting/increase-node-memory'
					listitem
						link Long Deploys, url='https://www.flightcontrol.dev/docs/troubleshooting/long-deploys'
					listitem
						link Too Many VPCs, url='https://www.flightcontrol.dev/docs/troubleshooting/too-many-vpcs'
			listitem
				link Tips, url='https://www.flightcontrol.dev/docs/tips'
					image
				list
					listitem
						link Cloud Tips, url='https://www.flightcontrol.dev/docs/tips/cloud'
							image
						list
							listitem
								link Log Groups, url='https://www.flightcontrol.dev/docs/tips/cloud/log-groups'
							listitem
								link Object Storage, url='https://www.flightcontrol.dev/docs/tips/cloud/object-storage'
					listitem
						link Nixpacks Tips, url='https://www.flightcontrol.dev/docs/tips/nixpacks'
							image
						list
							listitem
								link Speeding Up the Build, url='https://www.flightcontrol.dev/docs/tips/nixpacks/speeding-up-nixpacks-builds'
					listitem
						link Deployment Tips, url='https://www.flightcontrol.dev/docs/tips/deployment'
							image
						list
							listitem
								link Puppeteer, url='https://www.flightcontrol.dev/docs/tips/deployment/puppeteer'
			listitem
				link Flightcontrol Security & Compliance, url='https://www.flightcontrol.dev/docs/security'
		[535] button System, center=(350,1050), expanded=False, hasPopup='listbox', title=Change theme, type=button
			image
		[539] button Hide sidebar, center=(466,1050), title=Hide sidebar, type=button
			image
	navigation table of contents
		paragraph
			StaticText On This Page
		list
			listitem
				[802] link Working with Monorepos, center=(1547,142), url='https://www.flightcontrol.dev/docs/getting-started/javascript#working-with-monorepos'
			listitem
				[804] link Guides, center=(1547,170), url='https://www.flightcontrol.dev/docs/getting-started/javascript#guides'
			listitem
				[806] link Deployment Examples, center=(1547,200), url='https://www.flightcontrol.dev/docs/getting-started/javascript#deployment-examples'
			listitem
				[808] link JavaScript and TypeScript Support in Nixpacks, center=(1547,239), url='https://www.flightcontrol.dev/docs/getting-started/javascript#javascript-and-typescript-support-in-nixpacks'
		link, url='https://github.com/shuding/nextra/pages/getting-started/javascript.mdx'
	article
		main
			[814] link Getting Started, center=(592,96), title=Getting Started, url='https://www.flightcontrol.dev/docs/getting-started'
			[811] button, center=(1485,308), inner_text=Scroll to top, type=button
			image
			StaticText JavaScript
			heading JavaScript Resource Center
			paragraph
				StaticText Flightcontrol was built from the ground up to support modern JavaScript and TypeScript web application frameworks.
			paragraph
				StaticText Powered by Nixpacks, Flightcontrol deploys applications that you built with Blitz.js, Next.js, Remix, Astro, Express, and more.
			paragraph
				StaticText If you can run your project with
				code
					StaticText npm start
				StaticText or
				code
					StaticText yarn start
				StaticText , you can deploy it with Flightcontrol. If it’s a little more complicated, you can always change the run, build, or install commands to match your requirements.
			paragraph
				StaticText This page points you to all of our JavaScript ecosystem resources in our documentation.
			heading Working with Monorepos Permalink for this section
				[825] link Permalink for this section, center=(899,520), url='https://www.flightcontrol.dev/docs/getting-started/javascript#working-with-monorepos'
			paragraph
				StaticText If you are using a monorepo, for instance, with the
				code
					StaticText pnpm
				StaticText tool, use our
				[828] link Monorepo Support, center=(1102,586), url='https://www.flightcontrol.dev/docs/guides/flightcontrol/monorepos'
				StaticText guide to learn how to configure your project to work with Flightcontrol.
			heading Guides Permalink for this section
				[830] link Permalink for this section, center=(657,715), url='https://www.flightcontrol.dev/docs/getting-started/javascript#guides'
			table
				rowgroup
					row
						columnheader Title
				rowgroup
					row
						cell Building and Deploying a Remix project
							[838] link Building and Deploying a Remix project, center=(697,828), url='https://www.flightcontrol.dev/docs/reference/examples/remix'
					row
						cell Deploying a Bullet Train project
							[841] link Deploying a Bullet Train project, center=(670,870), url='https://www.flightcontrol.dev/docs/reference/examples/bullet-train'
					row
						cell Deploying a Strapi project
							[844] link Deploying a Strapi project, center=(653,910), url='https://www.flightcontrol.dev/docs/reference/examples/strapi'
					row
						cell Deploying a Shopify App
							[847] link Deploying a Shopify App, center=(647,952), url='https://www.flightcontrol.dev/docs/reference/examples/shopify'
			heading Deployment Examples Permalink for this section
				[849] link Permalink for this section, center=(867,1059), url='https://www.flightcontrol.dev/docs/getting-started/javascript#deployment-examples'
			table
				rowgroup
					row
						columnheader Title
						columnheader Description
				rowgroup
					row
						cell Blitz.js
							link Blitz.js, url='https://www.flightcontrol.dev/docs/reference/examples/blitz'
						cell
					row
						cell Next.js
							link Next.js, url='https://www.flightcontrol.dev/docs/reference/examples/nextjs'
						cell
					row
						cell Node
							link Node, url='https://www.flightcontrol.dev/docs/reference/examples/node'
						cell Generic example suitable for most Node.js projects
					row
						cell Prisma Studio
							link Prisma Studio, url='https://www.flightcontrol.dev/docs/reference/examples/prisma-studio'
						cell
					row
						cell Redwood
							link Redwood, url='https://www.flightcontrol.dev/docs/reference/examples/redwood'
						cell
					row
						cell Docusaurus
							link Docusaurus, url='https://www.flightcontrol.dev/docs/reference/examples/docusaurus'
						cell
			heading JavaScript and TypeScript Support in Nixpacks Permalink for this section
				link Permalink for this section, url='https://www.flightcontrol.dev/docs/getting-started/javascript#javascript-and-typescript-support-in-nixpacks'
			paragraph
				StaticText Flightcontrol uses Nixpacks, an advanced form of build packs, to deploy your JavaScript or TypeScript application.
			paragraph
				StaticText Nixpacks detects what type of application you are trying to deploy, and then uses a series of rules in the specific Nixpack provider (such as the JavaScript provider) to determine exactly how to build, install, and run that application.
			paragraph
				StaticText Nixpacks itself is open source, and available to view on GitHub. Each Nixpacks provider is written in Rust, but you can read through the source code to see exactly what it is doing with your application.
			paragraph
				StaticText To learn more, see the Nixpacks Documentation and the source code of the provider:
			list
				listitem
					ListMarker •
					link Nixpacks Node Documentation, url='https://nixpacks.com/docs/providers/node'
				listitem
					ListMarker •
					link Nixpacks JavaScript Provider, url='https://github.com/railwayapp/nixpacks/blob/main/src/providers/node'
					StaticText (Source Code on GitHub)
			link Connecting GitHub, url='https://www.flightcontrol.dev/docs/getting-started/connecting-github'
				image
			link Node Version, url='https://www.flightcontrol.dev/docs/getting-started/javascript/setting-node-version'
				image
	contentinfo
		separator, orientation='horizontal'
		StaticText Flightcontrol
	alert, atomic
		StaticText JavaScript Resource Center - Flightcontrol
```
</details>



```
RootWebArea Building and Deploying a Remix Application with Flightcontrol - Flightcontrol, focused, url='https://www.flightcontrol.dev/docs/reference/examples/remix'
	navigation
		[72] link Flightcontrol Logo, center=(344,32), url='https://www.flightcontrol.dev/'
			image Flightcontrol Logo, url='https://www.flightcontrol.dev/docs/img/fc-logo-black-wordmark.svg'
		[75] link Get Help, center=(1086,32), url='https://www.flightcontrol.dev/docs/troubleshooting/contacting-support'
```
<details><summary>Show more</summary>

```
		[76] link Status, center=(1150,32), url='https://status.flightcontrol.dev/'
		[77] link Roadmap, center=(1216,32), url='https://roadmap.flightcontrol.dev/roadmap'
		[78] link Changelog, center=(1297,32), url='https://roadmap.flightcontrol.dev/changelog'
		[79] button Search, center=(1452,32), inner_text=Search
K, type=button
			image
			StaticText K
		[87] link Sign Up, center=(1580,32), url='https://app.flightcontrol.dev/signup'
		[89] link Discord Discord, center=(1644,32), inner_text=Discord, url='https://discord.gg/yY8rSPrD6q'
			image Discord
	complementary
		list
			listitem
				[112] link Flightcontrol Docs, center=(363,96), url='https://www.flightcontrol.dev/docs'
			listitem
				[114] link Getting Started, center=(363,134), url='https://www.flightcontrol.dev/docs/getting-started'
					image
				list
					listitem
						[120] link First Project, center=(375,170), url='https://www.flightcontrol.dev/docs/getting-started/first-project'
					listitem
						[122] link Connecting GitHub, center=(375,208), url='https://www.flightcontrol.dev/docs/getting-started/connecting-github'
					[123] listitem, center=(375,244)
						separator, orientation='horizontal'
					listitem
						[126] link JavaScript, center=(375,282), url='https://www.flightcontrol.dev/docs/getting-started/javascript'
							image
						list
							listitem
								[132] link Node Version, center=(387,318), url='https://www.flightcontrol.dev/docs/getting-started/javascript/setting-node-version'
							listitem
								[134] link Instance Size, center=(387,356), url='https://www.flightcontrol.dev/docs/getting-started/javascript/node-fargate-instance-size'
					listitem
						[136] link Docker, center=(375,392), url='https://www.flightcontrol.dev/docs/getting-started/docker'
							image
						list
							listitem
								link Custom Dockerfile, url='https://www.flightcontrol.dev/docs/getting-started/docker/building-deploying-dockerfile'
							listitem
								link Docker Hub Images, url='https://www.flightcontrol.dev/docs/getting-started/docker/deploying-docker-hub'
							listitem
								link Amazon ECR Images, url='https://www.flightcontrol.dev/docs/getting-started/docker/deploying-docker-ecr'
							listitem
								link GitHub Container Registry, url='https://www.flightcontrol.dev/docs/getting-started/docker/github-container-registry'
							listitem
								link Automating Docker Deployments, url='https://www.flightcontrol.dev/docs/getting-started/docker/automating-docker-deployments'
					listitem
						[152] link Java, center=(375,430), url='https://www.flightcontrol.dev/docs/getting-started/java'
							image
						list
							listitem
								link Spring Boot, url='https://www.flightcontrol.dev/docs/getting-started/java/deploying-spring-boot'
					listitem
						[160] link PHP, center=(375,466), url='https://www.flightcontrol.dev/docs/getting-started/php'
							image
						list
							listitem
								link Laravel, url='https://www.flightcontrol.dev/docs/getting-started/php/deploying-laravel'
							listitem
								link PHP/Composer, url='https://www.flightcontrol.dev/docs/getting-started/php/deploying-php-composer'
					listitem
						[170] link Python, center=(375,504), url='https://www.flightcontrol.dev/docs/getting-started/python'
							image
						list
							listitem
								link Flask Deployment, url='https://www.flightcontrol.dev/docs/getting-started/python/getting-started-flask'
							listitem
								link Create a Flask App, url='https://www.flightcontrol.dev/docs/getting-started/python/creating-flask-app'
							listitem
								link Venv with Custom Commands, url='https://www.flightcontrol.dev/docs/getting-started/python/venv-custom-commands'
					listitem
						[182] link Ruby, center=(375,540), url='https://www.flightcontrol.dev/docs/getting-started/ruby'
							image
						list
							listitem
								link Rails Deployment, url='https://www.flightcontrol.dev/docs/getting-started/ruby/getting-started-rails'
							listitem
								link Using Sidekiq, url='https://www.flightcontrol.dev/docs/getting-started/ruby/using-sidekiq'
							listitem
								link Create a Rails App, url='https://www.flightcontrol.dev/docs/getting-started/ruby/creating-rails-app'
					[193] listitem, center=(375,578)
						separator, orientation='horizontal'
					listitem
						[196] link Everything Else, center=(375,614), url='https://www.flightcontrol.dev/docs/getting-started/everything-else'
			listitem
				[198] button Concepts, center=(363,652), type=button
					image
				list
					listitem
						[204] link Service Types, center=(375,688), url='https://www.flightcontrol.dev/docs/concepts/services'
					listitem
						[206] link Build Runners, center=(375,726), url='https://www.flightcontrol.dev/docs/concepts/build-runners'
					listitem
						[208] link Build Types, center=(375,762), url='https://www.flightcontrol.dev/docs/concepts/build-types'
					listitem
						[210] link Nixpacks, center=(375,800), url='https://www.flightcontrol.dev/docs/concepts/nixpacks'
					listitem
						[212] link Autoscaling, center=(375,836), url='https://www.flightcontrol.dev/docs/concepts/autoscaling'
			listitem
				[214] button Guides, center=(363,874), type=button
					image
				list
					listitem
						[220] button Flightcontrol, center=(375,910), type=button
							image
						list
							listitem
								[226] link Project Configuration, center=(387,948), url='https://www.flightcontrol.dev/docs/guides/flightcontrol/config'
							listitem
								[228] link Config with Code, center=(387,984), url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code'
									image
								list
									listitem
										link Web, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/web'
									listitem
										link Private Web, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/private-web'
									listitem
										link Worker, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/worker'
									listitem
										link Scheduler, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/scheduler'
									listitem
										link Lambda Function, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/lambda-function'
									listitem
										link Static Sites, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/static'
									listitem
										link RDS Database, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/rds'
									listitem
										link Redis, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/redis'
									listitem
										link Environment Variables, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code/environment-variables'
							listitem
								link Config with Dashboard, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/using-ui'
							listitem
								link Environment Variables, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/environment-variables'
							listitem
								link Custom Domains, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/custom-domains'
							listitem
								link Logging, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/logging'
							listitem
								link Monorepo Setup, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/monorepos'
							listitem
								link Notifications, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/notifications'
							listitem
								link Preview Environments, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/preview-environment'
							listitem
								link SSO, url='https://www.flightcontrol.dev/docs/guides/flightcontrol/sso'
					listitem
						button Amazon Web Services
							image
						list
							listitem
								link Getting Free AWS Credits, url='https://www.flightcontrol.dev/docs/guides/aws/aws-credits'
							listitem
								link Multiple AWS Accounts, url='https://www.flightcontrol.dev/docs/guides/aws/multiple-aws-accounts'
							listitem
								link Slack notification for ECS task status change, url='https://www.flightcontrol.dev/docs/guides/aws/ecs-task-status-notification'
					listitem
						button Integrations
							image
						list
							listitem
								button Datadog
									image
								list
									listitem
										link Set Up Core Datadog AWS Integration, url='https://www.flightcontrol.dev/docs/guides/integrations/datadog/setup'
									listitem
										link Metrics sidecar, url='https://www.flightcontrol.dev/docs/guides/integrations/datadog/metrics'
							listitem
								button Sentry
									image
								list
									listitem
										link Source Maps, url='https://www.flightcontrol.dev/docs/guides/integrations/sentry/uploading-source-maps'
							listitem
								link Logging with Firelens, url='https://www.flightcontrol.dev/docs/guides/integrations/logging'
					listitem
						button Advanced
							image
						list
							listitem
								link Watch Paths, url='https://www.flightcontrol.dev/docs/guides/advanced/watch-paths'
							listitem
								link Database Migrations, url='https://www.flightcontrol.dev/docs/guides/advanced/database-migrations'
							listitem
								link Pre-deploy Command, url='https://www.flightcontrol.dev/docs/guides/advanced/predeploy-command'
							listitem
								link Post-deploy Command, url='https://www.flightcontrol.dev/docs/guides/advanced/postdeploy-command'
							listitem
								link Deploy Prebuilt Image, url='https://www.flightcontrol.dev/docs/guides/advanced/deploy-prebuilt-image'
							listitem
								link Deploying into VPCs, url='https://www.flightcontrol.dev/docs/guides/advanced/deploying-vpc'
							listitem
								link Changing the Web Service Port, url='https://www.flightcontrol.dev/docs/guides/advanced/port-change'
							listitem
								link Git Submodules, url='https://www.flightcontrol.dev/docs/guides/advanced/git-submodules'
							listitem
								link Maintenance Mode, url='https://www.flightcontrol.dev/docs/guides/advanced/maintenance-mode'
							listitem
								link Rollback, url='https://www.flightcontrol.dev/docs/guides/advanced/rollback'
							listitem
								link Service Dependency, url='https://www.flightcontrol.dev/docs/guides/advanced/service-dependency'
							listitem
								link Sidecar Containers, url='https://www.flightcontrol.dev/docs/guides/advanced/sidecar-containers'
							listitem
								link Next.js Caching, url='https://www.flightcontrol.dev/docs/guides/advanced/isr'
							listitem
								link GitHub Actions, url='https://www.flightcontrol.dev/docs/guides/advanced/github-actions'
							listitem
								link Container Insights, url='https://www.flightcontrol.dev/docs/guides/advanced/enabling-container-insights'
							listitem
								link SSH, url='https://www.flightcontrol.dev/docs/guides/advanced/ssh'
							listitem
								link Multi-region, url='https://www.flightcontrol.dev/docs/guides/advanced/multi-region'
							listitem
								link Securely add environment variables to Dockerfile, url='https://www.flightcontrol.dev/docs/guides/advanced/add-env-vars-docker-securely'
					listitem
						button Migrations
							image
						list
							listitem
								link From Heroku, url='https://www.flightcontrol.dev/docs/guides/migrations/heroku-to-aws'
							listitem
								link Heroku Postgres to RDS, url='https://www.flightcontrol.dev/docs/guides/migrations/heroku-postgres-to-rds'
			listitem
				button Reference
					image
				list
					listitem
						link Flightcontrol API, url='https://www.flightcontrol.dev/docs/reference/http-api'
							image
						list
							listitem
								button Authorization
									image
								list
									listitem
										link API Keys, url='https://www.flightcontrol.dev/docs/reference/http-api/authorization/api-keys'
							listitem
								button Projects
									image
								list
									listitem
										link List Projects, url='https://www.flightcontrol.dev/docs/reference/http-api/projects/list-projects'
									listitem
										link Edit Preview Environment, url='https://www.flightcontrol.dev/docs/reference/http-api/projects/edit-preview-environment'
							listitem
								button Environments
									image
								list
									listitem
										link Create Environment, url='https://www.flightcontrol.dev/docs/reference/http-api/environments/create-environment'
									listitem
										link Edit Environment, url='https://www.flightcontrol.dev/docs/reference/http-api/environments/edit-environment'
							listitem
								button Services
									image
								list
									listitem
										link Get Service, url='https://www.flightcontrol.dev/docs/reference/http-api/services/get-service'
							listitem
								button Deployments
									image
								list
									listitem
										link Deploy Hooks, url='https://www.flightcontrol.dev/docs/reference/http-api/deployments/deploy-hooks'
									listitem
										link Get Deployment, url='https://www.flightcontrol.dev/docs/reference/http-api/deployments/get-deployment'
							listitem
								button CloudFront
									image
								list
									listitem
										link CloudFront Cache Invalidation, url='https://www.flightcontrol.dev/docs/reference/http-api/cloudfront/cache-invalidation-api'
									listitem
										link CloudFront Cache Invalidation Status, url='https://www.flightcontrol.dev/docs/reference/http-api/cloudfront/cache-invalidation-status-api'
							listitem
								button Scheduler Service
									image
								list
									listitem
										link Create Job Execution, url='https://www.flightcontrol.dev/docs/reference/http-api/scheduler/create-job-execution'
					listitem
						link Deployment Examples, url='https://www.flightcontrol.dev/docs/reference/examples'
							image
						list
							listitem
								link Blitz.js, url='https://www.flightcontrol.dev/docs/reference/examples/blitz'
							listitem
								link Bullet Train, url='https://www.flightcontrol.dev/docs/reference/examples/bullet-train'
							listitem
								link Docker, url='https://www.flightcontrol.dev/docs/reference/examples/docker'
							listitem
								link Gatsby, url='https://www.flightcontrol.dev/docs/reference/examples/gatsby'
							listitem
								link Hasura, url='https://www.flightcontrol.dev/docs/reference/examples/hasura'
							listitem
								link Next.js, url='https://www.flightcontrol.dev/docs/reference/examples/nextjs'
							listitem
								link Node.js, url='https://www.flightcontrol.dev/docs/reference/examples/node'
							listitem
								link Prisma Studio, url='https://www.flightcontrol.dev/docs/reference/examples/prisma-studio'
							listitem
								link Redwood, url='https://www.flightcontrol.dev/docs/reference/examples/redwood'
							listitem
								link Remix, url='https://www.flightcontrol.dev/docs/reference/examples/remix'
							listitem
								link Shopify App, url='https://www.flightcontrol.dev/docs/reference/examples/shopify'
							listitem
								link Strapi, url='https://www.flightcontrol.dev/docs/reference/examples/strapi'
							listitem
								link Docusaurus, url='https://www.flightcontrol.dev/docs/reference/examples/docusaurus'
							listitem
								link Solid, url='https://www.flightcontrol.dev/docs/reference/examples/solid'
							listitem
								link Vite, url='https://www.flightcontrol.dev/docs/reference/examples/vite'
			listitem
				link Troubleshooting and Errors, url='https://www.flightcontrol.dev/docs/troubleshooting'
					image
				list
					listitem
						link Contacting Support, url='https://www.flightcontrol.dev/docs/troubleshooting/contacting-support'
					listitem
						separator, orientation='horizontal'
					listitem
						link Changing Nixpacks Version, url='https://www.flightcontrol.dev/docs/troubleshooting/changing-nixpacks-version'
					listitem
						link CodeBuild Concurrency, url='https://www.flightcontrol.dev/docs/troubleshooting/codebuild-concurrency'
					listitem
						link Concurrency Limit for New Accounts, url='https://www.flightcontrol.dev/docs/troubleshooting/concurrency-limit'
					listitem
						link ECS Concurrent vCPU Limit, url='https://www.flightcontrol.dev/docs/troubleshooting/concurrent-cpu-limit'
					listitem
						link Configure CodeBuild, url='https://www.flightcontrol.dev/docs/troubleshooting/configure-codebuild'
					listitem
						link Docker Hub: Rate Limits, url='https://www.flightcontrol.dev/docs/troubleshooting/docker-hub-rate-limits'
					listitem
						link Fargate Task Storage, url='https://www.flightcontrol.dev/docs/troubleshooting/fargate-task-storage'
					listitem
						link Increase Node Memory, url='https://www.flightcontrol.dev/docs/troubleshooting/increase-node-memory'
					listitem
						link Long Deploys, url='https://www.flightcontrol.dev/docs/troubleshooting/long-deploys'
					listitem
						link Too Many VPCs, url='https://www.flightcontrol.dev/docs/troubleshooting/too-many-vpcs'
			listitem
				link Tips, url='https://www.flightcontrol.dev/docs/tips'
					image
				list
					listitem
						link Cloud Tips, url='https://www.flightcontrol.dev/docs/tips/cloud'
							image
						list
							listitem
								link Log Groups, url='https://www.flightcontrol.dev/docs/tips/cloud/log-groups'
							listitem
								link Object Storage, url='https://www.flightcontrol.dev/docs/tips/cloud/object-storage'
					listitem
						link Nixpacks Tips, url='https://www.flightcontrol.dev/docs/tips/nixpacks'
							image
						list
							listitem
								link Speeding Up the Build, url='https://www.flightcontrol.dev/docs/tips/nixpacks/speeding-up-nixpacks-builds'
					listitem
						link Deployment Tips, url='https://www.flightcontrol.dev/docs/tips/deployment'
							image
						list
							listitem
								link Puppeteer, url='https://www.flightcontrol.dev/docs/tips/deployment/puppeteer'
			listitem
				link Flightcontrol Security & Compliance, url='https://www.flightcontrol.dev/docs/security'
		[535] button System, center=(350,1050), expanded=False, hasPopup='listbox', title=Change theme, type=button
			image
		[539] button Hide sidebar, center=(466,1050), title=Hide sidebar, type=button
			image
	navigation table of contents
		paragraph
			StaticText On This Page
		list
			listitem
				[920] link Prerequisites, center=(1547,142), url='https://www.flightcontrol.dev/docs/reference/examples/remix#prerequisites'
			[811] button, center=(1485,703), inner_text=Scroll to top, type=button
			listitem
				[922] link Creating the Remix Jokes Application Locally, center=(1547,181), url='https://www.flightcontrol.dev/docs/reference/examples/remix#creating-the-remix-jokes-application-locally'
			listitem
				[924] link Updating the Node Version, center=(1555,220), url='https://www.flightcontrol.dev/docs/reference/examples/remix#updating-the-node-version'
			listitem
				[926] link Changing the Database Provider, center=(1555,260), url='https://www.flightcontrol.dev/docs/reference/examples/remix#changing-the-database-provider'
			listitem
				[928] link Running Prisma Migrate Locally, center=(1555,310), url='https://www.flightcontrol.dev/docs/reference/examples/remix#running-prisma-migrate-locally'
			listitem
				[930] link Running the Jokes Web Application Locally, center=(1555,360), url='https://www.flightcontrol.dev/docs/reference/examples/remix#running-the-jokes-web-application-locally'
			listitem
				[932] link Creating a GitHub Repository, center=(1555,400), url='https://www.flightcontrol.dev/docs/reference/examples/remix#creating-a-github-repository'
			listitem
				[934] link Deploying with Flightcontrol, center=(1547,428), url='https://www.flightcontrol.dev/docs/reference/examples/remix#deploying-with-flightcontrol'
			listitem
				[936] link Creating a Project on Flightcontrol, center=(1555,468), url='https://www.flightcontrol.dev/docs/reference/examples/remix#creating-a-project-on-flightcontrol'
			listitem
				[938] link Configure your Project, center=(1555,508), url='https://www.flightcontrol.dev/docs/reference/examples/remix#configure-your-project'
			listitem
				[940] link Using the Remix Preset, center=(1555,536), url='https://www.flightcontrol.dev/docs/reference/examples/remix#using-the-remix-preset'
			listitem
				[942] link Modifying the Remix App Service, center=(1555,576), url='https://www.flightcontrol.dev/docs/reference/examples/remix#modifying-the-remix-app-service'
			listitem
				[944] link Launching the Project, center=(1555,616), url='https://www.flightcontrol.dev/docs/reference/examples/remix#launching-the-project'
			listitem
				[946] link Next Steps, center=(1547,644), url='https://www.flightcontrol.dev/docs/reference/examples/remix#next-steps'
		link, url='https://github.com/shuding/nextra/pages/reference/examples/remix.mdx'
	article
		main
			[947] link Reference, center=(577,96), title=Reference, url='https://www.flightcontrol.dev/docs/reference/http-api'
			image
			[949] link Deployment Examples, center=(702,96), title=Deployment Examples, url='https://www.flightcontrol.dev/docs/reference/examples'
			image
			StaticText Remix
			heading Building and Deploying a Remix Application with Flightcontrol
			paragraph
				StaticText This guide will walk you through the process of building and deploying a
				[954] link Remix, center=(1070,260), url='https://www.remix.run/'
				StaticText application to AWS using Flightcontrol.
			paragraph
				StaticText In particular, we will use the
				[956] link Remix Jokes Tutorial, center=(809,312), url='http://remix.run/docs/en/main/tutorials/jokes'
				StaticText as a starting point. This project uses
				[957] link Prisma, center=(1173,312), url='https://www.prisma.io/'
				StaticText to connect to a SQLite database. We will change the database provider to be Postgres and then deploy the project to AWS.
			paragraph
				StaticText Once we’re finished, you’ll have a Remix application running on AWS with a Postgres database.
			paragraph
				StaticText If you have your own Remix project, it should deploy in a very similar manner. Feel free to skip ahead to the
				link Deploying with Flightcontrol, url='https://www.flightcontrol.dev/docs/reference/examples/remix#deploying-with-flightcontrol'
				StaticText section.
			heading Prerequisites Permalink for this section
				[962] link Permalink for this section, center=(744,573), url='https://www.flightcontrol.dev/docs/reference/examples/remix#prerequisites'
			paragraph
				StaticText You’ll need to have Node.js (Node 16 or higher) and Postgres installed locally, as well as the following accounts:
			list
				listitem
					ListMarker •
					[966] link GitHub Account, center=(624,688), url='https://www.github.com/'
				listitem
					ListMarker •
					[968] link AWS Account, center=(617,720), url='https://aws.amazon.com/'
				listitem
					ListMarker •
					[970] link Flightcontrol Account, center=(644,752), url='https://app.flightcontrol.dev/'
			heading Creating the Remix Jokes Application Locally Permalink for this section
				[972] link Permalink for this section, center=(1176,851), url='https://www.flightcontrol.dev/docs/reference/examples/remix#creating-the-remix-jokes-application-locally'
			paragraph
				StaticText For context, see the
				[974] link Remix Jokes Tutorial, center=(762,916), url='http://remix.run/docs/en/main/tutorials/jokes'
				StaticText - we’ll be using the final code from that tutorial as a starting point.
			paragraph
				StaticText Remix provides an easy way to setup an example project with their command line tool:
			code
				StaticText npx
				StaticText create-remix@latest
				StaticText --template
				StaticText examples/_official-jokes
			[987] button Copy code, center=(1345,1030), title=Copy code, type=button
				image
			paragraph
				StaticText You should see something similar to the following set of questions and answers, which will create a new directory called
				code
					StaticText jokes
				StaticText with the Remix application.
			code
				StaticText ? Where would you like to create your app? jokes
				StaticText ? TypeScript or JavaScript? TypeScript
				StaticText ? Do you want me to run `npm install`? Yes
				StaticText ⠦ Creating your app…(⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂) ⠧ idealTree:jokes: sill idealTree buildnpm WARN deprecated @npmcli/move-file@1.1.2: This functionality has been moved to @npmcli/fs
				StaticText added 999 packages, and audited 1000 packages in 60s
				StaticText 257 packages are looking for funding
				StaticText run `npm fund` for details
				StaticText found 0 vulnerabilities
				StaticText 💿 That's it! `cd` into "your-directory/jokes" and check the README for development and deploy instructions!
			button Copy code
				image
			paragraph
				StaticText We do need to update the Node version and modify the database configuration before running the Jokes project locally.
			heading Updating the Node Version Permalink for this section
				link Permalink for this section, url='https://www.flightcontrol.dev/docs/reference/examples/remix#updating-the-node-version'
			paragraph
				StaticText The Remix Jokes project uses Node 14, but we want to use Node 16. To update the Node version, we need to update the
				code
					StaticText package.json
				StaticText file to include the following (instead of
				code
					StaticText >=14
				StaticText ):
			code
				StaticText "engines"
				StaticText : {
				StaticText "node"
				StaticText :
				StaticText ">=16"
				StaticText }
			button Copy code
				image
			paragraph
				StaticText After making the change to the
				code
					StaticText package.json
				StaticText file, run
				code
					StaticText npm install
				StaticText to update the dependencies.
			heading Changing the Database Provider Permalink for this section
				link Permalink for this section, url='https://www.flightcontrol.dev/docs/reference/examples/remix#changing-the-database-provider'
			paragraph
				StaticText Inside the
				code
					StaticText jokes
				StaticText directory, you will find a
				code
					StaticText schema.prisma
				StaticText file. This file defines the database schema for the application. By default, this Remix example uses SQLite, but we want to use Postgres. MySQL would also be an option.
			paragraph
				StaticText Change the database section from:
			code
				StaticText datasource
				StaticText db
				StaticText {
				StaticText provider
				StaticText =
				StaticText "sqlite"
				StaticText url
				StaticText =
				StaticText env
				StaticText (
				StaticText "DATABASE_URL"
				StaticText )
				StaticText }
			button Copy code
				image
			paragraph
				StaticText to:
			code
				StaticText datasource
				StaticText db
				StaticText {
				StaticText provider
				StaticText =
				StaticText "postgres"
				StaticText url
				StaticText =
				StaticText env
				StaticText (
				StaticText "DATABASE_URL"
				StaticText )
				StaticText }
			button Copy code
				image
			paragraph
				StaticText You will also need to create a
				code
					StaticText .env
				StaticText file in the
				code
					StaticText jokes
				StaticText directory that includes the following:
			code
				StaticText DATABASE_URL="postgres://jeff@localhost:5432/remix_jokes"
				StaticText SESSION_SECRET="some-random-string"
			button Copy code
				image
			paragraph
				StaticText where
				code
					StaticText jeff
				StaticText is your username. You can find your username by running
				code
					StaticText whoami
				StaticText in your terminal on Linux or MacOS. For Windows, it will be the name of the folder in your
				code
					StaticText C:\Users
				StaticText directory.
			paragraph
				StaticText The session secret should also be a random string - not the default “remix-rulz” that can be found in the
				code
					StaticText .env.example
				StaticText file.
			heading Running Prisma Migrate Locally Permalink for this section
				link Permalink for this section, url='https://www.flightcontrol.dev/docs/reference/examples/remix#running-prisma-migrate-locally'
			paragraph
				StaticText Switching the database provider to Postgres means that we will need to delete the existing
				code
					StaticText migrations
				StaticText folder in our
				code
					StaticText jokes
				StaticText directory. This folder contains the migrations for SQLite, which we no longer need. For more about how Prisma manages switching database providers, see this
				link page on the Prisma docs, url='https://www.prisma.io/docs/concepts/components/prisma-migrate/prisma-migrate-limitations-issues#you-cannot-automatically-switch-database-providers'
			paragraph
				StaticText After deleting the existing SQLite migrations folder, we need to run the following command:
			code
				StaticText npx
				StaticText prisma
				StaticText migrate
				StaticText dev
				StaticText --name
				StaticText init
			button Copy code
				image
			paragraph
				StaticText This will create a new
				code
					StaticText migrations
				StaticText folder with the Postgres migrations. You should see something similar to the following:
			code
				StaticText Environment variables loaded from .env
				StaticText Prisma schema loaded from prisma/schema.prisma
				StaticText Datasource "db": PostgreSQL database "remix_jokes", schema "public" at "localhost:5432"
				StaticText Applying migration `20230620162445_init`
				StaticText The following migration(s) have been created and applied from new schema changes:
				StaticText migrations/
				StaticText └─ 20230620162445_init/
				StaticText └─ migration.sql
				StaticText Your database is now in sync with your schema.
				StaticText ✔ Generated Prisma Client (4.16.0 | library) to ./node_modules/@prisma/client in
				StaticText 47ms
			button Copy code
				image
			paragraph
				StaticText After the database is migrated, we can run the application on our own computer.
			heading Running the Jokes Web Application Locally Permalink for this section
				link Permalink for this section, url='https://www.flightcontrol.dev/docs/reference/examples/remix#running-the-jokes-web-application-locally'
			paragraph
				StaticText To run the application locally, you can run the following command:
			code
				StaticText npm
				StaticText run
				StaticText dev
			button Copy code
				image
			paragraph
				StaticText The jokes application should now be running at
				link http://localhost:3000, url='http://localhost:3000/'
				StaticText .
			heading Creating a GitHub Repository Permalink for this section
				link Permalink for this section, url='https://www.flightcontrol.dev/docs/reference/examples/remix#creating-a-github-repository'
			paragraph
				StaticText The last step is to create a Github repository for your project. You can use your favorite tools to create a GitHub repository, include your changes, and then push to GitHub.
			paragraph
				StaticText Your repository can be public or private. Flightcontrol connects with GitHub to deploy your application, so you will need to give Flightcontrol access to your repository.
			heading Deploying with Flightcontrol Permalink for this section
				link Permalink for this section, url='https://www.flightcontrol.dev/docs/reference/examples/remix#deploying-with-flightcontrol'
			paragraph
				StaticText Now that you have a Remix application to run, we can use Flightcontrol to deploy it to AWS.
			paragraph
				StaticText To create a Flightcontrol account, sign up at the
				link Flightcontrol Dashboard, url='https://app.flightcontrol.dev/'
				StaticText .
			heading Creating a Project on Flightcontrol Permalink for this section
				link Permalink for this section, url='https://www.flightcontrol.dev/docs/reference/examples/remix#creating-a-project-on-flightcontrol'
			paragraph
				StaticText If you haven’t already created a Flightcontrol account, you can do so at the
				link Flightcontrol Dashboard, url='https://app.flightcontrol.dev/'
				StaticText .
			paragraph
				StaticText Now that you have a Flightcontrol account, you can create a new project. Flightcontrol projects represent a single application or set of related applications that you want to deploy to AWS. Each project can have multiple environments, such as staging or production. Each environment can then have one or more services, such as a web application or a database.
			paragraph
				StaticText To create a new project, click the
				strong
					StaticText Create Project
				StaticText button on the right hand side of the dashboard. If you don’t have any projects yet, Flightcontrol will show you the form to create one when you log in to Flightcontrol.
			image Choose a Repository from the List, url='https://www.flightcontrol.dev/docs/_next/image?url=%2Fdocs%2F_next%2Fstatic%2Fmedia%2Fremix-choose-repository.63c1d249.png&w=640&q=75'
			paragraph
				StaticText If you don’t have the GitHub repository you want to deploy in that list, click the button at the bottom of the form that takes you to the Flightcontrol GitHub app. On that web page, you can authorize specific repositories for Flightcontrol to access.
			paragraph
				StaticText If you haven’t connected your Flightcontrol account to GitHub yet, let’s do that now.
			paragraph
				StaticText Follow our guide on
				link Connecting Flightcontrol to GitHub, url='https://www.flightcontrol.dev/docs/getting-started/connecting-github'
				StaticText to walk you through the necessary steps.
			paragraph
				StaticText Authorize access to the Remix repository you want to deploy. You don’t need to authorize access to all of your repositories.
			paragraph
				StaticText Once the GitHub repository is selected, you will be taken to the next step in the project creation process.
			heading Configure your Project Permalink for this section
				link Permalink for this section, url='https://www.flightcontrol.dev/docs/reference/examples/remix#configure-your-project'
			paragraph
				StaticText On the next screen, you configure the Flightcontrol Project. This includes the name of the project, the AWS account to use, the AWS region to deploy to, and the Git branch you want to pull from.
			image Configure a Project screen in Dashboard, url='https://www.flightcontrol.dev/docs/_next/image?url=%2Fdocs%2F_next%2Fstatic%2Fmedia%2Fremix-configure-project.d7b484a4.png&w=640&q=75'
			paragraph
				StaticText Choose your AWS account, and an AWS region, and then click the
				strong
					StaticText Next
				StaticText button.
			heading Using the Remix Preset Permalink for this section
				link Permalink for this section, url='https://www.flightcontrol.dev/docs/reference/examples/remix#using-the-remix-preset'
			paragraph
				StaticText On the next screen, you will see a list of presets. Presets are a set of services that Flightcontrol will configure for you. For this project, we will use the Remix preset.
			image Selecting the Remix Preset in the Dashboard, url='https://www.flightcontrol.dev/docs/_next/image?url=%2Fdocs%2F_next%2Fstatic%2Fmedia%2Fremix-preset.4bc7ac55.png&w=640&q=75'
			paragraph
				StaticText The Remix preset will configure the following services:
			list
				listitem
					ListMarker •
					StaticText Web Server with Amazon ECS Fargate
				listitem
					ListMarker •
					StaticText Postgres Database with Amazon Relational Database Service (RDS)
			paragraph
				StaticText The preset also sets an environment variable for the
				code
					StaticText SESSION_SECRET
				StaticText , which is required for the Remix application to run.
			paragraph
				StaticText Click the
				strong
					StaticText Remix
				StaticText preset, and Flightcontrol will take you to the next step.
			image Configured Remix Services, url='https://www.flightcontrol.dev/docs/_next/image?url=%2Fdocs%2F_next%2Fstatic%2Fmedia%2Fremix-services.2cd3d921.png&w=750&q=75'
			paragraph
				StaticText You can view the services that Flightcontrol will create. We will need to adjust the Remix App service to work with the Remix Jokes application.
			paragraph
				StaticText Click the
				strong
					StaticText Remix App
				StaticText Service to view the configuration.
			heading Modifying the Remix App Service Permalink for this section
				link Permalink for this section, url='https://www.flightcontrol.dev/docs/reference/examples/remix#modifying-the-remix-app-service'
			paragraph
				StaticText We need to provide a new build command for the Remix App service. The Remix Jokes application uses the following command to build the application:
			code
				StaticText npm
				StaticText run
				StaticText build
				StaticText &&
				StaticText npx
				StaticText prisma
				StaticText migrate
				StaticText deploy
			button Copy code
				image
			image Setting a build command, url='https://www.flightcontrol.dev/docs/_next/image?url=%2Fdocs%2F_next%2Fstatic%2Fmedia%2Fremix-build-command.4e60d163.png&w=640&q=75'
			paragraph
				StaticText We also need to adjust the health check path. The Jokes application does not have a health check path at the default Remix preset path of
				code
					StaticText /healthcheck
				StaticText , so we need to configure Flightcontrol to use the root path,
				code
					StaticText /
				StaticText .
			image Changing the Health check path, url='https://www.flightcontrol.dev/docs/_next/image?url=%2Fdocs%2F_next%2Fstatic%2Fmedia%2Fremix-health-check.2a2dd5e7.png&w=640&q=75'
			paragraph
				StaticText Once you finish configuration, click the
				strong
					StaticText Update service
				StaticText button to continue.
			heading Launching the Project Permalink for this section
				link Permalink for this section, url='https://www.flightcontrol.dev/docs/reference/examples/remix#launching-the-project'
			paragraph
				StaticText You’ll be taken back to the project overview screen. You can review the configuration, and then click the
				strong
					StaticText Create Project
				StaticText button.
			image Configured Remix Services, url='https://www.flightcontrol.dev/docs/_next/image?url=%2Fdocs%2F_next%2Fstatic%2Fmedia%2Fremix-services.2cd3d921.png&w=750&q=75'
			paragraph
				StaticText Flightcontrol will start the deployment process! Expect this to take between 10-20 minutes for the initial setup and deployment. Subsequent deployments will be much faster.
			paragraph
				StaticText Once the deployment is complete, you will have a URL for your project! In the following screenshot, the URL is highlighted - you can find it in the
				strong
					StaticText Remix App
				StaticText service.
			image Project URL highlighted on the dashboard., url='https://www.flightcontrol.dev/docs/_next/image?url=%2Fdocs%2F_next%2Fstatic%2Fmedia%2Fremix-deploy-success.3a125b16.png&w=1080&q=75'
			paragraph
				StaticText Visit the URL and enjoy your new Remix application running on AWS!
			image Remix Jokes App Running, url='https://www.flightcontrol.dev/docs/_next/image?url=%2Fdocs%2F_next%2Fstatic%2Fmedia%2Fremix-jokes-running.1e1a9eaf.png&w=1080&q=75'
			heading Next Steps Permalink for this section
				link Permalink for this section, url='https://www.flightcontrol.dev/docs/reference/examples/remix#next-steps'
			paragraph
				StaticText After a successful deployment with the Remix jokes application, make your own change to your GitHub repo and deploy it again! You’ll see a quick deployment time (compared to the initial launch) and your changes will be live.
			paragraph
				StaticText After you’re finished, be sure to delete the project from Flightcontrol to avoid any unnecessary charges.
			paragraph
				StaticText If you need any help getting this project (or any other project) up and running on Flightcontrol, please reach out to
				link our support, url='https://www.flightcontrol.dev/docs/troubleshooting/contacting-support'
			link Redwood, url='https://www.flightcontrol.dev/docs/reference/examples/redwood'
				image
			link Shopify App, url='https://www.flightcontrol.dev/docs/reference/examples/shopify'
				image
	contentinfo
		separator, orientation='horizontal'
		StaticText Flightcontrol
	alert, atomic
		StaticText Building and Deploying a Remix Application with Flightcontrol - Flightcontrol
```
</details>

**Reasoning for action:** By clicking on the 'Building and Deploying a Remix project' link, I have navigated to the relevant content that directly addresses the user's need for specific guides and examples related to using Flightcontrol for deploying applications. This action is essential in moving closer to achieving the user's goals, as it ensures that they can access and review the specific instructions necessary for their development work.

**Action:** click(838) # Click on the 'Building and Deploying a Remix project' link to explore a specific deployment example.

**Change Description:** The browser navigated to a new page titled 'Building and Deploying a Remix Application with Flightcontrol', revealing specific deployment instructions and resources for deploying a Remix application, replacing the previous content focused on JavaScript.

**Screenshot before:****Screenshot after:**---

