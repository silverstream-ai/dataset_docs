# Task

**Exploring Features of Trigger.dev**

As a potential user interested in background job solutions,
I explore the features of Trigger.dev,
so that I can evaluate if it meets my development needs.

**Success definition:** Given I am on the Trigger.dev homepage.
When I click on the 'How it works' link and then the 'Features' link followed by the 'All features' link.
Then I should be navigated to the Product page, where I can see the list of detailed features offered by Trigger.dev.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://trigger.dev/

https://trigger.dev/#how-it-works

**Content (before/after):** 

```
RootWebArea Trigger.dev | Open source background jobs with no timeouts., focused, url='https://trigger.dev/'
	banner
		navigation Main
			[25] link Go to homepage, center=(327,30), url='https://trigger.dev/'
				image Trigger.dev logo
```
<details><summary>Show more</summary>

```
			list
				listitem
					[32] link How it works, center=(479,30), url='https://trigger.dev/#how-it-works'
				listitem
					[34] link Features, center=(586,29), url='https://trigger.dev/product'
						button Features, expanded=False
				listitem
					[80] link Changelog, center=(686,29), url='https://trigger.dev/changelog'
						button Changelog, expanded=False
				listitem
					[113] link Blog, center=(771,29), url='https://trigger.dev/blog'
						button Blog, expanded=False
				listitem
					[146] link Docs, center=(835,29), url='https://trigger.dev/docs'
						button Docs, expanded=False
				listitem
					[255] link Pricing, center=(908,30), url='https://trigger.dev/pricing'
			list
				listitem
					[259] link Trigger.dev Discord server, center=(1320,30), url='https://trigger.dev/discord'
						image
				listitem
					[262] link Trigger.dev GitHub repo, center=(1408,30), inner_text=Star 9.8k, url='https://github.com/triggerdotdev/trigger.dev'
						image
						StaticText Star
						StaticText 9.8k
				listitem
					[267] link Login, center=(1504,30), url='https://cloud.trigger.dev/'
				listitem
					[269] link Get started, center=(1607,28), url='https://cloud.trigger.dev/'
	main
		heading The open source background jobs platform
		paragraph
			StaticText Write workflows in normal async code and we’ll handle the rest, from queues to elastic scaling. No timeouts, retries, observability, and zero infrastructure to manage.
		[289] link Get started now, center=(466,580), url='https://cloud.trigger.dev/'
		image Trigger.dev dashboard, url='https://trigger.dev/images/hero-image-dashboard.png'
		tablist, orientation='horizontal'
			[313] tab AI tasks, center=(407,757), selected=True, type=button
				Canvas
			[317] tab Video processing, center=(569,757), selected=False, type=button
				Canvas
			[321] tab Cron, center=(718,757), selected=False, type=button
				Canvas
			[325] tab Waits, center=(820,757), selected=False, type=button
				Canvas
			[329] tab Workflows, center=(945,757), selected=False, type=button
				Canvas
			[333] tab Concurrency, center=(1098,757), selected=False, type=button
				Canvas
			[337] tab Retries, center=(1238,757), selected=False, type=button
				Canvas
			[341] tab PDF to images, center=(1386,757), selected=False, type=button
				Canvas
			[345] tab Semantic search, center=(1572,757), selected=False, type=button
				Canvas
			tab AI Agent, selected=False
				Canvas
			tab Email campaign, selected=False
				Canvas
		[306] div, center=(227,757)
		tabpanel
			StaticText // Generate an image using OpenAI Dall-E 3
			StaticText export
			StaticText const
			StaticText generateContent
			StaticText =
			StaticText task
			StaticText (
			StaticText {
			StaticText id
			StaticText :
			StaticText "generate-content"
			StaticText ,
			StaticText retry
			StaticText :
			StaticText {
			StaticText maxAttempts
			StaticText :
			StaticText 3
			StaticText ,
			StaticText }
			StaticText ,
			StaticText run
			StaticText :
			StaticText async
			StaticText (
			StaticText {
			StaticText theme
			StaticText ,
			StaticText description
			StaticText }
			StaticText :
			StaticText Payload
			StaticText )
			StaticText =>
			StaticText {
			StaticText const
			StaticText textResult
			StaticText =
			StaticText await
			StaticText openai
			StaticText .
			StaticText chat
			StaticText .
			StaticText completions
			StaticText .
			StaticText create
			StaticText (
			StaticText {
			StaticText model
			StaticText :
			StaticText "gpt-4o"
			StaticText ,
			StaticText messages
			StaticText :
			StaticText generateTextPrompt
			StaticText (
			StaticText theme
			StaticText ,
			StaticText description
			StaticText )
			StaticText ,
			StaticText }
			StaticText )
			StaticText ;
			StaticText if
			StaticText (
			StaticText !
			StaticText textResult
			StaticText .
			StaticText choices
			StaticText [
			StaticText 0
			StaticText ]
			StaticText )
			StaticText {
			StaticText throw
			StaticText new
			StaticText Error
			StaticText (
			StaticText "No content, retrying…"
			StaticText )
			StaticText ;
			StaticText }
			StaticText const
			StaticText imageResult
			StaticText =
			StaticText await
			StaticText openai
			StaticText .
			StaticText images
			StaticText .
			StaticText generate
			StaticText (
			StaticText {
			StaticText model
			StaticText :
			StaticText "dall-e-3"
			StaticText ,
			StaticText prompt
			StaticText :
			StaticText generateImagePrompt
			StaticText (
			StaticText theme
			StaticText ,
			StaticText description
			StaticText )
			StaticText ,
			StaticText }
			StaticText )
			StaticText ;
			StaticText if
			StaticText (
			StaticText !
			StaticText imageResult
			StaticText .
			StaticText data
			StaticText [
			StaticText 0
			StaticText ]
			StaticText )
			StaticText {
			StaticText throw
			StaticText new
			StaticText Error
			StaticText (
			StaticText "No image, retrying…"
			StaticText )
			StaticText ;
			StaticText }
			StaticText return
			StaticText {
			StaticText text
			StaticText :
			StaticText textResult
			StaticText .
			StaticText choices
			StaticText [
			StaticText 0
			StaticText ]
			StaticText ,
			StaticText image
			StaticText :
			StaticText imageResult
			StaticText .
			StaticText data
			StaticText [
			StaticText 0
			StaticText ]
			StaticText .
			StaticText url
			StaticText ,
			StaticText }
			StaticText ;
			StaticText }
			StaticText ,
			StaticText }
			StaticText )
			StaticText ;
			paragraph
				StaticText Reliably call AI APIs with no timeouts, automatic retrying, and tracing. Use existing Node.js SDKs and code from your repo.
		[359] svg, center=(1690,757)
		heading Trusted by developers at companies all over the world
		image
		image
		image
		image
		image
		image
		heading How Trigger.dev works
		button Play and pause video
			paragraph
		button Restart video
			image
			paragraph
				StaticText Replay
		button Toggle fullscreen
			paragraph
				StaticText Full screen
		heading Deploy and scale to any size
		Canvas
		Canvas
		heading No timeouts
		paragraph
			StaticText Write simple, reliable code and never hit a timeout.
		heading Pay for what you use
		paragraph
			StaticText Only pay when your code is actually executing.
		Canvas
		Canvas
		heading No servers to manage
		paragraph
			StaticText We deploy your tasks and handle scaling for you.
		heading Find and fix bugs fast
		heading Alerts for errors
		paragraph
			StaticText Get notified via email, Slack or webhooks when your tasks or deployments fail.
		Canvas
		image hero, url='https://trigger.dev/patterns/alerts-bg.png'
		heading Advanced filtering
		paragraph
			StaticText Find runs fast using advanced filtering options, then apply bulk actions to multiple tasks at once.
		Canvas
		image hero, url='https://trigger.dev/patterns/alerts-bg.png'
		heading Versioning
		paragraph
			StaticText Each deploy is an atomic version ensuring started tasks are not affected by code changes.
		Canvas
		image hero, url='https://trigger.dev/patterns/alerts-bg.png'
		heading All the tools you need to ship
		link View all features, url='https://trigger.dev/product'
		image
		heading Development
		link Cron schedules, url='https://trigger.dev/product/scheduled-tasks'
			image
			heading Cron schedules
		link Realtime run status updates, url='https://trigger.dev/docs/realtime/overview#realtime-overview'
			image
			heading Realtime run status updates
			image
			image
		link Write tasks in async code, url='https://trigger.dev/docs/guides/introduction'
			image
			heading Write tasks in async code
			image
			image
		link React hooks, url='https://trigger.dev/docs/frontend/react-hooks#react-hooks'
			image
			heading React hooks
			image
			image
		link Max duration, url='https://trigger.dev/docs/runs/max-duration#max-duration'
			image
			heading Max duration
			image
			image
		link Batch triggering, url='https://trigger.dev/docs/triggering#tasks-batchtrigger'
			image
			heading Batch triggering
			image
			image
		link Runtime schema payloads, url='https://trigger.dev/docs/tasks/schemaTask#schematask'
			image
			heading Runtime schema payloads
			image
			image
		link Waits, url='https://trigger.dev/docs/wait'
			image
			heading Waits
			image
			image
		image
		heading Production
		link Concurrency controls, url='https://trigger.dev/product/concurrency-and-queues'
			image
			heading Concurrency controls
		link Multiple environments, url='https://trigger.dev/docs/how-it-works#dev-mode'
			image
			heading Multiple environments
			image
			image
		link No servers to manage, url='https://trigger.dev/docs/how-it-works#trigger-dev-architecture'
			image
			heading No servers to manage
			image
			image
		link Automatic retries, url='https://trigger.dev/docs/errors-retrying'
			image
			heading Automatic retries
			image
			image
		link Build extensions, url='https://trigger.dev/docs/config/extensions/overview#build-extensions'
			image
			heading Build extensions
			image
			image
		link Checkpointing, url='https://trigger.dev/docs/how-it-works#the-checkpoint-resume-system'
			image
			heading Checkpointing
			image
			image
		link Versioning, url='https://trigger.dev/docs/versioning'
			image
			heading Versioning
			image
			image
		image
		heading Observability
		link Live dashboard, url='https://trigger.dev/product/observability-and-monitoring'
			image
			heading Live dashboard
		link Easily test tasks, url='https://trigger.dev/docs/run-tests#run-tests'
			image
			heading Easily test tasks
			image
			image
		link Tags, url='https://trigger.dev/docs/tags#tags'
			image
			heading Tags
			image
			image
		link Advanced run filters, url='https://trigger.dev/product/observability-and-monitoring#advanced-filters'
			image
			heading Advanced run filters
		link Run metadata, url='https://trigger.dev/docs/runs/metadata#run-metadata'
			heading Run metadata
			image
			image
		link Custom alerts, url='https://trigger.dev/product/observability-and-monitoring#alerts'
			image
			heading Custom alerts
		heading Reliable by default
		link Docs, url='https://trigger.dev/docs/v3/errors-retrying'
			image
			image
		tablist, orientation='horizontal'
			tab Task retrying Configure automatic retrying for tasks., selected=True
				heading Task retrying
				paragraph
			tab handleError() Conditional retrying based on the error and run., selected=False
				heading handleError()
				paragraph
			tab retry.onThrow() Fine-grained retrying inside tasks., selected=False
				heading retry.onThrow()
				paragraph
			tab retry.fetch() Automatically retry requests based on the response., selected=False
				heading retry.fetch()
				paragraph
			tab trigger.config Configure default retrying in your config file., selected=False
				heading trigger.config
				paragraph
		tabpanel Task retrying Configure automatic retrying for tasks.
			StaticText import
			StaticText {
			StaticText task
			StaticText }
			StaticText from
			StaticText "@trigger.dev/sdk/v3"
			StaticText ;
			StaticText export
			StaticText const
			StaticText simpleTask
			StaticText =
			StaticText task
			StaticText (
			StaticText {
			StaticText id
			StaticText :
			StaticText "simple-task"
			StaticText ,
			StaticText retry
			StaticText :
			StaticText {
			StaticText maxAttempts
			StaticText :
			StaticText 3
			StaticText ,
			StaticText minTimeoutInMs
			StaticText :
			StaticText 1000
			StaticText ,
			StaticText maxTimeoutInMs
			StaticText :
			StaticText 5000
			StaticText ,
			StaticText factor
			StaticText :
			StaticText 2
			StaticText ,
			StaticText randomize
			StaticText :
			StaticText true
			StaticText ,
			StaticText }
			StaticText ,
			StaticText run
			StaticText :
			StaticText async
			StaticText (
			StaticText payload
			StaticText ,
			StaticText {
			StaticText ctx
			StaticText }
			StaticText )
			StaticText =>
			StaticText {
			StaticText logger
			StaticText .
			StaticText log
			StaticText (
			StaticText `
			StaticText Attempt
			StaticText ${
			StaticText ctx
			StaticText .
			StaticText attempt
			StaticText .
			StaticText number
			StaticText }
			StaticText `
			StaticText )
			StaticText ;
			StaticText try
			StaticText {
			StaticText throw
			StaticText new
			StaticText Error
			StaticText (
			StaticText "This is an error."
			StaticText )
			StaticText ;
			StaticText }
			StaticText catch
			StaticText (
			StaticText error
			StaticText )
			StaticText {
			StaticText // The error was caught, so no retry
			StaticText }
			StaticText throw
			StaticText new
			StaticText Error
			StaticText (
			StaticText "This will cause a retry."
			StaticText )
			StaticText ;
			StaticText }
			StaticText ,
			StaticText }
			StaticText )
			StaticText ;
		heading Works with your existing tech stack…
		image Vercel logo, url='https://trigger.dev/tech-stack/vercel.png'
		image AWS logo, url='https://trigger.dev/tech-stack/aws.png'
		image Remix logo, url='https://trigger.dev/tech-stack/remix.png'
		image Nuxt logo, url='https://trigger.dev/tech-stack/nuxt.png'
		image SvelteKit logo, url='https://trigger.dev/tech-stack/sveltekit.png'
		image Fastify logo, url='https://trigger.dev/tech-stack/fastify.png'
		image RedwoodJS logo, url='https://trigger.dev/tech-stack/redwoodjs.png'
		image Cloudflare logo, url='https://trigger.dev/tech-stack/cloudflare.png'
		image ExpressJS logo, url='https://trigger.dev/tech-stack/expressjs.png'
		image Astro logo, url='https://trigger.dev/tech-stack/astro.png'
		image Google Cloud logo, url='https://trigger.dev/tech-stack/google-cloud.png'
		image Azure logo, url='https://trigger.dev/tech-stack/azure.png'
		image Netlify logo, url='https://trigger.dev/tech-stack/netlify.png'
		image NextJS logo, url='https://trigger.dev/tech-stack/nextjs.png'
		image Heart 1, url='https://trigger.dev/build/_assets/1-OXKMZAUJ.png'
		image Heart 2, url='https://trigger.dev/build/_assets/2-JH3Y3YJF.png'
		image Heart 3, url='https://trigger.dev/build/_assets/3-Y24XLZQ2.png'
		image Heart 4, url='https://trigger.dev/build/_assets/4-I5XLMUM3.png'
		image Heart 5, url='https://trigger.dev/build/_assets/5-H2LZLREV.png'
		heading We love open source. Trigger.dev is Apache 2.0 licensed so you can view the source code, contribute and self-host.
		link 9,900+ stars on GitHub, url='https://github.com/triggerdotdev/trigger.dev'
			image
			image
			heading 9,900+
			paragraph
		link Apache 2.0 open source license, url='https://github.com/triggerdotdev/trigger.dev?tab=Apache-2.0-1-ov-file#readme'
			image
			image
			heading Apache 2.0
			paragraph
		link 2,800+ Discord members, url='https://discord.gg/nkqV9xBYWy'
			image
			image
			heading 2,800+
			paragraph
		heading Loved by developers
		link Join our community, url='https://discord.gg/nkqV9xBYWy'
			image
			image
			image
		figure
			blockquote
				paragraph
					StaticText Trigger.dev is redefining background jobs for modern developers.
			Figcaption
				image, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/e82deee8-b8ec-4092-3980-b268688d1900/public'
				paragraph
					StaticText Paul Copplestone
				paragraph
					StaticText Supabase
				link Supabase logo, url='https://supabase.com/'
					image Supabase logo, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/bfd6d823-7027-4c8b-0117-ef4085b76200/public'
		figure
			blockquote
				paragraph
					StaticText Trigger.dev was the missing piece in our journey to go fully serverless. It enables us to focus entirely on building our product without worrying about the complexities of background jobs. The best part? We’re continuously adding more jobs as we scale!
			Figcaption
				image, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/d60cc0d1-a132-420a-b7fa-bdb67267f800/public'
				paragraph
					StaticText Pontus Abrahamsson
				paragraph
					StaticText Midday
				link Midday logo, url='https://midday.ai/'
					image Midday logo, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/9c0e5ff1-b718-4b67-8e7c-4a45f4697f00/public'
		figure
			blockquote
				paragraph
					StaticText We have critical business functionalities that need to be reliable and replayable in the event of a failure.
					StaticText Trigger.dev helps us deliver messages over WhatsApp, run thousands of jobs with custom LLM workflows, and execute ETL processes to sync our data across multiple databases without breaking a sweat!
			Figcaption
				image, url='https://trigger.dev/testimonials/drpcrd/patryk-maron.png'
				paragraph
					StaticText Patryk Maron
				paragraph
					StaticText DRPCRD
				link DRPCRD logo, url='https://drpcrd.com/'
					image DRPCRD logo, url='https://trigger.dev/testimonials/drpcrd/drpcrd.png'
		figure
			blockquote
				paragraph
					StaticText The first time I used Trigger.dev, I had an a-ha moment, I no longer needed to set up everything with ECS or Lambda. What also stands out is the exceptional support, unlike any I've seen in the web community.
			Figcaption
				image, url='https://trigger.dev/testimonials/ps-bridal/martin-ruzicka.png'
				paragraph
					StaticText Martin Ruzicka
				paragraph
					StaticText P.S. Bridal
				link P.S. Bridal logo, url='https://psbridal.co.uk/'
					image P.S. Bridal logo, url='https://trigger.dev/testimonials/ps-bridal/ps-bridal.png'
		figure
			blockquote
				paragraph
					StaticText We’ve been looking for a product like Trigger.dev for a long time - automation that's simple and dev-focused.
			Figcaption
				image, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/4e3d1187-c27b-4bdc-feac-d2e5297e9a00/public'
				paragraph
					StaticText Han Wang
				paragraph
					StaticText Mintlify
				link Mintlify logo, url='https://mintlify.com/'
					image Mintlify logo, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/1a068830-bc93-451c-b5c2-f76b24e42000/public'
		figure
			blockquote
				paragraph
					StaticText Trigger.dev is a breath of fresh air in a world of 20 second lambda timeouts. Trigger has world-class DX, support, and handles my long-running jobs with ease.
			Figcaption
				image, url='https://trigger.dev/testimonials/propfeeds/ian-janicki.png'
				paragraph
					StaticText Ian Janicki
				paragraph
					StaticText PropFeeds
				link PropFeeds logo, url='https://propfeeds.com/'
					image PropFeeds logo, url='https://trigger.dev/testimonials/propfeeds/propfeeds.png'
		figure
			blockquote
				paragraph
					StaticText I’m in love with Trigger.dev – it’s so much better than the old bull.js + heroku + redis setup that I used to use. You’ve knocked it out of the park with this tool!
			Figcaption
				image, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/6738d30f-ccd5-4342-8764-a2194fc0d900/public'
				paragraph
					StaticText Kushal Byatnal
				paragraph
					StaticText Extend
				link Extend logo, url='https://www.extend.app/'
					image Extend logo, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/0db95e34-61a0-47ff-879d-7698f3084900/public'
		figure
			blockquote
				paragraph
					StaticText We found software that's open-source friendly called MuPDF which runs in Node.js environments. Combined with using Trigger's tasks and runs, it solved our problem instantly. We are now easily processing around 6,000 documents per month anywhere from one page to hundreds of pages.
			Figcaption
				image, url='https://trigger.dev/customers/papermark/marc-seitz.png'
				paragraph
					StaticText Marc Seitz
				paragraph
					StaticText Papermark
				link Papermark logo, url='https://papermark.io/'
					image Papermark logo, url='https://trigger.dev/customers/papermark/papermark-logo.png'
		figure
			blockquote
				paragraph
					StaticText We're using Trigger for our billing, background jobs and deployment pipeline without worrying about operations or infrastructure. It just works.
			Figcaption
				image, url='https://trigger.dev/testimonials/unkey/andreas-thomas-chronark.png'
				paragraph
					StaticText Andreas Thomas
				paragraph
					StaticText Unkey
				link Unkey logo, url='https://www.unkey.com/'
					image Unkey logo, url='https://trigger.dev/testimonials/unkey/unkey.png'
		figure
			blockquote
				paragraph
					StaticText Trigger.dev is undoubtedly one of my most cherished services. Throughout my two-decade career, it’s rare to encounter a product or service that truly resonates and makes a significant impact. It just clicks - an absolute game-changer for us. The support is beyond exceptional, and they genuinely care about the product and their users. I wholeheartedly recommend Trigger!
			Figcaption
				image, url='https://trigger.dev/testimonials/midtown/aaron-spurlock.png'
				paragraph
					StaticText Aaron J. Spurlock
				paragraph
					StaticText Midtown HI
				link Midtown HI logo, url='https://midtownhomeimprovements.com/'
					image Midtown HI logo, url='https://trigger.dev/testimonials/midtown/midtown-logo.png'
		figure
			blockquote
				paragraph
					StaticText Trigger is a central part of our architecture. It’s allowed us to build a resilient system to orchestrates data across multiple systems. We love its observability, replayability, and how easily it slots into our existing codebase. It allows us to refine over time how to set the boundaries between async tasks and synchronous business logic.
			Figcaption
				image, url='https://trigger.dev/testimonials/numi/agree-ahmed.png'
				paragraph
					StaticText Agree Ahmed
				paragraph
					StaticText NUMI
				link NUMI logo, url='https://numi.tech/'
					image NUMI logo, url='https://trigger.dev/testimonials/numi/numi.png'
		figure
			blockquote
				paragraph
					StaticText Trigger.dev has become my go-to tool for new projects. I no longer need an additional server and can forget about horizontal scaling!
			Figcaption
				image, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/f577a1b5-e9bc-46ae-af2e-517c8ebef700/public'
				paragraph
					StaticText Nevo David
				paragraph
					StaticText Novu
				link Novu logo, url='https://novu.co/'
					image Novu logo, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/c89f7bbe-5b66-4b3d-be59-02bcc3a4e800/public'
		figure
			blockquote
				paragraph
					StaticText For AI powered products, Trigger.dev is my clear go-to tool for building robust serverless pipelines stitching together various LLM calls.
			Figcaption
				image, url='https://trigger.dev/testimonials/blee/evan-sandler.png'
				paragraph
					StaticText Evan Sandler
				paragraph
					StaticText Blee
				link Blee logo, url='https://www.blee.com/'
					image Blee logo, url='https://trigger.dev/testimonials/blee/blee-icon.png'
		figure
			blockquote
				paragraph
					StaticText Trigger is packaging end-to-end cron, queues and webhooks platform in a slick interface. Integration was quick and we love the support ❤️
			Figcaption
				image, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/521fe3ce-20f6-4f9b-d8de-b1c3b4724100/public'
				paragraph
					StaticText Aseem Gupta
				paragraph
					StaticText SuperKalam
				link SuperKalam logo, url='https://superkalam.com/'
					image SuperKalam logo, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/cf46d1a3-604d-4eef-2e18-384b767a6600/public'
		figure
			blockquote
				paragraph
					StaticText Using Trigger.dev for our Slack jobs saved us loads of time! It was much easier to set up than a no-code tool.
			Figcaption
				image, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/9c9e9c2e-5ff1-4227-f0d3-514aa2e49300/public'
				paragraph
					StaticText Vlad Matsiiako
				paragraph
					StaticText Infisical
				link Infisical logo, url='https://infisical.com/'
					image Infisical logo, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/c01ec071-f909-4eed-2f0a-6db7aa885c00/public'
		figure
			blockquote
				paragraph
					StaticText We decided to use Trigger.dev over Inngest or setting up our own dedicated solution. We had also looked into UI-based solutions like Zapier and n8n, but they become complex, really slow, expensive and time-consuming to manage for large automations. Trigger.dev made the most overall sense for us when taking dev-speed, cost, scalability and being future-proof into account.
			Figcaption
				image, url='https://trigger.dev/testimonials/heartspace-ai/sohrab-fadai.png'
				paragraph
					StaticText Sohrab Fadai
				paragraph
					StaticText Heartspace AI
				link Heartspace AI logo, url='https://heartspace.ai/'
					image Heartspace AI logo, url='https://trigger.dev/testimonials/heartspace-ai/heartspace-ai.png'
		figure
			blockquote
				paragraph
					StaticText We needed a sophisticated event engine: chaining LLM queries, orchestrating responses, async tasks, persistent state (without long lived servers), complex concurrency, and variable compute power.
					StaticText Trigger’s managed infra and intuitive SDK allowed us to migrate our entire events engine in a day (with incredible support from the team).
			Figcaption
				image, url='https://trigger.dev/testimonials/turnout-labs/michael-parker.png'
				paragraph
					StaticText Michael Parker
				paragraph
					StaticText Turnout Labs
				link Turnout Labs logo, url='https://www.turnoutlabs.ai/'
					image Turnout Labs logo, url='https://trigger.dev/testimonials/turnout-labs/turnout-labs.png'
		figure
			blockquote
				paragraph
					StaticText Trigger.dev is a great way to automate email campaigns with Resend.
			Figcaption
				image, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/3aca9c05-4563-4924-61df-867ec8434200/public'
				paragraph
					StaticText Zeno Rocha
				paragraph
					StaticText Resend
				link Resend logo, url='https://resend.com/'
					image Resend logo, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/a7941fc0-bfe2-4067-9449-9c593cf54c00/public'
		figure
			blockquote
				paragraph
					StaticText Trigger.dev helps us process bounties & tips on Algora without having to duct-tape queues & crons. With standardized timeouts, retries & logging we get full resilience & observability!
			Figcaption
				image, url='https://trigger.dev/testimonials/algora/zafer-cesur.png'
				paragraph
					StaticText Zaf Cesur
				paragraph
					StaticText Algora
				link Algora logo, url='https://algora.io/'
					image Algora logo, url='https://trigger.dev/testimonials/algora/algora.png'
		figure
			blockquote
				paragraph
					StaticText I really enjoyed using Trigger.dev to create jobs through code. I found the API integrations and scheduling features super useful.
			Figcaption
				image, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/36535ea9-56b4-42e3-4e45-ef08d293dd00/public'
				paragraph
					StaticText Adam Shiervani
				paragraph
					StaticText BuildJet
				link BuildJet logo, url='https://buildjet.com/'
					image BuildJet logo, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/06b5fdf7-f7be-424c-a4df-dfa0e3d93100/public'
		figure
			blockquote
				paragraph
					StaticText We love Trigger.dev and it’s had a big impact in dev iteration velocity already.
			Figcaption
				image, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/3e6a3e0f-e4c9-41e9-3881-ffe4cfc50400/public'
				paragraph
					StaticText André Neves
				paragraph
					StaticText ZBD
				link ZBD logo, url='https://zbd.gg/'
					image ZBD logo, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/9bfbbd56-ec03-43ef-663a-15595ae7ab00/public'
		button Read more...
		heading We're backed by the world's best investors, founders and operators
		image Y Combinator, url='https://trigger.dev/build/_assets/yc-logo-XZXGTI4H.png'
		image Supabase, url='https://trigger.dev/build/_assets/supabase-logo-M3YU7ZPR.png'
		image PagerDuty, url='https://trigger.dev/build/_assets/pagerduty-logo-KQPQK6G5.png'
		image Dropbox, url='https://trigger.dev/build/_assets/dropbox-logo-QA6HV7QX.png'
		image Raycast, url='https://trigger.dev/build/_assets/raycast-logo-LZWKA7SA.png'
		image Instabug, url='https://trigger.dev/build/_assets/instabug-logo-3P2FNFZ5.png'
		image Atlassian, url='https://trigger.dev/build/_assets/atlassian-logo-EMV6JCYW.png'
		image Amazon Web Services, url='https://trigger.dev/build/_assets/aws-logo-padding-ZYYRMKKD.png'
		heading Ready to start building?
		paragraph
			StaticText Build and deploy your first task in 3 mins with no timeouts and no infrastructure to manage.
		link Get started for free, url='https://cloud.trigger.dev/'
		Canvas
		heading Simple pricing
		paragraph
			StaticText Only pay for what you use and scale with your needs.
		link Explore pricing, url='https://trigger.dev/pricing'
		Canvas
		heading Self-host
		paragraph
			StaticText Trigger.dev is open source and self-hostable.
		link Self-hosting docs, url='https://trigger.dev/docs/v3/open-source-self-hosting'
	contentinfo
		link Trigger.dev logo, url='https://trigger.dev/#top'
			image Trigger.dev logo
		link Discord link, url='https://trigger.dev/discord'
			image
		link GitHub link, url='https://github.com/triggerdotdev/trigger.dev'
			image GitHub
		link X (Twitter) link, url='https://twitter.com/triggerdotdev'
			image X
		link LinkedIn link, url='https://www.linkedin.com/company/triggerdotdev'
			image
		heading Docs
		link Introduction, url='https://trigger.dev/docs/introduction'
			paragraph
		link Quick start guide, url='https://trigger.dev/docs/quick-start'
			paragraph
		link Guides & examples, url='https://trigger.dev/docs/guides/introduction'
			paragraph
				StaticText Examples
		link Creating a task, url='https://trigger.dev/docs/writing-tasks-introduction'
			paragraph
		link Triggeing a task, url='https://trigger.dev/docs/triggering'
			paragraph
				StaticText Triggering a task
		link Self hosting, url='https://trigger.dev/docs/open-source-self-hosting'
			paragraph
		heading Developers
		link Docs, url='https://trigger.dev/docs'
			paragraph
		link Changelog, url='https://trigger.dev/changelog'
			paragraph
		link Contributing, url='https://github.com/triggerdotdev/trigger.dev/blob/main/CONTRIBUTING.md'
			paragraph
		link Open source, url='https://github.com/triggerdotdev/trigger.dev?tab=Apache-2.0-1-ov-file#readme'
			paragraph
		link GitHub, url='https://github.com/triggerdotdev/trigger.dev'
			image
			paragraph
		heading Product
		link Pricing, url='https://trigger.dev/pricing'
			paragraph
		link How it works, url='https://trigger.dev/#how-it-works'
			paragraph
		link Product, url='https://trigger.dev/product'
			paragraph
				StaticText Features
		link Roadmap, url='https://feedback.trigger.dev/roadmap'
			paragraph
		link FAQs, url='https://trigger.dev/pricing#faqs'
			paragraph
		link Uptime status, url='https://status.trigger.dev/'
			paragraph
		heading Company
		link Blog, url='https://trigger.dev/blog'
			paragraph
		link Email, url='https://trigger.dev/contact'
			paragraph
				StaticText Contact
		link Blog, url='https://trigger.dev/jobs'
			paragraph
				StaticText Careers
		link Privacy policy, url='https://trigger.dev/legal/privacy'
			paragraph
		link Terms and conditions, url='https://trigger.dev/legal'
			paragraph
		link OSS friends, url='https://trigger.dev/oss-friends'
			paragraph
		Iframe Uptime status
			RootWebArea, url='https://status.trigger.dev/badge?theme=dark'
				[a4] link All services are online, center=(457,9174), url='https://status.trigger.dev/'
					image
		paragraph
			StaticText ©
			StaticText 2025
			StaticText Trigger.dev
	StaticText ,
	paragraph
		StaticText We only collect analytics cookies so we can improve your experience.
	[2023] link Privacy policy, center=(84,1037), url='https://trigger.dev/legal/privacy'
	[2027] button Opt-out, center=(209,1037), type=button
	[2030] button Accept, center=(283,1037), type=button
```
</details>



