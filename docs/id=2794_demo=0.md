# Task

**Explore Blog Articles on Fly.io**

As a curious developer,
I explore articles on the Fly.io blog to learn about new technology insights and updates,
so that I can stay informed and enhance my knowledge about cloud deployment and development practices.

**Success definition:** Given I am on the Fly.io homepage
When I navigate to the Blog and click on an article titled 'AI GPU Clusters, From Your Laptop, With Livebook'
Then I should see the full article content displayed with headings, images, and interactive elements.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://fly.io/

https://fly.io/

**Content (before/after):** 

```
RootWebArea Deploy app servers close to your users · Fly, focused, url='https://fly.io/'
	banner
		navigation Logo menu
			[38] link The Fly.io logo: a stylized white and purple hot air balloon on a deep purple background, center=(448,48), url='https://fly.io/'
		navigation Main menu
```
<details><summary>Show more</summary>

```
			DescriptionList
				[50] term, center=(730,48), inner_text=Articles
					StaticText Articles
				definition
					link Blog, url='https://fly.io/blog/'
					link Phoenix Files, url='https://fly.io/phoenix-files/'
					link Laravel Bytes, url='https://fly.io/laravel-bytes/'
					link Ruby Dispatch, url='https://fly.io/ruby-dispatch/'
					link Django Beats, url='https://fly.io/django-beats/'
					link JavaScript Journal, url='https://fly.io/javascript-journal/'
			[59] link Security, center=(808,48), url='https://fly.io/security/'
			[63] link Infra Log, center=(890,48), url='https://fly.io/infra-log/'
			[67] link Docs, center=(960,48), url='https://fly.io/docs/'
			[71] link Community, center=(1039,48), url='https://community.fly.io/'
			[75] link Status, center=(1124,48), url='https://status.flyio.net/'
			[79] link Pricing, center=(1193,48), url='https://fly.io/pricing/'
			[84] link Sign In, center=(1384,48), url='https://fly.io/app/sign-in'
			[88] link Get Started, center=(1473,48), url='https://fly.io/app/sign-up'
	image
	main
		heading A Public Cloud Built For Developers Who Ship
			emphasis
		paragraph
			strong
				StaticText Over 3 million apps
			StaticText have launched on Fly.io, leveraging global Anycast load-balancing, zero-config private networking, hardware isolation, and instant WireGuard VPN connections, with push-button deployments scaling to thousands of instances.
		[124] link Deploy Your App in 5 minutes, center=(960,536), url='https://fly.io/app/sign-up'
			image
			image
		heading Public Cloud Infrastructure. Modern Platform Endorphins.
		paragraph
			StaticText The most flexible and powerful compute platform on any public cloud. Fly Machines are hardware-virtualized containers, running on our own hardware, that launch instantly and run exactly as long as you want them to — for a single HTTP request, or for weeks of uptime.
		image
		image, url='https://fly.io/phx/ui/images/fly-globe-cb332f77ddb429aa3ef4e0a2c6c592ba.png?vsn=d'
		list
			listitem
				image
				heading Get Right in Your Users’ Faces
				paragraph
					StaticText Deploy in 35 regions, from Sydney to São Paulo, for sub-100ms response times and native-app feel no matter where your users are.
			listitem
				image
				heading Fork Off VMs Like They’re Processes
				paragraph
					StaticText Fly Machines start fast enough to handle HTTP requests, run only when you need them, and scale into tens of thousands of instances.
			listitem
				image
				heading Ship GPU-Boosted Models
				paragraph
					StaticText From LLMs to inferencing, hardware acceleration with the same developer experience as a simple CRUD app.
			listitem
				image
				heading Built for Distributed Systems
				paragraph
					StaticText Clustered databases like Cockroach, globally-distributed Postgres, and modern RPC systems like Elixir FLAME, no Terraform required.
		image, url='https://fly.io/phx/ui/images/cool-bird-d997174954ab5a152ccac3d2dcb19c8d.png?vsn=d'
		heading Support By Developers For Developers
		paragraph
			StaticText Paid support packages include a team of actual engineers (not chatbots) who themselves ship code on our platform. Emergency support and guaranteed response times available.
		link Learn More, url='https://fly.io/support'
			image
			image
		heading Enterprise-Ready
		paragraph
			StaticText Apps running on Fly Machines are KVM hardware-isolated, built on a memory-safe stack and running directly on our own metal.
		link Enterprise Features, url='https://fly.io/enterprise'
			image
			image
		link Fly.io Security, url='https://fly.io/security'
			image
			image
		list
			listitem
				StaticText Single Sign-On
			listitem
				StaticText Guaranteed Support Response Times
			listitem
				StaticText SOC2 Type 2 Attested
			listitem
				StaticText Memory-safe Rust and Go stack
			listitem
				StaticText CI/CD Integration
		image, url='https://fly.io/phx/ui/images/js-love-b469706c4be3625b972ee3fdfcb80687.png?vsn=d'
		heading Serverful JavaScript Without the Hassle of Serverless
		paragraph
			StaticText Imagine if a server could boot as fast as a serverless function? That's Fly Machines—serverless compute is a trade-off you no longer need to make. Graduate to a full-stack cloud to regain control over your stack & hosting bill.
		list
			listitem
				image
				heading Boots in 250ms or Less
				paragraph
					StaticText Functions and apps boot and respond to web requests in 250ms or less with Fly Machines. You decide to keep them running or automatically put them to sleep.
			listitem
				image
				heading Built for JavaScript Developers
				paragraph
					StaticText JavaScript, TypeScript, Bun, Deno—whatever your flavor, Fly Launch automatically detects your runtime and generates a VM with everything you need to run your app.
			listitem
				image
				heading Real GPUs & CPUs on the Edge
				paragraph
					StaticText Run workloads that require GPUs or lots of CPUs, memory, and storage in over 30 regions around the world—all interconnected by a private, encrypted WireGuard network that works out of the box.
		heading Use the Tech You Love
		paragraph
			StaticText Build with your favorite framework. No Dockerfile? No problem: our CLI generates containers for most popular frameworks, including Rails, Phoenix, Django, Node, Laravel, and .NET.
		link Learn More, url='https://fly.io/docs/speedrun/'
			image
			image
		list
			listitem
				link Phoenix Framework, url='https://fly.io/phoenix/'
					image
			listitem
				link SvelteKit, url='https://fly.io/sveltekit/'
					image
			listitem
				link Ruby on Rails, url='https://fly.io/rails/'
					image
			listitem
				link Docker, url='https://fly.io/docs/getting-started/dockerfile/'
					image
			listitem
				link Go, url='https://fly.io/docs/getting-started/golang/'
					image
			listitem
				link Rust, url='https://fly.io/docs/rust/'
					image
			listitem
				link Django, url='https://fly.io/django/'
					image
			listitem
				link Laravel, url='https://fly.io/laravel/'
					image
			listitem
				link NextJS, url='https://fly.io/nextjs/'
					image
		image, url='https://fly.io/phx/ui/images/better-together-bg-630f84dc36727cb3216fe4536c3687db.png?vsn=d'
		heading Developer-Focused Public Cloud
		paragraph
			StaticText Help us build the next public cloud. No, seriously. Is your product something devs can take advantage of to ship better apps? Work with us.
		link Build A Cloud For Developers, url='https://fly.io/developer-cloud'
			image
			image
	alert, atomic
	alert, atomic
	alert, atomic
	alert, atomic
	alert, atomic
	contentinfo
		link Fly, url='https://fly.io/'
		DescriptionList
			term
				StaticText COMPANY
			definition
				link About, url='https://fly.io/about/'
				link Pricing, url='https://fly.io/pricing/'
				link Jobs, url='https://fly.io/jobs/'
		DescriptionList
			term
				StaticText ARTICLES
			definition
				link Blog, url='https://fly.io/blog/'
				link Phoenix Files, url='https://fly.io/phoenix-files/'
				link Laravel Bytes, url='https://fly.io/laravel-bytes/'
				link Ruby Dispatch, url='https://fly.io/ruby-dispatch/'
				link Django Beats, url='https://fly.io/django-beats/'
				link JavaScript Journal, url='https://fly.io/javascript-journal/'
		DescriptionList
			term
				StaticText RESOURCES
			definition
				link Docs, url='https://fly.io/docs/'
				link Customers, url='https://fly.io/customers'
				link Support, url='https://fly.io/docs/support/'
				link Support Metrics, url='https://fly.io/support/'
				link Status, url='https://status.flyio.net/'
		DescriptionList
			term
				StaticText CONTACT
			definition
				link GitHub, url='https://github.com/superfly/'
				link Twitter, url='https://twitter.com/flydotio'
				link Community, url='https://community.fly.io/'
		DescriptionList
			term
				StaticText LEGAL
			definition
				link Security, url='https://fly.io/security/'
				link Privacy policy, url='https://fly.io/legal/privacy-policy'
				link Terms of service, url='https://fly.io/legal/terms-of-service'
				link Acceptable Use Policy, url='https://fly.io/legal/acceptable-use-policy'
		paragraph
			StaticText Copyright © 2024 Fly.io
```
</details>



```
RootWebArea Deploy app servers close to your users · Fly, focused, url='https://fly.io/'
	banner
		navigation Logo menu
			[38] link The Fly.io logo: a stylized white and purple hot air balloon on a deep purple background, center=(448,48), url='https://fly.io/'
		navigation Main menu
```
<details><summary>Show more</summary>

```
			DescriptionList
				term
					StaticText Articles
				[49] span, center=(730,56)
				definition
					[53] link Blog, center=(730,110), url='https://fly.io/blog/'
					[54] link Phoenix Files, center=(730,152), url='https://fly.io/phoenix-files/'
					[55] link Laravel Bytes, center=(730,193), url='https://fly.io/laravel-bytes/'
					[56] link Ruby Dispatch, center=(730,235), url='https://fly.io/ruby-dispatch/'
					[57] link Django Beats, center=(730,277), url='https://fly.io/django-beats/'
					[58] link JavaScript Journal, center=(730,318), url='https://fly.io/javascript-journal/'
			[59] link Security, center=(808,48), url='https://fly.io/security/'
			[63] link Infra Log, center=(890,48), url='https://fly.io/infra-log/'
			[67] link Docs, center=(960,48), url='https://fly.io/docs/'
			[71] link Community, center=(1039,48), url='https://community.fly.io/'
			[75] link Status, center=(1124,48), url='https://status.flyio.net/'
			[79] link Pricing, center=(1193,48), url='https://fly.io/pricing/'
			[84] link Sign In, center=(1384,48), url='https://fly.io/app/sign-in'
			[88] link Get Started, center=(1473,48), url='https://fly.io/app/sign-up'
	image
	main
		heading A Public Cloud Built For Developers Who Ship
			emphasis
		paragraph
			strong
				StaticText Over 3 million apps
			StaticText have launched on Fly.io, leveraging global Anycast load-balancing, zero-config private networking, hardware isolation, and instant WireGuard VPN connections, with push-button deployments scaling to thousands of instances.
		[124] link Deploy Your App in 5 minutes, center=(960,536), url='https://fly.io/app/sign-up'
			image
			image
		heading Public Cloud Infrastructure. Modern Platform Endorphins.
		paragraph
			StaticText The most flexible and powerful compute platform on any public cloud. Fly Machines are hardware-virtualized containers, running on our own hardware, that launch instantly and run exactly as long as you want them to — for a single HTTP request, or for weeks of uptime.
		image
		image, url='https://fly.io/phx/ui/images/fly-globe-cb332f77ddb429aa3ef4e0a2c6c592ba.png?vsn=d'
		list
			listitem
				image
				heading Get Right in Your Users’ Faces
				paragraph
					StaticText Deploy in 35 regions, from Sydney to São Paulo, for sub-100ms response times and native-app feel no matter where your users are.
			listitem
				image
				heading Fork Off VMs Like They’re Processes
				paragraph
					StaticText Fly Machines start fast enough to handle HTTP requests, run only when you need them, and scale into tens of thousands of instances.
			listitem
				image
				heading Ship GPU-Boosted Models
				paragraph
					StaticText From LLMs to inferencing, hardware acceleration with the same developer experience as a simple CRUD app.
			listitem
				image
				heading Built for Distributed Systems
				paragraph
					StaticText Clustered databases like Cockroach, globally-distributed Postgres, and modern RPC systems like Elixir FLAME, no Terraform required.
		image, url='https://fly.io/phx/ui/images/cool-bird-d997174954ab5a152ccac3d2dcb19c8d.png?vsn=d'
		heading Support By Developers For Developers
		paragraph
			StaticText Paid support packages include a team of actual engineers (not chatbots) who themselves ship code on our platform. Emergency support and guaranteed response times available.
		link Learn More, url='https://fly.io/support'
			image
			image
		heading Enterprise-Ready
		paragraph
			StaticText Apps running on Fly Machines are KVM hardware-isolated, built on a memory-safe stack and running directly on our own metal.
		link Enterprise Features, url='https://fly.io/enterprise'
			image
			image
		link Fly.io Security, url='https://fly.io/security'
			image
			image
		list
			listitem
				StaticText Single Sign-On
			listitem
				StaticText Guaranteed Support Response Times
			listitem
				StaticText SOC2 Type 2 Attested
			listitem
				StaticText Memory-safe Rust and Go stack
			listitem
				StaticText CI/CD Integration
		image, url='https://fly.io/phx/ui/images/js-love-b469706c4be3625b972ee3fdfcb80687.png?vsn=d'
		heading Serverful JavaScript Without the Hassle of Serverless
		paragraph
			StaticText Imagine if a server could boot as fast as a serverless function? That's Fly Machines—serverless compute is a trade-off you no longer need to make. Graduate to a full-stack cloud to regain control over your stack & hosting bill.
		list
			listitem
				image
				heading Boots in 250ms or Less
				paragraph
					StaticText Functions and apps boot and respond to web requests in 250ms or less with Fly Machines. You decide to keep them running or automatically put them to sleep.
			listitem
				image
				heading Built for JavaScript Developers
				paragraph
					StaticText JavaScript, TypeScript, Bun, Deno—whatever your flavor, Fly Launch automatically detects your runtime and generates a VM with everything you need to run your app.
			listitem
				image
				heading Real GPUs & CPUs on the Edge
				paragraph
					StaticText Run workloads that require GPUs or lots of CPUs, memory, and storage in over 30 regions around the world—all interconnected by a private, encrypted WireGuard network that works out of the box.
		heading Use the Tech You Love
		paragraph
			StaticText Build with your favorite framework. No Dockerfile? No problem: our CLI generates containers for most popular frameworks, including Rails, Phoenix, Django, Node, Laravel, and .NET.
		link Learn More, url='https://fly.io/docs/speedrun/'
			image
			image
		list
			listitem
				link Phoenix Framework, url='https://fly.io/phoenix/'
					image
			listitem
				link SvelteKit, url='https://fly.io/sveltekit/'
					image
			listitem
				link Ruby on Rails, url='https://fly.io/rails/'
					image
			listitem
				link Docker, url='https://fly.io/docs/getting-started/dockerfile/'
					image
			listitem
				link Go, url='https://fly.io/docs/getting-started/golang/'
					image
			listitem
				link Rust, url='https://fly.io/docs/rust/'
					image
			listitem
				link Django, url='https://fly.io/django/'
					image
			listitem
				link Laravel, url='https://fly.io/laravel/'
					image
			listitem
				link NextJS, url='https://fly.io/nextjs/'
					image
		image, url='https://fly.io/phx/ui/images/better-together-bg-630f84dc36727cb3216fe4536c3687db.png?vsn=d'
		heading Developer-Focused Public Cloud
		paragraph
			StaticText Help us build the next public cloud. No, seriously. Is your product something devs can take advantage of to ship better apps? Work with us.
		link Build A Cloud For Developers, url='https://fly.io/developer-cloud'
			image
			image
	alert, atomic
	alert, atomic
	alert, atomic
	alert, atomic
	alert, atomic
	contentinfo
		link Fly, url='https://fly.io/'
		DescriptionList
			term
				StaticText COMPANY
			definition
				link About, url='https://fly.io/about/'
				link Pricing, url='https://fly.io/pricing/'
				link Jobs, url='https://fly.io/jobs/'
		DescriptionList
			term
				StaticText ARTICLES
			definition
				link Blog, url='https://fly.io/blog/'
				link Phoenix Files, url='https://fly.io/phoenix-files/'
				link Laravel Bytes, url='https://fly.io/laravel-bytes/'
				link Ruby Dispatch, url='https://fly.io/ruby-dispatch/'
				link Django Beats, url='https://fly.io/django-beats/'
				link JavaScript Journal, url='https://fly.io/javascript-journal/'
		DescriptionList
			term
				StaticText RESOURCES
			definition
				link Docs, url='https://fly.io/docs/'
				link Customers, url='https://fly.io/customers'
				link Support, url='https://fly.io/docs/support/'
				link Support Metrics, url='https://fly.io/support/'
				link Status, url='https://status.flyio.net/'
		DescriptionList
			term
				StaticText CONTACT
			definition
				link GitHub, url='https://github.com/superfly/'
				link Twitter, url='https://twitter.com/flydotio'
				link Community, url='https://community.fly.io/'
		DescriptionList
			term
				StaticText LEGAL
			definition
				link Security, url='https://fly.io/security/'
				link Privacy policy, url='https://fly.io/legal/privacy-policy'
				link Terms of service, url='https://fly.io/legal/terms-of-service'
				link Acceptable Use Policy, url='https://fly.io/legal/acceptable-use-policy'
		paragraph
			StaticText Copyright © 2024 Fly.io
```
</details>

**Reasoning for action:** By clicking the 'Blog' link, I access the dedicated section of the website that contains various articles. This is a necessary step toward finding the specific article mentioned in the user story. Once I'm on the blog page, I can look for the article title specified, which will allow me to proceed toward viewing its full content.

**Action:** click('50') # Click on the Blog link to explore articles.

**Change Description:** After clicking the Blog link, the browser's state reflected that the Blog section was opened, indicated by the updated position of the Blog link within the navigation menu, as well as the addition of a span element indicating the selected state.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://fly.io/

https://fly.io/blog/

**Content (before/after):** 

```
RootWebArea Deploy app servers close to your users · Fly, focused, url='https://fly.io/'
	banner
		navigation Logo menu
			[38] link The Fly.io logo: a stylized white and purple hot air balloon on a deep purple background, center=(448,48), url='https://fly.io/'
		navigation Main menu
```
<details><summary>Show more</summary>

```
			DescriptionList
				term
					StaticText Articles
				[49] span, center=(730,56)
				definition
					[53] link Blog, center=(730,110), url='https://fly.io/blog/'
					[54] link Phoenix Files, center=(730,152), url='https://fly.io/phoenix-files/'
					[55] link Laravel Bytes, center=(730,193), url='https://fly.io/laravel-bytes/'
					[56] link Ruby Dispatch, center=(730,235), url='https://fly.io/ruby-dispatch/'
					[57] link Django Beats, center=(730,277), url='https://fly.io/django-beats/'
					[58] link JavaScript Journal, center=(730,318), url='https://fly.io/javascript-journal/'
			[59] link Security, center=(808,48), url='https://fly.io/security/'
			[63] link Infra Log, center=(890,48), url='https://fly.io/infra-log/'
			[67] link Docs, center=(960,48), url='https://fly.io/docs/'
			[71] link Community, center=(1039,48), url='https://community.fly.io/'
			[75] link Status, center=(1124,48), url='https://status.flyio.net/'
			[79] link Pricing, center=(1193,48), url='https://fly.io/pricing/'
			[84] link Sign In, center=(1384,48), url='https://fly.io/app/sign-in'
			[88] link Get Started, center=(1473,48), url='https://fly.io/app/sign-up'
	image
	main
		heading A Public Cloud Built For Developers Who Ship
			emphasis
		paragraph
			strong
				StaticText Over 3 million apps
			StaticText have launched on Fly.io, leveraging global Anycast load-balancing, zero-config private networking, hardware isolation, and instant WireGuard VPN connections, with push-button deployments scaling to thousands of instances.
		[124] link Deploy Your App in 5 minutes, center=(960,536), url='https://fly.io/app/sign-up'
			image
			image
		heading Public Cloud Infrastructure. Modern Platform Endorphins.
		paragraph
			StaticText The most flexible and powerful compute platform on any public cloud. Fly Machines are hardware-virtualized containers, running on our own hardware, that launch instantly and run exactly as long as you want them to — for a single HTTP request, or for weeks of uptime.
		image
		image, url='https://fly.io/phx/ui/images/fly-globe-cb332f77ddb429aa3ef4e0a2c6c592ba.png?vsn=d'
		list
			listitem
				image
				heading Get Right in Your Users’ Faces
				paragraph
					StaticText Deploy in 35 regions, from Sydney to São Paulo, for sub-100ms response times and native-app feel no matter where your users are.
			listitem
				image
				heading Fork Off VMs Like They’re Processes
				paragraph
					StaticText Fly Machines start fast enough to handle HTTP requests, run only when you need them, and scale into tens of thousands of instances.
			listitem
				image
				heading Ship GPU-Boosted Models
				paragraph
					StaticText From LLMs to inferencing, hardware acceleration with the same developer experience as a simple CRUD app.
			listitem
				image
				heading Built for Distributed Systems
				paragraph
					StaticText Clustered databases like Cockroach, globally-distributed Postgres, and modern RPC systems like Elixir FLAME, no Terraform required.
		image, url='https://fly.io/phx/ui/images/cool-bird-d997174954ab5a152ccac3d2dcb19c8d.png?vsn=d'
		heading Support By Developers For Developers
		paragraph
			StaticText Paid support packages include a team of actual engineers (not chatbots) who themselves ship code on our platform. Emergency support and guaranteed response times available.
		link Learn More, url='https://fly.io/support'
			image
			image
		heading Enterprise-Ready
		paragraph
			StaticText Apps running on Fly Machines are KVM hardware-isolated, built on a memory-safe stack and running directly on our own metal.
		link Enterprise Features, url='https://fly.io/enterprise'
			image
			image
		link Fly.io Security, url='https://fly.io/security'
			image
			image
		list
			listitem
				StaticText Single Sign-On
			listitem
				StaticText Guaranteed Support Response Times
			listitem
				StaticText SOC2 Type 2 Attested
			listitem
				StaticText Memory-safe Rust and Go stack
			listitem
				StaticText CI/CD Integration
		image, url='https://fly.io/phx/ui/images/js-love-b469706c4be3625b972ee3fdfcb80687.png?vsn=d'
		heading Serverful JavaScript Without the Hassle of Serverless
		paragraph
			StaticText Imagine if a server could boot as fast as a serverless function? That's Fly Machines—serverless compute is a trade-off you no longer need to make. Graduate to a full-stack cloud to regain control over your stack & hosting bill.
		list
			listitem
				image
				heading Boots in 250ms or Less
				paragraph
					StaticText Functions and apps boot and respond to web requests in 250ms or less with Fly Machines. You decide to keep them running or automatically put them to sleep.
			listitem
				image
				heading Built for JavaScript Developers
				paragraph
					StaticText JavaScript, TypeScript, Bun, Deno—whatever your flavor, Fly Launch automatically detects your runtime and generates a VM with everything you need to run your app.
			listitem
				image
				heading Real GPUs & CPUs on the Edge
				paragraph
					StaticText Run workloads that require GPUs or lots of CPUs, memory, and storage in over 30 regions around the world—all interconnected by a private, encrypted WireGuard network that works out of the box.
		heading Use the Tech You Love
		paragraph
			StaticText Build with your favorite framework. No Dockerfile? No problem: our CLI generates containers for most popular frameworks, including Rails, Phoenix, Django, Node, Laravel, and .NET.
		link Learn More, url='https://fly.io/docs/speedrun/'
			image
			image
		list
			listitem
				link Phoenix Framework, url='https://fly.io/phoenix/'
					image
			listitem
				link SvelteKit, url='https://fly.io/sveltekit/'
					image
			listitem
				link Ruby on Rails, url='https://fly.io/rails/'
					image
			listitem
				link Docker, url='https://fly.io/docs/getting-started/dockerfile/'
					image
			listitem
				link Go, url='https://fly.io/docs/getting-started/golang/'
					image
			listitem
				link Rust, url='https://fly.io/docs/rust/'
					image
			listitem
				link Django, url='https://fly.io/django/'
					image
			listitem
				link Laravel, url='https://fly.io/laravel/'
					image
			listitem
				link NextJS, url='https://fly.io/nextjs/'
					image
		image, url='https://fly.io/phx/ui/images/better-together-bg-630f84dc36727cb3216fe4536c3687db.png?vsn=d'
		heading Developer-Focused Public Cloud
		paragraph
			StaticText Help us build the next public cloud. No, seriously. Is your product something devs can take advantage of to ship better apps? Work with us.
		link Build A Cloud For Developers, url='https://fly.io/developer-cloud'
			image
			image
	alert, atomic
	alert, atomic
	alert, atomic
	alert, atomic
	alert, atomic
	contentinfo
		link Fly, url='https://fly.io/'
		DescriptionList
			term
				StaticText COMPANY
			definition
				link About, url='https://fly.io/about/'
				link Pricing, url='https://fly.io/pricing/'
				link Jobs, url='https://fly.io/jobs/'
		DescriptionList
			term
				StaticText ARTICLES
			definition
				link Blog, url='https://fly.io/blog/'
				link Phoenix Files, url='https://fly.io/phoenix-files/'
				link Laravel Bytes, url='https://fly.io/laravel-bytes/'
				link Ruby Dispatch, url='https://fly.io/ruby-dispatch/'
				link Django Beats, url='https://fly.io/django-beats/'
				link JavaScript Journal, url='https://fly.io/javascript-journal/'
		DescriptionList
			term
				StaticText RESOURCES
			definition
				link Docs, url='https://fly.io/docs/'
				link Customers, url='https://fly.io/customers'
				link Support, url='https://fly.io/docs/support/'
				link Support Metrics, url='https://fly.io/support/'
				link Status, url='https://status.flyio.net/'
		DescriptionList
			term
				StaticText CONTACT
			definition
				link GitHub, url='https://github.com/superfly/'
				link Twitter, url='https://twitter.com/flydotio'
				link Community, url='https://community.fly.io/'
		DescriptionList
			term
				StaticText LEGAL
			definition
				link Security, url='https://fly.io/security/'
				link Privacy policy, url='https://fly.io/legal/privacy-policy'
				link Terms of service, url='https://fly.io/legal/terms-of-service'
				link Acceptable Use Policy, url='https://fly.io/legal/acceptable-use-policy'
		paragraph
			StaticText Copyright © 2024 Fly.io
```
</details>



