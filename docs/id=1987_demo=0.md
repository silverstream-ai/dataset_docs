# Task

**Book a Demo User Story**

As a potential customer,
I book a demo of the Lago billing system,
so that I can explore how Lago can meet my billing and pricing needs.

**Success definition:** Given I am a potential customer on the Lago website
When I fill out the demo booking form with my business email, company website, billing needs, and sources of information about Lago, and submit it successfully
Then I should receive a confirmation that my demo request has been received and will be followed up on by the Lago team.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.getlago.com/

https://www.getlago.com/book-a-demo

**Content (before/after):** 

```
RootWebArea Lago - Open Source Metering & Usage-Based Billing, focused, url='https://www.getlago.com/'
	[45] link Lago raised a $22M funding round & serves leading tech companies. Read more, center=(960,28), url='https://www.getlago.com/blog/lago-raises-22-millions'
		paragraph
			StaticText Lago raised a $22M funding round & serves leading tech companies.
			StaticText Read more
```
<details><summary>Show more</summary>

```
	banner
		[54] link home, center=(131,92), url='https://www.getlago.com/'
			image logo-lago, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/635150a2fbcf9418736be860_lago-logo.svg'
		navigation
			[59] button Product, center=(216,92), expanded=False, hasPopup='menu'
			[125] button Developers, center=(308,92), expanded=False, hasPopup='menu'
			[153] link Pricing, center=(396,92), url='https://www.getlago.com/pricing'
			[154] link Customers, center=(483,92), url='https://www.getlago.com/customers/stories'
			[156] button Solutions, center=(578,92), expanded=False, hasPopup='menu'
			[232] button Resources, center=(672,92), expanded=False, hasPopup='menu'
			[274] link GitHub, center=(1597,92), url='https://github.com/getlago/lago'
				Iframe GitHub
					RootWebArea Star getlago/lago on GitHub, url='https://ghbtns.com/github-btn.html?user=getlago&repo=lago&type=star&count=true&size=large'
						[a8] link Star getlago/lago on GitHub, center=(1560,92), url='https://github.com/getlago/lago'
						[a11] link 7,175 stargazers on GitHub, center=(1633,92), url='https://github.com/getlago/lago/stargazers'
			[276] link Book a demo, center=(1756,92), url='https://www.getlago.com/book-a-demo'
	main
		[365] link New Lago v1.17.4 is live, center=(960,271), inner_text=New
Lago v1.17.4 is live, url='https://www.getlago.com/resources/updates'
			StaticText New
			image, url='https://cdn.prod.website-files.com/6621983722e69c894e6c6d2d/6626d2657472e899879d4838_Vectors-Wrapper.svg'
		heading Welcome to the future of billing.
		StaticText Lago offers a self-hosted and cloud, scalable and modular architecture for metering and usage-based billing, at every stage of your company.
		[375] link Book a demo, center=(848,607), url='https://www.getlago.com/book-a-demo'
		[376] link Deploy Open Source, center=(1044,607), url='https://getlago.com/docs/guide/introduction/welcome-to-lago'
		tablist, orientation='horizontal'
			[380] tab Metering, center=(451,752), selected=True
				image
			[384] tab Price plans, center=(655,752), selected=False
				image
			[388] tab Coupons, center=(858,752), selected=False
				image
			[392] tab Add-ons, center=(1062,752), selected=False
				image
			[396] tab Invoicing, center=(1266,752), selected=False
				image
			[400] tab Prepaid credits, center=(1469,752), selected=False
				image
		tabpanel Metering
			heading Real-time usage metering
			paragraph
				StaticText Ingest up to 15,000 billing events per second. Lago’s event-based architecture provides a solid foundation for building a fair pricing model that scales with your business.
			tablist, orientation='horizontal'
				tab Define your metrics, selected=True
				tab Collect usage data, selected=False
				tab Always stay informed, selected=False
			tabpanel Define your metrics
				image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/6673f8dc1fe1931850782927_metering-01.svg'
		link Learn more, url='https://getlago.com/docs/guide/introduction/welcome-to-lago'
		heading Top companies bill with Lago
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/6720e06393f594bf0fe6d86a_mistral-logo-black.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66427f40dbfe8e41e6f8b0fb_together-ai-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66bb9f478d155150c63e974e_groq-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/6720e0ccdfc42e9ffb745f09_laravel-logo-black.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66ce2fc5f808a703a232c77a_surrealdb-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66ce36f980fe236f3c6d9500_bentoml-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66bb9e80337269cc9f4164d5_moov-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66427f40dbfe8e41e6f8b0f0_swan-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66427f41dbfe8e41e6f8b14d_unifonic-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66427f40dbfe8e41e6f8b0de_juni-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66bba20b8b81f55835fa8bd9_porter-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66a2b96ef156bb0f593874bf_qonto.svg'
		heading The usage-based billing solution loved by companies around the globe
		StaticText Loved by engineers, business and finance teams.
		heading Plug-and-play metering
			strong
		paragraph
			StaticText Tired of pre-aggregating and cleaning data, so that it can be used for billing? Skip this step. Connect your data sources to Lago, as they are, and we’ll take care of the rest.
		image plug-and-play-metering, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/635fefeaf72b7e01073b58d7_plug-and-play-metering.png'
		heading Out-of-the-box billing system
			strong
		paragraph
			StaticText Our billing product includes a first-class API for engineers and a pixel-perfect user interface for business teams. Every billing piece we build, you won’t have to build yourself.
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/666c05e7524558d329205335_pricing-packaging-billing.svg'
		heading Composability and security
			strong
		paragraph
			StaticText We’re open-source, so it’s not ‘buy Lago or build it yourself’, there’s a third option: you can build on top of Lago. Audit our code and keep your data within your infrastructure, if you want full control.
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/666c06ceb68bc15962edf712_composability-security.svg'
		heading Effortless metering and usage-based billing
		StaticText Lago manages the entire process seamlessly, from metering and billing to prepayments, commitments, discounts, and invoicing.
		link Book a demo, url='https://www.getlago.com/book-a-demo'
		link Subscription fee Set up recurring platform fees billed consistently each period., url='https://www.getlago.com/#'
			image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66312e53a53351cee2b4ef72_checkbox-turnon.svg'
			image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66312ca3ff33d79be7ca0ca3_line.svg'
			StaticText Subscription fee
			StaticText Set up recurring platform fees billed consistently each period.
		link Usage-based billing Bill usage with flexible pricing: tiers, packages or custom models., url='https://www.getlago.com/#'
			image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66323383fb9270ce7f0882b7_checkbox-off.svg'
			image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66312ca3ff33d79be7ca0ca3_line.svg'
			StaticText Usage-based billing
			StaticText Bill usage with flexible pricing: tiers, packages or custom models.
		link Seat-based pricing Implement seat-based pricing, with defined cadence and proration options., url='https://www.getlago.com/#'
			image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66323383fb9270ce7f0882b7_checkbox-off.svg'
			image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66312ca3ff33d79be7ca0ca3_line.svg'
			StaticText Seat-based pricing
			StaticText Implement seat-based pricing, with defined cadence and proration options.
		link Minimum commitments Set spending minimum rules for pricing units or the entire invoice., url='https://www.getlago.com/#'
			image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66323383fb9270ce7f0882b7_checkbox-off.svg'
			image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66312ca3ff33d79be7ca0ca3_line.svg'
			StaticText Minimum commitments
			StaticText Set spending minimum rules for pricing units or the entire invoice.
		link Prepaid credits Prepay for usage with credits, and define custom top-up rules., url='https://www.getlago.com/#'
			image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66323383fb9270ce7f0882b7_checkbox-off.svg'
			image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66312ca3ff33d79be7ca0ca3_line.svg'
			StaticText Prepaid credits
			StaticText Prepay for usage with credits, and define custom top-up rules.
		link Coupons Offer percentage or price-based discounts, with custom coupon rules., url='https://www.getlago.com/#'
			image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66323383fb9270ce7f0882b7_checkbox-off.svg'
			StaticText Coupons
			StaticText Offer percentage or price-based discounts, with custom coupon rules.
		StaticText Invoice
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/6631380eb19fe2a76ef0e075_pdf-invoice-logo.svg'
		StaticText Invoice number
		StaticText BTRNW-001
		StaticText Issue date
		StaticText April 17, 2023
		StaticText From
		StaticText Lago SAS
		StaticText 6 rue des Bateliers
		StaticText 92110, Clichy
		StaticText France
		StaticText hello@getlago.com
		StaticText Bill to
		StaticText Notion Labs, Inc.
		StaticText 548 Market St #74567
		StaticText CA 94104-5401, San Francisco
		StaticText United States
		StaticText team@makenotion.com
		StaticText $
		StaticText 100
		StaticText Due April 17, 2024
		StaticText Item
		StaticText Qty
		StaticText Unit price
		StaticText Amount
		StaticText Subscription fee
		StaticText 1
		StaticText $100.00
		StaticText $100.00
		heading Don't listen to us. Listen to them.
		link, url='https://techcrunch.com/2024/03/14/lago-a-paris-based-open-source-billing-platform-banks-22m/'
			image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/6630fda6013305466bf81832_techcrunch-lago.svg'
			image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/6631029b684804d1a9b9520b_Arrow%20Up%20Right.svg'
		link “Lago has been able to follow the pace of our releases.” Timothée Lacroix Co-Founder & CTO, Mistral AI, url='https://www.getlago.com/#'
			image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/6629c584d5f211dd434208c6_mistral-ai-founder-p-500.png'
			image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/663106298f603e917f988d63_mistral-ai-logo-customer-lago.svg'
			paragraph
				StaticText “Lago has been able to follow the pace of our releases.”
			paragraph
				StaticText Timothée Lacroix
			paragraph
				StaticText Co-Founder & CTO, Mistral AI
			image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66310a522a4cff265b6a2ad1_Chevron%20right.svg'
		link “I wish Lago existed when we started Algolia.” Nicolas Dessaigne Co-Founder, Algolia, url='https://www.getlago.com/#'
			image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/6629d45a37d7c761e393ccec_nicolas-dessaigne-algolia-p-500.png'
			image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/666c1bb24e3d8e6a216bf451_algolia-logo-white.svg'
			paragraph
				StaticText “I wish Lago existed when we started Algolia.”
			paragraph
				StaticText Nicolas Dessaigne
			paragraph
				StaticText Co-Founder, Algolia
			image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66310a522a4cff265b6a2ad1_Chevron%20right.svg'
		link “Lago can help solve the long tail of challenges.” Joel Taylor Billing Engineer, Github, url='https://www.getlago.com/#'
			image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/666c1d8beb2fc5afda8452ee_5ac848df-8b0b-4af8-b827-2104737bfbf8_medium-1.jpg'
			image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/666c1bd7d294d7109287cf8c_github-logo-white.svg'
			paragraph
				StaticText “Lago can help solve the long tail of challenges.”
			paragraph
				StaticText Joel Taylor
			paragraph
				StaticText Billing Engineer, Github
			image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66310a522a4cff265b6a2ad1_Chevron%20right.svg'
		link “Lago has the strongest product for hybrid monetization streams” Nicolas Benady Co-Founder, Swan, url='https://www.getlago.com/#'
			image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/666c1d374e3d8e6a216cff7a_nicolas-benady-swan-p-800.png'
			image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/666c1d6adee7df7ba5e74b1a_swan-logo-white.svg'
			paragraph
				StaticText “Lago has the strongest product for hybrid monetization streams”
			paragraph
				StaticText Nicolas Benady
			paragraph
				StaticText Co-Founder, Swan
			image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66310a522a4cff265b6a2ad1_Chevron%20right.svg'
		link, url='https://news.ycombinator.com/item?id=31424450'
			image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/6631219d3827c1a7a7e50ae5_hacker-news-logo.svg'
			image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/6631029b684804d1a9b9520b_Arrow%20Up%20Right.svg'
		heading Connect your favorite tools to Lago
		StaticText Stop switching between apps to get work done. Keep info flowing in and out of Lago and reduce overhead with our native integrations.
		link Browse integrations, url='https://getlago.com/docs/integrations'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/663153109cad70a5b819a470_stripe.svg'
		StaticText Stripe
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66316223642eea09104f0a7e_netsuite-integration.svg'
		StaticText NetSuite
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/663162585fd3b02cc7dfa9e5_aws-marketplace-integration.svg'
		StaticText AWS Marketplace
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/663162a495ddda6e37a26437_hubspot-integration.svg'
		StaticText HubSpot
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/663162c845527b5f8b2584a2_quickbooks.svg'
		StaticText QuickBooks
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/663162f060d09660b85710e1_xero-integration.svg'
		StaticText Xero
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66316314e2451c92a693037b_salesforce-integration.svg'
		StaticText Salesforce
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66316339f486f7c2bce50c48_gocardless-integration.svg'
		StaticText GoCardless
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/663163607b41244bfd97761c_adyen-integration.svg'
		StaticText Adyen
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/663163826878cec83157aad0_anrok.svg'
		StaticText Anrok
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/663164228ddb9855ce80ac61_amazon-s3-integration.svg'
		StaticText Amazon S3
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/6631644a32c97d6d1598cbeb_snowflake-integration.svg'
		StaticText Snowflake
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66316472bd1f9397bc92e1f1_segment-integration.svg'
		StaticText Segment
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/663164b3053a54ed4cfa66b3_gcp-marketplace-integration.svg'
		StaticText GCP Marketplace
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/663164d44a6de8db12b77076_hightouch-integration.svg'
		StaticText Hightouch
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/663165070de3da0ffe7ac0b5_zapier-integration.svg'
		StaticText Zapier
		heading We ship extraordinarily fast.
		list
			listitem
				link Update 37 — Oct. 3rd, 2024 Read more, url='https://www.getlago.com/product-updates/product-update-37'
					heading Update 37 — Oct. 3rd, 2024
					StaticText Read more
					image
			listitem
				link Update #36 - Sep. 19, 2024 Update #36 - Sep. 19, 2024 Read more, url='https://www.getlago.com/product-updates/2024-09-19'
					image Update #36 - Sep. 19, 2024, url='https://cdn.prod.website-files.com/63569f390f3a7ad4c76d2bd6/66fe9f4c9b087b715774d266_Card%20news%20(1)-p-800.png'
					heading Update #36 - Sep. 19, 2024
					StaticText Read more
					image
			listitem
				link Update #35 - Sep. 4, 2024 Update #35 - Sep. 4, 2024 Read more, url='https://www.getlago.com/product-updates/2024-09-04'
					image Update #35 - Sep. 4, 2024, url='https://cdn.prod.website-files.com/63569f390f3a7ad4c76d2bd6/66fe9dd5e5c842e0b3df630e_Card%20news-p-800.png'
					heading Update #35 - Sep. 4, 2024
					StaticText Read more
					image
		link See all updates, url='https://www.getlago.com/resources/updates'
		link See public roadmap, url='https://getlago.canny.io/'
		heading Two hosting options, same benefits
		paragraph
			StaticText Whether you choose the cloud version or decide to host the solution yourself, you will benefit from our powerful API and user-friendly interface.
		image
		heading Lago Premium
		paragraph
			StaticText The optimal solution for teams with control and flexibility.
		link Book a demo, url='https://www.getlago.com/book-a-demo'
		image lago-cloud-version, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/635ba0897bec1931b9f3975c_lago-cloud-version-p-1080.png'
		image
		heading Lago Open Source
		paragraph
			StaticText The optimal solution for small projects.
		link Deploy Open Source, url='https://getlago.com/docs/'
		image lago-open-source-version, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/635ba0890ce3207f9ce4f196_lago-open-source-version-p-1080.png'
	contentinfo
		link logo-lago Open source metering and usage-based billing, url='https://www.getlago.com/'
			image logo-lago, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/635150a2fbcf9418736be860_lago-logo.svg'
			paragraph
		form Email Form
			textbox Enter your email, required
			button Subscribe
		StaticText Products
		link Usage metering, url='https://www.getlago.com/products/metering'
		link Price plans, url='https://www.getlago.com/products/plans'
		link Coupons, url='https://www.getlago.com/products/coupons'
		link Add-ons, url='https://www.getlago.com/products/add-on'
		link Invoicing, url='https://www.getlago.com/products/invoicing'
		link Instant charge, url='https://www.getlago.com/premium-features/instant-charges'
		link Customer portal, url='https://www.getlago.com/premium-features/customer-portal'
		link Spending minimums, url='https://www.getlago.com/premium-features/spending-minimum'
		link Email invoices, url='https://www.getlago.com/premium-features/email-invoices'
		link Grace periods, url='https://www.getlago.com/premium-features/grace-periods'
		link Timezones, url='https://www.getlago.com/premium-features/timezones'
		link Credit notes & Refunds, url='https://www.getlago.com/premium-features/credit-notes-refunds'
		StaticText Developers
		link GitHub, url='https://github.com/getlago/lago'
		link Documentation, url='https://getlago.com/docs'
		link API references, url='https://getlago.com/docs/api-reference'
		link Community, url='https://www.getlago.com/slack'
		link Changelog, url='https://getlago.com/docs/changelog'
		link Roadmap, url='https://getlago.canny.io/'
		StaticText Solutions
		link Engineers, url='https://www.getlago.com/solutions/teams/engineers'
		link Product managers, url='https://www.getlago.com/solutions/teams/product-managers'
		link Revenue teams, url='https://www.getlago.com/solutions/teams/revenue-teams'
		link Business operations, url='https://www.getlago.com/solutions/teams/business-operations'
		link Finance leader, url='https://www.getlago.com/solutions/teams/finance-leaders'
		link Fintech, url='https://www.getlago.com/solutions/industries/fintechs'
		link CPaaS, url='https://www.getlago.com/solutions/industries/cpaas'
		link Artificial Intelligence, url='https://www.getlago.com/solutions/industries/ai'
		link Cloud Infra, url='https://www.getlago.com/solutions/industries/cloud-infra'
		link SaaS API, url='https://www.getlago.com/solutions/industries/saas-api'
		link B2C, url='https://www.getlago.com/solutions/industries/b2c'
		link Hybrid plans, url='https://www.getlago.com/solutions/use-cases/hybrid-plans'
		link Usage based, url='https://www.getlago.com/solutions/use-cases/usage-based'
		link Enterprise, url='https://www.getlago.com/solutions/use-cases/enterprise'
		link Multi products, url='https://www.getlago.com/solutions/use-cases/multi-products'
		link Advanced, url='https://www.getlago.com/solutions/use-cases/advanced'
		StaticText Resources
		link Pricing, url='https://www.getlago.com/pricing'
		link Templates, url='https://getlago.com/docs/templates'
		link Compare, url='https://www.getlago.com/resources/compare/compare-home'
		link Product updates, url='https://www.getlago.com/resources/updates'
		link Perks, url='https://www.getlago.com/resources/perks'
		link Status, url='https://status.getlago.com/'
		link Stripe fees calculator, url='https://stripe-calculator.getlago.com/'
		link Integrations, url='https://getlago.com/docs/integrations'
		link Customer stories, url='https://www.getlago.com/customers/stories'
		StaticText Company
		link Blog, url='https://www.getlago.com/blog'
		link About us, url='https://www.getlago.com/about-us'
		link Hiring, url='https://www.getlago.com/join-us'
		link Love wall, url='https://shoutout.io/lago/'
		link Beta, url='https://www.getlago.com/beta'
		link, url='https://github.com/getlago/lago'
			image
		link, url='https://www.getlago.com/slack'
			image
		link, url='https://twitter.com/GetLago'
			image
		link, url='https://www.youtube.com/channel/UCp6ltp7n3SgDVsmerJ7O7ZA'
			image
		StaticText 2025 Lago • Designed Worldwide
		link Privacy Policy, url='https://www.getlago.com/company/privacy-policy'
		link Security, url='https://www.getlago.com/company/security'
		link Terms of Service, url='https://www.getlago.com/company/terms-of-service'
		link, url='https://www.getlago.com/company/security'
			image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/6538dbfb169ed7220c29e6b0_soc-2-macaron.svg'
```
</details>