```
RootWebArea Trigger.dev | Open source background jobs with no timeouts., focused, url='https://trigger.dev/#how-it-works'
	banner
		navigation Main
			[25] link Go to homepage, center=(327,1658), url='https://trigger.dev/'
				image Trigger.dev logo
```
<details><summary>Show more</summary>

```
			list
				listitem
					[32] link How it works, center=(479,1658), focused, url='https://trigger.dev/#how-it-works'
				listitem
					[34] link Features, center=(586,1657), url='https://trigger.dev/product'
						button Features, expanded=False
				listitem
					[80] link Changelog, center=(686,1657), url='https://trigger.dev/changelog'
						button Changelog, expanded=False
				listitem
					[113] link Blog, center=(771,1657), url='https://trigger.dev/blog'
						button Blog, expanded=False
				listitem
					[146] link Docs, center=(835,1657), url='https://trigger.dev/docs'
						button Docs, expanded=False
				listitem
					[255] link Pricing, center=(908,1658), url='https://trigger.dev/pricing'
			list
				listitem
					[259] link Trigger.dev Discord server, center=(1320,1658), url='https://trigger.dev/discord'
						image
				listitem
					[262] link Trigger.dev GitHub repo, center=(1408,1658), inner_text=Star 9.8k, url='https://github.com/triggerdotdev/trigger.dev'
						image
						StaticText Star
						StaticText 9.8k
				listitem
					[267] link Login, center=(1504,1658), url='https://cloud.trigger.dev/'
				listitem
					[269] link Get started, center=(1607,1656), url='https://cloud.trigger.dev/'
	main
		heading The open source background jobs platform
		paragraph
			StaticText Write workflows in normal async code and we’ll handle the rest, from queues to elastic scaling. No timeouts, retries, observability, and zero infrastructure to manage.
		link Get started now, url='https://cloud.trigger.dev/'
		image Trigger.dev dashboard, url='https://trigger.dev/images/hero-image-dashboard.png'
		tablist, orientation='horizontal'
			tab AI tasks, selected=True
				Canvas
			tab Video processing, selected=False
				Canvas
			tab Cron, selected=False
				Canvas
			tab Waits, selected=False
				Canvas
			tab Workflows, selected=False
				Canvas
			tab Concurrency, selected=False
				Canvas
			tab Retries, selected=False
				Canvas
			tab PDF to images, selected=False
				Canvas
			tab Semantic search, selected=False
				Canvas
			tab AI Agent, selected=False
				Canvas
			tab Email campaign, selected=False
				Canvas
		tabpanel
			StaticText // Generate an image using OpenAI Dall-E 3
			StaticText export
			StaticText const
			StaticText generateContent
			StaticText =
			StaticText task
			StaticText (
			StaticText {
			StaticText id
			StaticText :
			StaticText "generate-content"
			StaticText ,
			StaticText retry
			StaticText :
			StaticText {
			StaticText maxAttempts
			StaticText :
			StaticText 3
			StaticText ,
			StaticText }
			StaticText ,
			StaticText run
			StaticText :
			StaticText async
			StaticText (
			StaticText {
			StaticText theme
			StaticText ,
			StaticText description
			StaticText }
			StaticText :
			StaticText Payload
			StaticText )
			StaticText =>
			StaticText {
			StaticText const
			StaticText textResult
			StaticText =
			StaticText await
			StaticText openai
			StaticText .
			StaticText chat
			StaticText .
			StaticText completions
			StaticText .
			StaticText create
			StaticText (
			StaticText {
			StaticText model
			StaticText :
			StaticText "gpt-4o"
			StaticText ,
			StaticText messages
			StaticText :
			StaticText generateTextPrompt
			StaticText (
			StaticText theme
			StaticText ,
			StaticText description
			StaticText )
			StaticText ,
			StaticText }
			StaticText )
			StaticText ;
			StaticText if
			StaticText (
			StaticText !
			StaticText textResult
			StaticText .
			StaticText choices
			StaticText [
			StaticText 0
			StaticText ]
			StaticText )
			StaticText {
			StaticText throw
			StaticText new
			StaticText Error
			StaticText (
			StaticText "No content, retrying…"
			StaticText )
			StaticText ;
			StaticText }
			StaticText const
			StaticText imageResult
			StaticText =
			StaticText await
			StaticText openai
			StaticText .
			StaticText images
			StaticText .
			StaticText generate
			StaticText (
			StaticText {
			StaticText model
			StaticText :
			StaticText "dall-e-3"
			StaticText ,
			StaticText prompt
			StaticText :
			StaticText generateImagePrompt
			StaticText (
			StaticText theme
			StaticText ,
			StaticText description
			StaticText )
			StaticText ,
			StaticText }
			StaticText )
			StaticText ;
			StaticText if
			StaticText (
			StaticText !
			StaticText imageResult
			StaticText .
			StaticText data
			StaticText [
			StaticText 0
			StaticText ]
			StaticText )
			StaticText {
			StaticText throw
			StaticText new
			StaticText Error
			StaticText (
			StaticText "No image, retrying…"
			StaticText )
			StaticText ;
			StaticText }
			StaticText return
			StaticText {
			StaticText text
			StaticText :
			StaticText textResult
			StaticText .
			StaticText choices
			StaticText [
			StaticText 0
			StaticText ]
			StaticText ,
			StaticText image
			StaticText :
			StaticText imageResult
			StaticText .
			StaticText data
			StaticText [
			StaticText 0
			StaticText ]
			StaticText .
			StaticText url
			StaticText ,
			StaticText }
			StaticText ;
			StaticText }
			StaticText ,
			StaticText }
			StaticText )
			StaticText ;
			paragraph
				StaticText Reliably call AI APIs with no timeouts, automatic retrying, and tracing. Use existing Node.js SDKs and code from your repo.
		heading Trusted by developers at companies all over the world
		image
		[752] video, center=(960,2100)
		image
		image
		image
		image
		image
		heading How Trigger.dev works
		[740] button Play and pause video, center=(1331,1730), inner_text=Play
			paragraph
		[743] button Restart video, center=(1407,1730), inner_text=Replay
			image
			paragraph
				StaticText Replay
		[746] button Toggle fullscreen, center=(1507,1730), inner_text=Full screen
			paragraph
				StaticText Full screen
		heading Deploy and scale to any size
		Canvas
		Canvas
		heading No timeouts
		paragraph
			StaticText Write simple, reliable code and never hit a timeout.
		heading Pay for what you use
		paragraph
			StaticText Only pay when your code is actually executing.
		Canvas
		Canvas
		heading No servers to manage
		paragraph
			StaticText We deploy your tasks and handle scaling for you.
		heading Find and fix bugs fast
		heading Alerts for errors
		paragraph
			StaticText Get notified via email, Slack or webhooks when your tasks or deployments fail.
		Canvas
		image hero, url='https://trigger.dev/patterns/alerts-bg.png'
		heading Advanced filtering
		paragraph
			StaticText Find runs fast using advanced filtering options, then apply bulk actions to multiple tasks at once.
		Canvas
		image hero, url='https://trigger.dev/patterns/alerts-bg.png'
		heading Versioning
		paragraph
			StaticText Each deploy is an atomic version ensuring started tasks are not affected by code changes.
		Canvas
		image hero, url='https://trigger.dev/patterns/alerts-bg.png'
		heading All the tools you need to ship
		link View all features, url='https://trigger.dev/product'
		image
		heading Development
		link Cron schedules, url='https://trigger.dev/product/scheduled-tasks'
			image
			heading Cron schedules
		link Realtime run status updates, url='https://trigger.dev/docs/realtime/overview#realtime-overview'
			image
			heading Realtime run status updates
			image
			image
		link Write tasks in async code, url='https://trigger.dev/docs/guides/introduction'
			image
			heading Write tasks in async code
			image
			image
		link React hooks, url='https://trigger.dev/docs/frontend/react-hooks#react-hooks'
			image
			heading React hooks
			image
			image
		link Max duration, url='https://trigger.dev/docs/runs/max-duration#max-duration'
			image
			heading Max duration
			image
			image
		link Batch triggering, url='https://trigger.dev/docs/triggering#tasks-batchtrigger'
			image
			heading Batch triggering
			image
			image
		link Runtime schema payloads, url='https://trigger.dev/docs/tasks/schemaTask#schematask'
			image
			heading Runtime schema payloads
			image
			image
		link Waits, url='https://trigger.dev/docs/wait'
			image
			heading Waits
			image
			image
		image
		heading Production
		link Concurrency controls, url='https://trigger.dev/product/concurrency-and-queues'
			image
			heading Concurrency controls
		link Multiple environments, url='https://trigger.dev/docs/how-it-works#dev-mode'
			image
			heading Multiple environments
			image
			image
		link No servers to manage, url='https://trigger.dev/docs/how-it-works#trigger-dev-architecture'
			image
			heading No servers to manage
			image
			image
		link Automatic retries, url='https://trigger.dev/docs/errors-retrying'
			image
			heading Automatic retries
			image
			image
		link Build extensions, url='https://trigger.dev/docs/config/extensions/overview#build-extensions'
			image
			heading Build extensions
			image
			image
		link Checkpointing, url='https://trigger.dev/docs/how-it-works#the-checkpoint-resume-system'
			image
			heading Checkpointing
			image
			image
		link Versioning, url='https://trigger.dev/docs/versioning'
			image
			heading Versioning
			image
			image
		image
		heading Observability
		link Live dashboard, url='https://trigger.dev/product/observability-and-monitoring'
			image
			heading Live dashboard
		link Easily test tasks, url='https://trigger.dev/docs/run-tests#run-tests'
			image
			heading Easily test tasks
			image
			image
		link Tags, url='https://trigger.dev/docs/tags#tags'
			image
			heading Tags
			image
			image
		link Advanced run filters, url='https://trigger.dev/product/observability-and-monitoring#advanced-filters'
			image
			heading Advanced run filters
		link Run metadata, url='https://trigger.dev/docs/runs/metadata#run-metadata'
			heading Run metadata
			image
			image
		link Custom alerts, url='https://trigger.dev/product/observability-and-monitoring#alerts'
			image
			heading Custom alerts
		heading Reliable by default
		link Docs, url='https://trigger.dev/docs/v3/errors-retrying'
			image
			image
		tablist, orientation='horizontal'
			tab Task retrying Configure automatic retrying for tasks., selected=True
				heading Task retrying
				paragraph
			tab handleError() Conditional retrying based on the error and run., selected=False
				heading handleError()
				paragraph
			tab retry.onThrow() Fine-grained retrying inside tasks., selected=False
				heading retry.onThrow()
				paragraph
			tab retry.fetch() Automatically retry requests based on the response., selected=False
				heading retry.fetch()
				paragraph
			tab trigger.config Configure default retrying in your config file., selected=False
				heading trigger.config
				paragraph
		tabpanel Task retrying Configure automatic retrying for tasks.
			StaticText import
			StaticText {
			StaticText task
			StaticText }
			StaticText from
			StaticText "@trigger.dev/sdk/v3"
			StaticText ;
			StaticText export
			StaticText const
			StaticText simpleTask
			StaticText =
			StaticText task
			StaticText (
			StaticText {
			StaticText id
			StaticText :
			StaticText "simple-task"
			StaticText ,
			StaticText retry
			StaticText :
			StaticText {
			StaticText maxAttempts
			StaticText :
			StaticText 3
			StaticText ,
			StaticText minTimeoutInMs
			StaticText :
			StaticText 1000
			StaticText ,
			StaticText maxTimeoutInMs
			StaticText :
			StaticText 5000
			StaticText ,
			StaticText factor
			StaticText :
			StaticText 2
			StaticText ,
			StaticText randomize
			StaticText :
			StaticText true
			StaticText ,
			StaticText }
			StaticText ,
			StaticText run
			StaticText :
			StaticText async
			StaticText (
			StaticText payload
			StaticText ,
			StaticText {
			StaticText ctx
			StaticText }
			StaticText )
			StaticText =>
			StaticText {
			StaticText logger
			StaticText .
			StaticText log
			StaticText (
			StaticText `
			StaticText Attempt
			StaticText ${
			StaticText ctx
			StaticText .
			StaticText attempt
			StaticText .
			StaticText number
			StaticText }
			StaticText `
			StaticText )
			StaticText ;
			StaticText try
			StaticText {
			StaticText throw
			StaticText new
			StaticText Error
			StaticText (
			StaticText "This is an error."
			StaticText )
			StaticText ;
			StaticText }
			StaticText catch
			StaticText (
			StaticText error
			StaticText )
			StaticText {
			StaticText // The error was caught, so no retry
			StaticText }
			StaticText throw
			StaticText new
			StaticText Error
			StaticText (
			StaticText "This will cause a retry."
			StaticText )
			StaticText ;
			StaticText }
			StaticText ,
			StaticText }
			StaticText )
			StaticText ;
		heading Works with your existing tech stack…
		image Vercel logo, url='https://trigger.dev/tech-stack/vercel.png'
		image AWS logo, url='https://trigger.dev/tech-stack/aws.png'
		image Remix logo, url='https://trigger.dev/tech-stack/remix.png'
		image Nuxt logo, url='https://trigger.dev/tech-stack/nuxt.png'
		image SvelteKit logo, url='https://trigger.dev/tech-stack/sveltekit.png'
		image Fastify logo, url='https://trigger.dev/tech-stack/fastify.png'
		image RedwoodJS logo, url='https://trigger.dev/tech-stack/redwoodjs.png'
		image Cloudflare logo, url='https://trigger.dev/tech-stack/cloudflare.png'
		image ExpressJS logo, url='https://trigger.dev/tech-stack/expressjs.png'
		image Astro logo, url='https://trigger.dev/tech-stack/astro.png'
		image Google Cloud logo, url='https://trigger.dev/tech-stack/google-cloud.png'
		image Azure logo, url='https://trigger.dev/tech-stack/azure.png'
		image Netlify logo, url='https://trigger.dev/tech-stack/netlify.png'
		image NextJS logo, url='https://trigger.dev/tech-stack/nextjs.png'
		image Heart 1, url='https://trigger.dev/build/_assets/1-OXKMZAUJ.png'
		image Heart 2, url='https://trigger.dev/build/_assets/2-JH3Y3YJF.png'
		image Heart 3, url='https://trigger.dev/build/_assets/3-Y24XLZQ2.png'
		image Heart 4, url='https://trigger.dev/build/_assets/4-I5XLMUM3.png'
		image Heart 5, url='https://trigger.dev/build/_assets/5-H2LZLREV.png'
		heading We love open source. Trigger.dev is Apache 2.0 licensed so you can view the source code, contribute and self-host.
		link 9,900+ stars on GitHub, url='https://github.com/triggerdotdev/trigger.dev'
			image
			image
			heading 9,900+
			paragraph
		link Apache 2.0 open source license, url='https://github.com/triggerdotdev/trigger.dev?tab=Apache-2.0-1-ov-file#readme'
			image
			image
			heading Apache 2.0
			paragraph
		link 2,800+ Discord members, url='https://discord.gg/nkqV9xBYWy'
			image
			image
			heading 2,800+
			paragraph
		heading Loved by developers
		link Join our community, url='https://discord.gg/nkqV9xBYWy'
			image
			image
			image
		figure
			blockquote
				paragraph
					StaticText Trigger.dev is redefining background jobs for modern developers.
			Figcaption
				image, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/e82deee8-b8ec-4092-3980-b268688d1900/public'
				paragraph
					StaticText Paul Copplestone
				paragraph
					StaticText Supabase
				link Supabase logo, url='https://supabase.com/'
					image Supabase logo, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/bfd6d823-7027-4c8b-0117-ef4085b76200/public'
		figure
			blockquote
				paragraph
					StaticText Trigger.dev was the missing piece in our journey to go fully serverless. It enables us to focus entirely on building our product without worrying about the complexities of background jobs. The best part? We’re continuously adding more jobs as we scale!
			Figcaption
				image, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/d60cc0d1-a132-420a-b7fa-bdb67267f800/public'
				paragraph
					StaticText Pontus Abrahamsson
				paragraph
					StaticText Midday
				link Midday logo, url='https://midday.ai/'
					image Midday logo, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/9c0e5ff1-b718-4b67-8e7c-4a45f4697f00/public'
		figure
			blockquote
				paragraph
					StaticText We have critical business functionalities that need to be reliable and replayable in the event of a failure.
					StaticText Trigger.dev helps us deliver messages over WhatsApp, run thousands of jobs with custom LLM workflows, and execute ETL processes to sync our data across multiple databases without breaking a sweat!
			Figcaption
				image, url='https://trigger.dev/testimonials/drpcrd/patryk-maron.png'
				paragraph
					StaticText Patryk Maron
				paragraph
					StaticText DRPCRD
				link DRPCRD logo, url='https://drpcrd.com/'
					image DRPCRD logo, url='https://trigger.dev/testimonials/drpcrd/drpcrd.png'
		figure
			blockquote
				paragraph
					StaticText The first time I used Trigger.dev, I had an a-ha moment, I no longer needed to set up everything with ECS or Lambda. What also stands out is the exceptional support, unlike any I've seen in the web community.
			Figcaption
				image, url='https://trigger.dev/testimonials/ps-bridal/martin-ruzicka.png'
				paragraph
					StaticText Martin Ruzicka
				paragraph
					StaticText P.S. Bridal
				link P.S. Bridal logo, url='https://psbridal.co.uk/'
					image P.S. Bridal logo, url='https://trigger.dev/testimonials/ps-bridal/ps-bridal.png'
		figure
			blockquote
				paragraph
					StaticText We’ve been looking for a product like Trigger.dev for a long time - automation that's simple and dev-focused.
			Figcaption
				image, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/4e3d1187-c27b-4bdc-feac-d2e5297e9a00/public'
				paragraph
					StaticText Han Wang
				paragraph
					StaticText Mintlify
				link Mintlify logo, url='https://mintlify.com/'
					image Mintlify logo, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/1a068830-bc93-451c-b5c2-f76b24e42000/public'
		figure
			blockquote
				paragraph
					StaticText Trigger.dev is a breath of fresh air in a world of 20 second lambda timeouts. Trigger has world-class DX, support, and handles my long-running jobs with ease.
			Figcaption
				image, url='https://trigger.dev/testimonials/propfeeds/ian-janicki.png'
				paragraph
					StaticText Ian Janicki
				paragraph
					StaticText PropFeeds
				link PropFeeds logo, url='https://propfeeds.com/'
					image PropFeeds logo, url='https://trigger.dev/testimonials/propfeeds/propfeeds.png'
		figure
			blockquote
				paragraph
					StaticText I’m in love with Trigger.dev – it’s so much better than the old bull.js + heroku + redis setup that I used to use. You’ve knocked it out of the park with this tool!
			Figcaption
				image, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/6738d30f-ccd5-4342-8764-a2194fc0d900/public'
				paragraph
					StaticText Kushal Byatnal
				paragraph
					StaticText Extend
				link Extend logo, url='https://www.extend.app/'
					image Extend logo, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/0db95e34-61a0-47ff-879d-7698f3084900/public'
		figure
			blockquote
				paragraph
					StaticText We found software that's open-source friendly called MuPDF which runs in Node.js environments. Combined with using Trigger's tasks and runs, it solved our problem instantly. We are now easily processing around 6,000 documents per month anywhere from one page to hundreds of pages.
			Figcaption
				image, url='https://trigger.dev/customers/papermark/marc-seitz.png'
				paragraph
					StaticText Marc Seitz
				paragraph
					StaticText Papermark
				link Papermark logo, url='https://papermark.io/'
					image Papermark logo, url='https://trigger.dev/customers/papermark/papermark-logo.png'
		figure
			blockquote
				paragraph
					StaticText We're using Trigger for our billing, background jobs and deployment pipeline without worrying about operations or infrastructure. It just works.
			Figcaption
				image, url='https://trigger.dev/testimonials/unkey/andreas-thomas-chronark.png'
				paragraph
					StaticText Andreas Thomas
				paragraph
					StaticText Unkey
				link Unkey logo, url='https://www.unkey.com/'
					image Unkey logo, url='https://trigger.dev/testimonials/unkey/unkey.png'
		figure
			blockquote
				paragraph
					StaticText Trigger.dev is undoubtedly one of my most cherished services. Throughout my two-decade career, it’s rare to encounter a product or service that truly resonates and makes a significant impact. It just clicks - an absolute game-changer for us. The support is beyond exceptional, and they genuinely care about the product and their users. I wholeheartedly recommend Trigger!
			Figcaption
				image, url='https://trigger.dev/testimonials/midtown/aaron-spurlock.png'
				paragraph
					StaticText Aaron J. Spurlock
				paragraph
					StaticText Midtown HI
				link Midtown HI logo, url='https://midtownhomeimprovements.com/'
					image Midtown HI logo, url='https://trigger.dev/testimonials/midtown/midtown-logo.png'
		figure
			blockquote
				paragraph
					StaticText Trigger is a central part of our architecture. It’s allowed us to build a resilient system to orchestrates data across multiple systems. We love its observability, replayability, and how easily it slots into our existing codebase. It allows us to refine over time how to set the boundaries between async tasks and synchronous business logic.
			Figcaption
				image, url='https://trigger.dev/testimonials/numi/agree-ahmed.png'
				paragraph
					StaticText Agree Ahmed
				paragraph
					StaticText NUMI
				link NUMI logo, url='https://numi.tech/'
					image NUMI logo, url='https://trigger.dev/testimonials/numi/numi.png'
		figure
			blockquote
				paragraph
					StaticText Trigger.dev has become my go-to tool for new projects. I no longer need an additional server and can forget about horizontal scaling!
			Figcaption
				image, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/f577a1b5-e9bc-46ae-af2e-517c8ebef700/public'
				paragraph
					StaticText Nevo David
				paragraph
					StaticText Novu
				link Novu logo, url='https://novu.co/'
					image Novu logo, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/c89f7bbe-5b66-4b3d-be59-02bcc3a4e800/public'
		figure
			blockquote
				paragraph
					StaticText For AI powered products, Trigger.dev is my clear go-to tool for building robust serverless pipelines stitching together various LLM calls.
			Figcaption
				image, url='https://trigger.dev/testimonials/blee/evan-sandler.png'
				paragraph
					StaticText Evan Sandler
				paragraph
					StaticText Blee
				link Blee logo, url='https://www.blee.com/'
					image Blee logo, url='https://trigger.dev/testimonials/blee/blee-icon.png'
		figure
			blockquote
				paragraph
					StaticText Trigger is packaging end-to-end cron, queues and webhooks platform in a slick interface. Integration was quick and we love the support ❤️
			Figcaption
				image, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/521fe3ce-20f6-4f9b-d8de-b1c3b4724100/public'
				paragraph
					StaticText Aseem Gupta
				paragraph
					StaticText SuperKalam
				link SuperKalam logo, url='https://superkalam.com/'
					image SuperKalam logo, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/cf46d1a3-604d-4eef-2e18-384b767a6600/public'
		figure
			blockquote
				paragraph
					StaticText Using Trigger.dev for our Slack jobs saved us loads of time! It was much easier to set up than a no-code tool.
			Figcaption
				image, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/9c9e9c2e-5ff1-4227-f0d3-514aa2e49300/public'
				paragraph
					StaticText Vlad Matsiiako
				paragraph
					StaticText Infisical
				link Infisical logo, url='https://infisical.com/'
					image Infisical logo, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/c01ec071-f909-4eed-2f0a-6db7aa885c00/public'
		figure
			blockquote
				paragraph
					StaticText We decided to use Trigger.dev over Inngest or setting up our own dedicated solution. We had also looked into UI-based solutions like Zapier and n8n, but they become complex, really slow, expensive and time-consuming to manage for large automations. Trigger.dev made the most overall sense for us when taking dev-speed, cost, scalability and being future-proof into account.
			Figcaption
				image, url='https://trigger.dev/testimonials/heartspace-ai/sohrab-fadai.png'
				paragraph
					StaticText Sohrab Fadai
				paragraph
					StaticText Heartspace AI
				link Heartspace AI logo, url='https://heartspace.ai/'
					image Heartspace AI logo, url='https://trigger.dev/testimonials/heartspace-ai/heartspace-ai.png'
		figure
			blockquote
				paragraph
					StaticText We needed a sophisticated event engine: chaining LLM queries, orchestrating responses, async tasks, persistent state (without long lived servers), complex concurrency, and variable compute power.
					StaticText Trigger’s managed infra and intuitive SDK allowed us to migrate our entire events engine in a day (with incredible support from the team).
			Figcaption
				image, url='https://trigger.dev/testimonials/turnout-labs/michael-parker.png'
				paragraph
					StaticText Michael Parker
				paragraph
					StaticText Turnout Labs
				link Turnout Labs logo, url='https://www.turnoutlabs.ai/'
					image Turnout Labs logo, url='https://trigger.dev/testimonials/turnout-labs/turnout-labs.png'
		figure
			blockquote
				paragraph
					StaticText Trigger.dev is a great way to automate email campaigns with Resend.
			Figcaption
				image, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/3aca9c05-4563-4924-61df-867ec8434200/public'
				paragraph
					StaticText Zeno Rocha
				paragraph
					StaticText Resend
				link Resend logo, url='https://resend.com/'
					image Resend logo, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/a7941fc0-bfe2-4067-9449-9c593cf54c00/public'
		figure
			blockquote
				paragraph
					StaticText Trigger.dev helps us process bounties & tips on Algora without having to duct-tape queues & crons. With standardized timeouts, retries & logging we get full resilience & observability!
			Figcaption
				image, url='https://trigger.dev/testimonials/algora/zafer-cesur.png'
				paragraph
					StaticText Zaf Cesur
				paragraph
					StaticText Algora
				link Algora logo, url='https://algora.io/'
					image Algora logo, url='https://trigger.dev/testimonials/algora/algora.png'
		figure
			blockquote
				paragraph
					StaticText I really enjoyed using Trigger.dev to create jobs through code. I found the API integrations and scheduling features super useful.
			Figcaption
				image, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/36535ea9-56b4-42e3-4e45-ef08d293dd00/public'
				paragraph
					StaticText Adam Shiervani
				paragraph
					StaticText BuildJet
				link BuildJet logo, url='https://buildjet.com/'
					image BuildJet logo, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/06b5fdf7-f7be-424c-a4df-dfa0e3d93100/public'
		figure
			blockquote
				paragraph
					StaticText We love Trigger.dev and it’s had a big impact in dev iteration velocity already.
			Figcaption
				image, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/3e6a3e0f-e4c9-41e9-3881-ffe4cfc50400/public'
				paragraph
					StaticText André Neves
				paragraph
					StaticText ZBD
				link ZBD logo, url='https://zbd.gg/'
					image ZBD logo, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/9bfbbd56-ec03-43ef-663a-15595ae7ab00/public'
		button Read more...
		heading We're backed by the world's best investors, founders and operators
		image Y Combinator, url='https://trigger.dev/build/_assets/yc-logo-XZXGTI4H.png'
		image Supabase, url='https://trigger.dev/build/_assets/supabase-logo-M3YU7ZPR.png'
		image PagerDuty, url='https://trigger.dev/build/_assets/pagerduty-logo-KQPQK6G5.png'
		image Dropbox, url='https://trigger.dev/build/_assets/dropbox-logo-QA6HV7QX.png'
		image Raycast, url='https://trigger.dev/build/_assets/raycast-logo-LZWKA7SA.png'
		image Instabug, url='https://trigger.dev/build/_assets/instabug-logo-3P2FNFZ5.png'
		image Atlassian, url='https://trigger.dev/build/_assets/atlassian-logo-EMV6JCYW.png'
		image Amazon Web Services, url='https://trigger.dev/build/_assets/aws-logo-padding-ZYYRMKKD.png'
		heading Ready to start building?
		paragraph
			StaticText Build and deploy your first task in 3 mins with no timeouts and no infrastructure to manage.
		link Get started for free, url='https://cloud.trigger.dev/'
		Canvas
		heading Simple pricing
		paragraph
			StaticText Only pay for what you use and scale with your needs.
		link Explore pricing, url='https://trigger.dev/pricing'
		Canvas
		heading Self-host
		paragraph
			StaticText Trigger.dev is open source and self-hostable.
		link Self-hosting docs, url='https://trigger.dev/docs/v3/open-source-self-hosting'
	contentinfo
		link Trigger.dev logo, url='https://trigger.dev/#top'
			image Trigger.dev logo
		link Discord link, url='https://trigger.dev/discord'
			image
		link GitHub link, url='https://github.com/triggerdotdev/trigger.dev'
			image GitHub
		link X (Twitter) link, url='https://twitter.com/triggerdotdev'
			image X
		link LinkedIn link, url='https://www.linkedin.com/company/triggerdotdev'
			image
		heading Docs
		link Introduction, url='https://trigger.dev/docs/introduction'
			paragraph
		link Quick start guide, url='https://trigger.dev/docs/quick-start'
			paragraph
		link Guides & examples, url='https://trigger.dev/docs/guides/introduction'
			paragraph
				StaticText Examples
		link Creating a task, url='https://trigger.dev/docs/writing-tasks-introduction'
			paragraph
		link Triggeing a task, url='https://trigger.dev/docs/triggering'
			paragraph
				StaticText Triggering a task
		link Self hosting, url='https://trigger.dev/docs/open-source-self-hosting'
			paragraph
		heading Developers
		link Docs, url='https://trigger.dev/docs'
			paragraph
		link Changelog, url='https://trigger.dev/changelog'
			paragraph
		link Contributing, url='https://github.com/triggerdotdev/trigger.dev/blob/main/CONTRIBUTING.md'
			paragraph
		link Open source, url='https://github.com/triggerdotdev/trigger.dev?tab=Apache-2.0-1-ov-file#readme'
			paragraph
		link GitHub, url='https://github.com/triggerdotdev/trigger.dev'
			image
			paragraph
		heading Product
		link Pricing, url='https://trigger.dev/pricing'
			paragraph
		link How it works, url='https://trigger.dev/#how-it-works'
			paragraph
		link Product, url='https://trigger.dev/product'
			paragraph
				StaticText Features
		link Roadmap, url='https://feedback.trigger.dev/roadmap'
			paragraph
		link FAQs, url='https://trigger.dev/pricing#faqs'
			paragraph
		link Uptime status, url='https://status.trigger.dev/'
			paragraph
		heading Company
		link Blog, url='https://trigger.dev/blog'
			paragraph
		link Email, url='https://trigger.dev/contact'
			paragraph
				StaticText Contact
		link Blog, url='https://trigger.dev/jobs'
			paragraph
				StaticText Careers
		link Privacy policy, url='https://trigger.dev/legal/privacy'
			paragraph
		link Terms and conditions, url='https://trigger.dev/legal'
			paragraph
		link OSS friends, url='https://trigger.dev/oss-friends'
			paragraph
		Iframe Uptime status
			RootWebArea, url='https://status.trigger.dev/badge?theme=dark'
				[a4] link All services are online, center=(457,9174), url='https://status.trigger.dev/'
					image
		paragraph
			StaticText ©
			StaticText 2025
			StaticText Trigger.dev
	StaticText ,
	paragraph
		StaticText We only collect analytics cookies so we can improve your experience.
	[2023] link Privacy policy, center=(84,2665), url='https://trigger.dev/legal/privacy'
	[2027] button Opt-out, center=(209,2665), type=button
	[2030] button Accept, center=(283,2665), type=button
```
</details>