```
RootWebArea The Fly Blog, focused, url='https://fly.io/blog/'
	banner
		navigation Logo menu
			[50] link Fly App performance optimization, center=(312,48), url='https://fly.io/'
				image Fly App performance optimization
```
<details><summary>Show more</summary>

```
			[53] link Blog, center=(356,48), url='https://fly.io/blog/'
				image Blog
		[57] link Need a Logo? View Our Brand Assets, center=(388,112), inner_text=Need a Logo?
View Our Brand Assets, url='https://fly.io/docs/about/brand/'
			strong
			image
		navigation Main menu
			DescriptionList
				[69] term, center=(730,48), inner_text=Articles
					StaticText Articles
				definition
					link Blog, url='https://fly.io/blog/'
					link Phoenix Files, url='https://fly.io/phoenix-files/'
					link Laravel Bytes, url='https://fly.io/laravel-bytes/'
					link Ruby Dispatch, url='https://fly.io/ruby-dispatch/'
					link Django Beats, url='https://fly.io/django-beats/'
					link JavaScript Journal, url='https://fly.io/javascript-journal/'
			[78] link Security, center=(808,48), url='https://fly.io/security/'
			[79] link Infra Log, center=(890,48), url='https://fly.io/infra-log/'
			[80] link Docs, center=(960,48), url='https://fly.io/docs/'
			[81] link Community, center=(1039,48), url='https://community.fly.io/'
			[82] link Status, center=(1124,48), url='https://status.flyio.net/'
			[83] link Pricing, center=(1193,48), url='https://fly.io/pricing/'
			[85] link Sign In, center=(1435,48), url='https://fly.io/app/sign-in'
			[86] link Get Started, center=(1536,48), url='https://fly.io/docs/hands-on/start/'
			[87] link RSS Feed, center=(1619,48), url='https://fly.io/blog/feed.xml'
				image
	main
		image, url='https://fly.io/static/images/blog-cover.webp'
		article
			StaticText BY CHRIS MCCORD & JOSÉ VALIM
			StaticText 8 MIN READ
			heading AI GPU Clusters, From Your Laptop, With Livebook
			paragraph
				StaticText Let’s begin by introducing our cast of characters. Livebook is usually described as Elixir’s answer to Jupyter Notebooks. And that’s a good way to think about it. But Livebook takes full advantage of the Elixir platform, which makes it sneakily powe
			paragraph
				StaticText Read more
				StaticText →
			[128] link Read more, center=(960,373), url='https://fly.io/blog/ai-gpu-clusters-from-your-laptop-livebook/'
			image, url='https://fly.io/blog/ai-gpu-clusters-from-your-laptop-livebook/assets/ai-gpu-livebook-cover.webp'
		article
			image, url='https://fly.io/blog/accident-forgiveness/assets/money-for-mistakes-blog-thumb.webp'
			StaticText BY THOMAS PTACEK
			StaticText 8 MIN READ
			heading Accident Forgiveness
			paragraph
				StaticText Public cloud billing is terrifying. The premise of a public cloud — what sets it apart from a hosting provider — is 8,760 hours/year of on-tap deployable compute, storage, and networking. Cloud resources are “elastic”: they’re acquired and released
			[143] link Read more, center=(508,945), url='https://fly.io/blog/accident-forgiveness/'
		article
			image, url='https://fly.io/blog/cutting-prices-for-l40s-gpus-in-half/assets/gpu-ga-thumb.webp'
			StaticText BY KURT MACKEY
			StaticText 6 MIN READ
			heading We're Cutting L40S Prices In Half
			paragraph
				StaticText We just lowered the prices on NVIDIA L40s GPUs to $1.25 per hour. Why? Because our feet are cold and we burn processor cycles for heat. But also other reasons. Let’s back up. We offer 4 different NVIDIA GPU models; in increasing order of performanc
			[155] link Read more, center=(960,945), url='https://fly.io/blog/cutting-prices-for-l40s-gpus-in-half/'
		article
			image, url='https://fly.io/blog/machine-migrations/assets/migrations-thumb.webp'
			StaticText BY THOMAS PTACEK
			StaticText 18 MIN READ
			heading Making Machines Move
			paragraph
				StaticText At the heart of our platform is a systems design tradeoff about durable storage for applications. When we added storage three years ago, to support stateful apps, we built it on attached NVMe drives. A benefit: a Fly App accessing a file on a Fly Vo
			[167] link Read more, center=(1412,945), url='https://fly.io/blog/machine-migrations/'
		article
			image, url='https://fly.io/blog/oidc-cloud-roles/assets/spooky-security-skeleton-thumb.webp'
			StaticText BY MOSS LILLEY
			StaticText 10 MIN READ
			heading AWS without Access Keys
			paragraph
				StaticText Let’s hypopulate you an app serving generative AI cat images based on the weather forecast, running on a g4dn.xlarge ECS task in AWS us-east-1. It’s going great; people didn’t realize how dependent their cat pic prefs are on barometric pressure, and
			link Read more, url='https://fly.io/blog/oidc-cloud-roles/'
		article
			image, url='https://fly.io/blog/llm-image-description/assets/image-description-thumb.webp'
			StaticText BY NOLAN DARILEK
			StaticText 14 MIN READ
			heading Picture This: Open Source AI for Image Description
			paragraph
				StaticText Picture this, if you will. You’re blind. You’re in an unfamiliar hotel room on a trip to Chicago. If you live in Chicago IRL, imagine the hotel in Winnipeg, the Chicago of the North. You’ve absent-mindedly set your coffee down, and can’t remember w
			link Read more, url='https://fly.io/blog/llm-image-description/'
		article
			image, url='https://fly.io/blog/jit-wireguard-peers/assets/network-thumbnail.webp'
			StaticText BY LILLIAN BERRY
			StaticText 10 MIN READ
			heading JIT WireGuard
			paragraph
				StaticText One of many odd decisions we’ve made at Fly.io is how we use WireGuard. It’s not just that we use it in many places where other shops would use HTTPS and REST APIs. We’ve gone a step beyond that: every time you run flyctl, our lovable, sprawling CLI,
			link Read more, url='https://fly.io/blog/jit-wireguard-peers/'
		article
			image, url='https://fly.io/blog/fks-beta-live/assets/fks-thumb.webp'
			StaticText BY SENYO SIMPSON & JP PHILLIPS
			StaticText 8 MIN READ
			heading Fly Kubernetes does more now
			paragraph
				StaticText Fly Kubernetes is the “blessed path"™️ to using Kubernetes backed by Fly.io infrastructure. Or, in simpler terms, it is our managed Kubernetes service. We take care of the complexity of operating the Kubernetes control plane, leaving you with the unf
			link Read more, url='https://fly.io/blog/fks-beta-live/'
		article
			image, url='https://fly.io/blog/tigris-public-beta/assets/tigris-public-beta-thumb.webp'
			StaticText BY XE IASO
			StaticText 9 MIN READ
			heading Globally Distributed Object Storage with Tigris
			paragraph
				StaticText There are three hard things in computer science: Cache invalidation Naming things Doing a better job than Amazon of storing files Of all the annoying software problems that have no business being annoying, handling a file upload in a full-stack a
			link Read more, url='https://fly.io/blog/tigris-public-beta/'
		article
			image, url='https://fly.io/blog/gpu-ga/assets/gpu-ga-thumb.webp'
			StaticText BY XE IASO
			StaticText 2 MIN READ
			heading GPUs on Fly.io are available to everyone!
			paragraph
				StaticText GPUs are now available to everyone! We know you’ve been excited about wanting to use GPUs on Fly.io and we’re happy to announce that they’re available for everyone. If you want, you can spin up GPU instances with any of the following cards: Ampere
			link Read more, url='https://fly.io/blog/gpu-ga/'
		article
			image, url='https://fly.io/blog/event-driven-machines/assets/lambdo-thumb.webp'
			StaticText BY CHRIS FIDAO
			StaticText 6 MIN READ
			heading Event Driven Machines
			paragraph
				StaticText Serverless is great because is has good ergonomics - when an event is received, a “not-server” boots quickly, code is run, and then everything is torn down. We’re billed only on usage. It turns out that Fly.io shares many of the same ergonomics as s
			link Read more, url='https://fly.io/blog/event-driven-machines/'
		article
			image, url='https://fly.io/blog/delegate-tasks-to-fly-machines/assets/delegate-tasks-to-fly-machines-thumb.webp'
			StaticText BY ANNIE SEXTON
			StaticText 12 MIN READ
			heading Delegating tasks to Fly Machines
			paragraph
				StaticText There are many ways to delegate work in web applications, from using background workers to serverless architecture. In this article, we explore a new machine pattern that takes advantage of Fly Machines and distinct process groups to make quick work
			link Read more, url='https://fly.io/blog/delegate-tasks-to-fly-machines/'
		article
			image, url='https://fly.io/blog/macaroons-escalated-quickly/assets/evil-cookies-thumb.webp'
			StaticText BY THOMAS PTACEK
			StaticText 22 MIN READ
			heading Macaroons Escalated Quickly
			paragraph
				StaticText 1 Let’s implement an API token together. It’s a design called “Macaroons”, but don’t get hung up on that yet. First some throat-clearing. Then: Wrap text Copy to clipboard import sys impor
			link Read more, url='https://fly.io/blog/macaroons-escalated-quickly/'
		article
			image, url='https://fly.io/blog/how-i-fly-yoko-li/assets/chat-bird-cover-thumb.webp'
			StaticText BY XE IASO
			StaticText 12 MIN READ
			heading How Yoko Li makes towns, tamagoes, and tools for local AI
			paragraph
				StaticText Hello all, and welcome to another episode of How I Fly, a series where I interview developers about what they do with technology, what they find exciting, and the unexpected things they’ve learned along the way. This time I’m talking with Yoko Li, an
			link Read more, url='https://fly.io/blog/how-i-fly-yoko-li/'
		article
			image, url='https://fly.io/blog/not-midjourney-bot/assets/purple-balloon-taking-off-thumb.webp'
			StaticText BY KYLE MCLAREN
			StaticText 15 MIN READ
			heading Deploy Your Own (Not) Midjourney Bot on Fly GPUs
			paragraph
				StaticText Some people daydream about normal things, like coffee machines or raising that Series A round (those are normal things to dream about, right?). I daydream about commanding a fleet of chonky NVIDIA Lovelace L40Ss. Also, totally normal. Well, fortunate
			link Read more, url='https://fly.io/blog/not-midjourney-bot/'
		article
			image, url='https://fly.io/blog/fly-with-alpine/assets/fly-with-alpine-thumb.webp'
			StaticText BY SAM RUBY
			StaticText 6 MIN READ
			heading Fly With Alpine
			paragraph
				StaticText Before proceeding, a caution. This is an engineering trade-off. Test carefully before deploying to production. By the end of this blog post you should have the information you need to make an informed decision. Introduction Alpine Linux is a Linux
			link Read more, url='https://fly.io/blog/fly-with-alpine/'
		article
			image, url='https://fly.io/blog/fks/assets/fks-thumb.webp'
			StaticText BY SENYO SIMPSON
			StaticText 10 MIN READ
			heading Introducing Fly Kubernetes
			paragraph
				StaticText Update, March 2024: FKS does more stuff now, and you can read about it in Fly Kubernetes does more now We’ll own it: we’ve been snarky about Kubernetes. We are, at heart, old-school Unix nerds. We’re still scandalized by systemd. To make matters mor
			link Read more, url='https://fly.io/blog/fks/'
		article
			image, url='https://fly.io/blog/fly-io-has-gpus-now/assets/llama-portal-thumb.webp'
			StaticText BY XE IASO
			StaticText 7 MIN READ
			heading Fly.io has GPUs now
			paragraph
				StaticText AI is pretty fly AI is apparently a bit of a thing (maybe even an thing come to think about it). We’ve seen entire industries get transformed in the wake of ChatGPT existing (somehow it’s only been around for a year, I can’t believe it either). It’s l
			link Read more, url='https://fly.io/blog/fly-io-has-gpus-now/'
		article
			image, url='https://fly.io/blog/what-are-these-gpus-really/assets/gpu-songstress-thumb.webp'
			StaticText BY XE IASO
			StaticText 14 MIN READ
			heading What are these "GPUs" really?
			paragraph
				StaticText GPU hardware will let our users run all sorts of fun Artificial Intelligence and Machine Learning (AI/ML) workloads near their users. But, what are these “GPUs” really? What can they do? What can’t they do? Listen here for my tale of woe as I spell
			link Read more, url='https://fly.io/blog/what-are-these-gpus-really/'
		article
			image, url='https://fly.io/blog/scaling-llm-ollama/assets/thumb.webp'
			StaticText BY XE IASO
			StaticText 12 MIN READ
			heading Scaling Large Language Models to zero with Ollama
			paragraph
				StaticText Open-source self-hosted AI tools have advanced a lot in the past 6 months. They allow you to create new methods of expression (with QR code generation and Stable Diffusion), easy access to summarization powers that would have made Google blush a deca
			link Read more, url='https://fly.io/blog/scaling-llm-ollama/'
		article
			image, url='https://fly.io/blog/rethinking-serverless-with-flame/assets/flame-thumb.webp'
			StaticText BY CHRIS MCCORD
			StaticText 19 MIN READ
			heading Rethinking Serverless with FLAME
			paragraph
				StaticText Imagine if you could auto scale simply by wrapping any existing app code in a function and have that block of code run in a temporary copy of your app. The pursuit of elastic, auto-scaling applications has taken us to silly places. Serverless/FaaS
			link Read more, url='https://fly.io/blog/rethinking-serverless-with-flame/'
		article
			image, url='https://fly.io/blog/the-risks-of-building-apps-on-chatgpt/assets/risks-building-on-chatgpt-thumb.webp'
			StaticText BY MARK ERICKSEN
			StaticText 15 MIN READ
			heading The risks of building apps on ChatGPT
			paragraph
				StaticText The topic of “AI” gets a lot of attention and press. Coverage ranges from apocalyptic warnings to Utopian predictions. The truth, as always, is likely somewhere in the middle. As developers, we are the ones that either imagine ways that AI can be use
			link Read more, url='https://fly.io/blog/the-risks-of-building-apps-on-chatgpt/'
		article
			image, url='https://fly.io/blog/print-on-demand/assets/print-on-demand-thumb.webp'
			StaticText BY SAM RUBY
			StaticText 6 MIN READ
			heading Print on Demand
			paragraph
				StaticText Scaling discussions often lead to recommendations to add more memory, more CPU, more machines, more regions, more, more, more. This post is different. It focuses instead on the idea of decomposing parts of your applications into event handlers, sta
			link Read more, url='https://fly.io/blog/print-on-demand/'
		article
			image, url='https://fly.io/blog/new-launch/assets/thumb.webp'
			StaticText BY XE IASO
			StaticText 2 MIN READ
			heading Launching to Victory
			paragraph
				StaticText Previously when you ran fly launch, you got asked a bunch of hopefully relevant questions to help you get your app up and running. We’ve taken a lot of the guesswork out of the process and made it a lot more streamlined. It turns out that even though
			link Read more, url='https://fly.io/blog/new-launch/'
		article
			image, url='https://fly.io/blog/how-i-fly/assets/thumb.webp'
			StaticText BY XE IASO
			StaticText 6 MIN READ
			heading How I Fly
			paragraph
				StaticText I’m Xe Iaso. I’m a writer, technical educator, and philosopher who focuses on making technology easy to understand and scale to your needs. I use Fly.io to host my website and in nearly all of my personal projects now. Fly.io allows me to experiment
			link Read more, url='https://fly.io/blog/how-i-fly/'
		article
			image, url='https://fly.io/blog/transcribing-on-fly-gpu-machines/assets/whispering-thumb.webp'
			StaticText BY CHRIS FIDAO
			StaticText 9 MIN READ
			heading Transcribing on Fly GPU Machines
			paragraph
				StaticText Fly.io has GPU Machines, which means we can finally run AI workloads with just a few API calls. This is exciting!
			link Read more, url='https://fly.io/blog/transcribing-on-fly-gpu-machines/'
		article
			image, url='https://fly.io/blog/skip-the-api/assets/skip-the-api-thumb.webp'
			StaticText BY BEN JOHNSON
			StaticText 6 MIN READ
			heading Skip the API, Ship Your Database
			paragraph
				StaticText My favorite part about building tools is discovering their unintended uses. It’s like starting to write a murder mystery book but you have no idea who the killer is! History is filled with examples of these accidental discoveries: WD-40 was original
			link Read more, url='https://fly.io/blog/skip-the-api/'
		article
			image, url='https://fly.io/blog/sentry-partnership/assets/sentry-thumb.webp'
			StaticText BY JOSHUA SIERLES
			StaticText 3 MIN READ
			heading Automated Sentry Error Tracking
			paragraph
				StaticText We’ve been using Sentry since the dawn of the internet. Or at least as far back as the discovery of the Higgs boson. Project to project, the familiar Sentry issue detail screen has been our faithful debugging companion. Today it’s no exception: All
			link Read more, url='https://fly.io/blog/sentry-partnership/'
		article
			image, url='https://fly.io/blog/tracking-consistency-with-litefs/assets/tracking-consistency-thumb.webp'
			StaticText BY BEN JOHNSON
			StaticText 8 MIN READ
			heading Tracking Application-Level Consistency with LiteFS
			paragraph
				StaticText When we started the LiteFS project a year ago, we started more with an ideal in mind rather than a specific implementation. We wanted to make it possible to not only run distributed SQLite but we also wanted to make it… gasp… easy! There were hurdle
			link Read more, url='https://fly.io/blog/tracking-consistency-with-litefs/'
		article
			image, url='https://fly.io/blog/redundant-logs/assets/lergs-thumb.webp'
			StaticText BY SAM RUBY
			StaticText 5 MIN READ
			heading Multiple Logs for Resiliency
			paragraph
				StaticText You’ve done everything right. You are well aware of Murphy’s Law. You have multiple redundant machines. You’ve set up a regular back up schedule for your database, perhaps even are using LiteFS CLoud. You ship your logs to LogTail or perhaps some o
			link Read more, url='https://fly.io/blog/redundant-logs/'
		article
			image, url='https://fly.io/blog/tokenized-tokens/assets/ghosts.png'
			StaticText BY BEN TOEWS
			StaticText 10 MIN READ
			heading Tokenized Tokens
			paragraph
				StaticText We built some little security thingies. We’re open sourcing them, and hoping you like them as much as we do. In a nutshell: it’s a proxy that injects secrets into arbitrary 3rd-party API calls. We could describe it more completely here, but that woul
			link Read more, url='https://fly.io/blog/tokenized-tokens/'
		article
			image, url='https://fly.io/blog/flydotio-heart-bun/assets/flydotio-heart-bun-thumb.webp'
			StaticText BY SAM RUBY
			StaticText 2 MIN READ
			heading Fly.io ❤️ Bun
			paragraph
				StaticText Bun 1.0 comes out September 7th. Fly.io is making preparations. Previously, we stated that Fly.io ❤️ JS, and we understandably started with Node.js. While that work is ongoing, it makes sense to start expanding to other runtimes. Bun is the obvio
			link Read more, url='https://fly.io/blog/flydotio-heart-bun/'
		article
			image, url='https://fly.io/blog/litefs-cloud/assets/litefs-cloud-thumb.webp'
			StaticText BY DARLA MAGDALENE SHOCKLEY & BEN JOHNSON
			StaticText 9 MIN READ
			heading LiteFS Cloud: Distributed SQLite with Managed Backups
			paragraph
				StaticText We love SQLite in production, and we’re all about running apps close to users. That’s why we created LiteFS: an open source distributed SQLite database that lives on the same filesystem as your application, and replicates data to all the nodes in you
			link Read more, url='https://fly.io/blog/litefs-cloud/'
		article
			image, url='https://fly.io/blog/we-raised-a-bunch-of-money/assets/fundraising-thumbnail.png'
			StaticText BY KURT MACKEY
			StaticText 6 MIN READ
			heading We Raised A Bunch Of Money
			paragraph
				StaticText This past July, we raised $25MM from A16Z and our existing investors, including Intel Capital and Dell. Recently, we raised an additional $70MM led by EQT Ventures. Why do startups write announcements like these? We went back and forth on it. There a
			link Read more, url='https://fly.io/blog/we-raised-a-bunch-of-money/'
		article
			image, url='https://fly.io/blog/python-async-workers-on-fly-machines/assets/python-async-workers-on-fly-machines-thumbnail.webp'
			StaticText BY DARLA MAGDALENE SHOCKLEY
			StaticText 10 MIN READ
			heading Python Async Workers on Fly Machines
			paragraph
				StaticText Last year, while working in what was my day job at the time (before I joined Fly.io!), we had just developed a new internal tool to help an adjacent team with their work. This adjacent team wrote technical content, and they had a lot of issues stemmi
			link Read more, url='https://fly.io/blog/python-async-workers-on-fly-machines/'
		article
			image, url='https://fly.io/blog/vanilla-candy-sprinkles/assets/vanilla-candy-sprinkles-thumb.webp'
			StaticText BY SAM RUBY
			StaticText 11 MIN READ
			heading Vanilla with Candy Sprinkles
			paragraph
				StaticText Recapping where we are to date: There are plenty of JavaScript frameworks to choose from, and fly.io loves them all. Pretty much all of the big name frameworks are delightfully weird. Picking up where we left off, this blog post will describe lite
			link Read more, url='https://fly.io/blog/vanilla-candy-sprinkles/'
		article
			image, url='https://fly.io/blog/how-to-fly-replay/assets/replay-router-thumb.webp'
			StaticText BY CHRIS FIDAO
			StaticText 7 MIN READ
			heading Playing Traffic Cop with Fly-Replay
			paragraph
				StaticText The Fly Replay header is deceptively simple. All your app has to do is respond with a header, and the HTTP request gets re-ran somewhere else. It’s behind-the-scenes of some pretty interesting apps on Fly.io (we wrote about using it with Globally Di
			link Read more, url='https://fly.io/blog/how-to-fly-replay/'
		article
			image, url='https://fly.io/blog/js-ecosystem-delightfully-wierd/assets/js-weird-cover.webp'
			StaticText BY SAM RUBY
			StaticText 7 MIN READ
			heading The JavaScript Ecosystem is Delightfully Weird
			paragraph
				StaticText Note, I’m not saying that JavaScript is weird, though it definitely is weird. But that’s not the point of this blog post. Bear with me, instead of starting with how JavaScript ecosystem is weird, I’m going to start with why the JavaScript ecosystem
			link Read more, url='https://fly.io/blog/js-ecosystem-delightfully-wierd/'
		article
			image, url='https://fly.io/blog/deploying-langchain-to-fly-io/assets/deploying-langchain-to-fly-io-thumbnail.webp'
			StaticText BY KÁTIA NAKAMURA
			StaticText 14 MIN READ
			heading Deploying LangChain to Fly.io
			paragraph
				StaticText I hear about Large Language Models (LLM) everywhere these days! Do you? 🤔 LLMs are a type of natural language processing (NLP) technology that uses advanced deep learning techniques to generate human-like language. If you haven’t heard about LLMs, y
			link Read more, url='https://fly.io/blog/deploying-langchain-to-fly-io/'
		article
			image, url='https://fly.io/blog/flydotio-heart-js/assets/flydotio-heart-js-thumb.webp'
			StaticText BY SAM RUBY
			StaticText 6 MIN READ
			heading Fly.io ❤️ JS
			paragraph
				StaticText Fly.io is a great place to run fullstack applications. For most programming languages, there is a defacto default fullstack framework. For Ruby, there is Rails. For Elixir, there is Phoenix. For PHP there is Laravel. For Python, there is Django.
			link Read more, url='https://fly.io/blog/flydotio-heart-js/'
		article
			image, url='https://fly.io/blog/gossip-glomers/assets/gossip-glomers-thumbnail.webp'
			StaticText BY BEN JOHNSON
			StaticText 5 MIN READ
			heading Gossip Glomers
			paragraph
				StaticText In the field of computer science, the industry is represented by two separate yet equally important groups: the software developers who build Rails applications and mobile games, and the academics who write theory papers about why the problems those
			link Read more, url='https://fly.io/blog/gossip-glomers/'
		article
			image, url='https://fly.io/blog/shipping-logs/assets/slinging-logs-in-nats-thumbnail.webp'
			StaticText BY CHRIS FIDAO
			StaticText 5 MIN READ
			heading Shipping Logs
			paragraph
				StaticText Nearly all of our apps are puking output. Sometimes, it’s intentional. Often this output is in the form of structured logs. Logs are helpful for a variety of use cases - debugging, tracking, collating, correlating, coalescing, and condensing the ha
			link Read more, url='https://fly.io/blog/shipping-logs/'
		article
			image, url='https://fly.io/blog/carving-the-scheduler-out-of-our-orchestrator/assets/starry-containers-thumbnail.webp'
			StaticText BY THOMAS PTACEK
			StaticText 26 MIN READ
			heading Carving The Scheduler Out Of Our Orchestrator
			paragraph
				StaticText So, you want to build an app to rate sandwiches. Well, the world has a lot of different sandwiches. Pit beefs in Baltimore, Tonkatsu sandos in Shinjuku, and Cemitas in Puebla. You want real-time sandwich telemetry, no matter the longitude of the sand
			link Read more, url='https://fly.io/blog/carving-the-scheduler-out-of-our-orchestrator/'
		article
			image, url='https://fly.io/blog/fly-in-johannesburg/assets/jnb-kota-thumbnail.webp'
			StaticText BY CHRIS NICOLL
			StaticText <1 MIN READ
			heading Fly.io is in Johannesburg
			paragraph
				StaticText Did you know that we’re in Johannesburg? There’s rugby and cricket. Hearty kota and Gatsby sandwiches. Braii under sunny skies and low-latency full-stack apps. Front end, Postgres, Redis, the works: if your users support the Springboks and Banyana Ba
			link Read more, url='https://fly.io/blog/fly-in-johannesburg/'
		article
			image, url='https://fly.io/blog/wal-mode-in-litefs/assets/wal-mode-thumbnail.webp'
			StaticText BY BEN JOHNSON
			StaticText 11 MIN READ
			heading WAL Mode in LiteFS
			paragraph
				StaticText By and large, SQLite is configuration-free. You can get pretty far by just using the default settings. As your application grows and you start tweaking settings, one of the first knobs you’ll come across is the journal mode. This setting determines h
			link Read more, url='https://fly.io/blog/wal-mode-in-litefs/'
		article
			image, url='https://fly.io/blog/launching-redis-by-upstash/assets/love-thumbnail.webp'
			StaticText BY JOSHUA SIERLES
			StaticText 11 MIN READ
			heading Launching Redis by Upstash
			paragraph
				StaticText We love databases that scale globally. As an ambivalent database provider, we built a global, automated Postgres, and we tinkered with global Redis on scrappy startup weekends. But the Fly.io forecast called for integration over invention. So we part
			link Read more, url='https://fly.io/blog/launching-redis-by-upstash/'
		article
			image, url='https://fly.io/blog/logbook-november-14-to-december-5-2022/assets/logbook-default2-thumbnail.webp'
			StaticText BY BRAD GESSLER
			StaticText 2 MIN READ
			heading Logbook: November 14 to December 5, 2022
			paragraph
				StaticText Build real-time applications on any backend with Replicache and Fly, run Cron on Fly, two LiveWire how-tos, and learn how Fly reluctantly built its Postgres database service. Ok, it’s been longer than a week since the last update because a lot of us
			link Read more, url='https://fly.io/blog/logbook-november-14-to-december-5-2022/'
		article
			image, url='https://fly.io/blog/how-we-built-fly-postgres/assets/keepers-proxies-thumbnail.webp'
			StaticText BY CHRIS NICOLL & SHAUN DAVIS
			StaticText 18 MIN READ
			heading How We Built Fly Postgres
			paragraph
				StaticText Fly.io is an ambivalent database provider—one might even use the word “reluctant”. The reasons for that are interesting, as is the way Fly Postgres works. When we relate this in conversations online, people are often surprised. So we thought we’d tak
			link Read more, url='https://fly.io/blog/how-we-built-fly-postgres/'
		article
			image, url='https://fly.io/blog/replicache-machines-demo/assets/network-thumbnail.webp'
			StaticText BY DOV ALPERIN
			StaticText 8 MIN READ
			heading Real-Time Collaboration with Replicache and Fly-Replay
			paragraph
				StaticText Imagine this: you have invented the best design tool since Figma. But before you can compete with the design-industry heavyweight, you need to be able to compete on one of Figma’s main propositions: real-time collaboration. You do some research and f
			link Read more, url='https://fly.io/blog/replicache-machines-demo/'
		article
			image, url='https://fly.io/blog/logbook-november-7-to-november-14-2022/assets/logbook-thumbnail.webp'
			StaticText BY BRAD GESSLER
			StaticText 2 MIN READ
			heading Logbook: November 7 to November 14, 2022
			paragraph
				StaticText Automatically deploy Elixir apps to production with Github Actions CI and troubleshoot performance issues with OpenTelemetry. Help the Python community draft Django docs. Deploy S3-compatible object storage close to your Fly apps. Last week we got im
			link Read more, url='https://fly.io/blog/logbook-november-7-to-november-14-2022/'
		article
			image, url='https://fly.io/blog/logbook-october-29-to-november-6-2022/assets/logbook-default3-thumbnail.webp'
			StaticText BY BRAD GESSLER
			StaticText 2 MIN READ
			heading Logbook: October 29 to November 6, 2022
			paragraph
				StaticText This week Redis gets some power-ups, Elixir confesses its love for React, Fly gets real about Postgres, Livewire gifts us with a few tutorials, and a many of us in North America didn’t have to change the clocks around our house because we convinced ou
			link Read more, url='https://fly.io/blog/logbook-october-29-to-november-6-2022/'
		article
			image, url='https://fly.io/blog/love-letter-react/assets/desktop-thumbnail.webp'
			StaticText BY CHRIS MCCORD
			StaticText 13 MIN READ
			heading A love letter to React
			paragraph
				StaticText It’s hard to overstate the impact React has had since its release in 2013. For me, React came with a few revelations. First was a reactive HTML-aware component model for building UIs. Second was colocated markup directly in the app code. Third, it fo
			link Read more, url='https://fly.io/blog/love-letter-react/'
		article
			image, url='https://fly.io/blog/logbook-october-21-to-28-2022/assets/logbook-default2-thumbnail.webp'
			StaticText BY BRAD GESSLER
			StaticText 3 MIN READ
			heading Logbook: October 21 to 28, 2022
			paragraph
				StaticText Postgres docs improvements First up, some new documentation was created to run people through how to fail over a Postgres database. Performing a Failover Performing a Regional Failover “Getting Started” was updated to show how to setup a Postgres
			link Read more, url='https://fly.io/blog/logbook-october-21-to-28-2022/'
		article
			image, url='https://fly.io/blog/introducing-litefs/assets/litefs-thumbnail.webp'
			StaticText BY BEN JOHNSON
			StaticText 12 MIN READ
			heading Introducing LiteFS
			paragraph
				StaticText Full-stack developers are sleeping on SQLite, a database most devs think more suited to unit tests than production loads. That’s true enough for some apps. Most web apps are read-heavy, though, and we can use that to our advantage. With the right too
			link Read more, url='https://fly.io/blog/introducing-litefs/'
		article
			image, url='https://fly.io/blog/scale-to-zero-minecraft/assets/mc-thumbnail.webp'
			StaticText BY DOV ALPERIN
			StaticText 8 MIN READ
			heading Scale-to-Zero Minecraft server with Terraform and Fly Machines
			paragraph
				StaticText Running a Minecraft server for friends has become an archetypal first foray into the workings of the Internet. For some it’s learning to expose the tender underbelly of a home network to outside connections. For others it’s exploring the world of VMs
			link Read more, url='https://fly.io/blog/scale-to-zero-minecraft/'
		article
			image, url='https://fly.io/blog/sqlite-virtual-machine/assets/vm-thumbnail.webp'
			StaticText BY BEN JOHNSON
			StaticText 15 MIN READ
			heading How the SQLite Virtual Machine Works
			paragraph
				StaticText SQL is a weird concept. You write your application in one language, say JavaScript, and then send commands in a completely different language, called SQL, to the database. The database then compiles and optimizes that SQL command, runs it, and return
			link Read more, url='https://fly.io/blog/sqlite-virtual-machine/'
		article
			image, url='https://fly.io/blog/sqlite-internals-wal/assets/internals-thumbnail.webp'
			StaticText BY BEN JOHNSON
			StaticText 14 MIN READ
			heading How SQLite Scales Read Concurrency
			paragraph
				StaticText If you scour Hacker News & Reddit for advice about databases, some common words of caution are that SQLite doesn’t scale or that it is a single-user database and it’s not appropriate for your web-scale application. Like any folklore, it has some his
			link Read more, url='https://fly.io/blog/sqlite-internals-wal/'
		article
			image, url='https://fly.io/blog/remote-ide-machines/assets/ide-the-hard-way-thumbnail.webp'
			StaticText BY LUBIEN & CHRIS NICOLL
			StaticText 22 MIN READ
			heading Building an In-Browser IDE the Hard Way
			paragraph
				StaticText “Remote development environment!” Whether you reacted with a thrill of enthusiasm, a surge of derision or a waft of indifference, we’re not really here to change your mind. That phrase means a lot of different things at this point in history. The m
			link Read more, url='https://fly.io/blog/remote-ide-machines/'
		article
			image, url='https://fly.io/blog/sqlite-internals-rollback-journal/assets/rollback-journal-thumbnail.webp'
			StaticText BY BEN JOHNSON
			StaticText 14 MIN READ
			heading How SQLite helps you do ACID
			paragraph
				StaticText When database vendors recite their long list of features, they never enumerate “doesn’t lose your data” as one of those features. It’s just assumed. That’s what a database is supposed to do. However, in reality, the best database vendors tell you exa
			link Read more, url='https://fly.io/blog/sqlite-internals-rollback-journal/'
		article
			image, url='https://fly.io/blog/volumes-expand-restore/assets/snapshot-restore-thumbnail.webp'
			StaticText BY CHRIS NICOLL
			StaticText 2 MIN READ
			heading Volume Expansion and Snapshot Restores
			paragraph
				StaticText Fly Volumes are the persistent storage that makes it possible to run full stack apps entirely on the Fly.io platform, keeping your configuration, session or user data in place across deployments. Looking at them from another angle, volumes are space
			link Read more, url='https://fly.io/blog/volumes-expand-restore/'
		article
			image, url='https://fly.io/blog/sqlite-internals-btree/assets/sqlite-thumbnail.webp'
			StaticText BY BEN JOHNSON
			StaticText 14 MIN READ
			heading SQLite Internals: Pages & B-trees
			paragraph
				StaticText Ok, I’ll admit it—I’m a SQLite shill. There are few holes that I don’t try to put a SQLite-shaped peg into. It’s not that I dislike other databases, they’re great. But SQLite is so easy to use and, more importantly, it’s simple. Simplicity leads to r
			link Read more, url='https://fly.io/blog/sqlite-internals-btree/'
		article
			image, url='https://fly.io/blog/launching-laravel-bytes/assets/laravel-announcement-thumbnail.webp'
			StaticText BY CHRIS FIDAO
			StaticText 1 MIN READ
			heading Launching Laravel Bytes
			paragraph
				StaticText Today we’re launching Laravel Bytes - our new home for anything Laravel. We’re excited to support deploying Laravel across the globe - and we have lots to talk about! We’ve already made it easy to run Laravel on Fly, but with the possibilities unlo
			link Read more, url='https://fly.io/blog/launching-laravel-bytes/'
		article
			image, url='https://fly.io/blog/liveview-its-alive/assets/phoenix-birth-thumbnail.webp'
			StaticText BY CHRIS MCCORD
			StaticText 18 MIN READ
			heading How LiveView Took on a Life of Its Own
			paragraph
				StaticText LiveView started with a simple itch. I wanted to write dynamic server-rendered applications without writing JavaScript. Think realtime validations on forms, or updating the quantity in a shopping cart. The server would do the work, with the client re
			link Read more, url='https://fly.io/blog/liveview-its-alive/'
		article
			image, url='https://fly.io/blog/logbook-2022-07-18/assets/logbook-default2.webp'
			StaticText BY THE FLY.IO BALLOON
			StaticText 7 MIN READ
			heading Logbook - 2022-07-18
			paragraph
				StaticText We have some real gems in this edition. Have you ever wished you could grow the storage volume on a Fly.io app? Now you can!! What about this one: Ever wished that the $99 Pro Plan would include $99 of usage credits? OK, that one may have been a li
			link Read more, url='https://fly.io/blog/logbook-2022-07-18/'
		article
			image, url='https://fly.io/blog/soc2-the-screenshots-will-continue-until-security-improves/assets/soc2-thumbnail.webp'
			StaticText BY THOMAS PTACEK
			StaticText 25 MIN READ
			heading SOC2: The Screenshots Will Continue Until Security Improves
			paragraph
				StaticText If you’re off getting your app up and running on Fly.io and finding your checkbook, great! I won’t get in your way. The rest of you, though, I want to talk to you about what SOC2 is and how it works. Spoiler: the SOC2 Starting Seven post held up pret
			link Read more, url='https://fly.io/blog/soc2-the-screenshots-will-continue-until-security-improves/'
		article
			image, url='https://fly.io/blog/the-serverless-server/assets/not-a-server-thumbnail.webp'
			StaticText BY WILL JORDAN
			StaticText 20 MIN READ
			heading The Serverless Server
			paragraph
				StaticText Fly.io isn’t a “Gartner Magic Quadrant” kind of company. We use terms like “FaaS” and “PaaS” and “serverless”, but mostly to dunk on them. It’s just not how we think about things. But the rest of the world absolutely does think this way, and I want t
			link Read more, url='https://fly.io/blog/the-serverless-server/'
		article
			image, url='https://fly.io/blog/logbook-2022-06-23/assets/logbook-default-thumbnail.webp'
			StaticText BY THE FLY.IO BALLOON
			StaticText 6 MIN READ
			heading Logbook - 2022-06-23
			paragraph
				StaticText We’ve had a lot of changelogs about our Phoenix/LiveView-based web UI in recent weeks. It’s pretty rad; we’ve been vocal about being CLI-first, but we love a first-class dashboard. Our dashboard has sprouted a lot of new capabilities, and at this poi
			link Read more, url='https://fly.io/blog/logbook-2022-06-23/'
		article
			image, url='https://fly.io/blog/rust-memory-leak/assets/fixing-leaks-thumbnail.webp'
			StaticText BY AMOS WENGER
			StaticText 24 MIN READ
			heading How to make Rust leak memory (also: how to make it stop)
			paragraph
				StaticText We have a Rust-based proxy. It was leaking memory. We fixed it, and we’ll talk about that, but to be really thorough, we’ll look at how loading a web page works. Starting with hardware interrupts. The downside of Thomas writing job postings is that t
			link Read more, url='https://fly.io/blog/rust-memory-leak/'
		article
			image, url='https://fly.io/blog/logbook-2022-06-10/assets/logbook-default3-thumbnail.webp'
			StaticText BY THE FLY.IO BALLOON
			StaticText 3 MIN READ
			heading Logbook - 2022-06-10
			paragraph
				StaticText Here’s our latest changelog. This week we’re putting the in-browser UI updates a little closer to all the other ones, to see if they’ll play nicely together. [Feature] Our WireGuard peers sync a lot faster with the kernel’s wg state, by adding only
			link Read more, url='https://fly.io/blog/logbook-2022-06-10/'
		article
			image, url='https://fly.io/blog/logbook-2022-06-01/assets/logbook-default2-thumbnail.webp'
			StaticText BY THE FLY.IO BALLOON
			StaticText 5 MIN READ
			heading Logbook - 2022-06-01
			paragraph
				StaticText Here’s our latest changelog. Looking back over the week, our forum community has been quite a driver of (logged) change. When you’re done here, head over there to be a part of it! [Feature] Created an example Node.js app to demonstrate how to expo
			link Read more, url='https://fly.io/blog/logbook-2022-06-01/'
		article
			image, url='https://fly.io/blog/logbook-2022-05-26/assets/logbook-default-thumbnail.webp'
			StaticText BY THE FLY.IO BALLOON
			StaticText 5 MIN READ
			heading Logbook - 2022-05-26
			paragraph
				StaticText Work leading up to the Fly Machines launch involved a multitude of changes by many of the cogs in this corporate machine, but that’s not to say the other production lines have been idle. For one thing, our web UI has been transforming before our eyes
			link Read more, url='https://fly.io/blog/logbook-2022-05-26/'
		article
			image, url='https://fly.io/blog/fly-machines/assets/machine-whack-a-mole-thumbnail.webp'
			StaticText BY KURT MACKEY
			StaticText 10 MIN READ
			heading Fly Machines: an API for fast-booting VMs
			paragraph
				StaticText Fly Machines are VMs with a fast REST API that can boot instances in about 300ms. Our proxy can boot Fly Machines for you, and you can shut them down when they’re idle. Which means you can cost-effectively create VMs and keep them standing by to ha
			link Read more, url='https://fly.io/blog/fly-machines/'
		article
			image, url='https://fly.io/blog/logbook-2022-05-13/assets/logbook-default-thumbnail.webp'
			StaticText BY THE FLY.IO BALLOON
			StaticText 2 MIN READ
			heading Logbook - 2022-05-13
			paragraph
				StaticText [Feature] Provisioned new servers in syd, iad, and dfw which were very full. Added capacity should mean customers should no longer get provisioning issues when trying to deploy to these regions. [Feature] The account deactivation page now asks users
			link Read more, url='https://fly.io/blog/logbook-2022-05-13/'
		article
			image, url='https://fly.io/blog/all-in-on-sqlite-litestream/assets/litestream-thumbnail.webp'
			StaticText BY BEN JOHNSON
			StaticText 15 MIN READ
			heading I'm All-In on Server-Side SQLite
			paragraph
				StaticText The conventional wisdom of full-stack applications is the n-tier architecture, which is now so common that it’s easy to forget it even has a name. It’s what you’re doing when you run an “application server” like Rails, Django, or Remix alongside a “d
			link Read more, url='https://fly.io/blog/all-in-on-sqlite-litestream/'
		article
			image, url='https://fly.io/blog/logbook-2022-05-05/assets/logbook-default3-thumbnail.webp'
			StaticText BY CHRIS NICOLL
			StaticText 5 MIN READ
			heading Logbook - 2022-05-05
			paragraph
				StaticText Features and fixes are flying like dodgeballs in a school gym, and the Fly.io Changelog Enforcer could probably have done a better job patrolling—but let’s have a look at our haul of updates since our first Logbook post. There’s a fair amount of pr
			link Read more, url='https://fly.io/blog/logbook-2022-05-05/'
		article
			image, url='https://fly.io/blog/accessibility-clearing-the-fog/assets/accessibility_02-thumbnail.webp'
			StaticText BY NOLAN DARILEK
			StaticText 10 MIN READ
			heading Accessibility and Real-time Apps: Clearing Fog and Picking Fruit
			paragraph
				StaticText Hey, everyone. Last time we talked a bit about what accessibility is, why it’s important, and how you can incorporate it into your process. Today, using the time-travel superpowers of Git, I’ll take you along as I start making LiveBeats more accessib
			link Read more, url='https://fly.io/blog/accessibility-clearing-the-fog/'
		article
			image, url='https://fly.io/blog/logbook-2022-04-20/assets/logbook-default2-thumbnail.webp'
			StaticText BY CHRIS NICOLL
			StaticText 6 MIN READ
			heading Logbook - 2022-04-20
			paragraph
				StaticText Here’s a changelog covering our most recent activity (i.e. since we started compiling updates, a bit under two weeks ago): [Feature] Added extra capacity in IAD. [Feature] Backup regions (by far our most confusing misfeature) are now disabled by de
			link Read more, url='https://fly.io/blog/logbook-2022-04-20/'
		article
			image, url='https://fly.io/blog/a-foolish-consistency/assets/default-books-thumbnail.webp'
			StaticText BY THOMAS PTACEK
			StaticText 21 MIN READ
			heading A Foolish Consistency: Consul at Fly.io
			paragraph
				StaticText We set the scene, as usual, with sandwiches. Dig if you will the picture: a global Sandwich Bracket application, ascertaining once and for all the greatest sandwich on the planet. Fly.io wants our app, sandwich-bracket, deployed close to users aroun
			link Read more, url='https://fly.io/blog/a-foolish-consistency/'
		article
			image, url='https://fly.io/blog/intro-to-accessibility/assets/accessibility-thumbnail.webp'
			StaticText BY NOLAN DARILEK
			StaticText 9 MIN READ
			heading Accessibility for real-time web apps
			paragraph
				StaticText Like every developer, I rely on a number of products and services to manage and promote my many side projects. But I’ve had more than one neat idea go down in flames because I simply couldn’t use the amazing, must-have service that would have made
			link Read more, url='https://fly.io/blog/intro-to-accessibility/'
		article
			image, url='https://fly.io/blog/our-user-mode-wireguard-year/assets/danger!-thumbnail.webp'
			StaticText BY THOMAS PTACEK
			StaticText 19 MIN READ
			heading Our User-Mode WireGuard Year
			paragraph
				StaticText WireGuard is fundamental to how Fly.io works. Along with Firecracker and Rust, it’s one of the three “interesting” technical choices we’ve made. Practically everything that talks to anything else at Fly.io does so over WireGuard. That goes for use
			link Read more, url='https://fly.io/blog/our-user-mode-wireguard-year/'
		article
			image, url='https://fly.io/blog/new-turboku/assets/turbocharge-heroku-thumbnail.webp'
			StaticText BY LUBIEN & CHRIS NICOLL
			StaticText 8 MIN READ
			heading Turbocharge your Heroku Apps with New Turboku
			paragraph
				StaticText In early 2020, before we launched our VM platform, we made a little landing page called Turboku. It was a one-click launcher to deploy a Heroku app on Fly.io. It let people try us out without spending time porting an app. Many of our first customers
			link Read more, url='https://fly.io/blog/new-turboku/'
		article
			image, url='https://fly.io/blog/livebeats/assets/livebeats-thumbnail.webp'
			StaticText BY CHRIS MCCORD
			StaticText 12 MIN READ
			heading LiveBeats: Building a social music app with Phoenix LiveView
			paragraph
				StaticText We decided that 2022 was a good year to ship a full-stack Phoenix reference app. The “full stack” metaphor has progressed beyond its humble beginnings of some REST endpoints and sprinkles of JS and CSS. Showing off a todo app is also no longer state
			link Read more, url='https://fly.io/blog/livebeats/'
		article
			image, url='https://fly.io/blog/free-postgres/assets/free-postgres-thumbnail.webp'
			StaticText BY KURT MACKEY & CHRIS NICOLL
			StaticText 4 MIN READ
			heading Free Postgres Databases
			paragraph
				StaticText We like building side projects and also hate paying for hosting for side projects. We also know that y'all like free stuff. And we think that when you use free stuff for side projects, there’s a pretty good chance you’ll pay for similar stuff for rea
			link Read more, url='https://fly.io/blog/free-postgres/'
		article
			image, url='https://fly.io/blog/self-service-account-deactivation/assets/bye-bye-bye-thumbnail.webp'
			StaticText BY LUBIEN
			StaticText 3 MIN READ
			heading Self-service account deactivation: why it’s harder than you would think
			paragraph
				StaticText We’ve just introduced a self-service UI for deleting your Fly.io account. From time to time people ask us to deactivate their account. It happens! Maybe you just tried a walkthrough out of interest, or you created a new account with a different name
			link Read more, url='https://fly.io/blog/self-service-account-deactivation/'
		article
			image, url='https://fly.io/blog/creating-the-livebook-launcher-in-liveview/assets/livebook-launcher-deploying.webp'
			StaticText BY MARK ERICKSEN
			StaticText 3 MIN READ
			heading Launching Livebook using LiveView
			paragraph
				StaticText The Livebook launcher was super fun to create. Everything happens in a single LiveView process. There was a problem though… it wasn’t great if we were in the middle of deploying the app for the user and one these things happened: User hits “refresh
			link Read more, url='https://fly.io/blog/creating-the-livebook-launcher-in-liveview/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY CHRIS MCCORD
			StaticText 3 MIN READ
			heading How Safari Ruined My Tuesday
			paragraph
				StaticText Safari 15 shipped in September 2021 and included an obscure CSS bug that broke most LiveView applications. The LiveView client operates in two modes – connected, when it can talk to the server over websockets, and disconnected when offline. When Live
			link Read more, url='https://fly.io/blog/how-safari-ruined-my-tuesday/'
		article
			image, url='https://fly.io/blog/32-bit-real-estate/assets/ipbank-thumbnail.webp'
			StaticText BY KURT MACKEY
			StaticText 18 MIN READ
			heading 32 Bit Real Estate
			paragraph
				StaticText Two obvious costs of running Internet apps for users on your own hardware: hardware and bandwidth. We buy big servers and run them in racks at network providers that charge us to route large volumes of traffic using BGP4 Anycast. You probably have at
			link Read more, url='https://fly.io/blog/32-bit-real-estate/'
		article
			image, url='https://fly.io/blog/how-we-got-to-liveview/assets/switches-thumbnail.webp'
			StaticText BY CHRIS MCCORD
			StaticText 21 MIN READ
			heading How We Got to LiveView
			paragraph
				StaticText LiveView strips away layers of abstraction, because it solves both the client and server in a single abstraction. HTTP almost entirely falls away. No more REST. No more JSON. No GraphQL APIs, controllers, serializers, or resolvers. You just write HTM
			link Read more, url='https://fly.io/blog/how-we-got-to-liveview/'
		article
			image, url='https://fly.io/blog/fly-io-is-hiring-full-stack-developers/assets/jobs-cover-01-thumbnail.webp'
			StaticText BY MICHAEL DWAN
			StaticText 6 MIN READ
			heading Fly.io Is Hiring Full-Stack Developers
			paragraph
				StaticText We’re working on super fun problems and are looking for more people to join us. In particular: we’re looking for full-stack developers. We expect this will be a good role for early-to-mid-level career developers. Some Background Fly.io’s users intera
			link Read more, url='https://fly.io/blog/fly-io-is-hiring-full-stack-developers/'
		article
			image, url='https://fly.io/blog/api-tokens-a-tedious-survey/assets/tedious-survey-thumbnail.webp'
			StaticText BY THOMAS PTACEK
			StaticText 29 MIN READ
			heading API Tokens: A Tedious Survey
			paragraph
				StaticText This is not really a post about Fly.io, though I’ll talk about us a little up front to set the scene. The last several weeks of my life have been about API security. I’m working on a new permissions system for Fly.io, and did a bunch of researc
			link Read more, url='https://fly.io/blog/api-tokens-a-tedious-survey/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY MARK ERICKSEN
			StaticText 8 MIN READ
			heading Better Business Intelligence in Elixir with Livebook
			paragraph
				StaticText As a developer, has your manager ever come and asked a question like, “How much money are we making?” If you were a line-of-business developer at a global insurance company, you’d reach for your handy, nosebleed-expensive Business Intelligence (BI) s
			link Read more, url='https://fly.io/blog/better-business-intelligence-in-elixir-with-livebook/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY MARK ERICKSEN
			StaticText 3 MIN READ
			heading FYI: Phoenix drops webpack and npm for esbuild
			paragraph
				StaticText The Phoenix Framework is the go-to web framework for Elixir developers. A recent PR was merged that replaces the use of node, npm, and webpack with esbuild. For those new to esbuild, it is written in Go so it compiles to native code and runs really f
			link Read more, url='https://fly.io/blog/phoenix-moves-to-esbuild-for-assets/'
		article
			image, url='https://fly.io/blog/last-mile-redis/assets/last-mile-redis-thumbnail.webp'
			StaticText BY KURT MACKEY
			StaticText 10 MIN READ
			heading Last Mile Redis
			paragraph
				StaticText 100 milliseconds is the magic number. For a backend application, a sub-100ms response time is effectively instantaneous, and people love using “instant” apps. Since we’re all dirty capitalists, we’d add: if people love your app, you’ll make more mone
			link Read more, url='https://fly.io/blog/last-mile-redis/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY MARK ERICKSEN
			StaticText 2 MIN READ
			heading FYI: Livebook 0.2 with Kino
			paragraph
				StaticText Livebook 0.2 was released. The big news here was the announcement of “Kino” (meaning “cinema”). It’s a client-side focused feature that animates data changes. José Valim created a video demonstrating some of the new Livebook features. Use this link to
			link Read more, url='https://fly.io/blog/livebook-with-kino/'
		article
			image, url='https://fly.io/blog/globally-distributed-postgres/assets/cats-around-the-world-thumbnail.webp'
			StaticText BY KURT MACKEY & KURT MACKEY
			StaticText 13 MIN READ
			heading Globally Distributed Postgres
			paragraph
				StaticText This is a story about a cool hack we came up with at Fly. The hack lets you do something pretty ambitious with full-stack applications. What makes it cool is that it’s easy to get your head around, and involves just a couple moving parts, assembled i
			link Read more, url='https://fly.io/blog/globally-distributed-postgres/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY ALEXANDER KOUTMOS
			StaticText 9 MIN READ
			heading Monitoring Elixir Apps on Fly.io With Prometheus and PromEx
			paragraph
				StaticText Fly.io takes Docker containers and converts them into fleets of Firecracker micro-vms running in racks around the world. If you have a working Docker container, you can run it close to your users, whether they’re in Singapore or Amsterdam, with just
			link Read more, url='https://fly.io/blog/monitoring-your-fly-io-apps-with-prometheus/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY MARK ERICKSEN
			StaticText 6 MIN READ
			heading Observing Elixir in Production
			paragraph
				StaticText Elixir, Erlang, and really just the BEAM has a feature called “Observer”. It’s fun showing it to people new to Elixir because it’s just so cool! It’s a WxWidgets graphical interface that connects in realtime to a running Erlang node and lets you “obs
			link Read more, url='https://fly.io/blog/observing-elixir-in-production/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY MARK ERICKSEN
			StaticText 7 MIN READ
			heading Livebook is a secret weapon for documentation
			paragraph
				StaticText Every application has that core, most important thing that it does. It is the reason the application exists. It’s that central idea that everything else is there to support. A major hurdle for new developers joining a project can be understanding an
			link Read more, url='https://fly.io/blog/livebook-for-app-documentation/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY THOMAS PTACEK
			StaticText 11 MIN READ
			heading Hooking Up Fly Metrics
			paragraph
				StaticText We’ve written a bit, for a general audience, about how Fly collects and manages metrics. If you’re just sort of generally interested in metrics and observability, go read that first. Meanwhile, if you’re a Fly user, or considering becoming such a us
			link Read more, url='https://fly.io/blog/hooking-up-fly-metrics/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY THOMAS PTACEK
			StaticText 13 MIN READ
			heading Fly's Prometheus Metrics
			paragraph
				StaticText We should talk a bit about metrics and measurement and stuff, because they’re how we all know what’s going on. There’s two reasons we’ve written this post. The first is just that we think this stuff is interesting, and that the world can always use
			link Read more, url='https://fly.io/blog/measuring-fly/'
		article
			image, url='https://fly.io/blog/building-a-distributed-turn-based-game-system-in-elixir/assets/elixir-game-thumbnail.webp'
			StaticText BY MARK ERICKSEN
			StaticText 8 MIN READ
			heading Building a Distributed Turn-Based Game System in Elixir
			paragraph
				StaticText One of the best things about building web applications in Elixir is LiveView, the Phoenix Framework feature that makes it easy to create live and responsive web pages without all the layers people normally build. Many great Phoenix LiveView examples
			link Read more, url='https://fly.io/blog/building-a-distributed-turn-based-game-system-in-elixir/'
		article
			image, url='https://fly.io/blog/docker-without-docker/assets/starry-containers-thumbnail.webp'
			StaticText BY THOMAS PTACEK
			StaticText 14 MIN READ
			heading Docker without Docker
			paragraph
				StaticText Even though most of our users deliver software to us as Docker containers, we don’t use Docker to run them. Docker is great, but we’re high-density multitenant, and despite strides, Docker’s isolation isn’t strong enough for that. So, instead, we tra
			link Read more, url='https://fly.io/blog/docker-without-docker/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY KURT MACKEY
			StaticText 14 MIN READ
			heading The 5-hour CDN
			paragraph
				StaticText The term “CDN” (“content delivery network”) conjures Google-scale companies managing huge racks of hardware, wrangling hundreds of gigabits per second. But CDNs are just web applications. That’s not how we tend to think of them, but that’s all they ar
			link Read more, url='https://fly.io/blog/the-5-hour-content-delivery-network/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY THOMAS PTACEK
			StaticText 12 MIN READ
			heading SSH and User-mode IP WireGuard
			paragraph
				StaticText But Fly is kind of an odd duck. We run hardware in data centers around the world, connected to the Internet via Anycast and to each other with a WireGuard mesh. We take Docker-type containers from users and transmogrify them into Firecracker micro-VM
			link Read more, url='https://fly.io/blog/ssh-and-user-mode-ip-wireguard/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY JEROME GRAVEL-NIQUET & THOMAS PTACEK & JEROME GRAVEL-NIQUET
			StaticText 12 MIN READ
			heading Persistent Storage and Fast Remote Builds
			paragraph
				StaticText If you’ve been keeping up with us at Fly, you may be picking up on a bit of a narrative with us. Fly launched, in the long-long-ago, with a somewhat narrow use case. We took containers from our customers and transmogrified them into fleets of Firecra
			link Read more, url='https://fly.io/blog/persistent-storage-and-fast-remote-builds/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY JEROME GRAVEL-NIQUET
			StaticText 5 MIN READ
			heading The Tokio Upgrade from 0.2 to 1.x
			paragraph
				StaticText At Fly.io, we run a Rust-based load-balancer which handles almost all of our traffic. It stands on the shoulders of Tokio and Hyper. When the Tokio team announced 0.3 and then 1.0, we figured we’d have to upgrade sooner than later to access related cr
			link Read more, url='https://fly.io/blog/the-tokio-1-x-upgrade/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY THOMAS PTACEK & DJ WALKER-MORGAN & THOMAS PTACEK
			StaticText 10 MIN READ
			heading You should know about Server-Side Request Forgery
			paragraph
				StaticText This is a post about the most dangerous vulnerability most web applications face, one step that we took at Fly to mitigate it, and how you can do the same. Server-side request forgery (SSRF) is application security jargon for “attackers can get you
			link Read more, url='https://fly.io/blog/practical-smokescreen-sanitizing-your-outbound-web-requests/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 4 MIN READ
			heading The January 2021 Fly ChangeLog
			paragraph
				StaticText If you missed 2020, lucky you, to get you all caught up, here’s our Previously On Fly segment. Caught up? Good. And now here is the Fly ChangeLog, covering the end of December 2020 to January 2021. 6PN Networking and IPv6 WireGuard VPNs Let your ap
			link Read more, url='https://fly.io/blog/the-january-2021-fly-changelog/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 4 MIN READ
			heading Fly In 2020 - A year in features (and articles)
			paragraph
				StaticText TL:DR; Launch, Turboku, Custom Domains, Scaling, One-Click Apps, Persistent Storage, Private Networking and WireGuard VPNs. Fly’s had an unprecedented year, along with everyone else. For us, it was bringing our Application Platform to the world, and
			link Read more, url='https://fly.io/blog/fly-in-2020/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY THOMAS PTACEK
			StaticText 16 MIN READ
			heading Building clusters with serf, my new favorite thing
			paragraph
				StaticText Assume for a second we’d like to see what happens when a web page loads in a browser in Singapore. Easy enough; Fly.io will take a container image you throw at it, transform it into a Firecracker VM, and run it in Singapore. Getting Up And Running We
			link Read more, url='https://fly.io/blog/building-clusters-with-serf/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 1 MIN READ
			heading How to build a global message service with NATS
			paragraph
				StaticText There are actually two examples that make up this example. One example is a Websocket-based chat that relays its messages through that NATS cluster. The other part is that NATS cluster, configured as a global messaging cluster that you can install in
			link Read more, url='https://fly.io/blog/how-to-build-a-global-message-service-with-nats/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 2 MIN READ
			heading Get fly with your Fly command line
			paragraph
				StaticText The command… It started off as flyctl but we kept being asked when would the command become fly. “Why not both?” we said and now, on most platforms, you can use flyctl or fly interchangeably. Boom! Three keystrokes saved! The current app… You alread
			link Read more, url='https://fly.io/blog/get-fly-with-your-fly-command-line/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY MICHAEL DWAN
			StaticText 4 MIN READ
			heading Graceful VM exits, some dials
			paragraph
				StaticText Fly apps are typically fast to boot, and it’s relatively easy to boot new VMs. We start them up, do some health checks, and then add them to our load balancer and DNS service discovery. But what comes up must go down. We shut VMs down for any number
			link Read more, url='https://fly.io/blog/graceful-vm-exits-some-dials/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY THOMAS PTACEK
			StaticText 12 MIN READ
			heading IPv6 WireGuard Peering
			paragraph
				StaticText They say that when you’re starting a product company, it’s a better plan to chase down something a bunch of people will really love a lot than it is to try to build something that everyone will just like a little bit. So when Fly.io launched, it had
			link Read more, url='https://fly.io/blog/ipv6-wireguard-peering/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY KURT MACKEY
			StaticText 5 MIN READ
			heading New VMs: more RAM, extra CPU, and a dollar menu
			paragraph
				StaticText We first showed Fly.io VMs to developers in early 2020. They were most interested in running CPU intensive apps doing image processing, machine learning predictions, and even video transcoding (despite what were, until recently, offensive bandwidth p
			link Read more, url='https://fly.io/blog/new-vms-more-ram-extra-cpu-and-a-dollar-menu/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY THOMAS PTACEK
			StaticText 6 MIN READ
			heading Incoming! 6PN Private Networks
			paragraph
				StaticText More often than not, modern applications are really ensembles of cooperating services, running independently and transacting with each other over the network. At Fly.io, we’d like it to be not just possible to express these kinds of applications, but
			link Read more, url='https://fly.io/blog/incoming-6pn-private-networks/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY KURT MACKEY
			StaticText 5 MIN READ
			heading We cut bandwidth prices. Go nuts.
			paragraph
				StaticText When we launched Fly way back in March, we charged $0.085 per GB to send data out from North America and Europe, and $0.14 per GB for Asia Pacific. Our volume has increased dramatically and pushed our unit costs down, so we lowered our prices as of D
			link Read more, url='https://fly.io/blog/we-cut-bandwidth-prices-go-nuts/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 4 MIN READ
			heading The November Fly Changelog
			paragraph
				StaticText Example Applications We’ve been focussing on getting more example applications for Fly into your hands. Each guide is complete with a walkthrough of how they were put together so you can see the power of Fly in action. Or you can hop straight to the G
			link Read more, url='https://fly.io/blog/the-november-fly-changelog/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 2 MIN READ
			heading More Appkata Examples to Try on Fly
			paragraph
				StaticText The latest additions to our Appkata collection of example apps have landed and they cover how to fit Fly to your selected applications and are some super useful apps anyway. So let’s dive in. Node-RED Ever wanted to be able to dive into your cloud ap
			link Read more, url='https://fly.io/blog/more-appkata-examples-to-try-on-fly/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 4 MIN READ
			heading Appkata - Example Apps on Fly
			paragraph
				StaticText To build a modern application, you need to know how to take down your technical challenges in style. It’s a style we call Appkata! Over the coming weeks, we’ll be sharing with you the moves you need to deploy apps onto Fly that let you build faster.
			link Read more, url='https://fly.io/blog/appkata-example-apps-on-fly/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 3 MIN READ
			heading Fly Answers Questions - Suspend, Resume, Restart and Redis
			paragraph
				StaticText Q: I’d like to park my Fly application for a little while so it isn’t consuming resources. How can I do this without destroying the application and redeploying it later? A: As you’ll have noticed, Fly applications stay running all the time ready to
			link Read more, url='https://fly.io/blog/fly-answers-questions-suspend-resume-restart-and-redis/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 2 MIN READ
			heading The October Fly Changelog: Preview Disks and DNS and Better Builtins
			paragraph
				StaticText Disks in Preview If your application needs to have persistent storage, then the currently in preview volumes feature is for you. The volumes command allows you to create persistent disks for your application. These persist between restarts, deployment
			link Read more, url='https://fly.io/blog/the-october-fly-changelog-preview-disks-and-dns-and-better-builtins/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY THOMAS PTACEK
			StaticText 18 MIN READ
			heading BPF, XDP, Packet Filters and UDP
			paragraph
				StaticText Imagine for a moment that you run a content distribution network for Docker containers. You take arbitrary applications, unmodified, and get them to run on servers close to their users around the world, knitting those servers together with WireGuard.
			link Read more, url='https://fly.io/blog/bpf-xdp-packet-filters-and-udp/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 7 MIN READ
			heading Fly Behind The Scenes: Fresh Logging
			paragraph
				StaticText Since Fly launched, we’ve been collecting and managing logs for all the applications running on the Fly platform. It’s a critical but often rarely noted function of the platform. When you type flyctl logs, behind the scenes, there is a lot of comput
			link Read more, url='https://fly.io/blog/fly-behind-the-scenes-fresh-logging/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 7 MIN READ
			heading Stuff Your Pi-Hole From Anywhere
			paragraph
				StaticText A Pi-Hole could be the hero of your web connection. It blocks advertising at the roots; the DNS roots that is. By setting up your own Pi-Hole, you can tip all your local network’s requests for known advertising domains down it. What is Pi-Hole? Thin
			link Read more, url='https://fly.io/blog/stuff-your-pi-hole-from-anywhere/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 2 MIN READ
			heading Maps, Apps, and Tracks
			paragraph
				StaticText Marathons, long and hard. Personally, I wouldn’t be caught doing one, but I’m always up to help someone who is, especially when I can use a bit of Fly to do it. Steve, our global infrastructure whiz, asked if I could think of a good way to track M
			link Read more, url='https://fly.io/blog/maps-apps-and-tracks/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 5 MIN READ
			heading The September Fly Changelog: New Names and Easier Updates
			paragraph
				StaticText Some common requests are addressed this month. One is ‘can you let us type “fly” instead of “flyctl”?’, and it is a shorter command, that is true. Another is can you ‘make updating flyctl easier?’, something we are more than happy to do. And in Septe
			link Read more, url='https://fly.io/blog/the-september-fly-changelog-new-names-and-easier-updates/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 5 MIN READ
			heading Using Heroku Postgres From A Fly App
			paragraph
				StaticText Heroku supports applications with no apps in them and only add-ons, like Postgres, as a way of providing those services to other applications. As we showed, you can access Heroku Postgres from Fly so it makes it a useful way to get yourself a databa
			link Read more, url='https://fly.io/blog/using-heroku-postgres-from-a-fly-app/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 6 MIN READ
			heading Migrating Heroku Database Apps To Fly
			paragraph
				StaticText I was recently asked how the database migration in the original Turboku demo worked. For that original demo, the migration was practically automatic. We already knew that you could access a Heroku database from outside Heroku. Since then, Changes in
			link Read more, url='https://fly.io/blog/migrating-heroku-database-apps-to-fly/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 4 MIN READ
			heading Always Be Connecting (with HTTPS)
			paragraph
				StaticText At Fly, you’ll have already discovered that when you create an app, it appears as http://appname.fly.dev and if you connect there, your browser switches automatically, by redirection, to https://appname.fly.dev. That’s how we do it for the fly.dev
			link Read more, url='https://fly.io/blog/always-be-connecting-with-https/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 4 MIN READ
			heading More Fly Answers To Questions
			paragraph
				StaticText Q: Is it ok to run non-HTTP apps on Fly? From Pier via community.fly.io A: It is, with one caveat: your applications need to have a network service of some kind. Why is that? Well, when your app deploys, we run health checks to ensure you can connec
			link Read more, url='https://fly.io/blog/more-fly-answers-to-questions/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 5 MIN READ
			heading Flyctl Builtins - The Fly Changelog for August
			paragraph
				StaticText For the latest version of flyctl, we’ve focussed on making your life fast and simple. From getting your first deployment up and running to setting up a host’s certificate. Builtins First up, we’ve got the new “builtin” builders which you can select w
			link Read more, url='https://fly.io/blog/flyctl-builtins-the-fly-changelog-for-august/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY THOMAS PTACEK
			StaticText 18 MIN READ
			heading Sandboxing and Workload Isolation
			paragraph
				StaticText Workload isolation makes it harder for a vulnerability in one service to compromise every other part of the platform. It has a long history going back to 1990s qmail, and we generally agree that it’s a good, useful thing. Despite a plethora of isola
			link Read more, url='https://fly.io/blog/sandboxing-and-workload-isolation/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 5 MIN READ
			heading Serve small with Fly.io and GoStatic
			paragraph
				StaticText Static websites are great for carrying unchanging content, be it assets, images, fonts or even, as in this case, an entire site. Well, I say entire site, but if you saw my last article, you’ll know I recently rebranded a Maker organization and needed
			link Read more, url='https://fly.io/blog/serve-small-with-fly-io-and-gostatic/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 8 MIN READ
			heading Hugo's There - Flying with Hugo and Caddy
			paragraph
				StaticText There I was wondering what to do about a website for a new community venture I was running where I thought, yes, let’s generate the site with Hugo, serve it with Caddy and run it all on Fly. Why Hugo and Caddy? Well, they both have good reputations as
			link Read more, url='https://fly.io/blog/hugo-s-there-flying-with-hugo-and-caddy/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 4 MIN READ
			heading Flyctl Evolved - Fly Changelog
			paragraph
				StaticText This flyctl release brings in some big changes in the command structure as we move to an app-centric command style. What does that mean? Well, the apps subcommand is being deprecated; we’ve kept it in place for this release but now all its commands h
			link Read more, url='https://fly.io/blog/flyctl-evolved-fly-changelog/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY KURT MACKEY
			StaticText 1 MIN READ
			heading Run Apollo Server Close to Your Users
			paragraph
				StaticText I’m a newly minted GraphQL convert. We built Fly on top of GraphQL and the experience turned me into a shameless cheerleader. An API format with static typing? That’s my jam. (If you don’t care for JAMStack puns you can just go read our guide on bui
			link Read more, url='https://fly.io/blog/run-apollo-graphql-close-to-your-users/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY THOMAS PTACEK
			StaticText 14 MIN READ
			heading How CDNs Generate Certificates
			paragraph
				StaticText It’s been a hectic first couple of weeks at Fly, and I’m writing things up as I go along, because if I have to learn, so do you. This is going to be a bit of a meander; you’ll have to deal. Let’s start with “what’s Fly?” Briefly: Fly is a content del
			link Read more, url='https://fly.io/blog/how-cdns-generate-certificates/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 5 MIN READ
			heading Flyctl meets JSON
			paragraph
				StaticText Say hello to --json or -j for short. This new flag attempts to present all output from flyctl as JSON. If a command queries the Fly GraphQL API, you’ll get the JSON data from that call in your output. If a command shows you logs, you’ll get the logs
			link Read more, url='https://fly.io/blog/flyctl-meets-json/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 3 MIN READ
			heading Fly Changelog for 9th June
			paragraph
				StaticText In this edition: a new way to install flyctl (and native Windows installers), new commands in flyctl that let you restart, list and monitor applications, an improved open command and an important update to the Deno Buildpack. Flyctl New instruction
			link Read more, url='https://fly.io/blog/fly-changelog-9th-june/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 1 MIN READ
			heading Fly Changelog for 29th May
			paragraph
				StaticText You can get the Changelog in the blog or through an RSS feed of just changelog updates available on fly.io/changelog.xml. There’s also a dedicated ChangeLog page with all the recent updates. Most of this week’s changelog items are covered in an recen
			link Read more, url='https://fly.io/blog/fly-changelog-may-29th-2020/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 2 MIN READ
			heading Fly - Now With Power Pause
			paragraph
				StaticText What’s a pause for? When you start building your applications, there may come a point where you don’t want to keep your application running - mothballing while another project happens, schedule delays, or just plain wanting to manage your costs. Tha
			link Read more, url='https://fly.io/blog/fly-now-with-power-pause/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 8 MIN READ
			heading WebSockets and Fly
			paragraph
				StaticText WebSockets are powerful things for creating interactive applications. Example Zero for WebSocket examples is the chat application. This leverages WebSockets’ ability to keep a connection alive over a long period of time while bidirectionally passing
			link Read more, url='https://fly.io/blog/websockets-and-fly/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DYLAN JHAVERI
			StaticText 4 MIN READ
			heading Mux, Fly, Wocket and RTMP
			paragraph
				StaticText Wocket (WebSocket to RTMP) This project is a proof-of-concept to demonstrate how you can stream live from your browser to an RTMP server. Streaming via RTMP is how you stream to Twitch, Youtube Live, Facebook Live, and other live streaming platforms
			link Read more, url='https://fly.io/blog/mux-fly-wocket-and-rtmp/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 1 MIN READ
			heading Fly Changelog May 15th 2020
			paragraph
				StaticText Since the last ChangeLog, we implemented a whole new scaling system with updates to the platform and flyctl. You can read all the details in the Updating Scale article. We’ve also been improving the performance of our backhaul, which moves traffice b
			link Read more, url='https://fly.io/blog/fly-changelog-may-15th-2020/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 6 MIN READ
			heading Deno on Fly
			paragraph
				StaticText We’ve been working with Deno for Fly for a while and its great blend of TypeScript, V8, Rust and simplicity makes for a great app experience. And great apps deserve a great deployment. We enjoy Deno so much that when we brought out our first cloud na
			link Read more, url='https://fly.io/blog/deno-on-fly/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 5 MIN READ
			heading Updating Scale
			paragraph
				StaticText We have been recently looking at how scaling commands work on Fly and we’ve come up with a new system with a simpler model and more compact command set to work with. We’d like to introduce it to you today. The Scaling System Previously, at least in t
			link Read more, url='https://fly.io/blog/updating-scale/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 1 MIN READ
			heading Fly Changelog 1st May 2020
			paragraph
				StaticText Since the last ChangeLog, we’ve introduced some enhancements to flyctl which make it easier to deploy tagged local and remote images directly to Fly. There is also a new load-balancing algorithm in operation which should be more effective with widely
			link Read more, url='https://fly.io/blog/fly-changelog-1st-may-2020/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 8 MIN READ
			heading Deno on Fly using Buildpacks
			paragraph
			link Read more, url='https://fly.io/blog/deno-on-fly-using-buildpacks/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 1 MIN READ
			heading Imaginary on Fly, just One-click
			paragraph
				StaticText Warning: This document is old! It is likely wrong in some important way. The folks behind Imaginary have worked with Fly and they also added the one-click launcher to their README on GitHub so that potential Imaginary users can be up, converting, res
			link Read more, url='https://fly.io/blog/imaginary-on-fly-just-one-click/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 1 MIN READ
			heading Fly Changelog 17th April 2020
			paragraph
				StaticText This past week has been one focused on the Fly infrastructure with earlier certificate renewals now in place and a dedicated Changlog page. We also made time to bring in some user contributed changes to the flyctl which make debugging fly.toml file
			link Read more, url='https://fly.io/blog/fly-changelog-17th-april-2020/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 1 MIN READ
			heading Fly Changelog 9th April 2020
			paragraph
				StaticText 7th April 2020 FlyCtl – v0.0.115 released Buildkit support. Setting environment variable DOCKER_BUILDKIT to 1 will enable use of the v2 buildkit backend which performs async parallel builds. For compatibility, DOCKER_BUILDKIT defaults to 0. The -
			link Read more, url='https://fly.io/blog/fly-changelog-9th-april-2020/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 3 MIN READ
			heading Powerbuilding with Fly
			paragraph
				StaticText Identifying your build When you deploy, the flyctl application looks for instructions to build the image in a Dockerfile or creates a builder VM to do the image build. Let’s start with the flags that control where flyctl looks for things. -c, –confi
			link Read more, url='https://fly.io/blog/powerbuilding-with-fly/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 3 MIN READ
			heading Fly Answers More Questions
			paragraph
				StaticText Q: What if I get a large number of malicious TCP connections from around the world that are malicious and cause a large number of apps to be launched in the various datacenters. Are we on the hook for the bill? And is there anything in place to stop
			link Read more, url='https://fly.io/blog/fly-answers-more-questions/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 9 MIN READ
			heading Making Datasets Fly with Datasette and Fly
			paragraph
				StaticText I’ve always liked finding a good dataset. With a background in databases and writing, I know a good dataset can bring a demo to life, be it a census of Squirrels in Central Park or a survey of grocery purchases in London. Datasets can also provide va
			link Read more, url='https://fly.io/blog/making-datasets-fly-with-datasette-and-fly/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 4 MIN READ
			heading Continuous Deployment with GitLab
			paragraph
				StaticText Starting with Continuous Deployment to Fly To deploy to Fly you essentially need four things The application you want to deploy. A runnable copy of flyctl. A fly.toml file. Your Fly API Token. For this example, we’ll deploy hellofly, our small Go
			link Read more, url='https://fly.io/blog/continuous-deployment-with-gitlab/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 4 MIN READ
			heading Fly Answers Questions
			paragraph
				StaticText Q: Can I set up a custom hostname or domain with Fly? A: You can. In fact you can set up as many of them on an application as you like. When you create a custom hostname on Fly and validate it, you also get Let’s Encrypt certificates automatically. Yo
			link Read more, url='https://fly.io/blog/fly-answers-questions/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 4 MIN READ
			heading Scaling Fly for All
			paragraph
				StaticText Update 15/May/2020: The contents of this article have been superceded by a new scaling system on Fly. We’ve refined the scaling models and commands to make things simpler to use. To read about these changes see the article on the updated scale system
			link Read more, url='https://fly.io/blog/scaling-fly-for-all/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 2 MIN READ
			heading How to do Custom Domains with Fly
			paragraph
				StaticText In Custom Domains with Fly, you’ll learn how to configure an NGINX server to proxy traffic to external sites and how to attach host and domain names to your Fly applications using Fly’s command line flyctl. For those of you who practice devops and
			link Read more, url='https://fly.io/blog/how-to-custom-domains-with-fly/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 1 MIN READ
			heading Fly Friday - News and Tips
			paragraph
				StaticText This week with Fly: We show you how to use Fly to build your own GraphQL APIs. Firefox is switching DNS over HTTPS (DoH) on by default in the USA. We already have a great guide to using Fly as your private DoH service. Fly’s new community portal for
			link Read more, url='https://fly.io/blog/fly-friday-feb28-news/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 1 MIN READ
			heading GraphQL, Hasura and Fly
			paragraph
				StaticText Hasura gives you an open source GraphQL backend which can make it simple to query PostgreSQL by helping you map all your schemas and roles. It also rolls in the ability to query other GraphQL services so you can mix in services. With an interactive c
			link Read more, url='https://fly.io/blog/graphql-hasura-and-fly/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 1 MIN READ
			heading Fly Friday - Customizing with Dockerfiles
			paragraph
				StaticText We deployed Docker’s official httpd image in our first Fly Friday video. That image, when run, serves up files from its /usr/local/apache2/html. By default the image contains the words “It works”. If we want it to say something else, we need to copy
			link Read more, url='https://fly.io/blog/fly-friday-customizing-with-dockerfiles/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 1 MIN READ
			heading Fly Friday - Flyctl and Ports
			paragraph
				StaticText TL;DR: The -p flag is used with flyctl apps create when you create a Fly app for the first time. Setting -p with a numeric value automatically sets the internal port of the generated fly.toml configuration file. The internal port is the port your a
			link Read more, url='https://fly.io/blog/fly-friday-flyctl-and-ports/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 2 MIN READ
			heading Simpler Fly deployments for NodeJS, Rails, Go, and Java
			paragraph
				StaticText A Speedrun for everyone Let’s get straight down to it. Make sure you have the latest version of flyctl and then get a Node application like this version of our hello world example - “hellonode-builder”. Wrap text
			link Read more, url='https://fly.io/blog/simpler-fly-deployments-nodejs-rails-golang-java/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 2 MIN READ
			heading Turboku - The Art Of Faster Heroku Apps
			paragraph
				StaticText The next question is how can they move their application the Fly. For that we’ve created “Turboku”, a simple way to bring your Heroku apps to Fly. What we do is take your Heroku web dynos and turn them into Fly applications automatically. That
			link Read more, url='https://fly.io/blog/turboku/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 3 MIN READ
			heading Command Lines, Flyctl and Fly
			paragraph
				StaticText Why Command Lines? As we’ve developed Fly, we’ve seen numerous benefits that come from driving the service through the command line. Our newest addition to our command armory is the flyctl command which now, quite literally, covers the entire lifecycl
			link Read more, url='https://fly.io/blog/command-lines-flyctl-and-fly/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText <1 MIN READ
			heading Welcome To Fly In 2020
			paragraph
				StaticText Check out our all new documentation for the Fly platform which covers everything from creating Apps you can deploy to Fly to how to take existing Docker images and setting them free across the globe. If you have any questions, drop a line to us on su
			link Read more, url='https://fly.io/blog/welcome-to-fly/'
	contentinfo
		link Fly App performance optimization, url='https://fly.io/'
			image Fly App performance optimization
		DescriptionList
			term
				StaticText COMPANY
			definition
				link About, url='https://fly.io/about/'
				link Pricing, url='https://fly.io/pricing/'
				link Jobs, url='https://fly.io/jobs/'
		DescriptionList
			term
				StaticText ARTICLES
			definition
				link Blog, url='https://fly.io/blog/'
				link Phoenix Files, url='https://fly.io/phoenix-files/'
				link Laravel Bytes, url='https://fly.io/laravel-bytes/'
				link Ruby Dispatch, url='https://fly.io/ruby-dispatch/'
				link Django Beats, url='https://fly.io/django-beats/'
				link JavaScript Journal, url='https://fly.io/javascript-journal/'
		DescriptionList
			term
				StaticText RESOURCES
			definition
				link Docs, url='https://fly.io/docs/'
				link Support, url='https://fly.io/docs/support/'
				link Support Metrics, url='https://fly.io/support/'
				link Status, url='https://status.flyio.net/'
		DescriptionList
			term
				StaticText CONTACT
			definition
				link GitHub, url='https://github.com/superfly/'
				link Twitter, url='https://twitter.com/flydotio'
				link Community, url='https://community.fly.io/'
		DescriptionList
			term
				StaticText LEGAL
			definition
				link Security, url='https://fly.io/docs/security/'
				link Privacy policy, url='https://fly.io/legal/privacy-policy'
				link Terms of service, url='https://fly.io/legal/terms-of-service'
				link Acceptable Use Policy, url='https://fly.io/legal/acceptable-use-policy'
		paragraph
			StaticText Copyright © 2024 Fly.io
```
</details>