```
RootWebArea Book a demo - Lago, focused, url='https://www.getlago.com/book-a-demo'
	banner
		[43] link home, center=(131,36), url='https://www.getlago.com/'
			image logo-lago, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/635150a2fbcf9418736be860_lago-logo.svg'
		navigation
```
<details><summary>Show more</summary>

```
			[48] button Product, center=(216,36), expanded=False, hasPopup='menu'
			[114] button Developers, center=(308,36), expanded=False, hasPopup='menu'
			[142] link Pricing, center=(396,36), url='https://www.getlago.com/pricing'
			[143] link Customers, center=(483,36), url='https://www.getlago.com/customers/stories'
			[145] button Solutions, center=(578,36), expanded=False, hasPopup='menu'
			[221] button Resources, center=(672,36), expanded=False, hasPopup='menu'
			[263] link GitHub, center=(1597,36), url='https://github.com/getlago/lago'
				Iframe GitHub
					RootWebArea Star getlago/lago on GitHub, url='https://ghbtns.com/github-btn.html?user=getlago&repo=lago&type=star&count=true&size=large'
						[a8] link Star getlago/lago on GitHub, center=(1560,36), url='https://github.com/getlago/lago'
						[a11] link 7,175 stargazers on GitHub, center=(1633,36), url='https://github.com/getlago/lago/stargazers'
			[265] link Book a demo, center=(1756,36), url='https://www.getlago.com/book-a-demo'
	main
		heading Book a demo
		paragraph
			StaticText Get in touch with our experts to automate billing and scale your revenue with Lago.
		form Webflow-Contact-sales
			LabelText
				StaticText Business email address*
			[289] textbox Business email address*, center=(632,402), contenteditable=True, required, type=email
			LabelText
				StaticText Company website*
			[292] textbox Company website*, center=(632,508), contenteditable=True, required, type=text
			LabelText
				StaticText Tell us more about your billing needs
			[295] textbox Tell us more about your billing needs, center=(632,626), contenteditable=True, required
			LabelText
				StaticText How did you hear about Lago?*
			[298] textbox How did you hear about Lago?*, center=(632,744), contenteditable=True, required, type=text
			[300] button Book a demo, center=(838,822), contenteditable=True, type=submit
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66427f40dbfe8e41e6f8b07b_mistral-ai-logo.svg'
		paragraph
			StaticText “Lago has been able to follow the pace of our releases and have allowed us to focus on what we do best.”
		StaticText Timothée Lacroix
		StaticText Co-Founder & CTO, Mistral AI
		heading Top companies bill with Lago
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/6720e06393f594bf0fe6d86a_mistral-logo-black.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66bb9f478d155150c63e974e_groq-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/6720e0a6c5efe92777b9b06c_together-logo-black.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/6720e0ccdfc42e9ffb745f09_laravel-logo-black.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66ce2fc5f808a703a232c77a_surrealdb-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66ce36f980fe236f3c6d9500_bentoml-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66bb9e80337269cc9f4164d5_moov-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66427f41dbfe8e41e6f8b14d_unifonic-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66427f40dbfe8e41e6f8b0f0_swan-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66427f40dbfe8e41e6f8b0de_juni-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66bba20b8b81f55835fa8bd9_porter-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66a2b96ef156bb0f593874bf_qonto.svg'
	contentinfo
		link logo-lago Open source metering and usage-based billing, url='https://www.getlago.com/'
			image logo-lago, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/635150a2fbcf9418736be860_lago-logo.svg'
			paragraph
		form Email Form
			textbox Enter your email, required
			button Subscribe
		StaticText Products
		link Usage metering, url='https://www.getlago.com/products/metering'
		link Price plans, url='https://www.getlago.com/products/plans'
		link Coupons, url='https://www.getlago.com/products/coupons'
		link Add-ons, url='https://www.getlago.com/products/add-on'
		link Invoicing, url='https://www.getlago.com/products/invoicing'
		link Instant charge, url='https://www.getlago.com/premium-features/instant-charges'
		link Customer portal, url='https://www.getlago.com/premium-features/customer-portal'
		link Spending minimums, url='https://www.getlago.com/premium-features/spending-minimum'
		link Email invoices, url='https://www.getlago.com/premium-features/email-invoices'
		link Grace periods, url='https://www.getlago.com/premium-features/grace-periods'
		link Timezones, url='https://www.getlago.com/premium-features/timezones'
		link Credit notes & Refunds, url='https://www.getlago.com/premium-features/credit-notes-refunds'
		StaticText Developers
		link GitHub, url='https://github.com/getlago/lago'
		link Documentation, url='https://getlago.com/docs'
		link API references, url='https://getlago.com/docs/api-reference'
		link Community, url='https://www.getlago.com/slack'
		link Changelog, url='https://getlago.com/docs/changelog'
		link Roadmap, url='https://getlago.canny.io/'
		StaticText Solutions
		link Engineers, url='https://www.getlago.com/solutions/teams/engineers'
		link Product managers, url='https://www.getlago.com/solutions/teams/product-managers'
		link Revenue teams, url='https://www.getlago.com/solutions/teams/revenue-teams'
		link Business operations, url='https://www.getlago.com/solutions/teams/business-operations'
		link Finance leader, url='https://www.getlago.com/solutions/teams/finance-leaders'
		link Fintech, url='https://www.getlago.com/solutions/industries/fintechs'
		link CPaaS, url='https://www.getlago.com/solutions/industries/cpaas'
		link Artificial Intelligence, url='https://www.getlago.com/solutions/industries/ai'
		link Cloud Infra, url='https://www.getlago.com/solutions/industries/cloud-infra'
		link SaaS API, url='https://www.getlago.com/solutions/industries/saas-api'
		link B2C, url='https://www.getlago.com/solutions/industries/b2c'
		link Hybrid plans, url='https://www.getlago.com/solutions/use-cases/hybrid-plans'
		link Usage based, url='https://www.getlago.com/solutions/use-cases/usage-based'
		link Enterprise, url='https://www.getlago.com/solutions/use-cases/enterprise'
		link Multi products, url='https://www.getlago.com/solutions/use-cases/multi-products'
		link Advanced, url='https://www.getlago.com/solutions/use-cases/advanced'
		StaticText Resources
		link Pricing, url='https://www.getlago.com/pricing'
		link Templates, url='https://getlago.com/docs/templates'
		link Compare, url='https://www.getlago.com/resources/compare/compare-home'
		link Product updates, url='https://www.getlago.com/resources/updates'
		link Perks, url='https://www.getlago.com/resources/perks'
		link Status, url='https://status.getlago.com/'
		link Stripe fees calculator, url='https://stripe-calculator.getlago.com/'
		link Integrations, url='https://getlago.com/docs/integrations'
		link Customer stories, url='https://www.getlago.com/customers/stories'
		StaticText Company
		link Blog, url='https://www.getlago.com/blog'
		link About us, url='https://www.getlago.com/about-us'
		link Hiring, url='https://www.getlago.com/join-us'
		link Love wall, url='https://shoutout.io/lago/'
		link Beta, url='https://www.getlago.com/beta'
		link, url='https://github.com/getlago/lago'
			image
		link, url='https://www.getlago.com/slack'
			image
		link, url='https://twitter.com/GetLago'
			image
		link, url='https://www.youtube.com/channel/UCp6ltp7n3SgDVsmerJ7O7ZA'
			image
		StaticText 2025 Lago • Designed Worldwide
		link Privacy Policy, url='https://www.getlago.com/company/privacy-policy'
		link Security, url='https://www.getlago.com/company/security'
		link Terms of Service, url='https://www.getlago.com/company/terms-of-service'
		link, url='https://www.getlago.com/company/security'
			image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/6538dbfb169ed7220c29e6b0_soc-2-macaron.svg'
```
</details>