**Reasoning for action:** By clicking on the 'How it works' link, I am moving the user to a section that provides an overview of the functionality and operational aspects of Trigger.dev. This step is essential as it is the first part of the user's journey to explore the product's features, helping them to understand how Trigger.dev can meet their development needs.

**Action:** click(32) # Click on 'How it works' link to explore that section.

**Change Description:** After clicking the 'How it works' link, the main focus of the webpage shifted to the relevant section, changing the URL to 'https://trigger.dev/#how-it-works' and updating the navigation link state to indicate that 'How it works' is now focused. The content of the page also adjusted to display details about the 'How Trigger.dev works' section, including headings, paragraphs, and interactive elements like a video.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://trigger.dev/#how-it-works

https://trigger.dev/product

**Content (before/after):** 

```
RootWebArea Trigger.dev | Open source background jobs with no timeouts., focused, url='https://trigger.dev/#how-it-works'
	banner
		navigation Main
			[25] link Go to homepage, center=(327,1658), url='https://trigger.dev/'
				image Trigger.dev logo
```
<details><summary>Show more</summary>

```
			list
				listitem
					[32] link How it works, center=(479,1658), focused, url='https://trigger.dev/#how-it-works'
				listitem
					[34] link Features, center=(586,1657), url='https://trigger.dev/product'
						button Features, expanded=False
				listitem
					[80] link Changelog, center=(686,1657), url='https://trigger.dev/changelog'
						button Changelog, expanded=False
				listitem
					[113] link Blog, center=(771,1657), url='https://trigger.dev/blog'
						button Blog, expanded=False
				listitem
					[146] link Docs, center=(835,1657), url='https://trigger.dev/docs'
						button Docs, expanded=False
				listitem
					[255] link Pricing, center=(908,1658), url='https://trigger.dev/pricing'
			list
				listitem
					[259] link Trigger.dev Discord server, center=(1320,1658), url='https://trigger.dev/discord'
						image
				listitem
					[262] link Trigger.dev GitHub repo, center=(1408,1658), inner_text=Star 9.8k, url='https://github.com/triggerdotdev/trigger.dev'
						image
						StaticText Star
						StaticText 9.8k
				listitem
					[267] link Login, center=(1504,1658), url='https://cloud.trigger.dev/'
				listitem
					[269] link Get started, center=(1607,1656), url='https://cloud.trigger.dev/'
	main
		heading The open source background jobs platform
		paragraph
			StaticText Write workflows in normal async code and we’ll handle the rest, from queues to elastic scaling. No timeouts, retries, observability, and zero infrastructure to manage.
		link Get started now, url='https://cloud.trigger.dev/'
		image Trigger.dev dashboard, url='https://trigger.dev/images/hero-image-dashboard.png'
		tablist, orientation='horizontal'
			tab AI tasks, selected=True
				Canvas
			tab Video processing, selected=False
				Canvas
			tab Cron, selected=False
				Canvas
			tab Waits, selected=False
				Canvas
			tab Workflows, selected=False
				Canvas
			tab Concurrency, selected=False
				Canvas
			tab Retries, selected=False
				Canvas
			tab PDF to images, selected=False
				Canvas
			tab Semantic search, selected=False
				Canvas
			tab AI Agent, selected=False
				Canvas
			tab Email campaign, selected=False
				Canvas
		tabpanel
			StaticText // Generate an image using OpenAI Dall-E 3
			StaticText export
			StaticText const
			StaticText generateContent
			StaticText =
			StaticText task
			StaticText (
			StaticText {
			StaticText id
			StaticText :
			StaticText "generate-content"
			StaticText ,
			StaticText retry
			StaticText :
			StaticText {
			StaticText maxAttempts
			StaticText :
			StaticText 3
			StaticText ,
			StaticText }
			StaticText ,
			StaticText run
			StaticText :
			StaticText async
			StaticText (
			StaticText {
			StaticText theme
			StaticText ,
			StaticText description
			StaticText }
			StaticText :
			StaticText Payload
			StaticText )
			StaticText =>
			StaticText {
			StaticText const
			StaticText textResult
			StaticText =
			StaticText await
			StaticText openai
			StaticText .
			StaticText chat
			StaticText .
			StaticText completions
			StaticText .
			StaticText create
			StaticText (
			StaticText {
			StaticText model
			StaticText :
			StaticText "gpt-4o"
			StaticText ,
			StaticText messages
			StaticText :
			StaticText generateTextPrompt
			StaticText (
			StaticText theme
			StaticText ,
			StaticText description
			StaticText )
			StaticText ,
			StaticText }
			StaticText )
			StaticText ;
			StaticText if
			StaticText (
			StaticText !
			StaticText textResult
			StaticText .
			StaticText choices
			StaticText [
			StaticText 0
			StaticText ]
			StaticText )
			StaticText {
			StaticText throw
			StaticText new
			StaticText Error
			StaticText (
			StaticText "No content, retrying…"
			StaticText )
			StaticText ;
			StaticText }
			StaticText const
			StaticText imageResult
			StaticText =
			StaticText await
			StaticText openai
			StaticText .
			StaticText images
			StaticText .
			StaticText generate
			StaticText (
			StaticText {
			StaticText model
			StaticText :
			StaticText "dall-e-3"
			StaticText ,
			StaticText prompt
			StaticText :
			StaticText generateImagePrompt
			StaticText (
			StaticText theme
			StaticText ,
			StaticText description
			StaticText )
			StaticText ,
			StaticText }
			StaticText )
			StaticText ;
			StaticText if
			StaticText (
			StaticText !
			StaticText imageResult
			StaticText .
			StaticText data
			StaticText [
			StaticText 0
			StaticText ]
			StaticText )
			StaticText {
			StaticText throw
			StaticText new
			StaticText Error
			StaticText (
			StaticText "No image, retrying…"
			StaticText )
			StaticText ;
			StaticText }
			StaticText return
			StaticText {
			StaticText text
			StaticText :
			StaticText textResult
			StaticText .
			StaticText choices
			StaticText [
			StaticText 0
			StaticText ]
			StaticText ,
			StaticText image
			StaticText :
			StaticText imageResult
			StaticText .
			StaticText data
			StaticText [
			StaticText 0
			StaticText ]
			StaticText .
			StaticText url
			StaticText ,
			StaticText }
			StaticText ;
			StaticText }
			StaticText ,
			StaticText }
			StaticText )
			StaticText ;
			paragraph
				StaticText Reliably call AI APIs with no timeouts, automatic retrying, and tracing. Use existing Node.js SDKs and code from your repo.
		heading Trusted by developers at companies all over the world
		image
		[752] video, center=(960,2100)
		image
		image
		image
		image
		image
		heading How Trigger.dev works
		[740] button Play and pause video, center=(1331,1730), inner_text=Play
			paragraph
		[743] button Restart video, center=(1407,1730), inner_text=Replay
			image
			paragraph
				StaticText Replay
		[746] button Toggle fullscreen, center=(1507,1730), inner_text=Full screen
			paragraph
				StaticText Full screen
		heading Deploy and scale to any size
		Canvas
		Canvas
		heading No timeouts
		paragraph
			StaticText Write simple, reliable code and never hit a timeout.
		heading Pay for what you use
		paragraph
			StaticText Only pay when your code is actually executing.
		Canvas
		Canvas
		heading No servers to manage
		paragraph
			StaticText We deploy your tasks and handle scaling for you.
		heading Find and fix bugs fast
		heading Alerts for errors
		paragraph
			StaticText Get notified via email, Slack or webhooks when your tasks or deployments fail.
		Canvas
		image hero, url='https://trigger.dev/patterns/alerts-bg.png'
		heading Advanced filtering
		paragraph
			StaticText Find runs fast using advanced filtering options, then apply bulk actions to multiple tasks at once.
		Canvas
		image hero, url='https://trigger.dev/patterns/alerts-bg.png'
		heading Versioning
		paragraph
			StaticText Each deploy is an atomic version ensuring started tasks are not affected by code changes.
		Canvas
		image hero, url='https://trigger.dev/patterns/alerts-bg.png'
		heading All the tools you need to ship
		link View all features, url='https://trigger.dev/product'
		image
		heading Development
		link Cron schedules, url='https://trigger.dev/product/scheduled-tasks'
			image
			heading Cron schedules
		link Realtime run status updates, url='https://trigger.dev/docs/realtime/overview#realtime-overview'
			image
			heading Realtime run status updates
			image
			image
		link Write tasks in async code, url='https://trigger.dev/docs/guides/introduction'
			image
			heading Write tasks in async code
			image
			image
		link React hooks, url='https://trigger.dev/docs/frontend/react-hooks#react-hooks'
			image
			heading React hooks
			image
			image
		link Max duration, url='https://trigger.dev/docs/runs/max-duration#max-duration'
			image
			heading Max duration
			image
			image
		link Batch triggering, url='https://trigger.dev/docs/triggering#tasks-batchtrigger'
			image
			heading Batch triggering
			image
			image
		link Runtime schema payloads, url='https://trigger.dev/docs/tasks/schemaTask#schematask'
			image
			heading Runtime schema payloads
			image
			image
		link Waits, url='https://trigger.dev/docs/wait'
			image
			heading Waits
			image
			image
		image
		heading Production
		link Concurrency controls, url='https://trigger.dev/product/concurrency-and-queues'
			image
			heading Concurrency controls
		link Multiple environments, url='https://trigger.dev/docs/how-it-works#dev-mode'
			image
			heading Multiple environments
			image
			image
		link No servers to manage, url='https://trigger.dev/docs/how-it-works#trigger-dev-architecture'
			image
			heading No servers to manage
			image
			image
		link Automatic retries, url='https://trigger.dev/docs/errors-retrying'
			image
			heading Automatic retries
			image
			image
		link Build extensions, url='https://trigger.dev/docs/config/extensions/overview#build-extensions'
			image
			heading Build extensions
			image
			image
		link Checkpointing, url='https://trigger.dev/docs/how-it-works#the-checkpoint-resume-system'
			image
			heading Checkpointing
			image
			image
		link Versioning, url='https://trigger.dev/docs/versioning'
			image
			heading Versioning
			image
			image
		image
		heading Observability
		link Live dashboard, url='https://trigger.dev/product/observability-and-monitoring'
			image
			heading Live dashboard
		link Easily test tasks, url='https://trigger.dev/docs/run-tests#run-tests'
			image
			heading Easily test tasks
			image
			image
		link Tags, url='https://trigger.dev/docs/tags#tags'
			image
			heading Tags
			image
			image
		link Advanced run filters, url='https://trigger.dev/product/observability-and-monitoring#advanced-filters'
			image
			heading Advanced run filters
		link Run metadata, url='https://trigger.dev/docs/runs/metadata#run-metadata'
			heading Run metadata
			image
			image
		link Custom alerts, url='https://trigger.dev/product/observability-and-monitoring#alerts'
			image
			heading Custom alerts
		heading Reliable by default
		link Docs, url='https://trigger.dev/docs/v3/errors-retrying'
			image
			image
		tablist, orientation='horizontal'
			tab Task retrying Configure automatic retrying for tasks., selected=True
				heading Task retrying
				paragraph
			tab handleError() Conditional retrying based on the error and run., selected=False
				heading handleError()
				paragraph
			tab retry.onThrow() Fine-grained retrying inside tasks., selected=False
				heading retry.onThrow()
				paragraph
			tab retry.fetch() Automatically retry requests based on the response., selected=False
				heading retry.fetch()
				paragraph
			tab trigger.config Configure default retrying in your config file., selected=False
				heading trigger.config
				paragraph
		tabpanel Task retrying Configure automatic retrying for tasks.
			StaticText import
			StaticText {
			StaticText task
			StaticText }
			StaticText from
			StaticText "@trigger.dev/sdk/v3"
			StaticText ;
			StaticText export
			StaticText const
			StaticText simpleTask
			StaticText =
			StaticText task
			StaticText (
			StaticText {
			StaticText id
			StaticText :
			StaticText "simple-task"
			StaticText ,
			StaticText retry
			StaticText :
			StaticText {
			StaticText maxAttempts
			StaticText :
			StaticText 3
			StaticText ,
			StaticText minTimeoutInMs
			StaticText :
			StaticText 1000
			StaticText ,
			StaticText maxTimeoutInMs
			StaticText :
			StaticText 5000
			StaticText ,
			StaticText factor
			StaticText :
			StaticText 2
			StaticText ,
			StaticText randomize
			StaticText :
			StaticText true
			StaticText ,
			StaticText }
			StaticText ,
			StaticText run
			StaticText :
			StaticText async
			StaticText (
			StaticText payload
			StaticText ,
			StaticText {
			StaticText ctx
			StaticText }
			StaticText )
			StaticText =>
			StaticText {
			StaticText logger
			StaticText .
			StaticText log
			StaticText (
			StaticText `
			StaticText Attempt
			StaticText ${
			StaticText ctx
			StaticText .
			StaticText attempt
			StaticText .
			StaticText number
			StaticText }
			StaticText `
			StaticText )
			StaticText ;
			StaticText try
			StaticText {
			StaticText throw
			StaticText new
			StaticText Error
			StaticText (
			StaticText "This is an error."
			StaticText )
			StaticText ;
			StaticText }
			StaticText catch
			StaticText (
			StaticText error
			StaticText )
			StaticText {
			StaticText // The error was caught, so no retry
			StaticText }
			StaticText throw
			StaticText new
			StaticText Error
			StaticText (
			StaticText "This will cause a retry."
			StaticText )
			StaticText ;
			StaticText }
			StaticText ,
			StaticText }
			StaticText )
			StaticText ;
		heading Works with your existing tech stack…
		image Vercel logo, url='https://trigger.dev/tech-stack/vercel.png'
		image AWS logo, url='https://trigger.dev/tech-stack/aws.png'
		image Remix logo, url='https://trigger.dev/tech-stack/remix.png'
		image Nuxt logo, url='https://trigger.dev/tech-stack/nuxt.png'
		image SvelteKit logo, url='https://trigger.dev/tech-stack/sveltekit.png'
		image Fastify logo, url='https://trigger.dev/tech-stack/fastify.png'
		image RedwoodJS logo, url='https://trigger.dev/tech-stack/redwoodjs.png'
		image Cloudflare logo, url='https://trigger.dev/tech-stack/cloudflare.png'
		image ExpressJS logo, url='https://trigger.dev/tech-stack/expressjs.png'
		image Astro logo, url='https://trigger.dev/tech-stack/astro.png'
		image Google Cloud logo, url='https://trigger.dev/tech-stack/google-cloud.png'
		image Azure logo, url='https://trigger.dev/tech-stack/azure.png'
		image Netlify logo, url='https://trigger.dev/tech-stack/netlify.png'
		image NextJS logo, url='https://trigger.dev/tech-stack/nextjs.png'
		image Heart 1, url='https://trigger.dev/build/_assets/1-OXKMZAUJ.png'
		image Heart 2, url='https://trigger.dev/build/_assets/2-JH3Y3YJF.png'
		image Heart 3, url='https://trigger.dev/build/_assets/3-Y24XLZQ2.png'
		image Heart 4, url='https://trigger.dev/build/_assets/4-I5XLMUM3.png'
		image Heart 5, url='https://trigger.dev/build/_assets/5-H2LZLREV.png'
		heading We love open source. Trigger.dev is Apache 2.0 licensed so you can view the source code, contribute and self-host.
		link 9,900+ stars on GitHub, url='https://github.com/triggerdotdev/trigger.dev'
			image
			image
			heading 9,900+
			paragraph
		link Apache 2.0 open source license, url='https://github.com/triggerdotdev/trigger.dev?tab=Apache-2.0-1-ov-file#readme'
			image
			image
			heading Apache 2.0
			paragraph
		link 2,800+ Discord members, url='https://discord.gg/nkqV9xBYWy'
			image
			image
			heading 2,800+
			paragraph
		heading Loved by developers
		link Join our community, url='https://discord.gg/nkqV9xBYWy'
			image
			image
			image
		figure
			blockquote
				paragraph
					StaticText Trigger.dev is redefining background jobs for modern developers.
			Figcaption
				image, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/e82deee8-b8ec-4092-3980-b268688d1900/public'
				paragraph
					StaticText Paul Copplestone
				paragraph
					StaticText Supabase
				link Supabase logo, url='https://supabase.com/'
					image Supabase logo, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/bfd6d823-7027-4c8b-0117-ef4085b76200/public'
		figure
			blockquote
				paragraph
					StaticText Trigger.dev was the missing piece in our journey to go fully serverless. It enables us to focus entirely on building our product without worrying about the complexities of background jobs. The best part? We’re continuously adding more jobs as we scale!
			Figcaption
				image, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/d60cc0d1-a132-420a-b7fa-bdb67267f800/public'
				paragraph
					StaticText Pontus Abrahamsson
				paragraph
					StaticText Midday
				link Midday logo, url='https://midday.ai/'
					image Midday logo, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/9c0e5ff1-b718-4b67-8e7c-4a45f4697f00/public'
		figure
			blockquote
				paragraph
					StaticText We have critical business functionalities that need to be reliable and replayable in the event of a failure.
					StaticText Trigger.dev helps us deliver messages over WhatsApp, run thousands of jobs with custom LLM workflows, and execute ETL processes to sync our data across multiple databases without breaking a sweat!
			Figcaption
				image, url='https://trigger.dev/testimonials/drpcrd/patryk-maron.png'
				paragraph
					StaticText Patryk Maron
				paragraph
					StaticText DRPCRD
				link DRPCRD logo, url='https://drpcrd.com/'
					image DRPCRD logo, url='https://trigger.dev/testimonials/drpcrd/drpcrd.png'
		figure
			blockquote
				paragraph
					StaticText The first time I used Trigger.dev, I had an a-ha moment, I no longer needed to set up everything with ECS or Lambda. What also stands out is the exceptional support, unlike any I've seen in the web community.
			Figcaption
				image, url='https://trigger.dev/testimonials/ps-bridal/martin-ruzicka.png'
				paragraph
					StaticText Martin Ruzicka
				paragraph
					StaticText P.S. Bridal
				link P.S. Bridal logo, url='https://psbridal.co.uk/'
					image P.S. Bridal logo, url='https://trigger.dev/testimonials/ps-bridal/ps-bridal.png'
		figure
			blockquote
				paragraph
					StaticText We’ve been looking for a product like Trigger.dev for a long time - automation that's simple and dev-focused.
			Figcaption
				image, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/4e3d1187-c27b-4bdc-feac-d2e5297e9a00/public'
				paragraph
					StaticText Han Wang
				paragraph
					StaticText Mintlify
				link Mintlify logo, url='https://mintlify.com/'
					image Mintlify logo, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/1a068830-bc93-451c-b5c2-f76b24e42000/public'
		figure
			blockquote
				paragraph
					StaticText Trigger.dev is a breath of fresh air in a world of 20 second lambda timeouts. Trigger has world-class DX, support, and handles my long-running jobs with ease.
			Figcaption
				image, url='https://trigger.dev/testimonials/propfeeds/ian-janicki.png'
				paragraph
					StaticText Ian Janicki
				paragraph
					StaticText PropFeeds
				link PropFeeds logo, url='https://propfeeds.com/'
					image PropFeeds logo, url='https://trigger.dev/testimonials/propfeeds/propfeeds.png'
		figure
			blockquote
				paragraph
					StaticText I’m in love with Trigger.dev – it’s so much better than the old bull.js + heroku + redis setup that I used to use. You’ve knocked it out of the park with this tool!
			Figcaption
				image, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/6738d30f-ccd5-4342-8764-a2194fc0d900/public'
				paragraph
					StaticText Kushal Byatnal
				paragraph
					StaticText Extend
				link Extend logo, url='https://www.extend.app/'
					image Extend logo, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/0db95e34-61a0-47ff-879d-7698f3084900/public'
		figure
			blockquote
				paragraph
					StaticText We found software that's open-source friendly called MuPDF which runs in Node.js environments. Combined with using Trigger's tasks and runs, it solved our problem instantly. We are now easily processing around 6,000 documents per month anywhere from one page to hundreds of pages.
			Figcaption
				image, url='https://trigger.dev/customers/papermark/marc-seitz.png'
				paragraph
					StaticText Marc Seitz
				paragraph
					StaticText Papermark
				link Papermark logo, url='https://papermark.io/'
					image Papermark logo, url='https://trigger.dev/customers/papermark/papermark-logo.png'
		figure
			blockquote
				paragraph
					StaticText We're using Trigger for our billing, background jobs and deployment pipeline without worrying about operations or infrastructure. It just works.
			Figcaption
				image, url='https://trigger.dev/testimonials/unkey/andreas-thomas-chronark.png'
				paragraph
					StaticText Andreas Thomas
				paragraph
					StaticText Unkey
				link Unkey logo, url='https://www.unkey.com/'
					image Unkey logo, url='https://trigger.dev/testimonials/unkey/unkey.png'
		figure
			blockquote
				paragraph
					StaticText Trigger.dev is undoubtedly one of my most cherished services. Throughout my two-decade career, it’s rare to encounter a product or service that truly resonates and makes a significant impact. It just clicks - an absolute game-changer for us. The support is beyond exceptional, and they genuinely care about the product and their users. I wholeheartedly recommend Trigger!
			Figcaption
				image, url='https://trigger.dev/testimonials/midtown/aaron-spurlock.png'
				paragraph
					StaticText Aaron J. Spurlock
				paragraph
					StaticText Midtown HI
				link Midtown HI logo, url='https://midtownhomeimprovements.com/'
					image Midtown HI logo, url='https://trigger.dev/testimonials/midtown/midtown-logo.png'
		figure
			blockquote
				paragraph
					StaticText Trigger is a central part of our architecture. It’s allowed us to build a resilient system to orchestrates data across multiple systems. We love its observability, replayability, and how easily it slots into our existing codebase. It allows us to refine over time how to set the boundaries between async tasks and synchronous business logic.
			Figcaption
				image, url='https://trigger.dev/testimonials/numi/agree-ahmed.png'
				paragraph
					StaticText Agree Ahmed
				paragraph
					StaticText NUMI
				link NUMI logo, url='https://numi.tech/'
					image NUMI logo, url='https://trigger.dev/testimonials/numi/numi.png'
		figure
			blockquote
				paragraph
					StaticText Trigger.dev has become my go-to tool for new projects. I no longer need an additional server and can forget about horizontal scaling!
			Figcaption
				image, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/f577a1b5-e9bc-46ae-af2e-517c8ebef700/public'
				paragraph
					StaticText Nevo David
				paragraph
					StaticText Novu
				link Novu logo, url='https://novu.co/'
					image Novu logo, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/c89f7bbe-5b66-4b3d-be59-02bcc3a4e800/public'
		figure
			blockquote
				paragraph
					StaticText For AI powered products, Trigger.dev is my clear go-to tool for building robust serverless pipelines stitching together various LLM calls.
			Figcaption
				image, url='https://trigger.dev/testimonials/blee/evan-sandler.png'
				paragraph
					StaticText Evan Sandler
				paragraph
					StaticText Blee
				link Blee logo, url='https://www.blee.com/'
					image Blee logo, url='https://trigger.dev/testimonials/blee/blee-icon.png'
		figure
			blockquote
				paragraph
					StaticText Trigger is packaging end-to-end cron, queues and webhooks platform in a slick interface. Integration was quick and we love the support ❤️
			Figcaption
				image, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/521fe3ce-20f6-4f9b-d8de-b1c3b4724100/public'
				paragraph
					StaticText Aseem Gupta
				paragraph
					StaticText SuperKalam
				link SuperKalam logo, url='https://superkalam.com/'
					image SuperKalam logo, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/cf46d1a3-604d-4eef-2e18-384b767a6600/public'
		figure
			blockquote
				paragraph
					StaticText Using Trigger.dev for our Slack jobs saved us loads of time! It was much easier to set up than a no-code tool.
			Figcaption
				image, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/9c9e9c2e-5ff1-4227-f0d3-514aa2e49300/public'
				paragraph
					StaticText Vlad Matsiiako
				paragraph
					StaticText Infisical
				link Infisical logo, url='https://infisical.com/'
					image Infisical logo, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/c01ec071-f909-4eed-2f0a-6db7aa885c00/public'
		figure
			blockquote
				paragraph
					StaticText We decided to use Trigger.dev over Inngest or setting up our own dedicated solution. We had also looked into UI-based solutions like Zapier and n8n, but they become complex, really slow, expensive and time-consuming to manage for large automations. Trigger.dev made the most overall sense for us when taking dev-speed, cost, scalability and being future-proof into account.
			Figcaption
				image, url='https://trigger.dev/testimonials/heartspace-ai/sohrab-fadai.png'
				paragraph
					StaticText Sohrab Fadai
				paragraph
					StaticText Heartspace AI
				link Heartspace AI logo, url='https://heartspace.ai/'
					image Heartspace AI logo, url='https://trigger.dev/testimonials/heartspace-ai/heartspace-ai.png'
		figure
			blockquote
				paragraph
					StaticText We needed a sophisticated event engine: chaining LLM queries, orchestrating responses, async tasks, persistent state (without long lived servers), complex concurrency, and variable compute power.
					StaticText Trigger’s managed infra and intuitive SDK allowed us to migrate our entire events engine in a day (with incredible support from the team).
			Figcaption
				image, url='https://trigger.dev/testimonials/turnout-labs/michael-parker.png'
				paragraph
					StaticText Michael Parker
				paragraph
					StaticText Turnout Labs
				link Turnout Labs logo, url='https://www.turnoutlabs.ai/'
					image Turnout Labs logo, url='https://trigger.dev/testimonials/turnout-labs/turnout-labs.png'
		figure
			blockquote
				paragraph
					StaticText Trigger.dev is a great way to automate email campaigns with Resend.
			Figcaption
				image, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/3aca9c05-4563-4924-61df-867ec8434200/public'
				paragraph
					StaticText Zeno Rocha
				paragraph
					StaticText Resend
				link Resend logo, url='https://resend.com/'
					image Resend logo, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/a7941fc0-bfe2-4067-9449-9c593cf54c00/public'
		figure
			blockquote
				paragraph
					StaticText Trigger.dev helps us process bounties & tips on Algora without having to duct-tape queues & crons. With standardized timeouts, retries & logging we get full resilience & observability!
			Figcaption
				image, url='https://trigger.dev/testimonials/algora/zafer-cesur.png'
				paragraph
					StaticText Zaf Cesur
				paragraph
					StaticText Algora
				link Algora logo, url='https://algora.io/'
					image Algora logo, url='https://trigger.dev/testimonials/algora/algora.png'
		figure
			blockquote
				paragraph
					StaticText I really enjoyed using Trigger.dev to create jobs through code. I found the API integrations and scheduling features super useful.
			Figcaption
				image, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/36535ea9-56b4-42e3-4e45-ef08d293dd00/public'
				paragraph
					StaticText Adam Shiervani
				paragraph
					StaticText BuildJet
				link BuildJet logo, url='https://buildjet.com/'
					image BuildJet logo, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/06b5fdf7-f7be-424c-a4df-dfa0e3d93100/public'
		figure
			blockquote
				paragraph
					StaticText We love Trigger.dev and it’s had a big impact in dev iteration velocity already.
			Figcaption
				image, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/3e6a3e0f-e4c9-41e9-3881-ffe4cfc50400/public'
				paragraph
					StaticText André Neves
				paragraph
					StaticText ZBD
				link ZBD logo, url='https://zbd.gg/'
					image ZBD logo, url='https://imagedelivery.net/3TbraffuDZ4aEf8KWOmI_w/9bfbbd56-ec03-43ef-663a-15595ae7ab00/public'
		button Read more...
		heading We're backed by the world's best investors, founders and operators
		image Y Combinator, url='https://trigger.dev/build/_assets/yc-logo-XZXGTI4H.png'
		image Supabase, url='https://trigger.dev/build/_assets/supabase-logo-M3YU7ZPR.png'
		image PagerDuty, url='https://trigger.dev/build/_assets/pagerduty-logo-KQPQK6G5.png'
		image Dropbox, url='https://trigger.dev/build/_assets/dropbox-logo-QA6HV7QX.png'
		image Raycast, url='https://trigger.dev/build/_assets/raycast-logo-LZWKA7SA.png'
		image Instabug, url='https://trigger.dev/build/_assets/instabug-logo-3P2FNFZ5.png'
		image Atlassian, url='https://trigger.dev/build/_assets/atlassian-logo-EMV6JCYW.png'
		image Amazon Web Services, url='https://trigger.dev/build/_assets/aws-logo-padding-ZYYRMKKD.png'
		heading Ready to start building?
		paragraph
			StaticText Build and deploy your first task in 3 mins with no timeouts and no infrastructure to manage.
		link Get started for free, url='https://cloud.trigger.dev/'
		Canvas
		heading Simple pricing
		paragraph
			StaticText Only pay for what you use and scale with your needs.
		link Explore pricing, url='https://trigger.dev/pricing'
		Canvas
		heading Self-host
		paragraph
			StaticText Trigger.dev is open source and self-hostable.
		link Self-hosting docs, url='https://trigger.dev/docs/v3/open-source-self-hosting'
	contentinfo
		link Trigger.dev logo, url='https://trigger.dev/#top'
			image Trigger.dev logo
		link Discord link, url='https://trigger.dev/discord'
			image
		link GitHub link, url='https://github.com/triggerdotdev/trigger.dev'
			image GitHub
		link X (Twitter) link, url='https://twitter.com/triggerdotdev'
			image X
		link LinkedIn link, url='https://www.linkedin.com/company/triggerdotdev'
			image
		heading Docs
		link Introduction, url='https://trigger.dev/docs/introduction'
			paragraph
		link Quick start guide, url='https://trigger.dev/docs/quick-start'
			paragraph
		link Guides & examples, url='https://trigger.dev/docs/guides/introduction'
			paragraph
				StaticText Examples
		link Creating a task, url='https://trigger.dev/docs/writing-tasks-introduction'
			paragraph
		link Triggeing a task, url='https://trigger.dev/docs/triggering'
			paragraph
				StaticText Triggering a task
		link Self hosting, url='https://trigger.dev/docs/open-source-self-hosting'
			paragraph
		heading Developers
		link Docs, url='https://trigger.dev/docs'
			paragraph
		link Changelog, url='https://trigger.dev/changelog'
			paragraph
		link Contributing, url='https://github.com/triggerdotdev/trigger.dev/blob/main/CONTRIBUTING.md'
			paragraph
		link Open source, url='https://github.com/triggerdotdev/trigger.dev?tab=Apache-2.0-1-ov-file#readme'
			paragraph
		link GitHub, url='https://github.com/triggerdotdev/trigger.dev'
			image
			paragraph
		heading Product
		link Pricing, url='https://trigger.dev/pricing'
			paragraph
		link How it works, url='https://trigger.dev/#how-it-works'
			paragraph
		link Product, url='https://trigger.dev/product'
			paragraph
				StaticText Features
		link Roadmap, url='https://feedback.trigger.dev/roadmap'
			paragraph
		link FAQs, url='https://trigger.dev/pricing#faqs'
			paragraph
		link Uptime status, url='https://status.trigger.dev/'
			paragraph
		heading Company
		link Blog, url='https://trigger.dev/blog'
			paragraph
		link Email, url='https://trigger.dev/contact'
			paragraph
				StaticText Contact
		link Blog, url='https://trigger.dev/jobs'
			paragraph
				StaticText Careers
		link Privacy policy, url='https://trigger.dev/legal/privacy'
			paragraph
		link Terms and conditions, url='https://trigger.dev/legal'
			paragraph
		link OSS friends, url='https://trigger.dev/oss-friends'
			paragraph
		Iframe Uptime status
			RootWebArea, url='https://status.trigger.dev/badge?theme=dark'
				[a4] link All services are online, center=(457,9174), url='https://status.trigger.dev/'
					image
		paragraph
			StaticText ©
			StaticText 2025
			StaticText Trigger.dev
	StaticText ,
	paragraph
		StaticText We only collect analytics cookies so we can improve your experience.
	[2023] link Privacy policy, center=(84,2665), url='https://trigger.dev/legal/privacy'
	[2027] button Opt-out, center=(209,2665), type=button
	[2030] button Accept, center=(283,2665), type=button
```
</details>