**Reasoning for action:** By clicking the Blog link, I am directed to the page containing all articles published by Fly.io. This step is crucial as it represents the first action needed to locate the specific article titled 'AI GPU Clusters, From Your Laptop, With Livebook'. Once on the Blog page, I can further refine my search to find and access the desired article.

**Action:** click('53') # Click on the Blog link to view the latest articles.

**Change Description:** The browser navigated from the Fly.io homepage to the Fly Blog, where the content now displays a list of articles under the heading 'The Fly Blog' instead of the previous homepage content. The link representing the Blog in the navigation menu was activated, and the main content area now shows featured blog posts with associated details, images, and links to read more.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://fly.io/blog/

https://fly.io/blog/ai-gpu-clusters-from-your-laptop-livebook/

**Content (before/after):** 

```
RootWebArea The Fly Blog, focused, url='https://fly.io/blog/'
	banner
		navigation Logo menu
			[50] link Fly App performance optimization, center=(312,48), url='https://fly.io/'
				image Fly App performance optimization
```
<details><summary>Show more</summary>

```
			[53] link Blog, center=(356,48), url='https://fly.io/blog/'
				image Blog
		[57] link Need a Logo? View Our Brand Assets, center=(388,112), inner_text=Need a Logo?
View Our Brand Assets, url='https://fly.io/docs/about/brand/'
			strong
			image
		navigation Main menu
			DescriptionList
				[69] term, center=(730,48), inner_text=Articles
					StaticText Articles
				definition
					link Blog, url='https://fly.io/blog/'
					link Phoenix Files, url='https://fly.io/phoenix-files/'
					link Laravel Bytes, url='https://fly.io/laravel-bytes/'
					link Ruby Dispatch, url='https://fly.io/ruby-dispatch/'
					link Django Beats, url='https://fly.io/django-beats/'
					link JavaScript Journal, url='https://fly.io/javascript-journal/'
			[78] link Security, center=(808,48), url='https://fly.io/security/'
			[79] link Infra Log, center=(890,48), url='https://fly.io/infra-log/'
			[80] link Docs, center=(960,48), url='https://fly.io/docs/'
			[81] link Community, center=(1039,48), url='https://community.fly.io/'
			[82] link Status, center=(1124,48), url='https://status.flyio.net/'
			[83] link Pricing, center=(1193,48), url='https://fly.io/pricing/'
			[85] link Sign In, center=(1435,48), url='https://fly.io/app/sign-in'
			[86] link Get Started, center=(1536,48), url='https://fly.io/docs/hands-on/start/'
			[87] link RSS Feed, center=(1619,48), url='https://fly.io/blog/feed.xml'
				image
	main
		image, url='https://fly.io/static/images/blog-cover.webp'
		article
			StaticText BY CHRIS MCCORD & JOSÉ VALIM
			StaticText 8 MIN READ
			heading AI GPU Clusters, From Your Laptop, With Livebook
			paragraph
				StaticText Let’s begin by introducing our cast of characters. Livebook is usually described as Elixir’s answer to Jupyter Notebooks. And that’s a good way to think about it. But Livebook takes full advantage of the Elixir platform, which makes it sneakily powe
			paragraph
				StaticText Read more
				StaticText →
			[128] link Read more, center=(960,373), url='https://fly.io/blog/ai-gpu-clusters-from-your-laptop-livebook/'
			image, url='https://fly.io/blog/ai-gpu-clusters-from-your-laptop-livebook/assets/ai-gpu-livebook-cover.webp'
		article
			image, url='https://fly.io/blog/accident-forgiveness/assets/money-for-mistakes-blog-thumb.webp'
			StaticText BY THOMAS PTACEK
			StaticText 8 MIN READ
			heading Accident Forgiveness
			paragraph
				StaticText Public cloud billing is terrifying. The premise of a public cloud — what sets it apart from a hosting provider — is 8,760 hours/year of on-tap deployable compute, storage, and networking. Cloud resources are “elastic”: they’re acquired and released
			[143] link Read more, center=(508,945), url='https://fly.io/blog/accident-forgiveness/'
		article
			image, url='https://fly.io/blog/cutting-prices-for-l40s-gpus-in-half/assets/gpu-ga-thumb.webp'
			StaticText BY KURT MACKEY
			StaticText 6 MIN READ
			heading We're Cutting L40S Prices In Half
			paragraph
				StaticText We just lowered the prices on NVIDIA L40s GPUs to $1.25 per hour. Why? Because our feet are cold and we burn processor cycles for heat. But also other reasons. Let’s back up. We offer 4 different NVIDIA GPU models; in increasing order of performanc
			[155] link Read more, center=(960,945), url='https://fly.io/blog/cutting-prices-for-l40s-gpus-in-half/'
		article
			image, url='https://fly.io/blog/machine-migrations/assets/migrations-thumb.webp'
			StaticText BY THOMAS PTACEK
			StaticText 18 MIN READ
			heading Making Machines Move
			paragraph
				StaticText At the heart of our platform is a systems design tradeoff about durable storage for applications. When we added storage three years ago, to support stateful apps, we built it on attached NVMe drives. A benefit: a Fly App accessing a file on a Fly Vo
			[167] link Read more, center=(1412,945), url='https://fly.io/blog/machine-migrations/'
		article
			image, url='https://fly.io/blog/oidc-cloud-roles/assets/spooky-security-skeleton-thumb.webp'
			StaticText BY MOSS LILLEY
			StaticText 10 MIN READ
			heading AWS without Access Keys
			paragraph
				StaticText Let’s hypopulate you an app serving generative AI cat images based on the weather forecast, running on a g4dn.xlarge ECS task in AWS us-east-1. It’s going great; people didn’t realize how dependent their cat pic prefs are on barometric pressure, and
			link Read more, url='https://fly.io/blog/oidc-cloud-roles/'
		article
			image, url='https://fly.io/blog/llm-image-description/assets/image-description-thumb.webp'
			StaticText BY NOLAN DARILEK
			StaticText 14 MIN READ
			heading Picture This: Open Source AI for Image Description
			paragraph
				StaticText Picture this, if you will. You’re blind. You’re in an unfamiliar hotel room on a trip to Chicago. If you live in Chicago IRL, imagine the hotel in Winnipeg, the Chicago of the North. You’ve absent-mindedly set your coffee down, and can’t remember w
			link Read more, url='https://fly.io/blog/llm-image-description/'
		article
			image, url='https://fly.io/blog/jit-wireguard-peers/assets/network-thumbnail.webp'
			StaticText BY LILLIAN BERRY
			StaticText 10 MIN READ
			heading JIT WireGuard
			paragraph
				StaticText One of many odd decisions we’ve made at Fly.io is how we use WireGuard. It’s not just that we use it in many places where other shops would use HTTPS and REST APIs. We’ve gone a step beyond that: every time you run flyctl, our lovable, sprawling CLI,
			link Read more, url='https://fly.io/blog/jit-wireguard-peers/'
		article
			image, url='https://fly.io/blog/fks-beta-live/assets/fks-thumb.webp'
			StaticText BY SENYO SIMPSON & JP PHILLIPS
			StaticText 8 MIN READ
			heading Fly Kubernetes does more now
			paragraph
				StaticText Fly Kubernetes is the “blessed path"™️ to using Kubernetes backed by Fly.io infrastructure. Or, in simpler terms, it is our managed Kubernetes service. We take care of the complexity of operating the Kubernetes control plane, leaving you with the unf
			link Read more, url='https://fly.io/blog/fks-beta-live/'
		article
			image, url='https://fly.io/blog/tigris-public-beta/assets/tigris-public-beta-thumb.webp'
			StaticText BY XE IASO
			StaticText 9 MIN READ
			heading Globally Distributed Object Storage with Tigris
			paragraph
				StaticText There are three hard things in computer science: Cache invalidation Naming things Doing a better job than Amazon of storing files Of all the annoying software problems that have no business being annoying, handling a file upload in a full-stack a
			link Read more, url='https://fly.io/blog/tigris-public-beta/'
		article
			image, url='https://fly.io/blog/gpu-ga/assets/gpu-ga-thumb.webp'
			StaticText BY XE IASO
			StaticText 2 MIN READ
			heading GPUs on Fly.io are available to everyone!
			paragraph
				StaticText GPUs are now available to everyone! We know you’ve been excited about wanting to use GPUs on Fly.io and we’re happy to announce that they’re available for everyone. If you want, you can spin up GPU instances with any of the following cards: Ampere
			link Read more, url='https://fly.io/blog/gpu-ga/'
		article
			image, url='https://fly.io/blog/event-driven-machines/assets/lambdo-thumb.webp'
			StaticText BY CHRIS FIDAO
			StaticText 6 MIN READ
			heading Event Driven Machines
			paragraph
				StaticText Serverless is great because is has good ergonomics - when an event is received, a “not-server” boots quickly, code is run, and then everything is torn down. We’re billed only on usage. It turns out that Fly.io shares many of the same ergonomics as s
			link Read more, url='https://fly.io/blog/event-driven-machines/'
		article
			image, url='https://fly.io/blog/delegate-tasks-to-fly-machines/assets/delegate-tasks-to-fly-machines-thumb.webp'
			StaticText BY ANNIE SEXTON
			StaticText 12 MIN READ
			heading Delegating tasks to Fly Machines
			paragraph
				StaticText There are many ways to delegate work in web applications, from using background workers to serverless architecture. In this article, we explore a new machine pattern that takes advantage of Fly Machines and distinct process groups to make quick work
			link Read more, url='https://fly.io/blog/delegate-tasks-to-fly-machines/'
		article
			image, url='https://fly.io/blog/macaroons-escalated-quickly/assets/evil-cookies-thumb.webp'
			StaticText BY THOMAS PTACEK
			StaticText 22 MIN READ
			heading Macaroons Escalated Quickly
			paragraph
				StaticText 1 Let’s implement an API token together. It’s a design called “Macaroons”, but don’t get hung up on that yet. First some throat-clearing. Then: Wrap text Copy to clipboard import sys impor
			link Read more, url='https://fly.io/blog/macaroons-escalated-quickly/'
		article
			image, url='https://fly.io/blog/how-i-fly-yoko-li/assets/chat-bird-cover-thumb.webp'
			StaticText BY XE IASO
			StaticText 12 MIN READ
			heading How Yoko Li makes towns, tamagoes, and tools for local AI
			paragraph
				StaticText Hello all, and welcome to another episode of How I Fly, a series where I interview developers about what they do with technology, what they find exciting, and the unexpected things they’ve learned along the way. This time I’m talking with Yoko Li, an
			link Read more, url='https://fly.io/blog/how-i-fly-yoko-li/'
		article
			image, url='https://fly.io/blog/not-midjourney-bot/assets/purple-balloon-taking-off-thumb.webp'
			StaticText BY KYLE MCLAREN
			StaticText 15 MIN READ
			heading Deploy Your Own (Not) Midjourney Bot on Fly GPUs
			paragraph
				StaticText Some people daydream about normal things, like coffee machines or raising that Series A round (those are normal things to dream about, right?). I daydream about commanding a fleet of chonky NVIDIA Lovelace L40Ss. Also, totally normal. Well, fortunate
			link Read more, url='https://fly.io/blog/not-midjourney-bot/'
		article
			image, url='https://fly.io/blog/fly-with-alpine/assets/fly-with-alpine-thumb.webp'
			StaticText BY SAM RUBY
			StaticText 6 MIN READ
			heading Fly With Alpine
			paragraph
				StaticText Before proceeding, a caution. This is an engineering trade-off. Test carefully before deploying to production. By the end of this blog post you should have the information you need to make an informed decision. Introduction Alpine Linux is a Linux
			link Read more, url='https://fly.io/blog/fly-with-alpine/'
		article
			image, url='https://fly.io/blog/fks/assets/fks-thumb.webp'
			StaticText BY SENYO SIMPSON
			StaticText 10 MIN READ
			heading Introducing Fly Kubernetes
			paragraph
				StaticText Update, March 2024: FKS does more stuff now, and you can read about it in Fly Kubernetes does more now We’ll own it: we’ve been snarky about Kubernetes. We are, at heart, old-school Unix nerds. We’re still scandalized by systemd. To make matters mor
			link Read more, url='https://fly.io/blog/fks/'
		article
			image, url='https://fly.io/blog/fly-io-has-gpus-now/assets/llama-portal-thumb.webp'
			StaticText BY XE IASO
			StaticText 7 MIN READ
			heading Fly.io has GPUs now
			paragraph
				StaticText AI is pretty fly AI is apparently a bit of a thing (maybe even an thing come to think about it). We’ve seen entire industries get transformed in the wake of ChatGPT existing (somehow it’s only been around for a year, I can’t believe it either). It’s l
			link Read more, url='https://fly.io/blog/fly-io-has-gpus-now/'
		article
			image, url='https://fly.io/blog/what-are-these-gpus-really/assets/gpu-songstress-thumb.webp'
			StaticText BY XE IASO
			StaticText 14 MIN READ
			heading What are these "GPUs" really?
			paragraph
				StaticText GPU hardware will let our users run all sorts of fun Artificial Intelligence and Machine Learning (AI/ML) workloads near their users. But, what are these “GPUs” really? What can they do? What can’t they do? Listen here for my tale of woe as I spell
			link Read more, url='https://fly.io/blog/what-are-these-gpus-really/'
		article
			image, url='https://fly.io/blog/scaling-llm-ollama/assets/thumb.webp'
			StaticText BY XE IASO
			StaticText 12 MIN READ
			heading Scaling Large Language Models to zero with Ollama
			paragraph
				StaticText Open-source self-hosted AI tools have advanced a lot in the past 6 months. They allow you to create new methods of expression (with QR code generation and Stable Diffusion), easy access to summarization powers that would have made Google blush a deca
			link Read more, url='https://fly.io/blog/scaling-llm-ollama/'
		article
			image, url='https://fly.io/blog/rethinking-serverless-with-flame/assets/flame-thumb.webp'
			StaticText BY CHRIS MCCORD
			StaticText 19 MIN READ
			heading Rethinking Serverless with FLAME
			paragraph
				StaticText Imagine if you could auto scale simply by wrapping any existing app code in a function and have that block of code run in a temporary copy of your app. The pursuit of elastic, auto-scaling applications has taken us to silly places. Serverless/FaaS
			link Read more, url='https://fly.io/blog/rethinking-serverless-with-flame/'
		article
			image, url='https://fly.io/blog/the-risks-of-building-apps-on-chatgpt/assets/risks-building-on-chatgpt-thumb.webp'
			StaticText BY MARK ERICKSEN
			StaticText 15 MIN READ
			heading The risks of building apps on ChatGPT
			paragraph
				StaticText The topic of “AI” gets a lot of attention and press. Coverage ranges from apocalyptic warnings to Utopian predictions. The truth, as always, is likely somewhere in the middle. As developers, we are the ones that either imagine ways that AI can be use
			link Read more, url='https://fly.io/blog/the-risks-of-building-apps-on-chatgpt/'
		article
			image, url='https://fly.io/blog/print-on-demand/assets/print-on-demand-thumb.webp'
			StaticText BY SAM RUBY
			StaticText 6 MIN READ
			heading Print on Demand
			paragraph
				StaticText Scaling discussions often lead to recommendations to add more memory, more CPU, more machines, more regions, more, more, more. This post is different. It focuses instead on the idea of decomposing parts of your applications into event handlers, sta
			link Read more, url='https://fly.io/blog/print-on-demand/'
		article
			image, url='https://fly.io/blog/new-launch/assets/thumb.webp'
			StaticText BY XE IASO
			StaticText 2 MIN READ
			heading Launching to Victory
			paragraph
				StaticText Previously when you ran fly launch, you got asked a bunch of hopefully relevant questions to help you get your app up and running. We’ve taken a lot of the guesswork out of the process and made it a lot more streamlined. It turns out that even though
			link Read more, url='https://fly.io/blog/new-launch/'
		article
			image, url='https://fly.io/blog/how-i-fly/assets/thumb.webp'
			StaticText BY XE IASO
			StaticText 6 MIN READ
			heading How I Fly
			paragraph
				StaticText I’m Xe Iaso. I’m a writer, technical educator, and philosopher who focuses on making technology easy to understand and scale to your needs. I use Fly.io to host my website and in nearly all of my personal projects now. Fly.io allows me to experiment
			link Read more, url='https://fly.io/blog/how-i-fly/'
		article
			image, url='https://fly.io/blog/transcribing-on-fly-gpu-machines/assets/whispering-thumb.webp'
			StaticText BY CHRIS FIDAO
			StaticText 9 MIN READ
			heading Transcribing on Fly GPU Machines
			paragraph
				StaticText Fly.io has GPU Machines, which means we can finally run AI workloads with just a few API calls. This is exciting!
			link Read more, url='https://fly.io/blog/transcribing-on-fly-gpu-machines/'
		article
			image, url='https://fly.io/blog/skip-the-api/assets/skip-the-api-thumb.webp'
			StaticText BY BEN JOHNSON
			StaticText 6 MIN READ
			heading Skip the API, Ship Your Database
			paragraph
				StaticText My favorite part about building tools is discovering their unintended uses. It’s like starting to write a murder mystery book but you have no idea who the killer is! History is filled with examples of these accidental discoveries: WD-40 was original
			link Read more, url='https://fly.io/blog/skip-the-api/'
		article
			image, url='https://fly.io/blog/sentry-partnership/assets/sentry-thumb.webp'
			StaticText BY JOSHUA SIERLES
			StaticText 3 MIN READ
			heading Automated Sentry Error Tracking
			paragraph
				StaticText We’ve been using Sentry since the dawn of the internet. Or at least as far back as the discovery of the Higgs boson. Project to project, the familiar Sentry issue detail screen has been our faithful debugging companion. Today it’s no exception: All
			link Read more, url='https://fly.io/blog/sentry-partnership/'
		article
			image, url='https://fly.io/blog/tracking-consistency-with-litefs/assets/tracking-consistency-thumb.webp'
			StaticText BY BEN JOHNSON
			StaticText 8 MIN READ
			heading Tracking Application-Level Consistency with LiteFS
			paragraph
				StaticText When we started the LiteFS project a year ago, we started more with an ideal in mind rather than a specific implementation. We wanted to make it possible to not only run distributed SQLite but we also wanted to make it… gasp… easy! There were hurdle
			link Read more, url='https://fly.io/blog/tracking-consistency-with-litefs/'
		article
			image, url='https://fly.io/blog/redundant-logs/assets/lergs-thumb.webp'
			StaticText BY SAM RUBY
			StaticText 5 MIN READ
			heading Multiple Logs for Resiliency
			paragraph
				StaticText You’ve done everything right. You are well aware of Murphy’s Law. You have multiple redundant machines. You’ve set up a regular back up schedule for your database, perhaps even are using LiteFS CLoud. You ship your logs to LogTail or perhaps some o
			link Read more, url='https://fly.io/blog/redundant-logs/'
		article
			image, url='https://fly.io/blog/tokenized-tokens/assets/ghosts.png'
			StaticText BY BEN TOEWS
			StaticText 10 MIN READ
			heading Tokenized Tokens
			paragraph
				StaticText We built some little security thingies. We’re open sourcing them, and hoping you like them as much as we do. In a nutshell: it’s a proxy that injects secrets into arbitrary 3rd-party API calls. We could describe it more completely here, but that woul
			link Read more, url='https://fly.io/blog/tokenized-tokens/'
		article
			image, url='https://fly.io/blog/flydotio-heart-bun/assets/flydotio-heart-bun-thumb.webp'
			StaticText BY SAM RUBY
			StaticText 2 MIN READ
			heading Fly.io ❤️ Bun
			paragraph
				StaticText Bun 1.0 comes out September 7th. Fly.io is making preparations. Previously, we stated that Fly.io ❤️ JS, and we understandably started with Node.js. While that work is ongoing, it makes sense to start expanding to other runtimes. Bun is the obvio
			link Read more, url='https://fly.io/blog/flydotio-heart-bun/'
		article
			image, url='https://fly.io/blog/litefs-cloud/assets/litefs-cloud-thumb.webp'
			StaticText BY DARLA MAGDALENE SHOCKLEY & BEN JOHNSON
			StaticText 9 MIN READ
			heading LiteFS Cloud: Distributed SQLite with Managed Backups
			paragraph
				StaticText We love SQLite in production, and we’re all about running apps close to users. That’s why we created LiteFS: an open source distributed SQLite database that lives on the same filesystem as your application, and replicates data to all the nodes in you
			link Read more, url='https://fly.io/blog/litefs-cloud/'
		article
			image, url='https://fly.io/blog/we-raised-a-bunch-of-money/assets/fundraising-thumbnail.png'
			StaticText BY KURT MACKEY
			StaticText 6 MIN READ
			heading We Raised A Bunch Of Money
			paragraph
				StaticText This past July, we raised $25MM from A16Z and our existing investors, including Intel Capital and Dell. Recently, we raised an additional $70MM led by EQT Ventures. Why do startups write announcements like these? We went back and forth on it. There a
			link Read more, url='https://fly.io/blog/we-raised-a-bunch-of-money/'
		article
			image, url='https://fly.io/blog/python-async-workers-on-fly-machines/assets/python-async-workers-on-fly-machines-thumbnail.webp'
			StaticText BY DARLA MAGDALENE SHOCKLEY
			StaticText 10 MIN READ
			heading Python Async Workers on Fly Machines
			paragraph
				StaticText Last year, while working in what was my day job at the time (before I joined Fly.io!), we had just developed a new internal tool to help an adjacent team with their work. This adjacent team wrote technical content, and they had a lot of issues stemmi
			link Read more, url='https://fly.io/blog/python-async-workers-on-fly-machines/'
		article
			image, url='https://fly.io/blog/vanilla-candy-sprinkles/assets/vanilla-candy-sprinkles-thumb.webp'
			StaticText BY SAM RUBY
			StaticText 11 MIN READ
			heading Vanilla with Candy Sprinkles
			paragraph
				StaticText Recapping where we are to date: There are plenty of JavaScript frameworks to choose from, and fly.io loves them all. Pretty much all of the big name frameworks are delightfully weird. Picking up where we left off, this blog post will describe lite
			link Read more, url='https://fly.io/blog/vanilla-candy-sprinkles/'
		article
			image, url='https://fly.io/blog/how-to-fly-replay/assets/replay-router-thumb.webp'
			StaticText BY CHRIS FIDAO
			StaticText 7 MIN READ
			heading Playing Traffic Cop with Fly-Replay
			paragraph
				StaticText The Fly Replay header is deceptively simple. All your app has to do is respond with a header, and the HTTP request gets re-ran somewhere else. It’s behind-the-scenes of some pretty interesting apps on Fly.io (we wrote about using it with Globally Di
			link Read more, url='https://fly.io/blog/how-to-fly-replay/'
		article
			image, url='https://fly.io/blog/js-ecosystem-delightfully-wierd/assets/js-weird-cover.webp'
			StaticText BY SAM RUBY
			StaticText 7 MIN READ
			heading The JavaScript Ecosystem is Delightfully Weird
			paragraph
				StaticText Note, I’m not saying that JavaScript is weird, though it definitely is weird. But that’s not the point of this blog post. Bear with me, instead of starting with how JavaScript ecosystem is weird, I’m going to start with why the JavaScript ecosystem
			link Read more, url='https://fly.io/blog/js-ecosystem-delightfully-wierd/'
		article
			image, url='https://fly.io/blog/deploying-langchain-to-fly-io/assets/deploying-langchain-to-fly-io-thumbnail.webp'
			StaticText BY KÁTIA NAKAMURA
			StaticText 14 MIN READ
			heading Deploying LangChain to Fly.io
			paragraph
				StaticText I hear about Large Language Models (LLM) everywhere these days! Do you? 🤔 LLMs are a type of natural language processing (NLP) technology that uses advanced deep learning techniques to generate human-like language. If you haven’t heard about LLMs, y
			link Read more, url='https://fly.io/blog/deploying-langchain-to-fly-io/'
		article
			image, url='https://fly.io/blog/flydotio-heart-js/assets/flydotio-heart-js-thumb.webp'
			StaticText BY SAM RUBY
			StaticText 6 MIN READ
			heading Fly.io ❤️ JS
			paragraph
				StaticText Fly.io is a great place to run fullstack applications. For most programming languages, there is a defacto default fullstack framework. For Ruby, there is Rails. For Elixir, there is Phoenix. For PHP there is Laravel. For Python, there is Django.
			link Read more, url='https://fly.io/blog/flydotio-heart-js/'
		article
			image, url='https://fly.io/blog/gossip-glomers/assets/gossip-glomers-thumbnail.webp'
			StaticText BY BEN JOHNSON
			StaticText 5 MIN READ
			heading Gossip Glomers
			paragraph
				StaticText In the field of computer science, the industry is represented by two separate yet equally important groups: the software developers who build Rails applications and mobile games, and the academics who write theory papers about why the problems those
			link Read more, url='https://fly.io/blog/gossip-glomers/'
		article
			image, url='https://fly.io/blog/shipping-logs/assets/slinging-logs-in-nats-thumbnail.webp'
			StaticText BY CHRIS FIDAO
			StaticText 5 MIN READ
			heading Shipping Logs
			paragraph
				StaticText Nearly all of our apps are puking output. Sometimes, it’s intentional. Often this output is in the form of structured logs. Logs are helpful for a variety of use cases - debugging, tracking, collating, correlating, coalescing, and condensing the ha
			link Read more, url='https://fly.io/blog/shipping-logs/'
		article
			image, url='https://fly.io/blog/carving-the-scheduler-out-of-our-orchestrator/assets/starry-containers-thumbnail.webp'
			StaticText BY THOMAS PTACEK
			StaticText 26 MIN READ
			heading Carving The Scheduler Out Of Our Orchestrator
			paragraph
				StaticText So, you want to build an app to rate sandwiches. Well, the world has a lot of different sandwiches. Pit beefs in Baltimore, Tonkatsu sandos in Shinjuku, and Cemitas in Puebla. You want real-time sandwich telemetry, no matter the longitude of the sand
			link Read more, url='https://fly.io/blog/carving-the-scheduler-out-of-our-orchestrator/'
		article
			image, url='https://fly.io/blog/fly-in-johannesburg/assets/jnb-kota-thumbnail.webp'
			StaticText BY CHRIS NICOLL
			StaticText <1 MIN READ
			heading Fly.io is in Johannesburg
			paragraph
				StaticText Did you know that we’re in Johannesburg? There’s rugby and cricket. Hearty kota and Gatsby sandwiches. Braii under sunny skies and low-latency full-stack apps. Front end, Postgres, Redis, the works: if your users support the Springboks and Banyana Ba
			link Read more, url='https://fly.io/blog/fly-in-johannesburg/'
		article
			image, url='https://fly.io/blog/wal-mode-in-litefs/assets/wal-mode-thumbnail.webp'
			StaticText BY BEN JOHNSON
			StaticText 11 MIN READ
			heading WAL Mode in LiteFS
			paragraph
				StaticText By and large, SQLite is configuration-free. You can get pretty far by just using the default settings. As your application grows and you start tweaking settings, one of the first knobs you’ll come across is the journal mode. This setting determines h
			link Read more, url='https://fly.io/blog/wal-mode-in-litefs/'
		article
			image, url='https://fly.io/blog/launching-redis-by-upstash/assets/love-thumbnail.webp'
			StaticText BY JOSHUA SIERLES
			StaticText 11 MIN READ
			heading Launching Redis by Upstash
			paragraph
				StaticText We love databases that scale globally. As an ambivalent database provider, we built a global, automated Postgres, and we tinkered with global Redis on scrappy startup weekends. But the Fly.io forecast called for integration over invention. So we part
			link Read more, url='https://fly.io/blog/launching-redis-by-upstash/'
		article
			image, url='https://fly.io/blog/logbook-november-14-to-december-5-2022/assets/logbook-default2-thumbnail.webp'
			StaticText BY BRAD GESSLER
			StaticText 2 MIN READ
			heading Logbook: November 14 to December 5, 2022
			paragraph
				StaticText Build real-time applications on any backend with Replicache and Fly, run Cron on Fly, two LiveWire how-tos, and learn how Fly reluctantly built its Postgres database service. Ok, it’s been longer than a week since the last update because a lot of us
			link Read more, url='https://fly.io/blog/logbook-november-14-to-december-5-2022/'
		article
			image, url='https://fly.io/blog/how-we-built-fly-postgres/assets/keepers-proxies-thumbnail.webp'
			StaticText BY CHRIS NICOLL & SHAUN DAVIS
			StaticText 18 MIN READ
			heading How We Built Fly Postgres
			paragraph
				StaticText Fly.io is an ambivalent database provider—one might even use the word “reluctant”. The reasons for that are interesting, as is the way Fly Postgres works. When we relate this in conversations online, people are often surprised. So we thought we’d tak
			link Read more, url='https://fly.io/blog/how-we-built-fly-postgres/'
		article
			image, url='https://fly.io/blog/replicache-machines-demo/assets/network-thumbnail.webp'
			StaticText BY DOV ALPERIN
			StaticText 8 MIN READ
			heading Real-Time Collaboration with Replicache and Fly-Replay
			paragraph
				StaticText Imagine this: you have invented the best design tool since Figma. But before you can compete with the design-industry heavyweight, you need to be able to compete on one of Figma’s main propositions: real-time collaboration. You do some research and f
			link Read more, url='https://fly.io/blog/replicache-machines-demo/'
		article
			image, url='https://fly.io/blog/logbook-november-7-to-november-14-2022/assets/logbook-thumbnail.webp'
			StaticText BY BRAD GESSLER
			StaticText 2 MIN READ
			heading Logbook: November 7 to November 14, 2022
			paragraph
				StaticText Automatically deploy Elixir apps to production with Github Actions CI and troubleshoot performance issues with OpenTelemetry. Help the Python community draft Django docs. Deploy S3-compatible object storage close to your Fly apps. Last week we got im
			link Read more, url='https://fly.io/blog/logbook-november-7-to-november-14-2022/'
		article
			image, url='https://fly.io/blog/logbook-october-29-to-november-6-2022/assets/logbook-default3-thumbnail.webp'
			StaticText BY BRAD GESSLER
			StaticText 2 MIN READ
			heading Logbook: October 29 to November 6, 2022
			paragraph
				StaticText This week Redis gets some power-ups, Elixir confesses its love for React, Fly gets real about Postgres, Livewire gifts us with a few tutorials, and a many of us in North America didn’t have to change the clocks around our house because we convinced ou
			link Read more, url='https://fly.io/blog/logbook-october-29-to-november-6-2022/'
		article
			image, url='https://fly.io/blog/love-letter-react/assets/desktop-thumbnail.webp'
			StaticText BY CHRIS MCCORD
			StaticText 13 MIN READ
			heading A love letter to React
			paragraph
				StaticText It’s hard to overstate the impact React has had since its release in 2013. For me, React came with a few revelations. First was a reactive HTML-aware component model for building UIs. Second was colocated markup directly in the app code. Third, it fo
			link Read more, url='https://fly.io/blog/love-letter-react/'
		article
			image, url='https://fly.io/blog/logbook-october-21-to-28-2022/assets/logbook-default2-thumbnail.webp'
			StaticText BY BRAD GESSLER
			StaticText 3 MIN READ
			heading Logbook: October 21 to 28, 2022
			paragraph
				StaticText Postgres docs improvements First up, some new documentation was created to run people through how to fail over a Postgres database. Performing a Failover Performing a Regional Failover “Getting Started” was updated to show how to setup a Postgres
			link Read more, url='https://fly.io/blog/logbook-october-21-to-28-2022/'
		article
			image, url='https://fly.io/blog/introducing-litefs/assets/litefs-thumbnail.webp'
			StaticText BY BEN JOHNSON
			StaticText 12 MIN READ
			heading Introducing LiteFS
			paragraph
				StaticText Full-stack developers are sleeping on SQLite, a database most devs think more suited to unit tests than production loads. That’s true enough for some apps. Most web apps are read-heavy, though, and we can use that to our advantage. With the right too
			link Read more, url='https://fly.io/blog/introducing-litefs/'
		article
			image, url='https://fly.io/blog/scale-to-zero-minecraft/assets/mc-thumbnail.webp'
			StaticText BY DOV ALPERIN
			StaticText 8 MIN READ
			heading Scale-to-Zero Minecraft server with Terraform and Fly Machines
			paragraph
				StaticText Running a Minecraft server for friends has become an archetypal first foray into the workings of the Internet. For some it’s learning to expose the tender underbelly of a home network to outside connections. For others it’s exploring the world of VMs
			link Read more, url='https://fly.io/blog/scale-to-zero-minecraft/'
		article
			image, url='https://fly.io/blog/sqlite-virtual-machine/assets/vm-thumbnail.webp'
			StaticText BY BEN JOHNSON
			StaticText 15 MIN READ
			heading How the SQLite Virtual Machine Works
			paragraph
				StaticText SQL is a weird concept. You write your application in one language, say JavaScript, and then send commands in a completely different language, called SQL, to the database. The database then compiles and optimizes that SQL command, runs it, and return
			link Read more, url='https://fly.io/blog/sqlite-virtual-machine/'
		article
			image, url='https://fly.io/blog/sqlite-internals-wal/assets/internals-thumbnail.webp'
			StaticText BY BEN JOHNSON
			StaticText 14 MIN READ
			heading How SQLite Scales Read Concurrency
			paragraph
				StaticText If you scour Hacker News & Reddit for advice about databases, some common words of caution are that SQLite doesn’t scale or that it is a single-user database and it’s not appropriate for your web-scale application. Like any folklore, it has some his
			link Read more, url='https://fly.io/blog/sqlite-internals-wal/'
		article
			image, url='https://fly.io/blog/remote-ide-machines/assets/ide-the-hard-way-thumbnail.webp'
			StaticText BY LUBIEN & CHRIS NICOLL
			StaticText 22 MIN READ
			heading Building an In-Browser IDE the Hard Way
			paragraph
				StaticText “Remote development environment!” Whether you reacted with a thrill of enthusiasm, a surge of derision or a waft of indifference, we’re not really here to change your mind. That phrase means a lot of different things at this point in history. The m
			link Read more, url='https://fly.io/blog/remote-ide-machines/'
		article
			image, url='https://fly.io/blog/sqlite-internals-rollback-journal/assets/rollback-journal-thumbnail.webp'
			StaticText BY BEN JOHNSON
			StaticText 14 MIN READ
			heading How SQLite helps you do ACID
			paragraph
				StaticText When database vendors recite their long list of features, they never enumerate “doesn’t lose your data” as one of those features. It’s just assumed. That’s what a database is supposed to do. However, in reality, the best database vendors tell you exa
			link Read more, url='https://fly.io/blog/sqlite-internals-rollback-journal/'
		article
			image, url='https://fly.io/blog/volumes-expand-restore/assets/snapshot-restore-thumbnail.webp'
			StaticText BY CHRIS NICOLL
			StaticText 2 MIN READ
			heading Volume Expansion and Snapshot Restores
			paragraph
				StaticText Fly Volumes are the persistent storage that makes it possible to run full stack apps entirely on the Fly.io platform, keeping your configuration, session or user data in place across deployments. Looking at them from another angle, volumes are space
			link Read more, url='https://fly.io/blog/volumes-expand-restore/'
		article
			image, url='https://fly.io/blog/sqlite-internals-btree/assets/sqlite-thumbnail.webp'
			StaticText BY BEN JOHNSON
			StaticText 14 MIN READ
			heading SQLite Internals: Pages & B-trees
			paragraph
				StaticText Ok, I’ll admit it—I’m a SQLite shill. There are few holes that I don’t try to put a SQLite-shaped peg into. It’s not that I dislike other databases, they’re great. But SQLite is so easy to use and, more importantly, it’s simple. Simplicity leads to r
			link Read more, url='https://fly.io/blog/sqlite-internals-btree/'
		article
			image, url='https://fly.io/blog/launching-laravel-bytes/assets/laravel-announcement-thumbnail.webp'
			StaticText BY CHRIS FIDAO
			StaticText 1 MIN READ
			heading Launching Laravel Bytes
			paragraph
				StaticText Today we’re launching Laravel Bytes - our new home for anything Laravel. We’re excited to support deploying Laravel across the globe - and we have lots to talk about! We’ve already made it easy to run Laravel on Fly, but with the possibilities unlo
			link Read more, url='https://fly.io/blog/launching-laravel-bytes/'
		article
			image, url='https://fly.io/blog/liveview-its-alive/assets/phoenix-birth-thumbnail.webp'
			StaticText BY CHRIS MCCORD
			StaticText 18 MIN READ
			heading How LiveView Took on a Life of Its Own
			paragraph
				StaticText LiveView started with a simple itch. I wanted to write dynamic server-rendered applications without writing JavaScript. Think realtime validations on forms, or updating the quantity in a shopping cart. The server would do the work, with the client re
			link Read more, url='https://fly.io/blog/liveview-its-alive/'
		article
			image, url='https://fly.io/blog/logbook-2022-07-18/assets/logbook-default2.webp'
			StaticText BY THE FLY.IO BALLOON
			StaticText 7 MIN READ
			heading Logbook - 2022-07-18
			paragraph
				StaticText We have some real gems in this edition. Have you ever wished you could grow the storage volume on a Fly.io app? Now you can!! What about this one: Ever wished that the $99 Pro Plan would include $99 of usage credits? OK, that one may have been a li
			link Read more, url='https://fly.io/blog/logbook-2022-07-18/'
		article
			image, url='https://fly.io/blog/soc2-the-screenshots-will-continue-until-security-improves/assets/soc2-thumbnail.webp'
			StaticText BY THOMAS PTACEK
			StaticText 25 MIN READ
			heading SOC2: The Screenshots Will Continue Until Security Improves
			paragraph
				StaticText If you’re off getting your app up and running on Fly.io and finding your checkbook, great! I won’t get in your way. The rest of you, though, I want to talk to you about what SOC2 is and how it works. Spoiler: the SOC2 Starting Seven post held up pret
			link Read more, url='https://fly.io/blog/soc2-the-screenshots-will-continue-until-security-improves/'
		article
			image, url='https://fly.io/blog/the-serverless-server/assets/not-a-server-thumbnail.webp'
			StaticText BY WILL JORDAN
			StaticText 20 MIN READ
			heading The Serverless Server
			paragraph
				StaticText Fly.io isn’t a “Gartner Magic Quadrant” kind of company. We use terms like “FaaS” and “PaaS” and “serverless”, but mostly to dunk on them. It’s just not how we think about things. But the rest of the world absolutely does think this way, and I want t
			link Read more, url='https://fly.io/blog/the-serverless-server/'
		article
			image, url='https://fly.io/blog/logbook-2022-06-23/assets/logbook-default-thumbnail.webp'
			StaticText BY THE FLY.IO BALLOON
			StaticText 6 MIN READ
			heading Logbook - 2022-06-23
			paragraph
				StaticText We’ve had a lot of changelogs about our Phoenix/LiveView-based web UI in recent weeks. It’s pretty rad; we’ve been vocal about being CLI-first, but we love a first-class dashboard. Our dashboard has sprouted a lot of new capabilities, and at this poi
			link Read more, url='https://fly.io/blog/logbook-2022-06-23/'
		article
			image, url='https://fly.io/blog/rust-memory-leak/assets/fixing-leaks-thumbnail.webp'
			StaticText BY AMOS WENGER
			StaticText 24 MIN READ
			heading How to make Rust leak memory (also: how to make it stop)
			paragraph
				StaticText We have a Rust-based proxy. It was leaking memory. We fixed it, and we’ll talk about that, but to be really thorough, we’ll look at how loading a web page works. Starting with hardware interrupts. The downside of Thomas writing job postings is that t
			link Read more, url='https://fly.io/blog/rust-memory-leak/'
		article
			image, url='https://fly.io/blog/logbook-2022-06-10/assets/logbook-default3-thumbnail.webp'
			StaticText BY THE FLY.IO BALLOON
			StaticText 3 MIN READ
			heading Logbook - 2022-06-10
			paragraph
				StaticText Here’s our latest changelog. This week we’re putting the in-browser UI updates a little closer to all the other ones, to see if they’ll play nicely together. [Feature] Our WireGuard peers sync a lot faster with the kernel’s wg state, by adding only
			link Read more, url='https://fly.io/blog/logbook-2022-06-10/'
		article
			image, url='https://fly.io/blog/logbook-2022-06-01/assets/logbook-default2-thumbnail.webp'
			StaticText BY THE FLY.IO BALLOON
			StaticText 5 MIN READ
			heading Logbook - 2022-06-01
			paragraph
				StaticText Here’s our latest changelog. Looking back over the week, our forum community has been quite a driver of (logged) change. When you’re done here, head over there to be a part of it! [Feature] Created an example Node.js app to demonstrate how to expo
			link Read more, url='https://fly.io/blog/logbook-2022-06-01/'
		article
			image, url='https://fly.io/blog/logbook-2022-05-26/assets/logbook-default-thumbnail.webp'
			StaticText BY THE FLY.IO BALLOON
			StaticText 5 MIN READ
			heading Logbook - 2022-05-26
			paragraph
				StaticText Work leading up to the Fly Machines launch involved a multitude of changes by many of the cogs in this corporate machine, but that’s not to say the other production lines have been idle. For one thing, our web UI has been transforming before our eyes
			link Read more, url='https://fly.io/blog/logbook-2022-05-26/'
		article
			image, url='https://fly.io/blog/fly-machines/assets/machine-whack-a-mole-thumbnail.webp'
			StaticText BY KURT MACKEY
			StaticText 10 MIN READ
			heading Fly Machines: an API for fast-booting VMs
			paragraph
				StaticText Fly Machines are VMs with a fast REST API that can boot instances in about 300ms. Our proxy can boot Fly Machines for you, and you can shut them down when they’re idle. Which means you can cost-effectively create VMs and keep them standing by to ha
			link Read more, url='https://fly.io/blog/fly-machines/'
		article
			image, url='https://fly.io/blog/logbook-2022-05-13/assets/logbook-default-thumbnail.webp'
			StaticText BY THE FLY.IO BALLOON
			StaticText 2 MIN READ
			heading Logbook - 2022-05-13
			paragraph
				StaticText [Feature] Provisioned new servers in syd, iad, and dfw which were very full. Added capacity should mean customers should no longer get provisioning issues when trying to deploy to these regions. [Feature] The account deactivation page now asks users
			link Read more, url='https://fly.io/blog/logbook-2022-05-13/'
		article
			image, url='https://fly.io/blog/all-in-on-sqlite-litestream/assets/litestream-thumbnail.webp'
			StaticText BY BEN JOHNSON
			StaticText 15 MIN READ
			heading I'm All-In on Server-Side SQLite
			paragraph
				StaticText The conventional wisdom of full-stack applications is the n-tier architecture, which is now so common that it’s easy to forget it even has a name. It’s what you’re doing when you run an “application server” like Rails, Django, or Remix alongside a “d
			link Read more, url='https://fly.io/blog/all-in-on-sqlite-litestream/'
		article
			image, url='https://fly.io/blog/logbook-2022-05-05/assets/logbook-default3-thumbnail.webp'
			StaticText BY CHRIS NICOLL
			StaticText 5 MIN READ
			heading Logbook - 2022-05-05
			paragraph
				StaticText Features and fixes are flying like dodgeballs in a school gym, and the Fly.io Changelog Enforcer could probably have done a better job patrolling—but let’s have a look at our haul of updates since our first Logbook post. There’s a fair amount of pr
			link Read more, url='https://fly.io/blog/logbook-2022-05-05/'
		article
			image, url='https://fly.io/blog/accessibility-clearing-the-fog/assets/accessibility_02-thumbnail.webp'
			StaticText BY NOLAN DARILEK
			StaticText 10 MIN READ
			heading Accessibility and Real-time Apps: Clearing Fog and Picking Fruit
			paragraph
				StaticText Hey, everyone. Last time we talked a bit about what accessibility is, why it’s important, and how you can incorporate it into your process. Today, using the time-travel superpowers of Git, I’ll take you along as I start making LiveBeats more accessib
			link Read more, url='https://fly.io/blog/accessibility-clearing-the-fog/'
		article
			image, url='https://fly.io/blog/logbook-2022-04-20/assets/logbook-default2-thumbnail.webp'
			StaticText BY CHRIS NICOLL
			StaticText 6 MIN READ
			heading Logbook - 2022-04-20
			paragraph
				StaticText Here’s a changelog covering our most recent activity (i.e. since we started compiling updates, a bit under two weeks ago): [Feature] Added extra capacity in IAD. [Feature] Backup regions (by far our most confusing misfeature) are now disabled by de
			link Read more, url='https://fly.io/blog/logbook-2022-04-20/'
		article
			image, url='https://fly.io/blog/a-foolish-consistency/assets/default-books-thumbnail.webp'
			StaticText BY THOMAS PTACEK
			StaticText 21 MIN READ
			heading A Foolish Consistency: Consul at Fly.io
			paragraph
				StaticText We set the scene, as usual, with sandwiches. Dig if you will the picture: a global Sandwich Bracket application, ascertaining once and for all the greatest sandwich on the planet. Fly.io wants our app, sandwich-bracket, deployed close to users aroun
			link Read more, url='https://fly.io/blog/a-foolish-consistency/'
		article
			image, url='https://fly.io/blog/intro-to-accessibility/assets/accessibility-thumbnail.webp'
			StaticText BY NOLAN DARILEK
			StaticText 9 MIN READ
			heading Accessibility for real-time web apps
			paragraph
				StaticText Like every developer, I rely on a number of products and services to manage and promote my many side projects. But I’ve had more than one neat idea go down in flames because I simply couldn’t use the amazing, must-have service that would have made
			link Read more, url='https://fly.io/blog/intro-to-accessibility/'
		article
			image, url='https://fly.io/blog/our-user-mode-wireguard-year/assets/danger!-thumbnail.webp'
			StaticText BY THOMAS PTACEK
			StaticText 19 MIN READ
			heading Our User-Mode WireGuard Year
			paragraph
				StaticText WireGuard is fundamental to how Fly.io works. Along with Firecracker and Rust, it’s one of the three “interesting” technical choices we’ve made. Practically everything that talks to anything else at Fly.io does so over WireGuard. That goes for use
			link Read more, url='https://fly.io/blog/our-user-mode-wireguard-year/'
		article
			image, url='https://fly.io/blog/new-turboku/assets/turbocharge-heroku-thumbnail.webp'
			StaticText BY LUBIEN & CHRIS NICOLL
			StaticText 8 MIN READ
			heading Turbocharge your Heroku Apps with New Turboku
			paragraph
				StaticText In early 2020, before we launched our VM platform, we made a little landing page called Turboku. It was a one-click launcher to deploy a Heroku app on Fly.io. It let people try us out without spending time porting an app. Many of our first customers
			link Read more, url='https://fly.io/blog/new-turboku/'
		article
			image, url='https://fly.io/blog/livebeats/assets/livebeats-thumbnail.webp'
			StaticText BY CHRIS MCCORD
			StaticText 12 MIN READ
			heading LiveBeats: Building a social music app with Phoenix LiveView
			paragraph
				StaticText We decided that 2022 was a good year to ship a full-stack Phoenix reference app. The “full stack” metaphor has progressed beyond its humble beginnings of some REST endpoints and sprinkles of JS and CSS. Showing off a todo app is also no longer state
			link Read more, url='https://fly.io/blog/livebeats/'
		article
			image, url='https://fly.io/blog/free-postgres/assets/free-postgres-thumbnail.webp'
			StaticText BY KURT MACKEY & CHRIS NICOLL
			StaticText 4 MIN READ
			heading Free Postgres Databases
			paragraph
				StaticText We like building side projects and also hate paying for hosting for side projects. We also know that y'all like free stuff. And we think that when you use free stuff for side projects, there’s a pretty good chance you’ll pay for similar stuff for rea
			link Read more, url='https://fly.io/blog/free-postgres/'
		article
			image, url='https://fly.io/blog/self-service-account-deactivation/assets/bye-bye-bye-thumbnail.webp'
			StaticText BY LUBIEN
			StaticText 3 MIN READ
			heading Self-service account deactivation: why it’s harder than you would think
			paragraph
				StaticText We’ve just introduced a self-service UI for deleting your Fly.io account. From time to time people ask us to deactivate their account. It happens! Maybe you just tried a walkthrough out of interest, or you created a new account with a different name
			link Read more, url='https://fly.io/blog/self-service-account-deactivation/'
		article
			image, url='https://fly.io/blog/creating-the-livebook-launcher-in-liveview/assets/livebook-launcher-deploying.webp'
			StaticText BY MARK ERICKSEN
			StaticText 3 MIN READ
			heading Launching Livebook using LiveView
			paragraph
				StaticText The Livebook launcher was super fun to create. Everything happens in a single LiveView process. There was a problem though… it wasn’t great if we were in the middle of deploying the app for the user and one these things happened: User hits “refresh
			link Read more, url='https://fly.io/blog/creating-the-livebook-launcher-in-liveview/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY CHRIS MCCORD
			StaticText 3 MIN READ
			heading How Safari Ruined My Tuesday
			paragraph
				StaticText Safari 15 shipped in September 2021 and included an obscure CSS bug that broke most LiveView applications. The LiveView client operates in two modes – connected, when it can talk to the server over websockets, and disconnected when offline. When Live
			link Read more, url='https://fly.io/blog/how-safari-ruined-my-tuesday/'
		article
			image, url='https://fly.io/blog/32-bit-real-estate/assets/ipbank-thumbnail.webp'
			StaticText BY KURT MACKEY
			StaticText 18 MIN READ
			heading 32 Bit Real Estate
			paragraph
				StaticText Two obvious costs of running Internet apps for users on your own hardware: hardware and bandwidth. We buy big servers and run them in racks at network providers that charge us to route large volumes of traffic using BGP4 Anycast. You probably have at
			link Read more, url='https://fly.io/blog/32-bit-real-estate/'
		article
			image, url='https://fly.io/blog/how-we-got-to-liveview/assets/switches-thumbnail.webp'
			StaticText BY CHRIS MCCORD
			StaticText 21 MIN READ
			heading How We Got to LiveView
			paragraph
				StaticText LiveView strips away layers of abstraction, because it solves both the client and server in a single abstraction. HTTP almost entirely falls away. No more REST. No more JSON. No GraphQL APIs, controllers, serializers, or resolvers. You just write HTM
			link Read more, url='https://fly.io/blog/how-we-got-to-liveview/'
		article
			image, url='https://fly.io/blog/fly-io-is-hiring-full-stack-developers/assets/jobs-cover-01-thumbnail.webp'
			StaticText BY MICHAEL DWAN
			StaticText 6 MIN READ
			heading Fly.io Is Hiring Full-Stack Developers
			paragraph
				StaticText We’re working on super fun problems and are looking for more people to join us. In particular: we’re looking for full-stack developers. We expect this will be a good role for early-to-mid-level career developers. Some Background Fly.io’s users intera
			link Read more, url='https://fly.io/blog/fly-io-is-hiring-full-stack-developers/'
		article
			image, url='https://fly.io/blog/api-tokens-a-tedious-survey/assets/tedious-survey-thumbnail.webp'
			StaticText BY THOMAS PTACEK
			StaticText 29 MIN READ
			heading API Tokens: A Tedious Survey
			paragraph
				StaticText This is not really a post about Fly.io, though I’ll talk about us a little up front to set the scene. The last several weeks of my life have been about API security. I’m working on a new permissions system for Fly.io, and did a bunch of researc
			link Read more, url='https://fly.io/blog/api-tokens-a-tedious-survey/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY MARK ERICKSEN
			StaticText 8 MIN READ
			heading Better Business Intelligence in Elixir with Livebook
			paragraph
				StaticText As a developer, has your manager ever come and asked a question like, “How much money are we making?” If you were a line-of-business developer at a global insurance company, you’d reach for your handy, nosebleed-expensive Business Intelligence (BI) s
			link Read more, url='https://fly.io/blog/better-business-intelligence-in-elixir-with-livebook/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY MARK ERICKSEN
			StaticText 3 MIN READ
			heading FYI: Phoenix drops webpack and npm for esbuild
			paragraph
				StaticText The Phoenix Framework is the go-to web framework for Elixir developers. A recent PR was merged that replaces the use of node, npm, and webpack with esbuild. For those new to esbuild, it is written in Go so it compiles to native code and runs really f
			link Read more, url='https://fly.io/blog/phoenix-moves-to-esbuild-for-assets/'
		article
			image, url='https://fly.io/blog/last-mile-redis/assets/last-mile-redis-thumbnail.webp'
			StaticText BY KURT MACKEY
			StaticText 10 MIN READ
			heading Last Mile Redis
			paragraph
				StaticText 100 milliseconds is the magic number. For a backend application, a sub-100ms response time is effectively instantaneous, and people love using “instant” apps. Since we’re all dirty capitalists, we’d add: if people love your app, you’ll make more mone
			link Read more, url='https://fly.io/blog/last-mile-redis/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY MARK ERICKSEN
			StaticText 2 MIN READ
			heading FYI: Livebook 0.2 with Kino
			paragraph
				StaticText Livebook 0.2 was released. The big news here was the announcement of “Kino” (meaning “cinema”). It’s a client-side focused feature that animates data changes. José Valim created a video demonstrating some of the new Livebook features. Use this link to
			link Read more, url='https://fly.io/blog/livebook-with-kino/'
		article
			image, url='https://fly.io/blog/globally-distributed-postgres/assets/cats-around-the-world-thumbnail.webp'
			StaticText BY KURT MACKEY & KURT MACKEY
			StaticText 13 MIN READ
			heading Globally Distributed Postgres
			paragraph
				StaticText This is a story about a cool hack we came up with at Fly. The hack lets you do something pretty ambitious with full-stack applications. What makes it cool is that it’s easy to get your head around, and involves just a couple moving parts, assembled i
			link Read more, url='https://fly.io/blog/globally-distributed-postgres/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY ALEXANDER KOUTMOS
			StaticText 9 MIN READ
			heading Monitoring Elixir Apps on Fly.io With Prometheus and PromEx
			paragraph
				StaticText Fly.io takes Docker containers and converts them into fleets of Firecracker micro-vms running in racks around the world. If you have a working Docker container, you can run it close to your users, whether they’re in Singapore or Amsterdam, with just
			link Read more, url='https://fly.io/blog/monitoring-your-fly-io-apps-with-prometheus/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY MARK ERICKSEN
			StaticText 6 MIN READ
			heading Observing Elixir in Production
			paragraph
				StaticText Elixir, Erlang, and really just the BEAM has a feature called “Observer”. It’s fun showing it to people new to Elixir because it’s just so cool! It’s a WxWidgets graphical interface that connects in realtime to a running Erlang node and lets you “obs
			link Read more, url='https://fly.io/blog/observing-elixir-in-production/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY MARK ERICKSEN
			StaticText 7 MIN READ
			heading Livebook is a secret weapon for documentation
			paragraph
				StaticText Every application has that core, most important thing that it does. It is the reason the application exists. It’s that central idea that everything else is there to support. A major hurdle for new developers joining a project can be understanding an
			link Read more, url='https://fly.io/blog/livebook-for-app-documentation/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY THOMAS PTACEK
			StaticText 11 MIN READ
			heading Hooking Up Fly Metrics
			paragraph
				StaticText We’ve written a bit, for a general audience, about how Fly collects and manages metrics. If you’re just sort of generally interested in metrics and observability, go read that first. Meanwhile, if you’re a Fly user, or considering becoming such a us
			link Read more, url='https://fly.io/blog/hooking-up-fly-metrics/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY THOMAS PTACEK
			StaticText 13 MIN READ
			heading Fly's Prometheus Metrics
			paragraph
				StaticText We should talk a bit about metrics and measurement and stuff, because they’re how we all know what’s going on. There’s two reasons we’ve written this post. The first is just that we think this stuff is interesting, and that the world can always use
			link Read more, url='https://fly.io/blog/measuring-fly/'
		article
			image, url='https://fly.io/blog/building-a-distributed-turn-based-game-system-in-elixir/assets/elixir-game-thumbnail.webp'
			StaticText BY MARK ERICKSEN
			StaticText 8 MIN READ
			heading Building a Distributed Turn-Based Game System in Elixir
			paragraph
				StaticText One of the best things about building web applications in Elixir is LiveView, the Phoenix Framework feature that makes it easy to create live and responsive web pages without all the layers people normally build. Many great Phoenix LiveView examples
			link Read more, url='https://fly.io/blog/building-a-distributed-turn-based-game-system-in-elixir/'
		article
			image, url='https://fly.io/blog/docker-without-docker/assets/starry-containers-thumbnail.webp'
			StaticText BY THOMAS PTACEK
			StaticText 14 MIN READ
			heading Docker without Docker
			paragraph
				StaticText Even though most of our users deliver software to us as Docker containers, we don’t use Docker to run them. Docker is great, but we’re high-density multitenant, and despite strides, Docker’s isolation isn’t strong enough for that. So, instead, we tra
			link Read more, url='https://fly.io/blog/docker-without-docker/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY KURT MACKEY
			StaticText 14 MIN READ
			heading The 5-hour CDN
			paragraph
				StaticText The term “CDN” (“content delivery network”) conjures Google-scale companies managing huge racks of hardware, wrangling hundreds of gigabits per second. But CDNs are just web applications. That’s not how we tend to think of them, but that’s all they ar
			link Read more, url='https://fly.io/blog/the-5-hour-content-delivery-network/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY THOMAS PTACEK
			StaticText 12 MIN READ
			heading SSH and User-mode IP WireGuard
			paragraph
				StaticText But Fly is kind of an odd duck. We run hardware in data centers around the world, connected to the Internet via Anycast and to each other with a WireGuard mesh. We take Docker-type containers from users and transmogrify them into Firecracker micro-VM
			link Read more, url='https://fly.io/blog/ssh-and-user-mode-ip-wireguard/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY JEROME GRAVEL-NIQUET & THOMAS PTACEK & JEROME GRAVEL-NIQUET
			StaticText 12 MIN READ
			heading Persistent Storage and Fast Remote Builds
			paragraph
				StaticText If you’ve been keeping up with us at Fly, you may be picking up on a bit of a narrative with us. Fly launched, in the long-long-ago, with a somewhat narrow use case. We took containers from our customers and transmogrified them into fleets of Firecra
			link Read more, url='https://fly.io/blog/persistent-storage-and-fast-remote-builds/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY JEROME GRAVEL-NIQUET
			StaticText 5 MIN READ
			heading The Tokio Upgrade from 0.2 to 1.x
			paragraph
				StaticText At Fly.io, we run a Rust-based load-balancer which handles almost all of our traffic. It stands on the shoulders of Tokio and Hyper. When the Tokio team announced 0.3 and then 1.0, we figured we’d have to upgrade sooner than later to access related cr
			link Read more, url='https://fly.io/blog/the-tokio-1-x-upgrade/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY THOMAS PTACEK & DJ WALKER-MORGAN & THOMAS PTACEK
			StaticText 10 MIN READ
			heading You should know about Server-Side Request Forgery
			paragraph
				StaticText This is a post about the most dangerous vulnerability most web applications face, one step that we took at Fly to mitigate it, and how you can do the same. Server-side request forgery (SSRF) is application security jargon for “attackers can get you
			link Read more, url='https://fly.io/blog/practical-smokescreen-sanitizing-your-outbound-web-requests/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 4 MIN READ
			heading The January 2021 Fly ChangeLog
			paragraph
				StaticText If you missed 2020, lucky you, to get you all caught up, here’s our Previously On Fly segment. Caught up? Good. And now here is the Fly ChangeLog, covering the end of December 2020 to January 2021. 6PN Networking and IPv6 WireGuard VPNs Let your ap
			link Read more, url='https://fly.io/blog/the-january-2021-fly-changelog/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 4 MIN READ
			heading Fly In 2020 - A year in features (and articles)
			paragraph
				StaticText TL:DR; Launch, Turboku, Custom Domains, Scaling, One-Click Apps, Persistent Storage, Private Networking and WireGuard VPNs. Fly’s had an unprecedented year, along with everyone else. For us, it was bringing our Application Platform to the world, and
			link Read more, url='https://fly.io/blog/fly-in-2020/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY THOMAS PTACEK
			StaticText 16 MIN READ
			heading Building clusters with serf, my new favorite thing
			paragraph
				StaticText Assume for a second we’d like to see what happens when a web page loads in a browser in Singapore. Easy enough; Fly.io will take a container image you throw at it, transform it into a Firecracker VM, and run it in Singapore. Getting Up And Running We
			link Read more, url='https://fly.io/blog/building-clusters-with-serf/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 1 MIN READ
			heading How to build a global message service with NATS
			paragraph
				StaticText There are actually two examples that make up this example. One example is a Websocket-based chat that relays its messages through that NATS cluster. The other part is that NATS cluster, configured as a global messaging cluster that you can install in
			link Read more, url='https://fly.io/blog/how-to-build-a-global-message-service-with-nats/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 2 MIN READ
			heading Get fly with your Fly command line
			paragraph
				StaticText The command… It started off as flyctl but we kept being asked when would the command become fly. “Why not both?” we said and now, on most platforms, you can use flyctl or fly interchangeably. Boom! Three keystrokes saved! The current app… You alread
			link Read more, url='https://fly.io/blog/get-fly-with-your-fly-command-line/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY MICHAEL DWAN
			StaticText 4 MIN READ
			heading Graceful VM exits, some dials
			paragraph
				StaticText Fly apps are typically fast to boot, and it’s relatively easy to boot new VMs. We start them up, do some health checks, and then add them to our load balancer and DNS service discovery. But what comes up must go down. We shut VMs down for any number
			link Read more, url='https://fly.io/blog/graceful-vm-exits-some-dials/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY THOMAS PTACEK
			StaticText 12 MIN READ
			heading IPv6 WireGuard Peering
			paragraph
				StaticText They say that when you’re starting a product company, it’s a better plan to chase down something a bunch of people will really love a lot than it is to try to build something that everyone will just like a little bit. So when Fly.io launched, it had
			link Read more, url='https://fly.io/blog/ipv6-wireguard-peering/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY KURT MACKEY
			StaticText 5 MIN READ
			heading New VMs: more RAM, extra CPU, and a dollar menu
			paragraph
				StaticText We first showed Fly.io VMs to developers in early 2020. They were most interested in running CPU intensive apps doing image processing, machine learning predictions, and even video transcoding (despite what were, until recently, offensive bandwidth p
			link Read more, url='https://fly.io/blog/new-vms-more-ram-extra-cpu-and-a-dollar-menu/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY THOMAS PTACEK
			StaticText 6 MIN READ
			heading Incoming! 6PN Private Networks
			paragraph
				StaticText More often than not, modern applications are really ensembles of cooperating services, running independently and transacting with each other over the network. At Fly.io, we’d like it to be not just possible to express these kinds of applications, but
			link Read more, url='https://fly.io/blog/incoming-6pn-private-networks/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY KURT MACKEY
			StaticText 5 MIN READ
			heading We cut bandwidth prices. Go nuts.
			paragraph
				StaticText When we launched Fly way back in March, we charged $0.085 per GB to send data out from North America and Europe, and $0.14 per GB for Asia Pacific. Our volume has increased dramatically and pushed our unit costs down, so we lowered our prices as of D
			link Read more, url='https://fly.io/blog/we-cut-bandwidth-prices-go-nuts/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 4 MIN READ
			heading The November Fly Changelog
			paragraph
				StaticText Example Applications We’ve been focussing on getting more example applications for Fly into your hands. Each guide is complete with a walkthrough of how they were put together so you can see the power of Fly in action. Or you can hop straight to the G
			link Read more, url='https://fly.io/blog/the-november-fly-changelog/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 2 MIN READ
			heading More Appkata Examples to Try on Fly
			paragraph
				StaticText The latest additions to our Appkata collection of example apps have landed and they cover how to fit Fly to your selected applications and are some super useful apps anyway. So let’s dive in. Node-RED Ever wanted to be able to dive into your cloud ap
			link Read more, url='https://fly.io/blog/more-appkata-examples-to-try-on-fly/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 4 MIN READ
			heading Appkata - Example Apps on Fly
			paragraph
				StaticText To build a modern application, you need to know how to take down your technical challenges in style. It’s a style we call Appkata! Over the coming weeks, we’ll be sharing with you the moves you need to deploy apps onto Fly that let you build faster.
			link Read more, url='https://fly.io/blog/appkata-example-apps-on-fly/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 3 MIN READ
			heading Fly Answers Questions - Suspend, Resume, Restart and Redis
			paragraph
				StaticText Q: I’d like to park my Fly application for a little while so it isn’t consuming resources. How can I do this without destroying the application and redeploying it later? A: As you’ll have noticed, Fly applications stay running all the time ready to
			link Read more, url='https://fly.io/blog/fly-answers-questions-suspend-resume-restart-and-redis/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 2 MIN READ
			heading The October Fly Changelog: Preview Disks and DNS and Better Builtins
			paragraph
				StaticText Disks in Preview If your application needs to have persistent storage, then the currently in preview volumes feature is for you. The volumes command allows you to create persistent disks for your application. These persist between restarts, deployment
			link Read more, url='https://fly.io/blog/the-october-fly-changelog-preview-disks-and-dns-and-better-builtins/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY THOMAS PTACEK
			StaticText 18 MIN READ
			heading BPF, XDP, Packet Filters and UDP
			paragraph
				StaticText Imagine for a moment that you run a content distribution network for Docker containers. You take arbitrary applications, unmodified, and get them to run on servers close to their users around the world, knitting those servers together with WireGuard.
			link Read more, url='https://fly.io/blog/bpf-xdp-packet-filters-and-udp/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 7 MIN READ
			heading Fly Behind The Scenes: Fresh Logging
			paragraph
				StaticText Since Fly launched, we’ve been collecting and managing logs for all the applications running on the Fly platform. It’s a critical but often rarely noted function of the platform. When you type flyctl logs, behind the scenes, there is a lot of comput
			link Read more, url='https://fly.io/blog/fly-behind-the-scenes-fresh-logging/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 7 MIN READ
			heading Stuff Your Pi-Hole From Anywhere
			paragraph
				StaticText A Pi-Hole could be the hero of your web connection. It blocks advertising at the roots; the DNS roots that is. By setting up your own Pi-Hole, you can tip all your local network’s requests for known advertising domains down it. What is Pi-Hole? Thin
			link Read more, url='https://fly.io/blog/stuff-your-pi-hole-from-anywhere/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 2 MIN READ
			heading Maps, Apps, and Tracks
			paragraph
				StaticText Marathons, long and hard. Personally, I wouldn’t be caught doing one, but I’m always up to help someone who is, especially when I can use a bit of Fly to do it. Steve, our global infrastructure whiz, asked if I could think of a good way to track M
			link Read more, url='https://fly.io/blog/maps-apps-and-tracks/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 5 MIN READ
			heading The September Fly Changelog: New Names and Easier Updates
			paragraph
				StaticText Some common requests are addressed this month. One is ‘can you let us type “fly” instead of “flyctl”?’, and it is a shorter command, that is true. Another is can you ‘make updating flyctl easier?’, something we are more than happy to do. And in Septe
			link Read more, url='https://fly.io/blog/the-september-fly-changelog-new-names-and-easier-updates/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 5 MIN READ
			heading Using Heroku Postgres From A Fly App
			paragraph
				StaticText Heroku supports applications with no apps in them and only add-ons, like Postgres, as a way of providing those services to other applications. As we showed, you can access Heroku Postgres from Fly so it makes it a useful way to get yourself a databa
			link Read more, url='https://fly.io/blog/using-heroku-postgres-from-a-fly-app/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 6 MIN READ
			heading Migrating Heroku Database Apps To Fly
			paragraph
				StaticText I was recently asked how the database migration in the original Turboku demo worked. For that original demo, the migration was practically automatic. We already knew that you could access a Heroku database from outside Heroku. Since then, Changes in
			link Read more, url='https://fly.io/blog/migrating-heroku-database-apps-to-fly/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 4 MIN READ
			heading Always Be Connecting (with HTTPS)
			paragraph
				StaticText At Fly, you’ll have already discovered that when you create an app, it appears as http://appname.fly.dev and if you connect there, your browser switches automatically, by redirection, to https://appname.fly.dev. That’s how we do it for the fly.dev
			link Read more, url='https://fly.io/blog/always-be-connecting-with-https/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 4 MIN READ
			heading More Fly Answers To Questions
			paragraph
				StaticText Q: Is it ok to run non-HTTP apps on Fly? From Pier via community.fly.io A: It is, with one caveat: your applications need to have a network service of some kind. Why is that? Well, when your app deploys, we run health checks to ensure you can connec
			link Read more, url='https://fly.io/blog/more-fly-answers-to-questions/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 5 MIN READ
			heading Flyctl Builtins - The Fly Changelog for August
			paragraph
				StaticText For the latest version of flyctl, we’ve focussed on making your life fast and simple. From getting your first deployment up and running to setting up a host’s certificate. Builtins First up, we’ve got the new “builtin” builders which you can select w
			link Read more, url='https://fly.io/blog/flyctl-builtins-the-fly-changelog-for-august/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY THOMAS PTACEK
			StaticText 18 MIN READ
			heading Sandboxing and Workload Isolation
			paragraph
				StaticText Workload isolation makes it harder for a vulnerability in one service to compromise every other part of the platform. It has a long history going back to 1990s qmail, and we generally agree that it’s a good, useful thing. Despite a plethora of isola
			link Read more, url='https://fly.io/blog/sandboxing-and-workload-isolation/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 5 MIN READ
			heading Serve small with Fly.io and GoStatic
			paragraph
				StaticText Static websites are great for carrying unchanging content, be it assets, images, fonts or even, as in this case, an entire site. Well, I say entire site, but if you saw my last article, you’ll know I recently rebranded a Maker organization and needed
			link Read more, url='https://fly.io/blog/serve-small-with-fly-io-and-gostatic/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 8 MIN READ
			heading Hugo's There - Flying with Hugo and Caddy
			paragraph
				StaticText There I was wondering what to do about a website for a new community venture I was running where I thought, yes, let’s generate the site with Hugo, serve it with Caddy and run it all on Fly. Why Hugo and Caddy? Well, they both have good reputations as
			link Read more, url='https://fly.io/blog/hugo-s-there-flying-with-hugo-and-caddy/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 4 MIN READ
			heading Flyctl Evolved - Fly Changelog
			paragraph
				StaticText This flyctl release brings in some big changes in the command structure as we move to an app-centric command style. What does that mean? Well, the apps subcommand is being deprecated; we’ve kept it in place for this release but now all its commands h
			link Read more, url='https://fly.io/blog/flyctl-evolved-fly-changelog/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY KURT MACKEY
			StaticText 1 MIN READ
			heading Run Apollo Server Close to Your Users
			paragraph
				StaticText I’m a newly minted GraphQL convert. We built Fly on top of GraphQL and the experience turned me into a shameless cheerleader. An API format with static typing? That’s my jam. (If you don’t care for JAMStack puns you can just go read our guide on bui
			link Read more, url='https://fly.io/blog/run-apollo-graphql-close-to-your-users/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY THOMAS PTACEK
			StaticText 14 MIN READ
			heading How CDNs Generate Certificates
			paragraph
				StaticText It’s been a hectic first couple of weeks at Fly, and I’m writing things up as I go along, because if I have to learn, so do you. This is going to be a bit of a meander; you’ll have to deal. Let’s start with “what’s Fly?” Briefly: Fly is a content del
			link Read more, url='https://fly.io/blog/how-cdns-generate-certificates/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 5 MIN READ
			heading Flyctl meets JSON
			paragraph
				StaticText Say hello to --json or -j for short. This new flag attempts to present all output from flyctl as JSON. If a command queries the Fly GraphQL API, you’ll get the JSON data from that call in your output. If a command shows you logs, you’ll get the logs
			link Read more, url='https://fly.io/blog/flyctl-meets-json/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 3 MIN READ
			heading Fly Changelog for 9th June
			paragraph
				StaticText In this edition: a new way to install flyctl (and native Windows installers), new commands in flyctl that let you restart, list and monitor applications, an improved open command and an important update to the Deno Buildpack. Flyctl New instruction
			link Read more, url='https://fly.io/blog/fly-changelog-9th-june/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 1 MIN READ
			heading Fly Changelog for 29th May
			paragraph
				StaticText You can get the Changelog in the blog or through an RSS feed of just changelog updates available on fly.io/changelog.xml. There’s also a dedicated ChangeLog page with all the recent updates. Most of this week’s changelog items are covered in an recen
			link Read more, url='https://fly.io/blog/fly-changelog-may-29th-2020/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 2 MIN READ
			heading Fly - Now With Power Pause
			paragraph
				StaticText What’s a pause for? When you start building your applications, there may come a point where you don’t want to keep your application running - mothballing while another project happens, schedule delays, or just plain wanting to manage your costs. Tha
			link Read more, url='https://fly.io/blog/fly-now-with-power-pause/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 8 MIN READ
			heading WebSockets and Fly
			paragraph
				StaticText WebSockets are powerful things for creating interactive applications. Example Zero for WebSocket examples is the chat application. This leverages WebSockets’ ability to keep a connection alive over a long period of time while bidirectionally passing
			link Read more, url='https://fly.io/blog/websockets-and-fly/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DYLAN JHAVERI
			StaticText 4 MIN READ
			heading Mux, Fly, Wocket and RTMP
			paragraph
				StaticText Wocket (WebSocket to RTMP) This project is a proof-of-concept to demonstrate how you can stream live from your browser to an RTMP server. Streaming via RTMP is how you stream to Twitch, Youtube Live, Facebook Live, and other live streaming platforms
			link Read more, url='https://fly.io/blog/mux-fly-wocket-and-rtmp/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 1 MIN READ
			heading Fly Changelog May 15th 2020
			paragraph
				StaticText Since the last ChangeLog, we implemented a whole new scaling system with updates to the platform and flyctl. You can read all the details in the Updating Scale article. We’ve also been improving the performance of our backhaul, which moves traffice b
			link Read more, url='https://fly.io/blog/fly-changelog-may-15th-2020/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 6 MIN READ
			heading Deno on Fly
			paragraph
				StaticText We’ve been working with Deno for Fly for a while and its great blend of TypeScript, V8, Rust and simplicity makes for a great app experience. And great apps deserve a great deployment. We enjoy Deno so much that when we brought out our first cloud na
			link Read more, url='https://fly.io/blog/deno-on-fly/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 5 MIN READ
			heading Updating Scale
			paragraph
				StaticText We have been recently looking at how scaling commands work on Fly and we’ve come up with a new system with a simpler model and more compact command set to work with. We’d like to introduce it to you today. The Scaling System Previously, at least in t
			link Read more, url='https://fly.io/blog/updating-scale/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 1 MIN READ
			heading Fly Changelog 1st May 2020
			paragraph
				StaticText Since the last ChangeLog, we’ve introduced some enhancements to flyctl which make it easier to deploy tagged local and remote images directly to Fly. There is also a new load-balancing algorithm in operation which should be more effective with widely
			link Read more, url='https://fly.io/blog/fly-changelog-1st-may-2020/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 8 MIN READ
			heading Deno on Fly using Buildpacks
			paragraph
			link Read more, url='https://fly.io/blog/deno-on-fly-using-buildpacks/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 1 MIN READ
			heading Imaginary on Fly, just One-click
			paragraph
				StaticText Warning: This document is old! It is likely wrong in some important way. The folks behind Imaginary have worked with Fly and they also added the one-click launcher to their README on GitHub so that potential Imaginary users can be up, converting, res
			link Read more, url='https://fly.io/blog/imaginary-on-fly-just-one-click/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 1 MIN READ
			heading Fly Changelog 17th April 2020
			paragraph
				StaticText This past week has been one focused on the Fly infrastructure with earlier certificate renewals now in place and a dedicated Changlog page. We also made time to bring in some user contributed changes to the flyctl which make debugging fly.toml file
			link Read more, url='https://fly.io/blog/fly-changelog-17th-april-2020/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 1 MIN READ
			heading Fly Changelog 9th April 2020
			paragraph
				StaticText 7th April 2020 FlyCtl – v0.0.115 released Buildkit support. Setting environment variable DOCKER_BUILDKIT to 1 will enable use of the v2 buildkit backend which performs async parallel builds. For compatibility, DOCKER_BUILDKIT defaults to 0. The -
			link Read more, url='https://fly.io/blog/fly-changelog-9th-april-2020/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 3 MIN READ
			heading Powerbuilding with Fly
			paragraph
				StaticText Identifying your build When you deploy, the flyctl application looks for instructions to build the image in a Dockerfile or creates a builder VM to do the image build. Let’s start with the flags that control where flyctl looks for things. -c, –confi
			link Read more, url='https://fly.io/blog/powerbuilding-with-fly/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 3 MIN READ
			heading Fly Answers More Questions
			paragraph
				StaticText Q: What if I get a large number of malicious TCP connections from around the world that are malicious and cause a large number of apps to be launched in the various datacenters. Are we on the hook for the bill? And is there anything in place to stop
			link Read more, url='https://fly.io/blog/fly-answers-more-questions/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 9 MIN READ
			heading Making Datasets Fly with Datasette and Fly
			paragraph
				StaticText I’ve always liked finding a good dataset. With a background in databases and writing, I know a good dataset can bring a demo to life, be it a census of Squirrels in Central Park or a survey of grocery purchases in London. Datasets can also provide va
			link Read more, url='https://fly.io/blog/making-datasets-fly-with-datasette-and-fly/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 4 MIN READ
			heading Continuous Deployment with GitLab
			paragraph
				StaticText Starting with Continuous Deployment to Fly To deploy to Fly you essentially need four things The application you want to deploy. A runnable copy of flyctl. A fly.toml file. Your Fly API Token. For this example, we’ll deploy hellofly, our small Go
			link Read more, url='https://fly.io/blog/continuous-deployment-with-gitlab/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 4 MIN READ
			heading Fly Answers Questions
			paragraph
				StaticText Q: Can I set up a custom hostname or domain with Fly? A: You can. In fact you can set up as many of them on an application as you like. When you create a custom hostname on Fly and validate it, you also get Let’s Encrypt certificates automatically. Yo
			link Read more, url='https://fly.io/blog/fly-answers-questions/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 4 MIN READ
			heading Scaling Fly for All
			paragraph
				StaticText Update 15/May/2020: The contents of this article have been superceded by a new scaling system on Fly. We’ve refined the scaling models and commands to make things simpler to use. To read about these changes see the article on the updated scale system
			link Read more, url='https://fly.io/blog/scaling-fly-for-all/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 2 MIN READ
			heading How to do Custom Domains with Fly
			paragraph
				StaticText In Custom Domains with Fly, you’ll learn how to configure an NGINX server to proxy traffic to external sites and how to attach host and domain names to your Fly applications using Fly’s command line flyctl. For those of you who practice devops and
			link Read more, url='https://fly.io/blog/how-to-custom-domains-with-fly/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 1 MIN READ
			heading Fly Friday - News and Tips
			paragraph
				StaticText This week with Fly: We show you how to use Fly to build your own GraphQL APIs. Firefox is switching DNS over HTTPS (DoH) on by default in the USA. We already have a great guide to using Fly as your private DoH service. Fly’s new community portal for
			link Read more, url='https://fly.io/blog/fly-friday-feb28-news/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 1 MIN READ
			heading GraphQL, Hasura and Fly
			paragraph
				StaticText Hasura gives you an open source GraphQL backend which can make it simple to query PostgreSQL by helping you map all your schemas and roles. It also rolls in the ability to query other GraphQL services so you can mix in services. With an interactive c
			link Read more, url='https://fly.io/blog/graphql-hasura-and-fly/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 1 MIN READ
			heading Fly Friday - Customizing with Dockerfiles
			paragraph
				StaticText We deployed Docker’s official httpd image in our first Fly Friday video. That image, when run, serves up files from its /usr/local/apache2/html. By default the image contains the words “It works”. If we want it to say something else, we need to copy
			link Read more, url='https://fly.io/blog/fly-friday-customizing-with-dockerfiles/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 1 MIN READ
			heading Fly Friday - Flyctl and Ports
			paragraph
				StaticText TL;DR: The -p flag is used with flyctl apps create when you create a Fly app for the first time. Setting -p with a numeric value automatically sets the internal port of the generated fly.toml configuration file. The internal port is the port your a
			link Read more, url='https://fly.io/blog/fly-friday-flyctl-and-ports/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 2 MIN READ
			heading Simpler Fly deployments for NodeJS, Rails, Go, and Java
			paragraph
				StaticText A Speedrun for everyone Let’s get straight down to it. Make sure you have the latest version of flyctl and then get a Node application like this version of our hello world example - “hellonode-builder”. Wrap text
			link Read more, url='https://fly.io/blog/simpler-fly-deployments-nodejs-rails-golang-java/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 2 MIN READ
			heading Turboku - The Art Of Faster Heroku Apps
			paragraph
				StaticText The next question is how can they move their application the Fly. For that we’ve created “Turboku”, a simple way to bring your Heroku apps to Fly. What we do is take your Heroku web dynos and turn them into Fly applications automatically. That
			link Read more, url='https://fly.io/blog/turboku/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText 3 MIN READ
			heading Command Lines, Flyctl and Fly
			paragraph
				StaticText Why Command Lines? As we’ve developed Fly, we’ve seen numerous benefits that come from driving the service through the command line. Our newest addition to our command armory is the flyctl command which now, quite literally, covers the entire lifecycl
			link Read more, url='https://fly.io/blog/command-lines-flyctl-and-fly/'
		article
			image, url='https://fly.io/static/images/default-post-thumbnail.webp'
			StaticText BY DJ WALKER-MORGAN
			StaticText <1 MIN READ
			heading Welcome To Fly In 2020
			paragraph
				StaticText Check out our all new documentation for the Fly platform which covers everything from creating Apps you can deploy to Fly to how to take existing Docker images and setting them free across the globe. If you have any questions, drop a line to us on su
			link Read more, url='https://fly.io/blog/welcome-to-fly/'
	contentinfo
		link Fly App performance optimization, url='https://fly.io/'
			image Fly App performance optimization
		DescriptionList
			term
				StaticText COMPANY
			definition
				link About, url='https://fly.io/about/'
				link Pricing, url='https://fly.io/pricing/'
				link Jobs, url='https://fly.io/jobs/'
		DescriptionList
			term
				StaticText ARTICLES
			definition
				link Blog, url='https://fly.io/blog/'
				link Phoenix Files, url='https://fly.io/phoenix-files/'
				link Laravel Bytes, url='https://fly.io/laravel-bytes/'
				link Ruby Dispatch, url='https://fly.io/ruby-dispatch/'
				link Django Beats, url='https://fly.io/django-beats/'
				link JavaScript Journal, url='https://fly.io/javascript-journal/'
		DescriptionList
			term
				StaticText RESOURCES
			definition
				link Docs, url='https://fly.io/docs/'
				link Support, url='https://fly.io/docs/support/'
				link Support Metrics, url='https://fly.io/support/'
				link Status, url='https://status.flyio.net/'
		DescriptionList
			term
				StaticText CONTACT
			definition
				link GitHub, url='https://github.com/superfly/'
				link Twitter, url='https://twitter.com/flydotio'
				link Community, url='https://community.fly.io/'
		DescriptionList
			term
				StaticText LEGAL
			definition
				link Security, url='https://fly.io/docs/security/'
				link Privacy policy, url='https://fly.io/legal/privacy-policy'
				link Terms of service, url='https://fly.io/legal/terms-of-service'
				link Acceptable Use Policy, url='https://fly.io/legal/acceptable-use-policy'
		paragraph
			StaticText Copyright © 2024 Fly.io
```
</details>