**Reasoning for action:** By clicking on the 'Book a demo' link, I am navigating to the demo booking form, which is essential for completing the user's task of scheduling a demo. This action is critical as it brings me closer to fulfilling the acceptance test criteria, allowing me to provide the necessary details such as business email, company website, billing needs, and sources of information about Lago. Each step I take on this page will contribute to successfully submitting the demo request and receiving the confirmation.

**Action:** click(375) # Click on 'Book a demo' link to explore demo options.

**Change Description:** After clicking the 'Book a demo' link, the browser navigated to a new page with the heading 'Book a demo' and a form allowing users to enter details such as business email, company website, and information about their billing needs, which is distinct from the previous page that provided general information about Lago.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://www.getlago.com/book-a-demo

https://www.getlago.com/book-a-demo

**Content (before/after):** 

```
RootWebArea Book a demo - Lago, focused, url='https://www.getlago.com/book-a-demo'
	banner
		[43] link home, center=(131,36), url='https://www.getlago.com/'
			image logo-lago, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/635150a2fbcf9418736be860_lago-logo.svg'
		navigation
```
<details><summary>Show more</summary>

```
			[48] button Product, center=(216,36), expanded=False, hasPopup='menu'
			[114] button Developers, center=(308,36), expanded=False, hasPopup='menu'
			[142] link Pricing, center=(396,36), url='https://www.getlago.com/pricing'
			[143] link Customers, center=(483,36), url='https://www.getlago.com/customers/stories'
			[145] button Solutions, center=(578,36), expanded=False, hasPopup='menu'
			[221] button Resources, center=(672,36), expanded=False, hasPopup='menu'
			[263] link GitHub, center=(1597,36), url='https://github.com/getlago/lago'
				Iframe GitHub
					RootWebArea Star getlago/lago on GitHub, url='https://ghbtns.com/github-btn.html?user=getlago&repo=lago&type=star&count=true&size=large'
						[a8] link Star getlago/lago on GitHub, center=(1560,36), url='https://github.com/getlago/lago'
						[a11] link 7,175 stargazers on GitHub, center=(1633,36), url='https://github.com/getlago/lago/stargazers'
			[265] link Book a demo, center=(1756,36), url='https://www.getlago.com/book-a-demo'
	main
		heading Book a demo
		paragraph
			StaticText Get in touch with our experts to automate billing and scale your revenue with Lago.
		form Webflow-Contact-sales
			LabelText
				StaticText Business email address*
			[289] textbox Business email address*, center=(632,402), contenteditable=True, required, type=email
			LabelText
				StaticText Company website*
			[292] textbox Company website*, center=(632,508), contenteditable=True, required, type=text
			LabelText
				StaticText Tell us more about your billing needs
			[295] textbox Tell us more about your billing needs, center=(632,626), contenteditable=True, required
			LabelText
				StaticText How did you hear about Lago?*
			[298] textbox How did you hear about Lago?*, center=(632,744), contenteditable=True, required, type=text
			[300] button Book a demo, center=(838,822), contenteditable=True, type=submit
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66427f40dbfe8e41e6f8b07b_mistral-ai-logo.svg'
		paragraph
			StaticText “Lago has been able to follow the pace of our releases and have allowed us to focus on what we do best.”
		StaticText Timothée Lacroix
		StaticText Co-Founder & CTO, Mistral AI
		heading Top companies bill with Lago
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/6720e06393f594bf0fe6d86a_mistral-logo-black.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66bb9f478d155150c63e974e_groq-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/6720e0a6c5efe92777b9b06c_together-logo-black.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/6720e0ccdfc42e9ffb745f09_laravel-logo-black.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66ce2fc5f808a703a232c77a_surrealdb-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66ce36f980fe236f3c6d9500_bentoml-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66bb9e80337269cc9f4164d5_moov-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66427f41dbfe8e41e6f8b14d_unifonic-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66427f40dbfe8e41e6f8b0f0_swan-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66427f40dbfe8e41e6f8b0de_juni-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66bba20b8b81f55835fa8bd9_porter-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66a2b96ef156bb0f593874bf_qonto.svg'
	contentinfo
		link logo-lago Open source metering and usage-based billing, url='https://www.getlago.com/'
			image logo-lago, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/635150a2fbcf9418736be860_lago-logo.svg'
			paragraph
		form Email Form
			textbox Enter your email, required
			button Subscribe
		StaticText Products
		link Usage metering, url='https://www.getlago.com/products/metering'
		link Price plans, url='https://www.getlago.com/products/plans'
		link Coupons, url='https://www.getlago.com/products/coupons'
		link Add-ons, url='https://www.getlago.com/products/add-on'
		link Invoicing, url='https://www.getlago.com/products/invoicing'
		link Instant charge, url='https://www.getlago.com/premium-features/instant-charges'
		link Customer portal, url='https://www.getlago.com/premium-features/customer-portal'
		link Spending minimums, url='https://www.getlago.com/premium-features/spending-minimum'
		link Email invoices, url='https://www.getlago.com/premium-features/email-invoices'
		link Grace periods, url='https://www.getlago.com/premium-features/grace-periods'
		link Timezones, url='https://www.getlago.com/premium-features/timezones'
		link Credit notes & Refunds, url='https://www.getlago.com/premium-features/credit-notes-refunds'
		StaticText Developers
		link GitHub, url='https://github.com/getlago/lago'
		link Documentation, url='https://getlago.com/docs'
		link API references, url='https://getlago.com/docs/api-reference'
		link Community, url='https://www.getlago.com/slack'
		link Changelog, url='https://getlago.com/docs/changelog'
		link Roadmap, url='https://getlago.canny.io/'
		StaticText Solutions
		link Engineers, url='https://www.getlago.com/solutions/teams/engineers'
		link Product managers, url='https://www.getlago.com/solutions/teams/product-managers'
		link Revenue teams, url='https://www.getlago.com/solutions/teams/revenue-teams'
		link Business operations, url='https://www.getlago.com/solutions/teams/business-operations'
		link Finance leader, url='https://www.getlago.com/solutions/teams/finance-leaders'
		link Fintech, url='https://www.getlago.com/solutions/industries/fintechs'
		link CPaaS, url='https://www.getlago.com/solutions/industries/cpaas'
		link Artificial Intelligence, url='https://www.getlago.com/solutions/industries/ai'
		link Cloud Infra, url='https://www.getlago.com/solutions/industries/cloud-infra'
		link SaaS API, url='https://www.getlago.com/solutions/industries/saas-api'
		link B2C, url='https://www.getlago.com/solutions/industries/b2c'
		link Hybrid plans, url='https://www.getlago.com/solutions/use-cases/hybrid-plans'
		link Usage based, url='https://www.getlago.com/solutions/use-cases/usage-based'
		link Enterprise, url='https://www.getlago.com/solutions/use-cases/enterprise'
		link Multi products, url='https://www.getlago.com/solutions/use-cases/multi-products'
		link Advanced, url='https://www.getlago.com/solutions/use-cases/advanced'
		StaticText Resources
		link Pricing, url='https://www.getlago.com/pricing'
		link Templates, url='https://getlago.com/docs/templates'
		link Compare, url='https://www.getlago.com/resources/compare/compare-home'
		link Product updates, url='https://www.getlago.com/resources/updates'
		link Perks, url='https://www.getlago.com/resources/perks'
		link Status, url='https://status.getlago.com/'
		link Stripe fees calculator, url='https://stripe-calculator.getlago.com/'
		link Integrations, url='https://getlago.com/docs/integrations'
		link Customer stories, url='https://www.getlago.com/customers/stories'
		StaticText Company
		link Blog, url='https://www.getlago.com/blog'
		link About us, url='https://www.getlago.com/about-us'
		link Hiring, url='https://www.getlago.com/join-us'
		link Love wall, url='https://shoutout.io/lago/'
		link Beta, url='https://www.getlago.com/beta'
		link, url='https://github.com/getlago/lago'
			image
		link, url='https://www.getlago.com/slack'
			image
		link, url='https://twitter.com/GetLago'
			image
		link, url='https://www.youtube.com/channel/UCp6ltp7n3SgDVsmerJ7O7ZA'
			image
		StaticText 2025 Lago • Designed Worldwide
		link Privacy Policy, url='https://www.getlago.com/company/privacy-policy'
		link Security, url='https://www.getlago.com/company/security'
		link Terms of Service, url='https://www.getlago.com/company/terms-of-service'
		link, url='https://www.getlago.com/company/security'
			image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/6538dbfb169ed7220c29e6b0_soc-2-macaron.svg'
```
</details>