```
RootWebArea Product | Trigger.dev, focused, url='https://trigger.dev/product'
	banner
		navigation Main
			[25] link Go to homepage, center=(327,30), url='https://trigger.dev/'
				image Trigger.dev logo
```
<details><summary>Show more</summary>

```
			list
				listitem
					[32] link How it works, center=(479,30), url='https://trigger.dev/#how-it-works'
				listitem
					[34] link Features, center=(586,29), url='https://trigger.dev/product'
						button Features, expanded=True, focused
						generic
							heading Product features
							[2091] link All features, center=(835,80), url='https://trigger.dev/product'
							[2096] link Trigger.dev Realtime Connect your frontend app to your tasks., center=(711,135), inner_text=Trigger.dev Realtime

Connect your frontend app to your tasks., url='https://trigger.dev/launchweek/0/realtime'
								image
								heading Trigger.dev Realtime
								paragraph
							[2102] link Concurrency & queues Control how many tasks run at once., center=(711,195), inner_text=Concurrency & queues

Control how many tasks run at once., url='https://trigger.dev/product/concurrency-and-queues'
								image
								heading Concurrency & queues
								paragraph
							[2108] link Scheduled tasks Durable cron schedules without timeouts., center=(711,255), inner_text=Scheduled tasks

Durable cron schedules without timeouts., url='https://trigger.dev/product/scheduled-tasks'
								image
								heading Scheduled tasks
								paragraph
							[2114] link Observability & monitoring Real-time monitoring and tracing of tasks., center=(711,315), inner_text=Observability & monitoring

Real-time monitoring and tracing of tasks., url='https://trigger.dev/product/observability-and-monitoring'
								image
								heading Observability & monitoring
								paragraph
							[2120] link Roadmap See what we're building next., center=(711,375), inner_text=Roadmap

See what we're building next., url='https://feedback.trigger.dev/roadmap'
								image
								heading Roadmap
								paragraph
								image
								image
				listitem
					[80] link Changelog, center=(686,29), url='https://trigger.dev/changelog'
						button Changelog, expanded=False
				listitem
					[113] link Blog, center=(771,29), url='https://trigger.dev/blog'
						button Blog, expanded=False
				listitem
					[146] link Docs, center=(835,29), url='https://trigger.dev/docs'
						button Docs, expanded=False
				listitem
					[255] link Pricing, center=(908,30), url='https://trigger.dev/pricing'
			list
				listitem
					[259] link Trigger.dev Discord server, center=(1320,30), url='https://trigger.dev/discord'
						image
				listitem
					[262] link Trigger.dev GitHub repo, center=(1408,30), inner_text=Star 9.8k, url='https://github.com/triggerdotdev/trigger.dev'
						image
						StaticText Star
						StaticText 9.8k
				listitem
					[267] link Login, center=(1504,30), url='https://cloud.trigger.dev/'
				listitem
					[269] link Get started, center=(1607,28), url='https://cloud.trigger.dev/'
	main
		heading Reliable background jobs without the headache of managing servers
		paragraph
			StaticText Trigger.dev has no timeouts, gives you control over concurrency, includes built-in monitoring, and scales to handle an elastic workload. You get all this and more without managing servers yourself.
		image
		heading Observability & monitoring
		image
		heading Concurrency & queues
		image
		heading Durable cron schedules
		image
		heading No infrastructure to manage
		image
		heading Advanced filtering
		image
		heading AI features
		image
		heading Automatic retries
		image
		heading Bulk replaying
		image
		heading Tag your tasks
		image
		heading Real-time alerts
		image
		heading Write normal code
		image
		heading Batch triggers
		image
		heading Long-running tasks
		image
		heading Checkpointing
		image
		heading Real-time alerts
		image
		heading Write normal code
		image
		heading Batch triggers
		image
		heading Long-running tasks
		image
		heading Checkpointing
		image
		heading Observability & monitoring
		image
		heading Concurrency & queues
		image
		heading Durable cron schedules
		image
		heading No infrastructure to manage
		image
		heading Advanced filtering
		image
		heading AI features
		image
		heading Automatic retries
		image
		heading Bulk replaying
		image
		heading Tag your tasks
		heading Feature spotlight
		[2255] link Trigger.dev Realtime Realtime is the bridge between your background tasks running on Trigger.dev and your frontend applications. It allows you to subscribe to runs and get live updates on the run status and more. Learn more, center=(654,932), inner_text=Trigger.dev Realtime

Realtime is the bridge between your background tasks running on Trigger.dev and your frontend applications. It allows you to subscribe to runs and get live updates on the run status and more.

Learn more, url='https://trigger.dev/docs/realtime/overview'
			Canvas
			heading Trigger.dev Realtime
			paragraph
			paragraph
		[2267] link Concurrency & queues Set concurrency rules to manage how multiple tasks execute. Run tasks sequentially or in parallel, and create custom queues for different users or tiers using concurrency keys. Learn more, center=(1265,932), inner_text=Concurrency & queues

Set concurrency rules to manage how multiple tasks execute. Run tasks sequentially or in parallel, and create custom queues for different users or tiers using concurrency keys.

Learn more, url='https://trigger.dev/product/concurrency-and-queues'
			Canvas
			heading Concurrency & queues
			paragraph
			paragraph
		link Durable cron schedules Create and attach recurring schedules of up to a year, which never hit a function timeout. These can be either created or attached in your codebase, or added in our dashboard. Learn more, url='https://trigger.dev/product/scheduled-tasks'
			Canvas
			heading Durable cron schedules
			paragraph
			paragraph
		link Observability & monitoring Our live run page, powered by OpenTelemetry, provides a real-time trace view of each run as it executes. This is great for viewing detailed logs of your task and debuging errors if they occur. Learn more, url='https://trigger.dev/product/observability-and-monitoring'
			Canvas
			heading Observability & monitoring
			paragraph
			paragraph
		heading Explore the full set of powerful features
		image
		heading No infrastructure to manage
		paragraph
			StaticText Your tasks are deployed and automatically scaled on Trigger.dev's long-running servers, which completely eliminates timeouts. This makes development easy without the worry of managing infrastructure.
		image
		heading Long-running tasks
		paragraph
			StaticText Trigger.dev makes it easy to run background jobs that take a long time to complete. So you can handle resource-heavy tasks like video processing, audio manipulation, PDF conversion, or large CSV processing all without timeouts.
		image
		heading AI features
		paragraph
			StaticText Trigger.dev is perfect for AI tasks that often exceed serverless timeouts, like waiting for LLM responses. Our
			link Realtime feature, url='https://trigger.dev/docs/realtime/overview'
			StaticText also lets you stream results directly to your frontend.
		image
		heading Checkpointing
		paragraph
			StaticText Tasks are inherently durable, thanks to our checkpointing feature. It allows the state of your task to be saved and resumed later, ensuring reliability. We also freeze tasks during waits meaning you only pay for task execution time.
		image
		heading Write normal code
		paragraph
			StaticText With Trigger.dev, you just write your usual async code, and it works seamlessly. No need to split your code into chunks to avoid serverless timeouts, as you deploy your tasks to our long-running servers.
			link Tasks docs, url='https://trigger.dev/docs/tasks-overview'
				image
				image
		image
		heading Batch triggering
		paragraph
			StaticText Use
			code
				StaticText batchTrigger()
			StaticText to initiate multiple runs of a task with custom payloads and options. For fanning-out scenarios,
			code
				StaticText batchTriggerAndWait()
			StaticText allows you to trigger multiple task instances and wait for all results before proceeding.
			link Batch triggering docs, url='https://trigger.dev/docs/triggering#task-batchtrigger'
				image
				image
		image
		heading Automatic retries
		paragraph
			StaticText If your task encounters an uncaught error, we automatically attempt to run it again. You can combine and nest tasks, triggering them from one another, with each task maintaining its own retry behavior.
			link Retrying docs, url='https://trigger.dev/docs/errors-retrying#errors-and-retrying'
				image
				image
		image
		heading Advanced filtering
		paragraph
			StaticText Easily
			link sort and find tasks, url='https://trigger.dev/changelog/v3-run-filters'
			StaticText based on status, environment,
			link tags, url='https://trigger.dev/changelog/run-tags'
			StaticText , and creation date. You can filter from the dashboard and programmatically via the SDK using
			code
				StaticText runs.list()
			StaticText .
		image
		heading Bulk replaying
		paragraph
			StaticText Create copies of multiple runs simultaneously, using the same payload but with the latest code version in your environment. This is particularly useful for replaying failed runs or testing updates across lots of tasks.
			link Replaying docs, url='https://trigger.dev/docs/replaying#bulk-replaying'
				image
				image
		image
		heading Real-time alerts
		paragraph
			StaticText Choose your
			link preferred notification method, url='https://trigger.dev/changelog/alerts'
			StaticText – email, Slack, or webhook – to stay updated on run failures, deployment issues, or successful deployments. We attempt runs multiple times based on your retry settings and alert you if an uncaught error occurs in any run.
			link Alerts docs, url='https://trigger.dev/docs/troubleshooting-alerts#alerts'
				image
				image
		image
		heading Tag your tasks
		paragraph
			StaticText Attach up to five
			link tags, url='https://trigger.dev/changelog/run-tags'
			StaticText to each run – strings between 1 and 64 characters – to serve as powerful identifiers. Use them to filter and organize your runs through both the dashboard and SDK.
			link Tags docs, url='https://trigger.dev/docs/tags#tags'
				image
				image
		image
		heading Test your tasks
		paragraph
			StaticText You can test your tasks in every environment using the
			link test page, url='https://trigger.dev/docs/run-tests#run-tests'
			StaticText in the Trigger.dev dashboard. This allows you to make sure everything is working correctly before pushing your tasks live.
		image React
		heading React hooks
		paragraph
			StaticText Interact with the Trigger.dev API using our
			link React hooks, url='https://trigger.dev/docs/frontend/react-hooks#react-hooks'
			StaticText package. You can use these to fetch runs, batches and subscribe to real-time updates.
		image
		heading Runtime schema payloads
		paragraph
			StaticText The
			code
				StaticText schemaTask
			StaticText function allows you to define a task with a
			link runtime payload schema, url='https://trigger.dev/docs/tasks/schemaTask#schematask'
			StaticText . This validates the payload before the task is run, or when a task is triggered directly. If a task is triggered with an invalid payload, the task will fail.
		image
		heading Versioning
		paragraph
			StaticText Atomic
			link versioning, url='https://trigger.dev/docs/versioning#versioning'
			StaticText allows you to deploy new versions of your code without affecting currently running tasks.
		image
		heading Waits
		paragraph
			StaticText You can add
			link waits, url='https://trigger.dev/docs/wait#wait-overview'
			StaticText to your tasks to pause execution for a specified duration. This is useful for writing complex tasks without having to schedule them manually or poll for changes.
		image
		heading Multiple environments
		paragraph
			StaticText Trigger.dev supports
			code
				StaticText DEV
			StaticText ,
			code
				StaticText STAGING
			StaticText , and
			code
				StaticText PROD
			StaticText environments, allowing your team to test and deploy your tasks in different environments without interrupting production.
		image
		heading Build extensions
		paragraph
			link Build extensions, url='https://trigger.dev/docs/config/extensions/overview#build-extensions'
			StaticText allow you to hook into the build system and customize the build process, or the resulting bundle and container image. They can add additional files, dependencies, esbuild plugins, npm dependencies, system packages, commands and environment variables.
		heading Run metadata
		paragraph
			StaticText Attach a small amount of
			link metadata, url='https://trigger.dev/docs/runs/metadata#run-metadata'
			StaticText to a run which updates as the run progresses. This data can be accessed from inside the run function, via the API, and in the dashboard.
		heading Ready to start building?
		paragraph
			StaticText Build and deploy your first task in 3 minutes.
		link Get started now, url='https://cloud.trigger.dev/'
	contentinfo
		link Trigger.dev logo, url='https://trigger.dev/product#top'
			image Trigger.dev logo
		link Discord link, url='https://trigger.dev/discord'
			image
		link GitHub link, url='https://github.com/triggerdotdev/trigger.dev'
			image GitHub
		link X (Twitter) link, url='https://twitter.com/triggerdotdev'
			image X
		link LinkedIn link, url='https://www.linkedin.com/company/triggerdotdev'
			image
		heading Docs
		link Introduction, url='https://trigger.dev/docs/introduction'
			paragraph
		link Quick start guide, url='https://trigger.dev/docs/quick-start'
			paragraph
		link Guides & examples, url='https://trigger.dev/docs/guides/introduction'
			paragraph
				StaticText Examples
		link Creating a task, url='https://trigger.dev/docs/writing-tasks-introduction'
			paragraph
		link Triggeing a task, url='https://trigger.dev/docs/triggering'
			paragraph
				StaticText Triggering a task
		link Self hosting, url='https://trigger.dev/docs/open-source-self-hosting'
			paragraph
		heading Developers
		link Docs, url='https://trigger.dev/docs'
			paragraph
		link Changelog, url='https://trigger.dev/changelog'
			paragraph
		link Contributing, url='https://github.com/triggerdotdev/trigger.dev/blob/main/CONTRIBUTING.md'
			paragraph
		link Open source, url='https://github.com/triggerdotdev/trigger.dev?tab=Apache-2.0-1-ov-file#readme'
			paragraph
		link GitHub, url='https://github.com/triggerdotdev/trigger.dev'
			image
			paragraph
		heading Product
		link Pricing, url='https://trigger.dev/pricing'
			paragraph
		link How it works, url='https://trigger.dev/#how-it-works'
			paragraph
		link Product, url='https://trigger.dev/product'
			paragraph
				StaticText Features
		link Roadmap, url='https://feedback.trigger.dev/roadmap'
			paragraph
		link FAQs, url='https://trigger.dev/pricing#faqs'
			paragraph
		link Uptime status, url='https://status.trigger.dev/'
			paragraph
		heading Company
		link Blog, url='https://trigger.dev/blog'
			paragraph
		link Email, url='https://trigger.dev/contact'
			paragraph
				StaticText Contact
		link Blog, url='https://trigger.dev/jobs'
			paragraph
				StaticText Careers
		link Privacy policy, url='https://trigger.dev/legal/privacy'
			paragraph
		link Terms and conditions, url='https://trigger.dev/legal'
			paragraph
		link OSS friends, url='https://trigger.dev/oss-friends'
			paragraph
		Iframe Uptime status
			RootWebArea, url='https://status.trigger.dev/badge?theme=dark'
				[a4] link All services are online, center=(457,3718), url='https://status.trigger.dev/'
					image
		paragraph
			StaticText ©
			StaticText 2025
			StaticText Trigger.dev
	StaticText ,
	paragraph
		StaticText We only collect analytics cookies so we can improve your experience.
	[2023] link Privacy policy, center=(84,1037), url='https://trigger.dev/legal/privacy'
	[2027] button Opt-out, center=(209,1037), type=button
	[2030] button Accept, center=(283,1037), type=button
```
</details>