```
RootWebArea AI GPU Clusters, From Your Laptop, With Livebook · The Fly Blog, focused, url='https://fly.io/blog/ai-gpu-clusters-from-your-laptop-livebook/'
	banner
		navigation Logo menu
			[50] link Fly App performance optimization, center=(312,48), url='https://fly.io/'
				image Fly App performance optimization
```
<details><summary>Show more</summary>

```
			[53] link Blog, center=(356,48), url='https://fly.io/blog/'
				image Blog
		[57] link Need a Logo? View Our Brand Assets, center=(388,112), inner_text=Need a Logo?
View Our Brand Assets, url='https://fly.io/docs/about/brand/'
			strong
			image
		navigation Main menu
			DescriptionList
				[69] term, center=(730,48), inner_text=Articles
					StaticText Articles
				definition
					link Blog, url='https://fly.io/blog/'
					link Phoenix Files, url='https://fly.io/phoenix-files/'
					link Laravel Bytes, url='https://fly.io/laravel-bytes/'
					link Ruby Dispatch, url='https://fly.io/ruby-dispatch/'
					link Django Beats, url='https://fly.io/django-beats/'
					link JavaScript Journal, url='https://fly.io/javascript-journal/'
			[78] link Security, center=(808,48), url='https://fly.io/security/'
			[79] link Infra Log, center=(890,48), url='https://fly.io/infra-log/'
			[80] link Docs, center=(960,48), url='https://fly.io/docs/'
			[81] link Community, center=(1039,48), url='https://community.fly.io/'
			[82] link Status, center=(1124,48), url='https://status.flyio.net/'
			[83] link Pricing, center=(1193,48), url='https://fly.io/pricing/'
			[85] link Sign In, center=(1435,48), url='https://fly.io/app/sign-in'
			[86] link Get Started, center=(1536,48), url='https://fly.io/docs/hands-on/start/'
			[87] link RSS Feed, center=(1619,48), url='https://fly.io/blog/feed.xml'
				image
	main
		StaticText READING TIME
		StaticText •
		StaticText 8 MIN
		[119] link SHARE THIS POST ON TWITTER, center=(1242,190), url='https://twitter.com/share?text=AI%20GPU%20Clusters,%20From%20Your%20Laptop,%20With%20Livebook&url=https://fly.io/blog/ai-gpu-clusters-from-your-laptop-livebook/&via=flydotio'
			image
		[122] link SHARE THIS POST ON HACKER NEWS, center=(1270,190), url='http://news.ycombinator.com/submitlink?u=https://fly.io/blog/ai-gpu-clusters-from-your-laptop-livebook/&t=AI%20GPU%20Clusters,%20From%20Your%20Laptop,%20With%20Livebook'
			image
		[125] link SHARE THIS POST ON REDDIT, center=(1298,190), url='http://www.reddit.com/submit?url=https://fly.io/blog/ai-gpu-clusters-from-your-laptop-livebook/&title=AI%20GPU%20Clusters,%20From%20Your%20Laptop,%20With%20Livebook'
			image
		heading AI GPU Clusters, From Your Laptop, With Livebook
		article
			DescriptionList
				term
					StaticText Author
				definition
					image Chris McCord, url='https://fly.io/static/images/chris-m.webp'
					DescriptionList
						term
							StaticText Name
						definition
							StaticText Chris McCord
						term
							StaticText @chris_mccord
						definition
							[139] link @chris_mccord, center=(396,332), url='https://twitter.com/chris_mccord'
				term
					StaticText Author
				definition
					image José Valim, url='https://fly.io/static/images/jose-v.webp'
					DescriptionList
						term
							StaticText Name
						definition
							StaticText José Valim
						term
							StaticText @josevalim
						definition
							[148] link @josevalim, center=(382,400), url='https://twitter.com/josevalim'
			figure
				image A cartoon of the Fly baloon and a livebook roasting marshmallows over a campfire., url='https://fly.io/blog/ai-gpu-clusters-from-your-laptop-livebook/assets/ai-gpu-livebook-cover.webp'
				Figcaption
					StaticText Image by
					image
					[155] link Annie Ruygt, center=(1276,913), url='https://annieruygtillustration.com/'
			paragraph
				StaticText Livebook, FLAME, and the Nx stack: three Elixir components that are easy to describe, more powerful than they look, and intricately threaded into the Elixir ecosystem. A few weeks ago, Chris McCord (👋) and Chris Grainger showed them off at ElixirConf 2024. We thought the talk was worth a recap.
			paragraph
				StaticText Let’s begin by introducing our cast of characters.
			paragraph
				link Livebook, url='https://livebook.dev/'
				StaticText is usually described as Elixir’s answer to
				link Jupyter Notebooks, url='https://jupyter.org/'
				StaticText . And that’s a good way to think about it. But Livebook takes full advantage of the Elixir platform, which makes it sneakily powerful. By linking up directly with Elixir app clusters, Livebook can switch easily between driving compute locally or on remote servers, and makes it easy to bring in any kind of data into reproducible workflows.
			paragraph
				link FLAME, url='https://fly.io/blog/rethinking-serverless-with-flame/'
				StaticText is the Elixir’s answer to serverless computing. By having the library manage a pool of executors for you, FLAME lets you treat your entire application as if it was elastic and scale-to-zero. You configure FLAME with some basic information about where to run code and how many instances it’s allowed to run with, and then mark off any arbitrary section of code with
				code
					StaticText Flame.call
				StaticText . The framework takes care of the rest. It’s the upside of serverless without committing yourself to blowing your app apart into tiny, intricately connected pieces.
			paragraph
				StaticText The
				link Nx stack, url='https://github.com/elixir-nx'
				StaticText is how you do Elixir-native AI and ML. Nx gives you an Elixir-native notion of tensor computations with GPU backends.
				link Axon, url='https://github.com/elixir-nx/axon'
				StaticText builds a common interface for ML models on top of it.
				link Bumblebee, url='https://github.com/elixir-nx/bumblebee'
				StaticText makes those models available to any Elixir app that wants to download them, from just a couple lines of code.
			paragraph
				StaticText Here is quick video showing how to transfer a local tensor to a remote GPU, using Livebook, FLAME, and Nx:
			Iframe
				RootWebArea Using Fly GPUs with Livebook - YouTube, url='https://www.youtube.com/embed/5ImP3gpUSkQ'
					[a31] link Photo image of Livebook, center=(608,1952)
					[a39] link Using Fly GPUs with Livebook, center=(951,1953), url='https://www.youtube.com/watch?v=5ImP3gpUSkQ'
					[a56] button Share, center=(1298,1951), hasPopup='menu'
						image
					[a92] button Play, center=(960,2136)
						image
					generic, atomic
					[a320] link Watch on YouTube, center=(662,2324), url='https://www.youtube.com/watch?v=5ImP3gpUSkQ&embeds_referring_euri=https%3A%2F%2Ffly.io%2F'
			paragraph
				StaticText Let’s dive into the
				link keynote, url='https://www.youtube.com/watch?v=4qoHPh0obv0'
				StaticText .
			heading Anchor Poking a hole in your infrastructure
				link Anchor, url='https://fly.io/blog/ai-gpu-clusters-from-your-laptop-livebook/#poking-a-hole-in-your-infrastructure'
			paragraph
				StaticText Any Livebook, including the one running on your laptop, can start a runtime running on a Fly Machine, in Fly.io’s public cloud. That Elixir machine will (by default) live in your default Fly.io organization, giving it networked access to all the other apps that might live there.
			paragraph
				StaticText This is an access control situation that mostly just does what you want it to do without asking. Unless you ask it to, Fly.io isn’t exposing anything to the Internet, or to other users of Fly.io. For instance: say we have a database we’re going to use to generate reports. It can hang out on our Fly organization, inside of a private network with no connectivity to the world. We can spin up a Livebook instance that can talk to it, without doing any network or infrastructure engineering to make that happen.
			paragraph
				StaticText But wait, there’s more. Because this is all Elixir, Livebook also allows you to connect to any running Erlang/Elixir application in your infrastructure to debug, introspect, and monitor them.
			paragraph
				StaticText Check out this clip of Chris McCord connecting
				link to an existing application, url='https://rtt.fly.dev/'
				StaticText during the keynote:
			Iframe
				RootWebArea Livebook in the cloud: GPUs and clustered workflows in seconds - YouTube, url='https://www.youtube.com/embed/4qoHPh0obv0?start=1106'
					[b30] link Photo image of ElixirConf, center=(608,3229)
					[b38] link Livebook in the cloud: GPUs and clustered workflows in seconds, center=(951,3230), url='https://www.youtube.com/watch?v=4qoHPh0obv0'
					[b55] button Share, center=(1298,3227), hasPopup='menu'
						image
					[b91] button Play, center=(960,3413)
						image
					generic, atomic
					[b319] link Watch on YouTube, center=(662,3600), url='https://www.youtube.com/watch?t=1106&v=4qoHPh0obv0&embeds_referring_euri=https%3A%2F%2Ffly.io%2F'
			paragraph
				StaticText Running a snippet of code from a laptop on a remote server is a neat trick, but Livebook is doing something deeper than that. It’s taking advantage of Erlang/Elixir’s native facility with cluster computation and making it available to the notebook. As a result, when we do things like auto-completing, Livebook delivers results from modules defined on the remote note itself. 🤯
			heading Anchor Elastic scale with FLAME
				link Anchor, url='https://fly.io/blog/ai-gpu-clusters-from-your-laptop-livebook/#elastic-scale-with-flame'
			paragraph
				StaticText When we first introduced FLAME, the example we used was video encoding.
			paragraph
				StaticText Video encoding is complicated and slow enough that you’d normally make arrangements to run it remotely or in a background job queue, or as a triggerable Lambda function. The point of FLAME is to get rid of all those steps, and give them over to the framework instead. So: we wrote our
				code
					StaticText ffpmeg
				StaticText calls inline like normal code, as if they were going to complete in microseconds, and wrapped them in
				code
					StaticText Flame.call
				StaticText blocks. That was it, that was the demo.
			paragraph
				StaticText Here, we’re going to put a little AI spin on it.
			paragraph
				StaticText The first thing we’re doing here is driving FLAME pools from Livebook. Livebook will automatically synchronize your notebook dependencies as well as any module or code defined in your notebook across nodes. That means any code we write in our notebook can be dispatched transparently out to arbitrarily many compute nodes, without ceremony.
			paragraph
				StaticText Now let’s add some AI flair. We take an object store bucket full of video files. We use
				code
					StaticText ffmpeg
				StaticText to extract stills from the video at different moments. Then: we send them to
				link Llama, url='https://www.llama.com/'
				StaticText , running on
				link GPU Fly Machines, url='https://fly.io/gpu'
				StaticText (still locked to our organization), to get descriptions of the stills.
			paragraph
				StaticText All those stills and descriptions get streamed back to our notebook, in real time:
			Iframe
				RootWebArea Livebook in the cloud: GPUs and clustered workflows in seconds - YouTube, url='https://www.youtube.com/embed/4qoHPh0obv0?start=1692'
					[c30] link Photo image of ElixirConf, center=(608,4744)
					[c38] link Livebook in the cloud: GPUs and clustered workflows in seconds, center=(951,4744), url='https://www.youtube.com/watch?v=4qoHPh0obv0'
					[c55] button Share, center=(1298,4742), hasPopup='menu'
						image
					[c91] button Play, center=(960,4928)
						image
					generic, atomic
					[c319] link Watch on YouTube, center=(662,5115), url='https://www.youtube.com/watch?t=1692&v=4qoHPh0obv0&embeds_referring_euri=https%3A%2F%2Ffly.io%2F'
			paragraph
				StaticText At the end, the descriptions are sent to
				link Mistral, url='https://mistral.ai/'
				StaticText , which builds a summary.
			paragraph
				StaticText Thanks to FLAME, we get explicit control over the minimum and the maximum amount of nodes you want running at once, as well their concurrency settings. As nodes finish processing each video, new ones are automatically sent to them, until the whole bucket has been traversed. Each node will automatically shut down after an idle timeout and the whole cluster terminates if you disconnect the Livebook runtime.
			paragraph
				StaticText Just like your app code, FLAME lets you take your notebook code designed to run locally, change almost nothing, and elastically execute it across ephemeral infrastructure.
			heading Anchor 64-GPUs hyperparameter tuning on a laptop
				link Anchor, url='https://fly.io/blog/ai-gpu-clusters-from-your-laptop-livebook/#64-gpus-hyperparameter-tuning-on-a-laptop'
			paragraph
				StaticText Next, Chris Grainger, CTO of
				link Amplified, url='https://amplified.ai/'
				StaticText , takes the stage.
			paragraph
				StaticText For work at Amplified, Chris wants to analyze a gigantic archive of patents, on behalf of a client doing edible cannibinoid work. To do that, he uses a BERT model (BERT, from Google, is one of the OG “transformer” models, optimized for text comprehension).
			paragraph
				StaticText To make the BERT model effective for this task, he’s going to do a hyperparameter training run.
			paragraph
				StaticText This is a much more complicated AI task than the Llama work we just showed up. Chris is going to generate a cluster of 64 GPU Fly Machines, each running an
				link L40s GPU, url='https://fly.io/blog/cutting-prices-for-l40s-gpus-in-half/'
				StaticText . On each of these nodes, he needs to:
			list
				listitem
					StaticText •
					StaticText setup its environment (including native dependencies and GPU bindings)
				listitem
					StaticText •
					StaticText load the training data
				listitem
					StaticText •
					StaticText compile a different version of BERT with different parameters, optimizers, etc.
				listitem
					StaticText •
					StaticText start the fine-tuning
				listitem
					StaticText •
					StaticText stream its results in real-time to each assigned chart
			paragraph
				StaticText Here’s the clip. You’ll see the results stream in, in real time, directly back to his Livebook. We’ll wait, because it won’t take long to watch:
			Iframe
				RootWebArea Livebook in the cloud: GPUs and clustered workflows in seconds - YouTube, url='https://www.youtube.com/embed/4qoHPh0obv0?start=3344'
					[d30] link Photo image of ElixirConf, center=(608,6447)
					[d38] link Livebook in the cloud: GPUs and clustered workflows in seconds, center=(951,6448), url='https://www.youtube.com/watch?v=4qoHPh0obv0'
					[d55] button Share, center=(1298,6445), hasPopup='menu'
						image
					[d91] button Play, center=(960,6631)
						image
					generic, atomic
					[d319] link Watch on YouTube, center=(662,6819), url='https://www.youtube.com/watch?t=3344&v=4qoHPh0obv0&embeds_referring_euri=https%3A%2F%2Ffly.io%2F'
			heading Anchor This is just the beginning
				link Anchor, url='https://fly.io/blog/ai-gpu-clusters-from-your-laptop-livebook/#this-is-just-the-beginning'
			paragraph
				StaticText The suggestion of mixing Livebook and FLAME to elastically scale notebook execution was originally proposed by Chris Grainger during ElixirConf EU. During the next four months, Jonatan Kłosko, Chris McCord, and José Valim worked part-time on making it a reality in time for ElixirConf US. Our ability to deliver such a rich combination of features in such a short period of time is a testament to the capabilities of the Erlang Virtual Machine, which Elixir and Livebook runs on. Other features, such as
				link remote dataframes and distributed GC, url='https://github.com/elixir-explorer/explorer/issues/932'
				StaticText , were implemented in a weekend. Bringing the same functionality to other ecosystems would take several additional months, sometimes accompanied by millions in funding, and often times as part of a closed-source product.
			paragraph
				StaticText Furthermore, since we announced this feature,
				link Michael Ruoss, url='https://github.com/mruoss'
				StaticText stepped in and brought the same functionality to Kubernetes. From Livebook v0.14.1, you can start Livebook runtimes inside a Kubernetes cluster and also use FLAME to elastically scale them. Expect more features and news in this space!
			paragraph
				StaticText Finally, Fly’s infrastructure played a key role in making it possible to start a cluster of GPUs in seconds rather than minutes, and all it requires is a Docker image. We’re looking forward to see how other technologies and notebook platforms can leverage Fly to also elevate their developer experiences.
			figure
				Figcaption
					heading Launch a GPU app in seconds
					paragraph
						StaticText Run your own LLMs or use Livebook for elastic GPU workflows ✨
					link Go!   →, url='https://fly.io/gpu'
				image, url='https://fly.io/static/images/cta-turtle.webp'
			DescriptionList
				term
					StaticText LAST UPDATED
				StaticText •
				definition
					time
						StaticText SEP 24, 2024
			link Share this post on Twitter, url='https://twitter.com/share?text=AI%20GPU%20Clusters,%20From%20Your%20Laptop,%20With%20Livebook&url=https://fly.io/blog/ai-gpu-clusters-from-your-laptop-livebook/&via=flydotio'
				image
			link Share this post on Hacker News, url='http://news.ycombinator.com/submitlink?u=https://fly.io/blog/ai-gpu-clusters-from-your-laptop-livebook/&t=AI%20GPU%20Clusters,%20From%20Your%20Laptop,%20With%20Livebook'
				image
			link Share this post on Reddit, url='http://www.reddit.com/submit?url=https://fly.io/blog/ai-gpu-clusters-from-your-laptop-livebook/&title=AI%20GPU%20Clusters,%20From%20Your%20Laptop,%20With%20Livebook'
				image
			DescriptionList
				term
					StaticText Previous post ↓
				definition
					[282] link Accident Forgiveness, center=(1540,351), url='https://fly.io/blog/accident-forgiveness/'
	contentinfo
		link Fly App performance optimization, url='https://fly.io/'
			image Fly App performance optimization
		DescriptionList
			term
				StaticText COMPANY
			definition
				link About, url='https://fly.io/about/'
				link Pricing, url='https://fly.io/pricing/'
				link Jobs, url='https://fly.io/jobs/'
		DescriptionList
			term
				StaticText ARTICLES
			definition
				link Blog, url='https://fly.io/blog/'
				link Phoenix Files, url='https://fly.io/phoenix-files/'
				link Laravel Bytes, url='https://fly.io/laravel-bytes/'
				link Ruby Dispatch, url='https://fly.io/ruby-dispatch/'
				link Django Beats, url='https://fly.io/django-beats/'
				link JavaScript Journal, url='https://fly.io/javascript-journal/'
		DescriptionList
			term
				StaticText RESOURCES
			definition
				link Docs, url='https://fly.io/docs/'
				link Support, url='https://fly.io/docs/support/'
				link Support Metrics, url='https://fly.io/support/'
				link Status, url='https://status.flyio.net/'
		DescriptionList
			term
				StaticText CONTACT
			definition
				link GitHub, url='https://github.com/superfly/'
				link Twitter, url='https://twitter.com/flydotio'
				link Community, url='https://community.fly.io/'
		DescriptionList
			term
				StaticText LEGAL
			definition
				link Security, url='https://fly.io/docs/security/'
				link Privacy policy, url='https://fly.io/legal/privacy-policy'
				link Terms of service, url='https://fly.io/legal/terms-of-service'
				link Acceptable Use Policy, url='https://fly.io/legal/acceptable-use-policy'
		paragraph
			StaticText Copyright © 2024 Fly.io
```
</details>

**Reasoning for action:** Since my goal is to access the full article with its headings, images, and interactive elements, clicking on the 'Read more' link corresponding to the desired article is essential. This action directs me away from the blog overview page where only snippets and summaries are displayed to the actual detailed content of the article, thus fulfilling the user's request to explore that specific article.

**Action:** click('128') # Click on the 'Read more' link for the article 'AI GPU Clusters, From Your Laptop, With Livebook'.

**Change Description:** After clicking the 'Read more' link for the article 'AI GPU Clusters, From Your Laptop, With Livebook', the browser navigated to a new page displaying the article's content, which includes headings, paragraphs, images, and interactive elements like video embeds and share links, effectively replacing the previous blog listing with full article details.

**Screenshot before:****Screenshot after:**---