```
RootWebArea Book a demo - Lago, focused, url='https://www.getlago.com/book-a-demo'
	alert Please fill out this field., atomic
	banner
		[43] link home, center=(131,36), url='https://www.getlago.com/'
			image logo-lago, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/635150a2fbcf9418736be860_lago-logo.svg'
```
<details><summary>Show more</summary>

```
		navigation
			[48] button Product, center=(216,36), expanded=False, hasPopup='menu'
			[114] button Developers, center=(308,36), expanded=False, hasPopup='menu'
			[142] link Pricing, center=(396,36), url='https://www.getlago.com/pricing'
			[143] link Customers, center=(483,36), url='https://www.getlago.com/customers/stories'
			[145] button Solutions, center=(578,36), expanded=False, hasPopup='menu'
			[221] button Resources, center=(672,36), expanded=False, hasPopup='menu'
			[263] link GitHub, center=(1597,36), url='https://github.com/getlago/lago'
				Iframe GitHub
					RootWebArea Star getlago/lago on GitHub, url='https://ghbtns.com/github-btn.html?user=getlago&repo=lago&type=star&count=true&size=large'
						[a8] link Star getlago/lago on GitHub, center=(1560,36), url='https://github.com/getlago/lago'
						[a11] link 7,175 stargazers on GitHub, center=(1633,36), url='https://github.com/getlago/lago/stargazers'
			[265] link Book a demo, center=(1756,36), url='https://www.getlago.com/book-a-demo'
	main
		heading Book a demo
		paragraph
			StaticText Get in touch with our experts to automate billing and scale your revenue with Lago.
		form Webflow-Contact-sales
			LabelText
				StaticText Business email address*
			[289] textbox Business email address* value='gavin@hooli.com', center=(632,402), contenteditable=True, required, type=email
			LabelText
				StaticText Company website*
			[292] textbox Company website*, center=(632,508), contenteditable=True, focused, required, type=text
			LabelText
				StaticText Tell us more about your billing needs
			[295] textbox Tell us more about your billing needs, center=(632,626), contenteditable=True, required
			LabelText
				StaticText How did you hear about Lago?*
			[298] textbox How did you hear about Lago?* value='hooli.comPricing model, billing system, current issues...LinkedIn, Y Combinator, GitHub', center=(632,744), contenteditable=True, required, type=text
			[300] button Book a demo, center=(838,822), contenteditable=True, type=submit
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66427f40dbfe8e41e6f8b07b_mistral-ai-logo.svg'
		paragraph
			StaticText “Lago has been able to follow the pace of our releases and have allowed us to focus on what we do best.”
		StaticText Timothée Lacroix
		StaticText Co-Founder & CTO, Mistral AI
		heading Top companies bill with Lago
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/6720e06393f594bf0fe6d86a_mistral-logo-black.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66bb9f478d155150c63e974e_groq-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/6720e0a6c5efe92777b9b06c_together-logo-black.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/6720e0ccdfc42e9ffb745f09_laravel-logo-black.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66ce2fc5f808a703a232c77a_surrealdb-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66ce36f980fe236f3c6d9500_bentoml-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66bb9e80337269cc9f4164d5_moov-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66427f41dbfe8e41e6f8b14d_unifonic-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66427f40dbfe8e41e6f8b0f0_swan-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66427f40dbfe8e41e6f8b0de_juni-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66bba20b8b81f55835fa8bd9_porter-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66a2b96ef156bb0f593874bf_qonto.svg'
	contentinfo
		link logo-lago Open source metering and usage-based billing, url='https://www.getlago.com/'
			image logo-lago, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/635150a2fbcf9418736be860_lago-logo.svg'
			paragraph
		form Email Form
			textbox Enter your email, required
			button Subscribe
		StaticText Products
		link Usage metering, url='https://www.getlago.com/products/metering'
		link Price plans, url='https://www.getlago.com/products/plans'
		link Coupons, url='https://www.getlago.com/products/coupons'
		link Add-ons, url='https://www.getlago.com/products/add-on'
		link Invoicing, url='https://www.getlago.com/products/invoicing'
		link Instant charge, url='https://www.getlago.com/premium-features/instant-charges'
		link Customer portal, url='https://www.getlago.com/premium-features/customer-portal'
		link Spending minimums, url='https://www.getlago.com/premium-features/spending-minimum'
		link Email invoices, url='https://www.getlago.com/premium-features/email-invoices'
		link Grace periods, url='https://www.getlago.com/premium-features/grace-periods'
		link Timezones, url='https://www.getlago.com/premium-features/timezones'
		link Credit notes & Refunds, url='https://www.getlago.com/premium-features/credit-notes-refunds'
		StaticText Developers
		link GitHub, url='https://github.com/getlago/lago'
		link Documentation, url='https://getlago.com/docs'
		link API references, url='https://getlago.com/docs/api-reference'
		link Community, url='https://www.getlago.com/slack'
		link Changelog, url='https://getlago.com/docs/changelog'
		link Roadmap, url='https://getlago.canny.io/'
		StaticText Solutions
		link Engineers, url='https://www.getlago.com/solutions/teams/engineers'
		link Product managers, url='https://www.getlago.com/solutions/teams/product-managers'
		link Revenue teams, url='https://www.getlago.com/solutions/teams/revenue-teams'
		link Business operations, url='https://www.getlago.com/solutions/teams/business-operations'
		link Finance leader, url='https://www.getlago.com/solutions/teams/finance-leaders'
		link Fintech, url='https://www.getlago.com/solutions/industries/fintechs'
		link CPaaS, url='https://www.getlago.com/solutions/industries/cpaas'
		link Artificial Intelligence, url='https://www.getlago.com/solutions/industries/ai'
		link Cloud Infra, url='https://www.getlago.com/solutions/industries/cloud-infra'
		link SaaS API, url='https://www.getlago.com/solutions/industries/saas-api'
		link B2C, url='https://www.getlago.com/solutions/industries/b2c'
		link Hybrid plans, url='https://www.getlago.com/solutions/use-cases/hybrid-plans'
		link Usage based, url='https://www.getlago.com/solutions/use-cases/usage-based'
		link Enterprise, url='https://www.getlago.com/solutions/use-cases/enterprise'
		link Multi products, url='https://www.getlago.com/solutions/use-cases/multi-products'
		link Advanced, url='https://www.getlago.com/solutions/use-cases/advanced'
		StaticText Resources
		link Pricing, url='https://www.getlago.com/pricing'
		link Templates, url='https://getlago.com/docs/templates'
		link Compare, url='https://www.getlago.com/resources/compare/compare-home'
		link Product updates, url='https://www.getlago.com/resources/updates'
		link Perks, url='https://www.getlago.com/resources/perks'
		link Status, url='https://status.getlago.com/'
		link Stripe fees calculator, url='https://stripe-calculator.getlago.com/'
		link Integrations, url='https://getlago.com/docs/integrations'
		link Customer stories, url='https://www.getlago.com/customers/stories'
		StaticText Company
		link Blog, url='https://www.getlago.com/blog'
		link About us, url='https://www.getlago.com/about-us'
		link Hiring, url='https://www.getlago.com/join-us'
		link Love wall, url='https://shoutout.io/lago/'
		link Beta, url='https://www.getlago.com/beta'
		link, url='https://github.com/getlago/lago'
			image
		link, url='https://www.getlago.com/slack'
			image
		link, url='https://twitter.com/GetLago'
			image
		link, url='https://www.youtube.com/channel/UCp6ltp7n3SgDVsmerJ7O7ZA'
			image
		StaticText 2025 Lago • Designed Worldwide
		link Privacy Policy, url='https://www.getlago.com/company/privacy-policy'
		link Security, url='https://www.getlago.com/company/security'
		link Terms of Service, url='https://www.getlago.com/company/terms-of-service'
		link, url='https://www.getlago.com/company/security'
			image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/6538dbfb169ed7220c29e6b0_soc-2-macaron.svg'
```
</details>