**Reasoning for action:** By clicking on the 'Features' link, I am moving closer to fulfilling the user's goal of evaluating Trigger.dev's offering. This action takes me to a page where I can gather detailed information about what Trigger.dev provides, which is essential for the user to assess whether it meets their development needs.

**Action:** click(34) # Click on 'Features' link to explore the features of Trigger.dev.

**Change Description:** After clicking the 'Features' link, the browser navigated to the 'Product' page of Trigger.dev, where the focus shifted to a new section displaying detailed features of the platform, including headings and links to various functionalities that were previously hidden.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://trigger.dev/product

https://trigger.dev/product

**Content (before/after):** 

```
RootWebArea Product | Trigger.dev, focused, url='https://trigger.dev/product'
	banner
		navigation Main
			[25] link Go to homepage, center=(327,30), url='https://trigger.dev/'
				image Trigger.dev logo
```
<details><summary>Show more</summary>

```
			list
				listitem
					[32] link How it works, center=(479,30), url='https://trigger.dev/#how-it-works'
				listitem
					[34] link Features, center=(586,29), url='https://trigger.dev/product'
						button Features, expanded=True, focused
						generic
							heading Product features
							[2091] link All features, center=(835,80), url='https://trigger.dev/product'
							[2096] link Trigger.dev Realtime Connect your frontend app to your tasks., center=(711,135), inner_text=Trigger.dev Realtime

Connect your frontend app to your tasks., url='https://trigger.dev/launchweek/0/realtime'
								image
								heading Trigger.dev Realtime
								paragraph
							[2102] link Concurrency & queues Control how many tasks run at once., center=(711,195), inner_text=Concurrency & queues

Control how many tasks run at once., url='https://trigger.dev/product/concurrency-and-queues'
								image
								heading Concurrency & queues
								paragraph
							[2108] link Scheduled tasks Durable cron schedules without timeouts., center=(711,255), inner_text=Scheduled tasks

Durable cron schedules without timeouts., url='https://trigger.dev/product/scheduled-tasks'
								image
								heading Scheduled tasks
								paragraph
							[2114] link Observability & monitoring Real-time monitoring and tracing of tasks., center=(711,315), inner_text=Observability & monitoring

Real-time monitoring and tracing of tasks., url='https://trigger.dev/product/observability-and-monitoring'
								image
								heading Observability & monitoring
								paragraph
							[2120] link Roadmap See what we're building next., center=(711,375), inner_text=Roadmap

See what we're building next., url='https://feedback.trigger.dev/roadmap'
								image
								heading Roadmap
								paragraph
								image
								image
				listitem
					[80] link Changelog, center=(686,29), url='https://trigger.dev/changelog'
						button Changelog, expanded=False
				listitem
					[113] link Blog, center=(771,29), url='https://trigger.dev/blog'
						button Blog, expanded=False
				listitem
					[146] link Docs, center=(835,29), url='https://trigger.dev/docs'
						button Docs, expanded=False
				listitem
					[255] link Pricing, center=(908,30), url='https://trigger.dev/pricing'
			list
				listitem
					[259] link Trigger.dev Discord server, center=(1320,30), url='https://trigger.dev/discord'
						image
				listitem
					[262] link Trigger.dev GitHub repo, center=(1408,30), inner_text=Star 9.8k, url='https://github.com/triggerdotdev/trigger.dev'
						image
						StaticText Star
						StaticText 9.8k
				listitem
					[267] link Login, center=(1504,30), url='https://cloud.trigger.dev/'
				listitem
					[269] link Get started, center=(1607,28), url='https://cloud.trigger.dev/'
	main
		heading Reliable background jobs without the headache of managing servers
		paragraph
			StaticText Trigger.dev has no timeouts, gives you control over concurrency, includes built-in monitoring, and scales to handle an elastic workload. You get all this and more without managing servers yourself.
		image
		heading Observability & monitoring
		image
		heading Concurrency & queues
		image
		heading Durable cron schedules
		image
		heading No infrastructure to manage
		image
		heading Advanced filtering
		image
		heading AI features
		image
		heading Automatic retries
		image
		heading Bulk replaying
		image
		heading Tag your tasks
		image
		heading Real-time alerts
		image
		heading Write normal code
		image
		heading Batch triggers
		image
		heading Long-running tasks
		image
		heading Checkpointing
		image
		heading Real-time alerts
		image
		heading Write normal code
		image
		heading Batch triggers
		image
		heading Long-running tasks
		image
		heading Checkpointing
		image
		heading Observability & monitoring
		image
		heading Concurrency & queues
		image
		heading Durable cron schedules
		image
		heading No infrastructure to manage
		image
		heading Advanced filtering
		image
		heading AI features
		image
		heading Automatic retries
		image
		heading Bulk replaying
		image
		heading Tag your tasks
		heading Feature spotlight
		[2255] link Trigger.dev Realtime Realtime is the bridge between your background tasks running on Trigger.dev and your frontend applications. It allows you to subscribe to runs and get live updates on the run status and more. Learn more, center=(654,932), inner_text=Trigger.dev Realtime

Realtime is the bridge between your background tasks running on Trigger.dev and your frontend applications. It allows you to subscribe to runs and get live updates on the run status and more.

Learn more, url='https://trigger.dev/docs/realtime/overview'
			Canvas
			heading Trigger.dev Realtime
			paragraph
			paragraph
		[2267] link Concurrency & queues Set concurrency rules to manage how multiple tasks execute. Run tasks sequentially or in parallel, and create custom queues for different users or tiers using concurrency keys. Learn more, center=(1265,932), inner_text=Concurrency & queues

Set concurrency rules to manage how multiple tasks execute. Run tasks sequentially or in parallel, and create custom queues for different users or tiers using concurrency keys.

Learn more, url='https://trigger.dev/product/concurrency-and-queues'
			Canvas
			heading Concurrency & queues
			paragraph
			paragraph
		link Durable cron schedules Create and attach recurring schedules of up to a year, which never hit a function timeout. These can be either created or attached in your codebase, or added in our dashboard. Learn more, url='https://trigger.dev/product/scheduled-tasks'
			Canvas
			heading Durable cron schedules
			paragraph
			paragraph
		link Observability & monitoring Our live run page, powered by OpenTelemetry, provides a real-time trace view of each run as it executes. This is great for viewing detailed logs of your task and debuging errors if they occur. Learn more, url='https://trigger.dev/product/observability-and-monitoring'
			Canvas
			heading Observability & monitoring
			paragraph
			paragraph
		heading Explore the full set of powerful features
		image
		heading No infrastructure to manage
		paragraph
			StaticText Your tasks are deployed and automatically scaled on Trigger.dev's long-running servers, which completely eliminates timeouts. This makes development easy without the worry of managing infrastructure.
		image
		heading Long-running tasks
		paragraph
			StaticText Trigger.dev makes it easy to run background jobs that take a long time to complete. So you can handle resource-heavy tasks like video processing, audio manipulation, PDF conversion, or large CSV processing all without timeouts.
		image
		heading AI features
		paragraph
			StaticText Trigger.dev is perfect for AI tasks that often exceed serverless timeouts, like waiting for LLM responses. Our
			link Realtime feature, url='https://trigger.dev/docs/realtime/overview'
			StaticText also lets you stream results directly to your frontend.
		image
		heading Checkpointing
		paragraph
			StaticText Tasks are inherently durable, thanks to our checkpointing feature. It allows the state of your task to be saved and resumed later, ensuring reliability. We also freeze tasks during waits meaning you only pay for task execution time.
		image
		heading Write normal code
		paragraph
			StaticText With Trigger.dev, you just write your usual async code, and it works seamlessly. No need to split your code into chunks to avoid serverless timeouts, as you deploy your tasks to our long-running servers.
			link Tasks docs, url='https://trigger.dev/docs/tasks-overview'
				image
				image
		image
		heading Batch triggering
		paragraph
			StaticText Use
			code
				StaticText batchTrigger()
			StaticText to initiate multiple runs of a task with custom payloads and options. For fanning-out scenarios,
			code
				StaticText batchTriggerAndWait()
			StaticText allows you to trigger multiple task instances and wait for all results before proceeding.
			link Batch triggering docs, url='https://trigger.dev/docs/triggering#task-batchtrigger'
				image
				image
		image
		heading Automatic retries
		paragraph
			StaticText If your task encounters an uncaught error, we automatically attempt to run it again. You can combine and nest tasks, triggering them from one another, with each task maintaining its own retry behavior.
			link Retrying docs, url='https://trigger.dev/docs/errors-retrying#errors-and-retrying'
				image
				image
		image
		heading Advanced filtering
		paragraph
			StaticText Easily
			link sort and find tasks, url='https://trigger.dev/changelog/v3-run-filters'
			StaticText based on status, environment,
			link tags, url='https://trigger.dev/changelog/run-tags'
			StaticText , and creation date. You can filter from the dashboard and programmatically via the SDK using
			code
				StaticText runs.list()
			StaticText .
		image
		heading Bulk replaying
		paragraph
			StaticText Create copies of multiple runs simultaneously, using the same payload but with the latest code version in your environment. This is particularly useful for replaying failed runs or testing updates across lots of tasks.
			link Replaying docs, url='https://trigger.dev/docs/replaying#bulk-replaying'
				image
				image
		image
		heading Real-time alerts
		paragraph
			StaticText Choose your
			link preferred notification method, url='https://trigger.dev/changelog/alerts'
			StaticText – email, Slack, or webhook – to stay updated on run failures, deployment issues, or successful deployments. We attempt runs multiple times based on your retry settings and alert you if an uncaught error occurs in any run.
			link Alerts docs, url='https://trigger.dev/docs/troubleshooting-alerts#alerts'
				image
				image
		image
		heading Tag your tasks
		paragraph
			StaticText Attach up to five
			link tags, url='https://trigger.dev/changelog/run-tags'
			StaticText to each run – strings between 1 and 64 characters – to serve as powerful identifiers. Use them to filter and organize your runs through both the dashboard and SDK.
			link Tags docs, url='https://trigger.dev/docs/tags#tags'
				image
				image
		image
		heading Test your tasks
		paragraph
			StaticText You can test your tasks in every environment using the
			link test page, url='https://trigger.dev/docs/run-tests#run-tests'
			StaticText in the Trigger.dev dashboard. This allows you to make sure everything is working correctly before pushing your tasks live.
		image React
		heading React hooks
		paragraph
			StaticText Interact with the Trigger.dev API using our
			link React hooks, url='https://trigger.dev/docs/frontend/react-hooks#react-hooks'
			StaticText package. You can use these to fetch runs, batches and subscribe to real-time updates.
		image
		heading Runtime schema payloads
		paragraph
			StaticText The
			code
				StaticText schemaTask
			StaticText function allows you to define a task with a
			link runtime payload schema, url='https://trigger.dev/docs/tasks/schemaTask#schematask'
			StaticText . This validates the payload before the task is run, or when a task is triggered directly. If a task is triggered with an invalid payload, the task will fail.
		image
		heading Versioning
		paragraph
			StaticText Atomic
			link versioning, url='https://trigger.dev/docs/versioning#versioning'
			StaticText allows you to deploy new versions of your code without affecting currently running tasks.
		image
		heading Waits
		paragraph
			StaticText You can add
			link waits, url='https://trigger.dev/docs/wait#wait-overview'
			StaticText to your tasks to pause execution for a specified duration. This is useful for writing complex tasks without having to schedule them manually or poll for changes.
		image
		heading Multiple environments
		paragraph
			StaticText Trigger.dev supports
			code
				StaticText DEV
			StaticText ,
			code
				StaticText STAGING
			StaticText , and
			code
				StaticText PROD
			StaticText environments, allowing your team to test and deploy your tasks in different environments without interrupting production.
		image
		heading Build extensions
		paragraph
			link Build extensions, url='https://trigger.dev/docs/config/extensions/overview#build-extensions'
			StaticText allow you to hook into the build system and customize the build process, or the resulting bundle and container image. They can add additional files, dependencies, esbuild plugins, npm dependencies, system packages, commands and environment variables.
		heading Run metadata
		paragraph
			StaticText Attach a small amount of
			link metadata, url='https://trigger.dev/docs/runs/metadata#run-metadata'
			StaticText to a run which updates as the run progresses. This data can be accessed from inside the run function, via the API, and in the dashboard.
		heading Ready to start building?
		paragraph
			StaticText Build and deploy your first task in 3 minutes.
		link Get started now, url='https://cloud.trigger.dev/'
	contentinfo
		link Trigger.dev logo, url='https://trigger.dev/product#top'
			image Trigger.dev logo
		link Discord link, url='https://trigger.dev/discord'
			image
		link GitHub link, url='https://github.com/triggerdotdev/trigger.dev'
			image GitHub
		link X (Twitter) link, url='https://twitter.com/triggerdotdev'
			image X
		link LinkedIn link, url='https://www.linkedin.com/company/triggerdotdev'
			image
		heading Docs
		link Introduction, url='https://trigger.dev/docs/introduction'
			paragraph
		link Quick start guide, url='https://trigger.dev/docs/quick-start'
			paragraph
		link Guides & examples, url='https://trigger.dev/docs/guides/introduction'
			paragraph
				StaticText Examples
		link Creating a task, url='https://trigger.dev/docs/writing-tasks-introduction'
			paragraph
		link Triggeing a task, url='https://trigger.dev/docs/triggering'
			paragraph
				StaticText Triggering a task
		link Self hosting, url='https://trigger.dev/docs/open-source-self-hosting'
			paragraph
		heading Developers
		link Docs, url='https://trigger.dev/docs'
			paragraph
		link Changelog, url='https://trigger.dev/changelog'
			paragraph
		link Contributing, url='https://github.com/triggerdotdev/trigger.dev/blob/main/CONTRIBUTING.md'
			paragraph
		link Open source, url='https://github.com/triggerdotdev/trigger.dev?tab=Apache-2.0-1-ov-file#readme'
			paragraph
		link GitHub, url='https://github.com/triggerdotdev/trigger.dev'
			image
			paragraph
		heading Product
		link Pricing, url='https://trigger.dev/pricing'
			paragraph
		link How it works, url='https://trigger.dev/#how-it-works'
			paragraph
		link Product, url='https://trigger.dev/product'
			paragraph
				StaticText Features
		link Roadmap, url='https://feedback.trigger.dev/roadmap'
			paragraph
		link FAQs, url='https://trigger.dev/pricing#faqs'
			paragraph
		link Uptime status, url='https://status.trigger.dev/'
			paragraph
		heading Company
		link Blog, url='https://trigger.dev/blog'
			paragraph
		link Email, url='https://trigger.dev/contact'
			paragraph
				StaticText Contact
		link Blog, url='https://trigger.dev/jobs'
			paragraph
				StaticText Careers
		link Privacy policy, url='https://trigger.dev/legal/privacy'
			paragraph
		link Terms and conditions, url='https://trigger.dev/legal'
			paragraph
		link OSS friends, url='https://trigger.dev/oss-friends'
			paragraph
		Iframe Uptime status
			RootWebArea, url='https://status.trigger.dev/badge?theme=dark'
				[a4] link All services are online, center=(457,3718), url='https://status.trigger.dev/'
					image
		paragraph
			StaticText ©
			StaticText 2025
			StaticText Trigger.dev
	StaticText ,
	paragraph
		StaticText We only collect analytics cookies so we can improve your experience.
	[2023] link Privacy policy, center=(84,1037), url='https://trigger.dev/legal/privacy'
	[2027] button Opt-out, center=(209,1037), type=button
	[2030] button Accept, center=(283,1037), type=button
```
</details>