**Reasoning for action:** Filling in the business email address is crucial because it allows Lago to contact the potential customer regarding the demo request. This step moves us closer to meeting the user's goal of booking a demo.

**Action:** fill(289, 'gavin@hooli.com') # Fill in the business email address
fill(292, 'hooli.com') # Fill in the company website
fill(295, 'Pricing model, billing system, current issues...') # Fill in billing needs
fill(298, 'LinkedIn, Y Combinator, GitHub') # Fill in how they heard about Lago
click(300) # Click on the 'Book a demo' button to submit the form.

**Change Description:** The form fields for 'Business email address' and 'How did you hear about Lago?' were successfully filled with the respective values 'gavin@hooli.com' and 'LinkedIn, Y Combinator, GitHub'. However, an alert indicates that the 'Company website' field remains empty and requires user input before the form can be submitted.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://www.getlago.com/book-a-demo

https://www.getlago.com/book-a-demo

**Content (before/after):** 

```
RootWebArea Book a demo - Lago, focused, url='https://www.getlago.com/book-a-demo'
	alert Please fill out this field., atomic
	banner
		[43] link home, center=(131,36), url='https://www.getlago.com/'
			image logo-lago, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/635150a2fbcf9418736be860_lago-logo.svg'
```
<details><summary>Show more</summary>

```
		navigation
			[48] button Product, center=(216,36), expanded=False, hasPopup='menu'
			[114] button Developers, center=(308,36), expanded=False, hasPopup='menu'
			[142] link Pricing, center=(396,36), url='https://www.getlago.com/pricing'
			[143] link Customers, center=(483,36), url='https://www.getlago.com/customers/stories'
			[145] button Solutions, center=(578,36), expanded=False, hasPopup='menu'
			[221] button Resources, center=(672,36), expanded=False, hasPopup='menu'
			[263] link GitHub, center=(1597,36), url='https://github.com/getlago/lago'
				Iframe GitHub
					RootWebArea Star getlago/lago on GitHub, url='https://ghbtns.com/github-btn.html?user=getlago&repo=lago&type=star&count=true&size=large'
						[a8] link Star getlago/lago on GitHub, center=(1560,36), url='https://github.com/getlago/lago'
						[a11] link 7,175 stargazers on GitHub, center=(1633,36), url='https://github.com/getlago/lago/stargazers'
			[265] link Book a demo, center=(1756,36), url='https://www.getlago.com/book-a-demo'
	main
		heading Book a demo
		paragraph
			StaticText Get in touch with our experts to automate billing and scale your revenue with Lago.
		form Webflow-Contact-sales
			LabelText
				StaticText Business email address*
			[289] textbox Business email address* value='gavin@hooli.com', center=(632,402), contenteditable=True, required, type=email
			LabelText
				StaticText Company website*
			[292] textbox Company website*, center=(632,508), contenteditable=True, focused, required, type=text
			LabelText
				StaticText Tell us more about your billing needs
			[295] textbox Tell us more about your billing needs, center=(632,626), contenteditable=True, required
			LabelText
				StaticText How did you hear about Lago?*
			[298] textbox How did you hear about Lago?* value='hooli.comPricing model, billing system, current issues...LinkedIn, Y Combinator, GitHub', center=(632,744), contenteditable=True, required, type=text
			[300] button Book a demo, center=(838,822), contenteditable=True, type=submit
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66427f40dbfe8e41e6f8b07b_mistral-ai-logo.svg'
		paragraph
			StaticText “Lago has been able to follow the pace of our releases and have allowed us to focus on what we do best.”
		StaticText Timothée Lacroix
		StaticText Co-Founder & CTO, Mistral AI
		heading Top companies bill with Lago
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/6720e06393f594bf0fe6d86a_mistral-logo-black.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66bb9f478d155150c63e974e_groq-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/6720e0a6c5efe92777b9b06c_together-logo-black.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/6720e0ccdfc42e9ffb745f09_laravel-logo-black.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66ce2fc5f808a703a232c77a_surrealdb-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66ce36f980fe236f3c6d9500_bentoml-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66bb9e80337269cc9f4164d5_moov-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66427f41dbfe8e41e6f8b14d_unifonic-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66427f40dbfe8e41e6f8b0f0_swan-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66427f40dbfe8e41e6f8b0de_juni-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66bba20b8b81f55835fa8bd9_porter-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66a2b96ef156bb0f593874bf_qonto.svg'
	contentinfo
		link logo-lago Open source metering and usage-based billing, url='https://www.getlago.com/'
			image logo-lago, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/635150a2fbcf9418736be860_lago-logo.svg'
			paragraph
		form Email Form
			textbox Enter your email, required
			button Subscribe
		StaticText Products
		link Usage metering, url='https://www.getlago.com/products/metering'
		link Price plans, url='https://www.getlago.com/products/plans'
		link Coupons, url='https://www.getlago.com/products/coupons'
		link Add-ons, url='https://www.getlago.com/products/add-on'
		link Invoicing, url='https://www.getlago.com/products/invoicing'
		link Instant charge, url='https://www.getlago.com/premium-features/instant-charges'
		link Customer portal, url='https://www.getlago.com/premium-features/customer-portal'
		link Spending minimums, url='https://www.getlago.com/premium-features/spending-minimum'
		link Email invoices, url='https://www.getlago.com/premium-features/email-invoices'
		link Grace periods, url='https://www.getlago.com/premium-features/grace-periods'
		link Timezones, url='https://www.getlago.com/premium-features/timezones'
		link Credit notes & Refunds, url='https://www.getlago.com/premium-features/credit-notes-refunds'
		StaticText Developers
		link GitHub, url='https://github.com/getlago/lago'
		link Documentation, url='https://getlago.com/docs'
		link API references, url='https://getlago.com/docs/api-reference'
		link Community, url='https://www.getlago.com/slack'
		link Changelog, url='https://getlago.com/docs/changelog'
		link Roadmap, url='https://getlago.canny.io/'
		StaticText Solutions
		link Engineers, url='https://www.getlago.com/solutions/teams/engineers'
		link Product managers, url='https://www.getlago.com/solutions/teams/product-managers'
		link Revenue teams, url='https://www.getlago.com/solutions/teams/revenue-teams'
		link Business operations, url='https://www.getlago.com/solutions/teams/business-operations'
		link Finance leader, url='https://www.getlago.com/solutions/teams/finance-leaders'
		link Fintech, url='https://www.getlago.com/solutions/industries/fintechs'
		link CPaaS, url='https://www.getlago.com/solutions/industries/cpaas'
		link Artificial Intelligence, url='https://www.getlago.com/solutions/industries/ai'
		link Cloud Infra, url='https://www.getlago.com/solutions/industries/cloud-infra'
		link SaaS API, url='https://www.getlago.com/solutions/industries/saas-api'
		link B2C, url='https://www.getlago.com/solutions/industries/b2c'
		link Hybrid plans, url='https://www.getlago.com/solutions/use-cases/hybrid-plans'
		link Usage based, url='https://www.getlago.com/solutions/use-cases/usage-based'
		link Enterprise, url='https://www.getlago.com/solutions/use-cases/enterprise'
		link Multi products, url='https://www.getlago.com/solutions/use-cases/multi-products'
		link Advanced, url='https://www.getlago.com/solutions/use-cases/advanced'
		StaticText Resources
		link Pricing, url='https://www.getlago.com/pricing'
		link Templates, url='https://getlago.com/docs/templates'
		link Compare, url='https://www.getlago.com/resources/compare/compare-home'
		link Product updates, url='https://www.getlago.com/resources/updates'
		link Perks, url='https://www.getlago.com/resources/perks'
		link Status, url='https://status.getlago.com/'
		link Stripe fees calculator, url='https://stripe-calculator.getlago.com/'
		link Integrations, url='https://getlago.com/docs/integrations'
		link Customer stories, url='https://www.getlago.com/customers/stories'
		StaticText Company
		link Blog, url='https://www.getlago.com/blog'
		link About us, url='https://www.getlago.com/about-us'
		link Hiring, url='https://www.getlago.com/join-us'
		link Love wall, url='https://shoutout.io/lago/'
		link Beta, url='https://www.getlago.com/beta'
		link, url='https://github.com/getlago/lago'
			image
		link, url='https://www.getlago.com/slack'
			image
		link, url='https://twitter.com/GetLago'
			image
		link, url='https://www.youtube.com/channel/UCp6ltp7n3SgDVsmerJ7O7ZA'
			image
		StaticText 2025 Lago • Designed Worldwide
		link Privacy Policy, url='https://www.getlago.com/company/privacy-policy'
		link Security, url='https://www.getlago.com/company/security'
		link Terms of Service, url='https://www.getlago.com/company/terms-of-service'
		link, url='https://www.getlago.com/company/security'
			image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/6538dbfb169ed7220c29e6b0_soc-2-macaron.svg'
```
</details>