```
RootWebArea Product | Trigger.dev, focused, url='https://trigger.dev/product'
	banner
		navigation Main
			[25] link Go to homepage, center=(327,30), url='https://trigger.dev/'
				image Trigger.dev logo
```
<details><summary>Show more</summary>

```
			list
				listitem
					[32] link How it works, center=(479,30), url='https://trigger.dev/#how-it-works'
				listitem
					[34] link Features, center=(586,29), url='https://trigger.dev/product'
						button Features, expanded=True
						generic
							heading Product features
							[2091] link All features, center=(835,80), focused, url='https://trigger.dev/product'
							[2096] link Trigger.dev Realtime Connect your frontend app to your tasks., center=(711,135), inner_text=Trigger.dev Realtime

Connect your frontend app to your tasks., url='https://trigger.dev/launchweek/0/realtime'
								image
								heading Trigger.dev Realtime
								paragraph
							[2102] link Concurrency & queues Control how many tasks run at once., center=(711,195), inner_text=Concurrency & queues

Control how many tasks run at once., url='https://trigger.dev/product/concurrency-and-queues'
								image
								heading Concurrency & queues
								paragraph
							[2108] link Scheduled tasks Durable cron schedules without timeouts., center=(711,255), inner_text=Scheduled tasks

Durable cron schedules without timeouts., url='https://trigger.dev/product/scheduled-tasks'
								image
								heading Scheduled tasks
								paragraph
							[2114] link Observability & monitoring Real-time monitoring and tracing of tasks., center=(711,315), inner_text=Observability & monitoring

Real-time monitoring and tracing of tasks., url='https://trigger.dev/product/observability-and-monitoring'
								image
								heading Observability & monitoring
								paragraph
							[2120] link Roadmap See what we're building next., center=(711,375), inner_text=Roadmap

See what we're building next., url='https://feedback.trigger.dev/roadmap'
								image
								heading Roadmap
								paragraph
								image
								image
				listitem
					[80] link Changelog, center=(686,29), url='https://trigger.dev/changelog'
						button Changelog, expanded=False
				listitem
					[113] link Blog, center=(771,29), url='https://trigger.dev/blog'
						button Blog, expanded=False
				listitem
					[146] link Docs, center=(835,29), url='https://trigger.dev/docs'
						button Docs, expanded=False
				listitem
					[255] link Pricing, center=(908,30), url='https://trigger.dev/pricing'
			list
				listitem
					[259] link Trigger.dev Discord server, center=(1320,30), url='https://trigger.dev/discord'
						image
				listitem
					[262] link Trigger.dev GitHub repo, center=(1408,30), inner_text=Star 9.8k, url='https://github.com/triggerdotdev/trigger.dev'
						image
						StaticText Star
						StaticText 9.8k
				listitem
					[267] link Login, center=(1504,30), url='https://cloud.trigger.dev/'
				listitem
					[269] link Get started, center=(1607,28), url='https://cloud.trigger.dev/'
	main
		heading Reliable background jobs without the headache of managing servers
		paragraph
			StaticText Trigger.dev has no timeouts, gives you control over concurrency, includes built-in monitoring, and scales to handle an elastic workload. You get all this and more without managing servers yourself.
		image
		heading Observability & monitoring
		image
		heading Concurrency & queues
		image
		heading Durable cron schedules
		image
		heading No infrastructure to manage
		image
		heading Advanced filtering
		image
		heading AI features
		image
		heading Automatic retries
		image
		heading Bulk replaying
		image
		heading Tag your tasks
		image
		heading Real-time alerts
		image
		heading Write normal code
		image
		heading Batch triggers
		image
		heading Long-running tasks
		image
		heading Checkpointing
		image
		heading Real-time alerts
		image
		heading Write normal code
		image
		heading Batch triggers
		image
		heading Long-running tasks
		image
		heading Checkpointing
		image
		heading Observability & monitoring
		image
		heading Concurrency & queues
		image
		heading Durable cron schedules
		image
		heading No infrastructure to manage
		image
		heading Advanced filtering
		image
		heading AI features
		image
		heading Automatic retries
		image
		heading Bulk replaying
		image
		heading Tag your tasks
		heading Feature spotlight
		[2255] link Trigger.dev Realtime Realtime is the bridge between your background tasks running on Trigger.dev and your frontend applications. It allows you to subscribe to runs and get live updates on the run status and more. Learn more, center=(654,932), inner_text=Trigger.dev Realtime

Realtime is the bridge between your background tasks running on Trigger.dev and your frontend applications. It allows you to subscribe to runs and get live updates on the run status and more.

Learn more, url='https://trigger.dev/docs/realtime/overview'
			Canvas
			heading Trigger.dev Realtime
			paragraph
			paragraph
		[2267] link Concurrency & queues Set concurrency rules to manage how multiple tasks execute. Run tasks sequentially or in parallel, and create custom queues for different users or tiers using concurrency keys. Learn more, center=(1265,932), inner_text=Concurrency & queues

Set concurrency rules to manage how multiple tasks execute. Run tasks sequentially or in parallel, and create custom queues for different users or tiers using concurrency keys.

Learn more, url='https://trigger.dev/product/concurrency-and-queues'
			Canvas
			heading Concurrency & queues
			paragraph
			paragraph
		link Durable cron schedules Create and attach recurring schedules of up to a year, which never hit a function timeout. These can be either created or attached in your codebase, or added in our dashboard. Learn more, url='https://trigger.dev/product/scheduled-tasks'
			Canvas
			heading Durable cron schedules
			paragraph
			paragraph
		link Observability & monitoring Our live run page, powered by OpenTelemetry, provides a real-time trace view of each run as it executes. This is great for viewing detailed logs of your task and debuging errors if they occur. Learn more, url='https://trigger.dev/product/observability-and-monitoring'
			Canvas
			heading Observability & monitoring
			paragraph
			paragraph
		heading Explore the full set of powerful features
		image
		heading No infrastructure to manage
		paragraph
			StaticText Your tasks are deployed and automatically scaled on Trigger.dev's long-running servers, which completely eliminates timeouts. This makes development easy without the worry of managing infrastructure.
		image
		heading Long-running tasks
		paragraph
			StaticText Trigger.dev makes it easy to run background jobs that take a long time to complete. So you can handle resource-heavy tasks like video processing, audio manipulation, PDF conversion, or large CSV processing all without timeouts.
		image
		heading AI features
		paragraph
			StaticText Trigger.dev is perfect for AI tasks that often exceed serverless timeouts, like waiting for LLM responses. Our
			link Realtime feature, url='https://trigger.dev/docs/realtime/overview'
			StaticText also lets you stream results directly to your frontend.
		image
		heading Checkpointing
		paragraph
			StaticText Tasks are inherently durable, thanks to our checkpointing feature. It allows the state of your task to be saved and resumed later, ensuring reliability. We also freeze tasks during waits meaning you only pay for task execution time.
		image
		heading Write normal code
		paragraph
			StaticText With Trigger.dev, you just write your usual async code, and it works seamlessly. No need to split your code into chunks to avoid serverless timeouts, as you deploy your tasks to our long-running servers.
			link Tasks docs, url='https://trigger.dev/docs/tasks-overview'
				image
				image
		image
		heading Batch triggering
		paragraph
			StaticText Use
			code
				StaticText batchTrigger()
			StaticText to initiate multiple runs of a task with custom payloads and options. For fanning-out scenarios,
			code
				StaticText batchTriggerAndWait()
			StaticText allows you to trigger multiple task instances and wait for all results before proceeding.
			link Batch triggering docs, url='https://trigger.dev/docs/triggering#task-batchtrigger'
				image
				image
		image
		heading Automatic retries
		paragraph
			StaticText If your task encounters an uncaught error, we automatically attempt to run it again. You can combine and nest tasks, triggering them from one another, with each task maintaining its own retry behavior.
			link Retrying docs, url='https://trigger.dev/docs/errors-retrying#errors-and-retrying'
				image
				image
		image
		heading Advanced filtering
		paragraph
			StaticText Easily
			link sort and find tasks, url='https://trigger.dev/changelog/v3-run-filters'
			StaticText based on status, environment,
			link tags, url='https://trigger.dev/changelog/run-tags'
			StaticText , and creation date. You can filter from the dashboard and programmatically via the SDK using
			code
				StaticText runs.list()
			StaticText .
		image
		heading Bulk replaying
		paragraph
			StaticText Create copies of multiple runs simultaneously, using the same payload but with the latest code version in your environment. This is particularly useful for replaying failed runs or testing updates across lots of tasks.
			link Replaying docs, url='https://trigger.dev/docs/replaying#bulk-replaying'
				image
				image
		image
		heading Real-time alerts
		paragraph
			StaticText Choose your
			link preferred notification method, url='https://trigger.dev/changelog/alerts'
			StaticText – email, Slack, or webhook – to stay updated on run failures, deployment issues, or successful deployments. We attempt runs multiple times based on your retry settings and alert you if an uncaught error occurs in any run.
			link Alerts docs, url='https://trigger.dev/docs/troubleshooting-alerts#alerts'
				image
				image
		image
		heading Tag your tasks
		paragraph
			StaticText Attach up to five
			link tags, url='https://trigger.dev/changelog/run-tags'
			StaticText to each run – strings between 1 and 64 characters – to serve as powerful identifiers. Use them to filter and organize your runs through both the dashboard and SDK.
			link Tags docs, url='https://trigger.dev/docs/tags#tags'
				image
				image
		image
		heading Test your tasks
		paragraph
			StaticText You can test your tasks in every environment using the
			link test page, url='https://trigger.dev/docs/run-tests#run-tests'
			StaticText in the Trigger.dev dashboard. This allows you to make sure everything is working correctly before pushing your tasks live.
		image React
		heading React hooks
		paragraph
			StaticText Interact with the Trigger.dev API using our
			link React hooks, url='https://trigger.dev/docs/frontend/react-hooks#react-hooks'
			StaticText package. You can use these to fetch runs, batches and subscribe to real-time updates.
		image
		heading Runtime schema payloads
		paragraph
			StaticText The
			code
				StaticText schemaTask
			StaticText function allows you to define a task with a
			link runtime payload schema, url='https://trigger.dev/docs/tasks/schemaTask#schematask'
			StaticText . This validates the payload before the task is run, or when a task is triggered directly. If a task is triggered with an invalid payload, the task will fail.
		image
		heading Versioning
		paragraph
			StaticText Atomic
			link versioning, url='https://trigger.dev/docs/versioning#versioning'
			StaticText allows you to deploy new versions of your code without affecting currently running tasks.
		image
		heading Waits
		paragraph
			StaticText You can add
			link waits, url='https://trigger.dev/docs/wait#wait-overview'
			StaticText to your tasks to pause execution for a specified duration. This is useful for writing complex tasks without having to schedule them manually or poll for changes.
		image
		heading Multiple environments
		paragraph
			StaticText Trigger.dev supports
			code
				StaticText DEV
			StaticText ,
			code
				StaticText STAGING
			StaticText , and
			code
				StaticText PROD
			StaticText environments, allowing your team to test and deploy your tasks in different environments without interrupting production.
		image
		heading Build extensions
		paragraph
			link Build extensions, url='https://trigger.dev/docs/config/extensions/overview#build-extensions'
			StaticText allow you to hook into the build system and customize the build process, or the resulting bundle and container image. They can add additional files, dependencies, esbuild plugins, npm dependencies, system packages, commands and environment variables.
		heading Run metadata
		paragraph
			StaticText Attach a small amount of
			link metadata, url='https://trigger.dev/docs/runs/metadata#run-metadata'
			StaticText to a run which updates as the run progresses. This data can be accessed from inside the run function, via the API, and in the dashboard.
		heading Ready to start building?
		paragraph
			StaticText Build and deploy your first task in 3 minutes.
		link Get started now, url='https://cloud.trigger.dev/'
	contentinfo
		link Trigger.dev logo, url='https://trigger.dev/product#top'
			image Trigger.dev logo
		link Discord link, url='https://trigger.dev/discord'
			image
		link GitHub link, url='https://github.com/triggerdotdev/trigger.dev'
			image GitHub
		link X (Twitter) link, url='https://twitter.com/triggerdotdev'
			image X
		link LinkedIn link, url='https://www.linkedin.com/company/triggerdotdev'
			image
		heading Docs
		link Introduction, url='https://trigger.dev/docs/introduction'
			paragraph
		link Quick start guide, url='https://trigger.dev/docs/quick-start'
			paragraph
		link Guides & examples, url='https://trigger.dev/docs/guides/introduction'
			paragraph
				StaticText Examples
		link Creating a task, url='https://trigger.dev/docs/writing-tasks-introduction'
			paragraph
		link Triggeing a task, url='https://trigger.dev/docs/triggering'
			paragraph
				StaticText Triggering a task
		link Self hosting, url='https://trigger.dev/docs/open-source-self-hosting'
			paragraph
		heading Developers
		link Docs, url='https://trigger.dev/docs'
			paragraph
		link Changelog, url='https://trigger.dev/changelog'
			paragraph
		link Contributing, url='https://github.com/triggerdotdev/trigger.dev/blob/main/CONTRIBUTING.md'
			paragraph
		link Open source, url='https://github.com/triggerdotdev/trigger.dev?tab=Apache-2.0-1-ov-file#readme'
			paragraph
		link GitHub, url='https://github.com/triggerdotdev/trigger.dev'
			image
			paragraph
		heading Product
		link Pricing, url='https://trigger.dev/pricing'
			paragraph
		link How it works, url='https://trigger.dev/#how-it-works'
			paragraph
		link Product, url='https://trigger.dev/product'
			paragraph
				StaticText Features
		link Roadmap, url='https://feedback.trigger.dev/roadmap'
			paragraph
		link FAQs, url='https://trigger.dev/pricing#faqs'
			paragraph
		link Uptime status, url='https://status.trigger.dev/'
			paragraph
		heading Company
		link Blog, url='https://trigger.dev/blog'
			paragraph
		link Email, url='https://trigger.dev/contact'
			paragraph
				StaticText Contact
		link Blog, url='https://trigger.dev/jobs'
			paragraph
				StaticText Careers
		link Privacy policy, url='https://trigger.dev/legal/privacy'
			paragraph
		link Terms and conditions, url='https://trigger.dev/legal'
			paragraph
		link OSS friends, url='https://trigger.dev/oss-friends'
			paragraph
		Iframe Uptime status
			RootWebArea, url='https://status.trigger.dev/badge?theme=dark'
				[a4] link All services are online, center=(457,3718), url='https://status.trigger.dev/'
					image
		paragraph
			StaticText ©
			StaticText 2025
			StaticText Trigger.dev
	StaticText ,
	paragraph
		StaticText We only collect analytics cookies so we can improve your experience.
	[2023] link Privacy policy, center=(84,1037), url='https://trigger.dev/legal/privacy'
	[2027] button Opt-out, center=(209,1037), type=button
	[2030] button Accept, center=(283,1037), type=button
```
</details>

**Reasoning for action:** I chose to click on the 'All features' link because it aligns directly with the user's goal of exploring the features of Trigger.dev. By doing this, I am ensuring that the user is taken to a comprehensive list where they can evaluate whether these features meet their development needs. This action directly fulfills the user's objective of assessing Trigger.dev's offerings.

**Action:** click(2091) # Click on 'All features' link to see a comprehensive list of all features offered by Trigger.dev.

**Change Description:** After clicking the 'All features' link, the focus shifted to this link, indicating it is currently selected, while still displaying the information about product features. The button for expanding the Features section is still active and expanded, allowing users to view all features offered by Trigger.dev.

**Screenshot before:****Screenshot after:**---