```
RootWebArea Book a demo - Lago, focused, url='https://www.getlago.com/book-a-demo'
	banner
		[43] link home, center=(131,36), url='https://www.getlago.com/'
			image logo-lago, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/635150a2fbcf9418736be860_lago-logo.svg'
		navigation
```
<details><summary>Show more</summary>

```
			[48] button Product, center=(216,36), expanded=False, hasPopup='menu'
			[114] button Developers, center=(308,36), expanded=False, hasPopup='menu'
			[142] link Pricing, center=(396,36), url='https://www.getlago.com/pricing'
			[143] link Customers, center=(483,36), url='https://www.getlago.com/customers/stories'
			[145] button Solutions, center=(578,36), expanded=False, hasPopup='menu'
			[221] button Resources, center=(672,36), expanded=False, hasPopup='menu'
			[263] link GitHub, center=(1597,36), url='https://github.com/getlago/lago'
				Iframe GitHub
					RootWebArea Star getlago/lago on GitHub, url='https://ghbtns.com/github-btn.html?user=getlago&repo=lago&type=star&count=true&size=large'
						[a8] link Star getlago/lago on GitHub, center=(1560,36), url='https://github.com/getlago/lago'
						[a11] link 7,175 stargazers on GitHub, center=(1633,36), url='https://github.com/getlago/lago/stargazers'
			[265] link Book a demo, center=(1756,36), url='https://www.getlago.com/book-a-demo'
	main
		heading Book a demo
		paragraph
			StaticText Get in touch with our experts to automate billing and scale your revenue with Lago.
		form Webflow-Contact-sales
			LabelText
				StaticText Business email address*
			[289] textbox Business email address* value='gavin@hooli.com', center=(632,402), contenteditable=True, required, type=email
			LabelText
				StaticText Company website*
			[292] textbox Company website* value='hooli.com', center=(632,508), contenteditable=True, focused, required, type=text
			LabelText
				StaticText Tell us more about your billing needs
			[295] textbox Tell us more about your billing needs, center=(632,626), contenteditable=True, required
			LabelText
				StaticText How did you hear about Lago?*
			[298] textbox How did you hear about Lago?* value='hooli.comPricing model, billing system, current issues...LinkedIn, Y Combinator, GitHub', center=(632,744), contenteditable=True, required, type=text
			[300] button Book a demo, center=(838,822), contenteditable=True, type=submit
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66427f40dbfe8e41e6f8b07b_mistral-ai-logo.svg'
		paragraph
			StaticText “Lago has been able to follow the pace of our releases and have allowed us to focus on what we do best.”
		StaticText Timothée Lacroix
		StaticText Co-Founder & CTO, Mistral AI
		heading Top companies bill with Lago
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/6720e06393f594bf0fe6d86a_mistral-logo-black.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66bb9f478d155150c63e974e_groq-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/6720e0a6c5efe92777b9b06c_together-logo-black.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/6720e0ccdfc42e9ffb745f09_laravel-logo-black.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66ce2fc5f808a703a232c77a_surrealdb-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66ce36f980fe236f3c6d9500_bentoml-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66bb9e80337269cc9f4164d5_moov-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66427f41dbfe8e41e6f8b14d_unifonic-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66427f40dbfe8e41e6f8b0f0_swan-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66427f40dbfe8e41e6f8b0de_juni-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66bba20b8b81f55835fa8bd9_porter-logo.svg'
		image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/66a2b96ef156bb0f593874bf_qonto.svg'
	contentinfo
		link logo-lago Open source metering and usage-based billing, url='https://www.getlago.com/'
			image logo-lago, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/635150a2fbcf9418736be860_lago-logo.svg'
			paragraph
		form Email Form
			textbox Enter your email, required
			button Subscribe
		StaticText Products
		link Usage metering, url='https://www.getlago.com/products/metering'
		link Price plans, url='https://www.getlago.com/products/plans'
		link Coupons, url='https://www.getlago.com/products/coupons'
		link Add-ons, url='https://www.getlago.com/products/add-on'
		link Invoicing, url='https://www.getlago.com/products/invoicing'
		link Instant charge, url='https://www.getlago.com/premium-features/instant-charges'
		link Customer portal, url='https://www.getlago.com/premium-features/customer-portal'
		link Spending minimums, url='https://www.getlago.com/premium-features/spending-minimum'
		link Email invoices, url='https://www.getlago.com/premium-features/email-invoices'
		link Grace periods, url='https://www.getlago.com/premium-features/grace-periods'
		link Timezones, url='https://www.getlago.com/premium-features/timezones'
		link Credit notes & Refunds, url='https://www.getlago.com/premium-features/credit-notes-refunds'
		StaticText Developers
		link GitHub, url='https://github.com/getlago/lago'
		link Documentation, url='https://getlago.com/docs'
		link API references, url='https://getlago.com/docs/api-reference'
		link Community, url='https://www.getlago.com/slack'
		link Changelog, url='https://getlago.com/docs/changelog'
		link Roadmap, url='https://getlago.canny.io/'
		StaticText Solutions
		link Engineers, url='https://www.getlago.com/solutions/teams/engineers'
		link Product managers, url='https://www.getlago.com/solutions/teams/product-managers'
		link Revenue teams, url='https://www.getlago.com/solutions/teams/revenue-teams'
		link Business operations, url='https://www.getlago.com/solutions/teams/business-operations'
		link Finance leader, url='https://www.getlago.com/solutions/teams/finance-leaders'
		link Fintech, url='https://www.getlago.com/solutions/industries/fintechs'
		link CPaaS, url='https://www.getlago.com/solutions/industries/cpaas'
		link Artificial Intelligence, url='https://www.getlago.com/solutions/industries/ai'
		link Cloud Infra, url='https://www.getlago.com/solutions/industries/cloud-infra'
		link SaaS API, url='https://www.getlago.com/solutions/industries/saas-api'
		link B2C, url='https://www.getlago.com/solutions/industries/b2c'
		link Hybrid plans, url='https://www.getlago.com/solutions/use-cases/hybrid-plans'
		link Usage based, url='https://www.getlago.com/solutions/use-cases/usage-based'
		link Enterprise, url='https://www.getlago.com/solutions/use-cases/enterprise'
		link Multi products, url='https://www.getlago.com/solutions/use-cases/multi-products'
		link Advanced, url='https://www.getlago.com/solutions/use-cases/advanced'
		StaticText Resources
		link Pricing, url='https://www.getlago.com/pricing'
		link Templates, url='https://getlago.com/docs/templates'
		link Compare, url='https://www.getlago.com/resources/compare/compare-home'
		link Product updates, url='https://www.getlago.com/resources/updates'
		link Perks, url='https://www.getlago.com/resources/perks'
		link Status, url='https://status.getlago.com/'
		link Stripe fees calculator, url='https://stripe-calculator.getlago.com/'
		link Integrations, url='https://getlago.com/docs/integrations'
		link Customer stories, url='https://www.getlago.com/customers/stories'
		StaticText Company
		link Blog, url='https://www.getlago.com/blog'
		link About us, url='https://www.getlago.com/about-us'
		link Hiring, url='https://www.getlago.com/join-us'
		link Love wall, url='https://shoutout.io/lago/'
		link Beta, url='https://www.getlago.com/beta'
		link, url='https://github.com/getlago/lago'
			image
		link, url='https://www.getlago.com/slack'
			image
		link, url='https://twitter.com/GetLago'
			image
		link, url='https://www.youtube.com/channel/UCp6ltp7n3SgDVsmerJ7O7ZA'
			image
		StaticText 2025 Lago • Designed Worldwide
		link Privacy Policy, url='https://www.getlago.com/company/privacy-policy'
		link Security, url='https://www.getlago.com/company/security'
		link Terms of Service, url='https://www.getlago.com/company/terms-of-service'
		link, url='https://www.getlago.com/company/security'
			image, url='https://cdn.prod.website-files.com/635119506e36baf5c267fecd/6538dbfb169ed7220c29e6b0_soc-2-macaron.svg'
```
</details>

**Reasoning for action:** The form has several required fields, and filling in the company website is necessary to progress towards submitting it. By completing this field, I ensure that I meet the requirement for the form, which is a step closer to booking the demo.

**Action:** fill(292, 'hooli.com') # Fill in the company website to complete the form.

**Change Description:** The value of the 'Company website*' textbox was updated to 'hooli.com', indicating the successful entry of the company website in the contact form.

**Screenshot before:****Screenshot after:**---

